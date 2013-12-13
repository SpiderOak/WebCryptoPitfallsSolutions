# Web Crypto Pitfalls

Trusting your web browser to provide you with real, tangible security and privacy is a tricky endeavor. Some say it is not possible, and never will be. Others are tinkering with crypto via the web attempting to design safer communications applictions. 

Either way, web users the world over are banking, trading stocks, engaging in commerce, selling illegal items and communicating with humman rights workers and dissidents. The Cat is Out of the Bag: we already do the things security experts tell us is "doing it wrong". This is being worked on, kudos! I say to our browser makers. They are nailing down many of the networking, content and certificate problems browsers face. 

This document intends to be a list of the problems we face, the technology already provided to mitigate risk in using web apps, and the functionality we need to further enable better-trusted web apps as well as a glossery of web browser-centric terms to help laypersons understand the jargon.    


# The PITFALLS

## Remote code is downloaded and executed immediately

## No native cryptography APIs are built into browsers... Yet.
### See: W3C Web Crypto API: 

## JavaScript is slow

## Lack of a big integers makes the Math hard to do

## Cross Site Scripting exploits (XSS)

## Cross Site Request Forgery (CSRF) https://www.owasp.org/index.php/Cross-Site_Request_Forgery_%28CSRF%29

## Browser "Zero Day" expolits https://en.wikipedia.org/wiki/Zero-Day_Attack

## Plugin exploits and issues

## JavaScript crypto now exposes key material to content directly
### Perhaps this can be partially mitigated by storing all key material in a Web Worker 
