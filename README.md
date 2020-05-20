# Naomi's Website

Future Imperfect by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)

# image resolution adjustment
Install imagemagick (sudo apt-get install imagemagick)
identify -ping oldname.jpg
convert -resize 1080x1080 oldname.jpg newname.jpg

# count how many photos I took

sudo mount -t drvfs 'D:\\' /mnt/d (or whichever drive)
then cd into the directory
'''find ./ -mindepth 1 -type f -name "\*.jpg" -printf x | wc -c'''
(try unplugging and replugging if issues)
(MUST PROPERLY EJECT)

From: <https://askubuntu.com/questions/454564/count-total-number-of-files-in-particular-directory-with-specific-extension>

# my forms work thanks to

<https://formspree.io/>

# notes from the person's template

It's been a long time coming, but I've finally gotten around to creating a brand new
blog-style template (and the first since Striped, which came out waaaaay back in 2013).
Anyway, Future Imperfect features a clean, expansive layout, a toggleable search box,
and -- because pretty much all modern browsers can use it now -- a whole lot of flexbox
action. Enjoy it :)

Demo images\* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(\* = not included)

AJ
aj@lkn.io | @ajlkn

Credits:

    Demo Images:
    	Unsplash (unsplash.com)

    Icons:
    	Font Awesome (fontawesome.io)

    Other:
    	jQuery (jquery.com)
    	Responsive Tools (github.com/ajlkn/responsive-tools)
