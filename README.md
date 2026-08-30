# HealthConnect Clinic- No-Show Patterns
A data analytics project focused on understanding appointment attendance and no-show patterns at HealthConnect Clinic.

### Project Overview

HealthConnect Clinic is a fictional healthcare provider. This project focuses on using data analytics to understand appointment attendance and identify patterns associated with missed appointments.
This repository will develop across multiple stages.

Week 4 focused on understanding the business problem, reviewing the available data and Data Dictionary, assessing data quality, identifying relevant variables, and defining the questions and KPIs that will guide further analysis.

### Data Quality Assessment

Initial checks identified:

- No duplicate `appointment_id` records
- Approximately 1% missing values in `distance_to_clinic_km`
- Approximately 1% missing values in `waiting_time_minutes`
- Data types and categorical fields reviewed against the Data Dictionary

### Key Variables

Variables identified for further analysis include:

- Appointment type, day and time
- Age and gender
- Booking lead time
- Previous no-shows
- Reminder status and channel
- Distance to clinic
- Waiting time
- Appointment outcome

### Business Questions

The analysis will explore:

- What proportion of appointments are no-shows?
- Which appointment factors are associated with no-shows?
- Is previous no-show behaviour associated with future no-shows?
- Is reminder engagement associated with attendance?
- Does booking lead time relate to no-show behaviour?

## Proposed KPIs

The following KPIs were identified as potentially relevant to the business questions:

| KPI | Business Question |

|---|---|

| **No-Show Rate** | What proportion of appointments are no-shows? |

| **Attendance Rate** | What proportion of appointments are attended? |

| **Cancellation Rate** | How many scheduled appointments are cancelled? |

| **Reminder-Associated Attendance Rate** | Is reminder engagement associated with attendance? |

| **Repeat No-Show Rate** | Are repeat no-shows common? |

At this stage, the KPIs were identified and their relevance considered. They were not yet calculated or visualised.

---

## Initial Analysis Approach

The proposed analytical approach for the next stage is to:
1. Review and prepare the dataset.
2. Address identified data-quality issues.
3. Examine appointment volumes and appointment outcomes.
4. Investigate no-show patterns across relevant variables.
5. Calculate the selected KPIs.
6. Compare patterns across relevant appointment and patient groups.
7. Interpret the findings and identify meaningful business insights.### Proposed KPIs

### Week 4 Outcome

Week 4 established the foundation for the HealthConnect Data Analytics project through data understanding, initial quality assessment, variable identification, business-question development and KPI planning.

**Tools:** Microsoft Excel | Power Query | GitHub
