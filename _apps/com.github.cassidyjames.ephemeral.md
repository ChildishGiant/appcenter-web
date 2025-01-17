---
app_id: com.github.cassidyjames.ephemeral
title: "Ephemeral"
summary: "The always-incognito web browser"
developer: "Cassidy James Blaede"
homepage: https://cassidyjames.com
help_page: https://cassidyjames.com/support
bugtracker: false
dist: hera
screenshots:
  - https://appstream.elementary.io/appcenter/media/bionic/com/github/cassidyjames.ephemeral/9C5F603D43C660EBF594B67AB16FD60E/screenshots/image-1_orig.png
  - https://appstream.elementary.io/appcenter/media/bionic/com/github/cassidyjames.ephemeral/9C5F603D43C660EBF594B67AB16FD60E/screenshots/image-2_orig.png
  - https://appstream.elementary.io/appcenter/media/bionic/com/github/cassidyjames.ephemeral/9C5F603D43C660EBF594B67AB16FD60E/screenshots/image-3_orig.png
  - https://appstream.elementary.io/appcenter/media/bionic/com/github/cassidyjames.ephemeral/9C5F603D43C660EBF594B67AB16FD60E/screenshots/image-4_orig.png
icons:
  "64": https://appstream.elementary.io/appcenter/media/bionic/com/github/cassidyjames.ephemeral/9C5F603D43C660EBF594B67AB16FD60E/icons/64x64/com.github.cassidyjames.ephemeral_com.github.cassidyjames.ephemeral.png
  "128": https://appstream.elementary.io/appcenter/media/bionic/com/github/cassidyjames.ephemeral/9C5F603D43C660EBF594B67AB16FD60E/icons/128x128/com.github.cassidyjames.ephemeral_com.github.cassidyjames.ephemeral.png
  "64@2": https://appstream.elementary.io/appcenter/media/bionic/com/github/cassidyjames.ephemeral/9C5F603D43C660EBF594B67AB16FD60E/icons/64x64@2/com.github.cassidyjames.ephemeral_com.github.cassidyjames.ephemeral.png
color:
  primary: "#3b2a7d"
  primary-text: "#fff"
price: 9
releases:
- version: 7.1.0
  unix-timestamp: 1616630400
  description: |-
    <p>Automatically Open Sites Externally</p>

    <p>You can now always open chosen sites externally, bypassing Ephemeral! On a page, open the &quot;Open page in…&quot; menu and check the new &quot;Automatically Open This Site Externally&quot;. Opening a link to that site will now open in your selected other browser instead of in Ephemeral; super handy for things like Twitter or GitHub where you always want to be logged in. To revert it, just open the site in Ephemeral and uncheck &quot;Automatically Open This Site Externally&quot; from the &quot;Open page in…&quot; menu.</p>

    <p>Improved reliability of setting the window title; the title seen in the Dock menu or Multitasking View should now more reliably match the page&apos;s title, especially when updated with JavaScript.</p>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 7.0.5
  unix-timestamp: 1610668800
  description: |-
    <p>Translation updates</p>

    <ul>

      <li>Translated to Portuguese thanks to Hugo Carvalho</li>

      <li>Updated Dutch translations thanks to Quinten</li>

    </ul>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 7.0.4
  unix-timestamp: 1601510400
  description: |-
    <p>Developers, Developers, Developers!</p>

    <ul>

      <li>Access WebKit Web Inspector and developer tools via Inspect Element</li>

      <li>New hard refresh action (bypassing the cache) with Shift+Ctrl+R</li>

      <li>Support for elementary OS 6, including the dark style preference</li>

      <li>Several new site suggestions</li>

    </ul>

    <p>Translation updates</p>

    <ul>

      <li>Translated to Ukranian thanks to Ihor Hordiichuk</li>

      <li>Updated Brazilian Portuguese translations thanks to Karl Prieb</li>

      <li>Updated Turkish translations thanks to Safak GENISOL</li>

    </ul>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 6.4.1
  unix-timestamp: 1588204800
  description: |-
    <p>Updated Spanish translations thanks to Adolfo Jayme-Barrientos</p>
- version: 6.4.0
  unix-timestamp: 1588118400
  description: |-
    <p>Sandboxing</p>

    <ul>

      <li>Enabled WebKit’s subprocess sandboxing</li>

      <li>Enabled WebKit’s process swapping on cross-site navigation, meaning separate domains are sandboxed from one another</li>

    </ul>

    <p>Search engine changes</p>

    <ul>

      <li>Switched to DuckDuckGo search by default since it supports a dark style</li>

      <li>Enabled strict Safe Browsing by default for DuckDuckGo to avoid unwanted results</li>

      <li>StartPage.com remains an available option in the menu</li>

      <li>Other search engines or configurations can be added under “Custom Search Engine…” in the menu, as always</li>

    </ul>
