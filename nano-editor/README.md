# nano editor

It is one of my favorite text editor for development.

# Configuration

## MacOS

### Allow highlighting syntax in color for Nano Editor

Reference: https://stackoverflow.com/questions/9642617/nano-syntax-highlighting-in-mac-os-x-10-7-lion

1. On Mac, Homebrew `brew` will allow you to easily upgrade nano to a newer version than the one that came with Mac OSX.
   brew install nano
2. Installing this way includes the `/usr/local/share/nano` folder containing the default syntax highlight files. You can now `include "/usr/local/share/nano/c.nanorc"` in `~/.nanorc`.  
   Bonus: a run-once one-liner to add all languages.
   `/bin/ls /usr/local/share/nano/\*.nanorc | xargs -I {} echo 'include "{}"' >> ~/.nanorc`

3. Add `export PATH=/usr/local/bin:$PATH` to my `.zshrc` to get it to work

# Commands

### Go to first / last line

The first is to press 'Ctrl + \_' (underscore). This will ask for a line number at which point then press 'Ctrl + V'. This will move the cursor directly to the bottom of the file. This process is similar to the above but instead of pressing 'Ctrl + V', press 'Ctrl + Y'.

# Extensions

## General

1. git graph → Provide a graphical easier view of
2. Prettier → Tools for formatting your code upon save
3. Docker → For graphical interface of docker that runs on ur PC
4. live-server → Run a web server for previewing your html / css / js files
5. Remote - WSL → For coding in WSL environment
6. Remote - SSH → For coding in remote server
7. DotENV → For files with ‘env’ extentsons
8. Live Share → For collaborative development
9. eslint → For coding best practice
10. Material icon Theme → For having customized icons for folders and files in VS Code explorer

## Framework related

1. vue → Necessary extension for Development of Vue / Nuxt app
2. Flutter → Necessary extension for Development of Flutter app
