# Information Retrieval Mid-term Assignment [Oct 2015]

## Source

Code forked & modified from:

[JavaBook](https://github.com/colloquial/javabook)

## How to

This project uses Apache Ant, to run just type these commands from command line / terminal:

```bash
# clean build
$ ant clean

# compile/build
$ ant compile

# make executable jar
$ ant jar

# clean index files
$ ant clean-index

# start classifying
$ ant classify
```

Modify the <property> inside `build.xml` to suit your needs for the classification method, you can also modify the train/test/index folders location if you really need to, else just paste in your data inside the provided location.

Available classification methods:

- `std`, uses `StandardAnalyzer`
- `lc`, uses `LowerCaseFilter`
- `ngram`, uses `NGramTokenizer`

## License

Copyright © 2015 Rudy <rudolf_bast@live.com>
This work is free. You can redistribute it and/or modify it under the
terms of the Do What The Fuck You Want To Public License, Version 2,
as published by Sam Hocevar. See the [LICENSE](/LICENSE.md) file for more details.
