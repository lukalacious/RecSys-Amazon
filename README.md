# RecSys-Amazon: Electronics Recommendation System

A comprehensive recommendation system for Amazon electronics using collaborative filtering and machine learning techniques.

## 📊 Project Overview

This project implements a recommendation system for Amazon electronics using a dataset of 7.8 million user ratings. The system employs collaborative filtering techniques to provide personalized product recommendations.

### Key Features
- **Large-scale Data Processing**: Handles 7.8M+ Amazon electronics ratings
- **Advanced Filtering**: Smart user/item threshold filtering to optimize data quality
- **Sparsity Analysis**: Comprehensive analysis of data sparsity and its impact
- **Collaborative Filtering**: Implementation of various recommendation algorithms
- **Performance Metrics**: Detailed evaluation using industry-standard metrics

## 🚀 Quick Start

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required packages: pandas, numpy, scikit-learn, matplotlib, seaborn

### Installation
```bash
git clone https://github.com/lukalacious/RecSys-Amazon.git
cd RecSys-Amazon
pip install -r requirements.txt
```

### Usage
1. Open `rec_sys_amazon.ipynb` in Jupyter Notebook
2. Download the Amazon Electronics dataset (link in notebook)
3. Run the cells sequentially for complete analysis

## 📁 Project Structure

```
RecSys-Amazon/
├── rec_sys_amazon.ipynb           # Main analysis notebook
├── ratings_Electronics.csv        # Amazon electronics dataset (318MB)
├── sampled_data_10mb.csv          # Smaller sample for testing
├── README.md                      # Project documentation
└── requirements.txt               # Python dependencies
```

## 🔍 Data Analysis

### Dataset Statistics
- **Original Dataset**: 7,824,482 ratings
- **After Filtering**: ~470,000 ratings (6% retention)
- **Users**: Filtered to users with ≥20 ratings
- **Items**: Filtered to items with ≥5 ratings
- **Sparsity**: Reduced from 100% to 99.96%

### Data Processing Pipeline
1. **Data Loading**: Import raw Amazon electronics ratings
2. **Exploratory Analysis**: Statistical overview and distribution analysis
3. **Threshold Analysis**: Optimize user/item filtering parameters
4. **Data Cleaning**: Apply filtering and create processed dataset
5. **Sparsity Calculation**: Measure data density improvements

## 🤖 Recommendation Algorithms

### Implemented Approaches
- [ ] **Collaborative Filtering**: User-based and item-based filtering
- [ ] **Matrix Factorization**: SVD and NMF techniques
- [ ] **Deep Learning**: Neural collaborative filtering
- [ ] **Hybrid Models**: Combining multiple approaches

### Evaluation Metrics
- [ ] **Accuracy**: RMSE, MAE
- [ ] **Ranking**: Precision@K, Recall@K, NDCG
- [ ] **Diversity**: Intra-list diversity, coverage

## 📈 Results

*Results will be updated as models are implemented and evaluated.*

## 🛠️ Technical Implementation

### Key Functions
- `analyze_threshold_impact()`: Analyzes impact of different filtering thresholds
- `recommend_threshold()`: Provides optimal threshold recommendations
- Sparsity calculation utilities
- Data visualization functions

### Optimization Strategies
- Memory-efficient data processing
- Intelligent threshold selection
- Sparse matrix operations
- Parallel processing capabilities

## 📚 References

- Amazon Product Data: [http://jmcauley.ucsd.edu/data/amazon/](http://jmcauley.ucsd.edu/data/amazon/)
- Collaborative Filtering Techniques
- Matrix Factorization Methods
- Evaluation Metrics for Recommender Systems

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

Luke Roberts - lukejrobertsza@gmail.com

Project Link: [https://github.com/lukalacious/RecSys-Amazon](https://github.com/lukalacious/RecSys-Amazon)

---

*This project is part of the MIT Applied Data Science Program - Module 7.1 Elective Project*
