# Try Hack Me - OhSINT

This is a writeup/report about my completion of the OhSINT room on TryHackMe, for future reference of how I completed the project.

## 0. Getting started

Since the starting point is just an image, I just downloaded that, and was ready to go.

## 1. Scanning via exiftool

The program exiftool can be used to view metadata of an image. I used it on the picture in question to find the following information that seemed significant:

* A Copyright to someone named OWoodflint, which sounds like a username
* The GPS coordinates 54 deg 17' 41.27" N Latitude, 2 deg 15' 1.33" W Longitude

The aformentioned GPS coordinates point to a spot in the town of Hawes, in the United Kingdoms, however, as it turns out, this has no significance to the TryHackMe room's task.
I may look into what these GPS cooridinates actually mean in the future, just out of curiosity.

## 2. OWoodflint

That word sounds like a nickname, so let's Google it. I found the following:

* A Twitter page
* A Wordpress blog
* A Github page

## 3. Twitter

On the Twitter page, I found a bragging post about OWoodflint probably not 100% legally accessing some Wifi network, which he even shared the BSSID of. Plugging that into `wigle.net`, I found out that he lives in London, and cross referencing with Google Maps, I found out he lives on Charles II Street, with the house number of around 71, near the Trafalgar Square.

I even have a handy screenshot of the building he probably lives in in my KeepNote notes.

## 4. The blog

The blog page doesn't tell us much at first glance, except, that he is currently in New York on vacation. However, upon viewing the page source, we can find a strange word, `pennYDr0pper.!` hidden on the page. It seems like a password, so it's a good idea to jot it down.

## 5. Github

From the Github page, we could find his personal email address.

## Conclusion

This room really opened my eyes as to how effective OSINT can really be, even without using tools such as Sherlock. If I were malicious, (and this was a real person, of course) I'd now know of a spot where the owner is not currently home.

I also know his address, have a picture of the place he lives at, and know he is abroad, so I could try to blackmail him in some manner.

## TODO

Set all my social media to private, hell, possibly delete them all...
