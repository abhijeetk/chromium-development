This repository contains information related to chromium developement.

-  [Reproduce a clusterfuzz issue](https://github.com/abhijeetk/chromium-development/wiki/Clusterfuzz)
-  [WPT](https://github.com/abhijeetk/chromium-development/wiki/WPT)
-  [Olipan](https://docs.google.com/presentation/d/1XPu03ymz8W295mCftEC9KshH9Icxfq81YwIJQzQrvxo/edit#slide=id.gbdc7c2c05_0_1108)
-  Check commit hash part of which chromium release.
   - https://omahaproxy.appspot.com/ OR
   - git find-releases commit_hash

- [How Browser works ? ](https://developer.chrome.com/blog/inside-browser-part1/)
- Running test on android
`out/android_release/bin/run_components_unittests --avd-config tools/android/avd/proto/generic_android30.textpb  --emulator-window -f "StarterFencedFrameTest.*" -v`

