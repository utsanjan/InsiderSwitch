<h1 align="center">
  <br>
  <a href="https://github.com/utsanjan/InsiderSwitch">
  <img src="https://lh3.googleusercontent.com/-R9auUcvj2Do/YQ6KPZ_rxaI/AAAAAAAAj80/ktWpV0mpCDMKPOJGWsST4DvINK1_My_EQCLcBGAsYHQ/w200-h200/InsiderSwitch.ico"
  alt="Insider Switch">
  </a><br>
  Insider Switch
  <br>
</h1>
<p align="center">InsiderSwitch is a simple Windows<br>
executable that enables access to the<br>
Windows Insider Program on computers<br>
that aren't signed in with Microsoft Account</p> <br>

## 📝 Usage guide
[![Buy Me A Coffee](https://img.shields.io/open-vsx/stars/redhat/java?color=D8B024&label=buy%20me%20a%20coffee&style=plastic)](https://www.buymeacoffee.com/utsanjan)‎ ‎
[![](https://img.shields.io/github/license/utsanjan/Tsunami-Bomber-Android?logoColor=red&style=plastic)](https://github.com/utsanjan/Tsunami-Bomber-Android/blob/main/LICENSE)‎ ‎ <br><br>
Just run the program by double clicking on it<br>
and choose your preferred option in the prompt.<br>
Click the button below to download InsiderSwitch.<br><br>

<a href="https://github.com/utsanjan/InsiderSwitch/releases">
<img src="https://bit.ly/3Ee49cs" alt="Insider Switch Releases" width="200" height"auto"></a><br>

## ⚙️ Installation and configurations
After starting the program it offers with the options to<br>
select the version of *Windows Insider Program* channels.<br>
To make a selection, press the respective option no. & press enter.<br>
If the machine was not enrolled to the Insider Program, you will get<br>
prompted to restart your machine to enable *Microsoft Flight Signing*. <br>

<a href="https://lh3.googleusercontent.com/-5_F7O8n2SrU/YQ7SlT1b25I/AAAAAAAAj9s/esEQnCQN9M8Fnx74HYE3R06f3G42KcZHgCLcBGAsYHQ/s16000/Screenshot%2B%2528228%2529.png"><img width="60%" height="auto" src="https://lh3.googleusercontent.com/-2R6W36ECe7o/YQ7R4gptrsI/AAAAAAAAj9k/FjALnC6Ecm0EBBnVUSV4KJSGZiXJsGqTQCLcBGAsYHQ/s16000/ss.png" height="175px"/></a>

**🔴 Notice:** Windows Insider Program requires telemetry to be set to *Full*.
After enrolling your machine to the *Windows Insider Program* please make sure
that your diagnostic data collection settings are set to *Full*. Some *Insider
Preview* builds may not get offered in *Windows Update* if you do not have
correct telemetry settings. You can verify or modify your telemetry settings in
*Settings* > *Privacy* > *Diagnostics & feedback*.

## ⚡ Restore to default
To restore *Windows Insider Program* to default settings<br>
just choose `Unenroll Insider Preview` in InsiderSwitch.<br>
You will get prompted to reboot, press Y and then enter.<br>

## 🧭 How it works
This program takes advantage of undocumented `TestFlags` registry value.
If this value is set to `0x20`, all access to online *Windows Insider* services
gets disabled. Because of this, we can set our own *Windows Insider Preview*
configuration without being overriden by the contact to the service. Since
Windows Update does not check if machine is actually enrolled to the program,
you will get offered *Insider Preview* builds by just setting correct values in registry.

## ✒️ Credits 
### [Whatever127](https://github.com/whatever127)<br>
**Work: Whatever127 designed the Offline Insider Enroll<br>
which helped me a lot to make this program working.** <br>
[Click here to visit offline Insider Enroll Repository](https://github.com/whatever127/offlineinsiderenroll)

## 🌎 Contact me  
For Queries: [My Instagram Profile](https://www.instagram.com/utsanjan/)  
[Check Out My YouTube Channel](https://www.youtube.com/DopeSatan)
