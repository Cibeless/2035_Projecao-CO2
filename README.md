
This project performs a **historical analysis and future projection** of carbon dioxide (CO₂) emissions for Brazil and Spain up to the year **2035**, using **Machine Learning** (Random Forest) models applied to environmental time series. In this specific case, data analysis techniques are used in the context of **ecological transition** and **environmental sustainability**.

The graphs include:
**Historical CO₂ emissions series**
**Projected curve for future years (up to 2035)**

Data loading**
**Public database containing historical CO₂ emissions series by country --> kaggle**
The column `Annual CO₂ emissions (tonnes)` was renamed to `Emissions`.

Only records relating to **Spain** (`Country = "Spain"`) were used.
The **Random Forest Regressor** model, suitable for trends over time, was applied.

**This project uses a** Estimated emissions until **2035**.
The final graph is saved.
