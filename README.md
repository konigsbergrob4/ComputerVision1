# Project 1: Hybrid Images
# CS 5670 Computer Vision

Robert Konigsberg
rak275@cornell.edu

## Summary
This README file contains information about the hybrid image created for Project 1. I used a photo of heath ledger (without makeup) and a photo of the Joker from Batman (also Heath Ledger, with makeup). The details below outline the high pass and low pass filter parameters, mix-in ratio, and which image's higher/lower frequcncies are used. 

## Contents
For submission, I included the following: <br />
> left.png - photo of Heath Ledger normally <br />
> right.png - photo of the Joker from Batman (Heath Ledger with makeup on) <br >
> hybrid.png - hybrid image constructed from left.png and right.png <br />
> Note: hybrid.py does not appear to be a submission requirement for the artifact on CMSX. Included in the prior Friday's submission. 

## Relevant Information for creating the hybrid image
Left image: 
> Sigma: 7.1 <br />
> Kernel Size: 21 <br />
> Low pass filter applied (not using high frequencies) <br />

Right image: 
> Sigma: 1.7 <br />
> Kernel Size: 9 <br />
> High pass filter applied (not using low frequencies) <br />

Additional: 
> Mix-in Ratio: 0.75 <br />
> Scale factor: 4.2 <br />
