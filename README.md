# Transporationprice
Machine Learning project 

Ligia Anjos and Baranaba Mugabane


## Welcome to our project

## Objective:
Develop a model to predict the price of a ride based on features.

## Useful Features:

-price: Target variable for prediction.

-distance: Ride distance (directly impacts price).

-name: Ride type (e.g., Lyft, Lyft XL, Lux, etc.), which may indicate different pricing structures.

-hour, day, month, timezone: To capture temporal patterns (rush hours, weekdays vs. weekends, etc.).


## Quick start

```bash
git clone https://github.com/Ligia-pdf/Transporationprice
cd rideshare-price-ml
python -m venv .venv && source .venv/bin/activate   # create & activate a virtual environment
pip install -r requirements.txt                     # install exact dependencies
jupyter notebook notebooks/data.ipynb       # open the notebook
```

