# Electoral Reforms on Media Access in Latin America

Welcome to the GitHub repository of the database "Electoral Reforms on Media Access in Latin America," maintained by members of the Political Reform Observatory in Latin America.

## Contents

- [Summary](#summary)
- [Description](#description)
- [Citation](#citation)

## Summary

The database contains information on regulations governing media access and election campaigns in 18 Latin American countries between 1981 and 2020. The review was carried out starting with the year of each country's transition to democracy, based on Alcántara; Páramo; Freidenberg and Déniz, 2006. In countries with gradual processes of political change, the year the third wave of democracy began in Latin America (Huntington, 1991) is used as the basis. The following table specifies, for each country, the initial (year zero) and final year of the information contained in the database.

Members of the Observatory of Political Reforms in Latin America collected and coded the information. The information collection managers are Flavia Freidenberg (Institute for Legal Research, UNAM) and Karina Cáceres (University of Salamanca). The coding managers are Mayte Sánchez Hernández (Faculty of Higher Studies Acatlán, UNAM) Carlos Guadarrama Cruz (Faculty of Higher Studies Acatlán, UNAM). 

## Description

The directory `./Data/` contains the file `./Data/DD_MediaAccess` where all relevant information regarding the database linked to the electoral reforms on media access in Latin America and its reforms is located. Specifically, the database consists of the following variables:

-   `country`: name of the country in which the reform to the electoral executive regime was implemented in Latin America.

-   `cowcode`: country code according to the coding of  “Correlates of War” https://correlatesofwar.org/data-sets/cow-country-codes.

-   `countrycode`: country abbreviation according to the three-letter ISO code
(e.g. ARG, MEX, SAL) http://utils.mucattu.com/iso_3166-1.html.

-   `reform_year`: calendar year corresponding to the reform of the electoral regime of the executive in each Latin American country between 1978-2021.

-   `consec_ctry_reform`: records the consecutive number of reforms to the executive electoral regime in each Latin American country. Example: Peru_1 Peru_2, Peru_3, Peru_4.

-   `propaganda_ban`: indicates whether or not the electoral reform bans the purchase of media advertising. Values: No [0]: the reform does not ban the purchase of media advertising. Yes [1]: The reform bans the purchase of media advertising.

-   `free_access`: indicates whether the reform establishes the free mode for media access. Values: No [0]: the reform does not establish the free mode for media access. Yes [1]:  the reform establishes the free mode for media access.

-   `time_distribution`: indicates the time distribution formula in the media. Values: Not applicable [0]: no media time distribution formula is mentioned. Equal [1]: the distribution of media time is based on principles of equality and fairness in the party competition. Random[2]: the distribution of media time is made on the basis of chance. Mixed [3]: the distribution of media time combines two or more formulas outlined in each country's legislation. Legislative [4]: the distribution of television time depends on the percentages of political party members in legislative bodies. Non-specific [99]: there is no information on funding for these activities.

-   `president_time_slot`: indicates the duration in days the amended legislation establishes for presidential election campaigns.

-   `legislative_time_slot`: indicates the duration in days the amended legislation establishes for legislative election campaigns.

-   `municipal_time_slot`: indicates the duration in days the amended legislation establishes for election campaigns at the municipal level.

-   `national_time_slot`: indicates the duration in days the amended legislation establishes for election campaigns at the national level.

-   `primaries_time_slot`: indicates the duration in days the amended legislation establishes for electoral campaigns for primary elections.

-   `electoral_ban_before`: indicates whether the reform regulates the election ban prior to election day. Values: No [0]: the reform does not regulate this issue. Yes [1]: the reform regulates the electoral ban prior to election day.

-   `electoral_ban_during`: indicates whether the reform regulates the election ban during election day. Values: No [0]: the reform does not regulate this issue. Yes [1]: the reform regulates the electoral ban during election day.

-   `electoral_ban_after`: indicates whether the reform regulates the election ban immediately after election day. Values: No [0]: the reform does not regulate anything on this matter. Yes [1]: the reform regulates the election ban after election day.

-   `ban_release_surveys_before`: indicates whether the electoral reform considers a ban on the release of election surveys prior to election day. Values: No [0]: the reform does not regulate this issue. Yes [1]: the reform bans the release of election surveys prior to election day. Not specific [99]: there is no information available on the ban on the release of surveys prior to election day.

-   `ban_release_surveys_during`: indicates whether the electoral reform considers a ban on the release of election surveys during election day. Values: No [0]: The reform does not regulate this issue. Yes [1]: the reform bans the release of election polls during election day. Not specific [99]: there is no information available on the ban of the release of surveys during election day.

-   `release_surveys_after`: indicates whether the electoral reform considers a ban on the release of election surveys prior to election day. Values: No [0]: the reform does not regulate this issue.
Yes [1]: the reform bans the release of surveys after election day. Not specific [99]: There is no information available on the ban on the release of surveys after election day.

## Citation

``` r
Freidenberg, Flavia. Dir., 2022, " Electoral Reforms on Media Access in Latin America", DOI: https://doi.org/10.6084/m9.figshare.18665819.v1. Observatory of Political Reforms in Latin America (1978-2021). Mexico City: Institute for Legal Research (IIJ-UNAM) and Washington, D.C.: Secretariat for Strengthening Democracy of the Organization of American States (SFD/OAS), V1. Available at: https://reformaspoliticas.org/bases-de-datos/
```