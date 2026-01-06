# Data Challenges & Competition Projects

Collection of data science competition entries and challenge projects, featuring time series forecasting, web scraping, and real-world problem solving.

## Projects

### 1. Gen-I Trading Challenge - Electricity Price Forecasting
**Forecasting electricity prices for Slovenia's IDA2 intraday market**

A comprehensive solution for the Gen-I Trading Challenge, predicting hourly electricity prices using machine learning and statistical methods. The project demonstrates feature engineering, model selection, and deployment strategies for time-critical trading decisions.

- **Tech Stack**: Python, scikit-learn, pandas, numpy, Selenium
- **Models Tried**: RANSAC, Gradient Boosting, XGBoost, TensorFlow/Keras, statsmodels
- **Final Approach**: RANSAC regressor with engineered features
- **Status**: Complete competition entry

**Key Features**:
- Automated data collection from multiple sources
- Advanced feature engineering (lag features, rolling statistics, time-based features)
- Robust outlier handling with RANSAC
- Comprehensive evaluation and backtesting

[See Gen-I README](./Gen-I-Trading-Challenge/Task%202/README.md)

### 2. arso-scraper - Weather Data Collection
**Slovenian weather data scraper for ARSO (Slovenian Environment Agency)**

Web scraper for collecting and analyzing weather data from Slovenia's official meteorological service. Includes data visualization and historical analysis capabilities.

- **Tech Stack**: Python, web scraping, pandas
- **Features**: Automated data collection, CSV export, visualization
- **Data**: Ljubljana weather data (2022-2024)
- **Status**: Functional scraper

[See arso-scraper README](./arso-scraper/readme.md)

## Purpose

These projects demonstrate:
- **Real-world problem solving**: Tackling actual business/research challenges
- **Time series forecasting**: Advanced techniques for temporal data
- **Web scraping & automation**: Data collection from live sources
- **Model deployment**: From prototype to production-ready solutions

## Competition Results

### Gen-I Trading Challenge
- **Task 2**: Complete implementation with comprehensive README
- **Approach**: Multi-model comparison with RANSAC as final choice
- **Lessons Learned**: Feature engineering crucial, simpler models often outperform complex ones

## Installation & Usage

Each project has its own setup instructions. Navigate to individual project directories for details:

```bash
cd Gen-I-Trading-Challenge/Task\ 2/
# See README for setup

cd arso-scraper/
# See readme for usage
```

## Project Structure

```
data-challenges/
├── Gen-I-Trading-Challenge/
│   ├── Task 1/          # Initial exploration
│   ├── Task 2/          # Main implementation ⭐
│   └── Task 3/          # Extended analysis
└── arso-scraper/        # Weather data scraper
```

## Skills Demonstrated

- Time series analysis and forecasting
- Feature engineering for ML models
- Web scraping and data extraction
- Model evaluation and selection
- Production deployment considerations
- Documentation and reproducibility

## Future Enhancements

- [ ] Deploy Gen-I model as API service
- [ ] Expand arso-scraper to more locations
- [ ] Add more competition entries
- [ ] Create unified data pipeline framework
- [ ] Benchmark against state-of-the-art methods

## License

MIT License - see individual projects for details

## Attribution

Project organization and documentation structure created with assistance from Claude Code. All competition code, analysis, and solutions are original work.

---

*Data science competition entries - 2023-2024*
