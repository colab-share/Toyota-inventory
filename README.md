# 🚗 Toyota Sienna Inventory Tracker

Find your perfect Toyota Sienna by filtering real-time inventory data from dealerships across the USA.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/colab-share/Toyota-inventory/blob/main/Sienna_Inventory.ipynb)

## Quick Start

1. **Click "Open in Colab"** above
2. **Edit your preferences** in the first code cell:
   ```python
   states = ['CA']  # Any US state(s)
   models = ['Limited FWD', 'Limited AWD']
   colors = ['Ruby Flare Pearl', 'Wind Chill Pearl']
   interior_colors = ['Macadamia leather-trimmed']
   ```
3. **Run all cells** (Runtime → Run all)
4. **View results** - Color-coded for easy scanning:
   - 🟢 Green = Best deals (low options, no markup)
   - 🔴 Red = Dealer markup over $1,000

## Available Options

**Models:** LE, XSE, XLE, Limited, Platinum, Woodland Edition (FWD/AWD)

**Colors:** Magnetic Gray Metallic, Ruby Flare Pearl, Midnight Black Metallic, Cypress, Ice Cap, Celestial Silver Metallic, Blueprint, Predawn Gray Mica, Cement, Wind Chill Pearl

**Interiors:** Gray Woven Fabric, Black/Cool Gray/Gray Softex, Black/Macadamia/Graphite Leather

*Tip: Leave color arrays empty `[]` to see all options*

## Understanding Results

- **Option Price** = Total MSRP - Base MSRP - $1,495 (delivery)
- **Markup** = Selling Price - Total MSRP
- **Shipping Status** = "At dealer" (in stock) or in transit

## Data Source

Inventory data from [Vehicle_Inventory](https://drive.google.com/drive/u/0/folders/1uOnNR7wVHN6o5rTjcMhVsNL3SKq5UJwC) - updated daily. Thanks to the community contributors who maintain this!

## Tips

- Search multiple states: `states = ['CA', 'NV', 'AZ']`
- Show more results: `entries_to_display = 50`
- Best deals = Green highlights (minimal options + no markup)
- Check "Upcoming" section for vehicles in transit

---

**Disclaimer:** Always verify availability and pricing directly with dealerships before visiting.
