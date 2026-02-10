# Swiggy Data Analysis Project

## 📊 Project Overview

This project provides a comprehensive analysis of Swiggy restaurant and food ordering data across multiple cities in India. The analysis explores ordering patterns, pricing trends, restaurant ratings, popular cuisines, and geographic distribution of food delivery services.

## 📁 Dataset Information

**Dataset Size:** 197,430 records

**Columns:**
- **State** - Indian state where the order was placed
- **City** - City of the order
- **Order Date** - Date when the order was placed (2025 data)
- **Restaurant Name** - Name of the restaurant
- **Location** - Specific location/area within the city
- **Category** - Food category (e.g., Momos, Snacks, Recommended)
- **Dish Name** - Name of the dish ordered
- **Price (INR)** - Price in Indian Rupees
- **Rating** - Restaurant/dish rating (0-5 scale)
- **Rating Count** - Number of ratings received

## 🛠️ Technologies Used

- **Python 3.x**
- **Libraries:**
  - `numpy` - Numerical computing
  - `pandas` - Data manipulation and analysis
  - `matplotlib` - Static visualizations
  - `seaborn` - Statistical data visualization
  - `plotly` - Interactive visualizations

## 📈 Analysis Performed

The notebook includes the following key analyses:

1. **Geographic Analysis**
   - Distribution of restaurants across states and cities
   - Top cities by sales volume
   - Regional food preferences

2. **Pricing Analysis**
   - Price distribution across different categories
   - City-wise pricing comparisons
   - Average price per dish category

3. **Rating Analysis**
   - Restaurant rating distributions
   - Correlation between price and ratings
   - Most highly-rated restaurants and dishes

4. **Category Analysis**
   - Popular food categories
   - Category-wise sales performance
   - Trending cuisines

5. **Temporal Analysis**
   - Order trends over time
   - Peak ordering periods

## 📊 Key Visualizations

- **Top 5 Cities by Sales (INR)** - Horizontal bar chart showing revenue distribution
- Interactive charts created using Plotly for dynamic exploration
- Statistical plots using Seaborn for pattern identification

## 🚀 Getting Started

### Prerequisites

```bash
pip install numpy pandas matplotlib seaborn plotly
```

### Running the Analysis

1. Clone this repository
2. Ensure you have the Swiggy dataset in the same directory
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook Swiggy.ipynb
   ```
4. Run all cells to generate the analysis and visualizations

## 📝 Usage

This analysis can be used for:
- Understanding food delivery market trends in India
- Restaurant business insights and decision-making
- Pricing strategy optimization
- Customer preference analysis
- Geographic expansion planning for food delivery services

## 🔍 Key Insights

The analysis reveals insights about:
- **Top performing cities** for food delivery services
- **Popular food categories** across different regions
- **Pricing patterns** and their relationship with ratings
- **Geographic distribution** of restaurants
- **Customer preferences** based on ordering patterns

## 📂 Project Structure

```
.
├── Swiggy.ipynb          # Main analysis notebook
├── README.md             # Project documentation
└── data/                 # Dataset directory (if applicable)
```

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new analyses
- Improve visualizations
- Add new features

## 📧 Contact

For questions or feedback about this analysis, please open an issue in the repository.

## 📄 License

This project is open source and available for educational and analytical purposes.

---

**Note:** This analysis is based on Swiggy data from 2025 and provides insights into the Indian food delivery market landscape.
