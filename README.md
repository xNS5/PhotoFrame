# Photo Frame

Tasker photo frame files 

**Goal**: Create an android digital picture frame that can be remotely administered with photos hosted in the cloud.

**Tablet**: Kindle Fire HD 10 ($115)

**Software**:

1. Fully Kiosk Browser PLUS (~$5)

2. Fotoo PLUS ($9.99)

3. Tasker ($3.49)

4. AutoApps (Free)

5. AutoInput ($1.99)

6. Airdroid (Free)

7. Immersive Mode Manager ($1.99)

Steps

    Get an android tablet. I didn't really know of any cheap name-brand tablet computers, so I settled on a Kindle Fire HD10 (9th gen). There was a black friday sale and I figured "What the hell"

    Install all of the programs I listed.

    Set up Tasker. I set a profile that detects a system boot, unlocks the device, show the blocking scene, and start the kiosk. I also set up a task that "kills" the overlay scene so I can interact with it. Note: When you create the overlay, make sure it's the max width of your screen, and set it to "overlay, blocking" instead of "overlay, blocking, full screen". Ensure that the overlay is aligned to center top.

    Install Immersive Mode Manager. This enables a system wide immersive mode which allows Tasker to utilize a full screen blocking overlay.

    Fully Kiosk Browser effectively turns your tablet into a single-app kiosk. I was intending to use tasker for this step, however I found this to be a better solution.

    Fotoo syncs with google photos and displays albums. You can set transition speeds and transition animations.

    I used Tasker to unlock the device, start AirDroid, and start up a blocking scene to prevent accidental touches. I created two buttons to move the pictures back and forth.

    AirDroid is a program that allows me to remotely administer the tablets. If you want to do this with a fire tablet, get an older model that you can root. A lot of these steps are much easier after rooting. Note: In order to use the remote access feature, you can either root or use what they call "non-root authority" which temporarily allows remote access. This gets reset every time the device reboots.

Alternatives:

Anydesk -- It works to see the device, however touch interface doesn't work on a PC or phone. No clue why.

Teamviewer -- I fucking hate teamviewer, but if it works, so be it.

DAKboard -- Works with Google Photos, however it's subscription based and is overall more limited.

I can post my tasks later/explain in more detail once I've gotten sleep. I've been wrestling with this project for a few weeks. Started from having a general idea of what I wanted to accomplish, finished with two functional digital picture frames that I can remotely administer at 4:00 AM PST on Christmas day.

Edit: Edited to add Immersive Mode Manager and some other stuff for tasker
