# BETTER LINUX
##### as of june 2022 we have no OS/environment that is able to satisfy needs of a music performer [saying 'environment' i mean some hypothetical system dedicated to music production that is running on bare hardware without any OS involved]. operating systems range from unusable paid stuff posessing extremely limited capabilities to produce sound to renowned free software that is potentially offering unlimited functionality but is impossible to maintain for a musician without programming background. among all the operating systems i tried [Fodos [PDP11 or CP/M]; Windows OS; Syllable/Rex-linux; jNode; Singularity; Free BSD; QNX; linux] only linux was usable and friendly. in this piece i am not going to propose any new features to linux --instead i name things a real-world programmer does not need. indeed we could return to the days when we had no OS involved in between hardware and user application producing music much like Doom was run without DOS back in 1995 and i recollect i was writing stuff in Basic for ZX Spectrum without any OS installed... but that is not progressive way to write programs.
### here are the things a real-world programmer does not need:
- without POSIX linux would be much better; [please note: i do not take an opinion[^1] of l. poettering[^2] --instead i stand FOR REAL PROGRESS NOT TEMPORARY ACHIEVEMENTS --by my experience things like POSIX are nothing but hastily complying to governments fascination with non-free OSes];
- without mitigations of vulnerabilities linux would be much better;
- without firewalls linux would be much better;
- without antiviruses linux would be much better [arch wiki (List of software) proposes clamav and i have some experience with software produced by clam
-- as a musician i used clamChordata --it was SUCH A PIECE OF TRASH (do not even tell me that some girl like an abalone may have A CHORD!!!)];
- without 'military-grade AES encryption' & LUKS or dm-raid or whatsoever linux would be much better;
- without apparmor linux would be much better; [...just some another military stuff];
- without systemd linux would be much better; ['SystemDumb! Return to the sweatest times of Windows OS 3.11!!!']; 'From dé- + merde + -er, literally “to remove oneself from the shit”'[^3]; 'In October 2012, Arch Linux made systemd the default, also switching from SysVinit. Developers had debated since August 2012 and came to the conclusion that it was faster and had more features than SysVinit, and that maintaining the latter was not worth the effort in patches. Some of them thought that the criticism towards the implementation of systemd was not based on actual shortcomings of the software, rather the disliking of Lennart from a part of the Linux community and the general hesitation for change...' [a fatal decision] '...Specifically, some of the complaints regarding systemd not being programmed in bash, it being bigger and more extensive than SysVinit, the use of D-bus, and the optional on-disk format of the journal were regarded[^4] as advantages by programmers.'[^5]; *final note:* wikipedians are ranting on 'old-fashioned linux users who are not ready to a switching from plain shell scripts and init scripts to some more abstract[^6] approach [like to one of this popular shit discussed here]' --this piece of trashy software is NOT ABSTRACT --it is derived[^6][^7][^8] AND contrived[^6][^7][^8]; ***also:*** *please* confer citation#6[^6] & citation#9[^9];
- without udev linux would be much better; ['no! --you develop!'];
- without pulseAudio linux would be much better; 'In 2011 Poettering, one of the main developers of PulseAudio, praised ~~the Windows~~ and macOS audio stacks as "~~more advanced~~" [and called Open Sound System "a simplistic 90s style audio stack" without relevance for a modern desktop].'[^2] [~~strike-through~~ is mine];
- without portAudio linux would be much better;
- without jackd linux would be much better;
- without X11 or Wayland linux would be much better;
- [consequentially] without widget toolkits (GTK, Qt, EFL or whatever else) linux would be much better. i guess real programmer does not need such stuff; only people that received any kind of formal education may benefit from those frameworks but just like creators of those toolkits they use visual editors designed for rapid application/interface development and in reality no one of them is able to code in a programming language. it is just like using stone scraper for cleaning a hide of hunted animal for paying for that stone scraper... you cannot use your nails for cleaning the hide and you cannot wear a stone for clothes!!!

---
###### you may ask 'But WHO needs you performing your non-classist music?' --and who may need hides and stone scrapers?
---
###### code sample 0

> ```
> [irulan-corrino@amelanchier ~]$ systemctl --user list-unit-files pulseaudio
> UNIT FILE STATE VENDOR PRESET
>
> 0 unit files listed. # ........................................... what DO YOU THINK it does mean?
>
> [irulan-corrino@amelanchier ~]$ systemctl --user list-unit-files pipewire
> UNIT FILE STATE VENDOR PRESET
>
> 0 unit files listed.
>
> [irulan-corrino@amelanchier ~]$ systemctl --user list-unit-files pipewire.service
> UNIT FILE        STATE   VENDOR PRESET
> pipewire.service enabled enabled      
>
> 1 unit files listed.
> ```

<img alt="WHAT? -Screenshot_2022-07-02_04-34-43" title="systemDumb! the sweatest taeste of Windows 3.11!!!" src="https://user-images.githubusercontent.com/98284211/177002808-b6d55aef-d69e-4b70-8cd7-d331ce0996cb.png" width="512" />

---

###### code sample 1

> ```
> [root@amelanchier irulan-corrino]# systemctl --global enable wireplumber@.service
> Failed to enable wireplumber@.service, destination unit pipewire.service is a non-template unit.
> [root@amelanchier irulan-corrino]# dont do -- to me
> ```

[^1]: 'For instance, Poettering has advocated speeding up Linux development at the expense of breaking compatibility with POSIX and other Unix-like operating systems such as the BSDs. He took this position because of his experience in writing some other low-level components in the desktop stack. He invites other developers to do the same. Poettering recommends also reading "The Linux Programming Interface" but ignoring the POSIX-specific parts.'
[^2]: https://en.wikipedia.org/wiki/Lennart_Poettering
[^3]: https://en.wiktionary.org/wiki/d%C3%A9merder
[^4]: [...and i read that. ONE PERSON!!! (but such an ugly tone is common for wikipedia-based critics)]
[^5]: https://en.wikipedia.org/wiki/Systemd
[^6]: 'A plain unit (not a template or an instance), may only be aliased by a plain name. A template instance may only be aliased by another template instance, and the instance part must be identical. A template may be aliased by another template (in which case the alias applies to all instances of the template). As a special case, a template instance (e.g.  "alias@inst.service") may be a symlink to different template (e.g.  "template@inst.service"). In that case, just this specific instance is aliased, while other instances of the template (e.g.  "alias@foo.service", "alias@bar.service") are not aliased. Those rules preserve the requirement that the instance (if any) is always uniquely defined for a given unit and all its aliases.'
[^7]: see code sample 0
[^8]: see code sample 1
[^9]: 'When, then, the Great Archon had been orally instructed, and every creature of the Ogdoad had been orally instructed and taught, and [after] the mystery became known to the celestial [powers], it was also necessary that afterwards the Gospel should come to the Hebdomad, in order likewise that the Archon of the Hebdomad might be similarly instructed and indoctrinated into the Gospel.'
https://en.wikipedia.org/wiki/Refutation_of_All_Heresies