- version: 6.3.4
  unix-timestamp: 1588032000
  description: |-
    <p>Updated Italian translations thanks to Mirko Brombin</p>
- version: 6.3.3
  unix-timestamp: 1585699200
  description: |-
    <p>Fool me twice…</p>

    <ul>

      <li>Remove sometimes-problematic dark style workaround CSS since it was fixed in WebKit</li>

      <li>Ensure correct browser icon size is set</li>

      <li>Remove dark style toggle when forcing a -dark stylesheet</li>

    </ul>
- version: 6.3.2
  unix-timestamp: 1585267200
  description: |-
    <p>Minor Fixes</p>

    <ul>

      <li>Fix entry selection color when using the light style</li>

      <li>Improve styling on other platforms/stylesheets by being less ambitious</li>

    </ul>
- version: 6.3.1
  unix-timestamp: 1584057600
  description: |-
    <p>Helping Hand</p>

    <ul>

      <li>Suggest turning on &quot;Close when opening externally&quot; if Ephemeral notices you frequently doing it yourself</li>

      <li>Turkish translations thanks to Safak GENISOL</li>

    </ul>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 6.2.1
  unix-timestamp: 1581897600
  description: |-
    <p>Translation updates</p>

    <ul>

      <li>Translation system improved thanks to @NathanBnm</li>

    </ul>
- version: 6.2.0
  unix-timestamp: 1580342400
  description: |-
    <p>Dark Style Rises</p>

    <ul>

      <li>A new toggle lets you choose light or dark style for sites, assuming they support the `prefers-color-scheme` CSS

    query</li>

      <li>Stopped defaulting to dark style by default since it can break some sites</li>

      <li>Set the window title to help distinguish different pages from the dock</li>

      <li>Simplified &quot;Open page in…&quot; menu and logic to always expose all options</li>

    </ul>

    <p>Translation updates</p>

    <ul>

      <li>Updated Dutch translations thanks to Heimen Stoffels</li>

      <li>Updated French translations thanks to @NathanBnm</li>

    </ul>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 6.1.1
  unix-timestamp: 1572912000
  description: |-
    <p>Minor updates</p>

    <ul>

      <li>Fixed checkbox and radio button styling</li>

      <li>Treat “localhost” as a valid domain</li>

      <li>Improved dark styling when building with newer versions of WebKit</li>

      <li>Under the hood changes to make translations easier</li>

      <li>Updated Spanish translations thanks to Adolfo Jayme-Barrientos and @riesp</li>

    </ul>
