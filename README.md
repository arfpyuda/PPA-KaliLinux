# PPA-KaliLinux

## Now for the Actual Tutorial
If you happen to know the exact URL of your PPA, you can remove it by using the --remove flag:

- sudo add-apt-repository --remove ppa:otto-kesselgulasch/gimp

### Not that you’d ever remove GIMP! It’s an awesome photo manipulation program and it’s included in official software stores in most distros anyway.

If you don’t know or can’t remember your exact PPA location, you can browse all the files in /etc/apt/sources.list.d/

- cd /etc/apt/sources.list.d/
- ls

### Once you find the PPA you wanna trash, just run:

- sudo rm nameOfThatPPA.list

### also, if you have a .save file paired with it, just trash it as well.

- sudo rm nameOfThatPPA.save

reff :
- https://mattjones.tech/2020/01/05/how-to-remove-a-ppa-via-the-command-line/
