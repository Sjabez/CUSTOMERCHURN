<h1>NEO - CUSTOMER CHURN PROJECT</h1>


<h2>Description</h2>
A data-driven project for Neo, a telecom company experiencing high customer churn. The goal was to analyze customer behavior, identify key factors contributing to churn, and generate actionable insights to support retention strategies. By leveraging historical customer data, the project aimed to build predictive models and uncover trends that could help reduce customer loss and improve overall service offerings.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 

<h2>Program walk-through:</h2>

<p align="center">
Step 1: Performed key data extraction and filtering steps to derive meaningful subsets from the telecom churn dataset:

- Extracted the **5th column** and stored it in `customer_5`.
<img src="https://i.imgur.com/CLbhjZd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

- Extracted the **15th column** and stored it in `customer_15`: <br/>
<img src="https://i.imgur.com/Vyl4cB8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
- Filtered all **male senior citizens** with **Electronic Check** as their payment method; stored in `senior_male_electronic`.
Select the disk:  <br/>
<img src="https://i.imgur.com/j5ju9vU.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>

- Retrieved customers with **tenure > 70 months** or **monthly charges > $100**; stored in `customer_total_tenure`: 
<img src="https://i.imgur.com/iSClXlP.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>

- Extracted customers whose **contract is two years**, **payment method is Mailed Check**, and **Churn is ‘Yes’**; stored in `two_mail_yes`.
<img src="https://i.imgur.com/nrlO6Da.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Selected **333 random records** from the dataset and stored in `customer_333`.
<img src="https://i.imgur.com/D9twVBt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Computed and displayed the **count of different levels in the `Churn` column**
<img src="https://i.imgur.com/EoEvVHl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
