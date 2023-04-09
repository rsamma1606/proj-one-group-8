# proj-one-group-8

Project 1 Group 8 - Property Values in Comparison to Crime Rate/Type by Suburb

* Project ideation

* `Bootcamp Project 1 - Group 8.docx`

* Data fetching/API integration

The `Resources` folder contains the following working csv files from merging on suburb/locality:
* `A Crimes against the person.csv`
* `B Property and deception offences.csv`
* `C Drug offences.csv`
* `D Public order and security offences.csv`
* `E Justice procedures offences.csv`
* `F Other offences.csv`

And the following from merging on postcode
* `A Crimes against the person_2.csv`
* `B Property and deception offences_2.csv`
* `C Drug offences_2.csv`
* `D Public order and security offences_2.csv`
* `E Justice procedures offences_2.csv`
* `F Other offences_2.csv`

## Test joining by OUTER join on Crime['Suburb/Town Name'] <-> Property['locality']
| Description | Count |
| ----------- | ----------- |
| Length of Crime table: | 357852 |
| Length of Property table: | 820 |
| Length of merged table: | 357894 |
| Merged from both tables: | 273479 |
| Merged from Crime table only: | 84373 |
| Merged from Property table only: | 42 |
| 2073 of 2851 unique suburbs in Crime table have no property data | 73% |
| 42 of 820 unique localities in Property table have no crime data | 5% |
| 778 of 2851 unique suburbs in Crime table match localities in Property table | 27% |
| 778 of 820 unique localities in Property table match suburbs in Crime table | 95% |

## Test joining by OUTER join on Crime['Postcode'] <-> Property_Data_Postcode['Postcode']
| Description | Value |
| ----------- | ----------- |
| Length of Crime table: | 357852 |
| Length of Property table: | 820 |
| Length of merged table: | 785215 |
| Merged from both tables: | 703720 |
| Merged from Crime table only: | 81281 |
| Merged from Property table only: | 214 |
| 1197 of 2851 unique suburbs in Crime table have no property data | 42% |
| 214 of 820 unique localities in Property table have no crime data | 26% |
| 1670 of 2851 unique suburbs in Crime table match localities in Property table | 59% |
| 606 of 820 unique localities in Property table match suburbs in Crime table | 74% |


* Data analysis

To do
* Testing

To do
* Creating documentation

To do
* Creating the presentation

To do
