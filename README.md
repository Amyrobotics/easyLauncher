If you dont want use Voice Launcher and AmySettings, you can install the easyLauncher and remove VoiceLauncher  and AmySettings.

remove VoiceLauncher  and AmySettings：
    adb root
    adb remount
	adb remove /system/app/AmySettings/AmySettings.apk
	adb remove /system/app/AmyVoice/AmyVoice.apk



当无需使用A1或A2系统预装的语音桌面和艾米设置时，可以安装并使用此easyLauncher。移除系统预装的语音桌面和艾米设置。

移除 VoiceLauncher AmySettings 步骤：
    adb root
    adb remount
	adb remove /system/app/AmySettings/AmySettings.apk
	adb remove /system/app/AmyVoice/AmyVoice.apk