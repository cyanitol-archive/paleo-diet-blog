=== MM Forms ===
Contributors: tbelmans
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6044941
Tags: forms, email, ajax, captcha, akismet
Requires at least: 2.5
Tested up to: 2.9
Stable tag: trunk

MM Forms is not just another contact form plugin!

== Description ==

<strong>MM Forms is the easy form builder for Wordpress.<br />
Easy, yet not simple.</strong>

MM Forms  comes with the power of a tank, but drives like a bike.<br />
Anyone who has the knowledge to connect to the internet will be able to create web forms with MM Forms.
Sounds easy, right?

But it ain't simple!

MM Forms has some basic features like :<br />
<ul>
<li>field creator</li>
<li>customize form and mail contents with simple markup</li>
<li>html layout possible</li>
<li>Spam filtering with Akismet</li>
<li>captcha prevention</li>
<li>multiple, not to say unlimited contact forms</li>
</ul>

But offcourse it also kicks some ass with the following cunning features : <br />
<ul>
<li>automatic thank you e-mail after a submission</li>
<li>Save form submissions to database</li>
<li>Export to CSV of submissions</li>
<li>RSS feed of form submissions</li>
<li>Send HTML formatted emails</li>
<li>Easy insert forms in posts/pages via TinyMCE button</li>
<li>Add your own customized HTML form code instead of using the build-in field creator, giving you more flexibility and control on form behaviour</li>
</ul>

Derivative work from Contact Form 7, written by Takayuki Miyoshi

== Installation ==

1. Upload whole `mm-forms` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Make following directories writable (chmod 777) /exports/ and /captcha/tmp
4. If you are using WordPress 3.2.x you have to move the files (jquery.js and jquery.form.js) in jquery-update to the wp-includes/js/jquery directory of your WordPress installation 

See also: [plugin homepage](http://plugins.motionmill.com/mm-forms/)

== Frequently Asked Questions ==

How Contact Form can be added in my Theme files (sidebar.php etc)?
You can add your created Contact Form in your Theme files just by calling a very simple function as shown below 
<?php insert_mm_form('Form Name'); ?>

Now for Example you have created a form with the name 'Email Form' then you would have to call the function like as below
<?php insert_mm_form('Email Form'); ?>

If you have questions about MM Forms,
please submit them on our plugins page : http://plugins.motionmill.com/mm-forms/

== Changelog ==
See changelog file

== Licence ==

This plugin is free for everyone! Since it's released under the GPL, you can use it free of charge on your personal or commercial blog.

== Your comments ==

Tell us what you think of this plugin on http://plugins.motionmill.com/mm-forms
