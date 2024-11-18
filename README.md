The contents of the HASYv2 dataset are:

hasy-data: 168236 png images, each 32px x 32px
hasy-data-labels.csv: Labels for all images.
classification-task: 10 folders (fold-1, fold-2, ..., fold-10) which contain a train.csv and a test.csv each. Every line of the csv files points to one of the png images (relative to itself). If those files are used, then the hasy-data-labels.csv is not necessary.
verification-task: A train.csv and three different test files. All files should be used in exactly the same way, but the accuracy should be reported for each one. The task is to decide for a pair of two 32px x 32px images if they belong to the same symbol (binary classification).
symbols.csv: All classes
README.txt: This file
link github: https://github.com/MartinThoma/HASY

