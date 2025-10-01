# SHS-100K-official-2025
SecondHandSongs 100K data set, 2025 version
# Overview
This repository is a follow-up of the external SHS100K dataset first published in 2017. Given its intensive use in song recognition research, a new dataset was needed. However, in contrast to the first repository, this one is published by the SecondHandSongs organization itself. 

This dataset contains the metadata of 10,000 musical works (in SHS terminology "works") with 100,000 cover versions (in SHS terminology "performances"). It splits into three sets: test.csv, train.csv and validate.csv.

The selection of the data was made by sampling the works (that have 20 versions with YouTube video or more) from a weighted distribution according to language/instrumental, and taking all performances with YouTube videos, until 100K performances were reached for train.csv. Then another 5K for validation.csv and another 5K for test.csv. The musical works remain separate by subset.

# Metadata
* Performance ID
* Work ID
* Performance title
* Performing artist
* Youtube ID
