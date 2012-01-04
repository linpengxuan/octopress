--- 
categories: []
comments: true
layout: post
published: true
status: publish
tags: []
title: "let it work. and it works"
type: post
---
<div id="msgcns!3725CC0EE38B1F6!440" class="bvMsg">ladies and gentles, you are not gonna believe what i have done. i tried
to install my wireless card in linux which is my favorite choise to
windows. but i failed all the time when system kernel tried to compile
source into a mod that i could use in linux which solely design to my
computer. here are the steps i took<br>
    1, recompile kernel-failed<br>
    2,recompile another kernel -failed<br>
    3,tried using ndiswrapper rather that rt2500, the
practice of which i have made it successful on my gentoo system -damn
,failed again,<br>
    4,i tried to think ,could be my system's too, recompile it. failed.<br>
    5.move onto rt2500,another better choice to my wireless card than ndiswrapper.<br>
    6 failed to compile<br>
    7,then i start to think by rename the files , maybe i could cheat on the system.damn,failed again.<br>
8 learn sth from the kernel. when i can't modprobe it ,it just because
the file i compile was basing on the .config in /usr/src/linux/ , which
is not concorde with  my current kernel if you know what i mean.<br>
9 i start to feel frustrated. but retrospecting all the way i have been throught, no ,i would'nt give up.<br>
10 keep trying. so far , 10 hours has past, and my time leaving for paris seem to be shorten and shorten<br>
11. googling sth and given the fact i could find lspci name in gentoo
but not here in arch, i start to figure could it be this problem, i
switch to gentoo and think maybe the rt2500.ko there could applied to
arch....failed again.<br>
12.then i start to research on the gentoo ebuild , what really surprise
me is there is an patch to pci_name. and that suddenly reminds me , i
got hope.<br>
13 by patching to system myself without any guide or instruction, yes,
i finally make my wireless card working on my computer. and i made it.<br><br>
card is rt2500. solely design to linux. and i am happy ..hahahahaha...不爱现。<br>
</div>
