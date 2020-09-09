# Content-Based-Book-Recommmendation-System
Created a prototype Content based Book Recommendation System using both Fiction and non- fiction books in the dataset. 
This system recommends books to a user by taking similarity between the books. 
It identifies the similarity between the books based on its description. It also considers the user previous history in order to recommend a similar book.
Developed the recommendation engine using book title. 
First converted each book title  into vectors using TF-IDF and bigram. 
Then calculated the similarity between all the books using cosine similarity.
At last defined a function that takes book title and genre as an input and returns the top five similar recommended books based on the title and description.
