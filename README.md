### Hi, I’m Alex. 👋

I currently work as a Security Engineer in the UK energy sector.

Here you'll find a few of my interesting projects. _Please_ don't rely on them for anything mission critical, but do feel free to look around! 😄

#### [AS215768](https://bgp.tools/as/215768)
My very own RIPE-allocated AS. A fun project that involved acquiring my own IPv6 prefixes to advertise, and learning far more than I wanted to know about BGP. It's currently fully functional, [as you can see here](https://as215768.net) (assuming your ISP supports IPv6), but there's not a lot on there yet. I have plans to get more adventurous with this project as time goes on.

#### [Pinewall](https://github.com/alexhaydock/pinewall)
This is my custom Alpine Linux router spin. I've been running this in production as my core (home!) internet gateway since mid-2021. It runs entirely from RAM on a Raspberry Pi 4 using images entirely built within GitLab CI, and leverages Alpine's [LBU](https://wiki.alpinelinux.org/wiki/Alpine_local_backup) functionality to overlay configs.

#### [Goldenblue](https://github.com/alexhaydock/goldenblue)
This is my personal "golden image" spin of the immutable [Fedora Silverblue](https://fedoraproject.org/atomic-desktops/silverblue/). It's also built entirely within GitLab CI, and is heavily inspired by the [Universal Blue](https://universal-blue.org/) project. I've been running this as my "daily driver" since Fedora 38 and it's been working very well for that purpose.

#### [Install-Gentoo](https://github.com/alexhaydock/install-gentoo)
Okay, this one is... not so serious. This is my attempt at building an end-to-end build process for a (mostly) entirely hands-free Stage 3 tarball install of Gentoo Linux using an Ansible playbook. Shockingly it does actually work.
