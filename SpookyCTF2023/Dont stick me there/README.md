## Challenge

```
I woke up after a night out and I'm hurting uh... everywhere... I think I left my phone at one of the bars we were at last night. Thankfully, I was able to see the last photo I took through the cloud.

Can you help me find my phone? I need to know the name of the bar and when the photo was taken.

flagformat: NICC{Bar_Name-HH:MM:SS}
```

And an attachment of an image.

## Solution

First, I try to work with the QR code on the image but the resolution was not enough to scan it easily.

Then I checked the metadata of the image and all the necessary information was there. I got the bar name from the latitude and longitude information using Google Maps.

### NICC{The_Anchored_Inn-03:47:12}
