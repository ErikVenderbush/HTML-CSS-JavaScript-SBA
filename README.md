# HTML-CSS-JavaScript-SBA

Submission for HTML/CSS/JS SBA
<br>https://github.com/ErikVenderbush/HTML-CSS-JavaScript-SBA
<br>The basic site layout and design for the Twitch chatbot in preparation for my case study project.

The navigation bar is fixed and present on all pages.
<br>It features the logo which takes you to the home page, navigation (duh), and a "Login with Twitch" button.
<br>The Twitch login icon opens a modal which replicates a normal sign-in and performs a regex validation.
<br>Most pages also feature a footer with external links.

Not all pages will be visible without linking your Twitch account (once I get that sorted).
<br>Those types of pages have a faux Settings/Sign Out dropdown.
<br>Sites always visible will be marked with :earth_americas:
<br>Sites requiring login will be marked with :lock:

- Index :earth_americas:
	- The Welcome/Home page showing off the features of the site and bot.
	- "Connect with Twitch" performs the same function as the Twitch icon, and "Learn More" scrolls down to the
	  features.
	- Feature buttons lead to their respective pages.
- Dashboard :lock:
	- A dashboard to display statistics and info from the connected Twitch channel (currently a placeholder).
	- Has a button that links to my Twitch testing channel.
- Commands :lock:
	- This accordion table is where users will be able create, edit, and delete commands.
	- In addition to the call and response, the permission, cooldown, and enablement can also be customized.
	- Right now it has the layout for some aspects of existing commands to be edited.
- Chat :lock:
	- Currently just an embedded version of chat found on Twitch (so it doesn't load if you launch from a file explorer,
	  use localhost instead).
	- Offers the same full functionality outside of sending messages.
	- Try chatting on [my test channel](https://www.twitch.tv/vendydev) to see the results back on this page (requires
	  Twitch login).
- Guide :earth_americas:
	- Essentially the placeholder until I get the actual functionality of the site sorted.
	- Has a button that links back to here lol.
- About :earth_americas:
	- (TODO) A small summary about the site, bot, and project.
	- (TODO) Includes a "Thank You" section for people and resources of help and support.
	- (TODO) Also features the external links to various related sites.
	- ~Mystery Button~

<br>Thanks for reading!
<br>I hope you enjoy your look around!