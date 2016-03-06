# gootville: Gootville SMuFL font package for lilypond

This package provides the Gootville open-source font for lilypond. The Gootville font was developed for [MuseScore](https://github.com/musescore/MuseScore) and is based on the [Gonville](http://www.chiark.greenend.org.uk/~sgtatham/gonville/) font originally developed for lilypond.

Gootville is a [SMuFL](http://www.smufl.org/) font.

## Installation

Install using [lyp](https://github.com/noteflakes/lyp):

```bash
$ lyp install gootville
```

## Usage

```lilypond
\require "gootville"

\layout {
  \context {
    \Score gootvilleOn
  }
}

```

For more details see the included [example](https://github.com/noteflakes/lyp-gootville/blob/master/test.ly).

## Compatibility with Lilypond versions

This font is known to work in Lilypond version 2.18.2 or later.