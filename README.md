# WEB102 Prework - *Sea Monster Crowdfunding*

Submitted by: **Joseph Musenge**

**Sea Monster Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **2** hours spent in total

## Required Features

The following **required** functionality is completed:

* [ ] The introduction section explains the background of the company and how many games remain unfunded.
* [ ] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [ ] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [ ] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='./assets/sea_monster_crowdfunding.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with [LiceCap](https://www.cockos.com/licecap/) for Windows


## Notes

Here are some challenges I encountered while working on this project.

1. Challenge: Implementing functions to filter and display funded and unfunded games.
Solution: Created functions (filterUnfundedOnly, filterFundedOnly, showAllGames) to filter and display games based on their funding status.

2. Challenge: Unexpected undefined return value when logging the result of filterUnfundedOnly.
Solution: Modified filterUnfundedOnly to explicitly return the array of unfunded games for better logging.

## License

    Copyright 2024 Joseph Musenge

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
