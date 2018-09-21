---
layout: post
title:  Open Source Licensing
categories:
tags: licence
author: Matt Clifford
---

* content
{:toc}

Open source licensing comparison report.<!--more-->

## Copyleft vs Permissive ##

The two main differences between open source licences are whether they are copyleft or permissive.

### Pros of copyleft ##
* Any derivative works must make the source code available, these modifications might be useful to incorporate into our package.
* Forces future usage to remain free and open to the public to modify.

### Cons of copyleft ###
* Could deter people from using or modifying if they don't want to make derivative work available, especially if using a strong copyleft licence which forces any linked work to be under copyleft licence not just derivatives of copyleft code.

### Pros of permissive ###
* Can add proprietary features if needed.
* Developers are more likely to use and make modifications, since they aren't forced to publish derivative source code.

### Cons of permissive ###
* Other developers could be unwilling to contribute if they think it will be used to commercial gain at a later date, or are set on the copyleft ideology.
* Any derivative works are not forced to be made available.


## Strong vs Weak Copyleft ##
There are two types of copyleft, weak and strong. Weak copyleft is usually used for software libraries as it allows other software to link to the library, meaning that only changes to the weak-copylefted software itself become subject to the copyleft provisions, not the linked libraries. Strong copyleft ensures that all code linked to the strong copyleft code has the same strong copyleft licensing.


## Open Source Initiative Popular Copyleft Licences ##
### [GNU GPLv3](https://opensource.org/licenses/GPL-3.0) — fifth most popular licence on GitHub (9%) ###
A strong copyleft licence, meaning that any modification made to the source code needs to be made available and published with the same GPLv3 licensing. This means that it is incompatible with BSD-licensed code ie. NumPy, SciPy etc.

### [GNU Affero GPLv3](https://opensource.org/licenses/AGPL-3.0) ###
The same as GPLv3 but if you run a modified program on a server and let other users communicate with it there, your server must also allow them to download the source code corresponding to the modified version running there. This addresses the 'Cloud Loophole' in GPLv3.

### [GNU Lesser GPLv3](https://opensource.org/licenses/LGPL-3.0) ###
The same as GPLv3 but allows work to be linked with non GPL licensed programmes, making this a weak copyleft licence.

### [Mozilla Public Licence 2.0](https://opensource.org/licenses/MPL-2.0) ###
A weak copyleft that is compatible with GPLv3, which allows derivative works to be released under any licence, including a proprietary licence, but source code must be disclosed.

### [Eclipse Public Licence 2.0](https://opensource.org/licenses/EPL-2.0) ###
A weak copyleft, that can be made compatible with GPLv3. Only the EPL modified code has to be released under EPL licence, even if full programme is released under a different licence.


## Open Source Initiative Popular Permissive Licences ## 
### [Apache Licence 2.0](https://opensource.org/licenses/Apache-2.0) — fourth most popular licence on GitHub (11%) ###
Allows sub-licensing and contains patent protection, which describes the rights to practice patent claims of contributors to the code. Any significant changes to the Apache source code must be stated to the authors, but the source code does not need to be published.

### [MIT Licence](https://opensource.org/licenses/MIT) — most popular licence on GitHub (45%) ###
Short and simple licence which allows merging, publishing, sub-licensing and selling.

### [BSD Licence](https://opensource.org/licenses/BSD-3-Clause) — sixth most popular licence on GitHub (4.5%) ###
2 clause version implies merging, publishing and selling. Added 3rd clause version addresses advertising, meaning that derivate code cannot advertise implying endorsement from original developers. Added 4th clause version addresses promotion. Scikit learn uses the 'new' 3-clause licence version.

## Other Popular Licences ##
### [The Unlicense](https://choosealicense.com/licenses/unlicense/) — seventh most popular licence on GitHub (1.8%) ###
Fully turning over to the public domain, with a no-warranty statement.


## BSD vs MIT ##
BSD and MIT are compact and simple licences, with the 2 clause BSD and MIT licences being very similar. However the MIT licence explicitly allows merging, publishing, sub-licensing and selling, whereas BSD only implies implies merging, publishing and selling under its permission of redistribution. This makes the MIT licence more attractive due to its unambiguity. However, one reason the 3-clause BSD might be suitable for our package is simply because it is the licence used by scikit learn.

## Package Licences ##
* Scikit Learn - BSD 3 Clause
* NumPy - BSD 3 Clause
* SciPy - BSD 3 Clause
* Shap - MIT
* Skater - MIT
* eli5 - MIT
* FairTest - Apache 2.0
* BlackBoxAuditing - Apache 2.0
* FairML - MIT
* FairLearn - MIT
