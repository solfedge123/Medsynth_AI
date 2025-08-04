#  MedSynth  Privacy-Preserving Synthetic EHR Generator

A privacy-aware synthetic Electronic Health Record (EHR) generator with built-in **Membership Inference Defense Metrics**.

Built for healthcare AI teams, researchers, and privacy engineers who need realistic patient data — without exposing real patient records.

---

##  Features

 **Generate Synthetic EHR Data**
- Realistic fields: age, diagnosis, medication, readmission, visit duration
- Statistically sampled from real-world distributions

 **Privacy Defense Metrics**
- Detects **Membership Inference Risk**
- Uses a shadow classifier to test if synthetic data leaks real patient info
- Flags high-risk generation patterns

**Data Utility Preservation**
- Measures RMSE between real and synthetic distributions
- Ensures synthetic data remains useful for downstream ML

 **Exportable Outputs**
- Download as CSV or JSON
- Ready for use
