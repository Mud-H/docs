---
title: Cerulean: Recreating the Demo - Demo Info
description: Your Guide to Recreating Elements of the Cerulean Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/cerulean:Cerulean

---

Demo Info
-----
![][demo]

:   1. **mod_custom** [20%, 7%, se]

We used a **mod_custom** module to make up the content in the **footer-a** position of the front page. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                                                         |  
| :--------- | :-------------------------------------------------------------- |  
| Title      | `Demo Info.  [span class="icon-chevron-down rt-teaser"][/span]` |  
| Show Title | Hide                                                            |  
| Position   | footer-a                                                        |  
| Status     | Published                                                       |  
| Access     | Public                                                          |  
| Language   | All                                                             |  
| Note       | Blank                                                           |  

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
<p>All demo content is for <strong>sample</strong> purposes only, intended to show a live site. All images are licensed from <a href="http://www.shutterstock.com" target="_blank"><strong>ShutterStock</strong></a> for  exclusive use on this <strong>demo</strong> site.</p>

<p>
    <img class="rt-noborder" src="images/rocketlauncher/frontpage/footer/logo-footer.png" alt="Logo" />
</p>
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                                                    |  
| :------------------ | :--------------------------------------------------------- |  
| Module Class Suffix | `nomarginbottom nopaddingbottom nomargintop medpaddingtop` |  

[demo]: assets/demo_9.jpeg
[demo2]: assets/info_1.jpeg
[demo3]: assets/info_2.jpeg
[demo4]: assets/info_3.jpeg
