📂 Projects in this Repo

* **Fraud Detection in Electricity & Gas Consumption (Zindi Challenge)**
  * Analyzed customer billing histories to predict utility fraud.
  * Extracted custom consumption features and built ensemble models using CatBoost & LightGBM.

* **Credit Risk Default Prediction (Zindi Challenge)**
  * Classified loan applicants as Good or Bad credit risks using current loan terms, customer demographics, and historical repayment records.
  * Engineered high-impact behavioral features including repayment delay statistics (`delay_days-mean`, `delay_days-max`), loan escalation ratios, and fee burdens.
  * Implemented 5-fold Stratified Cross-Validation and calibrated probability thresholds to directly optimize the competition Error Rate ($1 - \text{Accuracy}$).
  * Blended **LightGBM** and **CatBoost** to drop the out-of-fold error rate from a baseline of **21.80%** down to **19.28%**.

*More projects will be added as I keep learning and building!*