- version: 6.1.0
  unix-timestamp: 1571270400
  description: |-
    <p>🎉️ Emoji (and international character) support for domains! Punycode means domains like i❤tacos.ws will show up properly in the URL entry, while phishing domains should still show up like xn--80ak6aa92e.com</p>

    <p>Translation updates</p>

    <ul>

      <li>Updated Dutch translations thanks to Heimen Stoffels</li>

    </ul>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 6.0.0
  unix-timestamp: 1570924800
  description: |-
    <p>Adding Some Polish 💅️</p>

    <ul>

      <li>💻️ Touchpad gesture navigation: Use a two-finger swipe to move back or forward through your browsing history</li>

      <li>🔗️ More room for the URL entry to breathe: spacing on each side plus a maximum width means the window is easier to grab and move around</li>

      <li>UI styling fixes, plus dark style fixes for newer versions of WebKit</li>

      <li>Code cleaning to keep things fresh and clean</li>

    </ul>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 5.4.0
  unix-timestamp: 1568678400
  description: |-
    <p>McSipes</p>

    <ul>

      <li>Quickly disable or re-enable JavaScript from the menu</li>

      <li>Use Ctrl+D to add/remove a site from the suggestions</li>

      <li>Find text on the page with Ctrl+F</li>

      <li>New Paste and Go item in the URL bar context menu</li>

    </ul>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 5.3.2
  unix-timestamp: 1568592000
  description: |-
    <p>Translation updates</p>

    <ul>

      <li>Updated Dutch translations thanks to Heimen Stoffels</li>

    </ul>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 5.3.1
  unix-timestamp: 1568332800
  description: |-
    <p>Translation updates</p>

    <ul>

      <li>Updated Italian translations thanks to @meliurwen</li>

      <li>Updated Spanish translations thanks to Adolfo Jayme-Barrientos</li>

    </ul>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 5.3.0
  unix-timestamp: 1567036800
  description: |-
    <p>Hello from Thessaloniki</p>

    <ul>

      <li>Fixed window closing: now closing the first window does not close the rest</li>

      <li>Simplified “Erase” to always close the window instead of sometimes opening a new one</li>

    </ul>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 5.2.1
  unix-timestamp: 1564272000
  description: |-
    <p>Summer cleaning! Because that’s a thing, right?</p>

    <ul>

      <li>Fixed the “Open Link in New Window” menu item to actually do what it says</li>

      <li>Fixed opening target=&quot;_blank&quot; links in a new window with Ctrl- or middle-click</li>

      <li>Updated the base color in menus and dialog windows from the default elementary slate-ish black to a new deep,

    dark blue-ish purple</li>

      <li>Tweaked the “Open Link Externally” dialog to better isolate protocols like “mailto” or “tel”</li>

      <li>Significantly cleaned up and reorganized the codebase to make future features and fixes easier</li>

      <li>Updated Dutch translations thanks to Heimen Stoffels</li>

    </ul>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 5.1.1
  unix-timestamp: 1561334400
  description: |-
    <p>Translation updates</p>

    <ul>

      <li>Updated Catalán and Spanish translations thanks to Mario Rodrigo</li>

      <li>Updated French translations thanks to @NathanBnm</li>

    </ul>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 5.1.0
  unix-timestamp: 1557878400
  description: |-
    <p>Some great UI refinements!</p>

    <ul>

      <li>URL entry suggestions are much snazzier thanks to Hannes Schulze</li>

      <li>JavaScript alerts now follow the elementary HIG thanks to David Hewitt</li>

    </ul>

    <p>Translation updates</p>

    <ul>

      <li>Ciao! Translated to Italian thanks to @meliurwen</li>

      <li>Updated French translations thanks to @NathanBnm</li>

    </ul>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 5.0.3
  unix-timestamp: 1554681600
  description: |-
    <p>Updated Catalan translations thanks to Mario Rodrigo.</p>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 5.0.2
  unix-timestamp: 1554163200
  description: |-
    <p>Minor updates</p>

    <ul>

      <li>Updated Spanish translations thanks to Adolfo Jayme-Barrientos</li>

      <li>Code cleanup</li>

    </ul>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 5.0.1
  unix-timestamp: 1554163200
  description: |-
    <p>Translation updates</p>

    <ul>

      <li>Updated Dutch translations thanks to Heimen Stoffels</li>

      <li>Updated Russian translations thanks to Artem Polishchuk</li>

    </ul>

    <p>Additional translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 5.0.0
  unix-timestamp: 1554076800
  description: |-
    <p>No foolin&apos;. Two major new features:</p>

    <ul>

      <li>🔍️ New Custom Search Engine setting in the Menu</li>

      <li>⭐️ Add your own websites to the suggestions using the new button in the URL entry</li>

    </ul>

    <p>Plus the usual iterative improvements:</p>

    <ul>

      <li>Various URL entry fixes and tweaks</li>

      <li>Updated Dutch translations thanks to Heimen Stoffels</li>

      <li>Updated French translations thanks to @NathanBnm</li>

    </ul>

    <p>Translations for new features will appear in future updates as translators have a chance to do their thing.</p>
- version: 4.2.1
  unix-timestamp: 1553212800
  description: |-
    <p>Translation updates</p>

    <ul>

      <li>Cześć! Translated to Polish thanks to Paweł Jerzy Przybysz</li>

      <li>Updated French translations thanks to @NathanBnm</li>

      <li>Updated Lithuanian translations thanks to @welaq</li>

    </ul>
- version: 4.2.0
  unix-timestamp: 1550880000
  description: |-
    <p>Blaze It</p>

    <ul>

      <li>New option to close the window when opening a page in an external browser</li>

      <li>The web view is now focused when navigating</li>

    </ul>
- version: 4.1.2
  unix-timestamp: 1550793600
  description: |-
    <p>URL Entry Fixes</p>

    <ul>

      <li>Updated and corrected several autocomplete domains</li>

      <li>No longer attempt to force HTTPS on protocol-less domains—fixes several popular sites</li>

      <li>Strip whitespace from URL entry before navigating—fixes instances where trying to navigate to a domain would perform

    a search</li> </ul>
