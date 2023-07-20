# The Sound of Quantum Decoherence Museum Demo

## Introduction

This project aims to explore an innovative approach to understanding quantum decoherence through sonification. The focus is on audibly representing quantum decoherence by converting the median T1 and T2 values of an IBM Quantum device directly from microseconds to hertz. T1 values are indicative of the relaxation time that a qubit decoheres from state |1> to state |0>, which reflects quantum decoherence. T2 values are indictative of the dephasing time that a qubit takes to decohere from state |1> to state |0>. I specifically focus on sonifying older generations of IBM Quantum devices (once historical date for T1 and T2 values are acquired) by taking these median T1 values for the system and mapping them directly to hertz. This project not only facilitates an innovative way to physically listen to the phenomena of quantum decoherence, but provides an opportunity to hear the progression of pioneering quantum technology over time.

![Project Screenshot](./Screenshot(693).png "main menu of web app")

## Museum Exhibit

The project will form part of a museum exhibit at the Museum of Science and Industry. Along with the exhibit, besides web app of all the generations of IBM quantum devices, there will be a clear layman's description for visitors. The web app will have clear labels for each processor’s generation, and there will be a layman’s explanation of what the T1 and T2 values are, since it represents the relaxation time of a qubit going from the excited |1> state to the ground |0> state or the dephasing time. The description at the exhibit will also explain why those values are important to quantum decoherence, what each tone represents such as with the median T1 value and what that means for it to be the median, and the microseconds to hertz direct mapping being different than the technical reciprocal of frequency and time where technically it would be notes all around the range of a piccolo. The title of the exhibit is “The Sound of Quantum Decoherence”.

## Application Code

The application code is written in React and uses the chroma-js library for color manipulation. It provides a visual representation of each IBM Quantum device's T1 values, which are mapped to a specific color and tone. The tones are generated when the user interacts with the interface. The code for the application is available in the 'App.js' and 'App.css' file.
