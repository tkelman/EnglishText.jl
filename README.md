# English

[![Build Status](https://travis-ci.org/TotalVerb/English.jl.svg?branch=master)](https://travis-ci.org/TotalVerb/English.jl)

Currently this package includes two features: `indefinite` for finding the right
indefinite article to use, and `english` for converting a positive integer to an
English-language wordy representation.

```julia
julia> using English

julia> indefinite("hour")
"an"

julia> indefinite("hand")
"a"

julia> english(16)
"sixteen"

```