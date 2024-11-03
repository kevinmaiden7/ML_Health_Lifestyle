# [Sustainable Lifestyle Rating Dataset](https://www.kaggle.com/datasets/naveennas/sustainable-lifestyle-rating-dataset)

This dataset offers a holistic view of sustainable living by examining various lifestyle choices and their environmental impact. It encompasses demographic information (age, location, gender), dietary preferences (diet type, local food frequency), transportation habits, energy sources, housing characteristics (home type, size), consumption patterns (clothing frequency, use of sustainable brands), environmental awareness, community engagement, resource consumption (electricity, water), plastic usage, waste disposal methods, and physical activity levels. Each participant's lifestyle is then evaluated and assigned a sustainability rating. The dataset includes the following columns:

1. ParticipantID: A unique identifier for each participant.
2. Age: The age of the participant.
3. Location: The location of the participant (Urban, Suburban, or Rural).
4. DietType: The dietary preference of the participant (Mostly Plant-Based, Balanced, or 5. Mostly Animal-Based).
5. LocalFoodFrequency: How often the participant consumes locally sourced food (Often, Sometimes, or Rarely).
6. TransportationMode: The primary mode of transportation used by the participant (Bike, Public Transit, Car, or Walk).
7. EnergySource: The primary source of energy used in the participant's home (Renewable, Mixed, or Non-Renewable).
8. HomeType: The type of dwelling the participant lives in (Apartment or House).
9. HomeSize: The size of the participant's home in square feet.
10. ClothingFrequency: How often the participant purchases new clothing (Often, Sometimes, or Rarely).
11. SustainableBrands: Whether the participant prioritizes purchasing from sustainable brands (True or False).
12. EnvironmentalAwareness: A rating (1-5) indicating the participant's level of environmental awareness.
13. CommunityInvolvement: The participant's level of involvement in their community (High, Moderate, or Low).
14. MonthlyElectricityConsumption: The participant's average monthly electricity consumption in kilowatt-hours.
15. MonthlyWaterConsumption: The participant's average monthly water consumption in gallons.
16. Gender: The gender of the participant (Male, Female, or Non-Binary).
17. UsingPlasticProducts: How often the participant uses plastic products (Often, Sometimes, or Rarely).
18. DisposalMethods: The primary method the participant uses to dispose of waste (Composting, Recycling, Landfill, or Combination).
19. PhysicalActivities: The participant's level of physical activity (High, Moderate, or Low).
20. Rating: The overall sustainability rating assigned to the participant (1-5).

This data is created by taking reference of various surveys, articles and research papers.

# [Healthcare Data](https://www.kaggle.com/datasets/vibhaburman/healthcare-data)

## Chronic Disease Management Patient Data

**Description:** This dataset provides detailed information on patients suffering from chronic diseases, including their demographic details, medical history, and management strategies. It is designed to aid in the analysis of chronic disease management and preventive care.

**Content:**

patient_id: Unique identifier for each patient.
age: Age of the patient.
gender: Gender of the patient (M for Male, F for Female).
chronic_disease: Chronic disease diagnosed in the patient (e.g., Diabetes, Osteoarthritis, Asthma).
diagnosis_date: Date when the chronic disease was diagnosed.
current_medications: Medications currently prescribed to the patient (e.g., Metformin, Insulin).
last_checkup_date: Date of the last medical checkup.
blood_pressure: Latest recorded blood pressure of the patient (e.g., 121/80).
blood_sugar_levels: Latest recorded blood sugar levels (e.g., 160 mg/dL), or 'N/A' if not applicable.
lifestyle_interventions: Lifestyle changes recommended for managing the disease (e.g., Diet, Exercise).
education_level: Education level of the patient (e.g., Low, Medium, High).
preventive_measures: Preventive measures taken by the patient (e.g., Annual Screening, Routine Checkups).
quality_of_life_score: Score reflecting the patient’s quality of life, typically on a scale from 0 to 100.
follow_up_schedule: Date scheduled for the next follow-up appointment.
emp_id: Employee ID of the healthcare provider managing the patient (corresponds to the healthcare provider in the employee dataset).
healthcare_provider: Name of the healthcare provider assigned to the patient.
Purpose:
This dataset is intended to support research and analysis on chronic disease management and prevention strategies. It provides insights into how different factors, including medications, lifestyle interventions, and preventive measures, impact patient outcomes and quality of life.

**Applications:**

Chronic Disease Management: Analyzing how various interventions and treatments influence the management of chronic diseases.
Patient Care Analysis: Understanding the role of healthcare providers and the impact of their involvement on patient health outcomes.
Quality of Life Assessment: Evaluating how different chronic conditions and treatments affect patients’ quality of life.
Healthcare Provider Performance: Investigating the effectiveness of healthcare providers in managing chronic diseases and patient care.

# Run MLflow Server

```bat
mlflow server
```