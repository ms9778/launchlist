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

https://play.google.com/about/restricted-content.html#illegal-activities, https://play.google.com/intl/ALL_us/about/developer-distribution-agreement.html

##3. Test for Quality

Every app that gets published to Google Play is expected to meet certain quality criteria. Failing to do so would mean that users could become unsatisfied with the product and decide not to use it. But while the quality test is advised, it’s not necessary in order to get your app published. It’s just a good idea for the developer to make sure the app meets all the criteria in order to keep the customer satisfied with the end product.

For instance, some of the criteria to meet are things like “not repurposing common icons for some other task than the standard” and “to only ask for the minimum amount of permissions”. Things that seem obvious at first hand, but could be obscured during development.

Setting up testing environments for your app is a good idea to ensure it works across al available devices on the market. You can’t test on every single device available, but a small select group of the most commonly used phones would be more than enough to make sure it works on the majority of the market. If it isn’t possible to acquire the hardware, emulators can serve as an acceptable substitute.

StrictMode is a mode used for high performance testing, to see whether or not the app has detrimental effects on other apps if running in the background and so on. It is advised to test this at least a few times before publishing.


###Links

http://developer.android.com/distribute/essentials/quality/core.html 

##4. Determine your App’s Content Rating

###Links


##5. Confirm the App's Overall Size

###Links


##6. Confirm the App's Platform and Screen Compatibility Ranges

###Links


##7. Consider using In-app Billing or Android Pay

###Links



##8. Start Localization

###Links


##9. Prepare Promotional Graphics, Screenshots, and Videos

###Links


##10. Build and Upload the Release-ready APK

###Links



##11. Plan a Beta Release

###Links

##12. Complete the Apps’ Store Listing

###Links


##13. Use Google Play Badges and Links in your Promotional Campaigns

###Links


##14. Final Checks and Publishing

###Links


##15. Support Users after Launch

###Links






