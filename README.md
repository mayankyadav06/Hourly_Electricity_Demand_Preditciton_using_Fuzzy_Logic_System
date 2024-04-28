# Hourly_Electricity_Demand_Preditciton_using_Fuzzy_Logic_System

# Fuzzy Logic System
A Fuzzy Logic System is a type of artificial intelligence system that makes decisions based on 
fuzzy logic, a mathematical logic that attempts to solve problems with an open, imprecise spectrum 
of data, enabling it to operate akin to human brains. These systems are designed to mimic human 
decision-making processes and are widely used in various fields, including control systems and 
prediction models.

Dataset Link: https://data.mendeley.com/datasets/fdfftr3tc2/1

# Librarires Used
  1. scikit-learn
  2. pandas
  3. numpy


# Data Preprocessing
  1. Dataset Statistics Information
  2. Date Time Formatting
  3. Data Resampling
  4. Datatype Formatting
  5. Outlier Checking
  6. Dimensionality Reduction
  7. Label Encoding

# EDA
  1. Correlation Heatmap
  2. LinePlot
  3. HistPlot
  4. BoxPlot

# Membership Functions used
  1. Triangluar
  2. Trapezoidal
    
# Rules used
  1. If it is **night** and the **season** is **winter**, then the **electric demand** is **high**.
  2. If it is **morning** or **evening** and it is **not the weekend**, then the **electric demand** is **high**.
  3. If the **temperature** is **very high**, then the **electric demand** is **high**.
  4. If the **humidity** is **high** and the **temperature** is **very high**, then the **electric demand** is **high**.
  5. If it is **afternoon** and the **season** is **spring** or **autumn**, then the **electric demand** is **medium**.
  6. If the **temperature** is **very low** and the **humidity** is **low**, then the **electric demand** is **low**.
  7. If the **wind speed** is **medium** and the **temperature** is **medium**, then the **electric demand** is **medium**.
  8. If it is **morning** and the **wind speed** is **high**, then the **electric demand** is **low**.
  9. If it is **night** and the **temperature** is **very high**, then the **electric demand** is **high**.
  10. If it is **afternoon** and the **wind speed** is **high**, then the **electric demand** is **low**.
  11. If it is **afternoon** and the **season** is **summer**, then the **electric demand** is **high**.
  12. If it is **evening** or **night** and the **season** is **winter**, then the **electric demand** is **high**.
  13. If it is **afternoon**, the **wind speed** is **high**, and the **season** is **autumn**, then the **electric demand** is **low**.

# Result/Outcome
  System has MAE of +- 9508.16 KW
  ![image](https://github.com/mayankyadav06/Hourly_Electricity_Demand_Preditciton_using_Fuzzy_Logic_System/assets/140626220/d8c51b39-030e-4cc2-9f70-c8cc31bd5ba2)

