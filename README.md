# 📚 Book Recommendations

This is a machine learning project that provides book recommendations using Cosine Similarity and Collaborative Filtering. The system is designed to suggest books based on user preferences and past interactions, leveraging advanced recommendation techniques.

## ✨ Features
- **Collaborative Filtering**: Suggests books based on user-item interaction data.
- **Cosine Similarity**: Finds books that are similar to a given book based on content or features.
- **Data Visualization**: Displays popular books and trends for better insights.
- **Efficient Storage**: Precomputed similarity matrices for fast recommendations.

## 🛠️ Tech Stack
- **Programming Language**: Python
- **Libraries/Tools**: Pandas, NumPy, Scikit-learn, Streamlit, Jupyter Notebook
- **Data Storage**: CSV files for datasets, Pickle files for precomputed matrices

## 📊 Dataset
The project uses a dataset containing:
- **📘 Books.csv**: Metadata about books (e.g., title, author, genre).
- **⭐ Ratings.csv**: User ratings for different books.
- **👤 Users.csv**: Information about users.

## ⚙️ Installation

### Clone the Repository
```bash
git clone https://github.com/Harshith-Mutyapu/Books_Recommendations.git
cd Books_Recommendations
```

### Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

## 🚀 Usage

1. **Run the Streamlit Application**
   ```bash
   streamlit run app.py
   ```
2. Open your browser to the URL provided by Streamlit (e.g., `http://localhost:8501`).
3. Interact with the interface to get personalized book recommendations.

## 🧠 Recommendation Techniques

### 1. 🔍 Cosine Similarity
Cosine Similarity is used to compute the similarity between books based on their features. It measures the cosine of the angle between two vectors, indicating how similar the books are.

### 2. 🤝 Collaborative Filtering
Collaborative Filtering leverages user-item interaction data to suggest books that similar users have liked.

## 📂 Precomputed Files
- **📄 `books.pkl`**: Contains book metadata.
- **🔥 `popular.pkl`**: Contains data about the most popular books.
- **📊 `pt.pkl`**: Stores the pivot table of users and books for recommendations.
- **📈 `similarity_scores.pkl`**: Precomputed cosine similarity scores.

## 📁 File Structure
```
Books_Recommendations/
├── app.py                  # Main Streamlit application
├── Books.csv               # Book metadata
├── Ratings.csv             # User ratings
├── Users.csv               # User information
├── books.pkl               # Preprocessed book metadata
├── popular.pkl             # Precomputed popular books data
├── pt.pkl                  # Pivot table data
├── similarity_scores.pkl   # Cosine similarity scores
├── templates/              # HTML templates for visualization (if any)
├── static/                 # Static files (CSS, JS, Images)
└── .gitignore              # Git ignore file
```

## 🌟 Future Enhancements
- Add more advanced recommendation algorithms (e.g., Matrix Factorization).
- Integrate external APIs for real-time book information.
- Improve the UI/UX for better user interaction.

## 📜 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🤝 Contributing
Contributions are welcome! Please create an issue or submit a pull request to suggest improvements.

## 🙌 Acknowledgements
- The dataset is inspired by public book rating datasets.
- Thanks to open-source libraries and the developer community for their valuable tools and resources.
