# Reamde -- DDSM-plugin
A Dead's Man Switch for Wordpress 

----
## Usage

### Why this plugin ?
 It handles what happens after we die. It monitors your own visits to your wordpress system, and will send you a warning email after a number of weeks (of your choice) without a visit. If you fail to visit your blog even after that, the system will send a mail you wrote to whoever you choose.

All time intervals and messages are customizable.
 
The plugin will at the same time publish a page that you'd saved as a draft as your new frontpage - if you want to - so that your readers will know something happened to you.

This should be used to have someone keep your blog on the air in the unfortunate case of something mishappening to you.
 
This plugin is also useful for those that want their blog to out-live them, and serve as an online memorial. Even without use of this plugin, all are recommended to make sure someone can handle their website in case of emergency.

### Installation
A classical Wordpress plugin... upload the zip file, go to plugins -> Add Plugin, and that's it.

----
### Activation

* After installation, and the plugin activation, just check in the box.
* The plugin then activates if you _do not connect_ to your blog account. 

----
### Set up and usage
1. Check that your email is correct
2. Update the text of the reminders - mails that will be sent to you or anyone you want. Keep in mind there are 4 series of emails. 
3. On the last shipment of mails, when you have presumably been away too long from your 

----
##FAQ
 

**Shall I keep my passwords in the mails to be sent?**
> No. Definitely no.

**Why do I need to use a plugin like this? I'm going to live for ever!**
> No, you're not.

**I got a warning email, what do I do?**
> Go to your options panel, and hit Reset.

**Does this count only visits to my dashboard, or will it know me when I visit the blog?**
> Every visit to your wordpress system, blog or dashboard, count, as long as you're logged in.

**What if I just don't care much for my blog, and visit it only once every few months?**
> First, you can set the time intervals, up to 30 weeks before the system assumes you're no longer. Secondly, maybe this plugin is not for you. The idea behind this plugin is that we visit our blogs daily, if not hourly, so if something happens to you, the blog will be the first to feel it.

** I'm not using this plugin because I'm afraid my mother will get a false email from me saying I'm dead!**
> The system will first send you a warning email after a default time period of two weeks without a visit. A week later it will send you another warning, and also a warning to your chosen next of kin, whom you can ask to contact you and tell you to go in and reset. only after these two time periods, will the plugin allow itself to assume the worst.

**How do I know when the trigger will trigger ?**
> You'll know (if still opening your mail) that you haven't been connecting to your wordpress platform as you will receive a mail stating that you haven't.

** How can I know this will work?**
> If you're eager to test this before it matters, edit nextofkin.php: line 45 states the number of seconds in a week. If you change this to 300, then the time intervals will be five minutes worth, instead of a week. Enter an email address of your own as the second recepient (If you only have one, try using a mytrashmail.com address), and don't access your blog for a short while. Note - somebody needs to access your blog for the mails to be sent, but with search robots and spam bots, it shouldn't take long. After you finish testing, fix line 45 to its inital value (7 * 24 * 60 * 60 = 604800) and hit Reset in the options panel.


----
## Work in progress

_ To be updated, the V01 just got released so far =) _

----
## Contact
----
### Who ?
A plugin done for and by digitaldeathguide.com
More information on digitaldeathguide.com/ddsm/ or contact at ddsm@digitaldeathguide.com
----
## Contribute ?

+ Send a donation? Always appreciated 
+ Send a quick message
+ Give your opinions about the plugin
+ Drop me a line!
+ Thanks to Tzafrir for letting us resume his work =) 
http://tzafrir.net/nextofkin/