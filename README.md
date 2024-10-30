# Arch-audio

"Arch Linux Audio Setup Guide: Step-by-step instructions for configuring sound with PipeWire and ALSA on Arch Linux."

1. Install PipeWire Packages:

    '''bash
    $ sudo pacman -S pipewire pipewire-alsa pipewire-pulse pipewire-jack



2. Enable and start PipeWire Services


    $ systemctl --user enable pipewire.service pipewire-pulse.service
    $ systemctl --user start pipewire.service pipewire-pulse.service


3. Check your audio devices :


    $ pavucontrol


4. Test Sound


    $ speaker-test -c 2




    ******************************** HOPE IT WORKED **********************************
