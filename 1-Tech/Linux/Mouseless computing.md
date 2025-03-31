---
id: Mouseless computing
aliases: 
tags: 
created: 2025-03-09T15:25
updated: 2025-04-01T00:10
---
In the early days of computers, the main input device people used was the keyboard. Back then computers used be purely command line base, As graphical interfaces became more popular, so did mice as a intuitive way to interact with these new interfaces. However the mouse has a big flaw, it's slow to use. If you've spent a while typing on a keyboard and all of a sudden there's a button you want to click, you find yourself having to take your hand off the keyboard and move it on to the mouse. This motion is slow an inefficient. What if you could keep your hands on the keyboard to do all your tasks? Requiring very little movement to perform said tasks.

# Vim
For a while I'd been using [VScode](https://code.visualstudio.com/) until I switched to a de-microsoft version of it call [VSCodium](https://vscodium.com/). I heard about VIM from many jokes about how hard it is to exit and decided to learn what it was. 

## History
So in 1976, Bill Joy created a line editor called ex an improved version of the ed software created in 1969 by Ken Thompson. This editor could only editor one line at a time, which was ok because this is back when teletype machines (electronic type writers) were still used. However this was terrible for display monitors which didn't have the limitations as teletype. So he also made vi a visual mode for ex, the computer he developed it on did not have arrow keys so instead used h,j,k,l to move around as well as an insert mode to be able to enter h,j,k,l as characters into the file your were editing. In 1991, Bram Moolenaar created vim, an improved version of vi with more features and modes. And finally in 2015 Thiago de Arruda created [Neovim](https://neovim.io/) a fork of vim which uses Lua instead of vimscript to add extensions to the software. This is the editor I currently use. Infact, I am writing this blog post with neovim.

## Controls
In vim you move around with the keys h for left, j for down, k for up and l for right. The beauty of vim is that you can add numbers to the direction so you can type `100` then `j` to move 100 lines down or `30` then `k` to move 30 lines upgetting you to the line you want to be at way faster than using a mouse. You can use `l` to move one space to the right or you can use `w` to move one word to the right and `b` to move one word back. you can use `m` plus a letter to mark a line and use `` ` `` plus that letter to move to that mark. You can use `dd` to delete a whole line. You can use `yy` to copy a whole line. The shortcuts in this really speed coding and makes you look like a professional hacker while doing it.

## Vieb & Vimium
So I came across a program called [Vieb](https://vieb.dev/), which takes the concept of Vim and applies to a web brower. So you can stroll up and down the web page using `j` and `k` or use capital `J` and `K` to switch between tabs. You can use capital `H` to go back in your history or capital `L` to go forward in your history. You can also use the `f` key to highlight and links in a page which will all have there own set of letter and if you type those letters you can instantly click on that link. So you can brower the internet pureley with your keyboard. Now if you don't want to give up your current browser, you can install [Vimium](https://vimium.github.io/) a browser extention for Chrome, Firefox and Edge. This lets you use these same movements to navagate your current browser.

## Hyprland
So since switching to Linux, I've mainly been using [KDE plasma](https://kde.org/) as my desktop environment. It's a pretty good desktop for windows user who want to switch to linux. While plasma has a lot of keyboard shortcuts I can use, I thought a tiling window manager would suit going mouseless way more. So I decided to use Hyprland.

With a floating window manager, windows are able to be placed on top of one another. A tiling window manager however windows can only be placed next to each other like tiles. With the windows laid out like this you can use the VIM movements to go between windows.

# Better Typing
To get better at not using a mouse I had to get better at using a keyboard by learning to touch type the art of typing without looking at the keyboard. Using a site called [Typing Club](https://www.edclub.com/sportal/) to help train myself to touch type.  

## Ergonomics
Even with touch typing there are still certain keys I need to move my hands to press. I also have to keep arm in a certain position to use my keyboard. So I thought, what if I had a keyboard I could use in any position I wanted? So I decided to get a [Corne Split Keyboard](https://github.com/foostan/crkbd) from [typeractive](https://typeractive.xyz/pages/build/corne). With a nice nano to for wireless connectivity. I then purchased some [camera mount arms](https://www.amazon.co.uk/dp/B0D25VF8LF?ref=ppx_yo2ov_dt_b_fed_asin_title) and 3D printed a modifed version of the keyboard case, which I got from the corne github, to allow me to attach it to this arm with threaded inserts. This will allow me to use this keyboard in any position I wish. Either by attaching it to the arm rests on my chair or to my desk allowing me to have a standing desk. 

The Keyboard itself has taken some getting used to and I've been having troubles with the bluetooth so mainly use it over USB. But I can now use my computer in any way I wish. Though I found there are some programs that don't have a nice way of using it without a mouse. Fortunately, the keyboard is open source. So I can program a mousemode into the keyboard. Allowing me to control my mouse with a keyboard. 

# Concluion
While it requires a lot of setup and pratice. Going mouseless is pretty satisfing. Being able to perform tasks while not having to move my arms is absolute peak. It might take me a while for me to remember certain shortcuts, but regularly using them should help me learn them. The only times I think I'll still use a mouse is for tasks such as 3d Modeling and Gaming. Otherwise most task I do on my computer I can do without a mouse. 

Next I think look more into TUIs (Terminal/Text-based User Interfaces) which are programs that run in the terminal and are built purely for keyboard use. I've already started using [ranger](https://ranger.fm/) which lets me explore files from my terminal. It has made opening files into neovim way easier for me. After reading [this post](https://itsfoss.com/kew-terminal-player/#fastcomments-widget) on [it's foss](https://itsfoss.com), I think I might looking using some of these programs and see how it goes. 

For me all of this has changed how I interact with my computer. I've edited alot of config files inorder to get these programs to work how I want them. But the beauty of open source is I can completely tailor all my software to my needs and get it to function however I want it to. So overall would I say this was worth it for me? Defintely Yes. 
