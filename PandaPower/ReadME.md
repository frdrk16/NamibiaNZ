# PandaPower model of the Namibian grid
This folder contains the PandaPower model used to simulate current and 2050 powerflows for the Namibian
grid.

## Operation of the model
The jupyter notebook contains the code that will create and solve the network. Assumptions about lines, generators, transformers and loads are input via the excel files. The two files in this folder represent the present and proposed future configurations that were elaborated on in the report.

## Assumptions
1. Simplification: The grid was simulated in a simplified manner, breaking down the transmission system into the major hubs and most important lines. For a comparison between the actual transmission grid and the simplified version used in the model see "line_comparison.pdf".
2. Supply and demand data was taken from [here](https://www.ecb.org.na/wp-content/uploads/2023/08/Namibian_Transmission_Grid.pdf).
3. Line resistances and capacities were taken from [here](https://www.nexans.co/en/) while transformer ratings were extrapolated from the pandapowers standard type library. These parameters are summarized in the excel and could be changed with more accurate information
4. Net electricity imports were incorporated through interconnectors with Zambia, South Africa and Botswana. For now, no electricity exports were considered for the 2050 case.
