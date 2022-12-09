This script is meant as an example/tutorial for rotation students, new students, or other lab members interested in learning more about using pytorch lightning to train neural networks to predict the function of proteins given a sequence. 

This specific example takes a protein sequences as input and predicts a single score representing the function of the input variant. The scores in this example represent binding affinity of the variant Gb1 to IgG, but minor modificaitons to the code could be made to apply this simplified framework to other protein datasets. The dataset contains all single mutations and most double mutations of the 56 residue protein and associated scores. The simplest way to run this script is probably to copy all files to google colab and run it there.

There are notes interspersed throughout Seq2FxnNN_example.ipynb explaining what each section does, but ask around if something isn't clear.
