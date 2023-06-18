
 * [Stories of Atlantis](#stories-of-atlantis)
 * [Features](#features)
 * [Testing](#testing)
   * [Browers](#browers)
   * [on small phone](#on-random-wide-screen)
   * [ipad](#ipad)
   * [on random wide screen](#on-random-wide-screen)
   * [zoomed on desktop pc](#zoomed-on-desktop-pc)
   * [Spelling Check](#spelling-check)
   * [Lighthouse Approved](#lighthouse-approved)
 * [Issues](#issues)
   * [Bugs](#bugs)
     * [Solved](#solved)
     * [Open](#open)
   * [Future Improvements](#future-improvements)
 * [Codeanywhere Reminders](#codeanywhere-reminders)
 * [Sources](#sources)
   * [Media](#media)
   * [Code](#code)

# Stories of Atlantis

The webpage is intended to collect various webpages, which try to explain the history of Atlantis. People can contribute their own webpage to be displayed on this host webpage. One can navigate through the buttons on the top navigation bar. 
The welcome and story page have a background picture to support the athmosphere of ancient Greek world.
On the right site are supportive webpages.
The last page gives a form where a user can contribute with his own fantastical story.

# Features

Welcome page with short explanation what the webpage is for and how to interact.

Top navigation bar with buttons, which exchange the content by switching referenced html page.

The last button opens a page where to give ones own story and by that contribute to the idea.

The right side holds space for partners as references, where to go for building websites or just some distraction.

# Testing

## browers:
Firefox 112.0.2 (64-bit) on 5.19.0-41-generic #42~22.04.1-Ubuntu with KDE
Ecosia on Android 11, kernel 4.19.157-perf+

## on small phone: 			
![image](https://user-images.githubusercontent.com/93140389/235036933-f3c56b23-1fc0-44d3-9f82-8100680d1b70.png)

on Fairphone with Ecosia:
![image](https://user-images.githubusercontent.com/93140389/235036969-58348e39-b191-4bf0-be2c-f304c47da8a1.png)

## ipad:
![image](https://user-images.githubusercontent.com/93140389/235037015-b2320f5a-4131-4179-9a89-ca786cb2fd10.png)

## on random wide screen:
![image](https://user-images.githubusercontent.com/93140389/235037065-327941cb-d804-43dd-a22b-ccfbffda23dc.png)

## zoomed on desktop pc:
![image](https://user-images.githubusercontent.com/93140389/235037082-9e55c28a-d4b4-4205-b5a2-5b0d86d601f1.png)

## Spelling Check

style.css checked by
https://jigsaw.w3.org/css-validator/#validate_by_input

html files checked by
https://validator.w3.org/#validate_by_input

# Lighthouse Approved:
![image](https://user-images.githubusercontent.com/93140389/235037108-577e97b8-d3ed-4648-b1ff-2be77fd98962.png)

# issues

## Bugs:

### solved
1. Links were not all working.
2. I noticed, those where working which did not start from root directory ('/'), but locally and by that on referenced pages it was necessary to navigate first upwards in directory and the to the target: '../assets/css/style.css'

### open
1. between screen width 630 and 960 the background image in traders is jumping away from left side bar.
2. but 1. appears on zooming as well

## Future improvements:
1. In case of many storys, the buttons must appear to be scrollable or positioned more flexible.

#============== original by school: ==============


![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome,

This is the Code Institute student template for Codeanywhere. We have preinstalled all of the tools you need to get started. It's perfectly ok to use this template as the basis for your project submissions.

You can safely delete this README.md file, or change it for your own project. Please do read it at least once, though! It contains some important information about Codeanywhere and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **March 3rd, 2023**

# Sources

## Media

### Referenced

- https://codeinstitute.net/de/wp-content/themes/codeinstitute/img/svg/Code_logo_grey_fit.svg

- https://www.webfx.com/archive/assets/global/img/header/webfx-logo.png

- http://www.w3.org/2000/svg

- https://porenhub.de/img/porenhublogo4.gif

- https://img.freepik.com/free-vector/city-landmarks-background-video-conferencing_23-2148635775.jpg?w=2000&t=st=1682418883~exp=1682419483~hmac=809b46ef3442856d753d7eb17fcda789fbd88e433bbfd59ccef29a761f7655d9

- https://img.freepik.com/premium-photo/greece-santorini-island-iconic-view-with-blue-churches-oia-village_287743-185.jpg?w=2000

### Downloaded into source files

- https://de.freepik.com/fotos-kostenlos/taj-lake-palace-in-udaipur-rajasthan-indien_3540095.htm#page=2&query=ancient%20city%20on%20water&position=4&from_view=search&track=ais

- https://de.freepik.com/fotos-kostenlos/hausboot_1278009.htm#query=wooden%20house%20on%20water&position=48&from_view=search&track=ais

- https://de.freepik.com/fotos-kostenlos/schoene-aufnahme-eines-kleinen-dorfes-umgeben-von-einem-see-und-schneebedeckten-huegeln_13005858.htm#query=wooden%20house%20on%20water&position=26&from_view=search&track=ais

- https://de.freepik.com/fotos-premium/ein-see-mit-einem-dock-und-einem-berg-im-hintergrund_44867410.htm#query=houseboot&position=45&from_view=search&track=ais?sign-up=google

- https://de.freepik.com/fotos-premium/ein-bootshaus-am-wasser-mit-bergen-im-hintergrund_44737994.htm#query=houseboot&position=42&from_view=search&track=ais

- https://de.freepik.com/fotos-premium/antike-unterwasserstadt-in-den-tiefen-des-ozeans-atlantis-verlorene-welt-ki_36269755.htm#query=atlantis&position=7&from_view=search&track=sph


## Code

## Codeanywhere Reminders

To run a frontend (HTML, CSS, Javascript only) application in Codeanywhere, in the terminal, type:

`python3 -m http.server`

A button should appear to click: _Open Preview_ or _Open Browser_.

To run a frontend (HTML, CSS, Javascript only) application in Codeanywhere with no-cache, you can use this alias for `python3 -m http.server`.

`http_server`

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A button should appear to click: _Open Preview_ or _Open Browser_.

In Codeanywhere you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to _Account Settings_ in the menu under your avatar.
2. Scroll down to the _API Key_ and click _Reveal_
3. Copy the key
4. In Codeanywhere, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

---

Happy coding!
