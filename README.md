# Python--steam-game-analysis
🎮 Steam Game Data Analysis

---
## Dataset used
-<a href="https://github.com/Donovandonz/Python--steam-game-analysis/blob/main/steam_games_dataset.csv">RAW.steam-games-dataset</a>

---

## 🎯 Project Overview
A comprehensive data analysis of Steam games, exploring pricing strategies, player engagement, review patterns, and success metrics. This project provides actionable insights for game developers, publishers, and data enthusiasts.

---

## 🛠️ Tools & Technologies Used

### Core Technologies
| Tool | Purpose | Badge |
|------|---------|-------|
| **Python** | Primary programming language for data analysis | ![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python) |
| **Jupyter Notebook** | Interactive development and documentation | ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter) |
| **Google Colab** | Cloud-based development with free GPU access | ![Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab) |
| **Gemini AI** | AI-assisted coding, debugging, and optimization | ![Gemini](https://img.shields.io/badge/Gemini%20AI-Assisted-8E75B2?logo=google) |
| **Pandas** | Data manipulation and analysis | ![Pandas](https://img.shields.io/badge/Pandas-1.3.0+-150458?logo=pandas) |
| **NumPy** | Numerical computing | ![NumPy](https://img.shields.io/badge/NumPy-1.24.3-013243?logo=numpy) |

---

## 📊 Dataset Overview

The dataset contains **{number_of_games}** Steam games with the following key attributes:
- **Game Information**: App ID, name, developer, publisher
- **Review Metrics**: Positive/negative counts, score rank, user score
- **Player Engagement**: Average/median playtime (forever & 2 weeks), concurrent users
- **Financial Data**: Current price, initial price, discount percentage
- **Ownership**: Estimated owner ranges

---

## 🔍 Key Findings

### 🏆 Top Performing Games
| Category | Game | Metric |
|----------|------|--------|
| Most Reviewed | {top_reviewed_game} | {top_reviewed_count:,} reviews |
| Most Played | {top_played_game} | {top_played_hours:.0f} hours avg |
| Highest Concurrent | {top_ccu_game} | {top_ccu_count:,} players |
| Best Rated | {top_rated_game} | {top_rated_percent:.1f}% positive |

### 💰 Pricing Insights
- **Average Game Price**: ${avg_price:.2f}
- **Free-to-Play Games**: {free_percent:.1f}% of all games
- **Premium Games (>$60)**: {premium_percent:.1f}% of all games
- **Average Discount**: {avg_discount:.1f}% when on sale

### 📈 Player Engagement
- **Average Playtime**: {avg_playtime:.1f} hours per game
- **Most Engaging Category**: {most_engaging_category} ({most_engaging_hours:.1f} hours avg)
- **Recent Engagement Rate**: {avg_recent_engagement:.1f}% of total playtime in last 2 weeks

### ⭐ Review Analysis
- **Average Positive Rating**: {avg_positive:.1f}%
- **Games with >90% Positive**: {highly_rated_percent:.1f}% of all games
- **Correlation**: Strong positive correlation ({review_price_corr:.2f}) between reviews and playtime

## 📈 Key Insights

### 1. **Free Games Drive Higher Engagement**
Free-to-play games average **{free_playtime:.1f} hours** vs paid games' **{paid_playtime:.1f} hours**, showing that removing price barriers leads to significantly higher player engagement.

### 2. **Price Doesn't Guarantee Quality**
The correlation between price and positive reviews is weak ({price_review_corr:.2f}), indicating that expensive games aren't necessarily better received by players.

### 3. **Discount Strategy Matters**
Games with discounts have **{discount_reviews:.0f}% more reviews** on average, suggesting that sales significantly boost visibility and player acquisition.

### 4. **Developer Reputation Drives Success**
Top developers consistently achieve **{top_dev_rating:.1f}%+ positive ratings**, showing the importance of building a strong portfolio.

### 5. **Playtime Predicts Success**
Games with high playtime correlate strongly with positive reviews ({playtime_review_corr:.2f}), suggesting that engaging gameplay is the key to player satisfaction.
| **Matplotlib** | Static visualizations | ![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7.1-11557c?logo=python) |
| **Seaborn** | Statistical data visualization | ![Seaborn](https://img.shields.io/badge/Seaborn-0.12.2-3776AB?logo=python) |
| **Plotly** | Interactive visualizations | ![Plotly](https://img.shields.io/badge/Plotly-5.14.1-3F4F75?logo=plotly) |

---

# Visual and Code Overview
-<a href="https://github.com/Donovandonz/Python--steam-game-analysis/blob/main/Steam_games_analysis.ipynb">Steam-games-code-and-visual</a>