- version: 4.1.1
  unix-timestamp: 1550707200
  description: |-
    <p>URL Suggestion Fixes</p>

    <ul>

      <li>Corrected joinmastodon.org TLD</li>

      <li>Added additional useful sites</li>

      <li>Added descriptions for more sites</li>

      <li>Removed dead sites</li>

      <li>Updated translations</li>

    </ul>
- version: 4.1.0
  unix-timestamp: 1550188800
  description: |-
    <p>All New Search + Suggestions</p>

    <ul>

      <li>The URL entry will offer to complete over 400 popular sites*</li>

      <li>New Search Engine choice in the Menu</li>

      <li>Switched to Startpage.com by default</li>

      <li>Happy birthday, Katie!</li>

    </ul>

    <p>*This data is all shipped with Ephemeral itself, and Ephemeral still does not touch the network until you explicitly navigate somewhere. The list of domains is heavily inspired by a similar feature in Firefox Focus. Domains being included in completion suggestions are not an endorsement, it simply means that domain is relatively popular.</p>
- version: 4.0.4
  unix-timestamp: 1549929600
  description: |-
    <p>Guten Tag! German translations thanks to Hannes Schulze</p>
- version: 4.0.3
  unix-timestamp: 1549324800
  description: |-
    <p>Здравствуйте! Russian translations thanks to Artem Polishchuk</p>
- version: 4.0.2
  unix-timestamp: 1548633600
  description: |-
    <p>More translations:</p>

    <ul>

      <li>Lithuanian translations thanks to @welaq</li>

      <li>Updated Dutch translations thanks to Heimen Stoffels</li>

    </ul>
- version: 4.0.1
  unix-timestamp: 1548547200
  description: |-
    <p>Fixed some missed translations and updated French translations. Thanks again, @NathanBnm!</p>
- version: 4.0.0
  unix-timestamp: 1548201600
  description: |-
    <p>Lots o&apos; goodies:</p>

    <ul>

      <li>The last-used browser is remembered for next time</li>

      <li>New &quot;Reset Preferences&quot; menu item and dialog</li>

      <li>Ctrl+O to open the current page in another browser</li>

      <li>Refined (ever-so-subtly less flat) HeaderBar design</li>

      <li>Ephemeral is now translatable!</li>

    </ul>

    <p>Translations:</p>

    <ul>

      <li>¡Hola! Spanish translations thanks to Adolfo Jayme-Barrientos and Mario Rodrigo</li>

      <li>salut! French translations thanks to Nathan (@NathanBnm)</li>

      <li>Olá! Brazilian Portuguese translations thanks to Lucas Sanchez dos Anjos</li>

      <li>Hallo! Dutch translations thanks to Heimen Stoffels</li>

    </ul>
- version: 3.2.2
  unix-timestamp: 1548115200
  description: |-
    <p>Styling fixes for non-native platforms.</p>
- version: 3.2.1
  unix-timestamp: 1548115200
  description: |-
    <p>Fixed a few small issues with zoom:</p>

    <ul>

      <li>Zoom controls are now only sensitive when the web view is visible</li>

      <li>Reported zoom level is now correct when opening a new window</li>

      <li>Reported zoom level is now kept in sync across open windows</li>

    </ul>
- version: 3.2.0
  unix-timestamp: 1548028800
  description: |-
    <p>Zoom! And more…</p>

    <ul>

      <li>A new menu to keep the UI tidy and balanced</li>

      <li>Zoom in, out, and default from the new menu or with the keyboard</li>

      <li>New Window action moved into the menu</li>

      <li>Added a Quit All Windows action to the menu</li>

      <li>Smooth scrolling when using the keyboard or a scrollwheel</li>

      <li>Fixed Twitch livestreams</li>

      <li>Fixed YouTube resolution support: now up to 4K!</li>

      <li>Code cleaning to keep things fresh and clean</li>

    </ul>
- version: 3.1.0
  unix-timestamp: 1547424000
  description: |-
    <p>Better error handling and quality of life improvements all around:</p>

    <ul>

      <li>New approval dialogs for external apps, e.g. appstream or ftp protocols</li>

      <li>New warning when no network connection</li>

      <li>Prettier errors using native views</li>

      <li>Stopped throwing away text when unfocusing URL entry</li>

      <li>Stopped searching when the URL entry is empty</li>

      <li>Code cleaning to keep things smelling fresh</li>

    </ul>
