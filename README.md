### Sublime Text 2/3 Input Method (Fcitx) Fix [Ubuntu(Debian)]
Assume that you have installed sublime-text and fcitx with sogou input.

You can add following alias to `~/.bashrc` to start sublime with fix so file.

    alias st="LD_PRELOAD=/path_to/libsublime-imfix.so path_to/sublime_text"

Then you can alway start with `st` in console.

### Read More
http://c4fun.cn/blog/2013/11/30/linux-sublimetext-chinese/
