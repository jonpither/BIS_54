## Interoperability {#interoperability}

This eSENS eTendering BIS structure is based on the European Interoperability Framework 2.0\. It applies the Framework as follows:

1.  **Legal Interoperability**

*   Legal:
    *   Directive 2014/24/EU
    *   Directive 2014/25/EU
    *   Regulation 910/2014

1.  **Organizational interoperability**

*   Organization (Organization/Business):
    *   This eSENS eTendering BIS supports only B2G
    *   This eSENS eTendering BIS supports cross border, regional and domestic tendering procedures in EU and EEA
    *   This eSENS eTendering BIS can function as a standardized EDI agreement within a trading community
    *   This eSENS eTendering BIS supports linking of business processes within the sending and receiving organization.
*   Organization (Process):
    *   This eSENS eTendering BIS supports a set of “common business processes” that are assumed to be supported by most enterprises whether public or private. These are processes that are used widely or understood as being relevant for most companies.

1.  **Semantic interoperability**

*   Semantic:

A minimum set of information elements required to conduct a procurement procedure. The set of information elements is assumed to be sufficient to support organizational business and processing requirements stated above.

*   *   A CORE:
        *   Data model, a set of elements that the receiver MUST be able to process.
        *   Business rules, a set of business rules that ensure a common way of processing the information elements. The rules are stated in a way that allows for automated validation of document instances.

1.  **Technical interoperability**

*   Technical Interaction (Process and semantic implementation):
    *   Binding to SBDH v1.3:
        *   eTendering SBDH for UBL v3.1.xlsx
    *   ASIC-E container with CAdES signature:
    *   Binding to UBL 2.1:
        *   CWA3456 Part 212 UBL Syntax Implementation Guideline - Trdm083 Call for Tenders.docx
        *   Profiling of UBL XSDs - biitrdm083 CallForTender.xlsx
    *   Schematron files:
        *   CallForTenders v1.0.sch
        *   BIIRULESCodesT83-UBL.sch
        *   BIIRULES-T83.sch
        *   BIIRULES-UBL-T83.sch
        *   BIIRULES-UBL-T83.xsl