
##Linux
    `git clone --recursive git@github.com:rinetd/vimfiles .vim && .vim/install.sh`

    ` git clone  git@github.com:sdlylshl/vimfiles .vim `
    ` git submodule update --init --recursive `
    
    ` ln -sf .vim/gitconfig .gitconfig `
    ` ln -sf .vim/vimrc .vimrc `
    ` ./powerline-fonts/install.sh `

    {测试未通过 禁用
    sudo chmod 766 /usr/share/fonts
    cp -r vimfile/bundle/powerline-fonts /usr/share/fonts/
    cd /usr/share/fonts/powerline-fonts
    建立字体缓存
    a. makefontscale
    b. mkdir -p $font_dir  (创建字体目录font_dir="$HOME/.fonts")
    c. eval $find_command | xargs -0 -I % cp "%" "$font_dir/"
    d. fc-cache -f $font_dir (刷新字体缓存)
    }
##Windows
