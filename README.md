# instagram-api
Instagram API

The first version of the Instagram API is an exciting step forward towards making it easier for users to have open access to their data. We created it so that you can surface the amazing content Instagram users share every second, in fun and innovative ways.

https://instagram.com/developer/<BR><BR>

https://github.com/Instagram/python-instagram<BR><BR>

#What is Instagram?

Capture and Share the World's Moments
Instagram is a free and simple way to share your life and keep up with other people.

Take a picture or video, then customize it with filters and creative tools. Post it on Instagram and share instantly on Facebook, Twitter, Tumblr and more—or send it directly as a private message. Find people to follow based on things you’re into, and be part of an inspirational community.

https://instagram.com


#My small study about the instagram world and the picture world.

This small study is about the instagram api and pictures.

#How to use this app

Change the file client_credential.php and put your CLIENT_ID and CLIENT_SECRET

See:

```
$CLIENT_ID = 'XXXXXXXXXX';
$CLIENT_SECRET = 'YYYYYYYYYYY';
```


#Instagram App URLs (PHP)

Instagram User Search:<BR>
http://localhost:8282/instagram-app/search_for_users.php<BR>

Instagram User Profile<BR>
http://localhost:8282/instagram-app/get_user_profiles.php<BR>

Instagram User Relationships<BR>
http://localhost:8282/instagram-app/get_user_relationships.php<BR>

Instagram Get Image data<BR>
http://localhost:8282/instagram-app/image_data.php<BR><BR>

http://localhost:8282/instagram-app/popular_instagram_photos.php<BR>
http://localhost:8282/instagram-app/search_images_by_location.php<BR>
http://localhost:8282/instagram-app/search_by_tag.php<BR>
http://localhost:8282/instagram-app/search_images_by_tag.php<BR>

#Instagram App (Python)

See the code:<BR>
https://github.com/caiomsouza/instagram-api/blob/master/python/instagram_api.py<BR>

#Getting the picture metadata
Use a software called ExifTool.<BR>
http://www.sno.phy.queensu.ca/~phil/exiftool/

I tried on my Mac OS the version below:<BR>
Mac OS X Package: ExifTool-9.98.dmg (2.5 MB)<BR>

On the Mac OS Terminal or Linux type:<BR>

exiftool /Users/caiomsouza/Downloads/picuture_name.jpg > track.log<BR>

See also:<BR>
http://www.sno.phy.queensu.ca/~phil/exiftool/faq.html<BR>


#PyExifTool – A Python wrapper for Phil Harvey’s ExifTool
http://smarnach.github.io/pyexiftool/

# Photo EXIF Analysis | rCharts + catcorrjs + exiftool
http://timelyportfolio.github.io/rCharts_catcorrjs/exif/

#More links:
http://mygeoposition.com<BR>
http://www.ibm.com/developerworks/xml/library/x-instagram1/index.html#retrievedetails/<BR>
http://www.ibm.com/developerworks/library/x-instagram2/index.html<BR>
