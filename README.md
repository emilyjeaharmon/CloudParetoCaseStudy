# CloudParetoCaseStudy

### Goal
Develop recommendation model for social media posts, where users are shown posts similar to posts they have made in the past. 

### Approach Overview:
- Create visualizations and data summaries to verify data is clean and gain understanding of data context and components.
- Perform NLP cleanup to remove stopwords and retain words of interest to the analysis.
- Develop relationship strength matrix for Sellers based on the similarity of posts.
- Use sklearn CountVectorizer to create matrix of the count of words per post. 
- Use cosine_similarity to calculate the similarity of each Seller's post.
- Create function to take as input a Seller, and return the top 10 ranked potential Seller partners based on max similarity score.
