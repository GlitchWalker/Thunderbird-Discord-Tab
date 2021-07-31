# Google Messages Tab
Unofficial Google Messages add-on for Thunderbird, it adds a button that opens a Google Messages tab in Thunderbird.
Go to [Thunderbird Add-ons page](https://addons.thunderbird.net/thunderbird/addon/google-messages-tab) for download and reviews.

#### Installing 
Open Thunderbird, go to Tools -> Add-ons -> Extensions, search for Google Messages in the search box and click on "+ Add to Thunderbird".

#### Installing from sources
Download the repository, zip it, rename it to Google-Messages-Tab.xpi and choose install addon from file in Thunderbird.

In linux the xpi file can be created with the following commands
* `git clone https://github.com/sigurd-dev/Thunderbird-Google-Messages-Tab`
* `cd ./Thunderbird-Google-Messages-Tab`
* `VERSION=$(cat ./manifest.json | jq --raw-output '.version')`
* `zip -r "../Google-Messages-Tab-${VERSION}-tb.xpi" *`

This is really just a "rip off" of the [Google Keep Tab](https://github.com/Garoe/Thunderbird-Google-Keep-Tab)
where links and icon were changed.
