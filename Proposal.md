# LitRev Assistant: A Smart Literature Review Tool for the AI/ML papers in arXiv

## Team Members:

- Alice Smith – 
- Bob Johnson – 
- Hong Chu – 


## Data Source:
The project will utilize the arXiv dataset, a comprehensive repository of over a million scholarly articles in various fields of science and technology. <br>
The dataset satisfies the requirement of having more than 50,000 rows after cleaning and provides a rich set of features ideal for predictive modeling and NLP tasks.


## Project Goal:
The rapid proliferation of AI/ML research papers makes staying abreast of the latest trends and discoveries a daunting task, especially for researchers focusing on specific topics or for interdisciplinary scholars without a deep background in AI/ML. <br>
The LitRev Assistant aims to mitigate this challenge by providing a user-friendly tool to facilitate the literature review process.

## Project Plan:
Our team plans to develop a helpful literature review assistant that will guide users through the AI topic landscape, offering personalized paper recommendations from the arXiv dataset based on the user's selected topics, author networks, and paper similarities.

### 1. User Interface
An overview of AI topic trends and co-authorship networks will be presented to the user. <br>
After selecting desired tags/authors, the LitRev Assistant will generate a curated list of papers for review.

### 2. Methodology
The project will involve several key modeling components:
1. Extract the keywords and process the abstract for each paper to generate tags and calculate similarities.
2. Construct a detailed co-authorship network, revealing collaborative communities.
3. Cluster papers based on tags, contextual similarities, and coauthership communities.
4. Implement a recommendation system that intelligently suggests papers, tailored to user-selected keywords or authors.


### 3. Modeling & Tools
1. <b>NLP:</b>
- KeyBERT for keyword extraction with a noun-filtering step using NLTK's POS tagger.
- Gensim Word2Vec or SentenceTransformer for abstract similarity measurements.

2. <b>Network Analysis:</b>
- Co-authorship networks graphed with NetworkX.

3. <b>Clustering:</b>
- Clustering of papers through appropriate algorithms (e.g., K-Means) based on feature sets.

4. <b>Recommendation:</b>
- A collaborative filtering approach for recommendations to output a list of papers that are the best match of keywords and/or authors the user selected.

5. <b>Visualization & Deployment:</b>
- Interface built with Plotly Dash and deployment via Heroku for interactive user engagement.

## Interest and Challenges:
This project stands out for its potential to significantly expedite the literature review process in academic research. <br>
It promises to help domain researchers sift through extensive literature and aid non-specialists in quickly familiarizing themselves with AI/ML topics.

Challenges may include:
- Processing and managing the large volume of text data efficiently.
- Too many tags and clusters that larget increase the number of dimensions of features.
- Ensuring the relevance and accuracy of the recommendations.
- Designing an intuitive user interface that caters to researchers’ needs.

 
## Additional Notes:
1. TA Preference: We request TA John Doe for his expertise in NLP and machine learning.
2. Our team is committed to an iterative development approach, allowing for flexibility in our plan as we incorporate feedback and learn more about the data and user requirements.
