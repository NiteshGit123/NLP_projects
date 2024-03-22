# NLP_projects


This is my NLP based project

The dataset contains the abstract,title of the projects and also the subject/stream the project belong to.
The task is to classify any project's subject/stream based on its title and abstract

1. The title and abstract are added/concatenated together to form the context of the particular project.
2. Then input embeddings,token embeddings and attention mask are obtained using a pretrained BERT optimizer.
3. The obtained embeddings are given to BERT to get the pooled output of the project at once to perform the downstream classification using a linear layer


# Vector embeddings

Here I have put overview of what vector embeddings are.
They are machine interpretable format of the particular data.

This was done for a course Vector database for LLM by Deeplearning.ai
   
