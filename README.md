**Building a Chrome Extension**

Chrome Extensions are generally used to make your life easier, adding functionality within your browser or a website that currently doesn't exist. For example, the Gmail Checker chrome extension is something I use every day. It simply checks how many emails I have unread in my inbox, displays that number and if I click on the icon (called a 'browser action' in Chrome-speak) it takes me to my inbox.

The awesome thing about Chrome Extensions is that they are built using the tools a front-end developer are already familiar with: HTML, CSS and JavaScript.

_Insert Paragraph in which I explain which Chrome Extension I'm making_

The first file I created to make my chrome extension was the 'manifest.json' file. This is a description of your chrome extension using the JSON format and includes things like the version number of your extension, it's name and description as well as some more important things such as the websites that your extension are able to access.

_Insert example of manifest.json here_

_Insert explanation of what my manifest.json is doing here_

_Insert possible explanation on why we're using manifest_version '2' here_
Basically, version one is deprecated.
See: https://developer.chrome.com/extensions/manifestVersion

_Icon is 19*19px file_ _Point to link to make cool icons, maybe Jenn's 8bitart if I can find out if it will work like that_

**A HTML file and a JavaScript file walk into a bar...**


_How do I get my Chrome Extension Working / How do I test it?_
Never fear, you can load it into your browser.

_How do I share it with others?_
Putting shit in the Chrome Webstore.
https://developer.chrome.com/webstore/get_started_simple
