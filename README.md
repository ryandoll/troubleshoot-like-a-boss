# Troubleshoot Like a Boss

![Like a Boss](assets/likeaboss.jpg)

Nobody's code is perfect, and all browsers don't run that code the exact same way. A developer can be staring at the weirdest issue ever with no clue where to begin troubleshooting. Sometimes, searching Stack Overflow for related issues can feel like an exercise in futility. A developer's mettle can be tested when this happens, so having the right tools and the proper mindset can mean the difference between a five minute fix, and an all-nighter. This repo will serve as a great place for storing tips for troubleshooting, list some great tools, as well as be reference point for new devs who are trying to level up their trouble shooting skill.  Please feel free to submit a PR for any extra tools or tips you think should be added to the list.


[Presentation Slides](https://slides.com/ryandoll/troubleshoot-like-a-boss)

## Key Points
- Have a (good) browser you know inside and out - [Chrome Browser](https://www.google.com/chrome/)
  - Developer Tools
    - [Network Resources](https://developers.google.com/web/tools/chrome-devtools/profile/network-performance/resource-loading?utm_source=dcc)
      - Download as HAR File - upload to http://www.softwareishard.com/har/viewer/
      - Demo
  - Extensions
    - [Clear Session](https://chrome.google.com/webstore/detail/clear-session/maejjihldgmkjlfmgpgoebepjchengka)
    - [JSONView](https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc?hl=en)
- Have an isolated browser just for testing: [Chrome Canary](https://www.google.com/chrome/browser/canary.html)
  - ```open -a Google\ Chrome\ Canary --args --disable-web-security -–allow-file-access-from-files```
    - Helpful with CORS issues for local development
- Know your [HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)
- Proxy all the things!
  - [Fiddler](http://www.telerik.com/fiddler)
    - Debugging with Fiddler by Eric Lawrence (http://fiddlerbook.com/book/)
  - [Charles Proxy](https://www.charlesproxy.com/)
    - Looking at your browser traffic is easily handled through Chrome Developer Tools, but Charles can show requests from other applications like the iOS Simulator.
    - Most sites are using SSL, so you need to [configure Charles for SSL proxying](https://www.charlesproxy.com/documentation/using-charles/ssl-certificates/)!
    - Demo
      - Let's change the content of github.com!
- Know your IDE/Editor
  - Who cares what the editor is...find the one that YOU are most comfortable with!
- Know your version control tools inside and out
  - [Git](https://git-scm.com/book/en/v2)
  - [SVN](http://svnbook.red-bean.com/)
- Learn to love the command line
- Use Postman for API Testing
  - [Postman](https://www.getpostman.com/)
    - Demo if time
- Emulation
  - [IE Virtual Machine](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/)
  - [iOS Simulator](https://developer.apple.com/library/ios/documentation/IDEs/Conceptual/iOS_Simulator_Guide/Introduction/Introduction.html)
  - [Android Emulator](https://developer.android.com/studio/run/emulator.html)
    - [Speeding up the emulator on Intel machines](https://software.intel.com/en-us/android/articles/speeding-up-the-android-emulator-on-intel-architecture)

[License](LICENSE.md)
