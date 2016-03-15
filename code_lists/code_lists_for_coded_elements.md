## Code lists for coded elements {#code-lists-for-coded-elements}

Table of the code lists used in the Receive updates transactions:

| **Business Term** | **Source** | **Subset** | **Xpath** | **listID** |
| --- | --- | --- | --- | --- |
| Country of registration | [ISO 3166-1 alpha2](http://www.iso.org/iso/home/standards/country_codes.htm) |  | cac:Country/cbc:IdentificationCode | ISO3166-1:Alpha2 |
| Procedure type | OJEU |  | cbc:ProcedureCode | PR_PROC |
| Procurement project type | OJEU |  | cbc:ProcurementTypeCode | PROJECT_TYPE |
| CPV | CPV |  | cbc:ItemClassificationCode | CPV |
| CPV supplementary | CPV |  | cbc:ItemClassificationCode | CPV |
| Procurement project location NUTS code | NUTS |  | cac:RealizedLocation/cbc:ID | NUTS |
| Backup for electronic submission indicator / | CEN BII |  | cbc:SubmissionMethodCode | BII_SUBMISSION |
| Document Type Code | [IANA](ftp://ftp.cen.eu/public/CWAs/BII2/CWA16558/CWA16558-Annex-G-BII-CodeLists-V2_0_4.pdf%20) |  | cbc:DocumentTypeCode | MIME |
| Provided document language | ISO 639-1 |  | cbc:LocaleCode | ISO 639-1 Code |
| Type of Contract to Establish | OJEU |  | cbc:ContractingSystemCode | CONTRACT_TYPE |

### Links to code lists {#links-to-code-lists}

**CEN BII2 subsets**

[https://www.dropbox.com/home/BII3%20-%20Development/Architecture%20and%20Methodology/Codelists](https://www.dropbox.com/home/BII3%20-%20Development/Architecture%20and%20Methodology/Codelists)

**IANA**

[http://www.iana.org/assignments/media-types](http://www.iana.org/assignments/media-types)

**ISO 3166-1 alpha2:**

[http://www.iso.org/iso/home/standards/country_codes.htm](http://www.iso.org/iso/home/standards/country_codes.htm)

**ISO 639-1 alpha2:**

[http://www.iso.org/iso/home/standards/language_codes.htm](http://www.iso.org/iso/home/standards/language_codes.htm)