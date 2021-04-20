https://en.modole.io/posts/bqs13ou34qug00ahspgg

This program is used for creating, adjusting, and adapting my dictionaries for GoldenDict.

## Requirements

* mdict-analysis, used for understanding and extracting the mdx format
* writemdict, used for converting text to a dictionary of the mdx format

## word-family

An ordinary dictionary can list tense forms or plural form of word, regarded as inflections. However, derived forms are not only these, like artist that is corresponding to art. So I want to find a dictionary that can list utmost derived forms of a word, to learn more words. Up to now, I find Prof Paul Nation offering [headwords of the 25,000 word families](https://www.wgtn.ac.nz/lals/about/staff/paul-nation#vocab-lists), albeit not really exhaustive. I have not encountered any other better data, deciding to write a program to convert them to a dictionary, serving as word-family.

The word-family directory contains `main.py`, and `wordfamily.mdx`, produced by the former. `main`.py handles "basewrd\*.txt" from the first to the fourteenth, excluding the subsequent txts. This s because the encoding of the fifteen txt is erroneous, and frequencies of the remnant are so low as to be negligible. After all, `wordfamily.mdx` contains the top 14000 word families.

# note that

keep in mind that

# up to this point

* so far, informal
* thus far, formal
* up to now
