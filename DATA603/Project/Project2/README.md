The file directory is as follows:

Project2
├── README.md
├── code.ipynb
└── Data
    ├── t10k-images.idx3-ubyte
    ├── t10k-labels.idx1-ubyte
    ├── train-images.idx3-ubyte
    └── train-labels.idx1-ubyte

The main code is in 'code.ipynb'. Run it block by block, comments and results are displayed in annotation and markdown block.

The program will call the GPU first, then CPU. I run the code on GPU and it is fast during CNN training. But since the network is not deep, runtime of CPU is also acceptable.