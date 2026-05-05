# 🏆 Winner Product Radar

**The Ultimate AliExpress/Alibaba Product Research Tool**

Discover winning products with data-driven confidence. The Winner Product Radar uses a multi-signal Trust Algorithm to filter, score, and rank products so you can focus on winners.

## 🎯 Features

### Trust Algorithm (0-100 Score)
Products are scored across 5 weighted signals:

| Signal | Weight | Scoring Logic |
|--------|--------|---------------|
| Order Volume | 30% | Logarithmic curve rewarding high-volume sellers |
| Rating | 25% | Normalized 0-5 scale → 0-100 |
| Verification | 20% | Verified + Gold Supplier badges |
| Store Seniority | 15% | Years in business with diminishing returns |
| Quality Signals | 10% | Original, Authentic, ISO, CE keywords |

### Smart Filters
- **Verified Suppliers Only** - Removes unverified sellers
- **Gold Suppliers Only** - Premium tier suppliers
- **Minimum Rating** - Default 4.5/5.0
- **Minimum Orders** - Default 100+ orders
- **Store Years** - Minimum 1 year seniority
- **Trust Score Threshold** - Default 70/100

## 📦 Installation

```bash
git clone https://github.com/YOUR_USERNAME/winner-product-radar.git
cd winner-product-radar
pip install -r requirements.txt
export APIFY_API_TOKEN="your_token_here"