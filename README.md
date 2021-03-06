# Pre-work - Tippy

Tippy is a tip calculator application for iOS.

Submitted by: Allan Chen

Time spent: 5 hours spent in total

## User Stories

The following **required** functionality is complete:

* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [x] Settings page to change the default tip percentage.
* [ ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [x] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [x] Interactive slider for custom tip amounts between 10% and 20%.

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

http://g.recordit.co/zmJTYtDVuz.gif

GIF created with [Recordit](https://recordit.co).

## Notes

I attempted to implement a feature where the tip slider would update based on the currently selected segment as well as be set to a value set under the "Settings" page for a default. However, I encountered an issue where this would disable the user's ability to manually change the slider, else it would crash the app.

## License

    Copyright [2019] [Allan Chen]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
