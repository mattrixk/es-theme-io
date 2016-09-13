# Io
A theme for Emulationstation and RetroPie


##About

Io is a simple black and white theme created for EmulationStation and RetroPie. Well, not exactly black and white. I found the pure white to be too bright on the eyes, so I toned it down to #0c0c0c and #d8d8d8.

Io comes with 3 different sizes to deal with different sized screens:

- Large is the default size for TVs and computer monitors. The Detailed View shows all metadata except for the Publisher. I had to sacrifce something for space, and that one seemed like the best to remove.
- Medium removes most of the metadata from the Detailed View, leaving just the Image, Genre and Number of Players.
- Small is for small screens like those in Pi-modded gameboys. The fonts are larger in both Basic and Detailed Views. Detailed View only shows the Image and the Gamelist, and the gamelist only shows 3 titles at time. The help menu has also been removed from Basic and Detailed Views to maximise available space.

To change which size is used, open io.xml and change line 17:
```
<include>./_inc/templates/large.xml</include>
```
to say either 'small', 'medium' or 'large'.

I used the same system folders as Carbon V2.0.4. I also used the .svg images from Carbon, but changed all the colours to #0c0c0c and #d8d8d8 (that was time consuming) so they fit the theme.


##Images

*'Io' Theme System View*
![Io Theme System View](http://i.imgur.com/XqnAFNw.jpg)

*'Io' Theme Basic View - Large*
![Io Theme Basic View](http://i.imgur.com/E4Jbs1n.jpg)

*'Io' Theme Detailed View - Large*
![Io Theme Detailed View](http://i.imgur.com/PZEkapg.jpg)

*'Io' Theme Basic View - Medium*
![Io Theme Basic View](http://i.imgur.com/frkYj4W.jpg)

*'Io' Theme Detailed View - Medium*
![Io Theme Detailed View](http://i.imgur.com/zDe6I4L.jpg)

*'Io' Theme Basic View - Small*
![Io Theme Basic View](http://i.imgur.com/0F9YVL1.jpg)

*'Io' Theme Detailed View - Small*
![Io Theme Detailed View](http://i.imgur.com/zwaszYN.jpg)

More images available on [Imgur](http://imgur.com/a/v1V88).

##Artwork

- All Logo graphics are from the default Carbom theme made by Eric Hettervik.
- All screenshot artwork owned be their respective owners.


##Notes

- This theme has not been tested with a 4/3 ratio, but you should be okay if you use either the Medium or Small sizes. However, you may still come across some ugliness with the metadata on the Detailed view in the Medium size.
- This theme currently doesn't take into account either the GridView Mod, or the Child-Friendly versions of EmulationStation, but there are plans for them in the future.


##Changelog

2016-09-13
v1.1
- added Large, Medium and Small sizes.
- removed fontSize bug.

2016-09-07
v1.0 Initial version

---

Theme 'io' v1.0 - 2016-09-07
(c) Matt Kennedy - info@cutmonkey.net - http://cutmonkey.net/
For use with EmulationStation (http://www.emulationstation.org/)
and RetroPie (https://retropie.org.uk/)
