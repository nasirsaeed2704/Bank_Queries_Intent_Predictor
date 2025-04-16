# Bank_Queries_Intent_Predictor
link to data: https://github.com/PolyAI-LDN/task-specific-datasets/tree/master/banking_data
link to wandb report: https://api.wandb.ai/links/nasirsaeed-work-fast-nuces/gmbdvpz7

In this project I took banking data from the above link and squeezed the 77 categories down to 11 categories. The 'retrive_and_split_data.ipynb' file retrieves data from the github repo and squeezes classes to 11 classes and creates test, valid, and train csv files and saves them on google drive. After this I finetuned Roberta base with huggingFace and Pytorch and achieved an accuracy of 92.76% on the test set. I also integrated wandb and logged my experiments. A report of these is also uploaded.
