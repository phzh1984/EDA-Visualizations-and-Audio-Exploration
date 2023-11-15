# EDA-Visualizations-and-Audio-Exploration

Introduction

Birds play a crucial role in indicating biodiversity changes, making them valuable for conservation efforts. Traditional bird biodiversity surveys are expensive and logistically challenging, but passive acoustic monitoring (PAM) combined with machine learning offers a scalable solution. This project aims to develop algorithms to identify Eastern African bird species by their calls, contributing to the ongoing efforts led by NATURAL STATE, a Kenyan conservation organization.

Observations in Train Meta Data:

* There are total of 12 columns and 16941 rows in train meta data.
  
* Train data contains 16941 values with 454(0.2%) of missing values.
  
* There are total of 12 columns : 3 numerical , 9 categorical
  
* 454 Missing values in the train meta data.

Dataset

train_audio/: Short bird call recordings from xenocanto.org, downsampled to 32 kHz.

test_soundscapes/: Approximately 200 10-minute recordings in ogg format for scoring.

train_metadata.csv: Metadata for the training data, including primary_label (bird species code), latitude, longitude, author, and filename.

