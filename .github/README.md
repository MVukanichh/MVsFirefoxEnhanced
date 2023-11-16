[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
<!--   <a href="https://github.com/MVukanichh/MVsFirefoxEnhanced">
    <img src="assets/images/logo.png" alt="Logo" width="896" height="368">
  </a>
 -->

  <h1 align="center">MVukanichh's Firefox Enhanced</h1>

  <p align="center">
   MVukanichh's Firefox Enhanced improves Firefox by enhancing it's speed, look and feel.
    <br />
    <a href="../main/.github/CHANGELOG.md">View Changelog</a>
    ·
    <a href="../main/LICENSE">View License</a>
    ·
    <a href="https://github.com/MVukanichh/MVsFirefoxEnhanced/issues">Report Bug</a>
    ·
    <a href="https://github.com/MVukanichh/MVsFirefoxEnhanced/issues">Request Feature</a>
  </p>
</div>
<!-- PROJECT LOGO -->

---

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

---

<!-- ABOUT THE PROJECT -->
## About The Project

MVukanichh's Firefox Enhanced (hereinafter referred to as "Firefox Enhanced") is a project made to improve Firefox. It includes ``user.JS`` file which tweaks Firefox, improving it's speed, smoothness and security, while not compromising usability in any way. It also includes ``userchrome.css`` file which improves Firefox's user interface, while staying true to Firefox looks.

To accomplish this, Firefox Enhanced uses Yokoffing's BetterFox ``user.JS``'s files and black7375's Lepton.

---

<!-- GETTING STARTED -->
## Getting Started

While Firefox Enhanced has a mouse-drag installation, it is also customizable. It includes comments from both black7375's Lepton and Yokoffing's BetterFox, so that, if necessary, changes can be made according to personal preferences.

### Prerequisites

To install Firefox Enhanced, you must ensure you have following software installed:

* Up-to-date Firefox Nightly (v117+)
  - black7375's Lepton supports pre-v117 versions but Firefox Enhanced will not have a version that includes files that support those versions; therefore, only versions supportable are v117 and higher.
* Notepad++
  - Notepad++ is used to customize ``user.JS`` to suit user's preferences. It is not necessary to have and use, but is recommended.

### Installation

It is recommended to have freshly installed and up-to-date Firefox Nightly installation, but Firefox Enhanced can also be used on an already installed Firefox Nightly instance.

In order to install Firefox Enhanced, next steps must be followed:

 1. Open Firefox Nightly
 2. In the URL Bar, type ``about:profiles``

Note that you must decide whenever you want a profile without Firefox Enhanced and a profile with Firefox Enhanced that you can switch to and from:

**I.** If you wish to have only one profile that will use Firefox Enhanced, you should do the following:

* Click on ``Open Folder`` next to Root Directory
* Turn off Firefox Nightly
* Delete everything from inside the folder
* Continue with the guide

**II.** If you wish to have two separate profiles, one with and one without Firefox Enhanced, you should do the following:

* Click on ``Create New Folder``
* Click ``Next``
* Choose a name for your Profile in order to distinguish between Firefox Enhanced Profile and the one without
* Click ``Next``
* Click on ``Set as Default Profile`` if you wish to have Firefox Enhanced Profile as your Default Profile
* Click on ``Open Folder`` next to Root Directory of newly made Profile
* Turn off Firefox Nightly
* Continue with the guide

 3. Open ``Firefox-Enhanced-vDDMMYYYY_X.X.X.X.7z`` file
 4. Move everything to the Profile Folder that was opened before
 5. Launch Firefox Nightly

If first option, only one profile used, was chosen, Firefox Enhanced instance will open and you'll be free to use it as it is.

If second option, two different profiles, was chosen, Firefox Enhanced instance *might* open, depending on whenever you chose to set it as a Default Profile. If you did not put it as a default profile, you should do next to launch it:

* Open Firefox Nightly
* In the URL Bar, type ``about:profiles``
* Locate Profile that contains Firefox Enhanced
* Press ``Launch Profile in new browser`` below it

It is also possible to launch a specific profile by making a Firefox Nightly shortcut. In order to do so, follow next steps:

* Make a new shortcut of Firefox Nightly
* Right-click on it and press ``Properties``
* In the "Target" box, after everything currently in it, type ``-P "Profile"``

Note that ``"Profile"`` should be the name of your Firefox Profile. In order to see the name of said profile, you should do following:

* Open Firefox Nightly
* In the URL Bar, type ``about:profiles``

Also note that there should be a space between ``-P "Profile"`` and the previous string.

This can be done for both profiles, but it is not needed, as a shortcut without ``-P "Profile"`` will launch a profile that's set as a Default Profile in ``about:profiles``.

#### UBlock Origins Settings

In order to apply MVsFirefoxEnhanced UBlock Origins Setting, you must do the following:

1. Install [UBlock Origins](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
2. Download ``MVsFirefoxEnhanced_UBlock_Origins_Settings.txt`` from the Latest MVsFirefoxEnhanced Release
3. Left click on ``UBlock Origins Icon`` in Firefox Toolbar next to Address Bar
4. Press ``Open the Dashboard`` in bottom-right corner
5. In the newly opened tab, scroll all the way down
6. Click on ``Restore from file...``
7. Navigate to where ``MVsFirefoxEnhanced_UBlock_Origins_Settings.txt`` is downloaded
8. Click on ``MVsFirefoxEnhanced_UBlock_Origins_Settings.txt`` and press Open.
9. On the next pop-up press ``OK``

---

<!-- USAGE -->
## Usage

Firefox Enhanced can be used as is, but it is recommended to change ``user.JS`` to suit your preferences. In order to do this, you can follow comments that already are in the ``user.JS`` file, or go to GitHub page of the section's file you wish to change prefs for, e.g. for BetterFox's FastFox, SecureFox, PeskyFox or SmoothFox, Yokoffing's BetterFox GitHub page should be visited.

---

<!-- ROADMAP -->
## Roadmap

Roadmap for future Firefox Enhanced release: 

- [ ] Add Wiki
- [ ] Add more content
- [ ] Add images as examples

See the [open issues](https://github.com/MVukanichh/MVsFirefoxEnhanced/issues) for a full list of proposed features (and known issues).

---

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions made are **greatly appreciated**.

If there is any suggestion that would make this project better, open an issue with the tag "enhancement".

Don't forget to give the project a star! 

---

<!-- LICENSE -->
## License

Distributed under the CC-BY-4.0 License. See ``LICENSE`` for more information.

---

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

While writing this file, I've found these resources helpful and used them to make both this README.md file and other content in this project. Go check them out!

* [Choose an Open Source License](https://choosealicense.com)
* [black7375's Lepton](https://github.com/black7375/Firefox-UI-Fix)
* [Yokoffing's BetterFox](https://github.com/yokoffing/Betterfox)
* [GitHub Docs for help with Markdown](https://docs.github.com/en/get-started/writing-on-github)
* [README Templates](https://www.readme-templates.com/)
* [Yokoffing's Filterlists](https://github.com/yokoffing/filterlists)


<p align="center">(<a href="#about-the-project">back to top</a>)</p>

---

[contributors-shield]: https://img.shields.io/github/contributors/MVukanichh/MVsFirefoxEnhanced.svg?style=for-the-badge
[contributors-url]: https://github.com/MVukanichh/MVsFirefoxEnhanced/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/MVukanichh/MVsFirefoxEnhanced.svg?style=for-the-badge
[forks-url]: https://github.com/MVukanichh/MVsFirefoxEnhanced/network/members
[stars-shield]: https://img.shields.io/github/stars/MVukanichh/MVsFirefoxEnhanced.svg?style=for-the-badge
[stars-url]: https://github.com/MVukanichh/MVsFirefoxEnhanced/stargazers
[issues-shield]: https://img.shields.io/github/issues/MVukanichh/MVsFirefoxEnhanced.svg?style=for-the-badge
[issues-url]: https://github.com/MVukanichh/MVsFirefoxEnhanced/issues
[license-shield]: https://img.shields.io/github/license/MVukanichh/MVsFirefoxEnhanced.svg?style=for-the-badge
[license-url]: https://github.com/MVukanichh/MVsFirefoxEnhanced/blob/master/LICENSE.txt