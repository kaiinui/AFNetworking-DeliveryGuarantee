AFNetworking-DeliveryGuarantee
==============================

An `AFNetworking` category that guarantees delivery using Background Completion Task (which added on iOS6), Background Transfer Service (which added on iOS7), Background Fetch (iOS7) with appropriate fallbacks.

It queues request operations and try to request until it returns successive http status code.

References
---

- ios - Long-Running Upload Task In Background - Stack Overflow : http://stackoverflow.com/questions/20576302/long-running-upload-task-in-background
- Multitasking in iOS 7 - iOS 7 - objc.io issue #5 : http://www.objc.io/issue-5/multitasking.html
- アプリのバックグラウンド処理 | iOS 7エンジニア勉強会 : http://www.slideshare.net/techblogyahoo/3-ios7-workshopmultitask-26997115
