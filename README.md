# Naomi's Website
Template from html5up.net | @ajlkn

# image resolution adjustment
identify -ping oldname.jpg
convert -resize 500x500 oldname.jpg newname.jpg
convert -resize 333x500 oldname.jpg newname.jpg

# count how many photos I took
sudo mount -t drvfs 'D:\' /mnt/d (or whichever drive)
then cd into the directory
'''find ./ -mindepth 1 -type f -name "*.jpg" -printf x | wc -c'''
(try unplugging and replugging if issues)
(MUST PROPERLY EJECT)

From: https://askubuntu.com/questions/454564/count-total-number-of-files-in-particular-directory-with-specific-extension


# More details from AJ:
Astral by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


First of its kind on H5U! Astral features a flat, minimalistic design, a fully animated
interface (with noscript fallbacks), and styling for all basic page elements (including
blockquotes, tables and lists). Enjoy!

AJ
aj@lkn.io | @ajlkn

PS: Not sure how to get that contact form working? Give formspree.io a try (it's awesome).
