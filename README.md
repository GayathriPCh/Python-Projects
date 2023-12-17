# BeatWave: Generate Music from Images

## Overview

BeatWave is a Python-based web application developed using the Django framework that allows users to generate music compositions inspired by visual elements in an image. By mapping each pixel to a frequency value, BeatWave transforms images into unique musical experiences.

## Current Functionality

- **Upload Interface:** Users can upload an image of their choice through the user-friendly interface.
- **Generate Music Button:** By clicking the "generate music" button, a zip file is downloaded.
- **Output Files:** The downloaded zip file contains both a WAV file and a MIDI file, each representing different music compositions inspired by the uploaded image.
- **Image Size Compatibility:** BeatWave accommodates images of varying sizes.

## Work in Progress

- **User Authentication:** Upcoming features will include user login functionality, enhancing user experience and providing personalized access.
- **Batch Image Upload:** Users will soon be able to upload multiple images at once, enabling them to create diverse musical compositions in a single session.

## Why BeatWave?

- **Inspiration:** BeatWave aims to inspire new ways of making music, bridging the gap between visual and auditory art forms.
- **Creative Expression:** By generating music inspired by visual elements, BeatWave opens up new avenues for creative expression, making music production an immersive and dynamic experience.

## Getting Started

To run BeatWave locally:

```bash
git clone https://github.com/GayathriPCh/beatwave.git
cd beatwave
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
