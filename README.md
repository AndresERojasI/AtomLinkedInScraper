##Download the extension!
You can download the latest version of the extension (0.0.2) [here] (https://github.com/socialatom/AtomLinkedInScraper/raw/master/versions/AtomLinkedInScraper-0.0.2.zip)

###How to use it
Before you use it first enable the [developer mode in chrome] (https://developer.chrome.com/extensions/faq#faq-dev-01), to do this follow this instructions.

![Enable Dev Mode](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

After enabling the developer mode, you should unpack the downloaded file (AtomLinkedInScraper-0.0.X.zip) and in the "Extensions" window, load it as an unpacked extension, like this_

![Enable Dev Mode](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Once you add the extension it will automatically add the AtomLinkedInScraper button, where you can write what you are looking for in each candidate, and set some rules to keep in mind:

![Enable Dev Mode](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Also, when you use the search profile it will add the action buttons and once you "Get the profile" it will show you the Candidate rating and you'll be able to select him/her as a candidate:

![Enable Dev Mode](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

After you select the list of candidates you'll be able to download them in an Excel format:

![Enable Dev Mode](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Simply add the extension in developer mode, enable it and run any search on LinkedIn, on each of the results you'll find a set of new buttons to interact with the profile.

![Enable Dev Mode](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")



##How to work with the repo?
This extension is based on the Yeoman Google Chrome extension Generator (https://github.com/yeoman/generator-chrome-extension).

To use this repo, please:

```sh
# Transform updated source written by ES2015 (default option)
gulp babel

# or Using watch to update source continuously
gulp watch

# Make a production version extension
gulp build
```

## Test Chrome Extension

To test, go to: chrome://extensions, enable Developer mode and load app as an unpacked extension.

Need more information about Chrome Extension? Please visit [Google Chrome Extension Development](http://developer.chrome.com/extensions/devguide.html)