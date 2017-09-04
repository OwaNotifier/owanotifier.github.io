# OwaNotifier : get notified !

This daemon display notification when you have new mail on Office365 Outlook. [![Github Download](https://img.shields.io/badge/download-plastic-green.svg?style=plastic)](https://github.com/OwaNotifier/owa-notifier/releases/download/owanotifier-1.0.0/OwaNotifier-jar-with-dependencies.jar)

[![Build Status](https://travis-ci.org/matgou/owa-notifier.svg?branch=master)](https://travis-ci.org/matgou/owa-notifier)
[![codecov.io](https://codecov.io/github/matgou/owa-notifier/coverage.svg?branch=master)](https://codecov.io/github/matgou/owa-notifier?branch=master)

## Screenshoot

### Get notified when you have unread mail
![screenshot-notification](https://raw.githubusercontent.com/matgou/owa-notifier/master/documentation/screenshot-swing-notification.png "Screenshot Using Swing Notification")

### Unread mail reminder by icon tray

![screenshot-traynotification](https://raw.githubusercontent.com/owanotifier/owanotifier.github.io/master/images/TrayNotification.png "Screenshot Tray")

### Temporary mute notification

![screenshot-menu](https://raw.githubusercontent.com/owanotifier/owanotifier.github.io/master/images/trayMenu.png "Screenshot Menu")

## Usage

Just click on "jar" file :

![screenshot-click](https://raw.githubusercontent.com/owanotifier/owanotifier.github.io/master/images/OwaNotifier-jar-click.png "Screenshot Lauching")

Login on Microsoft :

![screenshot-login](https://raw.githubusercontent.com/owanotifier/owanotifier.github.io/master/images/login.microsoft.com.png "Screenshot Login")

## Minimum requirement

| System Requirements | minimum level |
|---|---|
| Operating System  | Linux or Windows |
| Java | OracleJRE or OpenJDK 6 or greater  |
| Memory | 64Mo |

### For low memory desktop

Just create symlink with those parameters:
```bash
java -jar OwaNotifier-jar-with-dependencies.jar -Xmx16m -Xms16m -Xss200k
```

## Download & Developpement

|Ressources|Link|
|---|---|
| Latest release | [OwaNotifier-jar-with-dependencies.jar](https://github.com/OwaNotifier/owa-notifier/releases/latest) |
| Github Project | https://github.com/OwaNotifier/owa-notifier |
| JavaDoc | [Java documentation](https://owanotifier.github.io/docs/apidocs/) |
