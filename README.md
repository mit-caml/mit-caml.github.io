CAML Lab Website
======================

📸 Updating a Photo
---------
1. Add your photo under "images/people" directory.
2. Create a markdown file named "Your-Name.md" in the "\_people" directory, containing the following (filled out with your information, instead).  If you have no website, fill this in as "https://mit-caml.github.io".
```
---
layout: post
type: "person"
name: "Divya Shanmugam"
image-path: "/images/people/<NAME OF YOUR FILE>.jpg"
website: "<YOUR WEBSITE>"
---
```

Make sure to include http:// or https:// at the beginning of the website.


📈 Adding a Publication
-------

Congrats on the publication! Share it with the world by following these steps.

1. Create a file under "\_posts" with the name "MM-DD-YYY-short-but-descriptive-name.md", where "MM-DD-YYYY" indicates the date of publication.
2. Fill out this template:

```
---
layout: post
type: "publication"
title:  "Formula 1 and Its Enduring Appeal over Time"
authors: "Divya Shanmugam, Lewis Hamilton, Carlos Sainz, Daniel Ricciardo, John Guttag"
venue: "NeurIPS 2021" 
external-url: "<arxiv-link"
code: "<optional-link>"
slides: "<optional-link>"
poster: "<optional-link>"
video: "<optiona-link>"
---

<YOUR-ABSTRACT>
``` 

🚨 Adding a News Item
--------------

You're famous! Rise to higher levels of reknown by following these steps.

1. Create a file under "\_posts" with the name "MM-DD-YYY-short-but-descriptive-name.md", where "MM-DD-YYYY" refers to the date of the announcement.
2. If you just want to link to an external article, fill out this template:

```
---
layout: post
type: "news"
title:  "Digital Ads are Ruining Basketball Uniforms"
date:   2013-06-05 20:33:11
external-url: https://paullukas.substack.com/p/exclusive-the-inside-story-of-why?utm_source=newsletter&utm_medium=email
---
```
3. If you want to write text too, fill out this template:

```
---
layout: post
type: "news"
title:  "Harini won the Great British Bakeoff!"
date:   2013-06-05 17:06:25
---

No one is surprised

---
```


📸 Adding Fun Photos
-----------------

You take an incredible photo of members of the lab!

1. Add your photo to `/images/fun`
2. Make a low-res thumbnail of your photo using `mogrify -path thumbs -resize 500px ./images/fun/YOURPHOTO`


That's it! Let me know if you run into issues, I would not be surprised if you do. 
