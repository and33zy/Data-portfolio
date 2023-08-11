# Data-Analysis-Portfolio
## Dental-Insurance-Fee-Analysis-and-Negotiations

This is a project I did while working in a dental office where I compare our current rates with offers from insurance companies to decide whether staying in network is still profitable, or dropping them so that a third party insurance company can pay under their rates. 

A direct contract is the easiest and fastest way a dentist can get into network with an insurance company and start working as a network provider. A direct contract generally includes a lower paid fee schedule that many budget insurance plans offer their patients.

### Purpose: 
- Gather and organize data from current insurance rates to other insurance companies and their rates
- Generate reports to compare fee schedules and offer insights to make better informed decisions when negotiating insurance rates

### Structure:
#### 1. [Insurance-utilization-report](https://github.com/and33zy/Insurance-utilization-report)
  * This report was generated by using SQL on OpenDental, a dental office management program, to compile data to showcase how much revenue has been generated from individual insurance carrier.
  * Depicts how many claims, estimated payouts, and actual payouts from all insurance carriers used in the dental office.
    * Can show discrepencies when quoting treatment plans to patients
  * Highlights the most common insurance carrier that patients use.
  * This report is significant because it helps me and our dentist figure out which insurance carrier we can decide on terminating our contract with and which ones we are okay to stay in network to negotiate or leave alone.
  * Some insurance carriers are non-negotiable, if those are on the lower paying carriers, we can use this report to see if we have a lot of patients using that specific carrier. 

#### 2. [Procedures-by-Procedure-Code](https://github.com/and33zy/Procedures-by-Procedure-Code.git)
  * A report generated through OpenDental, that tracks all known procedure codes used in our office.
  * Has a brief description of each procedure code used, the number of times a procedure code has been used between 01-Jan-2022 to 31-Dec-2022, how much revenue generated by each code and average fees based on all insurance company's fee schedule.

#### 3. [Cigna-Analysis-Report](https://github.com/and33zy/Cigna-Analysis-Report)
  * A comparison report to show % increase or decrease in fees with several offers given by Cigna.
  * Acess to original pdf files showing fee schedules from first and second offers.
  * Converted pdf to excel sheets
  * Shows differences in rates between current office fees, cigna offers, and fee schedule currently enrolled in with Careington Platinum schedule. 
