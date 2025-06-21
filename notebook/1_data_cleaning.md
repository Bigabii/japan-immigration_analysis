# Data Cleaning Process - Japanese Labor Trends (2010-2023)

## Sources
- **Raw Data**: Population of 15 Years Old and Over by Sex and Labour Force Status
- **Files**: `(raw)Population of 15 Years Old and Over by Sex and Labour Force Status` (see `/data/raw/`)

## Cleaning Steps
1. **Column Renaming**  
   - Translated headers from Japanese to English  

2. **Sheet Separation**  
   - Created tabs for:  
     - `both_sexes`: Total workforce  
     - `male`: Male employment trends  
     - `female`: Female employment trends  

3. **Format Fixes**  
   - Removed header notes (rows 1-11)  
   - Converted `"1,000"` → `1000` in numeric columns  

