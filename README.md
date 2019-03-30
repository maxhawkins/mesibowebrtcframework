# WebRTC framework for iOS - static version

## Why this framework?
It's an unfortunate decision on Google's part to remove the static target from the [WebRTC](https://webrtc.org/native-code/ios/) build. There are a couple of requests including [this one](https://bugs.chromium.org/p/webrtc/issues/detail?id=10008) for the rollback on WebRTC issue tracker, unfortunately, Google marked then as `WontFix` and hence this framework.

Here you will find WebRTC static framework for iOS recompiled using modified ninja files. This framework has some additional [Mesibo](https://mesibo.com) specific code. Note that, Mesibo specific code is additional and has no impact on the original API. You can use it even if you are not using Mesibo.

## Bitcode
Additionally, this build is bit code enabled unlike [Google version](https://webrtc.org/native-code/ios/) which is NOT bit code enabled.

## Open Source Messenger App For iOS
This framework is used in [Open Source Messenger App For iOS](https://github.com/mesibo/messenger-app-ios)
