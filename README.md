# GeezLab Tigrinya Word Count

This compilation of over `0.56 million` unique Tigrinya words and their frequencies is collected from huge body of text sources, including websites, books, newspapers and so on.

The source documents were deduplicated and the text was preprocessed (normalized and tokenized) before generating the stats. The statistics provided is a good represenation of the language characteristics. Due to Tigrinya's rich morphology, the vocabulary is expected to grow as more text becomes available for analysis. Accordingly, this repository will be updated from time to time.


## Format
 * Content file `ti_word_count.txt`
 * Each line formed as `<word>TAB<count>`


## Stats
 - Vocabulary: 565360
 - Source tokens: 12637126
 - Tigrinya word frequency and ranking distribution ![alt Zipf's](zipf.png)

## Uses
 * Licensed under the MIT License, it can be freely used for any purpose with proper attributions.
 * If you use this resource in a published work please cite as follows:

```
GeezLab Tigrinya WordCount, https://github.com/fgaim/Tigrinya-WordCount
```
