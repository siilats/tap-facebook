# Changelog

## meltano.1.1.0
  * [#5] Upgrade to Facebook Marketing API v8 by merging in v1.9.4 of https://github.com/singer-io/tap-facebook

## meltano.1.0.3
  *  [#4](https://gitlab.com/meltano/tap-facebook/issues/4) Update tap-facebook to always transmit STATE messages with all the STATES from the synced streams included. For more info check the related issue.
  *  Fix the example state on README not including the stream states under `bookmarks`


## meltano.1.0.2
  *  [#3](https://gitlab.com/meltano/tap-facebook/issues/3) Update the way `insights_buffer_days` is parsed to allow for a value of `0` and string encoded integers.

## meltano.1.0.1
  *  [#1](https://gitlab.com/meltano/tap-facebook/issues/1) Upgrade tap-facebook to work with Facebook Marketing API v5.0+
  *  Upgrade the `facebook_business` python module to version `5.0.4`
  *  Remove `relevance_score` and `video_10_sec_watched_actions` from all `ads_insights_*` streams as they are no longer supported in the latest version of the Facebook Marketing API.
  *  [#2](https://gitlab.com/meltano/tap-facebook/issues/2) Update Readme with additional info on the various configuration options available

## meltano.1.0.0
  *  Fork version 1.8.2 from https://github.com/singer-io/tap-facebook
