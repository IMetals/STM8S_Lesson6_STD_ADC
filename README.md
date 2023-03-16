# NOTE: ALL PROJECT USE STM8S208C8T6 WITH DISCOVERY BOARD. CODE PROGRAMING: IAR Embedded Workbench
See detail in this project: https://github.com/IMetals/Template_IAR_STM8S.git
# Lesson 6: STD_STM8S_ADC
## Introduce
STM8S20xxx performance line products contain a 10-bit successive approximation A/D
converter (ADC2) with up to 16 multiplexed input channels and the following main features:
- Input voltage range: 0 to VDDA
- Dedicated voltage reference (VREF) pins available on 80 and 64-pin devices
- Conversion time: 14 clock cycles
- Single and continuous modes
- External trigger input
- Trigger from TIM1 TRGO
- End of conversion (EOC) interrupt  
## Feature
These features are available in ADC1 and ADC2.
- 10-bit resolution
- Single and continuous conversion modes
- Programmable prescaler: fMASTER divided by 2 to 18
- External trigger option using external interrupt (ADC_ETR) or timer trigger (TRGO)
- Analog zooming (in devices with VREF pins)
- Interrupt generation at End of Conversion
- Data alignment with in-built data coherency
- ADC input range: VSSA ≤ VIN ≤ VDDA  


