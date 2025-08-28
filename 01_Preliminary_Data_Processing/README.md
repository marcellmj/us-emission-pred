# 1. Preliminary Data Processing

The raw data is prepared for further analysis through concatenation, transformation, and merging. This includes some general string transformations, and handling of missing values. 

We combine datasets containing:
- Hourly emissions data (CAMPD)
- Yearly facility data (CAMPD)
- Yearly generator data (EIA-860)
- Hourly temperature data (ASOS Network)

Files are named in logical processing order. Due to the large data volume, processing for the three main states (NY, TX, WY) is split into two notebooks: one filtered for operating hours, and one for non-operating hours. Additional states (ND, MT) are processed entirely within their respective notebooks. Temperature data is added in a separate, final notebook.
