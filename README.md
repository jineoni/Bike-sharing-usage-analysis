# Bike-Sharing Usage Analysis

This repository contains a single code file from a group project that analyzed bike-sharing usage patterns in Seoul. Unfortunately, we didn't organize the project on GitHub during its progress, so this repository only includes the final version of the code.

### 📅 Project Duration
- **1 Month**

### 📌 Problem Statement
- Growing popularity of Seoul's public bike-sharing system, "Ttareungyi."
- Existing studies focused on general bicycle environments, lacking a tailored analysis of Ttareungyi-specific factors.

### 🔍 Research Content
1. **Data Collection and Preprocessing**
   - Combined data on bike rental station locations with rental history data.
   - Excluded trips with 0m travel distance and trips below the average travel distance (2.08 km).
   
2. **Most Frequently Used Routes**
   - Identified the most common combinations of rental and return locations.
   - Removed trips where rental and return locations were the same before recalculating the most frequent combinations.
   
3. **Affinity Scoring**
   - Created a scoring system using key variables such as slope, illegal parking rate, and bicycle lane coverage.

### 📊 Research Findings
- **Distribution of Rental Stations (2022)**  
  Visualization of all bike rental stations across Seoul.  

  ![Map of bike rental stations](https://prod-files-secure.s3.us-west-2.amazonaws.com/db5c33d0-e510-4667-b185-b03bb446fb45/931bb721-5741-4fbf-96f8-5af074f38005/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-03-16_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_12.31.25.png)

- **Most Frequent Routes by Districts**  
  Key rental-return station pairs with the highest usage rates across different districts.  

  ![Map of popular routes](https://prod-files-secure.s3.us-west-2.amazonaws.com/db5c33d0-e510-4667-b185-b03bb446fb45/19fe4a2b-74cd-4c67-875c-94a2246b5185/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-03-16_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_12.33.27.png)

- **Highest Usage for Unique Routes**  
  Excluding same-location rentals and returns, high usage was observed in areas with greenery or near waterfronts.

  ![Green and water regions map](https://prod-files-secure.s3.us-west-2.amazonaws.com/db5c33d0-e510-4667-b185-b03bb446fb45/aac94b2e-e650-4941-9c14-03d67259c63e/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-03-16_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_12.45.39.png)

- **Final Affinity Score**  
  Map reflecting rideability scores based on environmental factors.

  ![Rideability score](https://prod-files-secure.s3.us-west-2.amazonaws.com/db5c33d0-e510-4667-b185-b03bb446fb45/92524205-fb19-42ae-b39b-113b1a08f66e/%EC%B5%9C%EC%A2%85_%EC%A3%BC%ED%96%89%ED%99%98%EA%B2%BD%EC%A0%90%EC%88%98.png)

### 🌟 Conclusion
- **Optimal placement of bike rental stations** can significantly improve usage rates.
- Limitations include not incorporating variable importance and weights, requiring **further research**.

---

### 🙋 My Role and Takeaways
- Conducted data preprocessing.
- Analyzed most frequent routes for five districts in collaboration with team members.
- Visualized rental station distribution and popular routes using Kepler.gl.

#### Key Learnings:
- Developed skills in using Kepler.gl for intuitive spatial data visualization.
- Improved efficiency in data management and collaborative project planning.
