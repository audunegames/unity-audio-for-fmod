# Audune Audio for FMOD

This repository contains scripts to enhance the **FMOD for Unity** package, which is used in Audune's own projects.

The FMOD for Unity package provides a thin wrapper around the C/C++ FMOD studio code and confronts the developer with many C++ paradigms ported to C#. This package was made to make the use of that package easier from a C# perspective, using C# paradigms like properties and events out of the box.

See the [wiki](https://github.com/audunegames/unity-audio-for-fmod/wiki) of the repository to get started with the package.

## Installation

### Requirements

This package depends on the following external dependencies. Make sure you have these installed before installing this package. The package might work with lower versions of the dependencies, but those have not been tested:

* [FMOD for Unity](https://fmod.com/download#fmodforunity) >=2.02.21

### Installing from the OpenUPM registry

To install this package as a package from the OpenUPM registry in the Unity Editor, use the following steps:

* In the Unity editor, navigate to **Edit › Project Settings... › Package Manager**.
* Add the following Scoped Registry, or edit the existing OpenUPM entry to include the new Scope:

```
Name:     package.openupm.com
URL:      https://package.openupm.com
Scope(s): com.audune.audio.fmod
```

* Navigate to **Window › Package Manager**.
* Click the **+** icon and click **Add package by name...**
* Enter the following name in the corresponding field and click **Add**:

```
com.audune.pickle
```

### Installing as a Git package

To install this package as a Git package in the Unity Editor, use the following steps:

* In the Unity editor, navigate to **Window › Package Manager**.
* Click the **+** icon and click **Add package from git URL...**
* Enter the following URL in the URL field and click **Add**:

```
https://github.com/audunegames/audio-for-fmod.git
```

## License

This package is licensed under the GNU LGPL 3.0 license. See `LICENSE.txt` for more information.
