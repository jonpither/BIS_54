## Code lists for identifier schemes {#code-lists-for-identifier-schemes}

### Constrains identifiers Call for Tenders transaction {#constrains-identifiers-call-for-tenders-transaction}

Table of the code lists used to constrain the values for identifiers in the Receive updates transaction:

| **Business Term** | **Allowed Scheme** | **Applicable Xpath** | **Note** |
| --- | --- | --- | --- |
| Call for tender identifier | schemeURI = "urn:uuid" | cbc:ID |  |
| Call for tender previous identifier | schemeURI = "urn:uuid" | cbc:PreviousVersionID |  |
| Contracting body identifier | schemeID='iso6523-actorid-upis' | ContractingParty/Party/PartyIdentification/ID | Value needs to start with 4 digits and a colon followed by anything (regexp = '^\d{4}:.+') |
| Tender procurement documents URI | schemeID='iso6523-actorid-upis' | cbc:EndpointID |  |
| Lot identifier | none | cac:ProcurementProjectLot/cbc:ID |  |