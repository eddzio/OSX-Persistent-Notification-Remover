
# Description:
MacOS keeps showing irrelevant Login Item notifications.

[@abelcha](https://github.com/abelcha) wrote an Apple Script to remove the notification. I had to change the title of the notification in the script for it to on Sonoma 14.0.

Here's the original Readme from @abelcha:


# How it works

## Option 1: Apple Scripts
1. You need to grant Accessibility permissions to the Script Editor app in `System Settings -> Privacy & Security -> Accessibility` — Click the `+` button and add `/Applications/Script Editor.app`
2. Open the Script Editor app and paste the content of `NotifRemover.scpt`
3. Run the script by pressing `CMD + R` or pressing the play button on the top right corner of the Script Editor app.


## Option 2: via the Terminal
1. You need to grant access to the terminal app in `System Settings -> Privacy & Security -> Accessibility`
2. Run the script:
```shell
curl -s https://raw.githubusercontent.com/eddzio/OSX-Persistent-Notification-Remover/main/NotifRemover.scpt | osascript
```

A million thanks to [@abelcha](https://github.com/abelcha) for the original script!