# scripts

This is a repository for random simple tools that I mostly wrote to quickly sort out a small problem or an annoyance I encountered.

* __custom\_backup__: A bash script that makes a backup of a list of files and folders to a given location using the _rsync_ tool. It is documented and has some safeguards implemented so a very basic Linux user should be able to modify it to his/her needs and use it. The only thing one has to do is change the `DEST_root` and `stuff_to_backup` variables, make the file executable, for example using: `sudo chmod +774 custom_backup`, and then run it with: `./custom_backup`.

* __srt\_sync\_tool__: A python script for basic syncing of .srt subtitle files that can shift all subtitles in time by a given amount and in order by given number (for example if there are extra subtitles, happened to me once). It is somewhat documented and will print out its proper usage when run.

* __user\_dict\_sorter__: A python script for (case insensitive) sorting of `*_user.dict` files. It annoyed me to have unsorted dictionary files of words I added while writing stuff in LaTeX. This will sort all such files in a given folder. The Script is also somewhat documented and will print out its proper usage when run.
