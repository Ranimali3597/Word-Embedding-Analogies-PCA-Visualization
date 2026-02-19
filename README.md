# Word-Embedding-Analogies-PCA-Visualization
This project demonstrates word embedding analogies using the Google News Word2Vec model and visualizes semantic relationships through PCA. It extracts a subset of embeddings, performs country–capital analogy predictions, evaluates accuracy, and presents 2D PCA plots for meaningful word clusters.
This project explores the power of word embeddings by demonstrating how semantic relationships between words can be represented and analyzed using vector operations. Using the pre-trained Google News Word2Vec model, the project extracts a meaningful subset of word embeddings from a custom dataset containing capital–country pairs and additional semantic words.

The core objective is to showcase how vector arithmetic can capture linguistic analogies such as king − man + woman ≈ queen and how city–country relationships can be used to predict missing countries. A custom analogy function is implemented to evaluate these relationships and measure prediction accuracy on a capitals dataset.

To visualize how embeddings cluster semantically, the project applies Principal Component Analysis (PCA) to reduce the original 300-dimensional word vectors into 2D space. The resulting scatter plot highlights how similar words naturally group together—for example, city, town, village appear close, and happy, joyful cluster away from sad. This visual interpretation reinforces how embedding spaces encode semantic patterns.

Overall, this project serves as an educational demonstration of word embeddings, vector analogies, PCA-based dimensionality reduction, and visualization—offering an intuitive understanding of how modern NLP models represent meaning numerically.
