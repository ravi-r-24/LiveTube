# Requirements

# 1. UI Overview

    -> Header
        1. Left part
            -> Menu Icon
            -> Logo
        2. Middle part
            -> Search Bar
            -> Mic Icon
        3. Right part
            -> Add Video Icon
            -> Notification Icon
            -> User Icon

    -> Body
        1. Left Part
            -> Sidebar
                a. Part-1
                    -> Base Features URL button
                b. Part-2
                    -> User related activity button [playlist, download and all]
                c. Part-3
                    -> User subscribed Channel list
                d. Part-4
                    -> Explore [Rest all features URL button]
                e. Part-5
                    -> More from LiveTube
                f. Part-6
                    -> Privacy
                g. Part-7
                    -> About LiveTube

        2. Right Part
            -> Top navbar [scrollable]
            -> Video Container
                a. Video Card
                    -> Thumbnail
                    -> Video Title
                    -> Channel Name
                    -> Views . Time ago uploaded
                b. Shorts Card
                    -> Thumbnail
                    -> Title
                    -> Views

# 2. Functionality

    -> Header
        a. Menu Icon
            -> On click left sidebar should open/close
        b. ⁡⁢⁣⁣Search bar [In Update]
            -> On change call API [suggestion]⁡

        c. ⁡⁢⁣⁣Mic Icon [In further Update]
            -> On click a prompt should open which will capture the voice of the user⁡

        d. ⁡⁢⁣⁣Add Video Icon [In further Update]
            -> A form prompt should open and ask user to fill it to upload their video with all information⁡

        e. Notification Icon
            -> On click open a side bar from right which provide list of notification to the user

        f. User Icon
            -> On click open a sidebar from right which provide many options to the user

    -> Body
        1. Left Part
            -> Sidebar
                -> On Click buttons of all sections of the sidebar should open the the specified page

        2. Right Part
            -> On click button of the top navbar the video related to that key [either in the video title or in the channel description] should be searched

            -> On click video card the video player page should be opened with playing video un-muted
