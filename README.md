# Naomi's Website

Future Imperfect by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)

# Poses
tips:
-try to get the engagement ring to show
-have them pancake hold hands when their fingers might be visible (waffle if not)
-don't bother to keep looking for different locations; just do different poses
-try to get them to laugh or even better giggle (cheesy jokes, get one to whisper in the ear of the other)

A. STANDING
1. Front to side
2. front to front (ALWAYS make girl pop foot out)
3. side to side (only shoot back, adn turn 45degrees into each other)
4. cut in half (guy's hands in pockets and girls behind with arms looped in; his elbow should be in her chest)
5. from behind (his arms looped around her shoulders, NOT stomach or neck; his head needs to the side of her head)
6. the snuggle (like 'front to front', but she's a half step back from the camera, her belly button to hip; then ask her to point her nose to the camera)

B. SITTING
1. sitting out (guy sits first facing camera; girl puts butt right into his leg and leans back into her; guy puts his arm around her and gets a bit of an ab workout)
2. sitting in (girl puts her legs over ONE of his legs)
C. BODY, ADVANCED
1. the lean (start front-to-front; but he puts back leg past her; she pops foot out; she bends leg; both lean back)
2. the lift (face each other; guy staggers stance; girl puts all hair all on the back side away from the camera; guy squats and picks her up under her butt but do a pep talk before about grabbing the dress if it's a short dress; have him lift her and lean back) note that girl might not want to be lifted or the guy might not feel like he can lift her

C. DYNAMIC POSES
1. walking (the lead where they're perpendicular to your camera, have them take turns OR just hold hands and stay close together OR the 'escort' pose where he has his outside hand in a pocket and she puts both arms on his other; she does the beyonce/catwalk where each foot goes directly in front of the other; but try a bigger apperture like f/2.8)
2. dancing - the sway (holding one hand; his hand on the small of her back; her hand on his shoulder; just let them chat and move)
3. dancing - the twirl (only have them do it if she's in a long/flowy dress; have her hold her dess, toss it super quickly and THEN twirl; tell them to  maintain eye contact as long as possible; make sure they don't hurt their wrists)

D. BRIDE ONLY
1. the classic
2. the walk
3. the twirl

E. GROOM ONLY
1. the classic (he turns 45 degrees to make waist small and shoulders big, hands in pocket)
2. the lapel (hand on lapel to show of his watch)

F. HANDS
1. waist/arm
2. waist/shoulder
3. waist/neck (girl puts her hand on his 'jawline' to prevent strangle look; good to prevent double chin if he's super tall)
4. chin/arm
5. high hands
6.

G. FACE
1. both smiling at the camera
2. eye contact
3. kiss (we're going to have you go in really slowly for a kiss WHILE SMILING/NEUTRAL FACED not puckering lips, pause there, and then slowly come out)
4. forehead touch (I should adjust my voice/tone and slow down)
5. she looks at camera (guy should lightly touch his nose to her cheek OR temple depending on height)
6. turn and laugh
7. he looks

# image resolution adjustment

Install imagemagick (sudo apt-get install imagemagick)
identify -ping oldname.jpg
convert -resize 1080x1080 oldname.jpg newname.jpg
convert -resize 3240x3240 oldname.jpg newname.jpg

# count how many photos I took

sudo mount -t drvfs 'D:\\' /mnt/d (or whichever drive)
then cd into the directory
'''find ./ -mindepth 1 -type f -name "\*.jpg" -printf x | wc -c'''
(try unplugging and replugging if issues)
(MUST PROPERLY EJECT)

From: <https://askubuntu.com/questions/454564/count-total-number-of-files-in-particular-directory-with-specific-extension>

# Facebook cover photo dimensions are (2.628205128205128 or 1.777777777777778)

\-Displays at 820 pixels wide by 312 pixels tall on your Page on computers and 640 pixels wide by 360 pixels tall on smartphones.
\-Must be at least 400 pixels wide and 150 pixels tall.
\-Loads fastest as an sRGB JPG file that's 851 pixels wide, 315 pixels tall and less than 100 kilobytes.

# my forms work thanks to

<https://formspree.io/>

# example portfolios:
-split into wedding and portraits: https://www.cataracarrell.com


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
