## Overview

The main purpose of this repo is to provide a quick example of running hyperparmeter tuning in a pipeline that works with the current SDK. 

### Objectives

In this tutorial, you learn how to use prebuilt `Google Cloud Pipeline Components` for `Vertex AI Hyperparameter Tuning`.

This tutorial uses the following Google Cloud ML services:

- `Google Cloud Pipeline Components`
- `Vertex AI Dataset, Model and Endpoint` resources
- `Vertex AI Hyperparameter Tuning`

The steps performed include:

- Construct a pipeline for:
    - Hyperparameter tune/train a custom model.
    - Retrieve the tuned hyperparameter values and metrics to optimize.
    - Return the best run from a cutom KFP component
- Execute a Vertex AI pipeline.