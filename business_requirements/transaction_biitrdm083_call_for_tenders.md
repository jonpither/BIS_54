## Transaction BiiTrdm083 Call for tenders {#transaction-biitrdm083-call-for-tenders}

### Transaction business requirements {#transaction-business-requirements}

**Note:**

Detailed information about the transaction business and information requirement can be found in document

_CWA3456 Part 112 Profile 47 - Call for Tenders.doc_

**Metadata**

| **ID** | **Requirement** |
| --- | --- |
| tbr83-001 | The call for tenders shall contain a unique ID, the issue date and the reference number of the procurement project. A unique ID is needed to establish the relation between all the documents in the process, and the tendering procedure by all the parties involved. |
| tbr83-002 | The call for tenders may contain the issue time. |
| tbr83-003 | If the call for tenders is an update of a previously issued call for tenders, this shall be indicated. |
| tbr83-004 | The contracting body shall be identified with a name, the country of registration, an endpoint and an identifier. |
| tbr83-005 | The call for tenders may include information about contacts to obtain additional information. Email or internet address at which the procurement documents shall be available for unrestricted and full direct access, free of charge. |
| tbr83-007 | The Call for tenders shall contain the following information about the procurement process: |
| tbr83-008 | The address to which tenders or requests to participation shall be submitted must be included in the call for tenders, including encryption parameters and time-stamping: Art 22 and 53 of Directive 2014/24/EC. |
| tbr83-009 | The call for tenders may include references to specific legislation applying to the procedure. |
| tbr83-012 | The call for tenders shall contain a title and a description of the object of the contract. The description of the object of the contract is basic information for both tenderer and contracting body. |
| tbr83-013 | The call for tenders shall contain information about the type of procurement project (goods, works, services) and corresponding subtype. Type of contracts is defined in article 2 of the Directive 2014/24/EU and article 2 of the Directive 2014/25/EU. Depending on the contract type different articles, thresholds, information, etc. are required. |
| tbr83-014 | The call for tenders may contain extra characteristics about the type of contract (public contract, framework agreement, qualification system, concession, design contest or DPS). Types of contracts are defined in article 2 of the Directive 2014/24/EU. Depending on the contract type different articles, thresholds, information, etc. apply. |
| tbr83-015 | The call for tenders shall contain information about the classification of the object of the contract (CPV code). CPV is defined in article 23 of the Directive 2014/24/EU. This code is a basic information element for common understanding of the object of the contract in cross-border procurement. |
| tbr83-016 | The call for tenders shall contain information about the place where the works, services or goods will be delivered (NUTS code). The location is basic information for the tenderer to elaborate the tender. |
| tbr83-018 | The Call for tenders may contain information about lots. If lots are specified, each lot shall be identified. |
| tbr83-019 | The call for tenders may indicate if variants are accepted or required. Article 45 of the Directive 2014/24/EU. |
| tbr83-020 | The call for tenders may indicate the maximum number of variants accepted or required, if there were a limit. |

**Provided documents**

| **ID** | **Requirement** |
| --- | --- |
| tbr83-022 | For each document a name shall be provided. |
| tbr83-023 | For each document a version number, a indication of the technical type an issue date and the language may be provided. |
| tbr83-024 | If a document belongs to a lot, the lot shall be identified. |
| tbr83-025 | For each document a URL may be provided where the software can be obtained to read the document. |
| tbr83-026 | For each document the file size may be specified. |
| tbr83-027 | For each document it shall be indicated whether the document is to be returned and if so, whether it must be signed and with what signature level. |

**Required documents**

| **ID** | **Requirement** |
| --- | --- |
| tbr83-028 | The Call for tenders may specify what documents are required in tenders, with their name, a description and a reference ID. |
| tbr83-029 | For each required document the level of the signature may be specified. |

**Tender submission**

| **ID** | **Requirement** |
| --- | --- |
| tbr83-030 | In the Call for tenders it may be specified that electronic submission of tenders or requests to participate will be required/accepted. If paper submission is allowed, the number of copies of the tender to be provided may be specified. |
| tbr83-031 | If paper submission is allowed, it may be indicated that paper submission serves as back-up of an electronic submission. |
| tbr83-032 | When electronic signatures are required, the signature level shall be provided. |

### Transaction Information requirements {#transaction-information-requirements}

