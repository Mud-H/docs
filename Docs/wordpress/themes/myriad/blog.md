---
title: Myriad: Recreating the Demo - Blog Page
description: Your Guide to Recreating Elements of the Myriad Demo for WordPress
breadcrumb: /wordpress:WordPress/!themes:Themes/myriad:Myriad

---

Introduction
-----

The **Blog** example page demonstrates how you can create a beautiful page with the Myriad template. Here is some information to help you replicate this page as it appears in the demo.

Theme Override Options
-----

![Override](page_blog_menu.jpeg)

The **Blog** page is a regular **Page**. To recreate the layout the way it appears in our demo, enter `menu-blog` in the **Page Suffix** field in the **Gizmos** page inside the **Myriad** theme settings. This suffix is tied to a class in the demo.less file that sets the page up so it appears the way it does in the demo.

In order for this to work, you should have the **Page Suffix** option set to **On** in **Admin > Myriad > Gizmos**. You will likely need to create a theme override specifically for the page before assigning that suffix to it. For more information on creating theme overrides, visit our [Gantry Documentation](http://gantry-framework.org/documentation/wordpress/configure/).

Mainbody
-----

![Mainbody](page_blog_3.jpeg)

The page's content body is set to display posts in the **Blog** category. The first post is the **Powered by Gantry Framework** article. You will find the content used in the post below.

~~~ .html
<p><span class="rt-image"><img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/pages/blog/img-01.jpg" alt="image" /></span></p>

<p>Collaboratively administrate empowered markets via plug-and-play networks. Dynamically procrastinate B2C users after installed base benefits. Dramatically visualize customer directed convergence without revolutionary ROI.</p>

<p>Efficiently unleash cross-media information without cross-media value. Quickly maximize timely deliverables for real-time schemas. Dramatically maintain clicks-and-mortar solutions without functional solutions.</p>
~~~

Widgets
-----

Below is a brief rundown of the widgets used to make up the demo page. Widgets in the [**Header**](demo_header.md) and [**Copyright**](demo_copyright.md) positions are outlined in the main demo replication area of this guide.

![Widgets](page_blog.jpeg)

:   1. **Showcase - Text** [9%, 45%, se]
    2. **Breadcrumbs** [11%, 15%, se]
    3. **Sidebar - RokAjaxSearch** [13%, 84%, sw]
    4. **Sidebar - Gantry Menu** [19%, 84%, sw]
    5. **Sidebar - Gantry Login Form** [57%, 84%, sw]
    6. **Bottom - Text** [82%, 15%, se]
    7. **Bottom - Text** [82%, 50%, se]
    8. **Blog** [15%, 15%, se]

1. [Showcase - Text](blog.md#showcase-section)
2. [Breadcrumbs](blog.md#breadcrumbs-section)
3. [Sidebar - RokAjaxSearch](blog.md#sidebar-section)
4. [Sidebar - Gantry Menu](blog.md#sidebar-section)
5. [Sidebar - Gantry Login Form](blog.md#sidebar-section)
6. [Bottom - Text](blog.md#extension-section)
7. [Bottom - Text](blog.md#footer-section)
8. [Blog](blog.md#mainbody)

Showcase Section
-----

![Showcase](page_blog_1.jpeg)

Here is the widget breakdown for the Showcase section:

#### Text

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
&nbsp;
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Blog[span class="rt-title-tag"]Read the Latest News[/span]`.
* Switch the **Widget Variations** option to **RT-Center, No Margin All**.
* Enter `rt-title-large rt-nomodulecontent rt-top-large-padding` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

Breadcrumbs Section
-----

![Breadcrumbs](assets/page_blog_2.jpeg)

#### Gantry Breadcrumbs

The **Gantry Breadcrumbs** widget gives you the ability to present page-aware breadcrumbs on the page. All you need to do to add them is to drag the **Gantry Breadcrumbs** widget from the **Available Widgets** area to the **Breadcrumbs** widget position.

Sidebar Section
-----

![Sidebar](assets/page_blog_4.jpeg)

:   1. **RokAjaxSearch** [6%, 18%, se]
    2. **Gantry Menu** [13%, 18%, se]
    3. **Gantry Login Form** [77%, 18%, se]

Here is the widget breakdown for the Breadcrumbs section:

* RokAjaxSearch
* Gantry Menu
* Gantry Login Form

#### RokAjaxSearch

The RokAjaxSearch widget allows users to search your site for interesting content. Here is a breakdown of the options you will want to change to match the demo.

* Enter `Search the Blog` in the **Title** field.
* Set the **Widget Variations** to **Box 3, Title 1**.
* Leaving everything else at its default setting, select **Save**.

#### Gantry Menu

The Gantry Menu widget should be set to match your site's main menu as it serves as the primary menu widget for the entire site. You can customize this menu by navigating to **Administration -> Appearance -> Menus** and creating or modifying your selected menu there.

Here is a breakdown of the widget options for this menu widget. Any options not present in this breakdown are left at default and should not be adjusted.

| Option            | Setting        |
| :----------       | :----------    |
| Title             | `Site Menu`    |
| Menu              | Main Menu      |
| Menu Theme        | Split-Menu     |
| SplitMenu Style   | Sidebar Menu   |
| Limit Levels      | Yes            |
| Start Level       | 0              |
| End Level         | 1              |
| Show All Children | Yes            |
| Show Empty Menu   | No             |
| Maximum Depth     | 10             |
| Widget Variations | Box 2, Title 3 |

#### Gantry Login Form

The login form located in this area of the page is actually a **Gantry Login Form** widget. Here are the widget options you will need to change in order to match the demo.

| Option            | Setting        |
| :----------       | :----------    |
| Title             | `Login Form`   |
| User Greeting     | `Hi,`          |
| Pre-text          | Blank          |
| Post-text         | Blank          |
| Widget Variations | Box 4, Title 4 |

Bottom Section
-----

![Bottom](assets/page_aboutus_7.jpeg)

:   1. **Text 1** [20%, 5%, se]
    2. **Text 2** [20%, 52%, se]

#### Text 1

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p class="hidden-phone">These examples are intended to show how Myriad can be constructed on your site, above and beyond the frontpage demonstration. These include WordPress content with varying widgetized content, mainbody widths and page lengths.</p>

<p class="nomarginbottom">All demo content is for sample purpose only, intended to show a live site. Use the <a href="http://www.rockettheme.com/wordpress/themes/myriad">Myriad RocketLauncher</a> to install an equivalent of the demo onto your site.</p>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Myriad Demo`.
* Enter `rt-phone-center` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.

#### Text 2

This section of the page is a standard text widget. You will need to enter the following in the main text field.

~~~ .html
<p>Completely synergize resource sucking relationships via premier niche markets. Professionally cultivate one-to-one customer service with robust ideas.</p>

<div class="gantry-width-container">
    <div class="gantry-width-40">
        <div class="gantry-width-spacer">
            <img src="http://demo.rockettheme.com/live/wordpress/myriad/wp-content/rockettheme/rt_myriad_wp/pages/pages-overview/logo.png" alt="image" />
        </div>  
    </div>

    <div class="gantry-width-60">
        <div class="gantry-width-spacer">
            <span class="rt-intro-text">+1(123)456-5555-555</span><br />
            <span>Myriad Theme, LLC</span><br />
            <span>123 WordPress Boulevard</span><br />
            <span>Seattle, WA 00000, USA</span><br />
            <span><a href="#">noreply@domain.com</a></span>
        </div>
    </div>
</div>
<div class="clear"></div>
~~~

Here is a breakdown of options changes you will want to make to match the demo.

* Set the **Title** to `Sample Contact Info`.
* Enter `rt-phone-center` in the **Custom Variations** field.
* Leaving everything else at its default setting, select **Save**.
