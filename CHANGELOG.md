## [1.0.0](https://github.com/NYTimes/NYTPhotoViewer/releases/tag/1.0.0)

Changes for users of the library in 1.0.0:

- **The library now supports iOS 8.0 and newer.** ([#82](https://github.com/NYTimes/NYTPhotoViewer/pull/82), [#84](https://github.com/NYTimes/NYTPhotoViewer/pull/84), [#107](https://github.com/NYTimes/NYTPhotoViewer/pull/107))
- Support programmatic view controller dismissal via `dismissViewControllerAnimated:completion:` ([#121](https://github.com/NYTimes/NYTPhotoViewer/pull/121), [#122](https://github.com/NYTimes/NYTPhotoViewer/pull/122))
- Use scrolling `UITextView` for captions ([#88](https://github.com/NYTimes/NYTPhotoViewer/pull/88))
- Fix a bug when presenting NYTPhotoViewer from a subview of `UIStackView` ([#104](https://github.com/NYTimes/NYTPhotoViewer/pull/104))
- Update overlay information after `displayPhoto:` call ([#100](https://github.com/NYTimes/NYTPhotoViewer/pull/100))
- Implements animated GIF support ([#71](https://github.com/NYTimes/NYTPhotoViewer/pull/71), [#94](https://github.com/NYTimes/NYTPhotoViewer/pull/94), [#106](https://github.com/NYTimes/NYTPhotoViewer/pull/106), [#111](https://github.com/NYTimes/NYTPhotoViewer/pull/111))
- Fix misplacing view position while zoom transition ([#89](https://github.com/NYTimes/NYTPhotoViewer/pull/89))
- Adopt CocoaPods `resource_bundles` and fix resource image loading ([#80](https://github.com/NYTimes/NYTPhotoViewer/pull/80), [#113](https://github.com/NYTimes/NYTPhotoViewer/pull/113), [#123](https://github.com/NYTimes/NYTPhotoViewer/pull/123))
- Use iOS 8 `UIActivityViewController.completionWithItemsHandler` API ([#82](https://github.com/NYTimes/NYTPhotoViewer/pull/82))
- Nullability and lightweight generics annotations on important public API ([#83](https://github.com/NYTimes/NYTPhotoViewer/pull/83), [#98](https://github.com/NYTimes/NYTPhotoViewer/pull/98))
- Fix circular reference of `NYTPhotosViewController` ([#79](https://github.com/NYTimes/NYTPhotoViewer/pull/79))
- Set `barButtonItem` on popover `UIActivityViewController`s ([#65](https://github.com/NYTimes/NYTPhotoViewer/pull/65/))
- Accept Xcode 7 build settings and fix Xcode 7 warnings ([#76](https://github.com/NYTimes/NYTPhotoViewer/pull/76))
- Ensure our nav bar will always be translucent with no tint color ([#57](https://github.com/NYTimes/NYTPhotoViewer/pull/57))
- Fix crash on tapping Share button on iPad ([#52](https://github.com/NYTimes/NYTPhotoViewer/pull/52))
- Allow customizing maximum photo zoom scale([#51](https://github.com/NYTimes/NYTPhotoViewer/pull/51))
- Rename `…didDisplayPhoto…` delegate method to `…didNavigateToPhoto…` ([#47](https://github.com/NYTimes/NYTPhotoViewer/pull/47))
- Adds support for setting `rightBarButtonItems` and `leftBarButtonItems` on `NYTPhotosViewController` ([#49](https://github.com/NYTimes/NYTPhotoViewer/pull/49))

## [0.1.2](https://github.com/NYTimes/NYTPhotoViewer/releases/tag/0.1.2)

Initial open-source release.
