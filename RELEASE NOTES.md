Version 1.3

- added stripEmptyNodes property (defaults to YES)
- added arrayValueForKeyPath, stringValueForKeyPath and dictionaryValueForKeyPath methods to simplify working with data

Version 1.2.2

- sharedInstance method no longer returns a new instance each time

Version 1.2.1

- Removed isa reference, deprecated in iOS 7

Version 1.2

- Exposed XMLDictionaryParser object, which can be used to configure the parser
- Parsing options can now be changed without modifying the library
- Added option to always encode properties as arrays
- `__name` and `__coment` keys are no longer included by default
- Apostrophe is now encoded as `&apos;`
- removed `attributeForKey:` method

Version 1.1

- Updated to use ARC
- Added podspec

Version 1.0

- Initial release