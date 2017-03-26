# Websites

**Table of Contents**
1. Bek Bakes
2. Port Noarlunga Football Club
3. Fresh Rejuvenations
4. Other
 
## Bek Bakes

I've built this as a static website, leveraging HTML5 templates a custom Javascript to lazy loading images. The gallery
also has a custom built infinite loader.

Another notable addition to the website is the spam filter. I've implemented a simple bait field that any normal used
wouldn't see, however bots will see and will think it's a required field, so they will fill it in. Before submitting a
form, this field is checked for a value. If there is a value, that means its likely a bot that filled in the form, so the
submission is abandoned. The label for the field has a note for people who use screen readers that should prevent them
from filling in the field.

The site will have a blog very soon, which will be managed using a custom built CMS. This CMS will also allow more images
to be uploaded and the gallery to be managed from a separate server, meaning the site will have to access that data through
and API call.

I also designed this website, which is not something I do a lot of, so I'm very happy with how it turned out.

[Bek Bakes](http://www.bekbakes.com)

## Port Noarlunga Football Club

I built this site using Flexible ORM and Smarty for server side templating. I created a custom CMS for adding/managing news and
events. A lot of the design is based off Bootstrap, with very little custom design work.

The contact form on the site has a simple spam filter that has proven to be very effective. I simple ask the user to solve
a basic math equation, which is then checked against the server stored solution before the form is allowed to be submitted.

This site is due for a design update, possibly overhaul, in order to make it more usable, faster and visually appealing.

[Port Noarlunga Football Club](http://www.pnfc.org.au)

## Fresh Rejuvenations

This site has been built in a very similar way to the one for Bek Bakes. It is static, with HTML5 templating being used
for custom image lazy loading. The images are stored on Cloudinary, and loaded after the page has finished downloading.

As the site is static, I've been able to use GitHub pages for hosting, making it incredibly fast but also free for the client.

I designed the website, as well as the logo, in collaboration with the client. Unfortunately we haven't got further than
the design and development of the website, which is disappointing for me because I'm very proud of the work I had done.

[Fresh Rejuvenations](http://freshrejuvenations.github.io/site/)

## Other

Around 10 years ago, I designed and developed 2 other websites, however they have since been updated and changed, so I
can't link to a version of them, because it's not the work that I did.

### Willunga Environment Centre

From memory, I created the site for the centre using Dreamweaver. The sites files were managed using FTP, and as part of
creating the website, I taught one of the volunteers at the centre how to update the website. This meant writing
code, and using the FTP client. The volunteer there only knew a little bit about computers, so I was very proud of myself
for being able to teach them some basic HTML and FTP.

### So You Think You Can Bowl (Ascot Park Bowls Club)

This website was created for an event held at the Ascot Park Bowls Club. The client had come up with a design and provided
it to me in a Microsoft Publisher file, so I replicated that as a web page/site. One of the big things that the site had to
 do was accept registration fees, so I was able to integrate the site with PayPal IPN so those payments could be accepted
 securely. The site was used for a couple of years, however it seems that the domain has since lapsed, as the URL no longer
 works.
