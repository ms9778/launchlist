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

When you publish an app, you mainly do two things

You prepare the application for release
        - Build a release version of your app, wich users can download and install.

You release the application to users
        - You publish, sell and destribute the release version

Normaly you publish your app through Google Play, but you can publish it by sending it via email or directly to a phone. 
(Big companies could have a monthly newsletter, where you can attach APK file)

The publishing process


Preparing the app for release
Configure the app for release
        - Remove log calls
        - Remove Android:Debuggable attribute from manifest file
        - Provide values for Android:VersionCode and Android:VersionName attributes,   also located in manifest file
        - You might have to configure several other settings to meet Google Play requirements.

Build and signing a release version of your app


###Links
http://developer.android.com/tools/publishing/publishing_overview.html
http://developer.android.com/tools/publishing/preparing.html


##2. Understand Google Play Policies and Agreements

Policies:
* Sexually Explicit Content
* Child Endangerment
* (Realistic) Violence
* Bullying and Harassment
* Lack of safeguards for UGC
* Hate Speech (Racism)
* Sensitive Events
* Gambling (Real Money)
* Illegal Activities




###Links

https://play.google.com/about/restricted-content.html#illegal-activities
https://play.google.com/intl/ALL_us/about/developer-distribution-agreement.html

##3. Test for Quality

Every app that gets published to Google Play is expected to meet certain quality criteria. Failing to do so would mean that users could become unsatisfied with the product and decide not to use it. But while the quality test is advised, it’s not necessary in order to get your app published. It’s just a good idea for the developer to make sure the app meets all the criteria in order to keep the customer satisfied with the end product.

For instance, some of the criteria to meet are things like “not repurposing common icons for some other task than the standard” and “to only ask for the minimum amount of permissions”. Things that seem obvious at first hand, but could be obscured during development.

Setting up testing environments for your app is a good idea to ensure it works across al available devices on the market. You can’t test on every single device available, but a small select group of the most commonly used phones would be more than enough to make sure it works on the majority of the market. If it isn’t possible to acquire the hardware, emulators can serve as an acceptable substitute.

StrictMode is a mode used for high performance testing, to see whether or not the app has detrimental effects on other apps if running in the background and so on. It is advised to test this at least a few times before publishing.


###Links

http://developer.android.com/distribute/essentials/quality/core.html 

##4. Determine your App’s Content Rating

Google Play use four content rating levels:

- Everyone
- Low maturity
- Medium maturity
- High maturity

These ratings are used to inform the users about the contents maturity level, and will block or filter content in regions where this is required.
To classify your apps rating level it is possible to take a survey in the Google developer console.
You can assign (or change) the content rating for your apps in the Developer Console.

- It is important to answer correct and truthfully on the survey as a misleading describtion or rating can result in removal of your app.

###Links
https://play.google.com/apps/publish/signup/


##5. Confirm the App's Overall Size

The max size for an APK published on Google Play is 100 MB. If your app exceeds that size, or if you want to offer a secondary download, you can use APK Expansion Files, which Google Play will host for free on its server infrastructure and automatically handle the download to devices.

You can use up to two (2) APK Expansion Files, each up to 2GB in size, for each APK.
Using APK Expansion files is a convenient, cost-effective method of distributing large apps. However, the use of APK Expansion Files requires some changes in your app binary, so you will need to make those changes before creating your release-ready APK.

The expansion files are saved to the device's shared storage location (the SD card or USB-mountable partition; also known as the "external" storage) where your app can access them. On most devices, Google Play downloads the expansion file(s) at the same time it downloads the APK, so your application has everything it needs when the user opens it for the first time. In some cases, however, your application must download the files from Google Play when your application starts.

###Links
http://developer.android.com/google/play/expansion-files.html

##6. Confirm the App's Platform and Screen Compatibility Ranges

Ionic handles this by default using cordovas platform api.
However it is possible to change the default settings in the config.xml file located in the Ionic project folder


###Links
http://ionicframework.com/docs/guide/publishing.html

http://cordova.apache.org/docs/en/latest/config_ref/index.html

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

To be able to upload your application to the Google Play marketplace, you'll need to export it as an **APK (Android Package)** file.

This can be achieved by using Android Studio's build in function **"Generate Signed APK"**. Just like in Windows we have an .exe file, in Android we have an .apk file for running the application, so Google Play needs a file to distribute. Android requires that all apps be digitally signed with a certificate before they can be installed; therefore, your application will require a release key generated in the export process - you define it in the **"New Key Store"** section. 

This preparation process, as well as the cleanup and optimization of your code, is a required development task and is the first step in publishing your application. 

###Links
* http://www.tutorialspoint.com/android/android_publishing_application.htm
* http://developer.android.com/tools/publishing/app-signing.html#overview
* http://developer.android.com/tools/publishing/preparing.html


##11. Plan a Beta Release

Testing of your application helps to ensure that your application runs properly under realistic device and network conditions, while gathering suggestions on improvements and bugs. Google Play provides secure means to do that in its **Developer Console**, but for a feedback mechanism, you'll need to consider integrating it yourself or using Google Forums. 

The key to a successful beta test is finding the people to with the right knowledge that are committed to the product and still being able to monitor their every move. Google offers a beta testing tool for getting as much feedback as possible, but you can consider different platforms, like TestFlight, Crashyltics Beta, HockeyApp with different analytic features. 

###Links
* https://www.quora.com/What-are-some-strategies-for-beta-testing-an-app-that-will-be-paid-when-released
* http://blog.instabug.com/2015/07/the-beginners-guide-for-beta-testing-your-app/

##12. Complete the Apps’ Store Listing

Google Play displays your product information in a store listing page, here the users learn more about your apps and decide whether to purchase or download it. The page can hold colorful graphics, screenshots, and videos to descriptions, release details, catrgory keywords, and links to your other apps.

###Links
* http://www.apptamin.com/blog/optimize-play-store-app/

##13. Use Google Play Badges and Links in your Promotional Campaigns
Google Play badges give you an officially branded way of promoting your apps to Android users. Use the Google Play Badge generator to quickly create badges to link users to your products from web pages, ads, reviews, and more. You can also use special link formats to link directly to your store listing page, to a list of your products, or to search results. 
### Links
https://play.google.com/intl/en_us/badges/


##14. Final Checks and Publishing
When you think you’re ready to publish, sign in to the Developer Console and take a few moments for a few final checks. 
Here is a few points to be on the lookout for when your publishing your first application!
### Links
http://developer.android.com/distribute/tools/launch-checklist.html#final-checks


##15. Support Users after Launch
After you publish apps or app updates, it's crucial for you to support your customers. Prompt and courteous support can provide a better experience for users that results in better ratings and more positive reviews for your products. Users are likely to be more engaged with your app and recommend it if you’re responsive to their needs and feedback. This is especially true after publishing if you’re using a coordinated promotional campaign. 
### Links
http://developer.android.com/distribute/tools/launch-checklist.html#support-users






