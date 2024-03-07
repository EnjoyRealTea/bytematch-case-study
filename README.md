# ByteMatch Case Study

A recommendation system case study focussing on semantic similarity.

## Case Study Premise

### Background: 
  _In the heart of the digital age, the "Daily Byte" stands as one of the most renowned online news platforms. With a vast array of articles spanning various topics, readers are spoilt for choice. However, with such an abundance of information, many readers feel overwhelmed, often missing out on articles that might resonate with their interests._

### Challenge: 
_The editorial team, led by the visionary editor-in-chief, Ms. Penelope Wordsworth, has a challenge for the students. They've noticed a trend: readers who enjoy articles on specific topics tend to have a high likelihood of enjoying other articles with semantic similarities. With this observation, Ms. Wordsworth poses a question: "Can we guide our readers to articles they'll love, based on what they've previously enjoyed?"_

### Objective: 
To create ByteMatch, a recommendation system for the Daily Byte.

### Concepts Covered:
1. **Algorithm Efficiency:** Comprehending and leveraging the efficiency of the ByteMatch system will generally result in improved performance in text-processing tasks as opposed to complex algorithms.

2. **NLP:** Valuable for information extraction, summarising and sentiment analysis, where patterns are taken from the meaning of the words instead of their byte sequences.

## Installation
ByteMatch.ipynb can be downloaded and run locally with Jupyter Notebook.

The following libraries will need to be installed before running:
- spacy

## Useage

ByteMatch.ipynb contains two functions:
 - preprocess: This function preprocesses a string by removing punctuation and stop words, and lemmatizing the remaining words.
 - recommendation: This function takes the text of the last article read and a dictionary containing article titles and text, and returns the title of the most similar article as a recommendation to read next.

After running these functions on the sample articles, the recommendations for each article are displayed for evaluation. The recommendations given with and without preprocessing are shown for comparison.

## Credits
ByteMatch.ipynb notebook was written by E. Thompson.

The selection of sample articles used in this demonstration are from [CNN's 'Good News Generator 2023'](https://edition.cnn.com/interactive/2023/12/specials/good-news-generator-dg-cec/)
