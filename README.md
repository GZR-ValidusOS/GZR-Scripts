FORKED from DU , CUZ I CAN !! :)

# DU Scripts #

### Build scripts ###

# To use the Nico-Build-Script

git clone this repo
https://github.com/DirtyUnicorns/DU-Scripts.git

Open up a terminal in a directory where you want to download it and copy/paste this

```bash
git clone git@github.com:DirtyUnicorns/DU-Scripts.git
```

Now with your file browser go into the DU-Scripts folder and copy the build_DU.sh file and paste it in your DU root source.

After doing that, you are ready to use the script simply by this way :

Open up a terminal or if you have the old terminal still open, in your DU root source and type this ```. build_DU.sh```

After, simply respond to what is displayed to compile the build.


# To use the Nathan-Build-Script

git clone this repo
https://github.com/DirtyUnicorns/DU-Scripts.git

cd/navigate into build-script and open Nathan-Build-Script.sh either with a text editor or in terminal using nano
and fill in the following areas

- SOURCEDIR
- OURDIR
- DESTDIR

<b>Only fill out these if you want a custom user@host in the kernel version</b>
- export KBUILD_BUILD_USER
- export KBUILD_BUILD_HOST

<b>Only fill this one out if you want something out than Dirty Deeds to show up as your build type</b>
- export DU_BUILD_TYPE
