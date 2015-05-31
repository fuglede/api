# Version 1

This version is available at **http://www.speedrun.com/api/v1**.

:warning: **Version 1 is not yet stable and can change at any time.** :warning:

## Basics

* All dates and times are ISO 8601 encoded. Durations (like run times) use both ISO 8601 as well as
  the number of seconds and milliseconds (use whatever is convenient for you).
* In most responses, the JSON structure contains a ``data`` key as its root element. This ``data``
  element is omitted from the sample JSONs on this page.

## Resources

This version offers access to the following resources:

* [Games](games.md), including their levels, categories and custom variables
* [Platforms](platforms.md)
* [Regions](regions.md)
* [Runs](runs.md)
* [Users](users.md)

**Important:** To get a leaderboard of sorts, you need to use the legacy API available at
http://www.speedrun.com/api_records.php, until we had time to refactor and implement the leaderboard
as part of this API.