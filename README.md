# Céu Estrelado

Point your phone's camera at the sky and find out which constellation you're looking at.

## The Idea

Looking up at the night sky and recognizing constellations is hard if you've never studied astronomy. Céu Estrelado solves that: you take a photo of the sky, and the app shows which constellation is there, drawing the lines that connect the stars and labeling each one by name.

## How It Works

The app combines two sources of information:

1. **Where you are and where you're pointing.** Using your location, the time, and the phone's sensors (compass and accelerometer), the app estimates which part of the sky is in front of the camera. This matters because the visible sky changes with your location, the time of night, and the season. Someone in Brazil sees different stars than someone in Europe.

2. **What the camera actually sees.** Phone sensors are imprecise, so the app also analyzes the photo: it finds the stars in the image and matches the pattern they form against an astronomical catalog, much like recognizing a picture by connecting the dots. When the pattern matches, the constellation is identified precisely.

## Status

In development.
