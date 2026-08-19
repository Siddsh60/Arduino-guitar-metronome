# Arduino-guitar-metronome
An Arduino based metronome which starts buzzing at half of the target tempo you set. It listens to your guitar strumming via a piezo sensor to check how closely you match the current tempo, automatically increases it if you can play accurately at that speed for 8 strums in a row, and resets the count if you make a mistake. This process is repeated until you can accurately play at the target tempo.

See [Hardware](https://github.com/Siddsh60/Arduino-guitar-metronome/blob/main/hardware) for the exact wiring and [Firmware](https://github.com/Siddsh60/Arduino-guitar-metronome/blob/main/firmware) for the code.
