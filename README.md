# FluxProcessingBB2

Script for cleaning and gap-filling met and flux data

## Usage

1. Clone this repo: https://github.com/mnybe1/FluxProcessingBB2.git

2. Run the following scripts in this order

- 0.download_metBB2.R 

NOTE: you will need to change the path in 'setwd()' at the start of the script to run locally

- 1.merging_met_filesBB2.Rmd

NOTE: you will need to change the path in 'dir' at the start of the script to run locally
Will also need to update the path to write the csv at the end of the script

- 2.met_filtering_gapfillingBB2.Rmd

NOTE: you will need to to change the paths throughout so that it can be run locally. 
You will also need to download the most recent UBC climate data. The link to do this is on line 136 of the script. The file needs to replace the current file in the folder.

- 3.export_biomet_for_EddyProBB2.R

NOTE: change paths to run locally
