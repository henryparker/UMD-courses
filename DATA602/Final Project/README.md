This final project is to use TF-IDF for document classification. Within each fold of 5-fold cross validation, the detailed accuracy and score of each category is displayed.

Before running the code, make sure to put the dataset in the directory, for example

Final Project
├── README.md
├── code.ipynb
└── 20_newsgroups
    ├── alt.atheism
    ├── comp.graphics
    ...
    └── talk.religion.misc

Then run the code block by block. My CPU is R7 7700, with memory 32 GB. I use the CSR matrix to save memory, so 1 GB of extra memory should work. Estimated runtime is within 3 minutes.

Result: Average Accuracy of 5-Fold is about 88.2%