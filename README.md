# Comorbidities_T1DM
Clustering Diabetes Type 1 Patients based on their Comorbidities and Patient Profile

- Subjects.ipnyb first extracts all Type 1 diabetes patients and then extarcts comorbidities of each patient and gorups these comorbidities, then the dataframe is saved as 'Comorb.csv', which is used in Clustering.

- Age_Gender extracts the gender and computes the age of the patient on discharge day based on the text data in the discharge summaries, the outcome is saved as 'typ1.csv'.

- Subjects_with_age merges both datasets and preprocesses the data for the final cluster computation, this file requires the 'Comorb.csv' files and the 'typ1.csv', preprocessed data is saved as 'unique_subject_ids_df.csv'.

- Clustering is the last used file which computes the clusters with the preprocessed data, this file is processed last since it requires the 'unique_subject_ids_df.csv' file.
