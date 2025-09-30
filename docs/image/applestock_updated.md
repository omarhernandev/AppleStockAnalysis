# Apple Stock Analysis System Diagram

```mermaid
graph TD
    A[Apple Stock Data<br/>Kaggle Dataset<br/>CSV File<br/>1985-2025] --> B[Data Processing]
    
    B --> C[Data Cleaning<br/>• Convert dates<br/>• Handle missing values<br/>• Type conversion]
    
    C --> D[Feature Engineering<br/>• Calculate daily returns<br/>• Extract day of week<br/>• Create monthly averages<br/>• Add year variable]
    
    D --> E[Statistical Analysis]
    
    E --> F[Exploratory Data Analysis<br/>• Summary statistics<br/>• Distribution analysis<br/>• Correlation analysis]
    
    E --> G[Central Limit Theorem Demo<br/>• Random sampling<br/>• Stratified sampling<br/>• Sample mean distribution<br/>• CLT visualization]
    
    E --> H[Data Visualization<br/>• Interactive plots with Plotly<br/>• Histograms & bar charts<br/>• Scatter plots<br/>• Time series trends]
    
    F --> I[Statistical Insights<br/>• Return distribution patterns<br/>• Trading day analysis<br/>• Monthly trend analysis]
    
    G --> I
    
    H --> I
    
    I --> J[RMarkdown Report<br/>• Statistical findings<br/>• Interactive visualizations<br/>• CLT demonstration<br/>• Data insights]
    
    J --> K[HTML Output<br/>• GitHub Pages deployment<br/>• Interactive dashboard<br/>• Shareable report]
    
    style A fill:#e1f5fe
    style E fill:#f3e5f5
    style G fill:#fff3e0
    style I fill:#e8f5e8
    style K fill:#fce4ec
```

## Key Components:

1. **Data Input**: Apple stock CSV data from Kaggle dataset (1985-2025)
2. **Data Processing**: Cleaning, transformation, and feature engineering
3. **Statistical Analysis**: EDA and Central Limit Theorem demonstration
4. **Visualization**: Interactive plots using Plotly
5. **Output**: RMarkdown report with statistical insights

## Technologies Used:
- R/RMarkdown
- tidyverse
- plotly
- lubridate
- ggplot2
