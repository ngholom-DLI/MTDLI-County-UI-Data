# MTDLI-County-UI-Data
The data in this repository contains the total number of claimants for Montana counties by the week end date for which the claimant experienced unemployment. For example, a claimant may file a claim on December 3rd, 2020, for weeks in October ending in on the 10th, 17th, and 24th. The person is counted across the weeks they were unemployed in October and are not added to October's weekly claimants until they file in December. Past dates, therefore, can have an increase in claimants as more claimants are added. However, a majority of claimants file claims for a given week within a couple of weeks, so the past claimant counts do not change that significantly.

The variables are as follows:

wk_end - the week end date that the claimant may have experienced unemployment

CountyName - the claimant's county of residence

res_county - the county code of the claimant's residence

People - number of claimants of all types, which includes initial claims, continued claims, and pua claims

IPeople - number of claimants filing a PUA or regular UI claim for the first week

amt_benefits - benefits paid in that week according to the benefit amounts on file. This can differ from benefits paid published by the UI division for a few reasons. The data we use is a snapshot and whether payments are on hold for a particular account can change between the time the snapshot of data is saved and the time payments are processed. It can also differ because the benefit amounts are being reported by the week end date for which they are filed and not by the date for which they are paid. For example, a claimant filing in December, who filed for weeks of unemployment that occurred in October would receive the payments in December, while process would count the benefits as having occurred in October.
