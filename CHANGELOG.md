## 1.1.3 (2017-01-17)

### Fixed:

- Import framework, not a module in ```FSDownloader```.

## 1.1.2 (2017-01-12)

### Added:

- Navigation bar title color can now themed.

## 1.1.0 (2017-01-12)

### Added:

- ```shouldDownload``` now works.
- Picker/Save controllers navigation bar title is now configurable (```title``` property of ```FSConfig```).
- Support for ```maxSize```.

## 1.0.6 (2016-09-14)

### Added:

- ```New Box authorization path.```

## 1.0.5 (2016-07-14)

### Fixed

- ```FSExporter``` now creates an empty ```storeOptions``` if copy returns nil.

## 1.0.4 (2016-07-12)

### Fixed

- Image rotation before uploading.
- Progress modal dismiss is no longer based on timing.

## 1.0.3 (2016-06-09)

### Fixed

- Initialize "empty" ```FSStoreOptions``` for uploading of local file if no options were provided in config.

## 1.0.0 (2016-05-27)

### Added:

- FSSaveController.

## 0.1.5-beta (2016-05-18)

### Fixed

- ```FSGridViewController``` crash on uploading multiple files.

## 0.1.4-beta (2016-05-17)

### Fixed:

- ```FSSearchViewController``` crash on uploading multiple files.

## 0.1.3-beta (2016-05-12)

### Fixed:

- Missing FSPicker.h source file added to pod.

## 0.1.2-beta (2016-05-11)

### Added:

- ```defaultToFrontCamera``` configuration option.
- ```selectMultiple``` option implementation.
- Small delay before dismissing upload progress view.

### Fixed:

- ```picker:didFinishedPickingMediaWithBlobs:``` should be now called only once, after finished upload.
- Web Search is now correctly returning results (if any present).
- FSPickerDelegate methods messages are now dispatched to main thread.

## 0.1.1-beta (2016-05-06)

### Initial beta release
