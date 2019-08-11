# BatchSize

Exploring the increase or decrease in batch size and its effect on the accuracy of a model trained on the anime face dataset from kaggle found here. https://www.kaggle.com/mylesoneill/tagged-anime-illustrations/home

General rule of thumb seems to be to make the batch size as large as possible to be able to train faster and and more accuractely. This notebook, looks at decreasing the batch size to see the effcts on training. It was tried on a GTX 1080 TI GPU, and trained for 5 epochs each. The accuracy presented in the notebook is the validation accuracy, which is 20% of the training data. 

This approach has been heavily influenced by the Fast.ai library and their course which can be found here: https://course.fast.ai 
A special thanks to Jeremy Howard and Rachel Thomas for their contributions in the community.
