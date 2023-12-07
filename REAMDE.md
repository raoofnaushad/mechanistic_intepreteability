# Interpretability Implementation with TransformerLens

In this repository, we explore interpretability implementation using Hugging Face Transformers and the mechanistic interpretability package created by Neel Nanda. Our analysis is based on the concepts from the TinyStories paper.

## Overview

This is a library for performing mechanistic interpretability analysis on GPT-2 Style language models. The primary goal of mechanistic interpretability is to reverse engineer the algorithms that a trained model has learned during training, based on its weights.

TransformerLens allows you to load over 50 different open-source language models and provides access to their internal activations. You can cache any internal activation in the model and incorporate functions to edit, remove, or replace these activations as the model runs.

## About This Repository

This repository serves as an experimental exploration of TransformerLens using the mechanistic interpretability package. We aim to gain a deeper understanding of the interpretability of language models and how they make predictions.

Feel free to explore the code and experiments in this repository to learn more about the inner workings of language models and their attention mechanisms.
