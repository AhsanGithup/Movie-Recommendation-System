# 🎬 Movie Recommendation System

This project is a content-based movie recommendation system built using Python and popular data science libraries. It suggests movies based on a given movie title by analyzing similarities in genres, keywords, cast, and crew.

## 🚀 Features

- Recommends movies similar to a selected title  
- Uses content-based filtering with cosine similarity  
- Preprocessing of metadata like genres, keywords, cast, and crew  
- Interactive with user inputs  
- Built with clean and modular code in Jupyter Notebook  

## 🧰 Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn (for TF-IDF Vectorization and Cosine Similarity)  
- NLTK (Natural Language Toolkit)  
- Jupyter Notebook  

## 📁 Dataset

The model is based on the TMDB 5000 Movie Dataset (https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata), which includes metadata for 5000 movies.

Files used:  
- movies.csv  
- credits.csv  

Make sure these files are in your working directory.

## 🧠 How It Works

1. Load and merge data from movies.csv and credits.csv  
2. Data cleaning: Remove duplicates, handle nulls, and extract useful fields  
3. Feature engineering: Extract keywords, genres, director, and top cast members  
4. Create a "tags" column by combining relevant text features  
5. Vectorization: Use CountVectorizer to convert text to numerical form  
6. Calculate similarity: Use cosine similarity to measure how alike two movies are  
7. Recommendation: Return top 5–10 similar movies to the user input  

## 📸 Sample Output

If you input: Avatar  
The system returns:  
1. John Carter  
2. Guardians of the Galaxy  
3. Prince of Persia: The Sands of Time  
4. Star Trek Into Darkness  
5. The Host  

## 🏁 Getting Started

1. Clone the repository:  
git clone https://github.com/your-username/movie-recommendation-system.git  
cd movie-recommendation-system  

2. Install the requirements:  
pip install -r requirements.txt  

3. Launch the Jupyter Notebook:  
jupyter notebook  

4. Run Movie Recommended.ipynb and test it with your favorite movies!

## 📦 Requirements

Recommended libraries to install:  
- pandas  
- numpy  
- scikit-learn  
- nltk  

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📝 License

This project is open-source and available under the MIT License.

