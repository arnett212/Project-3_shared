# UFO Sightings Data Analysis

## Overview

This project analyzes UFO sighting data to uncover patterns and trends related to geographic locations, sighting frequencies, durations, and UFO shapes. The dataset, originally consisting of **70,000 unique records**, was reduced to **10,000 records** for computational efficiency while maintaining statistical reliability through proper sampling techniques.

The analysis aims to answer three key questions:

1. **What is the frequency of UFO sightings in the USA compared to the rest of the world?**
2. **What are the common location sightings, and how does their frequency/duration differ from one place to another?**
3. **What are the most common shapes of UFOs, varying by location as well?**

---

## Dataset

### Column Descriptions
- **`datetime`**: The date and time of the UFO sighting.
- **`city`**: The city where the UFO sighting occurred.
- **`state`**: The state (for US sightings).
- **`country`**: The country where the sighting was reported (e.g., `us`).
- **`shape`**: The reported shape of the UFO (e.g., `disk`, `triangle`, `circle`).
- **`duration (seconds)`**: The duration of the sighting in seconds.
- **`comments`**: Textual descriptions of the sighting.
- **`date posted`**: The date the sighting was reported.
- **`latitude`** and **`longitude`**: Geographic coordinates of the sighting.

### Sampling Approach
The dataset was reduced to 10,000 records using:
1. **Random Sampling**: Ensured unbiased representation across geographic locations, UFO shapes, and durations.
2. **Stratification**: Maintained proportionality of records based on countries and shapes.
3. **Preservation of Extreme Cases**: Included records with unique shapes or unusually long durations.

---

## Key Questions and Findings

### **Question 1: What is the frequency of UFO sightings in the USA compared to the rest of the world?**
- **Results**:
  - **USA**: 9,676 sightings
  - **Canada**: 320 sightings
  - **Australia**: 2 sightings
  - **Great Britain**: 1 sighting
- **Insights**:
  - The USA reports an overwhelming majority of sightings, influenced by cultural fascination, larger population, and centralized UFO reporting systems.

### **Question 2: What are the common location sightings, and how does their frequency/duration differ?**
- **Top 5 Cities**:
  - **Seattle, WA**: 80 sightings (Avg. duration: ~626 seconds)
  - **Tinley Park, IL**: 70 sightings (Avg. duration: ~1,169 seconds)
  - **San Diego, CA**: 61 sightings (Avg. duration: ~3,161 seconds)
  - **Phoenix, AZ**: 58 sightings (Avg. duration: ~983 seconds)
  - **Las Vegas, NV**: 56 sightings (Avg. duration: ~1,136 seconds)
- **Insights**:
  - High population cities report more sightings.
  - San Diego's sightings are notable for significantly higher durations, indicating possible persistent phenomena or environmental factors.

### **Question 3: What are the most common shapes of UFOs, varying by location?**
- **Top 5 Shapes in the USA**:
  - **Light**: 1,923 sightings
  - **Triangle**: 1,004 sightings
  - **Circle**: 923 sightings
  - **Unknown**: 880 sightings
  - **Fireball**: 805 sightings
- **Insights**:
  - "Light" sightings dominate, likely due to their simple appearance, while structured shapes like "Triangle" may align with reports of experimental aircraft.
  - Distribution of shapes across states reveals interesting regional variations.

---

## Visualizations

1. **Bar Chart**: Frequency of UFO sightings by country.
2. **Scatter Plot (Bubble Chart)**: Top 10 cities by sightings, with bubble size representing average duration.
3. **Stacked Bar Chart**: Most common UFO shapes across countries.
4. **Heatmap**: UFO sightings by state and shape within the USA.

---

## Future Work

1. **Temporal Analysis**:
   - Examine sighting trends over time (e.g., year-over-year changes).
2. **Seasonality**:
   - Determine if sightings are more common during specific months or seasons.
3. **Event Correlation**:
   - Analyze whether sightings coincide with meteor showers, satellite launches, or other celestial events.


---

## Contributing

We welcome contributions to expand the analysis or improve visualizations. Please submit a pull request or open an issue for suggestions. 

--- 
