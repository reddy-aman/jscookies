## What are Cookies?
Cookies are small pieces of data stored in the user’s browser. Websites use cookies to remember things like login details, preferences, and analytics.

## Purpose of the "Accept All Cookies"
When a user clicks "Accept All Cookies," the website stores cookies to track their session or user behavior, store preferences, etc.

## How It Works
1. When you visit the page, if you haven't accepted the cookies before, a banner will show at the bottom.
2. When you click "Accept All Cookies", it sets a cookie in your browser, and the banner disappears.
3. he cookie will remain for 1 year, and on subsequent visits, the banner will not show.

## Basic examples project : 
#### 1. Remembering User Login / Session
Features :
1. Setting a cookie when the user logs in.
2. Storing the login start time in the cookie.
3. On every page load, calculate how much time has passed since login.
4. If 5 seconds passed → log out.
5. If not → resume countdown from where it left off.
