Michael Savitski

February 18, 2019

Individual Subject Proposal

Project Name: Open Camera

SourceForge Page: https://sourceforge.net/projects/opencamera/

Git Repository: git clone <https://git.code.sf.net/p/opencamera/code>

Project Abstraction:

Open Camera is an open source camera application for Android devices, coded in
Java. It includes a number of features such as auto-stabilizing, noise
reduction, remote controls and a widget for automatic photo taking, a
configurable GUI, etc. The project is heavily focused on adding features and
modifications based on user requests.

Conceptual Design:

There are currently over 400 open tickets on the project’s page for feature
requests and bug fixes. I propose we tackle a number of these, such as:

-   Features

    -   QR Code recognition / reading

    -   Privacy mode with a simple toggle in the UI to omit metadata from the
        image file, such as location

    -   Option to configure which camera on the device is automatically chosen
        when launching the app

    -   Prevent OS-initiated screen sleeping while recording a video

-   Bugs

    -   Does not correctly detect 60FPS support on all devices

    -   Audio in video playback does not play through headphones

I specifically selected these features and bugs based on their approachability
for programmers who do not have extensive knowledge of photography or image
processing.

Project Relevance:

This project has both a SourceForge page for ticketing and issue tracking, and
GitHub repository for source control and versioning. It is of a scope that it
can easily be worked on in tandem by a small group. As it is an Android project,
it is coded in Java and the JUnit testing we have learned can be utilized, as
well as usage testing via the Android emulator and deployment on Android
devices.

Required Resources:

-   Android Studio IDE

-   Android device with camera and headphone jack (such as a phone or tablet)
