# Decode Chip-seq datasets with run-length encoding

This repository contains code that can be used to perform machine learning experiments on coverage.bedGraph files. However, before conducting any analyses, these files need to be decoded from their run-length encoding format. This repository provides codes that enable you to easily perform this decoding step.

Here are the key features of this repository:

1. Unpack datasets from .gz format: Some coverage.bedGraph files may be compressed in .gz format. This repository provides tools that allow you to easily unpack these compressed files.

2. Decode coverage.bedGraph files: The coverage.bedGraph files contain data in a run-length encoding format, which can make it difficult to work with the data. This repository provides code that decodes the coverage.bedGraph files, allowing you to more easily manipulate and analyze the data.

3. Make a dataset based on annotated regions: This repository also provides code that allows you to generate datasets based on annotated regions. This can be useful for supervised machine learning techniques where you need to train models on specific annotated genomic regions.

Additionally, if you're looking for an example of coverage.bedGraph files in the context of ChIP-seq datasets, you can check out the following link: https://archive.ics.uci.edu/ml/datasets/chipseq.
