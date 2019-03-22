### the-threat-within-data

## ABOUT THIS DATA

This data was published on March 23, 2019, as part of [“The Threat Within,”](https://theintercept.com/series/the-threat-within) a series by [The Intercept](https://theintercept.com/) about federal domestic terrorism prosecutions.

Contributing writer [Trevor Aaronson](https://theintercept.com/staff/trevor-aaronson/) and researcher [Margot Williams](https://theintercept.com/staff/margotwilliams/) examined hundreds of prosecutions to identify crimes that appear to have met the Patriot Act definition of domestic terrorism — “acts dangerous to human life” intended to intimidate civilians or influence government in the service of a domestic extremist ideology. A second analysis, of federal prosecutions of radical environmentalists and animal rights activists, included cases that were prosecuted under the Animal Enterprise Terrorism Act or its precursor, or described publicly by the Justice Department as domestic terrorism. The right-wing and eco data are available with this document on GitHub.

Each line of data in the right-wing and eco databases represents an individual defendant. If an individual defendant is in the data more than once, each line represents a unique case.

The right-wing data fields are:

```
BOP_Number          the defendant’s Bureau of Prisons number, if available
Last_Name           the defendant’s last name
Given_Names         the defendant’s given names
State               the state in which the defendant was charged in U.S.
                    District Court
District            the district in which the defendant was charged, if more
                    than one district in the state
Docket_Number       the docket number for the case
Charge_Year         the year in which the defendant was charged
Charges             types of charges filed, according to attached legend,
                    including charges dismissed, dropped and pending
Terrorism_Charge    whether the defendant was charged under a Category I
                    terrorism statute, as defined here:
                    http://bit.ly/doj_code_list
Disposition         current status of the case
Sentence_in_Months  the sentence imposed on the defendant
Alleged_Ideology    the defendant’s alleged extremist ideology or ideologies
Alleged_Affiliation the extremist group or groups with which the defendant
                    was allegedly affiliated
BOP_releaseCode     the defendant’s current Bureau of Prisons status; R is
                    released and D is deceased
BOP_race            the defendant’s race, according to the Bureau of Prisons
BOP_projRelDate     the defendant’s projected release date, according to the
                    Bureau of Prisons as of March 23, 2019
BOP_age             the defendant’s age, according to the Bureau of Prisons
                    as of March 23, 2019
BOP_sex             the defendant’s gender, according to the Bureau of Prisons
BOP_actRelDate      the defendant’s actual release date, according to the
                    Bureau of Prisons
```

One defendant in the right-wing data is an outlier. Gale William Nettles, an anti-government extremist, was prosecuted on charges related to an alleged domestic terrorism plot and an alleged international terrorism plot. The right-wing data includes only the charges related to the domestic terrorism case.

The eco data fields are:

```
BOP_Number          the defendant’s Bureau of Prisons number, if available
Last_Name           the defendant’s last name
Given_Names         the defendant’s given names
State               the state in which the defendant was charged in U.S.
                    District Court
District            the district in which the defendant was charged, if more
                    than one district in the state
Docket_Number       the docket number for the case
Charge_Date         the date on which the defendant was charged, generally
                    designated as the date on which prosecutors filed a
                    criminal complaint or indictment
Charges             types of charges filed, according to attached legend,
                    including charges dismissed, dropped and pending
Disposition         current status of the case
Disposition_Date    the date on which a defendant was convicted, acquitted,
                    or had charges dismissed or dropped
Sentence_in_Months  the sentence imposed on the defendant
```