| **InfRqID** | **Crd** | **Tree and Business term** | **Usage** | **Data Type** | **ReqID** |
| --- | --- | --- | --- | --- | --- |
|  |  | Call for tender | Document used for a contracting body  to define the procurement project to buy. |  |  |
| tir83-002 | 1..1 |  | Call for tender identifier | Identifies the call for tender as issued by the contracting body. | Identifier | tbr83-001 |
| tir83-003 | 1..1 |  | Reference number | An identifier that is specified by the buyer and used as a reference number for all documents in the procurement process. It is also known as procurement project identifier, procurement reference number or contract folder identifier. Used as a link between the call for tenders and the tender from the economic operators. |  | tbr83-002 |
| tir83-341 | 1..1 |  | Call for tender issue date | The date on which the call for tender is issued. | Date | tbr83-001 |
| tir83-355 | 0..1 |  | Call for tender issue time | Time of issue of a call for tender. The time zone has to be informed following the BII Guideline on Data Formats. | Time | tbr83-002 |
| tir83-001 | 0..1 |  | Call for tender version | Identifies the version of the call for tenders. |  | tbr83-003 |
| tir83-367 | 0..1 |  | Call for tender previous identifier | Identifies a previously issued call for tender when updated by the contracting body. | Identifier | tbr83-003 |
| tir83-368 | 0..1 |  | Tender procurement documents URI | URI from where tenderers and interested economic operators can access procurement documents. | Identifier | tbr83-005 |
| tir83-369 | 0..1 |  | Submission of tenders and requests to participate URI | The URI where the tenderer provides  the submission. |  | tbr83-008 |
|  | 1..1 |  | Process control | Information about the specification that apply to the transaction. |  |  |
| tir83-004 | 1..1 |  | Profile identifier | Identifies the BII profile or business process context in which the transaction appears. | Code | tbr00-001 |
| tir83-005 | 1..1 |  | Customization identifier | Identifies the specification of content and rules that apply to the transaction. | Code | tbr00-002 |
|  | 1..1 |  | Contracting body | The contracting authority or contracting entity who is buying supplies, services or public works using a tendering procedure as described in the applicable directive (Directives 2014/23/EU, 2014/24/EU, 2014/25/EU). |  | tbr83-004 |
| tir83-008 | 0..1 |  | Contracting body name | The name of the contracting body as it is registered. |  | tbr83-004 |
| tir83-006 | 1..1 |  | Contracting body identifier | The national identifier of a contracting body as it is legally registered (e.g. VAT identification, such as KBO) | Identifier | tbr83-001 |
| tir83-007 | 0..1 |  | Country of registration | The country where the party is registered. The country should always be given by using ISO code 3166 alpha 2 The contracting body country of registration | Code | tbr83-002 |
|  | 1..1 |  | Tendering process | Information about the tendering process. Defines the deadlines and specific terms to contract goods, services or works. |  |  |
| tir83-032 | 1..1 |  | Procedure type | A code specifying the type of this tendering process. The coded version of the description of procedure. (E.g.) Open procedure, negotiated etc. | Code | tbr83-007 |
| tir83-034 | 1..1 |  | Tender submission deadline | The date and time before which the Tender must be properly submitted to be considered. | Date | tbr83-007 |
| tir83-036 | 0..1 |  | Request for participation deadline | The date and time before which documents are available for access or may be requested and before which requests to participate must be received. | Date | tbr83-005 |
|  | 1..1 |  | Procurement project | A structured description of the project to contract services, buy goods or works. A description of the procurement project |  |  |
| tir83-044 | 0..1 |  | Procurement project name | Title attributed to the contract by the contracting body. |  | tbr83-012 |
| tir83-045 | 1..1 |  | Procurement project description | A short textual description of this Procurement project. |  | tbr83-012 |
| tir83-046 | 1..1 |  | Procurement project type | Type of contract (Works, Supplies or Services). | Code | tbr83-013 |
|  | 1..1 |  | Main common procurement vocabulary | A classification system for public procurement with the terms used by contracting bodies to describe the subject of contracts. |  | tbr83-015 |
| tir83-049 | 1..1 |  | CPV | Classification code of goods, works and services commonly used in procurement. | Code | tbr83-015 |
| tir83-350 | 0..n |  | CPV supplementary | A supplementary code to help contracting bodies describe the subject matter of contracts comprehensively. | Code | tbr83-015 |
|  | 1..1 |  | Project execution location | Information about the place where the works, services or goods will be delivered or executed. This information may include address, region, or a description. |  | tbr83-016 |
| tir83-052 | 1..1 |  | Procurement project location NUTS code | The identification with the NUTS code of the project location. | Code | tbr83-016 |

