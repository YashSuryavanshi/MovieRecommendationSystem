# Movie Recommender System - TMDB Dataset  

## Overview  
This project is a **content-based movie recommendation system** that leverages **Natural Language Processing (NLP)** techniques to recommend movies similar to a user's preferences. The system uses metadata such as genres, keywords, cast, and crew to generate recommendations using **cosine similarity**.  

## Key Features  
- Content-based filtering to recommend movies based on metadata tags.  
- Preprocessed and merged data from TMDB 5000 Movies and Credits datasets.  
- Utilizes **Bag of Words** and **TF-IDF vectorization** for feature extraction.  
- Computes **cosine similarity** between movies for precise recommendations.  
- Streamlit-based user interface for seamless interaction and deployment.  
- Model serialized with **Pickle** for efficient storage and reuse.  

## Technologies Used  
- **Python**: Core programming language for data preprocessing and modeling.  
- **Libraries**:  
  - **NumPy**: Numerical computations.  
  - **Pandas**: Data manipulation and preprocessing.  
  - **AST**: Parsing and evaluation of data structures.  
  - **Scikit-learn**: Feature extraction, vectorization, and similarity calculations.  
  - **Pickle**: Model serialization and storage.  
  - **Streamlit**: Web interface for deployment.  
- **Deployment**: Hosted on **Heroku** for public access.  

## Methodology  
1. **Data Preprocessing**:  
   - Merged TMDB 5000 Movies and Credits datasets.  
   - Extracted relevant features (genres, keywords, cast, crew) and converted them into a unified "tags" column.  
   - Applied **CountVectorizer** for feature vectorization.  

2. **Model Development**:  
   - Employed **Bag of Words** and **TF-IDF** for feature representation.  
   - Calculated **cosine similarity** between movies to determine relevance.  

3. **Web Deployment**:  
   - Built an interactive **Streamlit** interface for users to input movie preferences.  
   - Deployed the application on **Heroku**, ensuring a user-friendly experience.  

## How to Run  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/movie-recommender-system-tmdb-dataset.git  
   ```  

2. Navigate to the project directory:  
   ```bash  
   cd movie-recommender-system-tmdb-dataset  
   ```  

3. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

4. Run the Streamlit app:  
   ```bash  
   streamlit run app.py  
   ```  

5. Open the local server link in your browser and enjoy movie recommendations!  

## Dataset  
- TMDB 5000 Movies and Credits datasets available on **Kaggle**.  
- Includes over 5,000 movies with detailed metadata.  

## Results  
The recommender system accurately suggests movies based on metadata similarity, offering users a tailored experience for discovering new films.  


## Future Enhancements  
- Incorporate collaborative filtering for hybrid recommendations.  
- Add advanced NLP techniques such as BERT for deeper metadata analysis.  
- Include real-time user feedback to improve recommendations dynamically.  

---