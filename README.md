# Improving Human-AI Interactions with More Accessible Deep Learning

In this tutorial, we train an AI system that understands the intent and the entities involved within the query, lookup or launch the relevant information, and return the appropriate response to the customer in a reasonable amount of time. We leverage the Intel Extension for PyTorch to fine-tune a foundational BertModel from the Hugging Face Transformers library to train and deploy an accurate and quick AI system to predict the Intent and Entities of a user requesting information about airline travel.

*The notebooks in this repository is an adaption of the [Intel AI "Customer Chatbot" Reference Kit](https://github.com/oneapi-src/customer-chatbot)*

### Create Environment
You can setup your environment by running `conda env create -f env.yaml` 

This will pre-install: 
- intel distribution of python
- pytorch
- scikit learn
- intel extension for pytorch
- hugging face transformers

If you would like to learn more about the intel extension for pytorch, I highly recommend reviewing the associated GitHub.io Page: https://intel.github.io/intel-extension-for-pytorch/

### Dataset
Preprocessing code and data for this repository were originally sourced from https://github.com/sz128/slot_filling_and_intent_detection_of_SLU/tree/master/data/atis-2.

*Please see this data set's applicable license for terms and conditions. Intel does not own the rights to this data set and does not confer any rights to it.*

### Getting Access to Similar Compute
This notebook was originally developed and tested on an Intel 4th Generation Xeon Baremetal Instance on the Intel Developer Cloud. You can register for Beta cloud access here: https://cloud.intel.com

### Associated Medium Article
- [Improving Human-AI Interactions with More Accessible Deep Learning](https://medium.com/@eduand-alvarez)