| **InfRqID** | **Crd** | **Tree and Business term** | **Usage** | **Data Type** | **ReqID** |
| --- | --- | --- | --- | --- | --- |
|  | 0..1 |  | Document package |  |  |  |
| tir83-356 | 0..1 |  | Document package identifier | Identifier of a document package within a call for tender or tender | Identifier | tbr83-021 |
| tir83-374 | 0..1 |  | Lot reference | A reference to one or more lots the economic operator is applying for. The original lot definition is part of the call for tender document. The Qualification instance only references the corresponding IDs in order to establish the connection to the call for tender information. Used to identify the lot this document package is intended for. |  | tbr83-024 |
| tir83-357 | 0..1 |  | Document package publication date | Date of publication of a document package. | Date | tbr83-023 |
| tir83-358 | 0..1 |  | Document package version | Version of a document package within a call for tender or tender. |  | tbr83-023 |
|  | 0..n |  | Provided document |  |  |  |
| tir83-375 | 0..1 |  | Document type code | A code specifying the type of the document. The mime type of the file. | Code | tbr83-013 |
| tir83-076 | 0..1 |  | Document issue date | Date when the referred document was issued. | Date | tbr83-013 |
| tir83-077 | 0..1 |  | Provided document version | Version of a document that is provided as part of a tender or call for tender. |  | tbr83-023 |
| tir83-359 | 0..1 |  | Provided document name | Name of a document that is provided as part of a tender or call for tender. |  | tbr83-022 |
| tir83-078 | 0..1 |  | Provided document language | Language of a document that is provided as part of a call for tender. | Code | tbr83-021 |
| tir83-360 | 0..1 |  | Provided document file size | UOM should be stated  by using recommendation 20 v10 File size in bytes of a document that is provided as part of a tender or call for tender. | Quantity | tbr83-026 |
| tir83-361 | 0..1 |  | Provided document url | URL where a document that is provided as part of a call for tender can be downloaded. |  | tbr83-025 |
| tir83-079 | 0..1 |  | Provided document to be returned indicator | Indicates that the provided document in the call for tender has to be returned as part of the tender. | Indicator | tbr83-027 |
| tir83-362 | 0..1 |  | Provided document signature requested | The indication whether a document is or needs to be signed. | Indicator | tbr83-027 |
| tir83-080 | 0..1 |  | Document signature level | The level of the signature to be used to sign a document. |  | tbr83-027 |
| tir83-363 | 0..1 |  | Provided document software url | The URL where the software can be found to read the document. |  | tbr83-025 |
|  | 0..n |  | Required document | Document that is required as part of a tender. |  |  |
| tir83-376 | 0..1 |  | Required document reference identifier | Reference identifier for a required document for a tender. |  | tbr83-028 |
| tir83-377 | 0..1 |  | Required document name | Name of a document that is required as part of a tender. |  | tbr83-028 |
| tir83-378 | 0..1 |  | Required document description | Description of a document that is required as part of a tender. |  | tbr83-028 |
| tir83-379 | 0..1 |  | Document signature level | The level of the signature to be used to sign a document. |  | tbr83-029 |
|  | 1..1 |  | Tendering terms | Information about the tendering terms. |  |  |
| tir83-082 | 1..1 |  | Variants indicator | Indicates if variants are accepted in the tender. Use true when variants are allowed. | Indicator | tbr83-019 |
| tir83-380 | 0..1 |  | Maximum number of variants to submit | Maximum number of variants a tenderer can submit. | Numeric | tbr83-020 |
| tir83-083 | 0..1 |  | Legal references | Textual description of references to specific legislation |  | tbr83-009 |
| tir83-364 | 0..1 |  | Backup for electronic submission indicator | Indicator whether postal submission of the tender is merely a backup for the electronic submission | Indicator | tbr83-031 |
| tir83-365 | 0..1 |  | Electronic submission required/accepted indicator | Indicator whether the use of electronic submission of tenders or requests to participate will be accepted in the execution of the contact | Indicator | tbr83-030 |
| tir83-366 | 0..1 |  | Required number of copies | Required number of paper copies to submit if using postal submission. | Numeric | tbr83-030 |
| tir83-381 | 0..1 |  | Overall expected level of tender signature | Expected level of signature to be used by the tenderer when submitting the tenders. |  | tbr83-032 |
| tir83-382 | 0..1 |  | Tender encryption key | Public key generated by the contracting body that has to be used to encrypt the tender. |  | tbr83-033 |
|  | 0..n |  | Requested lot | Information about the object of the lots, specific tenderer selection criteria for each lot, different awarding  criteria, and execution deadline. |  |  |
| tir83-187 | 1..1 |  | Lot identifier | An identifier for the lot. | Identifier | tbr83-018 |
| tir83-188 | 0..1 |  | Lot name | The title of the lot |  | tbr83-018 |