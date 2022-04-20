# Open In Other Application

- English
- [中文版](/README_CN.md)

> Support to open the URL using other applications in the Chromium kernel browser on Windows system.

It can automatically run other applications and transfer information such as URL after opening the matching URL in chromium kernel browser; optionally, enable the right-click menu. You can open the URL or selected text with other applications on the web page.

Only Windows system is supported.

## Installation

Need 2 files to [Releases](https://github.com/LightAPIs/open-in-other-application/releases/latest) download:

1. Program for running on this machine: `host.zip`. Unzip the `zip` file to the local disk.
2. Browser extension: `open-in-other-application_manifest-vx.crx`. If the Chromium version is less than 88, you need to download the `manifest-v2` version of the extension. Drag the `crx` file to `chrome://extensions/` page to install the extension.

## Usage

### First use

When using for the first time, you need to perform the following steps:

1. Enter the extension options. Click the copy button in the upper right corner of the page to copy extension ID.
2. Running `HostRegistrar.exe` on local disk. Fill in the copied extension ID. Click the register button, wait for the prompt to complete. Then you can close the program. (_The program directory and files need to be retained and cannot be deleted._)

### General Usage

Enter the extension option, add applications that you want to run, and writing automatic operation rules that need to open some URLs. You can open the right-click menu of displaying Web pages in the settings in the upper right corner.

Click the extension icon to switch the enabled status of automatic rules.
