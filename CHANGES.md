### Version 1.0 ###

* Initial Release of EnlighterJS (fork of [Lighter.js](https://github.com/pradador/Lighter) v3.0)
* Added ANT based build-script and utilities (YUI-compressor)
* Included prebuilds within the new GIT repository
* Added current MooTools build (1.4.5)
* Modified the testcases (now generated by ANT-buildfile)
* Renamed Fuels/Flames/Wick into conventional scheme Language/Themes/Token/Tokenizer
* Added SQL, Java testcases
* Added Apache Ant-contrib package (required for the new build script)
* Removed Loader.js - themes&languages are now bundled with the build
* Modified the complete software-architecture (tokenizers are now initialized by the chosen language)
* Modified the usage - one EnlighterJS instance per codeblock is required (strict oop design)
* Modified the usage - HTML5 data- attributes are used instead of css class attribute language:theme combo
* Added XML and HTML support (incorrect html support got fixed)
* Added support for tab based code-groups (displays multiple code-blocks within a tab-pane)
* Removed the outdated class-documentation of Lighter.js (extensive documentation/inline comments are in the source files)