# AI Weather Examples

Maintained by Luke Madaus

A collection of jupyter notebooks and related code illustrating various tools and methods used in modern AI weather and climate model development.  These are designed to give the novice user a place to dig in and see examples of how to run and train AI weather and climate models.  An emphasis is placed on extensive commenting and annotation in the notebooks to help with understanding.

## Contents

The following examples are included:

- **ai_models_utility**: Shows how ECMWF's `ai-models` package can be used to run a large number of modern AI global weather forecasting models with a common interface.  See their repo for more details: https://github.com/ecmwf-lab/ai-models
- **neuralGCM**: An example of more directly running inference with a state-of-the-art global weather/climate model (with good documentation).  See their documentation for more details here: https://neuralgcm.readthedocs.io/en/latest/index.html
- **basic_vae** : A notebook that walks through the setup and training of a variational autoencoder type model using Pytorch and publicly-accessible cloud-hosted reanalysis data.  It's meant to show everything that's involved in setting up the data and model for a low- to intermediate complexity weather/climate application.