- version: 3.0.0
  unix-timestamp: 1547251200
  description: |-
    <p>Fresh styles to keep things funky, plus more:</p>

    <ul>

      <li>The new start page makes Ephemeral faster and makes it not touch the network until you&apos;re ready to browse</li>

      <li>Middle- or Ctrl-click a link to open it in a new window</li>

      <li>Displayed URLs are kept in sync for pages that manually update the URL without a page load</li>

      <li>Local HTML files can now be opened</li>

    </ul>
- version: 2.0.1
  unix-timestamp: 1547078400
  description: |-
    <ul>

      <li>More informative &quot;set as default&quot; infobar</li>

      <li>Tweaked &quot;set as default&quot; infobar styling</li>

    </ul>
- version: 2.0.0
  unix-timestamp: 1547078400
  description: |-
    <ul>

      <li>Search from URL entry!</li>

      <li>Asks (politely!) to be set as the default browser</li>

      <li>Open unsupported links (like AppCenter ones) in the OS-default app</li>

    </ul>
- version: 1.2.0
  unix-timestamp: 1546992000
  description: |-
    <ul>

      <li>Add &quot;New Window&quot; to headerbar, app launcher, and keyboard shortcuts</li>

      <li>Collapse external browsers into a menu when there&apos;s more than one</li>

    </ul>
- version: 1.1.0
  unix-timestamp: 1546905600
  description: |-
    <p>Add several useful keyboard and mouse shortcuts</p>
- version: 1.0.1
  unix-timestamp: 1546905600
  description: |-
    <p>Fix links that try to open in a new window</p>
- version: 1.0.0
  unix-timestamp: 1546905600
  description: |-
    <p>Initial release for AppCenter</p>
redirect_from:
  - /com.github.cassidyjames.ephemeral.desktop/
---

<p>Browse the Internet in private without leaving a trace of history on your computer. Ephemeral is a stripped down private browser that&apos;s perfect for avoiding persistent cookies or web trackers. Close the window and all traces of your browsing are removed from your device.</p>
<p>Handy features:</p>
<ul>
  <li>Easily open pages in any other installed browser</li>
  <li>Search right from the URL bar</li>
  <li>Pick between privacy-respecting search engines from the menu</li>
  <li>Quickly disable or re-enable JavaScript from the menu</li>
  <li>Choose to automatically open certain sites in another browser from the &quot;Open page in…&quot; menu</li>
</ul>
<p>Useful keyboard shortcuts and gestures:</p>
<ul>
  <li>Navigate back or forward with a two-finger swipe on your trackpad</li>
  <li>Open page in another browser with Ctrl+O</li>
  <li>Add a website to the URL suggestions with the ⭐️ icon or Ctrl+D</li>
  <li>Find text on the page with Ctrl+F</li>
  <li>Zoom in or out with Ctrl+Plus and Ctrl+Minus</li>
  <li>Open a new window with Ctrl+N</li>
  <li>Hit Ctrl+W to close the current window or Ctrl+Q to quit all windows</li>
</ul>
<p>Ephemeral protects you in five key ways:</p>
<p>1️⃣ Always incognito. From the second you open an Ephemeral window until you close it (or hit the Erase button), Ephemeral is in private browsing mode. That means history, cookies, local storage, passwords, etc. are all blown away as soon as you leave.</p>
<p>2️⃣ Sandboxed. Each window uses a separate instance of the browser engine, domains inside each window are rendered using different processes, and the engine’s processes are sandboxed from one another to keep you safe. Sign into a service in one window, and sites in other windows will have no idea.</p>
<p>3️⃣ No third-party cookies. Ephemeral blocks cookies from third-party sources, which cuts down on advertising cookies and other unwanted forms of cross-site tracking.</p>
<p>4️⃣ No telemetry. Ephemeral does not touch the network until you explicitly load a web page or perform a search. Even then, no usage data is ever collected—I have no idea what you do with Ephemeral, and I don&apos;t want to know!</p>
<p>5️⃣️ Ephemeral uses DuckDuckGo—the search engine that doesn’t track you—by default to avoid as much Google tracking as possible. You can also choose StartPage.com from the menu if that’s your preference, or even set your own entirely custom search engine.</p>
<p>Make privacy a habit by opening links in Ephemeral by default, knowing you can always jump back into a traditional browser like Epiphany, Firefox, Chrome, Opera, Brave—or any other installed browser—with one click. Perfect in case you want to use saved passwords or other extensions.</p>
<p>Remember, Ephemeral and any browser&apos;s incognito or private mode can only do so much: they mitigate some tracking and don&apos;t store data on your device, but they won&apos;t stop your ISP, government, or determined websites from tracking you.</p>
<p>For the best protection, always use a VPN.</p>