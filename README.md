# LITA_Project/ AVA_project

### Project title: Test case summary report
---
### Book a Trainer Report
#### Objective
To verify the functionality of the Book-a-Trainer feature, ensuring that users can successfully book a trainer for a specific date and time, and that system correctly processes and confirms the booking. [Download here](https://www.micrososft.com)
- Test case ID: BT_001
- Test created By: Oluwaseun, Chukwuemeka, and Edmond.
- Test creation Date: 28-05-2024
- Test case priority: High

  ### Test case summary
  The Book-a-Trainer feature allows users to select a trainer, choose a date and time, and confirm booking. This test case validates that the feature works as expected.

  #### Preconditions:
1.	User is registered and logged into the system
2. 	Trainers are available in the system with their schedules updated.
3.	The booking system is functional and accessible
4.	Payment methods are configured and available.

### Status: Completed
This structured test case report ensures that the ‘Book-a-Trainer’ feature is thoroughly tested for functionality, usability, and accuracy, providing a clear frame work for validation.

### Data Analysis
``` SQL
select companies.state_code,
     COUNT(DISTINCT companies.permalink) AS distinct_companies,
        COUNT(DISTINCT acquisitions.company_permalink) AS distinct_acquisitions
        FROM tutorial.crunchbase_companies companies
  LEFT JOIN tutorial.crunchbase_acquisitions acquisitions
  ON companies.permalink = acquisitions.company_permalink
  GROUP BY 1
  ORDER BY 3
```

