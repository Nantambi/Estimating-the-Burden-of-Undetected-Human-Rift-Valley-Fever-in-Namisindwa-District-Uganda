# Estimating-the-Burden-of-Undetected-Human-Rift-Valley-Fever-in-Namisindwa-District-Uganda
This project uses a simulation model to estimate how many human Rift Valley Fever cases are missed by routine surveillance in Namisindwa, Uganda. It focus on high-risk occupational groups that is abattoir workers. Because most RVF infections are mild,asymptomatic or misdiagnosed,routine surveillance systems detect only a small
fraction of cases. This project quantifies that hidden burden and evaluates how improved surveillance could reduce under-reporting.

This model integrates livestock-to-human spillover seasonal transmission,waning immunity and disease-related mortality,making it suitable for studying zoonotic disease dynamics in high risk settings.

*Objectives*
1.  To develop and parameterize an SEIR model for abattoir staff in Namisindwa District, incorporating the importation of livestock across the Kenya border.
2.	To compare the burden of undetected Rift Valley Fever cases under two surveillance scenarios: baseline diagnostics versus improved diagnostics with active screening.
3.	To compute endemic equilibrium states and simulate epidemic trajectories over 50 years.


Model Structure
The model is a deterministic SEIR compartmental model:
S-Suspetible
E-Exposed(infected but not yet infectious)
I-Infectious
R-Recovered with warning immunity

Human infections occur through a spillover force of infection from infected livestock,with seasonal variation that decays overtime. A surveillance module removes a fraction of infectious individuals based on screening coverage and test sensitivity.

Surveillance Scenarios
Two scenarios are simulated:
Scenario                    Sensitivity             Screening
Status Quo                      74%                     0%
Improved Surveillance           90%                     80%
These allow estimation of how many infections remain missed under current conditions and how many could be detected with better surveillance

*KEY OUTPUTS
1.Spillover reproductive number (R0)
2.Endemic equilibrium of RVF in humans
3.Long term infection trajectories
4.Impact of surveillance on detected vs undetected cases

This project is implemented using R software.

PUBLIC HEALTH RELEVANCE
This work supports One Health surveillance,helping authorities understand how much RVF is being missed and how improved screening can reduce disease burden in high risk Ugandan communities.

Author:_Nantambi Faith Gloria_    

Research Focus: _Zoonotic disease modelling,surveillance gaps and public health preparedness in Uganda.
