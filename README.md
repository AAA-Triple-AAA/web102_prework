# WEB102 Prework - Triple A's Sea Monster Crowdfunding

Submitted by: **Adrian Abella Acosta**

**Triple A's Sea Monster Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **4** hours spent in total

## Required Features

The following **required** functionality is completed:

-   [x] The introduction section explains the background of the company and how many games remain unfunded.
-   [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
-   [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
-   [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

-   [x] Added a feature where whenever a game card is hovered over, a progress bar is shown with the total amount the game has raised and in text, and the bar showing the progress the crowdfunding campaign has towards its goal. If it has met or exceeded that goal, the bar is completely filled. This was an important addition since the user has no information as to the level to which a game is funded, only whether it is fully funded or not. It also displays the absolute dollar amount a game has been funded which was a piece of information not found previously at all.

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src="assets/VideoWalkthrough.gif" title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->

GIF created with LICEcap

<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

-   Got stuck on the reduce functions for a while due to missing the default value
    as the second argument.
-   In developing the progress bar, a lot of tinkering had to be done with the styling in order to achieve the proper look.
-   Because the game cards are removed and refreshed with every filter, so too did the event listeners on each of those cards, as a result I added the even listeners for the cards in a function that is executed at the end of every filter function.
-   IMGUR link to GIF for video walkthrough was not showing in GitHub
    view of README.md, so I added the GIF to the assets folder and linked to it.

## License

    Copyright 2024 Adrian Abella Acosta

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
