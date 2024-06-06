# Iosevkins

[![License](https://img.shields.io/github/license/fernzi/iosevkins?label=License)](LICENSE)
[![CI](https://github.com/fernzi/iosevkins/actions/workflows/ci.yaml/badge.svg)][url-ci]

My very own customized version of the free [Iosevka][url-io] font.
It's meant for code, terminals, prose, verse, and mostly just Emacs.

[url-io]: https://typeof.net/Iosevka/
[url-ci]: https://github.com/fernzi/iosevkins/actions/workflows/ci.yaml

## Design

Iosevkins doesn't consider, or makes any promises about,
any measure of legibility, accessibility, or usability,
and it rather completely conforms to my entirely subjective
(yet objectively correct, and better than yours) sense of taste.

I do keep it aesthetically consistent though, and
would describe it as kinda futuristic, or even sci-fi looking.

The general style of Iosevkins should be round and precise,
using the (al)most rounded, simplest shape variants in Iosevka.
The roman glyphs avoid spurs on most letters, in favour of corners,
while the italics add some extra curves and flourishes to get a
more caligraphic feel to them.

## Features

The font includes two variants, each with romans and italics;
two widths: Regular, and Extended; and
five weights: Light, Normal, Medium, Bold, and Heavy.

#### Iosevkins:
The default, is strictly monospaced, with no wide glyphs,
so it should be readily recognized as a mono font by FontConfig.

#### Iosevkins Michi:
A proportional font (or "variable pitch," as Emacs calls it)
intended for regular body text, rather than writing code.

> [!NOTE]
> The *Extended* width in Iosevkins is narrower
> than the width of the same name in Iosevka.
> This might change when I figure out how to make Emacs
> accept hyphenated names like "Semi-Extended."

None of the included variants support programming ligatures,
mostly cause I think they're stupid and pointless.
