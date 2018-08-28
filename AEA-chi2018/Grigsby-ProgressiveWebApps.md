# Designing Progressive Web Apps (PWA) - Jason Grigsby

[PWA Stats]()

## What is a PWA? (Slide 18)

Installed application or on the web (URL)

PWA - a website that has been enhanced with

* https: (Let's Encrypt, some APIs now require https)
* service worker 
    * need https for service worker
    * managing cache/network
    * increases performance
    * offline experience
    * notifications
* {manifest} - locally stored JSON document 

## Native App vs. PWA

__Yes__, PWAs can access the camera (Instagram), do geolocation (Google geolocation), and fingerprint sensor (JCrew, almost TOO EASY)!

## Factors to look at: (slide 84)

* Making it feel like an app
    * each team member will have a different opinion
    * Make it look native
    * Design your own design and be consistent
    * more immersive experience 
    * use the manifest files to determine full screen browser or keep browser utility bars
    * back button requires browser history, do you need one versus the browser's built-in back button?
    * new ```@media (display-mode:standalone), (display-mode: fullscreen) {css}```
    * fast and fluid experience
    * animate transitions to support wayfinding (ex: WEGO)
    * smooth pages /- avoid jumps, use skeleton pages
    * App Shell: put things in the cache (header, footer, etc.)
    * Single page application (SPA), user your traditional web site's API
    * Personality &amp; Polish, attention to detail and polish
    * Animation for wayfinding (css.tricks.com/native-like-animation...)
    * Should you really make it feel like an app?
* Installation and Discovery
    * manifest file: icon sources, theme colors, etc.
    * Use the Google Chrome tools to find manifest files
    * "Install to Homescreen", trigger browser request after repeated visits.
    * You don't need the app stores! But if you want to:
        * [MicroSoft PWA Builder]()
        * Google: Trusted Web Activity
        * Apple Phone Gap
* Offline mode
    * Store offline to make loads faster
    * offline fall-back page
    * Ask user(when on line) if they want to store for offline
    * Time stamp for user to know if the content is "stale"
    * Give users control
    * default pre-cache and giving user control of what is pre-cached
    * notification that user is offline
    * cache user inputs (such as blog posts)
    * [Workbox]()
* Push Notifications (sliding scale /- slide 179)
    * Notification JS
    * Personalize notifications (Slacks decision flowchart, slide 168)
    * Push notification services (slide 169)
    * __Don't__ immediately ask for push notification permission
        * try placing at the bottom of a blog post or at the end of a purchase
    * __ONLY ask ONCE__ about push notifications
    * Remember that smartphones have a "kill switch" for notifications per app that users can use
* Beyond PWAs (slide 185)
    * Credential Management API combined with Auto-login
    * Payment Request API (example: Apple Pay)

Decision sliding scale for incremental improvements (slide 190)
* benchmark for ROI

If the traditional website is slow, converting to a PWA is __NOT__ going to improve the speed.

Progressive Web App Blueprint (slide 95)

You can do all of this in small increments. It does not have to be done all at once!

Look for A Book Apart in November 2018