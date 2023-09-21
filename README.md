# EDA-on-Odom-data in R
A much-cited 2012 psychology paper claimed that asking people to sign a statement of honesty before providing information, rather than afterwards, could strongly affect behavior. One piece of evidence it gave was data from an experiment conducted by an auto insurance company. According to the author, an insurance company had baseline odometer readings of miles traveled (measured some time ago) by the primary car covered under 13,488 policies. Each of the policy holders was randomly assigned to one of two conditions: “sign at the top” or “sign at the bottom” and asked to report the current mileage of the car. The
hypothesis was that signing at the top would make customers more likely to tell the truth, so the “sign at the top” group would on average report more miles traveled than the “sign at the bottom” group. The response variable was the difference between self-reported miles and baseline miles. The author of that section of the paper found that this difference averaged 26,100 miles for the “sign at the top” group and 23,700 miles for the “sign at the bottom” group. A t-test gives a tiny P-value, so this data would be very strong evidence that signing at the top affects behavior. Unfortunately however, it has been recently (2021) claimed that the data was fraudulent.

The spreadsheet DrivingdataAll.xls contains the data set from the experiment. I have analyzed the first four columns in R and the data was proved to be fraudulent.
• OMR Version: “Sign Top” or “Sign Bottom”.
• Policy # (masked): an ID number from 1 to 13488.
• Odom Reading 1 (Previous): the baseline odometer reading for the primary car, in miles.
• Odom Reading 1 (Update): the self-reported odometer reading for the primary car, in miles.
