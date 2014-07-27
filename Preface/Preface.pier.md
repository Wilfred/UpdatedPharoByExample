

##Preface




###1\. What is Pharo?


Pharo is a modern, open source, fully\-featured implementation of the Smalltalk programming language and environment\. Pharo is derived from Squeak \(see Dan Ingalls et al\., Back to the Future: The Story of Squeak, a Practical Smalltalk Written in Itself\. [Link](http://www.cosc.canterbury.ac.nz/~wolfgang/cosc205/squeak.html) \), a re\-implementation of the classic Smalltalk\-80 system\.

Whereas Squeak was developed mainly as a platform for developing experimental educational software, Pharo strives to offer a lean, open\-source platform for professional software development, and a robust and stable platform for research and development into dynamic languages and environments\. Pharo serves as the reference implementation for the Seaside web development framework\.

Pharo resolves some licensing issues with Squeak\. Unlike previous versions of Squeak, the Pharo core contains only code that has been contributed under the MIT license\. The Pharo project started in March 2008 and the first 1\.0 beta version was released on July 31, 2009\. The current version is Pharo 3\.0 and it was released beginning of May 2014\.

Although Pharo removes many packages from Squeak, it also includes numerous features that are optional in Squeak\. For example, true type fonts are bundled into Pharo\. Pharo also includes support for true block closures\. The user interfaces has been simplified and revised\.

Pharo is highly portable \- even its virtual machine is written entirely in Smalltalk, making it easy to debug, analyze, and change\. Pharo is the vehicle for a wide range of innovative projects from multimedia applications and educational platforms to commercial web development environments\.

There is an important aspect behind Pharo: Pharo should not just be a copy of the past but really reinvent Smalltalk\. Big\-bang approaches rarely succeed\. Pharo will really favor evolutionary and incremental changes\. We want to be able to experiment with important new features or libraries\. Evolution means that Pharo accepts mistakes and is not aiming for the next perfect solution in one big step \- even if we would love it\. Pharo will favor small incremental changes but a multitude of them\. The success of Pharo depends on the contributions of its community\.



###2\. Who should read this book ?

This book is based on [Squeak by Example](http://SqueakByExample.org) , an open\-source introduction to Squeak written by the authors\. The book has been liberally adapted and revised to reflect the differences between Pharo and Squeak\. This book presents the various aspects of Pharo, starting with the basics, and proceeding to more advanced topics\.

This book will not teach you how to program\. The reader should have some familiarity with programming languages\. Some background with object\-oriented programming would be helpful\.

This book will introduce the Pharo programming environment, the language and the associated tools\. You will be exposed to common idioms and practices, but the focus is on the technology, not on object\-oriented design\. Wherever possible, we will show you lots of examples\. We have been inspired by Alec Sharp’s excellent book on Smalltalk \(Alec Sharp, [Smalltalk by Example](Http://stephane.ducasse.free.fr/FreeBooks/ByExample)\. McGraw\-Hill, 1997\)\.

There are [numerous other books on Smalltalk freely available on the web](http://stephane.ducasse.free.fr/FreeBooks.html) but none of these focuses specifically on Pharo\.



###3\. A word of advice


Do not be frustrated by parts of Smalltalk that you do not immediately understand\. You do not have to know everything\! Alan Knight expresses as follows:

**Try not to care**\. Beginning Smalltalk programmers often have trouble because they think they need to understand all the details of how a thing works before they can use it\. This means it takes quite a while before they can master Transcript show: 'Hello World'\. One of the great leaps in OO is to be able to answer the question “How does this work?” with "I don't care"\.



###4\. An open book

This book is open book in the following senses:



- The content of this book is released under the Creative Commons Attribution\-ShareAlike \(by\-sa\) license\. In short, you are allowed to freely share and adapt this book, as long as you respect the conditions of the license available at the following [URL:http://creativecommons\.org/licenses/by\-sa/3\.0/](http://creativecommons.org/licenses/by-sa/3.0/)\.



- This book just describes the core of Pharo\. Ideally we would like to encourage others to contribute chapters on the parts of Pharo that we have not described\. If you would like to participate in this effort, please contact us\. We would like to see this book grow\!



- It also possible to contribute directly to this book via Github \. Just follow the instructions there and ask any question to the mailing list\. You can find the Github repo here [https://github\.com/SquareBracketAssociates/UpdatedPharoByExample](https://github.com/SquareBracketAssociates/UpdatedPharoByExample)



###5\. The Pharo community

The Pharo community is friendly and active\. Here is a short list of resources that you may find useful:



- [http://www\.pharo\.org](http://www.pharo.org) is the main web site of Pharo
- In irc you can find us in freedone\.net server , channel "pharo"
- you can also ask questions in stackoverflow [http://stackoverflow\.com/questions/tagged/pharo](http://stackoverflow.com/questions/tagged/pharo) with the tag "pharo" and "smalltalk"\.
- [http://www\.smalltalkhub\.com/](http://www.smalltalkhub.com/) is the equivalent of SourceForge for Pharo projects\. Many optional packages for Pharo live there\.



###6\. Examples and exercises

We make use of two special conventions in this book\.

We have tried to provide as many examples as possible\. In particular, there are many examples that show a fragment of code which can be evaluated\. We use the symbol \-> an expression and to indicate the result that you obtain when you select an expression and **print it**:



<a name="script1"></a>**Small example
**

```smalltalk
3 + 4
\-\> 7 "if you select 3+4 and 'print it', you will see 7"
```



In case you want to play in Pharo with these code snippets, you can download a plain text file with all the example code from the book's web site: [http://PharoByExample\.org](http://PharoByExample.org)\.





###7\. Acknowledgments

We would first like to thank the original developers of Squeak for making this amazing Smalltalk development environment available as an open source project\.

We would also like to thank Hilaire Fernandes and Serge Stinckwich who allowed us to translate parts of their columns on Smalltalk, and Damien Cassou for contributing the chapter on streams\. We especially thank Alexandre Bergel, Orla Greevy, Fabrizio Perin, Lukas Renggli, Jorge Ressia and Erwann Wernli for their detailed reviews\.

We thank the University of Bern, Switzerland, for graciously supporting this open\-source project and for hosting the web site of this book\.

We also thank the Squeak community for informing us of the errors found in the first edition of this book\.

We also thank the Pharo community for their enthusiastic support of this book project\. Thank for all the translations\.