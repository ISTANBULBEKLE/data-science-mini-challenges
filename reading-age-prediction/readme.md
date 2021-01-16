# Project Zulu Reading Age Prediction

## Background

Project Zulu is a UWE Bristol charity initiative supporting educational development projects in South Africa.

Working together with schools and local government partners, Project Zulu identifies support programmes for education, resourcing and infrastructure, and this includes drawing on student and tutor expertise, fundraising, as well as local knowledge and talent.

We have a research project to train teachers in early reading, including the development of a mobile app which will predict the reading age of a book given a photo of one of the pages of text. We need to develop a predictive model to give an age based on an Optically Character Recognition (OCR'd) piece of text.

## Dataset

This is a series of pages of some example books with a reading age associated.

| Excerpt                | Book and Page              | Age |
|------------------------|----------------------------|-----|
| Is it a big dinosaur?  | Big feet pg8/589_right.png | 1   |
| Come and look at this. | Big feet pg8/590_left.png  | 1   |
| No. It is Dad.         | Big feet pg8/591_left.png  | 1   |


## Reading Age Algorithms

Many of the algorithms used in Europe and the US are proprietory, so we don't know exactly how they rate a text. But we can be fairly sure they use some recoverable structural and linguistics features.

* The [Flesch–Kincaid readability Algorithm](https://en.wikipedia.org/wiki/Flesch%E2%80%93Kincaid_readability_tests) uses the words, syllables and sentences in the text to compute a readability score.

* [YARC- Standardised reading comprehension test](https://www.gl-assessment.co.uk/products/york-assessment-of-reading-for-comprehension-yarc/ )

* [Coh -Matrix and relevent documentation](http://cohmetrix.com/); [Information on how it works](https://www.researchgate.net/publication/8358727_Coh-Metrix_Analysis_of_text_on_cohesion_and_language); [Webtool](http://141.225.61.35/CohMetrix2017/)
