
# Dipy Tractometry

The App uses Bundles Analytics frameworks to do analyse your tractography data. It creates bundle profiles of the pathways and saves the information in HD5 files. This app implements bundle profiles method presented in Bundle analytics, a computational framework for investigating the shapes and profiles of brain pathways across populations paper [1].

### Authors

- [Bramsh Chandio](https://github.com/BramshQamar)

### Contributors

- [Serge Koudoro](skoudoro@iu.edu)
- [Javier Ricardo Guaje Guerra](jrguajeg@iu.edu)

### Funding Acknowledgement
brainlife.io is publicly funded and for the sustainability of the project it is helpful to Acknowledge the use of the platform. We kindly ask that you acknowledge the funding below in your code and publications. Copy and past the following lines into your repository when using this code.

[![NSF-BCS-1734853](https://img.shields.io/badge/NSF_BCS-1734853-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1734853)
[![NSF-BCS-1636893](https://img.shields.io/badge/NSF_BCS-1636893-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1636893)
[![NSF-ACI-1916518](https://img.shields.io/badge/NSF_ACI-1916518-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1916518)
[![NSF-IIS-1912270](https://img.shields.io/badge/NSF_IIS-1912270-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1912270)
[![NIH-NIBIB-R01EB029272](https://img.shields.io/badge/NIH_NIBIB-R01EB029272-green.svg)](https://grantome.com/grant/NIH/R01-EB029272-01)

### Citations
We ask that you the following articles when publishing papers that used data, code or other resources created by the brainlife.io community.

[1] Chandio, BQ., et al. Bundle analytics, a computational framework for investigating the shapes and profiles of brain pathways across populations. Scientific reports,  10, 17149 (2020).

[2] Garyfallidis, E., Brett, M., Amirbekian, B., Rokem, A., van der Walt, S., Descoteaux, M., Nimmo-Smith, I., & Dipy Contributors (2014). Dipy, a library for the analysis of diffusion MRI data. Frontiers in neuroinformatics, 8, 8. [https://doi.org/10.3389/fninf.2014.00008](https://doi.org/10.3389/fninf.2014.00008)

[3] Avesani, P., McPherson, B., Hayashi, S. et al. The open diffusion data derivatives, brain data upcycling via integrated publishing of derivatives and reproducible open cloud services. Sci Data 6, 69 (2019). [https://doi.org/10.1038/s41597-019-0073-y](https://doi.org/10.1038/s41597-019-0073-y)

## Running the App

#### 1. On Brainlife.io

You can see a list of [Dipy Apps currently regsitered on Brainlife](https://brainlife.io/apps#dipy). Find the App that you'd like to run and click "Execute" tab to specify dataset that you'd like to run the App on.

#### 2. On  your machine (Running Locally)

To run this command, you can simply type:

`singularity exec -e docker://brainlife/dipy:1.1.1 dipy_buan_profiles [your_args]`

To see the documentation of all arguments, [go to the following page](https://dipy.org/documentation/1.1.1./reference_cmd/dipy_buan_profiles/)

## Input

To see the documentation of all the arguments, follow this [link](https://dipy.org/documentation/1.1.1./reference_cmd/dipy_buan_profiles/).

## Output

All output files will be generated according to the passed arguments, as explained [here](https://dipy.org/documentation/1.1.1./reference_cmd/dipy_buan_profiles/).

### Dependencies

This app runs on [singularity](https://www.sylabs.io/singularity/).

### DIPY
- This is a Brainlife wrapper App stemming from the [`dipy_buan_profiles`](https://dipy.org/documentation/latest/reference_cmd/dipy_buan_profiles/) workflow.
- This single wrapper is exposed through an apps registered on [Brainlife.io](https://brainlife.io).
- More information about DIPY : [https://dipy.org/](https://dipy.org/).
- More information about the command line `dipy_buan_profiles`: [Command line Reference](https://dipy.org/documentation/latest/reference_cmd/dipy_buan_profiles/).

