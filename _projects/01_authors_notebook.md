---
title: AuthorsNotebook
icon: icons/ANB_AppIcon_120.png
---

AuthorsNotebook is a suite of applications focused on helping authors create
novels.

The project is run on a few key ideals:

* *Professional* The target audience is professional authors, or those wishing
  to be professional.
* *Users own their content* The users should be able to access their data easily
  without the application. The formats must be easily interpreted - by non-tech
  professionals
* *Orthogonality* Libraries should do one thing and do it well. Applications
  will wrap these functional pieces.

The components currently under development are

## twirl <img src="icons/rust.svg" class=icon>
**STATUS** Under development - not yet publicly released.

Twirl is a markdown library for rust designed to support lossless conversion and
commonmark compatibility. In particular we should be able to convert a text
document to an AST and back without change in the content (unlike existing
markdown libraries)

It does not aim to be fast, or memory light. Hopefully it will be both of the
above, but we wont sacrifice the primary aims to obtain these.

It's primary use in AuthorsNotebook is to allow the use of markdown as the
data storage format. 

## [markovian](https://github.com/mikeando/markovian) <img src="icons/rust.svg" class=icon>
**STATUS** WIP - but currently usable and public.

Rust library and application for text generation using Markov chains and grammars.

## [inscenerator] <img src="icons/rust.svg" class=icon>
**STATUS** Under development - not yet public

The main application and AuthorsNotebook libraries.

Can currently process directories of structured markdown files to create
annotated documents of various forms - including high level
summaries, annotated drafts and drafts matching the 
format required for submission to professional publishers and editors.

Planned features include better support for research, plotting and world-building.
Also gamification of targets, and "walk-throughs".

Some form of integration with git to provide versioning and mobile access is also planned.

