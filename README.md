# Chrome Apps for Rails

![Chrome Apps logo](images/chrome_apps.png)

## Installation

### 1. Clone this repository and see its contents.
Open a terminal give the following command:

```bash
$ git clone https://github.com/enogrob/chromeapps-rails.git
```

As we can see a subdirectory is created for each Rails app.

```bash
drwxr-xr-x@  10 enogrob  staff    340 Oct  3 16:42 .
drwxr-xr-x@ 296 enogrob  staff  10064 Oct  3 02:38 ..
-rw-r--r--@   1 enogrob  staff  12292 Sep 24  2017 .DS_Store
drwxr-xr-x   14 enogrob  staff    476 Dec 17  2016 .git
-rw-r--r--    1 enogrob  staff      5 May 31  2016 .gitignore
drwxr-xr-x   10 enogrob  staff    340 Nov 17  2016 .idea
-rw-r--r--@   1 enogrob  staff      0 Nov 17  2016 Icon?
-rw-r--r--@   1 enogrob  staff   1823 Oct  3 16:49 README.md
drwxr-xr-x   19 enogrob  staff    646 Oct  3 16:43 apps
drwxr-xr-x    4 enogrob  staff    136 Oct  3 16:47 images

$ tree -L 1 apps/
apps
├── Rails-API
├── Rails-BoringRails
├── Rails-CBRA
├── Rails-EverydayRails
├── Rails-Homepage
├── Rails-MiniTest
├── Rails-OpenSourceRails
├── Rails-RSpec
├── Rails-RailsBytes
├── Rails-RailsDiscuss
├── Rails-RailsGuides
├── Rails-RailsWikipedia
├── Rails-RubyOnRailsBosnia
├── Rails-RubyOnRailsPodcast
├── Rails-StimulusReflex
├── Rails-Trailblazer
└── Rails-Webpack

17 directories, 0 file
$
```

### 2. Open Chrome with the following url:
In order to load the `Chrome Apps` for Eicon, check `Developer Mode` and press `Load unpacked extension...` to load each App selecting its corresponding directory inside `apps` e.g. `Rails-Homepage`, and then repeat that for the wanted apps.

```
chrome://extensions/
```

### 3. After load the Chrome Apps wanted for Rails, Chrome will look like the screenshot below:

![Chrome screenshot](images/chrome_screenshot1.png)