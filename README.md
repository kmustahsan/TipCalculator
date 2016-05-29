# TipCalculator
A Simple Tip Calculator for iOS


## User Stories

The following **features**  are implemented:
* [X] User can enter a bill amount, choose a tip percentage, and see the tip and total values.
* [X] Settings page to change the default tip percentage<sup name="a2">[2](#f2)</sup>.
* [X] UI animations
* [X] Remembering the bill amount across app restarts (if <10mins)<sup name="a3">[3](#f3)</sup>
* [X] Using locale-specific currency and currency thousands separators<sup name="a4">[4](#f4)</sup>.
* [X] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.
* [X] **Feelin' `tipsy`? Shake your device to get a random tip amount!**
* [X] Using geolocation-specific currency. Uses GPS tracking (**harnessing iOS Location Services API**) for user's current location to determine the local currency type. #VacationMode !
* [X] **Universal app.** Compatible with all device types and sizes. Using **size classes and constraints** for every UI element and every view controller including Startup Screen view.
* [X] **Slider** to change the Tip amount! Using constraints programmatically to **make UILabel follow the UISlider** as you change the tip amount.
* [X] Split the bill with up to 10 people. Use a **UIStepper** to specify the number of people in the party.
* [X] SettingsViewController has **switches**. UISwitch events interact with each other and enable/disable each other.
* [X] Integration with iOS Settings app (iOS Settings Bundle)
* [X] Dedicated icons for Spotlight.
* [X] App icons for every device type and size.
* [X] Startup Screen for every device type and size.


## Video Walkthrough 

#### Here's a walkthrough of implemented user stories on an *iPhone*:
<img src='http://i.imgur.com/W3dAC4d.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />




GIFs created with [LiceCap](http://www.cockos.com/licecap/).

