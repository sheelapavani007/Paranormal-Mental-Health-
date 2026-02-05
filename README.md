# Paranormal-Mental-Health-
# The Paranormal-Mental Health Nexus
### Investigating Supernatural Phenomena as a Proxy for Population Distress

## 📌 Project Overview
Why do we see ghosts? This project explores the hypothesis that **paranormal sightings are not random events, but "idioms of distress"** triggered by physiological and psychological factors. 

By analyzing search engine behavior (Temporal Analysis) and reported sighting density (Geospatial Analysis), this study identifies a strong correlation between sleep disturbances, regional stress, and supernatural claims.

## 🚀 Key Insights
* **The "Shadow Person" Link:** Found a moderate correlation ($r = 0.56$) between Insomnia and "Shadow People" searches, suggesting a direct link between sleep deprivation and entity-based hallucinations.
* **Clinical Knowledge Gap:** Despite the medical link between sleep paralysis and hallucinations, the correlation between these terms was nearly zero ($r = 0.09$), proving that the public interprets these events through a supernatural lens rather than a medical one.
* **The Rust Belt Signal:** High-stress states (MI, OH, WV) show a significantly higher density of paranormal reports compared to lower-stress states, even when adjusted for population.
* **Trendy "Sensors":** Modern slang (e.g., "Crash Out") and niche media (Analog Horror) proved to be more sensitive sensors for mental health spikes than traditional clinical terms.

## 📊 Data & Methodology
### Phase 1: Temporal (Google Trends)
* **Keywords:** Clinical (Insomnia, Anxiety) vs. Paranormal (Shadow People, Skinwalkers).
* **Normalization:** All search data was scaled ($0$ to $1$) to compare low-volume niche terms with high-volume clinical terms.
* **Smoothing:** Applied a 7-day rolling average to filter noise from the data.

### Phase 2: Geospatial (Sighting Density)
* **Sources:** Haunted Places Index (10,000+ reports) & CDC Mental Health Distress Scores (2025/2026).
* **Metric:** Calculated **Ghost Density** (Reports per 1,000,000 residents) to find true hotspots independent of population size.

## 🛠️ Tech Stack
* **Language:** Python
* **Data Acquisition:** Pytrends API
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Plotly Express, Seaborn, Matplotlib

## 📈 Visualizations

*Figure 1: Scatter plot showing the upward trend between State Distress Scores and Ghost Sighting Density.*
<img width="1118" height="360" alt="image" src="https://github.com/user-attachments/assets/0f05ffee-038c-4439-a5d1-9520d27d8ab1" />

*Figure 2: Temporal sync between "Night Terrors" and "Analog Horror" consumption in late 2025.*
<img width="1209" height="609" alt="image" src="https://github.com/user-attachments/assets/fa6617e4-f585-4ba3-9106-50b76e9677c4" />

## 🧠 Scientific Discussion
The project utilizes **Agency Detection Theory** and **REM Intrusion** mechanics to explain the results. When the amygdala is hyper-active due to stress (Hypervigilance), the brain is prone to **Pareidolia**—misinterpreting random stimuli (shadows, creaks) as sentient entities.

