# Advanced Keymapping

This repo collects useful tools to help you take keybindings to the next level. In order to get most of this post, please read <a href="https://github.com/yifanchen/macOS-shortcuts-collection">Shortcuts Collection</a> first.

## Tools

### Chrome C-Vim

An excellent Vim Emulator for your browser. <a href="https://github.com/1995eaton/chromium-vim" target="_blank">C-Vim</a> is a must have if you use Vim, it comes with tons keybindings to reinforce the keyboard golden rule to keep your hands just on the home row of keyboards. Ambitiously, you can make your own `.cvimrc` for C-Vim.

Following is a couple of keybindings that I use everyday.

`gi`: goes to the first input of a page.

`f` and `F`: show marks on links, hit the marks open the page without using trackpad, cap case to open in tabs.

`H` and `L`: previous and next page.

`<` and `>`: Chrome tab movement.

`gg`: scroll to the top of the page.

`G`: scroll to the bottom of the page.

For some websites like Jira and Google Inbox, there are already built in shortcuts, with C-Vim you can whitelist them to keep the old shortcuts you like.

### Karabiner

Both Karabiner and Seil aren't compatible with Sierra yet.

A dream tool for keymapping. <a href="https://pqrs.org/osx/karabiner" target="_blank">Karabiner</a> is the most powerful key mapping tool on this planet. It's capable of doing all sorts of crazy key mappings. It doesn't matter if you use Vim or Emacs, the options are there, ready for you. Unlike Windows, on macOS number keys and letter keys don't repeat themselves, this may make cursor movement clumsy. From my experience, Karabiner is the only tool I have tried so far is capable of solving this problem.

### Seil

Same author as Karabiner, <a href="https://github.com/tekezo/Seil" target="_blank">Seil</a> made for `caps lock` key. With Seil, you can map `caps lock` key smartly.


### Keyboard Maestro

I upgraded my OS to Sierra without check the compatibility of Karabiner, so I found this Keyboard Maestro, an excellent tool to use.

## Mapping `hjkl` with `control` as `arrow` keys

I started to use Vim last year. I like model editing and the idea of mouse-less in development. `hjkl` is one of the most beautiful inventions in Vim, it makes development fun and productive. I wanted to apply the idea to the entire system. It turned out better than I thought.

As I mentioned before, `control` + `n` and `control` + `p` work as same as `down` and `up` a lot of times, but not all the times. Another key difference is that `arrow` keys repeat, but `contorl` + `n` and `control` + `p` don't. That's why I chose to use Karabiner. It helps me to map `arrow` keys with different keys, not using the unoptimized `control` + `n` or `control` + `p`.

After you map it the way like I do, the beautiful part happens:

`control` + `h` + `j` + `k` + `l`: `left` `down` `up` `right`.

`control` + `cmd` + `h` or `l`: navigating through beginning and end of a line.

`control` + `cmd` + `shift` + `h` or `l`: select entire line.

`control` + `cmd` + `k` or `j`: top or bottom of the file

`control` + `cmd` + `shift` + `k` or `j`: select entire file from either top or bottom.

`control` + `j` and `control` + `k`: going through intellisense in IDE or up and down when search in Google.

`control` + `l`: very useful to attach parameters to the end of a url.

##### Example of adding a parameter to an url with both hands on home row of keyboard

1. `cmd` + `l`
2. `control` + `l`
3. type the parameter.

or

1. `cmd` + `l`
2. `control` + `e`
3. type the parameter.

Now, you can navigate through lines of code without moving right hand to `arrow` keys.

