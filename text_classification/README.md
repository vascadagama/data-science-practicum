# Classification of toxic comments (with BERT)

Online store "Wikishop" launches a new service. Now users can edit and supplement product descriptions, just like in wiki communities. That is, clients propose their edits and comment on the changes of others. The store needs a tool that will look for toxic comments and submit them for moderation.

Train the model to classify comments into positive and negative. At your disposal is a dataset with markup on the toxicity of edits.

Build a model with a quality metric *F1* of at least 0.75.

**Instructions for the implementation of the project**

1. Download and prepare data.
2. Train different models.
3. Draw conclusions.


**Data Description**

The data is in the `toxic_comments.csv` file. The *text* column contains the text of the comment, and *toxic* is the target attribute.
