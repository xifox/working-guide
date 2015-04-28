## working with debian
This section is about installing debian for the first time, and/or solving some
issues about it.

#### Before Install

You need to make sure you have space enough in some hdd drive to install
debian. You may want to check [online
manual](https://www.debian.org/releases/stable/installmanual), in the section
corresponding to your machine's architecture, system requirements section to be
more sure.
Normally, win users need to reduce their system volume to create a new one to
install a new system on there. Many tools are known to do this, such as
[partition magic 8](https://duckduckgo.com/?q=partition+magic+8), but you also
can use that which comes with windows. Since 7, windows operating systems bring
a disc manager application which you can use to do the trick.

![test](https://github.com/xifox/working-guide/blob/master/debian/windm.jpg)

The above image is an example of two discs seen in this app. In this example,
first disc containing windows 7, was shrinked at aprox 1/3 of its
original size. With the remaining space, there were created two partitions. The
last one was left to use by windows to store documents. The other one, was for
debian.

Move/resize/delete partition to have a portion of one disc free to install your
new system.

[![fs](http://img.youtube.com/vi/vTewGX67vu0/0.jpg)](http://www.youtube.com/watch?v=vTewGX67vu0)

The video linked above, shows how to resize your hd using partition magic.

#### Installation.

First thing you need to do is download any of iso images to start your machine
with the instalation of debian. I recomend for now `net-install'. It has the
basic system enough to start the instalation. In it, you can choose later one
or more servers from where to download the rest of the packages, from a list of
repositories all arround the world. [Visit debian download
page](https://www.debian.org/releases/stable/debian-installer/)

You can burn the image into a cd, or you can put it on an usb stick. There are
many tutorials to learn how to do this, but in fact, and for new linux users,
maybe "[linux live usb creator](http://www.linuxliveusb.com/)", known as
'lili', is a very good option. More than it, imho, is
[UNetbootin](http://unetbootin.sourceforge.net/). It's multiplatform between
others beneficts. [Unetbootin
Wikipedia](https://en.wikipedia.org/wiki/UNetbootin).

Above this readme, is loaded a version of it, for win operating sytem. Please, 
in the pass of time, check official site for new verions.

Normally, new linux users come from win operating systems, so, these programs run on
it. What these program do, is pick up an iso image of some linux distros, an
puts it on a usb stick, making it bootable.

[![fs](http://img.youtube.com/vi/Qmqaf805XzQ/0.jpg)](http://www.youtube.com/watch?v=Qmqaf805XzQ)

The above video shows, shortened, a debian network install. It shows a virtual
machine booting from an image cd, performing a full install.

#### Usefull links

[on line manual](https://www.debian.org/releases/stable/installmanual).

[debian wiki](https://wiki.debian.org/)

[Social Contract](https://www.debian.org/social_contract)

[Mailing list support](https://www.debian.org/MailingLists/)
