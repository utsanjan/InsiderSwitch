## Description
InsiderSwitch is a simple Windows 11 executable to<br>
enable access to the Windows Insider Program on PCs<br>
not signed in with Microsoft Account. This program<br>
is compatible only with Windows 11 only.

## Usage guide
Just run the program by double clicking it<br>
and choose your option in the prompt.

### Installation and configuration changes
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

## Restoring Windows Insider Program to default options
To restore *Windows Insider Program* to default settings just<br>
choose `Quit without making any changes` in InsiderSwitch.<br>
You will get prompted to reboot, press Y and then enter.<br>

## How does this work?
This program takes advantage of undocumented `TestFlags` registry value.
If this value is set to `0x20`, all access to online *Windows Insider* services
gets disabled. Because of this, we can set our own *Windows Insider Preview*
configuration without being overriden by the contact to the service. Since
Windows Update does not check if machine is actually enrolled to the program,
you will get offered *Insider Preview* builds by just setting correct values in
the registry.

## Credits
https://github.com/whatever127
