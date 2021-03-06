# SbeamRSS
[![CodeFactor](https://www.codefactor.io/repository/github/sbeam-dev/sbeamrss/badge)](https://www.codefactor.io/repository/github/sbeam-dev/sbeamrss)![releases](https://img.shields.io/github/v/release/sbeam-dev/SbeamRSS?include_prereleases)

An Android RSS reader based on flutter.

In early development state.

[Documentation](https://github.com/sbeam-dev/SbeamRSS/blob/master/Docs.md)

## We launched at Play Store!

<a href='https://play.google.com/store/apps/details?id=dev.sbeam.rss&pcampaignid=pcampaignidMKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png' height=80/></a>

Alpha testing versions will be released in the github release page.

## Features

During the first stage of development, the app will be working full offline(relys fully on local device to pull updates and store data). In the future, cloud integration and push notifications might be implemented.

### To-dos

  - [x] Subscription source management
  - [x] Feed pull and storage
  - [x] UI for reading feed articles
  - [x] Frontend refinement and theming
  - [x] Put on Beta testing
  - [ ] Feed filtering
  - [x] Search articles
  - [x] Favorite articles
  - [ ] Advanced filter options when viewing the feeds list
  - [ ] Optimization for tablets

## Known Defects

+ Text can't be selected in reading page. Waiting for the flutter_html package to implement this feature.
+ The Scrollbar in reading page can't be updated instantly. It's a workaround to avoid severe performance issue.
+ If you have other suggestions, feel free to open an issue!

## Some technical detail

We use the latest stable branch of flutter(1.17). The used pub packages can be found in `pubspecs.yaml`. Pull requests are welcomed.