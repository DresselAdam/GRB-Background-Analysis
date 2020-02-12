# GRB-Background-Analysis

## FGCU Stellar Research

## Authors
- Adam Dressel
- Lindsey Carboneau


## Overview
This project serves as a supplementary agent in our research on Gamma-ray burst optical progenitors. We search random areas around a potential precursor candidate, and create a visualization of TESScut's full-frame images. In these "movies" we are looking for an optical flash that resembles the original candidate's (similar length, brightness). So far we have made 10 movies and the plan is to perform 100 tests for verification.

## Results Methodology
1. The results of this analysis are obtained by observing short "movies" created from TESScut images.

1. A TESScut image contains a "flash" based on the following criteria:
    1. Independence: a flash is independent of any nearby stars or instrument anomoly.
    1. Time: a flash lasts only 1-2 frames.

1. An image is determined to be a valid candidate for a test based on the following:
    1. An image is selected by creating a mask of around 4 pixels closest to the reference pixels, and obtaining the median flux values.
    1. An image is selected if this median flux value is under 100. Fairly close to the background median.
    1. Further subjective analysis on an image of the first frame is also used. If a brightish star is near the reference pixels, then the image is not used.
    1. Excess instrument errors will also exclude an animation from being used.


  
