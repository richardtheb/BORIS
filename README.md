Introducing **BORIS - Big Offline Intelligent Responsive Intelligent(ish) System.**



This is a fork of [Pi-C.A.R.D, the Pi Camera Audio Responsive Device]([url](https://github.com/nkasmanoff/pi-card)) from [Noah Kamansoff]([url](https://github.com/nkasmanoff)): Kudos to him for most of teh code and stuff going on here. I've taken his excellent work and added to it: see the note below on changes. 





Changes From Pi-CARD
The main hanges I have made are

- Added an install script that does most of the setting up to run on a clean install of Raspbian on a Pi 5, including
  - Installing requirements
  - Downloading the LLMs required
- Changed the audio system to use PortAudio
- Added changes that detect the default sample rate and use this rather than assuming. That makes it more compatible with multiple microphone devices.
- 



