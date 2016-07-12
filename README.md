# Advanced Keymapping

This post collects good tools to help you take keybindings to the next level. In order to get most of this post, please read my <a href="" target="_blnk">https://github.com/yifanchen/macOS-shortcuts-collection></a> first.

### Chrome C-Vim

A good Vim Emulator for your browser. <a href="https://github.com/1995eaton/chromium-vim" target="_blank">C-Vim</a> is a must have if you use Vim, it comes with tons keybindings to reinforce the keyboard golden rule to keep your hands just on the home row of keyboards. Ambitiously, you can make your own `.cvimrc` for C-Vim.

### Karabiner

A dream tool for keymapping. <a href="https://pqrs.org/osx/karabiner" target="_blank">Karabiner</a> is the most powerful key mapping tool on this planet. It's capable of doing all sorts of crazy key mappings. It doesn't matter if you use Vim or Emacs, the options are there, preset ready for you.

#### Mapping `hjkl` with `control` as `arrow` keys

I started to use Vim last year. I absolutely like model editing and the idea of mouse-less. `hjkl` is one of the most beautiful inventions in Vim.
I wanted to apply the idea to the entire system. It turned out better than I thought. Now I use it for everything, checking out emails in Mail, browsing files in Finder,
going through lists in Slack, etc.

The screen shot is my setting. You are welcome to play with it, map any way you like. I am going to use my mapping as an example.

![Karabiner key mapping]({{ site.url }}/assets/images/karabiner-setting.jpg)

After you map it the way like I do, the beautiful part happens:

`control` + `h` + `j` + `k` + `l`: `left` `down` `up` `right`.

`control` + `cmd` + `h` or `l`: navigating through beginning and end of a line.

`control` + `cmd` + `shift` + `h` or `l`: select entire line.

`control` + `cmd` + `k` or `j`: top or bottom of the file

`control` + `cmd` + `shift` + `k` or `j`: select entire file from either top or bottom.

`control` + `j` and `control` + `k`: going through intellisense in IDE or up and down when search in Google.

`control` + `l`: very useful to attach parameters to the end of a url.

##### Example of adding a parameter to an url with both hands on row 2 of keyboard

1. `cmd` + `l`
2. `control` + `l`
3. type the parameter.

Now, you can navigate through lines of code without moving right hand to `arrow` keys.

### Seil

Same author as Karabiner, <a href="https://github.com/tekezo/Seil" target="_blank">Seil</a> made for `caps lock` key.
