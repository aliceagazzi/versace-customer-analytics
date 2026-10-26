# Versace E-Commerce Customer Analytics

**Customer journey analysis · Conversion analytics · Market basket analysis · Recommendation rules**

## Overview

This academic analytics project explores customer behaviour across the Versace e-commerce journey using three complementary Python notebooks: time to purchase and cross-session exploration, cart abandonment versus completed purchases, and product-level association rules for recommendations.

> **Data availability:** The source datasets are **not included** in this repository. The notebooks require access to the original datasets and have not been rerun as part of this packaging. This is a code-and-methodology showcase, not a fully reproducible public dataset release.

## Analyses

| Notebook | Focus |
| --- | --- |
| [`01_customer_journey_time_to_purchase.ipynb`](notebooks/01_customer_journey_time_to_purchase.ipynb) | Cleaning, exploratory analysis, customer journey and time-to-purchase behaviour across sessions |
| [`02_cart_abandonment_vs_purchase.ipynb`](notebooks/02_cart_abandonment_vs_purchase.ipynb) | Funnel behaviour, abandonment versus purchase, predictive/statistical analysis |
| [`03_market_basket_recommendations.ipynb`](notebooks/03_market_basket_recommendations.ipynb) | Frequent itemsets, association rules and product recommendations |

## Methods and tools

Python, pandas, NumPy, matplotlib, seaborn, scikit-learn and mlxtend. Methods include exploratory data analysis, customer funnel analysis, and FP-Growth-based association rules.

## Running the notebooks

1. Install packages: `pip install -r requirements.txt`.
2. Obtain authorized access to the datasets listed below and place them in the working directory (or update the notebook paths).
3. Open notebooks in the order listed above. Some cells may depend on additional generated files or notebook-specific environment paths.

Required input files (not distributed):

- `IMA2026_Versace_Time_to_Purchase.csv`
- `IMA2026_Versace_Cart_Abandonment.csv`
- `IMA2026_Versace_MBA_Product_Level.csv`

The cart-abandonment notebook also references `dataset_cleaned.xlsx`, which may be a generated/intermediate file.

## Publication notes

The uploaded notebook **outputs and execution counts have been cleared** in this public-ready copy to avoid accidentally exposing transaction-level records, user identifiers, or proprietary results. The code and markdown have been retained. See [`PUBLICATION_CHECKLIST.md`](PUBLICATION_CHECKLIST.md) before making this repository public.

## Credits

Academic group project. Add the full team credits and specify Alice Agazzi's individual contributions before public release. Versace is referenced as the subject of the academic case study; this repository is not an official Versace publication.
