# Changelog

All notable changes to this project will be documented in this file, in reverse chronological order by release.

## 0.1.5 - 2017-07-12

### Added

- Adds documentation; see the [doc/book/](doc/book/) tree, or browse at
  https://weierophinney.github.io/hal/

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 0.1.4 - 2017-07-12

### Added

- Adds the method `templatedFromRoute()` to the `LinkGenerator` class. Acts
  exactly like `fromRoute()`, but the generated `Link` instance will have the
  `isTemplated` property toggled `true`.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 0.1.3 - 2017-07-11

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Fixes registration of the `MetadataMap` in the `ConfigProvider`; it was
  previously using an incorrect namespace.

## 0.1.2 - 2017-07-11

### Added

- Adds `HalResponseFactoryFactory`, a factory for generating a
  `HalResponseFactory` instance.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 0.1.1 - 2017-07-11

### Added

- Adds the ability to inject route params and query string arguments at run-time
  to the route-based metadata instances.

  When dealing with route-based metadata, we may be dealing with
  sub-resources; in such cases, the route parameters may be derived from
  the request, and we will want to inject them at run-time.

  When dealing with collections, the query string arguments may indicate
  things such as searches, sort directions, sort columns, filters, limits,
  etc.; these will be derived from the request, and need to be injected at
  run-time.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 0.1.0 - 2017-07-10

Initial Release.

### Added

- Everything.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.