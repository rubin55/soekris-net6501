# Soekris NET6501 PXE bootstrapping FreeBSD 11 How-to

After the untimely demise of my 11 year old Mac Mini PowerPC, I was in dire need of some new networking whatchamacallit. In a distant past, I'd heard about Soekris and so I figured I'd take a look on Wim Vandeputte's webshop [KD85](https://encrypted.kd85.com/soekris.html) and bought a 1ghz NET6501.

It turned out that it was a bit more involved than I expected to get stuff on the Soekris. So much so, that I decided to document my adventures in this little how-to repository, complete with the neccessary files to set up stuff.

In this how-to, I'll focus on a network based (PXE) installation of FreeBSD 11, But I think quite a few things will be eye-openers and/or helpful for other operating system bootstraps on the NET6501 also, so feel free to read along even if you don't do FreeBSD! Note that I have also tried the more obvious USB based installation, but I found the Soekris so picky with regards to USB stick variants, and in the case of FreeBSD the standard memstick.img so broken, that I opted for PXE instead.

(work-in-progress)
