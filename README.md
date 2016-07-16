# Troubleshoot Like A Boss

## Key Points
- Have a browser you know in and out: [Chrome Browser](https://www.google.com/chrome/)
  - Developer Tools
    - [Network Resources](https://developers.google.com/web/tools/chrome-devtools/profile/network-performance/resource-loading?utm_source=dcc)
      - Download as HAR File - upload to http://www.softwareishard.com/har/viewer/
  - Extensions
    - [Clear Session](https://chrome.google.com/webstore/detail/clear-session/maejjihldgmkjlfmgpgoebepjchengka)
- Have a DMZ Brower for testing: [Chrome Canary](https://www.google.com/chrome/browser/canary.html)
  - ```open -a Google\ Chrome\ Canary --args --disable-web-security -–allow-file-access-from-files```
    - Helpful with CORS issues for local development
- Get comfortable with a good text editor.
  - I recommend Atom or Sublime
- [Charles Proxy](https://www.charlesproxy.com/)
- [Postman](https://www.getpostman.com/)
- Emulation
  - [IE Virtual Machine](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/)
  - [iOS Simulator](https://developer.apple.com/library/ios/documentation/IDEs/Conceptual/iOS_Simulator_Guide/Introduction/Introduction.html)
  - [Android Emulator](https://developer.android.com/studio/run/emulator.html)
    - [Speeding up the emulator on Intel machines](https://software.intel.com/en-us/android/articles/speeding-up-the-android-emulator-on-intel-architecture)
