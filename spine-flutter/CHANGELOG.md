# 4.1.10
# Update WASM binaries

# 4.1.9
# Fixes #2412, single bone, translation only IK constraints did not take skeleton scale into account.

# 4.1.8
* Fixes compilation errors due to API change in Flutter 3.16.0, see [this issue](https://github.com/EsotericSoftware/spine-runtimes/issues/2420). **Note**: Depending on this version requires your project to depend on Flutter >= 3.16.0 as well.

# 4.1.7
* Fix allocation patter for temporary structs on Windows, which resulted in a hard crash without a stack trace on the native side.

# 4.1.6
* Fixed bug in path handling on Windows.

# 4.1.5
* Updated http dependency to 1.1.0

# 4.1.4
* Fixes for WASM/web builds.

# 4.1.3
* Fixes for Impeller.

# 4.1.2
* API documentation and minor cosmetics.

# 4.1.1
* Backport to 4.1 spine-runtimes branch.
* Blend mode support.
* Hot-reload support. The underlying `SkeletonDrawable` will be retained if the asset file names and type provided to the `SpineWidget` constructor has not changed.

# 4.2.11
* Update README.md with setup and development instructions.

# 4.2.10
* Update README.md to point to Junji's Dart-only Spine runtime.

# 4.2.9
* Fix atlas parsing.

# 4.2.8
* Change reversed positional argument order in `SpineWidget` constructors.

# 4.2.7
* Change package name from  `esotericsoftware_spine_flutter` to `spine_flutter`.

# 4.2.6
* Fix analyzer errors, fix code style to adhere to Dart standards.

# 4.2.5
* Implemented batching of render commands, reducing the number of draw calls. 60/120fps for 100 Spineboys on all platforms.

# 0.0.4
* Clean-up `fromAsset()` factory methods so the atlas comes before skeleton data file name.
* Rename `Vector2` to `Vec2`.
* Make the bundle configurable in `SpineWidget.asset()`.

# 0.0.3
* Lower macOS deployment target to 10.11.

# 0.0.2
* Fix package name in build system `spine_flutter` > `esotericsoftware_spine_flutter`.

# 0.0.1
Initial test release.