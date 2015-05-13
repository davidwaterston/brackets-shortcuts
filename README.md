## brackets-shortcuts

<a href="http://semver.org" target="_blank" alt="Semantic Versioning"><img src="https://img.shields.io/badge/semver-1.0.0-lightgrey.svg?style=flat-square"></a>
<a href="https://github.com/davidwaterston/brackets-shortcuts/blob/master/LICENSE" target="_blank" alt="MIT License"><img src="http://img.shields.io/badge/license-MIT-blue.svg?style=flat-square"></a>
<a href="#verifying-releases" alt="Releases signed with Gnu Privacy Guard"><img src="https://img.shields.io/badge/gpg-signed-green.svg?style=flat-square"></a>
<a href="https://gitter.im/davidwaterston/brackets-shortcuts" target="_blank" alt="Join the chat at https://gitter.im/davidwaterston/brackets-shortcuts"><img src="https://badges.gitter.im/Join%20Chat.svg"></a>

A set of flashcards that cover the essential keyboard shortcuts ("hot keys") available in the [Brackets](http://brackets.io/) editor on the Mac OSX operating system. Multiple formats are included to allow import into most popular Flashcard apps.


##What's included?
The shortcuts are provided in four different formats:   

- **brackets-shortcuts-tilde.txt**  
The shortcuts in *tilde-delimited* (~) format. These can be imported into many applications such as [Quizlet](http://quizlet.com) or [Cram](http://www.cram.com).
The file is tilde rather than comma-delimited because some of the definitions may contain a comma. Most apps will allow you to specify the delimiter character so this file will import into the vast majority of applications. 
For some applications to recognize the file you may have to change the extension.

- **brackets-shortcuts-tab.txt**  
The shortcuts in *tab-delimited* format. The second most popular format, when tilde-delimited is not supported.
For some applications to recognize the file you may have to change the extension.

- **brackets-shortcuts-excel.xls**  
The shortcuts in Microsoft Excel 97-2004 format. These can be imported into apps which don't support delimited files.  
This file can also be used to easily manipulate and export the shortcuts to other formats.

- **brackets-shortcuts.studyarch**  
The shortcuts in *Mental Case* Study Archive format. *Mental Case* is a popular Flashcard application available for Mac OSX and iOS. Although it supports many import formats, "Study Archive" is the most convenient. 


##Ready Mades  
If you would prefer to use these cards online without downloading and importing them yourself they are available at the following websites:  

* [Quizlet](https://quizlet.com/82915780/brackets-for-mac-version-13-flash-cards)
* [Cram](http://www.cram.com/flashcards/brackets-for-mac-version-13-5842118)
* [Flashcard Machine](http://www.flashcardmachine.com/flashcards/?topic_id=3247613)
* [Study Blue](https://www.studyblue.com/#flashcard/view/14662571)

All of these sites have free signup and mobile apps.


## Compatibility
These keyboard shortcuts are compatible with Brackets for Mac, version 1.3+. 
  
  
## Release History
See the [change log](https://github.com/davidwaterston/brackets-shortcuts/blob/master/CHANGELOG.md) file for more details.


## Verifying Releases
I use <a href="http://semver.org" target="_blank" alt="Semantic Versioning">Semantic Versioning</a> to number releases. Each release is tagged with the appropriate version number and signed using <a href="https://www.gnupg.org" target="_blank" alt="Gnu Privacy Guard (GPG)">Gnu Privacy Guard (GPG)</a>. The public key used to sign releases is  
```
Name: David Waterston  
Email: david@davidwaterston.com  
Key ID: A7AD9C85  
Signature: 71A9 DC13 447A 1E4F C6EB  5D64 DE08 A991 A7AD 9C85  
```
This public key is included in the repository with a SHA1 of 16d013451476fa4a1a67d6ad4b90583e205b53b1.  
After cloning the repo, and assuming you have GPG installed correctly, you can import this key into your keychain
```
git cat-file blob pubkey | gpg --import
```
When this public key is successfully imported, you can use it to verify the integrity of any of the tagged releases of this repo
```
git tag -v v1.7.0
```
which should produce output similar to:
```
object 04f37a55784c1f3abc2cf927a935a488aa954035  
type commit  
tag v1.4.0  
tagger David Waterston <david@davidwaterston.com> 1427387056 +0000  
  
Update the thing to be more like the other thing.  
  
Make a really useful update to stuff.
gpg: Signature made Thu 26 May 16:24:16 2015 GMT using RSA key ID A7AD9C85
gpg: Good signature from "David Waterston <david@davidwaterston.com>" [ultimate]
```
The important thing to notice here is that the RSA key ID matches mine (A7AD9C85) and the line that says that this is a good signature.  
  
  The public key can further be verified by checking the details held on <a href="http://pgp.mit.edu/pks/lookup?search=david%40davidwaterston.com&op=index&fingerprint=on&exact=on" target="_blank" alt="pgp.mit.edu">pgp.mit.edu</a>.
  
  
## License
Copyright (c) 2015 David Waterston. All rights reserved.  
Distributed under an MIT license. See the [LICENSE](https://github.com/davidwaterston/brackets-shortcuts/blob/master/LICENSE) file for more details.
