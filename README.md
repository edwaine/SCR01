# For Samsung Galaxy 5G Mobile Wi-Fi SCR01 (SM-H412J)

=============================================
Reference Links: 
=============================================
XDA Forum Support: https://forum.xda-developers.com/t/please-help-me-to-get-5g-connection-on-galaxy-5g-mobile-wi-fi-scr01.4469827/

Amazon Japan Store Link: https://www.amazon.jp/dp/B098XJ88HM

Dedicated Device Page: https://www.samsung.com/jp/mobile-accessories/galaxy-5g-mobile-wi-fi-white-sm-h412jzwauqm/

Dedicated Device Support Page: https://www.samsung.com/jp/support/model/SM-H412JZWAKDI/

Device Update Changelog: https://doc.samsungmobile.com/SCR01/KDI/doc.html

Compiled OTA Updates: https://app.box.com/s/hn55vxnurdkvg6zlu8r2nixwhl7f0dg7

=============================================
Complete Device Specifications:
=============================================
MediaTek Dimensity 720 (MT6853)

Android 11 with OneUI 3.0 (w/o Google Play Services)

2.5GB RAM

32GB Internal Storage

WiFi 5

5000mAH Battery

5.3" (1480x720) LCD Display

Network bands:

5G: n28 / n41 / n77 / n78

4G: LTE FDD: B1 / B3 / B17 / B18 TDD: B41

Disabled Bands that can be enabled:

4G: B7 / B38

=============================================
Instructions:
=============================================
A. Setting up your device.

	1. Upon first boot, you will need to setup your device in Landscape mode. Choose your language first then tap "Ok" then tap "Start". On the 2nd page tap "Continue".
	2. On the 3rd page, choose "Plus Area (+A)" and tap "Next". That way it will also search for bands in a wider area. Otherwise, if your signal in your area is strong, choose "Standard (ST)".
	3. On the 4th page, choose "Optimized Mode" and tap "Next". High Performance mode heats up your device too quickly and Eco mode doesn't utilize 5G and only uses 4G/LTE.
	4. On the 5th page, just tap "skip".
	5. On the 6th & 7th page, you will need to setup your Wi-Fi. But first, you will need to change your keyboard language and layout.
		5.1. Tap the SSID first so a keyboard will pop-out.
		5.2. Tap the "Gear Icon" on top of the keyboard screen to go to the Keyboard Settings.
		5.3. Tap "Languages & Types">"English (US)" & choose "Qwerty".
		5.4. Tap "Manage input languages" and de-select "Japanese".
		5.5. Optional: Tap back 2 times and de-select "Predictive Text" then tap back to go back to Wi-Fi Setup
	6. On the 8th page, select a screen lock type & tap "Next".
	7. On the 9th page, select if you want your Wi-Fi to "Turn off automatically" or "Don't turn off automatically & tap "Next".
	8. On the 10th page, select if you want to use battery protection and tap "Next".
	9. Reboot if you choose to disable battery protection.

B. Setting up your APN/Access Point Names

	1. Swipe up your device
	2. Go to "Hamburger Icon>Communication Setting>APN".
	3. Go to "3 dot menu" and tap "Add".
	4. Input your carrier's Name, Access Point Name, Username, Password, Authentication, PDN & tap "Save" then tap Save again
	5. If you have another Carrier, remove your current SIM Card and replace it with your preferred one & repeat step's B1 to B4 again.

C. How to Access ServiceMode

	1. Swipe up your device
	2. Go to "Hamburger Icon>Status" and tap "Phone Number" 10 times.
	3. Type *#0011# to go to ServiceMode.
	**Remember, on the ServiceMode if you want to go back to the previous menu, tap the "3 dot menu" and tap "Back"**
	4. Go to "3 dot menu" and tap "Back" and tap "Key Input" then type "Q" and tap "Ok".

D. Unlocking 5G Mode for Non-Japanese Carriers

	1. Go to "ServiceMode"
	2. Tap "UE SETTING & INFO>SETTING>PROTOCOL>NR".
		2.1. On "NR CONFIGURATION", tap first "ALLOW LIST CONTROL" & tap "ALLOW LIST OFF". A message will show "Apply Success" then go back to "NR CONFIGURATION".
		2.2. Going back to "NR CONFIGURATION", tap "NR5G/NSA MODE CONTROL" & tap "SA/NSA ENABLE". A message will show "Feature Apply Success, Please reboot".
		2.3. Reboot to apply setting.

E. Enable USB Debugging

	1. Swipe up your device
	2. Go to "Hamburger Icon>Status" and tap "Phone Number" 10 times.
	3. On Developer Options, tap to enable "USB Debugging".

F. Enable 4G Band B7 & B38

	1. Go to "ServiceMode"
	2. Tap "UE SETTING & INFO>SETTING>PROTOCOL>AS>NEXT PAGE>USA LTE B7 & B38 SETTING>".
		2.1. On "LTE B7 & B38 SETTING", tap "ENABLE LTE B7B38 in USA"
		2.2. A message will show "Feature Apply Success, Please reboot".
		2.3. Reboot to apply setting.

G. How to Band Lock

	1. Go to "ServiceMode"
	2. Tap "UE SETTING & INFO>SETTING>PROTOCOL>NAS>NETWORK CONTROL>BAND SELECTION>BAND SELECTION SIM 1".
	3. Once there, you can go to "LTE Band Preference" & "NR Band Preference" & select your locally available network bands.
