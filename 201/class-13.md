# **Local storage - (Past, Present, and Future)**

### **Local Storage For Web Applications**

Native Client Application:
  - Is one that is installed on a user's computer or device. Examples of such an application include, but is not limited to, WinForms, WPF, Windows Store, Windows Phone, and iOS applications.

* Persistent local storage is one of the areas where native client applications have held an advantage over web applications. 

* For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, **INI** files, **XML** files, or some other place according to platform convention.

*  If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.

### **Cookies**

* **Potential Dealbreaking Downsides:**
  - Cookies are included with every **HTTP** request, thereby slowing down your web application by needlessly transmitting the same data over and over.

  - Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over **SSL**)

  - Cookies are limited to about **4 KB** of data — enough to slow down your application (see above), but not enough to be terribly useful.

* **What we really want:*
  - a lot of storage space.
  - on the client.
  - that persists beyond a page refresh.
  - and isn’t transmitted to the server.

> Before HTML5, all attempts to achieve this were ultimately unsatisfactory in different ways.

## **Local Storage Before HTML5 - (Past)**

* In the beginning, there was only **Internet Explorer**. Or at least, that’s what Microsoft wanted the world to think. To that end,

   * **[userData](https://docs.microsoft.com/en-us/previous-versions//ms531424(v=vs.85)?redirectedfrom=MSDN) Behavior:** 
      - Allows web pages to store up to 64 KB of data per domain, in a hierarchical **XML-based** structure. (Trusted domains, such as intranet sites, can store 10 times that amount.

* In 2002, **Adobe** introduced a feature in Flash 6 that gained the unfortunate and misleading name of **“Flash cookies.”** Within the Flash environment, the feature is properly known as Local Shared Objects. It allows Flash objects to store up to 100 KB of data per domain.  

* By 2006, with the advent of ExternalInterface in **Flash 8**, accessing LSOs from JavaScript with a **Dojo Toolkit** under the moniker `dojox.storage`. Flash gives each domain **100 KB** of storage “for free.” Beyond that, it prompts the user for each order of magnitude increase in data storage (1 Mb, 10 Mb, and so on).

* In 2007, Google launched [Gears](http://gearsblog.blogspot.com/2011/03/stopping-gears.html), an open source browser plugin aimed at providing additional capabilities in browsers.Gears provides an API to an embedded **SQL** database based on `SQLite`. It can store **unlimited** amounts of data per domain in SQL database tables.

* By 2009, `dojox.storage` could auto-detect (and provide a unified interface on top of) Adobe Flash, Gears, Adobe AIR, and an early prototype of HTML5 storage that was only implemented in older versions of Firefox.

> **HTML5** provide a standardized API, implemented natively and consistently in multiple browsers, without having to rely on third-party plugins.


## **HTML5 - (Present)**

* It’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you.

* **“5 megabytes”** is how much storage space each origin gets by default. This is surprisingly consistent across browsers, although it is phrased as no more than a suggestion in the HTML5 Storage specification.


## **Competing Vision - (Future)**

* [Web SQL Database.](https://en.wikipedia.org/wiki/Web_SQL_Database)
* [IndexedDB.]((https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API))

> **At time of writing, IndexedDB has only been implemented in a beta version of Firefox 4. (By contrast, Mozilla has stated that they will never implement Web SQL Database.) Google has stated that they are considering IndexedDB support for Chromium and Google Chrome. And even Microsoft has said that IndexedDB “is a great solution for the web.”**


