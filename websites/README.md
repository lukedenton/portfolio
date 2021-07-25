# Websites

**Table of Contents**
1. [Luke Lights](https://github.com/lukedenton/portfolio/tree/master/websites#luke-lights)
2. [Links List](https://github.com/lukedenton/portfolio/tree/master/websites#links-list)
3. [Bek Bakes](https://github.com/lukedenton/portfolio/tree/master/websites#bek-bakes)
4. [Calendar Icons Generator](https://github.com/lukedenton/portfolio/tree/master/websites#calendar-icons-generator)
4. [Notion Image Generator](https://github.com/lukedenton/portfolio/tree/master/websites#notion-images)

## Luke Lights

This is a mobile-first application I created that allowed people to control the Christmas lights on my house over the holiday season.

It was built using Vue JS and Firebase, as a serverless application. Anything that would otherwise require a server was
done using Firebase Cloud Functions.

[Luke Lights](https://lukelights.app)

## Links List

A simple online application that allows users to create a list of links that includes a link preview. The driving force behind
creating this was the lack of ability to share a wish list of items on eBay.

This application is build using the same approach as Luke Lights, Vue JS with Firebase as a serverless application.

[Links List](https://linkslist.app)
 
## Bek Bakes

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

[Bek Bakes](http://www.bekbakes.com.au)

## Calendar Icons Generator

An application that allows people to design an icon, and then use that design to create 365 individual icons, one for 
each day of the year, with specific day and date information for each month.

[Calendar Icons Generator](http://www.calendariconsgenerator.app)

## Notion Images

This app generates images of the perfect aspect ratio for Notion databases using the Gallery view. The image preview 
displayed in the gallery view will take up the whole space, and not leave any blank space either side 

[Notion Image Generator](https://notionimages.netlify.app/)
