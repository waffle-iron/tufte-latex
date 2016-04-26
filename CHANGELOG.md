# Changelog

## Unreleased
### Added
* CHANGELOG.md to document changes in the project.
* Project changes from git diff.
* Treat i.e., and e.g. as full fledged citizens of the English language.

### Changed
* Merged History.txt with CHANGELOG.md.
* Update UK TeX FAQ link.

### Fixed
* Fixed bug with `\frontmatter` and `\mainmatter` and `openany` option.

### Removed
* History.txt in place of CHANGELOG.md.
* Obsolete `usenames` option from `xcolor` package.

## 3.5.2 - 2015-06-21
### Fixed
* A variety of bug fixes and small improvements.

## 3.5.1 - 2010-03-28
### Added
*  Added bibliography style that didn't make it into the intial release.

## 3.5.0 - 2009-12-11
### Added
* Added a `nohyper` document class option that suppresses loading of the
  `hyperref` package.
* Added three commands to modify the positioning of the captions.
* Now automatically recalculates the lengths in case you've modified the page
  size or margins.
* Added a B5 paper size.
* The justification of sidenotes, margin notes, captions, and citations can be
  set individually now.
* The font and style of sidenotes, margin notes, captions, and citations can
  now be set individually.
* The `\caption` command now accepts an optional vertical offset argument.
* Added the `\morefloats` command that works in the same way the morefloats
  package does.

### Fixed
* Fixed a number of bugs.

## 3.0.0 - 2009-05-17
### Added
* Created a Tufte-book document class.
* Added optional offset parameter to sienotes, cite, etc. so their vertical
  position can be adjusted manually.
* Added support for the `bidi` package with XeLateX.

### Changed
* Adjusted font sizes and spacing to more closely reflect those used in
  Tufte's books.
* Captions are now typeset in the margin as in Tufte's books.

## 2.0.1 - 2008-11-16
### Changed
* Now works with `footmisc` version > 5.4.

## 2.0.0 - 2008-06-06
### Added
* Added `sfsidenotes` option to set the sidenotes and captions in the sans
  serif font.
* Use the Palatino fonts if they're installed.
* Created `marginfig` and `margintab` environments.
* Added running heads.
* Added `\section` and `\subsection` headings.
* Uses the Bera Mono fonts if they're installed.
* Added `symmetric` option to produce outside-margin sidenotes in two-sided
  spreads.
* Added `justified` option to set the text fully justified.

### Changed
* Rewrote sample-handout to illustrate the tufte-handout usage and serve as an
  example of its features.

### Fixed
* Fixed the alignment of sidenote numbers.

## 1.2.3 - 2008-02-11
### Changed
* Updated README.txt

### Removed
* To remove References section from sample-handout.

## 1.2.2 - 2008-02-09
### Added
* Use `footmisc` package to set `\footnotes` as sidenotes.
* Use `natbib` package to set bibliography entries as sidenotes.

## 1.2.1 - 2007-10-21
### Added
* To assure existing `\footnotes` become `\sidenotes`.

## 1.2.0 - 2007-10-20
### Added
* Added `a4paper` option (Kevin Godby).
* Have `\margin{note,figure,table}` use `\@tufteh@marginfont`.
* `\@tufteh@overhang` typo in `figure*`, `table*`, and `fullwidth` environments (Kevin Godby).

## 1.1.0 - 2007-10-18
### Added
* To add some missing environments and commands:
  * `sidenote`.
  * `marginnote` (no mark).
  * `marginfigure`/`margintable`.
  * text-width figure/table (`figure`/`table`).
  * page-width figure/table (`figure*`/`table*`).
  * page-width environment (for custom `minipage` displays).
* To namespace `raggedright`.
* To add margin font hook.

## 1.0.1 - 2007-09-24
### Changed
* To correct README instructions.

## 1.0.0 - 2007-09-24
### Added
* First public release.

## 0.1.0 - 2004-02-04
### Added
* Birthday!
