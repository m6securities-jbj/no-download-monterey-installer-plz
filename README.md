# Are you tired of Apple "Drive by Downloading" their full 12GB macOS Monterey Installer without your permission? If so, then this is the perfect solution for you, and you're in the right place!

#### This repository has been created for the sole purpose of providing those people that wish for Apple not to "Drive by Download" their full 12GB macOS Monterey Installer app onto their machines a hacky, yet viable solution to prevent Apple from automatically downloading the macOS Monterey Installer without permission.


## Acknowledgements

 - [Apple, for their "drive by downloading" of their OS Installers, not giving the end user the choice](https://www.apple.com/macos/monterey/)
 - [The EFF, for defending digital privacy, free speech, and innovation.](https://eff.org/)
 - [Myself, for never wanting to accept what's forced upon another as being okay](https://joshuajones.dev)


## Authors

- [@m6securities-jbj](https://www.github.com/m6securities-jbj)


## FAQ

### This sounds great! How do I stop Apple from Drive by Downloading the OS Installer without my permission to my Applications folder? How do I use this?

You obtain the .DMG file from this GitHub repository that you're currently on, mount the DMG, and place the file into your Applications directory.

### How is this achieved, and how does it work?

This is achieved by tricking Apple's servers when they run their sneaky little check for the file being present in the Applications to show that yes, the OS Installer application is there. It works by ommitting the huge parts of the Installer.app that take up the most space, whilst leaving the other files, and then locking the file to make sure that it can't be modified by Apple, or anyone else without removing the lock first.

## Features

- An alternative choice to Apple's forced "Drive by Downloading"
- Locked file, preventing modification by Apple (hopefully)
- Prevents Apple from downloading full 12GB Installer.app
- Small in file size, 42.4MB


## Feedback

If you have any feedback, please do so via the appropriate location in the repository.


## Installation

- Obtain DMG file
- Mount DMG file
- Drag DMG to Applications folder
- Profit
    
![Logo](https://i.ibb.co/Yyr0gX0/No-Mac-OSMonterey-Installer.png)
