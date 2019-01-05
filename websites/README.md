# Websites

**Table of Contents**
1. [Bek Bakes](https://github.com/lukedenton/portfolio/tree/master/websites#bek-bakes)
2. [Port Noarlunga Football Club](https://github.com/lukedenton/portfolio/tree/master/websites#port-noarlunga-football-club)
3. [Fresh Rejuvenations](https://github.com/lukedenton/portfolio/tree/master/websites#fresh-rejuvenations)
4. [Bulk Pinner](https://github.com/lukedenton/portfolio/tree/master/websites#bulk-pinner)
5. [Luke Lights](https://github.com/lukedenton/portfolio/tree/master/websites#luke-lights)
6. [Links List](https://github.com/lukedenton/portfolio/tree/master/websites#links-list)
 
## Bek Bakes (and custom CMS)

I've recently rebuilt this website to use VueJS, with a custom headless CMS. This means that the website is all client side,
making use of API calls to get data dynamically. As part of the application, I've made use of Vuex to manage the state
of the application.

Another notable addition to the website is the spam filter. I've implemented a simple bait field that any normal user
wouldn't see, however bots will see and will think it's a required field, so they will fill it in. Before allowing the
form to be submitted, this field is checked for a value. If a value is present it means that the user is likely a bot, so the
submission is abandoned. The label for the field has a note for people who use screen readers that should prevent them
from filling in the field.

The custom CMS, which I can't link here because you would only see a login page, allows Bek to upload new images (with
thumbnails being automatically generated), re-order images, edit image names, as well as create and edit blog posts. The blog hasn't
been implemented on the main website yet, that will be part of a stage 2 rollout.

Along with designing and developing the website, I've set up a whole social media presence, with a [Facebook page](https://www.facebook.com/BekBakesSA),
[YouTube](https://www.youtube.com/channel/UCfDWd_I72C86Kk50TIjoH8g), [Pinterest](https://au.pinterest.com/bekbakes/)
and [Instagram](https://www.instagram.com/bek_bakes/) accounts

[Bek Bakes](http://www.bekbakes.com)

## Port Noarlunga Football Club

I built this site using Flexible ORM and Smarty for server side templating. I created a custom CMS for adding/managing news and
events. A lot of the design is based off Bootstrap, with very little custom design work.

The contact form on the site has a simple spam filter that has proven to be very effective. I simply ask the user to solve
a basic math equation, which is then checked against the server stored solution before the form is allowed to be submitted.

This site is due for a design update, possibly overhaul, in order to make it more usable, faster and visually appealing.

[Port Noarlunga Football Club](http://www.pnfc.org.au)

## Fresh Rejuvenations

This site has been built in a very similar way to the one for Bek Bakes. It is static, with HTML5 templating being used
for custom image lazy loading. The images are stored on Cloudinary, and loaded after the page has finished downloading.

As the site is static, I've been able to use GitHub pages for hosting, making it incredibly fast but also free for the client.

I designed the website, as well as the logo, in collaboration with the client. Unfortunately we haven't got further than
the design and development of the website, which is disappointing for me because I'm very proud of the work I had done.

[Fresh Rejuvenations (staging site)](http://freshrejuvenations.github.io/site/)

## Bulk Pinner

An application I made that allowed me to upload multiple pins to Pinterest at once.

I had a need to move a bunch of images from another service to Pinterest, but using the official website, you can only create 1 pin at a time. I had around 30 images that I wanted to move, so that was going to take a lot of time.

Looking online for an existing tool that allowed you to bulk upload pins, I found one that is tailored to social media marketers, allowing them to schedule pins. I tried to use the free tier on that service to upload my images, but I couldn't get it to work. Also, I was only using the free tier, so there were limitations.

I figured I could create something better, because it would be simpler, not require any account sign up, and allow people to add as many images to as many different boards as they wanted, at once.

The source code is open under the GNU General Public License, so people are more than welcome to help contribute to making this application great, or simple learn from how I interacted with the Pinterest API

[Bulk Pinner GitHub (source code)](https://github.com/bulkpinner/bulkpinner)

[Bulk Pinner site](https://bulkpinner.app)

## Luke Lights

This is a mobile-first application I created that allowed people to control the Christmas lights on my house over the holiday season.

It was build using Vue JS and Firebase, as a serverless application. Anything that would otherwise require a server was
done using Firebase Cloud Functions.

[Luke Lights](https://lukelights.app)

## Links List 

A simple online application that allows users to create a list of links that includes a link preview. The driving force behind
creating this was the lack of ability to share a wish list of items on eBay.

This application is build using the same approach as Luke Lights, Vue JS with Firebase as a serverless application.

[Links List](https://linkslist.app)
