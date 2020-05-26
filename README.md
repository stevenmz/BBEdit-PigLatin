# BBEdit-PigLatin
===============

A codeless language module (CLM) to provide syntax highlighting and other features for the Pig Latin language to the TextWrangler / BBedit text editor.

## Purpose
[Text Wrangler](http://www.barebones.com/products/textwrangler/) is a free graphical text editor for OS X that provides a good solution to developers that do not want to open heavyweight IDEs like Eclipse or NetBeans. Text Wrangler comes with built-in support for many languages, though Pig Latin is not one of them.

[Pig Latin](http://pig.apache.org/docs/r0.14.0/basic.html) is the high-level language used by the [Apache Pig project](http://pig.apache.org/) to allow allow developers to quickly code or explore their data analysis tasks. This CLM is based off of the [Pig Latin Reference Manual 2](https://pig.apache.org/docs/r0.7.0/piglatin_ref2.html).

This project merges the efforts of TextWrangler with Pig by providing the syntax highlighting and other features of TextWrangler for Pig Latin script files.

## Installation
### Text Wrangler
1. Fully quit from any running instance of TextWrangler
2. Download the pig.plist file above.
3. Copy the pig.plist file into /Applications/TextWrangler.app/Contents/Language Modules/
4. Start TextWrangler and open any file with the extension .pig to enjoy syntax highlighting.

### BBEdit (Untested)
1. Fully quit from any running instance of BBEdit
2. Download the pig.plist file above.
3. Copy the pig.plist file into /Library/Application Support/BBEdit/Language Modules/ creating directories as needed.
4. Start BBEdit and open any file with the extension .pig to enjoy syntax highlighting.

Contributions and feedback are welcome!
