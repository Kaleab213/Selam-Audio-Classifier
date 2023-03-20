# Selam-Audio-Classifier

Embedded Machine Learning Model that detects keywords.

Exported dataset for Kal / minnovation-first-project
To import this data into a new Edge Impulse project, either use:

The Edge Impulse CLI (https://docs.edgeimpulse.com/docs/edge-impulse-cli/cli-overview), run with:

edge-impulse-uploader --clean --info-file info.labels

Or, via the Edge Impulse Studio. Go to Data acquisition > Upload data.

This project is all about detecting some keywords - including the words "Selam" and "Stop" - each of which is detected with high accuracy using the sensors. 
the model is also trained to detect some noises and also unknown sounds.
However, sometimes the sound can be unpredictable, for example: if I say "Bye", which can make it 
difficult to classify the sound accurately. 
I have used my phone as the data collection and deployment tool, since I cannot afford an Arduino microcontroller.
