# vim-distro
Temporary vim distro for use in CS332 group project

The following commands will download vim settings and plugins in this repo, then extract to `~/.vim` and `~/.vimrc`

    $ cd ~
    $ wget --no-check-certificate https://github.com/NLKNguyen/vim-distro/raw/master/vim-distro.tar.bz2
    $ tar xvfj vim-distro.tar.bz2

**PHP**

`<F5>` Run PHP code and show the output in the preview window

`<F4>` toggle preview window

`<F9>` Run PHP code in the terminal

**MySQL**

`<F5>` Run MySQL queries in the file and show the output in the preview window

`<F4>` toggle preview window

`<F9>` Run MySQL queries in the terminal

To not having to type MySQL username and password everytime, make this file `~/.my.cnf` and store your login info inside
using the template below. MySQL will look into this file.

    [client]
    host=hostname
    user=my_username
    password=my_password

-----------------
**Some basic keys:**

`Esc` to switch to normal mode

`i` to insert mode



**In normal mode:**

[motion] keys include h, j, k, l

`Ctrl-w [motion]` jump between windows

`,1` go to tab #1, can be 1-9

``,``` open new tab

``,-`` open file browser in new tab

`,,` save the file

`:w somename.ext` write the current buffer content to somename.ext

`:q` quit current window

`:qa` quit all

`Ctr-z` put Vim to background and use the terminal. When in the terminal, `fg` to bring Vim back to foreground.

Something weird happen? just press ESC :)
