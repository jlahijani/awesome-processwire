Awesome ProcessWire
===================

> A curated list of awesome bookmarks, modules, tutorials, videos and other cool resources from the ProcessWire ecosystem.  Maintained by [Jonathan Lahijani](https://jonathanlahijani.com/).

---

- [Official Links](#official-links)
- [Why ProcessWire?](#why-processwire)
- [Important Docs](#important-docs)
- [Staying Up-to-date](#staying-up-to-date)
- [Modules](#modules)
  - [Pro Modules](#pro-modules)
  - [Community Modules](#community-modules)
- [Site Profiles](#site-profiles)
- [Deprecations and Replacements](#deprecations-and-replacements)
  - [Core and Pro Modules](#core-and-pro-modules)
  - [Community Modules](#community-modules-1)
- [Notable People](#notable-people)
- [Frontend Recommendations](#frontend-recommendations)
  - [CSS Frameworks](#css-frameworks)
  - [Libraries](#libraries)
- [Other Links](#other-links)

---

## Official Links
* [ProcessWire Website](https://processwire.com/)
* [ProcessWire GitHub (dev branch)](https://github.com/processwire/processwire/tree/dev)
* [ProcessWire Forum](https://processwire.com/talk/)
* [Docs](https://processwire.com/docs/)
* [API Reference](https://processwire.com/api/ref/)
* [API Cheatsheet](https://cheatsheet.processwire.com/)
* [Blog](https://processwire.com/blog/)
* [ProcessWire Developer Directory](https://directory.processwire.com/): not maintained well / needs work
* [ProcessWire Weekly](https://weekly.pw/)
* [GitHub](https://github.com/processwire)
* [Twitter](https://twitter.com/processwire)
* [Facebook](https://www.facebook.com/groups/265558090161714/)

## Why ProcessWire?
* Free and open-source (an unbelievable value!)
* Uses classic LAMP stack (it still rocks)
* Developed consistently since 2003 (and only getting better)
* Updated **nearly every single Friday** (see the [dev branch](https://github.com/processwire/processwire/tree/dev))
* Fun (and perhaps addictive; seriously I've been using it for over 10 years straight)
* Simple (fields, templates and pages can pretty much do everything)
* Fast (built for speed)
* Secure (a 10 year old, neglected ProcessWire site won't get hacked)
* Developer-oriented (but easy for non-technical users to manage content)
* Unopinionated (do things your way)
* Completely markup agnostic on the frontend (for the OCD people out there)
* Well architected OOP and API (it's a work of art)
* Powerful hook system (modify core functionality with ease)
* Strong data relationships (relate pages with each other)
* Everything is a custom field (no 'metadata' like WordPress)
* Multi-lingual capability (a native feature and why so many non-Americans use it 😊)
* Friendly community (from all parts of the planet)
* Small but high-quality (less is more; for example, one great caching module instead of 347)
* The lead developer is a super human "10x" developer, excellent writer with Cal Ripken-like dedication (rare to find)

## Important Docs
* [$pages](https://processwire.com/api/ref/pages/)
* [$page](https://processwire.com/api/ref/page/)
* [$config](https://processwire.com/docs/start/variables/config/)
* [$files](https://processwire.com/api/ref/wire-file-tools/)
* [$sanitizer](https://processwire.com/api/ref/sanitizer/)
* [Selectors](https://processwire.com/docs/selectors/)
* [Hooks](https://processwire.com/docs/modules/hooks/)
* [Markup Regions](https://processwire.com/docs/front-end/output/markup-regions/)
* [setting() Function](https://processwire.com/api/ref/functions/setting/)
* [datetime() Function](https://processwire.com/api/ref/functions/datetime/)
* [WireHttp class](https://processwire.com/api/ref/wire-http/)

## Staying Up-to-date
Here's a quick guide on how to stay up-to-date with ProcessWire, both in terms of code and community activity:

- Use the [dev branch](https://github.com/processwire/processwire/tree/dev).  Follow the [commitment history](https://github.com/processwire/processwire/commits/dev).
- View the [weekly update posted by Ryan in the forum "News and Announcements" section of the forum](https://processwire.com/talk/forum/7-news-amp-announcements/), generally on Fridays between 12:00pm to 3:00pm PST.  Depending on what's happening in a particular week, the weekly update may include a dedicated blog post.
- View all [latest activity](https://processwire.com/talk/discover/) in the forum.
- Visit [ProcessWire Weekly](https://weekly.pw/) on Saturday/Sunday for the latest post (or register for the newsletter to get it emailed to you 5-6 days after it is initially posted).

## Modules

### Pro Modules

Pro modules are first party modules developed by Ryan Cramer, the lead developer of ProcessWire and help support continued development of the project.  Unlike community modules, Pro modules are downloaded from forum threads after purchasing a license (they cannot be updated from GitHub or the ProcessWire Upgrade module).  The links labeled "Forum Thread / Download" are the direct links to the forum threads which are viewable if you are (a) a forum member and (b) have an active module subscription:

* [ProFields](https://processwire.com/store/pro-fields/): [Forum Thread / Download](https://processwire.com/talk/topic/6413--)
  * Combo
  * Repeater Matrix
  * Table
  * Date Range
  * Verified URL
  * Textareas
  * Multiplier
  * AutoLinks
  * Functional Fields
  * Fieldset Group
  * Text Blocks
* [ProDevTools](https://processwire.com/store/pro-dev-tools/): [Forum Thread / Download](https://processwire.com/talk/topic/14885--)
  * ProfilerPro
  * UserActivity
  * ProcessWire API Explorer
  * WireSitemapXML
  * WireRequestBlocker
  * FormAutosaver
  * PageAutoSave
* [ProCache](https://modules.processwire.com/modules/pro-cache/): [Forum Thread / Download](https://processwire.com/talk/topic/2654--)
* [FormBuilder](https://modules.processwire.com/modules/form-builder/): [Forum Thread / Download](https://processwire.com/talk/topic/1844--)
* [ListerPro](https://processwire.com/store/lister-pro/): [Forum Thread / Download](https://processwire.com/talk/topic/7793--)
* [ProMailer](https://processwire.com/store/pro-mailer/): [Forum Thread / Download](https://processwire.com/talk/topic/21048--)
* [LoginRegisterPro](https://processwire.com/store/login-register-pro/): [Forum Thread / Download](https://processwire.com/talk/topic/22778--)
* [PagesVersionsPro](#): [Forum Thread / Download](https://processwire.com/talk/topic/29357--)
* [ProDrafts](https://processwire.com/store/pro-drafts/): [Forum Thread / Download](https://processwire.com/talk/topic/12195--)
* [Likes](https://processwire.com/talk/store/product/12-likes-fieldtype-dev/)

### Community Modules
* Primary Modules
  * [Tracy Debugger](https://modules.processwire.com/modules/tracy-debugger/): It is **strongly recommended** you install and understand how to use this module.
  * [Hanna Code](https://modules.processwire.com/modules/process-hanna-code/)
  * [ProcessWire Upgrade](https://modules.processwire.com/modules/process-wire-upgrade/)
  * [Database Backups](https://modules.processwire.com/modules/process-database-backups/)
  * [ProcessRedirects](https://processwire.com/modules/process-redirects/)
* Secondary Modules
  * [Dashboard](https://processwire.com/modules/dashboard/)
  * [WireMailSmtp](https://processwire.com/modules/wire-mail-smtp/)
  * [ProcessMediaLister](https://processwire.com/modules/process-media-lister/)
  * [LoginPersist](https://processwire.com/modules/login-persist/)
  * [PrivacyWire](https://processwire.com/modules/privacy-wire/)
* API/JSON
  * [AppApi](https://processwire.com/modules/app-api/)
  * [GraphQL](https://modules.processwire.com/modules/process-graph-ql/)
  * [Pages2JSON](https://github.com/IDT-media/Pages2JSON)
* Fields
  * [Mystique](https://modules.processwire.com/modules/mystique/)
  * [Select File](https://modules.processwire.com/modules/fieldtype-select-file/)
* Multi-lingual
  * [Fluency](https://processwire.com/modules/fluency/)
* Ecommerce
  * [Padloper](https://processwire.com/talk/topic/26944--)
  * [SnipWire](https://github.com/gadgetto/SnipWire)
* Admin Tools
  * [Admin Template Columns](https://modules.processwire.com/modules/admin-template-columns/)
  * [SelectizeAll](https://processwire.com/modules/selectize-all/)
  * [CustomInputfieldDependencies](https://processwire.com/modules/custom-inputfield-dependencies/)


## Site Profiles
When installing ProcessWire, you are only given the option to use the [Blank Site Profile](https://processwire.com/download/site-profiles/#blank-site-profile), which demonstrates a ProcessWire site in its purest, most minimal form.  While this suits the needs for experienced ProcessWire developers looking for a clean starting point, it may be too minimal for those just starting out.

Consider using the [Regular Site Profile](https://processwire.com/download/site-profiles/#regular-site-profile) to get a better idea of how to build a typical website.

If you are creating something more app-like with a strong emphasis on the admin interface, consider studying the [Invoices Site Profile](https://github.com/processwire/site-invoices) which demonstrates the use of Page Classes.

## Deprecations and Replacements
Like any long-running software, certain features have been deprecated and replaced with improved solutions over time.  These include:

### Core and Pro Modules
- [$cache](https://processwire.com/api/ref/wire-cache/) replaces [MarkupCache](https://processwire.com/modules/markup-cache/)
- [$database](https://processwire.com/api/ref/wire-database-p-d-o/) replaces [$db](https://processwire.com/api/ref/database-mysqli/)
- TinyMCE replaces CKEditor [(blog post)](https://processwire.com/blog/posts/using-tinymce-6-in-processwire/)
- PagesVersionsPro will replace (or merge with) ProDrafts [(forum post)](https://processwire.com/talk/topic/29358--/#comment-237891)
- FieldsetGroup is now considered legacy [(forum post)](https://processwire.com/talk/topic/28637--/?do=findComment&comment=233904)

### Community Modules
The following modules are recommended alternatives for similar modules that are no longer maintained:
- [RockShell](https://github.com/baumrock/RockShell) replaces [WireShell](https://github.com/wireshell/wireshell)
- [ProcessRedirects](https://processwire.com/modules/process-redirects/) replaces [Jumplinks](https://github.com/mikerockett/jumplinks)

## Notable People
* [Ryan Cramer](https://processwire.com/about/team/ryan/): Founder and lead ProcessWire developer; [BDFL](https://en.wikipedia.org/wiki/Benevolent_dictator_for_life).
* [Teppo Koivula](https://github.com/teppokoivula): Author of ProcessWire Weekly newsletter and module developer.
* [Robin Sallis](https://github.com/Toutouwai): Author of dozens of useful ProcessWire modules.
* [Adrian Jones](https://github.com/adrianbj): Author of several ProcessWire modules, including the strongly recommended TracyDebugger.
* [Bernhard Baumrock](https://github.com/BernhardBaumrock): Author of several key ProcessWire modules, including RockMigrations, RockFrontend and RockShell.

## Frontend Recommendations

**Keep it simple!** Use a CSS framework combined with Alpine.js and HTMX and you'll have 99% of what you need on the frontend.  Embrace the concept of [HTML Over The Wire](https://signalvnoise.com/svn3/html-over-the-wire/), the modern monolith and consider ditching Node-based solutions for radical simplicity.

### CSS Frameworks
* [UIkit](https://getuikit.com/): CSS framework with JavaScript components
* [Bootstrap](https://getbootstrap.com/): CSS framework with JavaScript components
* [Tailwind CSS](https://tailwindcss.com/): CSS utility framework (no JavaScript components); [Flowbite](https://flowbite.com/) is strongly recommended for the JavaScript components

### Libraries
* [jQuery](https://jquery.com/): JavaScript library (or just use vanilla JavaScript)
* [Alpine.js](https://alpinejs.dev/): Lightweight JavaScript framework
* [HTMX](https://htmx.org/): HTML Over The Wire library
* [Hyperscript](https://hyperscript.org/): JavaScript library that embraces locality of behavior-style development (from the developer of HTMX)

## Other Links
* [ProcessWire Asset Catalog](https://pwgeeks.com/)
* [WordPress vs. ProcessWire](https://www.youtube.com/playlist?list=PLOrdUWNK38ibz8U_5Vq4zSPZfvFKzUuiT): 36 comparison videos