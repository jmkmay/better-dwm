### Jonathan's dwm

This is my fork/iteration on dwm.

Patches are set in the patches folder, and contain a single patch file that was applied incrementally to produce the current state of the software.

Patches included are:
- alpha: change the alpha of dwm components (top bar and borders)
- anybar: allows for polybar to be used in place of dmenu
- attachdirection: allows you to configure the behaviour of whether new windows are treated as master/slave (current configuration is that new windows are treated as slaves)
- autostart: allows running of autostart programs (picom, nitrogen, etc.) that get hitched onto the dwm process such that if dwm closes, the programs will be terminated as well
- cfacts: allows runtime configuration of "weights" for slaves, affecting how much screen real estate a slave will use
- vanitygaps: i3-like gaps configuration with various new layouts