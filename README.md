# Amazon_ML
Amazon ML Project
Product Price Prediction Solution 
Methodology 
Data Processing 
• Text Analysis:  
• Feature Engineering 
• Image Processing: Model Selection 
I used a Random Forest Regressor because: 
• Handles mixed data types well (numbers, categories) 
• Robust to outliers and noisy data 
• Provides good performance without extensive tuning 
• Works within the 8-billion parameter limit 
Key Innovations 
Smart Unit Processing 
Instead of treating all units equally, I standardized them into meaningful categories: 
• Weight units (ounce, pound, gram) 
• Volume units (fl oz, liter, milliliter) 
• Count-based units (count, capsule, pack) 
• This helped the model learn consistent pricing patterns 
Product Category Intelligence 
The system automatically detects: 
• Food products (chutney, candy, spices) 
• Beverages (tea, coffee, juice) 
• Health products (supplements, vitamins) 
• Seasonings and flavorings 
Error Resilience 
• Handles missing or malformed data gracefully 
• Standardizes diverse unit formats automatically 
• Provides fallback predictions for edge cases
