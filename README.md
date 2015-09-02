### Sublime Text 2/3 Input Method (Fcitx) Fix [Ubuntu(Debian)]
Assume that you have installed sublime-text and fcitx with sogou input.

You can add following alias to `~/.bashrc` to start sublime with fix so file.

    alias st="LD_PRELOAD=/path_to/libsublime-imfix.so path_to/sublime_text"

Then you can alway start with `st` in console.

Maybe you should change the key map in sublime-text if you are using
`<ctrl-space>` to change to chinese input.

    [
      { "keys": ["ctrl+k"], "command": "set_mark" }
    ]

### Read More
http://c4fun.cn/blog/2013/11/30/linux-sublimetext-chinese/
