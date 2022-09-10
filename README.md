# Echo for Shortcuts
## **An application that can *translate* Shortcuts to a human-readable format**; either for sharing (without actually sharing the Shortcut itself, but instead a description of the actions) or for debugging purposes.

## Features
- [ ] Translate Shortcuts to a human-readable format (i.e. provide a simple description of the actions incl. in the shortcut)

## Planned Features
- [ ] Online translation (i.e. provide a link to a website that can translate the Shortcut)
- [ ] Offline translation (i.e. provide a way to translate the Shortcut without an internet connection)

## Potential Features
- [ ] Translation to other programming languages
- [ ] Check for potential security risks and provide a warning if any are found (e.g. if the Shortcut contains a "Get Contents of URL" action, it could be a potential security risk)

## Why?
- **Privacy and Security risks**:
    - The ability to *share* and *download* Shortcuts online (made by third parties) can be a privacy and security risk
        1. Sharing a Shortcut allows others to see the actions you have in your shortcuts (potentially revealing sensitive information)
        2. Downloading a Shortcut can contain malicious code that can be used to steal your data (opening a website that can steal your data, sending files/photos/health information to a third party, [etc.](https://www.idownloadblog.com/2019/01/29/malicious-shortcuts/))
            - *Always be careful when sharing and downloading shortcuts from the internet - and always check the code before running it*
    - Echo only shares a description of the actions included in the Shortcut which another person can then build themselves in the shortcuts app
- **Debugging**: 
    - You can easily see what a Shortcut does without actually running it
    - Text-based version of a Shortcut can improve searching through the code (e.g. searching for a specific action)
    - Text-based version of a Shortcut can be used to find potential errors in the code (e.g. missing actions, missing parameters, etc.)
- **Sharing**:
    - You can easily share a description of a Shortcut without actually sharing the Shortcut itself
    - You can easily share a description of a Shortcut with someone who doesn't have the Shortcuts app and/or doesn't have an iOS device
    - Improved readability of the code (e.g. easier to read than the .shortcut format in Shortcuts app / Xcode)


## How?
**Status**: *In Development*
This project is currently in development and is not yet available for download. If you would like to contribute to this project, please don't hesitate to contact me! 

**Feedback** 
Issue creation, feature requests, bug squashing, pull requests are welcome, and encouraged!