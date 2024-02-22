# Recipe ingredient extraction with OpenAI GPT Fine-tuning

## Overview
This project aims to leverage the powerful language generation capabilities of OpenAI's GPT models to automatically generate captions for chest X-ray images. By fine-tuning GPT on a specialized dataset of X-ray images and associated medical reports, the model can assist radiologists and healthcare professionals by providing initial draft reports, which can then be reviewed and edited as necessary.

## Features
- Utilization of OpenAI's GPT model for text generation.
- Fine-tuning on a dataset comprising chest X-ray images and corresponding radiological reports.
- A simple API endpoint for submitting X-ray images and retrieving generated captions.
- Options for manual input to guide the model's text generation.

## Prerequisites
Before running this project, you will need:
- Python 3.8 or later.
- Access to the OpenAI API with API key.
- The `python-dotenv` package for loading environment variables.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/chest-xray-captioning.git
   cd chest-xray-captioning
