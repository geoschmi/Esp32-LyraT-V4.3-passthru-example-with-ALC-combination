# Audio passthru Combination with ALC

This example passes audio received at the "aux_in" port to the headphone and speaker outputs.

Typical use cases:

- Exercising the audio pipeline from end to end when bringing up new hardware.
- Checking for left and right channel consistency through the audio path.
- Used in conjunction with an audio test set to measure THD+N, for production line testing or performance evaluation.

- This example has ALC initialized on top



## Usage

Prepare the audio board:

- Connect speakers or headphones to the board.
- Connect audio source to "aux_in".

Configure the example:

- Select compatible audio board in `menuconfig` > `Audio HAL`

Load and run the example:

- You should hear the audio passed from "aux_in" in the headphone and speaker outputs.
