Medicare Cost Prediction

**Objective:**

Predict the submitted charged amount based on the HCPCS Description and additional attributes

**Data location** (Medicare National HCPCS Aggregate Summary Table CY2015)

[https://data.cms.gov/Medicare-Physician-Supplier/Medicare-National-HCPCS-Aggregate-Summary-Table-CY/uqfq-w9cg](https://data.cms.gov/Medicare-Physician-Supplier/Medicare-National-HCPCS-Aggregate-Summary-Table-CY/uqfq-w9cg)

**Data description**

The Physician and Other Supplier Public Use File (Physician and Other Supplier PUF) provides information on services and procedures provided to Medicare beneficiaries by physicians and other healthcare professionals. The Physician and Other Supplier PUF contains information on utilization, payment (allowed amount and Medicare payment), and submitted charges organized by National Provider Identifier (NPI), Healthcare Common Procedure Coding System (HCPCS) code, and place of service. The data in the Physician and Other Supplier PUF covers calendar year 2015 and contains 100% final-action physician/supplier Part B non-institutional line items for the Medicare fee-for-service population.

| Column name | Description | Type |
| --- | --- | --- |
| **HCPCS Code** | HCPCS code used to identify for the specific medical service furnished by the provider. HCPCS codes include two levels. Level I codes are the Current Procedural Terminology (CPT) codes that are maintained by the American Medical Association and Level II codes are created by CMS to identify products, supplies and services not covered by the CPT codes (such as ambulance services). CPT codes, descriptions and other data only are copyright 2014 American Medical Association. All rights reserved. CPT is a registered trademark of the American Medical Association (AMA). Please review the complete CMS AMA CPT License agreement which is presented to users when accessing the data. For additional information on HCPCS codes, visit [http://www.cms.gov/Medicare/Coding/MedHCPCSGenInfo/index.html](http://www.cms.gov/Medicare/Coding/MedHCPCSGenInfo/index.html). | Plain Text |
| **HCPCS Description** | Description of the HCPCS code for the specific medical service furnished by the provider. HCPCS descriptions associated with CPT codes are consumer friendly descriptions provided by the AMA. All other descriptions are CMS Level II descriptions provided in long form. Due to variable length restrictions, the CMS Level II descriptions have been truncated to 256 bytes. As a result, the same HCPCS description can be associated with more than one HCPCS code. For complete CMS Level II descriptions, visit [http://www.cms.gov/Medicare/Coding/HCPCSReleaseCodeSets/Alpha-Numeric-HCPCS.html](http://www.cms.gov/Medicare/Coding/HCPCSReleaseCodeSets/Alpha-Numeric-HCPCS.html). | Plain Text |
| **HCPCS Drug Indicator** | Identifies whether the HCPCS code for the specific service furnished by the provider is a HCPCS listed on the Medicare Part B Drug Average Sales Price (ASP) Files. For additional information on the ASP drug pricing, visit [http://www.cms.gov/Medicare/Medicare-Fee-for-Service-Part-B-Drugs/McrPartBDrugAvgSalesPrice/index.html](http://www.cms.gov/Medicare/Medicare-Fee-for-Service-Part-B-Drugs/McrPartBDrugAvgSalesPrice/index.html). | Plain Text |
| **Place of Service** | Identifies whether the place of service submitted on the claims is a facility (value of &#39;F&#39;) or non-facility (value of &#39;O&#39;). Non-facility is generally an office setting; however other entities are included in non-facility. | Plain Text |
| **Number of Providers** | Number of providers within HCPCS code and place of service. | Number |
| **Number of Services** | Number of services provided; note that the metrics used to count the number provided can vary from service to service. | Number |
| **Number of Unique Beneficiary/Provider Interactions** | Number of unique beneficiary/provider interactions (e.g., if a single beneficiary sees two different providers for a given HCPCS code this value would be two). | Number |
| **Number of Distinct Medicare Beneficiary/Per Day Services** | Number of distinct Medicare beneficiary/per day services. Since a given beneficiary may receive multiple services of the same type (e.g., single vs. multiple cardiac stents) on a single day, this metric removes double-counting from the line service count to identify whether a unique service occurred. | Number |
| **Average Submitted Charge Amount** | Average of the charges that providers submit for the service. | Number |
| **Average Medicare Allowed Amount** | Average of the Medicare allowed amount for the service. Medicare allowed amounts includes the amount Medicare pays, the deductible and coinsurance amounts that the beneficiary is responsible for paying, and any amounts that a third party is responsible for paying. | Number |
| **Average Medicare Payment Amount** | Average amount that Medicare paid after deductible and coinsurance amounts have been deducted for the line item service. | Number |
| **Average Medicare Standardized Payment Amount** | Average amount that Medicare paid after beneficiary deductible and coinsurance amounts have been deducted for the line item service and after standardization of the Medicare payment has been applied. Standardization removes geographic differences in payment rates for individual services, such as those that account for local wages or input prices and makes Medicare payments across geographic areas comparable, so that differences reflect variation in factors such as physicians&#39; practice patterns and beneficiaries&#39; ability and willingness to obtain care. Additional information on the standardization of Medicare payments can be found in the &quot;Geographic Variation Public Use File: Technical Supplement on Standardization&quot; available within the &quot;Related Links&quot; section of the following web page: [https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Geographic-Variation/GV\_PUF.html](https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Geographic-Variation/GV_PUF.html). Note: This variable is available starting with the calendar year 2014 data. | Number |





[https://colab.research.google.com/drive/1zgD6tY2RBzr\_gOVzIwPLQbByn1gg5y8B#scrollTo=ptsaA5QKn1HB](https://colab.research.google.com/drive/1zgD6tY2RBzr_gOVzIwPLQbByn1gg5y8B#scrollTo=ptsaA5QKn1HB)
