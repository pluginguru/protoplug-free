# protoplug-free
MIT-licensed version of [Protoplug](https://www.osar.fr/protoplug/).

[Protoplug](https://www.osar.fr/protoplug/) is a VST/AU plug-in that lets you load and edit [Lua](https://www.lua.org/) scripts as audio (or MIDI) effects and instruments. The original version was developed by [Pierre Cusa](https://github.com/pac-dev) and can be found on GitHub at https://github.com/pac-dev/protoplug. The code here was originally taken from [Sin-tel's fork of Protoplug](https://github.com/Sin-tel/protoplug), which I found to be a bit more recent.

Unfortunately, although the original Protoplug was published under the highly permissive [MIT License](https://en.wikipedia.org/wiki/MIT_License), it incorporated [Vinnie Falco's version](https://github.com/vinniefalco/VFLib/tree/master/modules/vf_freetype/FreeTypeAmalgam) of the [FreeType library](https://www.freetype.org/), which uses a more restrictive license. Since all this adds is a couple of fonts, I decided to purge it and create an "MIT-only" version of Protoplug.

The original [Protoplug repo](https://github.com/pac-dev/protoplug) (and its many forks) included many unnecessary files (not mapped out via *.gitignore*), and is thus much larger than it needs to be. In pursuit of a more minimalist approach, this repo is **not a direct fork of the original**, and hence, does not include the full Git history. This is most unfortunate, and I strongly advise readers to refer to [the original Protoplug repo](https://github.com/pac-dev/protoplug) to learn the full story.

Finally, I have chosen not to include the *ProtoplugFiles* folder, containing all of the Lua example files as well as many common files to implement the [Protoplug Lua API](https://www.osar.fr/protoplug/api/). The base version can be found at [Pierre Cusa's original Protoplug repo](https://github.com/pac-dev/protoplug), and an expanded version (with many more examples) is available in [Sin-tel's fork](https://github.com/Sin-tel/protoplug).
