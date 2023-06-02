# Multilingual Conversational Model

## Introduction

This repository contains a Jupyter notebook that demonstrates how to prototype a multilingual conversational model using Google Dialogflow. This model is part of Natural Language Processing (NLP) and conversational models. The objectives of this notebook are:

- Understand solution design components
- Understand how to integrate different AI components, including training and runtime phases
- Understand how to evaluate a potential AI solution based on different components

## Scenario

Our organization, an airline company, is exploring the idea of implementing a conversational model in two languages: English and Russian. To evaluate the feasibility of this idea, we have built a prototype that tests the concept and assesses its viability.

The conversational model should be able to answer two questions:

1. Can I cancel my ticket and get a refund?
2. How many items/kilos of luggage can I check in?

## Design: Potential Solution

The prototype consists of the following components:

- **Front-end**: The front-end is delivered with Gradio, an easy-to-use tool for creating interfaces.
- **Translation service**: Google Translation AI is used for translating from English to Russian and vice versa.
- **Conversational Engine**: Google Dialogflow is used as the conversational engine. It is a powerful tool for creating conversational agents and is the backbone of our multilingual model.

## Usage

This notebook is intended to be a guide for prototyping a multilingual conversational model using Google Dialogflow. It can be used as a reference for building similar models or for understanding the integration of different AI components.

## Acknowledgements

- [Gradio](https://www.gradio.app/)
- [Google Translation AI](https://cloud.google.com/translate)
- [Google Dialogflow](https://cloud.google.com/dialogflow)
