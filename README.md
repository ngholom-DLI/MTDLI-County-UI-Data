# MTDLI-County-UI-Data
This repository contains data on the number of claimants for Montana counties by the week end date for which the claimant was unemployed. For example, a claimant may file a claim in December for the weeks they were unemployed in November. The person is counted for the weeks in November, but they are not added to weekly claimant counts until they file in December. Past dates, therefore, can have an increases in claimants even after a few months have passed. A majority of claimants file initial claims not long after they become unemployed, so past claimant counts do not increase that significantly.

The variables are as follows:

wk_end - the week end date that the claimant may have experienced unemployment

CountyName - the claimant's county of residence

res_county - the county code of the claimant's residence

People - number of claimants of all types, which includes initial claims, continued claims, and pua claims

IPeople - number of claimants filing a PUA or regular UI claim for the first week

amt_benefits - total benefit amount by the week the claimant's unemployment occurred. This is different from when the claim is filed or when the payment is processed. For example, a claimant filing a claim in January for weeks in which they were unemployed in December may receive payments in January or after January depending on how quickly the claim can be verified. 
