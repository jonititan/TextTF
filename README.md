# TextTF

An example for the use of Tensorflow in text classification using the SMS Spam Collection dataset and the Glove embedding

https://www.dt.fee.unicamp.br/~tiago/smsspamcollection/

https://nlp.stanford.edu/projects/glove/

To try this out install miniconda


Then create a virtual environment using the following command

conda env export > environment.yml

more info here
https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#sharing-an-environment

You will also need to download and extract the glove embeddings into the inputs folder


To launch 

conda activate TextTF

jupyter notebook



If the environment configuration fails try the following

conda create --name TextTF

conda activate TextTF

conda install scikit-learn matplotlib tensorflow jupyter pandas


