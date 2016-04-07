# Android-app launch checklist



This document should be a collaborative effort from the groups. 
The groups must construct and finish the app launch checklist.

Each group will have 3 topics to research and present @ 10.30.

The point of presenting these topics is to involve the students and to better understand the concept when releasing an app on the
Google store.

To find each subject go to http://developer.android.com/distribute/tools/launch-checklist.html and learn more. 

###Group information

* Find 1 group member who is responsible for commiting changes on github.
* Joker = if some students are not attending, jokers can be used for filling in if < 2 group members.
* Any question concerning GitHub contact Mike/Martin.


###Presentation

Each group will have a maximum of 10 minutes to present their subjects. start @ 10.30


###GitHub Pull request by the student who is responsible to commiting changes.

1. fork this repository by clicking on Fork -> http://prntscr.com/aobz1e
2. Next goto https://github.com/yourusername/launchlist and click on the README.MD file
3. click on the pen for edit the file -> http://prntscr.com/aoc3x9
4. add your text and links under your 3 subjects to finish the checklist.
5. when you are done editing click on commmit change -> http://prntscr.com/aoc4an
6. goto pull request and click New pull request -> http://prntscr.com/aoc7gr
7. click the create pull request and add description and then you are done http://prntscr.com/aocxvd

-----

###Group 1

Rene,
Anete,
Thomas

* Understand the Publishing Process
* Understand Google Play Policies and Agreements
* Test for Quality

###Group 2

Christoffer,
Jimmi

* Determine your App’s Content Rating
* Confirm the App's Overall Size
* Confirm the App's Platform and Screen Compatibility Ranges

###Group 3

Hui,
Angel,
Carsten[Joker]*,

* Consider using In-app Billing or Android Pay
* Start Localization
* Prepare Promotional Graphics, Screenshots, and Videos

###Group 4

Kristina
Ron[Joker]*

* Build and Upload the Release-ready APK
* Plan a Beta Release
* Complete the Apps’ Store Listing

###Group 5

Matthias,
Tine,
Theis


* Use Google Play Badges and Links in your Promotional Campaigns
* Final Checks and Publishing
* Support Users after Launch
 




-----




##1. Understand the Publishing Process

Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. The first line of Lorem Ipsum, "Lorem ipsum dolor sit amet..", comes from a line in section 1.10.32.

###Links
http://developer.android.com/tools/publishing/publishing_overview.html
http://developer.android.com/tools/publishing/preparing.html


##2. Understand Google Play Policies and Agreements

###Links

##3. Test for Quality

###Links


##4. Determine your App’s Content Rating

###Links


##5. Confirm the App's Overall Size

###Links


##6. Confirm the App's Platform and Screen Compatibility Ranges

###Links


##7. Consider using In-app Billing or Android Pay
Google Play In-app Billing lets you sell digital content in your applications, ranging from one-time purchases to subscriptions. This can help you to monetize the app over its installed lifetime.

###In-app billing & subscriptions
In-app Billing lets you sell to sell a wide range of digital content, including downloadable content such as media files or photos, virtual content such as game levels or potions, premium services and features, and more. In-app billing can be sold as:
* Standard in-app products (one-time billing), or
* Subscriptions (recurring, automated billing)

Subscriptions let you sell content, services, or features in your app with automated, recurring billing. An existing In-app Billing implementation can easily be adapted to sell subscriptions. You can sell subscriptions to almost any type of digital content, from any type of app or game.

Users can be billed
* Weekly
* Monthly
* 3 months
* 6 months
* Annually
* Seasonal

Any application that you publish through Google Play can implement In-app Billing. No special account or registration is required other than a Google Play Developer Console account and a Google Wallet merchant account.

To help integrate in-app billing, the Android SDK provides a sample application that demonstrates to implement in-app billing.

###Android pay
Android Pay enables simple and secure purchases of physical goods and services in your app, such as clothing, food delivery or movie tickets.

####Read more
* General about In-app billing : http://developer.android.com/google/play/billing/index.html
* Selling In-app Products training class : http://developer.android.com/training/in-app-billing/index.html
* Version 3 API : http://developer.android.com/google/play/billing/api.html
* Testing In-app billing : http://developer.android.com/google/play/billing/billing_testing.html
* General about subscriptions : http://developer.android.com/google/play/billing/billing_subscriptions.html
* Implementing subscriptions : http://developer.android.com/google/play/billing/billing_integrate.html#Subs

##8. Start Localization
With your country targeting in mind, it's a good idea to assess your localization needs, ensure your apps are internationalized, and start the work of localizing well in advance of your target launch date.

Localization involves a variety of tasks throughout your app development cycle, and advance planning is essential. When considering localization, there are at least three aspects you need to consider:
* Localizing the strings, images, and other resources in your apps.
* Localizing your apps’ store listing details on Google Play.
* Localizing the apps’ graphic assets, screenshots, and videos that accompany your store listing.
* 
To localize your store listing, first create and finalize your app title, description, and promotional text. Collect and send all of these for localization. You can optionally translate the "Recent Changes" text for app updates as well. Later you can add your localized listing details in the Developer Console, or you can choose to let Google Play auto-translate your listing details into the languages you support.

In general there are 7 steps that you should go thru for localization of the app

