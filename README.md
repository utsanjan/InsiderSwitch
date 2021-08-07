<h1 align="center">
  <br>
  <a href="https://github.com/utsanjan/Android-Pin-Bruteforce/">
  <img src="https://lh3.googleusercontent.com/-R9auUcvj2Do/YQ6KPZ_rxaI/AAAAAAAAj80/ktWpV0mpCDMKPOJGWsST4DvINK1_My_EQCLcBGAsYHQ/w200-h200/InsiderSwitch.ico"
  alt="Android Pin Bruteforce">
  </a><br>
  Insider Switch
  <br>
</h1>
<p align="center">InsiderSwitch is a simple Windows<br>
executable that enables access to the<br>
Windows Insider Program on computers<br>
that aren't signed in with Microsoft Account</p> <br>

## 📝 Usage guide
Just run the program by double clicking on it<br>
and choose your preferred option in the prompt.

## ⚙️ Installation and configurations
After starting the program it offers with options to<br>
select the version of *Windows Insider Program* channels.<br>
To make a selection, press the respective option no. & press enter.<br>
If the machine was not enrolled to the Insider Program, you will get<br>
prompted to restart your machine to enable *Microsoft Flight Signing* <br>
which is required by *Windows Insider Program*.

**Notice:** Windows Insider Program requires telemetry to be set to *Full*.
After enrolling your machine to the *Windows Insider Program* please make sure
that your diagnostic data collection settings are set to *Full*. Some *Insider
Preview* builds may not get offered in *Windows Update* if you do not have
correct telemetry settings. You can verify or modify your telemetry settings in
*Settings* > *Privacy* > *Diagnostics & feedback*.

## 🔄️ Restoring Windows Insider Program to default
To restore *Windows Insider Program* to default settings just<br>
choose `Quit without making any changes` in InsiderSwitch.<br>
You will get prompted to reboot, press Y and then enter.<br>

## 🧭 How it works
This program takes advantage of undocumented `TestFlags` registry value.
If this value is set to `0x20`, all access to online *Windows Insider* services
gets disabled. Because of this, we can set our own *Windows Insider Preview*
configuration without being overriden by the contact to the service. Since
Windows Update does not check if machine is actually enrolled to the program,
you will get offered *Insider Preview* builds by just setting correct values in
the registry.

## 🌎 Contact me  
For Queries: [My Instagram Profile](https://www.instagram.com/utsanjan/)  
[Check Out My YouTube Channel](https://www.youtube.com/DopeSatan)
