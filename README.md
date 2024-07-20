# Burrows Wheeler Transform (BWT)
The Burrows-Wheeler Transform (BWT), also known as block-sorting compression, reorganizes a character string into sequences of similar characters, aiding in compression. In Next-Generation Sequencing (NGS), DNA is broken into small fragments, with the initial bases sequenced, producing millions of "reads," each ranging from 30 to 500 base pairs ("DNA characters") long. In various experiments, such as ChIP-Seq, the goal is to align these reads to a reference genome, which is the known, nearly complete sequence of the organism (potentially several billion base pairs long). To minimize memory usage for sequence alignment, several programs (Bowtie2, BWA, and SOAP2) were developed utilizing the Burrows-Wheeler Transform.

## Usage
1. Clone this repo:
```
git clone https://github.com/amisha1699/Burrows-Wheeler.git
cd Burrows-Wheeler
```

2. Prepare input data in the format as given in data/data.txt