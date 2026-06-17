READ_ME DOCUMENT    : SCHOOL_HEALTH_360


Overview
School Health360 is a digital school health screening and monitoring platform designed to support the early identification of physical and mental health concerns among school-going children.
The application integrates multiple validated screening components into a single digital workflow, enabling standardized assessment, automated recommendations, health record generation, and referral support within school settings.
The platform is particularly designed for resource-constrained educational environments where routine school health services may be limited.

Problem Statement
Many physical, behavioral, emotional, and developmental concerns among school children remain unidentified until they begin to affect academic performance, attendance, wellbeing, and participation in school activities.
Traditional paper-based screening methods are often fragmented, difficult to monitor longitudinally, and challenging to scale.
School Health360 addresses this gap by providing a structured digital solution for routine school health screening and monitoring.

Project Aim
To develop a digital School Health Screening and Monitoring Application that supports routine health assessment, documentation, referral, and follow-up of school-going children.

Key Features
Mental Health Screening
Uses the Strengths and Difficulties Questionnaire – Teacher Version (SDQ-T) to assess:
•	Emotional symptoms
•	Conduct problems
•	Hyperactivity/Inattention
•	Peer relationship problems
•	Prosocial behavior
The system automatically:
•	Calculates SDQ scores
•	Classifies risk levels
•	Generates recommendations
•	Stores results for summary reporting

Anthropometric Assessment
The platform performs:
•	Height assessment
•	Weight assessment
•	BMI calculation
•	BMI classification
BMI categories are interpreted using age- and sex-specific WHO growth standards.
Automated recommendations are generated for:
•	Normal weight
•	Underweight
•	Overweight
•	Obesity

Blood Pressure Screening
The application screens pediatric blood pressure using:
•	Age
•	Sex
•	Systolic blood pressure
•	Diastolic blood pressure
Interpretation is based on pediatric screening thresholds and automatically generates monitoring or referral recommendations.

Vision Screening
Visual Acuity Assessment
Screens visual acuity using standard school screening criteria.
Results include:
•	Normal Vision
•	Vision Referral Recommended
Color Vision Screening
Supports color vision assessment and documentation.

Physical Health Screening
The platform includes structured screening for:
Hair Hygiene
•	Healthy Hair and Scalp
•	Dandruff
•	Lice/Nits
•	Other abnormalities
Oral Health
•	Teeth condition
•	Gum health
•	Oral hygiene
Skin Health
•	Healthy skin
•	Rash
•	Redness
•	Dryness
•	Wounds
•	Other abnormalities
Nail Health
•	Nail hygiene
•	Nail abnormalities
•	Signs requiring further assessment

Automated Recommendations
Each screening module automatically generates evidence-informed recommendations based on the screening findings.
Examples include:
•	Routine monitoring
•	Hygiene improvement
•	Nutritional assessment
•	Lifestyle counselling
•	Vision referral
•	Dental referral
•	Psychological referral
•	Clinical assessment recommendations

Overall Health Status Dashboard
After all screening modules are completed, the application generates an overall health status dashboard using a traffic-light approach:
•	🟢 Normal
•	🟡 Monitor / Mild Concern
•	🔴 Referral or Significant Concern
The dashboard provides a quick visual summary of all completed screening domains.

Student Health Summary Report
The application automatically compiles a consolidated report including:
Mental Health Summary
•	SDQ Total Score
•	SDQ Risk Category
Physical Health Summary
•	BMI Status
•	Blood Pressure Status
•	Vision Status
•	Color Vision Status
•	Hair Health Status
•	Oral Health Status
•	Skin Health Status
•	Nail Health Status
Recommendations
All module-specific recommendations are combined into a single report section.
Overall Recommendation
An integrated summary recommendation is generated based on the screening findings.

Technology Stack
•	Python
•	Streamlit
•	Pandas
•	NumPy
•	Matplotlib

Reference Standards
Domain	Reference Standard
Mental Health	Strengths and Difficulties Questionnaire (SDQ-T)
Anthropometry	WHO 2007 Growth Reference
Blood Pressure	AAP 2017 Pediatric Guideline
Physical Health Screening	Structured School Health Assessment Checklist

Expected Impact
School Health360 supports:
•	Early identification of health concerns
•	Standardized school health screening
•	Improved referral pathways
•	Longitudinal health monitoring
•	Data-driven school health planning
•	Scalable implementation in low-resource settings

Future Enhancements
Planned developments include:
•	PDF report generation
•	Student health record database
•	Longitudinal trend tracking
•	Follow-up monitoring system
•	School-level analytics dashboard
•	Population health surveillance reporting
•	AI-assisted integrated screening summaries

Developer
School Health360 was developed as a digital school health screening and monitoring solution to strengthen early detection and follow-up of physical and mental health concerns among school children.

