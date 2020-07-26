# IIIT-H OLX

====================
    <Project>
====================

I have created a web-app that I lovingly call 'IIITOlx'. As the name suggests, 
anyone who has created an account here can post an article about what they want to sell. 
They just have to add the name of the item they want to sell, the picture of the said item, 
a small description(optional) and the price at which they are inclined to sell it.

This application lets the user to view the list of items currently up for sale BUT to 
post reviews and remarks (hence making deals and actually buying) the user must be 
logged in (this is to support the buyer/seller if a breach of trust were to transpire). 
Once the seller has handed over the product to buyer and recieved the money, 
they can remove the item from the list of available items. Currently we support only buy 
and sell options but we shall soon add new options like rent,lost,found,etc.

===================
   <APP SETUP>
===================

You just need to make sure you have Node.js installed.
Open the Hackathon directory in your terminal and run
    
    $ npm install   // To install all the dependencies

    For Mongodb server I have used MONGO ATLAS but I suggest
    you to use your own mongodb server so that you disturb my
    personal account. But for testing purposes you are free to use mine

    To run the application locally on port 3000 run
    
    $ node app.js

===================
   <DEPLOYING>
===================

I recommend you to use HEROKU
Make your account in HEROKU
Open the Hackathon directory in your terminal and run

    $ git init
    $ git add .
    $ git commit -m "<Your Message>"
    $ heroku login   // login with your account
    $ heroku create  // It will provide you url
    $ git push heroku master

BTW I already deployed it 
LINK:- https://iiitolx.herokuapp.com/

=================================
    <FURTHER IDEAS We can Add>
=================================

1  User can upload pictures rather than copying urls from internet
2  Distribute pages or renting,buying and selling
3  Add notification setting when there is a reply or query
4  Request Page
5  Special page for paid users for other STUFFS // NO PUNS INTENDED
6  Add reply and delete option for replies also

=========================
    <Need of website>
=========================

As you all know BAKUL HONESTY BOX was complete flop.

We can use this site to run same type of service in which
many people can keep different items in their room and sell
it.This will not create burden on a single person and will be
helpful for whole Campus

=========================
   <SPECIAL FEATURES>
=========================

1  Those who are admins can delete and edit any post or query
    // Currenly "Him Agrawal" is the only admin but we can add more according to the need
2  Site supports fuzzy search
3  Compatible for Cellphones too

===================
   <Motivation>
===================

When I came to ken about the 'HackAthon2k20' i decided to make a web application that 
would not only basically be a cognition opportunity for us BUT also something that would actually 
leave our mark on the IIIT community and help the future generations of students who are yet to come here. 
IIIT community for all intents and purposes is one driven by the students. Our seniors before us literally 
had created the ever so helpful mess portal, Felicity website and many other things we can't even contemplate 
living without. Since majority of our team mates were well versed in the ways of web development and rest kind 
of were tyros in both android and web app development domain, I decided to create a web application 
that would tackle a real life problem. This was the humble beginning of our project (^ v ^).



   

