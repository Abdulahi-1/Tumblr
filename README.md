# TumblrFeed

Submitted by: Abdulahi Abdi

**TumblrFeed** is an app that displays posts from a Tumblr blog in a clean, scrollable feed. It fetches data from the Tumblr API and dynamically populates a table view so users can browse through the latest blog posts.

Time spent: 6 hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] App has a configured table view and table view cell
- [x] App populates the table view with data fetched from an API

The following **optional** features are implemented:

- [x] App fetches posts from a different Tumblr blog
- [x] App has a refresh control to update the table view

The following **additional** features are implemented:

- [x] Custom cell layout to improve readability of posts
- [x] Error handling for failed API requests
- [x] Loading indicator while fetching posts

## Video Walkthrough

https://www.loom.com/share/b76feab2d7274dd4becd063fd15d2802?sid=d8be3306-1a06-4d59-ba3e-84dff359cbf2

## Notes

One challenge I faced while building the app was configuring the table view cells to display the correct post data from the Tumblr API. At first, the cells weren’t updating with the fetched data, which made it look like the app wasn’t working. I overcame this by double-checking my model’s decoding logic and ensuring the table view was reloaded on the main thread after the data was retrieved. Once fixed, the posts displayed correctly, and scrolling through the feed worked smoothly. This gave me a stronger understanding of how to connect APIs with UI components in iOS development.

## License

    Copyright 2025 Abdulahi Abdi

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
