# ComputeFest 2019: Interpretability + Fairness Workshop

## Instructions

Install with the following steps:

```
$ git clone https://github.com/pblankley/interp-workshop-2019.git
$ cd interp-workshop-2019
$ ./make_env.sh
```

## Data

url	URL for the LC page with listing data.
verification_status	Indicates if income was verified by LC, not verified, or if the income source was verified
verified_status_joint	Indicates if the co-borrowers' joint income was verified by LC, not verified, or if the income source was verified
zip_code	The first 3 numbers of the zip code provided by the borrower in the loan application.
revol_bal_joint 	 Sum of revolving credit balance of the co-borrowers, net of duplicate balances
sec_app_fico_range_low 	 FICO range (high) for the secondary applicant
sec_app_fico_range_high 	 FICO range (low) for the secondary applicant
sec_app_earliest_cr_line 	 Earliest credit line at time of application for the secondary applicant
sec_app_inq_last_6mths 	 Credit inquiries in the last 6 months at time of application for the secondary applicant
sec_app_mort_acc 	 Number of mortgage accounts at time of application for the secondary applicant
sec_app_open_acc 	 Number of open trades at time of application for the secondary applicant
sec_app_revol_util 	 Ratio of total current balance to high credit/credit limit for all revolving accounts
sec_app_open_act_il	 Number of currently active installment trades at time of application for the secondary applicant
sec_app_num_rev_accts 	 Number of revolving accounts at time of application for the secondary applicant
sec_app_chargeoff_within_12_mths 	 Number of charge-offs within last 12 months at time of application for the secondary applicant
sec_app_collections_12_mths_ex_med 	 Number of collections within last 12 months excluding medical collections at time of application for the secondary applicant
sec_app_mths_since_last_major_derog 	 Months since most recent 90-day or worse rating at time of application for the secondary applicant
hardship_flag	Flags whether or not the borrower is on a hardship plan
hardship_type	Describes the hardship plan offering
hardship_reason	Describes the reason the hardship plan was offered
hardship_status	Describes if the hardship plan is active, pending, canceled, completed, or broken
deferral_term	Amount of months that the borrower is expected to pay less than the contractual monthly payment amount due to a hardship plan
hardship_amount	The interest payment that the borrower has committed to make each month while they are on a hardship plan
hardship_start_date	The start date of the hardship plan period
hardship_end_date	The end date of the hardship plan period
payment_plan_start_date	The day the first hardship plan payment is due. For example, if a borrower has a hardship plan period of 3 months, the start date is the start of the three-month period in which the borrower is allowed to make interest-only payments.
hardship_length	The number of months the borrower will make smaller payments than normally obligated due to a hardship plan
hardship_dpd	Account days past due as of the hardship plan start date
hardship_loan_status	Loan Status as of the hardship plan start date
orig_projected_additional_accrued_interest	The original projected additional interest amount that will accrue for the given hardship payment plan as of the Hardship Start Date. This field will be null if the borrower has broken their hardship payment plan.
hardship_payoff_balance_amount	The payoff balance amount as of the hardship plan start date
hardship_last_payment_amount	The last payment amount as of the hardship plan start date
disbursement_method	The method by which the borrower receives their loan. Possible values are: CASH, DIRECT_PAY
debt_settlement_flag	Flags whether or not the borrower, who has charged-off, is working with a debt-settlement company.
debt_settlement_flag_date	The most recent date that the Debt_Settlement_Flag has been set
settlement_status	The status of the borrower’s settlement plan. Possible values are: COMPLETE, ACTIVE, BROKEN, CANCELLED, DENIED, DRAFT
settlement_date	The date that the borrower agrees to the settlement plan
settlement_amount	The loan amount that the borrower has agreed to settle for
settlement_percentage	The settlement amount as a percentage of the payoff balance amount on the loan
settlement_term	The number of months that the borrower will be on the settlement plan
