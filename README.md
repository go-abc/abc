[![Build Status](https://travis-ci.org/go-abc/abc.svg?branch=master)](https://travis-ci.org/go-abc/abc) [![GoDoc](https://godoc.org/github.com/go-abc/abc?status.svg)](https://godoc.org/github.com/go-abc/abc) [![Go Report Card](https://goreportcard.com/badge/github.com/go-abc/abc)](https://goreportcard.com/report/github.com/go-abc/abc) [![codebeat badge](https://codebeat.co/badges/b8826919-e364-4861-8acd-76f7983b853e)](https://codebeat.co/projects/github-com-go-abc-abc)

[https://github.com/go-abc/abc](github.com/go-abc/abc)

## ABC musical notation in Go

ABC notation is a shorthand form of musical notation.

In basic form it uses the letters A through G to represent the given notes, with other elements used to place added value on these - sharp, flat, the length of the note, key, ornamentation.

Later, with computers becoming a major means of communication, others saw the possibilities of using this form of notation as an ASCII code that could facilitate the sharing of music online, also adding a new and simple language for software developers. In this later form it remains a language for notating music using the ASCII character set. The earlier ABC notation was built on, standardized and changed to better fit the keyboard and an ASCII character set by Chris Walshaw, with the help and input of others.

Although now re-packaged in this form, the original ease of writing and reading, for memory jogs and for sharing tunes with others on a scrap of paper or a beer coaster remains, a simple and accessible form of music notation, not unlike others, such as tablature and Solfeggio. Originally designed for use with folk and traditional tunes of Western European origin (e.g. English, Irish, Scottish) which are typically single-voice melodies which can be written on a single staff in standard notation, the work of Chris Walshaw and others has opened this up with an increased list of characters and headers in a syntax that can also support metadata for each tune.

[ABC notation on Wikipedia](https://en.wikipedia.org/wiki/ABC_notation)

[Chris Walshaw's official ABC notation website](http://abcnotation.com/)

[An ABC primer by John Chambers](http://trillian.mit.edu/~jc/doc/doc/ABCprimer.html)

## Music theory models in Go

ABC musical notation is ultimately converted to musical notes and chords via the [github.com/go-music-theory/music-theory](https://github.com/go-music-theory/music-theory) package.
