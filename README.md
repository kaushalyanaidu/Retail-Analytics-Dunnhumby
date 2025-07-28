# Dataset Information

## Required Dataset Files
The following files are required for running the analysis:

1. `transaction_data.csv` (135MB)
   - Contains detailed transaction records
   - Too large for GitHub, must be downloaded separately

2. `causal_data.csv` (664MB)
   - Contains promotional and causal information
   - Too large for GitHub, must be downloaded separately

3. Smaller data files included in repository:
   - `campaign_desc.csv`
   - `campaign_table.csv`
   - `coupon.csv`
   - `coupon_redempt.csv`
   - `hh_demographic.csv`
   - `product.csv`

## Data Size Limitations
Due to GitHub's file size limitations (100MB per file), the following files are not included in this repository:
- `transaction_data.csv` (135MB)
- `causal_data.csv` (664MB)

## Obtaining the Dataset
1. Visit the Dunnhumby - The Complete Journey dataset website
2. Download the required files
3. Place the downloaded files in this directory

## Data File Descriptions

### transaction_data.csv
- Contains household-level transactions
- Fields: household_key, basket_id, day, product_id, quantity, sales_value, store_id, retail_disc, trans_time, week_no, coupon_disc, coupon_match_disc

### causal_data.csv
- Contains promotion and display information
- Fields: product_id, store_id, week_no, display, mailer

### Other Files
- `campaign_desc.csv`: Campaign descriptions and types
- `campaign_table.csv`: Campaign schedule and household assignments
- `coupon.csv`: Coupon characteristics
- `coupon_redempt.csv`: Coupon redemption details
- `hh_demographic.csv`: Household demographics
- `product.csv`: Product characteristics

## Data Privacy
This dataset has been anonymized to protect customer privacy. Please handle the data responsibly and in accordance with applicable data protection regulations. 