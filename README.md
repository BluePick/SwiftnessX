<h1 align="center">
  <br>
  <img src="https://s15.postimg.cc/omhc6tcrv/256px_2x.png" alt="Swiftness" width="100"></a>
  <br>
  SwiftnessX
  <br>
</h1>


<div align="center">

[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/winter-is-coming.svg)](https://forthebadge.com)

</div>

<p align="center">A cross-platform note-taking & target-tracking app for penetration testers built on ElectronJS.</p>

![swiftnessX](https://image.ibb.co/hJPgxf/checklist-view.png)



## Downloads

- **Windows:** [Download](https://github.com/ehrishirajsharma/SwiftnessX/releases/download/v0.1.1/swiftness-setup-0.1.1.exe)
- **Linux:** [Download](https://github.com/ehrishirajsharma/SwiftnessX/releases/download/v0.1.1/swiftness-0.1.1-x86_64.AppImage)

Check [Releases](https://github.com/ehrishirajsharma/SwiftnessX/releases) for support on different Operating Systems. 

*App supports auto-updating system when new release gets available.*

Check our [upcoming](https://github.com/ehrishirajsharma/SwiftnessX/wiki/Upcomings) releases and we also need security-folks interested in contributing to checklist-libraries ([get in touch here](https://goo.gl/forms/YoM31FUQ0at3b51i2)). 

It’s pretty straightforward to use SwiftnessX, I’ve created a small video on how to use Targets with checklist: https://www.youtube.com/watch?v=s227q_rTVkw

## Installation

The current version is specially designed for Windows users therefore, installation process is pretty straightforward - just use the installer and it will be installed under the applications section.

For Linux users (it's a bit complex and we will try to fix it very soon), you will need to give permission to the app; just `chmod +x swiftness-0.1.0.AppImage` for installer file and then open it (in first attempt, it will try to install) and then it will be ready to use. (Make sure you're extracting the app in a dedicated folder)

If you want to use the portable version, extract the folder and give same permission to Swiftness executable file and utilise in the same manner.


## Setup Electron (if you want to run dev-environment)


1. First install [Node.JS](https://nodejs.org/en/download/) on your system
2. now run `sudo npm install electron -g --unsafe-perm=true --allow-root`
3. Download or Clone this repository
4. Within its folder run `sudo npm install --unsafe-perm=true --allow-root` to install dependencies
5. And to run use `npm run dev`

To update just use `git pull` or if dependencies are updated than first install them by `npm install`


## Discuss


:seedling: **Feature Request / Changes:** This is a very early version of SwiftnessX with a completely new flow and architecture from macOS build and it's likely that some features & flow may not be perfect. We encourage you to tell us if a flow or feature is not fitting in, we will discuss with you and along with other users’ on possible way to improve or change that. 

----

:rotating_light: **Security:** Electron projects are often dependent upon too many 3rd party libraries and in result it has more chances of being vulnerable to security-vulnerabilities compared to native-apps.


We tried our best to not make app’s modules too dependent upon the 3rd party packages however, we still recommend you to understand the basics of ElectronJS and let us know if you observe any security vulnerabilities.


To understand the basics of Electron Security & NodeJS Packages:


  - https://electronjs.org/docs/tutorial/security
  - https://www.blackhat.com/docs/us-17/thursday/us-17-Carettoni-Electronegativity-A-Study-Of-Electron-Security-wp.pdf
  - https://www.youtube.com/watch?v=QSMbk2nLTBk


You can find the packages under package.json, check them:


  - You can check how packages are integrated and can manually check the process by debugging the app in dev-environment. (explained above)
  - Use Chromium Developer Tools to check each functionality and their dependent JS files.


Directly ask us on Issues Section or Email (security@swiftness.org) to understand how a specific package is integrated. 


To report a security-vulnerability within the app, please send us an email directly to security@swiftness.org


If issues are derived from a 3rd-party module, also report to the person or team maintaining the module. 

----
  
:bug: **Bugs:**

When opening a new issue in the `ehrishirajsharma/SwifnessX` issue tracker, users will be presented with a template that should be filled in.


The two most important pieces of information needed to evaluate the report are a description of the bug and a simple test case to recreate it. It easier to fix a bug if it can be reproduced.

See [How to create a Minimal, Complete, and Verifiable example](https://stackoverflow.com/help/mcve).
  
**Reference & Inspired from:** https://github.com/electron/electron/blob/master/docs/development/issues.md

----


## Credits

Special thanks to the below contributors - It would not be possible without their contributions:


- Tomas Baskys
- Pankaj Prajapat
- Sahil Ahamad
