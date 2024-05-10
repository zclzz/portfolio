# Real-time Hand Gesture to Text Translation

![example](./misc/example.gif)


## About

This is a real-time hand sign to-text translation using in-context learning to fine tune an LSTM model to recognize hand gestures and translate them to text.

## Dataset

Data for this version of the model contains 7 phrases x 30 videos x 30 frames. The 7 phrases are an adaptation of the American Sign Language (ASL). Each phrase contain 30 videos of 30 sequential frames each forming the gesture completely for the LSTM model to recognize the gesture to generate the word for that phrase

## Run

Simply run:

	```bash
	python model1.py
