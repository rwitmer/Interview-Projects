This project is comprised of a report and four Jupyter notebooks. Please begin by reading ChallengeSummary.pdf. 

The report refers to four notebooks which can best be understood by reading them in order.
 
1_Data_Exploration.ipynb
2_Legal_BERT_Build_Embeddings.ipynb
3_Simple_Classifier_on_Embeddings.ipynb
4_Simple_Classifier_on_Top_10_Embeddings.ipynb

The last two notebooks refer to two pickled files that are produced in the second notebook. I have not included them in the zip file for the sake of space but you can find them at these links. Only those people with the links can access the data so for security purposes, you should not share the links with those outside the organization.

df_w_embeddings_ohe.pkl	https://drive.google.com/file/d/1Uze08NCrKQBUAhT9FNotmFUuRmvCexhU/view?usp=sharing
df_w_embeddings.pkl	https://drive.google.com/file/d/1cCokepcMT77hWaA-FurzDQ9j9Q6xr1Ef/view?usp=sharing

Alternatively, you can reproduce the files by running the second notebook and uncommenting the lines that produce each file. However, the dataframes in question contain embeddings for all 18k rows of documents and will take 45 minutes to re-create using an A100 GPU on Google Colab. 

7:17PM
