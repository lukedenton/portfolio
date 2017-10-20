# Websites

**Table of Contents**
1. [Bek Bakes](https://github.com/lukedenton/portfolio/tree/master/websites#bek-bakes)
2. [Port Noarlunga Football Club](https://github.com/lukedenton/portfolio/tree/master/websites#port-noarlunga-football-club)
3. [Fresh Rejuvenations](https://github.com/lukedenton/portfolio/tree/master/websites#fresh-rejuvenations)
4. [Bulk Pinner](https://github.com/lukedenton/portfolio/tree/master/websites#bulk-pinner)
 
## Bek Bakes

I've built this as a static website, leveraging HTML5 templates and custom Javascript to lazy load images. The gallery
also has a custom built infinite loader.

Another notable addition to the website is the spam filter. I've implemented a simple bait field that any normal user
wouldn't see, however bots will see and will think it's a required field, so they will fill it in. Before allowing the
form to be submitted, this field is checked for a value. If a value is present it means that the user is likely a bot, so the
submission is abandoned. The label for the field has a note for people who use screen readers that should prevent them
from filling in the field.

The site will have a blog very soon, which will be managed using a custom built CMS. This CMS will also allow more images
to be uploaded and the gallery to be managed from a separate server, meaning the site will have to access that data through
API calls.

Along with developing the website, I designed it, and set up a whole social media presence ([Facebook page](https://www.facebook.com/BekBakesSA),
[YouTube](https://www.youtube.com/channel/UCfDWd_I72C86Kk50TIjoH8g), [Pinterest](https://au.pinterest.com/bekbakes/)
and [Instagram](https://www.instagram.com/bek_bakes/) accounts), which is not something I do a lot of, so I'm very happy
with how it has all turned out

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

I built this online application because I had a few images that I needed to transfer to Pinterest. There are a couple of options online that allow you to schedule pins, but I couldn't get it to work properly, and they are a subscription based service, with limitations on the free tier. This application allows anyone to quickly upload multiple images to Pinterest without any sign up or any hassle.

The code is open source, and can be found here [Bulk Pinner GitHub](https://github.com/bulkpinner/bulkpinner)

[Bulk Pinner](https://bulkpinner.github.io/site/)
