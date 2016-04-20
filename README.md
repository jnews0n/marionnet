# marionnet
Marionnet network simulator


====== ''marionnet_from_scratch'' ======
The script ''marionnet_from_scratch'' automatically downloads, compiles and install Marionnet and its dependencies. It's the easiest way of installing the latest version of Marionnet on your machine, and we particularly recommend it to beginners.

===== Requirements =====
Marionnet requires a GNU/Linux system, with a x86 or x86_64 processor (if you don't know the type of your processor don't worry: it's one of these two), to which you have access as root.  A machine with 512Mb of RAM should be enough.  Of course you will need an Internet connection for downloading.

Any GNU/Linux distribution should work, but we have mostly tested on debian, ubuntu and gentoo; on debian-like distributions the script can also install some packages rather than compiling from sources (asking for permission before).

==== Disk space ====
You currently need about 1Gb of free disk space per filesystem image, in case you choose to download the biggest ones; a lot less if you only choose minimal images (Pinocchio). Marionnet itself and its dependencies should take less than 100Mb.
You will need around 500Mb more at compile time; of course that additional space is automatically freed after installation.

===== What to do =====
You can download the script from the address [[http://www.marionnet.org/downloads/marionnet_from_scratch/marionnet_from_scratch|http://www.marionnet.org/downloads/marionnet_from_scratch/marionnet_from_scratch]] (Save As... ''marionnet_from_scratch'').
It comes with a [[http://www.marionnet.org/downloads/marionnet_from_scratch/README|README file]]. You should start by reading that and following the instructions.

Essentially, in order to install into ''/usr/local'', you will need to download the script, and then execute:
<code>
chmod +x marionnet_from_scratch 
./marionnet_from_scratch
</code>

In case you need help with command-line options:
<code>
marionnet_from_scratch --help
</code>


===== If anything fails =====
The script has been developed quite carefully, but it might still have some problems; please [[:start|contact us]] if you find any bug.

//Please also remember that some parts of the script require superuser privileges, and may have security implications. There is no warranty.//
