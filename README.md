# Project Title

ADC example with a **nRF5x** chip from **Nordic Semiconductor**

## Getting Started

Hardware: 

- nRF5x series (nRF52832)

Pinout: 

- signal to be sampled must be set on any Analog Input pin of the nRF5x (P0.02/AIN0 ... P0.31/AIN7)


## Installing
- for a quick demo, put this sketch in nRF5_SDK_15.0.0_a53641a\examples\peripheral\\[Your_Project]

## Main Functionality

This firmware samples the voltage on the targetted Analog Input Pin. Using "NRF_SAADC_INPUT_VDD" allows to sample Vdd (the chip own power source)

## Built With

Keil V5

## Test
Has been tested with nRF52-DK and custom board 

## Author

https://github.com/johnmarcc



