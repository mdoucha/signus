# Signus

Clone of Signus: the Artefact Wars. The Artefact Wars is a highly-playable turn-based strategy game with 19 long missions, lots of precisely designed units and very good AI.

## Requirements

**openSUSE**

    zypper in libSDL-devel libSDL_mixer-devel libvorbis-devel libSDL_ttf-devel

## Building

Default `autotools` installation of [signus-data](signus-data) and [signus](signus)

First build the [data](signus-data) directory

    cd signus-data
    ./bootstrap
    ./configure
    make -j4
    sudo make install

Then build [signus](signus) itself

    cd signus
    ./bootstrap
    ./configure
    make -j4
    sudo make install


Have a lot of fun!