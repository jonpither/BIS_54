# Business rules {#business-rules}

For each element in the transaction business rules are defines implicit in the Call For Tenders information requirements regarding:

*   The cardinality
*   Data type
*   Code list to be used

The following table contains additional business rules:

| **RuleID** | **rulenote** | **target** | **errorlevel** | **source** |
| --- | --- | --- | --- | --- |
| BII3-T83-R001 | A Call for Tenders shall have a specification identifier | Call for Tenders | fatal | T83 |
| BII3-T83-R002 | A Call for Tenders shall have a business process identifier | Call for Tenders | fatal | T83 |
| BII3-T83-R003 | A Call for Tenders shall have a Call for Tenders identifier | Call for Tenders | fatal | T83 |
| BII3-T83-R004 | A Call for Tenders shall have a reference number | Call for Tenders | fatal | T83 |
| BII3-T83-R005 | A Call for Tenders shall have an issue date | Call for Tenders | fatal | T83 |
| BII3-T83-R006 | A Call for Tenders shall identify the Contracting Body | Call for Tenders | fatal | T83 |
| BII3-T83-R007 | A Call for Tenders shall define the tendering terms. | Call for Tenders | fatal | T83 |
| BII3-T83-R008 | A Call for Tenders shall define the tendering process. | Call for Tenders | fatal | T83 |
| BII3-T83-R009 | A Call for Tenders shall define the procedure type (open, restricted, ….). | Call for Tenders | fatal | T83 |
| BII3-T83-R010 | A Call for Tenders shall define the tender submission deadline. | Call for Tenders | fatal | T83 |
| BII3-T83-R011 | A Call for Tenders shall define the request for participation deadline. | Call for Tenders | fatal | T83 |
| BII3-T83-R012 | A Call for Tenders shall define whether there are variants allowed in the tenders or not | Call for Tenders | fatal | T83 |
| BII3-T83-R013 | A Call for Tenders shall define the procurement project name. | Call for Tenders | fatal | T83 |
| BII3-T83-R014 | A Call for Tenders shall define the procurement project description. | Call for Tenders | fatal | T83 |
| BII3-T83-R015 | A Call for Tenders shall define the procurement project type (works, supplies, ...). | Call for Tenders | fatal | T83 |
| BII3-T83-R016 | A Call for Tenders shall define the main CPV code (Common Procurement Vocabulary) | Call for Tenders | fatal | T83 |
| BII3-T83-R017 | A Call for Tenders shall define the NUTS code of the execution location. | Call for Tenders | fatal | T83 |
| BII3-T83-R018 | List identifier for country code must be “ISO3166-1:Alpha2” | Country | fatal | T83 |
| **RuleID** | **rulenote** | **target** | **errorlevel** | **source** |
| BII3-T83-R019 | List identifier for CPV must be “CPV” | CPV | fatal | T83 |
| BII3-T83-R020 | Scheme identifier for location codes must be “NUTS” | NUTS | fatal | T83 |
| BII3-T83-R021 | List identifier for procedure type must be “PR_PROC” | Procedure | fatal | T83 |
| BII3-T83-R022 | List identifier for part presentation code must be “TYPE_BID” | Presentation | fatal | T83 |
| BII3-T83-R023 | List identifier for submission type code must be “BII_SUBMISSION” | Submission | fatal | T83 |
| BII3-T83-R024 | List identifier for procurement type must be “PROJECT_TYPE” | Project | fatal | T83 |

These business rules are imposed by the usage of:

*   UBL-CallForTenders-Pre-award.xsd
*   UBLExtension-CallForTender.xsd (for elements missing in the UBL-CallForTenders-Pre-award.xsd)
*   CallForTenders v1.0.sch (to implement business rules and code lists missing in the xsd’s)
*   CallForTenders v1.0.sch
*   BIIRULESCodesT83-UBL.sch
*   BIIRULES-T83.sch
*   BIIRULES-UBL-T83.sch
*   BIIRULES-UBL-T83.xsl