# Torch-RNN-Trained

## torch-rnn
from https://github.com/jcjohnson/torch-rnn <br/>
torch-rnn provides high-performance, reusable RNN and LSTM modules for torch7, and uses these modules for character-level
language modeling similar to [char-rnn](https://github.com/karpathy/char-rnn).

You can find documentation for the RNN and LSTM modules [here](doc/modules.md); they have no dependencies other than `torch`
and `nn`, so they should be easy to integrate into existing projects.

Compared to char-rnn, torch-rnn is up to **1.9x faster** and uses up to **7x less memory**. For more details see 
the [Benchmark](#benchmarks) section below.

## Biological Samples
1. Human GRCh38 reference genome
2. E. Coli reference genome

## Input Arguments
-max_epochs 8 -rnn_size 128 -dropout 0.05 -num_layers 3

## Blastn Alignments
See blast at: https://blast.ncbi.nlm.nih.gov/Blast.cgi<br/>
**Sampling from the longest checkpoints**<br/>

Eli:
![alt text](https://github.com/flynn-chen/Torch-RNN-Trained/blob/master/Screen%20Shot%202018-08-20%20at%202.49.26%20PM.png)

Adam:
