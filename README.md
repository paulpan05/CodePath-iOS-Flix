## Flix Part 2

**Flix** is a movies scroll view made by fetching data remotely.

Submitted by: **Junhong Pan (Paul)**

Time spent: **5** hours spent in total

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [x] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF

<img src="ezgif-6-baf35426f822.gif" width=250><br>

GIF created with [ezgif](https://ezgif.com/video-to-gif).

### Notes
I encountered difficulties in the superheroes page in scaling the movie images to the correct size. It turns out that there is a newly added feature in iOS that automatically scales the images in storyboard. Thanks to the Slack channel, I was able to get the issue resolved. Other than the above mentioned issue, I spent quite some time exploring AutoLayout, missing several constraints until I finally got it right.



# Part 1 - *Flix*

**Flix** is a movies scroll view made by fetching data remotely.

Submitted by: **Junhong Pan (Paul)**

Time spent: **4** hours spent in total

## User Stories

The following **required** functionality is complete:

* [x] User sees an app icon on the home screen and a styled launch screen.
* [x] User can view and scroll through a list of movies now playing in theaters.
* [x] User sees an app icon on the home screen and a styled launch screen.

The following **optional** features are implemented:
* [x] User can view the app on various device sizes and orientations.
* [x] Run your app on a real device.

Just launch the app and start scrolling.

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='ezgif-6-269f6451f288.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [ezgif](https://ezgif.com/video-to-gif).

## Notes

Getting the currency to update in the main view apart from the setting page is somewhat difficult since the states of the tip amount and currency need to be shared between different views. I managed to solve it by creating a struct that is passed in to each of the sub-views when creating the app, having the main contentview encompass both the settings and main view.

Spacing the app correctly for multiple device sizes is difficult, I had to make sure the ratios of the boxes are correct so the tips and settings are displayed reasonably on different devices.

## License

    Copyright [2020] [Junhong Pan (Paul)]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

