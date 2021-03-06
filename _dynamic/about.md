---
layout: default
title: About Cobbler
---

## Batteries Included

With a simple series of commands, network installs can be configured for PXE, reinstallations, media-based net-installs, and virtualized installs (supporting Xen, qemu, KVM, and some variants of VMware). Cobbler uses a helper program called 'koan' (which interacts with Cobbler) for reinstallation and virtualization support.

## #devops Friendly

Cobbler is a small and lightweight application (about 15k lines of Python code). It tries to be extremely simple to use both for very small and very large installations -- as well as easy to work on, extend, and hack. It avoids being "enterprisey" (as in complicated) whenever possible, but is highly useful in all sorts of enterprises by having a lot of advanced features and doing small things to save a large amount of time in repeated tasks.

## Infrastructure United

Cobbler can also optionally help with managing DHCP, DNS, and yum package mirroring infrastructure -- in this regard, it is a more generalized automation app, rather than just dealing specifically with installations. There is also a lightweight built-in configuration management system, as well as support for integrating with configuration management systems like Puppet. Cobbler has a command line interface, a web interface (screenshot), and also several API access options. 

That sounds like a lot, but it's really pretty simple. New users may like to start with the web app after doing the initial setup steps on the command line (cobbler check; cobbler import) as it will give them a good idea of all of the features available. Advanced features don't have to be understood all at once, they can be incorporated over time as the need for them arises.