1.	**Identify target languages and locales** : A basic but important step in preparing for localization is identifying the countries where you’ll distribute your apps and the languages spoken there.
2.	**Design for localization** : After you've determined your target languages for localization, assess what you'll need to do to support them in your apps and plan the work early. Consider the vocabulary expansion, script requirements, character spacing and wrapping constraints, left-to-right and right-to-left support, and other potential factors in each language.
3.	**Manage strings for localization** : It's important to manage your apps’ UI strings properly, so that you deliver a great experience for users and make localization straightforward.
4.	**Translate UI strings and other resources** : Translating your apps’ UI strings and resources to your target languages is the key phase of localization, and it's the one that requires the most care and planning.
5.	**Test your localized app** : Once you've received your translated strings and resources and moved them back into your apps, you need to test the apps to make sure that they’re ready for distribution to your international users.
6.	**Prepare for international launch** : Getting your apps translated is a key part of localization, but to help your product attract users and gain visibility, you should prepare for launch in your target countries and create a broader launch and marketing plan for international users.
7.	**Support international users after launch** : After you launch your apps internationally, you should be prepared to support users in a variety of languages and time zones.

####Read more
Google Play distribution & seller countries : https://support.google.com/googleplay/android-developer/table/3541286?rd=1
Localization checklist : http://developer.android.com/distribute/tools/localization-checklist.html


##9. Prepare Promotional Graphics, Screenshots, and Videos
When you publish on Google Play, you can supply a variety of high-quality graphic assets to showcase your app or brand. Screenshots and videos are also very important, because they show how your apps look, how they’re used or played, and what makes them different.

###Possibilities
For your app you have a range of possibilities for promoting your app.
* Screenshots : Add up to 8 screenshots for each supported device (Phone, Tablet, Android TV and Android WE)
* Icon : A high resolution icon is required for the app to be published. It must be a 32-bit PNG (Alpha) sized 512x512px with a maximum file size of 1024kb
* Feature graphic : Your feature graphic is a powerful tool to show off your creative assets and attract users. A feature graphic is required in order to be featured anywhere within Google Play. It must be a JPEG or 24-bit PNG (no alpha) 1024 px by 500 px.
* Promo graphic : This is not required and is used on older versions of Android OS (earlier than 4.0).
* Banner asset (Android TV) : To publish an Android TV-enabled app, a banner asset is required. When you're creating a banner asset, think of it like your app’s icon on Android TV.
* Promo video : The promo video appears in the first position of your graphic assets on the Google Play store. It must be an Youtube video.

###Do’s and don’t’s
Your graphic is not an ad, it’s a teaser. It’s a place for bold, creative promotional images.

Vivid background colors work best. Black and white are problems because those are the backgrounds used by the mobile-device and Web versions of Google Play.

Limit Text to your app name and maybe a few additional descriptive words. Anything else will be unreadable on phones, anyhow.

DO:
* Make the graphic fun and enticing
* Use colors that stand out on black or white backgrounds
* Promote your brand prominently
* Localize your image as needed for different languages

DONT:
* Create a text-heavy advertising-style graphic
* Let the graphic fade into the background
* Overload the graphic with details
* Device imagery is tempting, but becomes dated fast, and may be inappropriate if your user’s device looks entirely different.
* In-app screenshots are inappropriate because your product page already includes a place for these.
* Just using your app icon is a failure of imagination. You have more room; put it to good use!

###Scaling
Your image has to be designed to scale. You can rely on the aspect ratio being constant, but not the size. Try resizing your image down to 1 inch in width. If it still looks good and conveys your brand message, you have a winner.

###Localization
Android's user base is global. Therefor you should provide a separate featured image for each language that you support, as well as separate screenshots and promotional videos.

###Don’t Forget
A 1024 x 500 Featured Image is required for feature placement consideration. Don't miss out on the opportunity!

####Read more
Graphic assets, screenshots & video : https://support.google.com/googleplay/android-developer/answer/1078870
Feature image guidelines : http://android-developers.blogspot.dk/2011/10/android-market-featured-image.html

##10. Build and Upload the Release-ready APK

###Links



##11. Plan a Beta Release

###Links

##12. Complete the Apps’ Store Listing

###Links


##13. Use Google Play Badges and Links in your Promotional Campaigns
Google Play badges give you an officially branded way of promoting your apps to Android users. Use the Google Play Badge generator to quickly create badges to link users to your products from web pages, ads, reviews, and more. You can also use special link formats to link directly to your store listing page, to a list of your products, or to search results. 
### https://play.google.com/intl/en_us/badges/


##14. Final Checks and Publishing
When you think you’re ready to publish, sign in to the Developer Console and take a few moments for a few final checks. 
Here is a few points to be on the lookout for when your publishing your first application!
### http://developer.android.com/distribute/tools/launch-checklist.html#final-checks


##15. Support Users after Launch
After you publish apps or app updates, it's crucial for you to support your customers. Prompt and courteous support can provide a better experience for users that results in better ratings and more positive reviews for your products. Users are likely to be more engaged with your app and recommend it if you’re responsive to their needs and feedback. This is especially true after publishing if you’re using a coordinated promotional campaign. 
### Links
http://developer.android.com/distribute/tools/launch-checklist.html#support-users






