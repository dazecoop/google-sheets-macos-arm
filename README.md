# Google Sheets application for MacOS Arm/M1 machines

This is a step-by-step that seemed to work for me (dated March 2023).

## Install steps

1. `npm install -g nativefier` (see https://github.com/nativefier/nativefier)
2. Move `icon.icns` into your user directory
3. Within your user directory, run `nativefier 'https://docs.google.com/spreadsheets' --user-agent firefox --icon icon.icns --name 'Google Sheets' --honest`
4. Open generated folder and move **Google Sheets** application to your **Applications** folder
5. Open it
6. Open **Activity Monitor**, right-click on columns and ensure **Kind** is selected
7. Search for Google Sheets to double check **Kind=Apple**. If yes, this is a Universal App ✅
