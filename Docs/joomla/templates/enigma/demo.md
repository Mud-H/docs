---
title: Enigma: Recreating the Demo
description: Your Guide to Recreating Elements of the Enigma Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/Enigma:Enigma

---

Introduction
-----

![][enigma2]

Recreating features of the demo site used to show off some of the more interesting aspects of Enigma can be done fairly easily. All you need is the right extensions and settings, and you should be able to reproduce most (if not all) of the elements found in our demo site. 

Below, we will break down some of these elements and give you the information you need to know to recreate them on your own site using the Enigma Template.

Keep in mind that a lot of the detail that makes our demos look so good are the result of many hours of hard work by our team, and some of them will require a moderate level of experience working with the Joomla back end. We have added most of these elements into the Template's core files in order to make them easily accessible without having to edit any code.

Module Settings
-----

Like any Gantry template, Enigma allows you to assign modules to specific positions within selected overrides. This makes it possible to not only utilize the full power of the Gantry framework, but to make each area of your site uniquely suited to meet your user's needs.

Below, you will find the module placement and settings for the various module positions as they appear on the front page of our demo. Not all of these position assignments are unique to the front page.

![][enigma]

:   1. **RokGallery Showcase**  [13%, 18%, se]
    2. **FP Feature A** [26%, 18%, se]
    3. **FP Feature C** [26%, 63%, se]
    4. **Frontpage Login Form**  [37%, 81%, sw]
    5. **Template Features**  [48%, 81%, sw]
    6. **RocketLauncher Available**  [63%, 81%, sw]
    7. **Template Information** [79%, 19%, se]
    8. **Site Map** [79%, 52%, se]
    9. **Our Location** [84%, 52%, se]
    10. **Connect With Us** [79%, 68%, se]
    11. **Contact Details** [84%, 68%, se]
    12. **Featured Article** [62%, 18%, se]

We have detailed how to recreate the individual modules pictured above in the links below.

1. [RokGallery Showcase][module1]
2. [FP Feature A][module2]
3. [FP Feature C][module3]
4. [Frontpage Login Form][module4]
5. [Template Features][module5]
6. [RocketLauncher Available][module6]
7. [Template Information][module7]
8. [Site Map][module8]
9. [Our Location][module9]
10. [Connect With Us][module10]
11. [Contact Details][module11]
12. [Featured Article][module12]

Recommended Extensions
-----

Here is a list of RocketTheme extensions used to create the demo version of Enigma:

* [Gantry Template Framework][gantry]
* [RokAjaxSearch][rokajaxsearch]
* [RokBox][rokbox]
* RokCommon Library (Installed with RokGallery)
* [RokGallery][rokgallery]
* [RokCandy][rokcandy]
* [RokNavMenu][roknavmenu]
* [RokBooster][rokbooster]

All of these extensions are included with the Enigma RocketLauncher, and can be downloaded and installed individually by going to the RocketTheme website.

Recreating the Front Page
-----

The front page of the Enigma demo sits apart from the rest of the page layouts in that it features the latest and greatest features of the template. It is because of this that several module and layout overrides were done. In this section, we will break down the settings you will need to recreate elements present in the front page of the Enigma template.

Template Settings
-----

The first thing you will need to do in order to set your front page apart as it appears in the demo is to create a style override. This can be done by navigating to **Administrator -> Extensions -> Template Manager** and selecting the template you wish to change.  Once you have checked the box next to the template, you can click the **Duplicate** button to create a second copy of the template. This will become the Override while the primary copy of the template remains the designated Master.

Only options that are different from the Master copy will take hold on the menu items you have assigned to the override. In this case, you will be assigning the front page to the override as we have in the demo.

It would be a good idea for organization to name this override something like **Enigma - Home** as it would be used only for the front page of your site.

#### Assignments

The next step you will need to take in creating your Template Settings override is to assign the Front Page style to the site's home page. Under the **Main Menu** list, you will want to select **Home** in the Menu Assignments tab..

Doing this will assign the style to the home page. This will allow the style to cover all access scenarios that would lead a user to your site's main home page.

You can find more information about the entire override breakdown for both the front page and our default settings in the demo by visiting the [template style portion][demooverride] of this tutorial.

Menu Settings
-----

![][mainmenu]

In your site's main menu, you will want to make a couple of key changes in order for your home page to appear as it does in our demo.

You will need to change the **Page Class** setting under the Home menu **Page Display Options** submenu to `nov11-home`.

[gantry]: http://gantry-framework.org/download
[rokajaxsearch]: http://www.rockettheme.com/extensions-joomla/rokajaxsearch
[rokbox]: http://www.rockettheme.com/extensions-joomla/rokbox
[rokgallery]: http://www.rockettheme.com/extensions-joomla/rokgallery
[enigma]: assets/enigma2.jpeg
[enigma2]: assets/enigma.jpeg
[demooverride]: demo_override.md
[roknavmenu]: http://www.rockettheme.com/extensions-joomla/roknavmenu
[rokbooster]: http://www.rockettheme.com/extensions-joomla/rokbooster
[rokcandy]: http://www.rockettheme.com/extensions-joomla/rokcandy
[module1]: demo_module_1.md
[module2]: demo_module_2.md
[module3]: demo_module_3.md
[module4]: demo_module_4.md
[module5]: demo_module_5.md
[module6]: demo_module_6.md
[module7]: demo_module_7.md
[module8]: demo_module_8.md
[module9]: demo_module_9.md
[module10]: demo_module_10.md
[module11]: demo_module_11.md
[module12]: demo_module_12.md
[module13]: demo_module_13.md
[module14]: demo_module_14.md
[module15]: demo_module_15.md
[mainmenu]: assets/menu_1.jpeg
[icons]: http://fortawesome.github.io/Font-Awesome/icons/
[article]: assets/article.jpg