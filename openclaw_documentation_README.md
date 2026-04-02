# ie-citations-sources

Information Extraction for Buddhist literature

## Language

Python

## Description

Entities are (ལུང་ཁུངས།, ལུང་དེའི་མཛད་པ་པོ།, ལུང་ཚིག་དངོས།) and annotation scheme used for this task is BIO.

Note: We have used Pybo for word tokenization and Lighttag for text annotation.

## Citation Detection Models Comparison

| Model | Test F1 |
|-------|--------|
| Memorization_v1 | 2.2032 |
| Bi-LSTM_v2 | 34.56 |
| Bi-LSTM_CRF_v2 | 31.92 |
| Bi-LSTM_CRF_Word2Vec_v2 | 54.09 |
| Bi-LSTM_CRF_Word2Vec_v3 | 63.41 |

Note: F1-score is based on metric used for CoNLL-2000. We have used seqeval package for measuring the F1-score.

## How to get help

- Open an issue at https://github.com/OpenPecha/ie-citations-sources/issues
- Check existing issues for solutions

## Terms of use

This project is part of OpenPecha. See https://openpecha.org for terms of use.