# StoryDownloader

Free Windows desktop beta for saving Telegram stories available to your account. Independent client, not affiliated with Telegram. Closed-source application.

**[Download the Windows beta](https://github.com/Eugene-Tarasov/StoryDownloader/releases/latest)** · **[Русская инструкция](README-RU.md)** · **[Report a problem](https://github.com/Eugene-Tarasov/StoryDownloader/issues)**

Download the ZIP from Releases, extract the entire archive and run StoryDownloader.exe. No Python installation is required. You need your own Telegram API ID and API Hash; the application includes API setup help.

Features include year folders, publication dates in filenames, pause/resume, stop, tray support and 11 interface languages. Dates use the computer timezone. The application does not bypass Telegram access restrictions.

## Beta status

Version 0.1.0-beta.1 was extracted and launched in Windows Sandbox. Live Telegram login and downloading could not be tested there because networking was unavailable. Automated checks used a simulated Telegram client. The executable is unsigned; native-speaker translation review is pending.

Settings, credentials and the authorization session are stored locally without encryption in %LOCALAPPDATA%/StoryDownloader. Do not share API Hash, session files, configuration or unredacted logs. Save and reuse only content you have permission to use.

Read README.md and README-RU.md in the release archive for full instructions. This repository contains documentation and releases; the application source code is not published. The first beta is free under the terms in [LICENSE.txt](LICENSE.txt). Third-party licenses are included in the ZIP.

## Feedback

Open an Issue with your Windows version, app version, interface language, steps and expected/actual result. Remove personal information from logs and screenshots.
