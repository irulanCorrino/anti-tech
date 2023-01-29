#### all the stuff is broken. fuck[^1]. they declare 'Minimalism' telling base system is sufficient. no way without DE in reality
# this what has hapened to me and my laptop called amelanchier [ASUS K5OIN, Pentium T4300, Penryn]
- from my mail box ['message to myself']:
> ```
> 
> [irulan-corrino@amelanchier ~]$ caja
> (caja:2293): Gtk-WARNING **: 08:41:20.850: Could not load a pixbuf from icon theme.
> This may indicate that pixbuf loaders or the mime database could not be found.
> **
> Gtk:ERROR:../gtk/gtk/gtkiconhelper.c:494:ensure_surface_for_gicon: assertion failed (error == NULL): Failed to load /usr/share/icons/Adwaita/24x24/status/image-missing.png: Unrecognized image file format (gdk-pixbuf-error-quark, 3)
> Bail out! Gtk:ERROR:../gtk/gtk/gtkiconhelper.c:494:ensure_surface_for_gicon: assertion failed (error == NULL): Failed to load /usr/share/icons/Adwaita/24x24/status/image-missing.png: Unrecognized image file format (gdk-pixbuf-error-quark, 3)
> Aborted
> [irulan-corrino@amelanchier ~]$
>  
>  
> /home/irulan-corrino/Desktop/fstab                                                                                                            373/373               100%
> # Static information about the filesystems.
> # See fstab(5) for details.
> # <file system> <dir> <type> <options> <dump> <pass>
> # /dev/sda1 LABEL=amelanchier
> UUID=1d395df2-919f-44a5-bf9b-47d7c64cd70b       /               xfs             rw,noatime,attr2,inode64,logbufs=8,logbsize=32k,noquota 0 1
> # /dev/sda2
> UUID=b4673bfe-b1e3-4de9-8a44-1898b5344c2d       none            swap            defaults        0 0
>  
>  
> /home/irulan-corrino/Desktop/pacman.conf                                                                                                                                                                                                                                                                                                                                                                                             3414/3414              100%
> # Pacman won't upgrade packages listed in IgnorePkg and members of IgnoreGroup
> #IgnorePkg   =
> #IgnoreGroup =
> #NoUpgrade   =
> #NoExtract   =
> # Misc options
> #UseSyslog
> #Color
> #NoProgressBar
> CheckSpace
> #VerbosePkgLists
> #ParallelDownloads = 5
> # By default, pacman accepts packages signed by keys that its local keyring
> # trusts (see pacman-key and its man page), as well as unsigned packages.
> SigLevel    = Required DatabaseOptional
> LocalFileSigLevel = Optional
> #RemoteFileSigLevel = Required
> # NOTE: You must run `pacman-key --init` before first using pacman; the local
> # keyring can then be populated with the keys of all official Artix Linux
> # packagers with `pacman-key --populate artix`.
> #
> # REPOSITORIES
> #   - can be defined here or included from another file
> #   - pacman will search repositories in the order defined here
> #   - local/custom mirrors can be added here or in separate files
> #   - repositories listed first will take precedence when packages
> #     have identical names, regardless of version number
> #   - URLs will have $repo replaced by the name of the current repo
> #   - URLs will have $arch replaced by the name of the architecture
> #   
> # Repository entries are of the format:
> #       [repo-name]
> #       Server = ServerName
> #       Include = IncludePath
> #       
> # The header [repo-name] is crucial - it must be present and
> # uncommented to enable the repo.
> #
> # The gremlins repositories are disabled by default. To enable, uncomment the
> # repo name header and Include lines. You can add preferred servers immediately
> # after the header, and they will be used before the default mirrors.
> #[gremlins]
> #Include = /etc/pacman.d/mirrorlist
> [system]
> Include = /etc/pacman.d/mirrorlist
> [world]
> Include = /etc/pacman.d/mirrorlist
> #[galaxy-gremlins]
> #Include = /etc/pacman.d/mirrorlist
> [galaxy]
> Include = /etc/pacman.d/mirrorlist
> # If you want to run 32 bit applications on your x86_64 system,
> # enable the lib32 repositories as required here.
> #[lib32-gremlins]
> #Include = /etc/pacman.d/mirrorlist
> #[lib32]
> #Include = /etc/pacman.d/mirrorlist
> [universe]
> Server = https://universe.artixlinux.org/$arch
> Server = https://mirror1.artixlinux.org/universe/$arch
> Server = https://mirror.pascalpuffke.de/artix-universe/$arch
> Server = https://artixlinux.qontinuum.space/artixlinux/universe/os/$arch
> Server = https://mirror1.cl.netactuate.com/artix/universe/$arch
> Server = https://ftp.crifo.org/artix-universe/
> # Arch
> [extra]
> Include = /etc/pacman.d/mirrorlist-arch
> [community]
> Include = /etc/pacman.d/mirrorlist-arch
> [multilib]
> Include = /etc/pacman.d/mirrorlist-arch
> # An example of a custom package repository.  See the pacman manpage for
> # tips on creating your own repositories.
> #[custom]
> #SigLevel = Optional TrustAll
> #Server = file:///home/custompkgs
>  
> /home/irulan-corrino/Desktop/root bash_history                                                                                                                                                                                                                                                                                                                                                                                      11124/14654              75%
> ls /usr/share/zoneinfo/
> ls /usr/share/zoneinfo/Europe
> ln -sf /usr/share/zoneinfo/Europe/Kyiv /etc/localtime
> hwclock --systohc
> pacman -S nano
> nano /etc/locale.gen
> locale-gen
> touch /etc/locale.conf
> nano /etc/locale.conf
> pacman -S grub
> pacman -S --needed freetype2 fuse2 lzop libisoburn wpa_supplicant dhcpcd mc git ly lynx links elinks gpm gpm-openrc top neomutt
> pacman -S --needed freetype2 fuse2 lzop libisoburn wpa_supplicant dhcpcd mc git lynx links elinks gpm gpm-openrc neomutt
> pacman -S --needed freetype2 fuse2 lzop libisoburn wpa_supplicant dhcpcd mc git lynx links elinks gpm gpm-openrc neomutt notmuch offlineimap gnupg ruby alsa-utilspacman-contrib diffutils findutils plocate
> pacman -S --needed freetype2 fuse2 lzop libisoburn wpa_supplicant dhcpcd mc git lynx links elinks gpm gpm-openrc neomutt notmuch offlineimap gnupg ruby alsa-utils pacman-contrib diffutils findutils plocate
> pacman -S --needed freetype2 fuse2 lzop libisoburn wpa_supplicant dhcpcd mc git lynx links elinks gpm gpm-openrc neomutt notmuch ruby alsa-utils pacman-contrib plocate cmus moc pianobar beets  colordiff git-delta difftastic dust ncdu fdupes rmlintdmidecode hwdetect hwinfo nmon screenfetch e3 dictd sdcv bc calc
> pacman -S --needed freetype2 fuse2 lzop libisoburn wpa_supplicant dhcpcd mc git lynx links elinks gpm gpm-openrc neomutt notmuch ruby alsa-utils pacman-contrib plocate cmus colordiff ncdu rmlint dmidecode  hwinfo bc calc units task todoman twin
> pacman -S --needed freetype2 fuse2 lzop libisoburn wpa_supplicant dhcpcd mc git lynx links elinks gpm gpm-openrc neomutt notmuch ruby alsa-utils pacman-contrib plocate cmus colordiff ncdu dmidecode hwinfo bc calc
> pacman -S --needed freetype2 fuse2 lzop libisoburn wpa_supplicant dhcpcd mc git lynx links elinks gpm gpm-openrc neomutt notmuch ruby alsa-utils pacman-contrib plocate cmus colordiff ncdu dmidecode hwinfo bc calc ruby-docs gdb lldb tcc distcc distcc-openrc rustup
> grub-install --recheck /dev/sda
> grub-mkconfig -o /boot/grub/grub.cfg
> elinks
> ls
> nano ./Repositories.html
> nano /etc/pacman.conf
> nano ./Repositories.html
> nano /etc/pacman.conf
> pacman -Syu artix-archlinux-support
> pacman-key --populate archlinux
> nano /etc/pacman.conf
> pacman -S --needed rmlint units task todoman twin
> pacman -Syu --needed rmlint units task todoman twin
> pacman -S --needed moc pianobar beets git-delta difftastic dust fdupes
> passwd
> useradd -m irulan-corrino
> passwd irulan-corrino
> nano /etc/hostname
> nano /etc/hosts
> nano /etc/conf.d/hostname
> useradd -m irulan-corrino
> pacman -Qqn | pacman -S -
> pacman -Syu --needed ly grub-customizer xorg-xinput xorg jwm parcellite pacutils lostfiles pkgfile meld xorg-xinit geany geany-plugins caja
> pacman -Syu --needed man-pages texinfo intel-ucode iucode-tool cpupower hdparm acpid alsa-plugins meson smartmontools soundfonts wget artix-desktop-presets atril bash-bats bash-bats-support caja-extensions-common eom mate-terminal mate-utils pluma mate-system-monitor top bash-bats-asserts adwaita-icon-theme arc-icon-theme deepin-icon-theme elementary-icon-theme gnome-icon-theme-extras lxde-icon-theme mate-icon-theme mate-icon-theme-faenza papir
> us-icon-theme pop-icon-theme kturtle kruler github-cli mypaint xcursor-themes clementine xorg-xlsfonts gsfontstex-gyre-fonts kmag asp lshw usbvew clipgrab puredata wine gvfs gvfs-mtp gvfs-smb qjackctl gpick libgsf engrampa ttf=droid ttf-dejavu gimp blender devhelp thunderbird brave-bin mate-calc caja-admin caja-seahorse seahorse gnome-keyring openvpn openvpn-openrc acpi-openrc alsa-utils-openrc cpupower-openrc colord colord-openrc dhcpcd-openrc
>  distcc-openrc fuse-openrc git-openrc hdparm-openrc glibc-openrc openrc-settingsd  rsync rsync-openrc archivetools syslogng-openrc syslog-ng wpa_supplicant-openrc openrc-deptree2dot xsettingsd
> pacman -Syu --needed man-pages texinfo intel-ucode iucode-tool cpupower hdparm acpid alsa-plugins meson smartmontools soundfonts wget artix-desktop-presets atril bash-bats bash-bats-support caja-extensions-common eom mate-terminal mate-utils pluma mate-system-monitor bash-bats-assert  arc-icon-theme deepin-icon-theme elementary-icon-theme gnome-icon-theme-extras lxde-icon-theme mate-icon-theme mate-icon-theme-faenza papirus-icon-theme pop-icon-
> theme kturtle kruler github-cli mypaint xcursor-themes clementine xorg-xlsfonts gsfonts tex-gyre-fonts kmag asp lshw usbview clipgrab puredata wine gvfs-mtp gvfs-smb qjackctl gpick libgsf engrampa ttf-droid ttf-dejavu gimp blender devhelp thunderbird brave-bin mate-calc caja-admin caja-seahorse seahorse gnome-keyring openvpn openvpn-openrc acpid-openrc alsa-utils-openrc cpupower-openrc colord colord-openrc dhcpcd-openrc fuse-openrc git-openrc h
> dparm-openrc glibc-openrc openrc-settingsd  rsync rsync-openrc archivetools syslog-ng-openrc syslog-ng wpa_supplicant-openrc openrc-deptree2dot xsettingsd
> pacman -Syu --needed man-pages texinfo intel-ucode iucode-tool cpupower hdparm acpid alsa-plugins meson smartmontools soundfonts wget artix-desktop-presets atril bash-bats bash-bats-support caja-extensions-common eom mate-terminal mate-utils pluma mate-system-monitor bash-bats-assert  arc-icon-theme deepin-icon-theme elementary-icon-theme gnome-icon-theme-extras lxde-icon-theme mate-icon-theme mate-icon-theme-faenza papirus-icon-theme pop-icon-
> theme kturtle kruler github-cli mypaint xcursor-themes clementine xorg-xlsfonts gsfonts tex-gyre-fonts kmag asp lshw usbview clipgrab puredata wine gvfs-mtp gvfs-smb qjackctl gpick libgsf engrampa ttf-droid ttf-dejavu gimp blender devhelp thunderbird brave-bin mate-calc caja-admin caja-seahorse seahorse gnome-keyring openvpn openvpn-openrc acpid-openrc alsa-utils-openrc cpupower-openrc colord colord-openrc dhcpcd-openrc fuse-openrc git-openrc h
> dparm-openrc glibc-openrc openrc-settingsd  rsync rsync-openrc archivetools syslog-ng-openrc syslog-ng wpa_supplicant-openrc openrc-deptree2dot xsettingsd | less
> pacman -Syu --needed man-pages texinfo intel-ucode iucode-tool cpupower hdparm acpid alsa-plugins meson smartmontools soundfonts wget artix-desktop-presets atril bash-bats bash-bats-support caja-extensions-common eom mate-terminal mate-utils pluma mate-system-monitor bash-bats-assert  arc-icon-theme deepin-icon-theme elementary-icon-theme gnome-icon-theme-extras lxde-icon-theme mate-icon-theme mate-icon-theme-faenza papirus-icon-theme pop-icon-
> theme kturtle kruler github-cli mypaint xcursor-themes clementine xorg-xlsfonts gsfonts tex-gyre-fonts asp lshw usbview clipgrab puredata wine gvfs-mtp gvfs-smb qjackctl gpick libgsf engrampa ttf-droid ttf-dejavu gimp blender devhelp thunderbird brave-bin mate-calc caja-admin caja-seahorse seahorse gnome-keyring openvpn openvpn-openrc acpid-openrc alsa-utils-openrc cpupower-openrc colord colord-openrc dhcpcd-openrc fuse-openrc git-openrc hdparm
> -openrc glibc-openrc openrc-settingsd  rsync rsync-openrc archivetools syslog-ng-openrc syslog-ng wpa_supplicant-openrc openrc-deptree2dot xsettingsd
> pacman -Syu --needed man-pages intel-ucode iucode-tool cpupower hdparm acpid alsa-plugins meson smartmontools soundfonts wget artix-desktop-presets atril bash-bats bash-bats-support caja-extensions-common eom mate-terminal mate-utils pluma mate-system-monitor bash-bats-assert  arc-icon-theme deepin-icon-theme elementary-icon-theme gnome-icon-theme-extras lxde-icon-theme mate-icon-theme mate-icon-theme-faenza papirus-icon-theme pop-icon-theme kt
> urtle kmag pacmanlogviewer github-cli mypaint xcursor-themes clementine xorg-xlsfonts gsfonts tex-gyre-fonts asp lshw usbview clipgrab puredata wine gvfs-mtp gvfs-smb qjackctl gpick libgsf engrampa ttf-droid ttf-dejavu gimp blender devhelp thunderbird brave-bin mate-calc caja-admin caja-seahorse seahorse gnome-keyring openvpn openvpn-openrc acpid-openrc alsa-utils-openrc cpupower-openrc colord colord-openrc dhcpcd-openrc fuse-openrc git-openrc
> hdparm-openrc glibc-openrc openrc-settingsd  rsync rsync-openrc archivetools syslog-ng-openrc syslog-ng wpa_supplicant-openrc openrc-deptree2dot xsettingsd
> pacman -Syu --needed man-pages intel-ucode iucode-tool cpupower hdparm acpid alsa-plugins meson smartmontools soundfonts wget artix-desktop-presets atril bash-bats bash-bats-support caja-extensions-common eom mate-terminal mate-utils pluma mate-system-monitor bash-bats-assert  arc-icon-theme deepin-icon-theme elementary-icon-theme gnome-icon-theme-extras lxde-icon-theme mate-icon-theme mate-icon-theme-faenza papirus-icon-theme pop-icon-theme kt
> urtle scribus hydrogen kruler csound-plugins jacktrip csound-doc solfege lilypond vorbis-tools texlive-bin timidity++ snd wavpack speex mpg123 csoundqt pencil2d kmag pacmanlogviewer github-cli mypaint xcursor-themes clementine xorg-xlsfonts gsfonts tex-gyre-fonts asp lshw usbview clipgrab puredata wine gvfs-mtp gvfs-smb qjackctl gpick libgsf engrampa ttf-droid ttf-dejavu gimp blender devhelp thunderbird brave-bin mate-calc caja-admin caja-seaho
> rse seahorse gnome-keyring openvpn openvpn-openrc acpid-openrc alsa-utils-openrc cpupower-openrc colord colord-openrc dhcpcd-openrc fuse-openrc git-openrc hdparm-openrc glibc-openrc openrc-settingsd  rsync rsync-openrc archivetools syslog-ng-openrc syslog-ng wpa_supplicant-openrc openrc-deptree2dot xsettingsd
> pacman -Syu --needed man-pages intel-ucode iucode-tool cpupower hdparm acpid alsa-plugins meson smartmontools soundfonts wget artix-desktop-presets atril bash-bats bash-bats-support caja-extensions-common eom mate-terminal mate-utils pluma mate-system-monitor bash-bats-assert  arc-icon-theme deepin-icon-theme elementary-icon-theme gnome-icon-theme-extras lxde-icon-theme mate-icon-theme mate-icon-theme-faenza papirus-icon-theme pop-icon-theme kt
> urtle scribus hydrogen kruler jacktrip csound-doc solfege lilypond vorbis-tools texlive-bin timidity++ snd wavpack speex mpg123 csoundqt pencil2d kmag pacmanlogviewer github-cli mypaint xcursor-themes clementine xorg-xlsfonts gsfonts tex-gyre-fonts asp lshw usbview clipgrab puredata wine gvfs-mtp gvfs-smb qjackctl gpick libgsf engrampa ttf-droid ttf-dejavu gimp blender devhelp thunderbird brave-bin mate-calc caja-admin caja-seahorse seahorse gn
> ome-keyring openvpn openvpn-openrc acpid-openrc alsa-utils-openrc cpupower-openrc colord colord-openrc dhcpcd-openrc fuse-openrc git-openrc hdparm-openrc glibc-openrc openrc-settingsd  rsync rsync-openrc archivetools syslog-ng-openrc syslog-ng wpa_supplicant-openrc openrc-deptree2dot xsettingsd
> pacman -Spacman -Rns jacktrip
> pacman -Rns jacktrip
> pacman -S foot swappy imv wayst screenkey
> pacman -S foot swappy imv screenkey
> ls /boot
> grub-mkconfig -o /boot/grub/grub.cfg
> pacman -q linux-firmware
> pacman -Q linux-firmware
> pacman -Q nouveau
> pacman -Qi mesa xf86-video-nouveau lib32-mesa
> nano /etc/pacman.conf
> pacman -Si xf86-video-nouveau
> pacman -Syu xf86-video-nouveau
> pacman -Qi mesa lib32-mesa
> pacman -S mesa-vdpau libva-mesa-driver lib32-mesa-vdpau lib32-libva-mesa-driver
> pacman -Qi xf86-video-nouveau
> pacman -Qi xrandr
> pacman -S xrandr
> nano /boot/grub/grub.cfg
> exit
> man xprop
> man xwininfo
> man xfontsel
> man xterm
> man xclock
> pacman -Qi xclock
> man brave
> man brave-bin
> info brave-bin
> info brave
> pacman -Qi brave-bin
> pacman -Qi compton
> pacman -Si compton
>  
>  
> /home/irulan-corrino/
>  
> /home/irulan-corrino/Desktop/root bash_history                                                                                                                                                                                                                                                                      12637/14654              86%
> man brave-bin
> info brave-bin
> info brave
> pacman -Qi brave-bin
> pacman -Qi compton
> pacman -Si compton
> man compton
> ls /usr/share/icons
> mc
> exit
> adduser irulan-corrino sudo
> visudo
> EDITOR=nano visudo
> groups irulan-corrino
> cat /etc/group
> cat /etc/group | less
> groupadd sudo
> usermod -aG sudo irulan-corrino
> nano /etc/wpa_supplicant/wpa_supplicant.conf
> rc-update show -v
> rc-update show -v | less
> rc-update status s6-svscan
> rc-status s6-svscan
> rc-status -s
> rc-status -s | less
> nano ~/.asoundrc
> rc-status -s | less
> ls /var/lib/alsa/asound.state
> ls /var/lib/alsa/
> alsamixer
> alsamixer
> alsamixer
> rc-status -s | less
> rc-update show -v | less
> nano /etc/system.jwm
> nano /etc/system.jwmrc
> exit
> find / -name system.jwmrc -type f -print
> find / -name .jwmrc -type f -print
> find / -name ".jwmrc" -type f -print
> nano /etc/system.jwmrc
> exit
>  pacman -Syu openconnect gtk-engines gtk-engine-murrine
> exit
> rc-update add dhcpcd default
> rc-service dhcpcd start
> rc-update add wpa_supplicant default
> rc-service wpa_supplicant start
> rc-service wpa_supplicant start
> wpa_cli
> ping artixlinux.org
> rc-update add alsasound default
> rc-service alsasound start
> rc-status
> rc-service alsasound restart
> beep
> bell
> rc-update del alsasound default
> rc-update add alsasound boot
> rc-service alsasound start
> /etc/init.d/acpid start
> rc-update add acpid default
> startx /usr/bin/jwm
> mc
> nano
> find .jwmrc
> find system.jwmrc
> man finfd
> man find
> shutdown now
> pacman -Syu
> ly -h
> man ly
> startx /usr/bin/jwm
> mc
> pacman -Syu
> pacman -Qi lib32-ncurses
> pacman -Qi libtiff
> pacman -Qi gdk-pixbuf2
> pacman -Qi lib32-libpcap
> pacman -Qi libpcap
> pacman -Qi lib32-ncurses
> pacman -Qi ncurses
>  1Help                            2UnWrap                          3Quit                             4Hex                              5Goto                             6                                7Search                          8Raw                              9Format                          10Quit
>  
>  
> Desktop/root bash_history                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      14654/14654             100%
> mc
> pacman -Syu
> pacman -Qi lib32-ncurses
> pacman -Qi libtiff
> pacman -Qi gdk-pixbuf2
> pacman -Qi lib32-libpcap
> pacman -Qi libpcap
> pacman -Qi lib32-ncurses
> pacman -Qi ncurses
> pacman -Syu lib32-ncurses ncurses
> pacman -Syu gdk-pixbuf2 libtiff
> pacman -Syu gdk-pixbuf2 libtiff lib32-libtiff
> pacman -S libtiff lib32-libtiff
> loginctl poweroff
> pacman -Syu
> loginctl poweroff
> pacman -Syu
> loginctl poweroff
> mc
> pacman -Syu
> pacman -Qi links2
> pacman -Si links2
> pacman -Qi lynx
> pacman -Qi w3m
> pacman -Si links
> pacman -Qi links
> pacman -S ungoogled-chromium
> pacman -S librewolf
> pacman -Qi librewolf
> pacman -Si tor-browser
> pacman -Si firefox
> pacman -S tor-browser
> pacman -S w3m
> pacman -Qi w3m
> pacman -S imlib2
> pacman -Rns tor-browser
> pacman -Qi sqlite
> loginctl poweroff
> pacman -Rns brave-bin
> pacman -Syu firefox-esr seamonkey
> grub-install --recheck /dev/sda
> grub-mkconfig -o /boot/grub/grub.cfg
> pacman -S  hunspell-en_US
> exit
> pacman -Rns hydrogen
> pacman -Syu
> grub-install --recheck /dev/sda
> grub-mkconfig -o /boot/grub/grub.cfg
> exit
> 
> /* ______________________- non-root bash -__________________________*/
> ping artixlinux.org
> shutdown -R now
> sudo shutdown -R now
> sudo su
> visudo
> aplay -L
> aplay -L | less
> cat /sys/class/sound/card*/id
> sudo su
> exit
> sudo su
> exit
> cmus
> brave
> brave
> sudo su
> exit
>  pacman -Si openconnect
> sudo su
> startx /usr/binjwm
> startx /usr/bin/jwm
> sudosu
> sudo su
> startx /usr/bin/jwm
> shutdown now
> sudo top
> loginctl --shutdown
> loginctl --help
> loginctl --poweroff
> loginctl poweroff
> startx /usr/bin/ly
> caja-admin
> pacma Si caja-admin
> pacman Si caja-admin
> pacman -Si caja-admin
> pacman -Qi caja-admin
> pacman -Qi mate-terminal
> man caja-admin
> caja-admin --help
> pacman -Si thunar
> pacman -Si tumbler
> pacman -Si libxfce4util
> pacman -Si libxfce4ui
> exit
> sudo caja
> exit
> ly -h
> startx /usr/bin/jwm
> loginctl --help
> sudo su
> sudo su
> sudo su
> sudo su
> pacman -Qi ungoogled-chromium
> ungoogled-chromium
> pacman -Qi pulseaudio
> chromium
> tor-browser
> librewolf
> exit
> links
> lynx
> lynx
> mc
> elinks
> startx /usr/bin/jwm
> sudo su
> pacman -Qi libpulse
> pacman -Qi thunderbird
> sudo su
> exit
> sudo caja
> startx /usr/bin/jwm
>  
> 
> /* ______________________-wpa-cli history-__________________________*/
> add_network
> enable_network 0
> save_config
> quit
>  
> /home/irulan-corrino/Desktop/root bash_history                                                                                                                                                                                                                                                                      12637/14654              86%
> man brave-bin
> info brave-bin
> info brave
> pacman -Qi brave-bin
> pacman -Qi compton
> pacman -Si compton
> man compton
> ls /usr/share/icons
> mc
> exit
> adduser irulan-corrino sudo
> visudo
> EDITOR=nano visudo
> groups irulan-corrino
> cat /etc/group
> cat /etc/group | less
> groupadd sudo
> usermod -aG sudo irulan-corrino
> nano /etc/wpa_supplicant/wpa_supplicant.conf
> rc-update show -v
> rc-update show -v | less
> rc-update status s6-svscan
> rc-status s6-svscan
> rc-status -s
> rc-status -s | less
> nano ~/.asoundrc
> rc-status -s | less
> ls /var/lib/alsa/asound.state
> ls /var/lib/alsa/
> alsamixer
> alsamixer
> alsamixer
> rc-status -s | less
> rc-update show -v | less
> nano /etc/system.jwm
> nano /etc/system.jwmrc
> exit
> find / -name system.jwmrc -type f -print
> find / -name .jwmrc -type f -print
> find / -name ".jwmrc" -type f -print
> nano /etc/system.jwmrc
> exit
>  pacman -Syu openconnect gtk-engines gtk-engine-murrine
> exit
> rc-update add dhcpcd default
> rc-service dhcpcd start
> rc-update add wpa_supplicant default
> rc-service wpa_supplicant start
> rc-service wpa_supplicant start
> wpa_cli
> ping artixlinux.org
> rc-update add alsasound default
> rc-service alsasound start
> rc-status
> rc-service alsasound restart
> beep
> bell
> rc-update del alsasound default
> rc-update add alsasound boot
> rc-service alsasound start
> /etc/init.d/acpid start
> rc-update add acpid default
> startx /usr/bin/jwm
> mc
> nano
> find .jwmrc
> find system.jwmrc
> man finfd
> man find
> shutdown now
> pacman -Syu
> ly -h
> man ly
> startx /usr/bin/jwm
> mc
> pacman -Syu
> pacman -Qi lib32-ncurses
> pacman -Qi libtiff
> pacman -Qi gdk-pixbuf2
> pacman -Qi lib32-libpcap
> pacman -Qi libpcap
> pacman -Qi lib32-ncurses
> pacman -Qi ncurses
>  
>  
>  
>  
>  
>  
> /home/irulan-corrino/.jwmrc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          4789/8301               57%
> <?xml version="1.0"?>
> <JWM>
>     <!-- The root menu. -->
>     <RootMenu onroot="12">
>         <Menu icon="folder" label="Applications">
>             <Program icon="utilities-terminal" label="Terminal">mate-terminal</Program>
>             <Program icon="sound" label="clementine">clementine</Program>
>             <Program icon="calc" label="calculator">mate-calc</Program>
>             <Program icon="text-editor" label="geany">geany</Program>
>             <Program icon="development" label="meld">meld</Program>
>             <Program icon="image" label="gimp">gimp</Program>
>             <Program icon="email" label="mail">thunderbird</Program>
>             <Program icon="web-browser" label="firefox">firefox-esr</Program>
>             <Program icon="web-browser" label="librewolf [rem.term]">librewolf</Program>
>             <Program icon="web-browser" label="chromium [rem.term]">chromium</Program>
>             <Program icon="internet" label="seamonkey">seamonkey</Program>
>             <Program icon="system-file-manager" label="caja">caja</Program>
>             <Program icon="soundcard" label="plug jack in">qjackctl</Program>
>             <Program icon="text editor" label="text editor">pluma</Program>
>             <Program icon="task-manager" label="system monitor">mate-system-monitor</Program>
>         </Menu>
>         <Menu icon="folder" label="Utilities">
>             <Program icon="color-picker" label="picker">gpick</Program>
>             <Program icon="info" label="Window Properties">
>                 xprop | xmessage -file -
>             </Program>
>             <Program icon="info" label="Window Information">
>                 xwininfo | xmessage -file -
>             </Program>
>         </Menu>
>         <Separator/>
>         <Menu icon="system-shutdown" label="poweroff">
>             <Program icon="shutdown" label="poweroff">loginctl poweroff</Program>
>             <Program icon="reboot" label="reboot">loginctl reboot</Program>
>         </Menu>
>         <Separator/>
>         <Restart label="Restart" icon="reload"/>
>         <Exit label="Exit" confirm="true" icon="exit"/>
>     </RootMenu>
>     <!-- Options for program groups. -->
>     <Group>
>         <Option>tiled</Option>
>     </Group>
>     <Group>
>         <Name>mate-terminal</Name>
>    <!--     <Option>vmax</Option> -->
>     </Group>
>     <Group>
>         <Name>xclock</Name>
>         <Option>drag</Option>
>         <Option>notitle</Option>
>     </Group>
>     <!-- Tray at the bottom. -->
>     <Tray x="0" y="-1" autohide="off" delay="1000">
>         <TrayButton label="JWM">root:1</TrayButton>
>         <Spacer width="2"/>
>         <TrayButton label="_">showdesktop</TrayButton>
>         <Spacer width="2"/>
>         <Pager labeled="true"/>
>         <TaskList maxwidth="256"/>
>         <Swallow width="32" height="32" name="clipboard">parcellite</Swallow>
>         <Swallow width="32" height="32" name="xclock">xclock</Swallow>
>         <Dock/>
>         <Clock format="%l:%M %p"><Button mask="123">exec:xclock</Button></Clock>
>     </Tray>
>     <!-- Visual Styles -->
>     <WindowStyle decorations="flat">
>         <Font>Sans-12:bold</Font>
>         <Width>2</Width>
>         <Corner>5</Corner>
>         <Foreground>#FFFFFF</Foreground>
>         <Background>#555555</Background>
>         <Opacity>1.0</Opacity>
>         <Active>
>             <Foreground>#FFFFFF</Foreground>
>             <Background>#0077CC</Background>
>             <Opacity>1.0</Opacity>
>         </Active>
>     </WindowStyle>
>     <TrayStyle decorations="flat">
>         <Font>Sans-12</Font>
>         <Background>#333333</Background>
>         <Foreground>#FFFFFF</Foreground>
>         <Opacity>1.0</Opacity>
>     </TrayStyle>
>     <TaskListStyle list="all" group="true">
>       <Font>Sans-12</Font>
>       <Active>
>         <Foreground>#FFFFFF</Foreground>
>         <Background>#555555</Background>
>       </Active>
>       <Foreground>#FFFFFF</Foreground>
>       <Background>#333333</Background>
>     </TaskListStyle>
>     <PagerStyle>
>         <Foreground>#555555</Foreground>
>         <Background>#333333</Background>
>         <Text>#FFFFFF</Text>
>         <Active>
>             <Foreground>#0077CC</Foreground>
>             <Background>#004488</Background>
>         </Active>
>     </PagerStyle>
>     <MenuStyle decorations="flat">
>         <Font>Sans-12</Font>
>         <Foreground>#FFFFFF</Foreground>
>         <Background>#333333</Background>
>         <Active>
>             <Foreground>#FFFFFF</Foreground>
>             <Background>#0077CC</Background>
>         </Active>
>         <Opacity>1.0</Opacity>
>     </MenuStyle>
>     <PopupStyle>
>         <Font>Sans-12</Font>
>         <Foreground>#000000</Foreground>
>         <Background>#999999</Background>
>     </PopupStyle>
>     <!-- Path where icons can be found.
>          IconPath can be listed multiple times to allow searching
>          for icons in multiple paths.
>       -->
>  
>  
>  
>  
>  
> /home/irulan-corrino/.jwmrc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          8301/8301              100%
>     </TaskListStyle>
>     <PagerStyle>
>         <Foreground>#555555</Foreground>
>         <Background>#333333</Background>
>         <Text>#FFFFFF</Text>
>         <Active>
>             <Foreground>#0077CC</Foreground>
>             <Background>#004488</Background>
>         </Active>
>     </PagerStyle>
>     <MenuStyle decorations="flat">
>         <Font>Sans-12</Font>
>         <Foreground>#FFFFFF</Foreground>
>         <Background>#333333</Background>
>         <Active>
>             <Foreground>#FFFFFF</Foreground>
>             <Background>#0077CC</Background>
>         </Active>
>         <Opacity>1.0</Opacity>
>     </MenuStyle>
>     <PopupStyle>
>         <Font>Sans-12</Font>
>         <Foreground>#000000</Foreground>
>         <Background>#999999</Background>
>     </PopupStyle>
>     <!-- Path where icons can be found.
>          IconPath can be listed multiple times to allow searching
>          for icons in multiple paths.
>       -->
>     <IconPath>
>       /usr/share/icons/hicolor/scalable/actions
>     </IconPath>
>     <IconPath>
>       /usr/share/icons/hicolor/scalable/apps
>     </IconPath>
>     <IconPath>
>       /usr/share/icons/hicolor/scalable/places
>     </IconPath>
>     <IconPath>
>       /usr/share/icons/hicolor/scalable/status
>     </IconPath>
>     <IconPath>
>       /usr/share/icons/hicolor/scalable/mimetypes
>     </IconPath>
>     <IconPath>
>       /usr/share/jwm
>     </IconPath>
>     <!-- Virtual Desktops -->
>     <!-- Desktop tags can be contained within Desktops for desktop names. -->
>     <Desktops width="4" height="1">
>         <!-- Default background. Note that a Background tag can be
>               contained within a Desktop tag to give a specific background
>               for that desktop.
>          -->
>         <Background type="solid">#111111</Background>
>     </Desktops>
>     <!-- Double click speed (in milliseconds) -->
>     <DoubleClickSpeed>400</DoubleClickSpeed>
>     <!-- Double click delta (in pixels) -->
>     <DoubleClickDelta>2</DoubleClickDelta>
>     <!-- The focus model (sloppy or click) -->
>     <FocusModel>sloppy</FocusModel>
>     <!-- The snap mode (none, screen, or border) -->
>     <SnapMode distance="10">border</SnapMode>
>     <!-- The move mode (outline or opaque) -->
>     <MoveMode>opaque</MoveMode>
>     <!-- The resize mode (outline or opaque) -->
>     <ResizeMode>opaque</ResizeMode>
>     <!-- Key bindings -->
>     <Key key="Up">up</Key>
>     <Key key="Down">down</Key>
>     <Key key="Right">right</Key>
>     <Key key="Left">left</Key>
>     <Key key="h">left</Key>
>     <Key key="j">down</Key>
>     <Key key="k">up</Key>
>     <Key key="l">right</Key>
>     <Key key="Return">select</Key>
>     <Key key="Escape">escape</Key>
>     <Key mask="A" key="Tab">nextstacked</Key>
>     <Key mask="A" key="F4">close</Key>
>     <Key mask="A" key="#">desktop#</Key>
>     <Key mask="A" key="F1">root:1</Key>
>     <Key mask="A" key="F2">window</Key>
>     <Key mask="A" key="F10">maximize</Key>
>     <Key mask="A" key="Right">rdesktop</Key>
>     <Key mask="A" key="Left">ldesktop</Key>
>     <Key mask="A" key="Up">udesktop</Key>
>     <Key mask="A" key="Down">ddesktop</Key>
>     <!-- Mouse bindings -->
>     <Mouse context="root" button="4">ldesktop</Mouse>
>     <Mouse context="root" button="5">rdesktop</Mouse>
>     <Mouse context="title" button="1">move</Mouse>
>     <Mouse context="title" button="2">move</Mouse>
>     <Mouse context="title" button="3">window</Mouse>
>     <Mouse context="title" button="4">shade</Mouse>
>     <Mouse context="title" button="5">shade</Mouse>
>     <Mouse context="title" button="11">maximize</Mouse>
>     <Mouse context="icon" button="1">window</Mouse>
>     <Mouse context="icon" button="2">move</Mouse>
>     <Mouse context="icon" button="3">window</Mouse>
>     <Mouse context="icon" button="4">shade</Mouse>
>     <Mouse context="icon" button="5">shade</Mouse>
>     <Mouse context="border" button="1">resize</Mouse>
>     <Mouse context="border" button="2">move</Mouse>
>     <Mouse context="border" button="3">window</Mouse>
>     <Mouse context="close" button="-1">close</Mouse>
>     <Mouse context="close" button="2">move</Mouse>
>     <Mouse context="close" button="-3">close</Mouse>
>     <Mouse context="maximize" button="-1">maximize</Mouse>
>     <Mouse context="maximize" button="-2">maxv</Mouse>
>     <Mouse context="maximize" button="-3">maxh</Mouse>
>     <Mouse context="minimize" button="-1">minimize</Mouse>
>     <Mouse context="minimize" button="2">move</Mouse>
>     <Mouse context="minimize" button="-3">shade</Mouse>
> </JWM>
>  1Help                                                              2UnWrap                                                            3Quit                                                              4Hex                                                               5Goto                                                               6                                                                  7Search                                                            8Raw                                                               9Format                                                           10Quit
>  
>  
>  
> --
> sov thade tage em ereb
> ```
[^1]: 'why have you decided to perform clean install of base system? you have made it a few weeks ago!!!' you would ask; i have tried TO MOUNT removable storage in caja ...then in terminal ...then to attach these logs to the email in seamonkey [as browser] ...then installed udiskie ...then another text editor [from XFCE, probably] ...then pcmanfm-gtk3 ...then have lost working installation!!!!
