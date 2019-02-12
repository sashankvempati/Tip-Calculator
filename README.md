# Pre-work - *Tip Calculator*

**Tip Calculator** is a tip calculator application for iOS.

Submitted by: **Sashank Vempati**

Time spent: **10-12** hours spent in total

## User Stories

The following **required** functionality is complete:

* [ Yes] User can enter a bill amount, choose a tip percentage, and see the tip and total values.

The following **optional** features are implemented:
* [Yes ] Settings page to change the default tip percentage.
* [Yes ] UI animations
* [Yes ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [ ] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

  * I have included a slider in the settings menu of my app for how many people would be paying the bill. Based on this, 
    The bill can be split based on how many people there are and could pay an equal share of the total bill, including the tip.

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='http://g.recordit.co/ihzQICtOd3.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [Recordit.co](http://g.recordit.co/ihzQICtOd3.gif).

## Notes

Describe any challenges encountered while building the app.

One of the biggest issues I faced was that as I was creating my app, I encountered an NSException Error and the SIGABRT issue.
This happens whenever I click on the settings button on the navigation bar. What made this problem even more challenging is 
that I had removed my latest code I wrote in order to see what the problem was, but even then, the SIGABRT still kept happening.
This, along with the unclear messages that the program sends me, had made it very challenging to resolve. 


## License

    Copyright [2019] [Sashank Vempati]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
