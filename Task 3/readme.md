# Task 3 – Mortgage Portfolio (FICO Quantization)

This task focused on modeling the **probability of default (PD)** using borrower FICO scores from the mortgage portfolio.

### Key Objectives
- Implemented **quantization** via **dynamic programming** to bucket continuous FICO scores.
- Optimized buckets based on:
  - **Mean Squared Error (MSE)** – minimizes score variance.
  - **Log-Likelihood (PD-focused)** – maximizes accuracy of default prediction.
- Created a general approach for mapping FICO scores into rating categories.

### Files
- `task3_quantization.py` – quantization algorithm implementation.
- `Task3_and_4_Loan_Data.csv` – dataset used.
- `Presentation.pdf` *(or .pptx)* – summary presentation explaining the methodology, logic, and results.

### Presentation Overview
The presentation includes:
- Background on **FICO score quantization** and its importance in credit risk modeling.  
- Comparison of **MSE vs Log-Likelihood** optimization results.  
- Key insights on how credit ratings relate to the probability of default.  
- Visualizations of **FICO score distribution** and **default trends**.  

**Outcome:**  
Generated optimal FICO bucket boundaries and clearly communicated findings through a professional presentation.

