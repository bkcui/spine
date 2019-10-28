This module is backport version branch forked from (https://github.com/GodotExplorer/spine).
The master branch tagged with 2.1.25's current Godot version is 3.2 and I changed spine runtime that can run 2.1.25 version.
Some property of current version is depreciated, it may not fully compatible with current version.
So use this module only spine 2.1.25

## About the license

This module is forked from [GodotExplorer's branch](https://github.com/GodotExplorer/spine).

And GodotExplore's module is forked from [sanikoyes's godot branch](https://github.com/sanikoyes/godot/tree/develop/modules/spine) and some of the code is forked from [godot-spine-module](https://github.com/jjay/godot-spine-module). Both of the code are declared as MIT license.

The license of this module is under the [Spine Runtimes Software License](https://github.com/EsotericSoftware/spine-runtimes/blob/3.6/LICENSE).

## Usage

Add this code under `modules/spine` in your Godot source tree. You may either copy it or use `git submodule add`.

Build Godot using `scons platform=x11 tools=yes target=release_debug` or whatever [build options](http://docs.godotengine.org/en/latest/development/compiling/) you prefer.

Use the `Spine` type in your scene tree and load your animation into it as a resource.

## Further reference

The [Spine API Reference](http://esotericsoftware.com/spine-api-reference) is useful to learning more about how the code works.

