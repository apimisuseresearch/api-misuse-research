	# Deep Learning Approach for API Misuse Detection

<p aligh="center"> This repository contains the code for <b>Deep Learning Approach for API Misuse Detection</b>.</p>

# Source Code: https://github.com/apimisuseresearch/api-misuse-research/tree/master/MUInspect#Instruction_to_Run_MUInspect


## Contents
1. [Introduction](#Introduction)
2. [Dataset](#Dataset)
3. [Requirement](#Requirement)
4. [Instruction_to_Run_MUInspect](#Instruction_to_Run_MUInspect)

## Introduction

API misuses are the incorrect usages that violate the usage constraints of the API elements. API misuses could cause several issues ranging from run-time errors and exceptions, program crashes, to security vulnerabilities. The state-of-the-art mining-based approaches suffer low accuracy because they cannot differentiate infrequent from invalid usage. This is an inherent issue with the mining approaches because they need to set a pre-defined threshold for frequent API usage patterns. Another issue is that they mine a pattern and then report instances of alternative usages as violations. This paper introduces a learning-based approach for API misuse detection that avoids the need for pre-defined thresholds. To overcome the lack of training data, we designed a new data augmentation technique to apply to a graph-based representation of API usages. We also leverage Labeled, Graph-based Convolutional Network to learn the embeddings for API usages, which capture the key features in API usages and are used for API misuse detection. Our empirical evaluation on a real-world API misuse benchmark shows that our model relatively improves over the state-of-the-art API misuse detection techniques from 1.52X–11.51X in F-score.

## Dataset

We use the dataset from existing benchmark : [Investigating Next Steps in Static API-Misuse Detection](https://github.com/stg-tud/MUBench)

## Requirement

Install ```Torch``` by following the Instruction from [PyTorch](https://pytorch.org/get-started/locally).

Install ```torch_sparse``` by following the Instruction from [pytorch_sparse](https://github.com/rusty1s/pytorch_sparse).

Install ```torch_geometric``` by following the Instruction from [torch_geometric](https://pytorch-geometric.readthedocs.io/en/latest/notes/installation.html).

Install ```scikit-learn``` by following the Instruction from [scikit-learn](https://scikit-learn.org/stable/getting_started.html).

Install ```networkx``` by following the Instruction from [networkx](https://networkx.org/documentation/stable/install.html).

## Instruction_to_Run_MUInspect

Download the MUInspect source code and run ```main.py``` to see the result for our experiment. 

