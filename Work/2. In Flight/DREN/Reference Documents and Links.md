#DREN

- **Templates (Confluence Page)**
	https://mgmdigitalventures.atlassian.net/wiki/spaces/PER/pages/2355987200/DREN+-+Reference+documents

- **JIRA For PDF generation (RTC-1403) and Confluence Page**
	- JIRA Ticket: https://mgmdigitalventures.atlassian.net/browse/RTC-1403
	- Confluence Page for the above ticket: https://mgmdigitalventures.atlassian.net/wiki/spaces/PER/pages/2412478467/RTC-1403+Deposit+Receipt+PDF+Template
	- Sample Email and Receipt Templates (Confluence)
	- : https://mgmdigitalventures.atlassian.net/wiki/spaces/PER/pages/2406417173/DREN+-+RTC+Requirements#Sample-Email-and-Receipt-templates

##### Other/External Links

- DREN Reference Documents
	- https://mgmdigitalventures.atlassian.net/wiki/spaces/PER/pages/2355987200/DREN+-+Reference+documents

- DREN Solution Architecture
	- https://mgmdigitalventures.atlassian.net/wiki/spaces/PER/pages/2346451368/DREN+Solution+Architecture#Deposit-Receipt


##### Open Questions <font color="red">⁉️</font>

- [ ] Resort ID is not the same as `Property ID`
	- currently used to fetch details like phone number etc
- [ ] Room Number is missing in the `body` (JSON string being passed to RTC)
- [ ] Date format in payloads is `"departure_date": "12/10/2023 0:00"`  and we are using `"departure_date": "2023-09-16T19:46:14.00Z"` (as everywhere else)
----

**Links**
- [[DREN]]