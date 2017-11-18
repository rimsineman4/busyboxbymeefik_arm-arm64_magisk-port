# BusyBox by Meefik, Magisk port by Anton2365

## CHANGELOG:

2017-11-18: Repo created. Includes static BusyBox v1.27.2

## DESCRIPTION:

#### Hey guys! :)

This is meefiks version of the most-common used unix binary, **BusyBox**. This version is supported on both ARM & ARM64 platform.

After lots of tries of getting his apps, like e.g. *Linux Deploy*, to work with other busybox versions by other people/ports, I got the idea of porting his BusyBox binary into the Magisk repo, as this fixes most of the compatibility issues you're getting.

**NOTE: As this is the binary only, the utilities won't be linked.** So, to run a utility from shell you have to write
`(/system/bin/)busybox abc (--args) (xyz)`.

For example, to run *telnet*, run:

`(/system/bin/)busybox telnet 127.0.0.1:5023`.

Also, it depends on what ROM you use, and what tools that ROM aleady has (in use).

## DISCLAMIER:

As there are still some kind of people living out there who don't use their heads, I have to write that...

**THIS SOFTWARE COMES WITH ABSOLUTE NO WARRANTY. So if you get headaches or your kitty is going to throw flames at you, this is not my fault, it is purely yours. You have been warned.**

Also I didn't modify the binary, nor aren't I going to.

## LICENSING:

This software is fully open source and free to redistribute. It is licenced under GNU GPL v3.

Special thanks to Meefik for the actual binary.
