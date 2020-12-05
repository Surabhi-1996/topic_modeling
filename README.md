# Topic Modeling using Latent Dirichlet Allocation and Non-negative Matrix Factorization

## We are using npr dataset, which contains comprehensive identity database for every usual resident in the country.

Using LDA and NMF, we will classify the Article data into below 6 topics:
- health
- election
- legis
- politics
- election
- music
- edu

- Import the dataset using pandas and conduct data preprocessing.
- Use TF-IDF Vectorization to create a vectorized document term matrix. 
- Using Scikit-Learn create an instance of LDA and NMF with 7 expected components.
- Print our the top 15 most common words for each of the 7 topics.
- Assign the rows with maximum probability of relation with topic
