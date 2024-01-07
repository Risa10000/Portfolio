# Turnover analysis and prediction model project

### Project details

- Scenario
    - The HR department of consulting company A aims to improve employee turnover rates.
- Project Goal
    - Providing data-driving suggestions by:
        - Identifying key factors driving employee turnover. 
        - building a predictive model determining whether an employee will leave the company.
- Project Execution
    - Following the PACE strategy, consisting of the Plan, Analyze, Construct, and Execute phases.
- Analytical Approach:
    - Statistical analysis
    - Building three predictive models:
        - Logistic Regression
        - Random Forest with GridSearch
        - XGBoost with GridSearch
            - in this case, the Random Forest model scored the highest performance
　　　　　　　　![results](https://github.com/risa-001/portfolio/assets/148436136/b93c8764-23e9-4032-a43a-6d568014a009)
   
### Insights/Next steps

- Employees leaving the company fall into two categories.
- One group spent a lot of time working on multiple projects. Despite receiving positive evaluations, they were not promoted, and satisfaction levels were lower.
    - Losing such hardworking employees, who deliver excellent work and receive high evaluations, is a significant setback for the company.
    - Recommendations to retain these valuable employees: 
        - Monitor and regulate their working hours and project load to prevent overexertion.
        - Implement incentives or rewards for high-performing employees.
- The second group comprises individuals with shorter working hours and lower performance evaluations.
    - they could need help staying motivated or finishing tasks. HR or managers could provide consultations to address their concerns.
- There is no difference in the turnover rates between departments. Addressing this at the company level presents a notable opportunity for improvement, mainly focusing on employees who have worked for 3 to 6 years, as the length of service is also a turnover factor.

![fi](https://github.com/risa-001/portfolio/assets/148436136/8989d026-f625-41c7-924b-8332e92a682d)

- The results of statistical analysis and Random model align. The RF model predicts a 95% F1 score, demonstrating its effectiveness in aiding the HR process.

![cm](https://github.com/risa-001/portfolio/assets/148436136/2560f233-d788-4fbd-8d95-edb8da758628)

### Main coding file

[jupyter notebook](Prediction_of_turnover.ipynb)


Originally a capstone project from the Google Advanced Data Analytics Professional Certificate program, this is Risa Shimowada's portfolio project.

[Google Advanced Data Analytics Professional Certificate program](https://www.coursera.org/professional-certificates/google-advanced-data-analytics?utm_medium=sem&utm_source=gg&utm_campaign=B2C_EMEA__coursera_FTCOF_career-academy_pmax-multiple-audiences-country-multi&campaignid=20858198824&adgroupid=&device=c&keyword=&matchtype=&network=x&devicemodel=&adposition=&creativeid=&hide_mobile_promo&gclid=Cj0KCQiAkKqsBhC3ARIsAEEjuJg0i1r3Auo6PgTjurVDXqunwTCtysfDfCEp7MwhFeo8xQ0z4w-EZlUaAjqXEALw_wcB)






