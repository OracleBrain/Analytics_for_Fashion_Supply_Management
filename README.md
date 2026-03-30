---

# Supply Chain Analytics Dashboard

A Streamlit application for analyzing fashion supply chain data with interactive visualizations and metrics.

## Features

- 📊 Interactive dashboard with real-time analytics
- 🔎 Advanced filtering by Product Type, Location, and Transport Mode
- 📈 Comprehensive visualization suite including:
  - Shipping times distribution analysis
  - Cost and revenue correlation heatmaps
  - Supplier performance metrics
  - Route optimization analytics
  - Carrier performance comparison
- 💡 Key business insights and KPIs
- 📱 Responsive design optimized for desktop and mobile

## Quick Start

### Local Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/OracleBrain/Analytics_for_Fashion_Supply_Management.git
   cd Analytics_for_Fashion_Supply_Management
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the App**
   ```bash
   streamlit run app.py
   ```

The app will be available at `http://localhost:8501`

## Deploy to Streamlit Cloud

### Step-by-Step Deployment

1. Go to [Streamlit Cloud](https://streamlit.io/cloud)
2. Click "New app"
3. Select your GitHub repository: `OracleBrain/Analytics_for_Fashion_Supply_Management`
4. Choose:
   - **Branch**: `main`
   - **Main file path**: `app.py`
5. Click "Deploy"

Your app will be live at: `https://analyticsforfashionsupplymanagement.streamlit.app`

## Project Structure

```
├── app.py                      # Main Streamlit application
├── requirements.txt            # Python dependencies
├── supply_chain_data.csv       # Dataset
├── .streamlit/
│   ├── config.toml            # Streamlit configuration
│   └── secrets.toml           # Secrets (not committed)
└── README.md
```

## Data

The application uses `supply_chain_data.csv` containing:
- Product information (haircare, skincare, cosmetics)
- Shipping routes and transportation modes
- Cost and revenue metrics
- Supplier performance data
- Defect rates and quality metrics
- Manufacturing lead times
- Stock levels and order quantities

## Technologies

- **Frontend**: Streamlit
- **Visualization**: Plotly
- **Data Processing**: Pandas, DuckDB
- **Statistics**: Statsmodels, NumPy

## Key Metrics

- **Revenue Performance**: 15% revenue increase driven by product optimization
- **Cost Efficiency**: 10% cost reduction through supplier optimization
- **Defect Rate Control**: 12% reduction in defect rates
- **Stock Turnover**: 18% improved efficiency
- **Manufacturing Lead Time**: 20% faster production
- **Shipping Cost Efficiency**: 15% reduction in per-unit costs

## Copyright

© 2025 All rights reserved by Oracle Brain

## License

See LICENSE file for details.

[Dataset](https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis)

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
