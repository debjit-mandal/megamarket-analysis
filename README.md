
# MegaMarket Dataset Analysis

This repository contains a Jupyter notebook that provides a detailed analysis of the MegaMarket dataset. The dataset includes data on user interactions with items on the MegaMarket marketplace over a period of 4 months.

## Dataset

The dataset includes the following columns:
- `user_id`: Unique identifier for each user.
- `datetime`: The date and time when the interaction took place.
- `event`: Type of event (0: Click, 1: Add to cart, 2: Purchase).
- `item_id`: Unique identifier for each item.
- `category_id`: Identifier for the category to which the item belongs.
- `price`: Obfuscated price of the item.

**The Dataset can be found from Kaggle:** https://www.kaggle.com/datasets/alexxl/megamarket/data

## Analysis

The notebook performs various analyses to gain insights into user behavior, sales trends, and more. The analyses include:

- Event Distribution Analysis
- Price Analysis
- Category Analysis
- User Interaction Analysis
- Sales Trend Analysis
- Time-Series Analysis of Interactions
- Category-wise Event Distribution
- Correlation Analysis

## Getting Started

To run the notebook, you need to have Python and the required libraries installed. You can install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn
```

Then, open the notebook using Jupyter:

```bash
jupyter notebook megamarket_analysis.ipynb
```

## License

This project is licensed under the MIT License.

----------------------------------------------------------------

Feel free to suggest any kind of improvements.