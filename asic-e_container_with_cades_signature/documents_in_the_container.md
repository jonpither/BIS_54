## Documents in the container {#documents-in-the-container}

The container includes the following files:

**mimetype**

*   The purpose of this file is to identify the format of the container.
*   Fixed name with the value “application/vnd.etsi.asic-e+zip”.
*   It is the first file in the container.

**sbdh.xml**

*   Xml file containing the standard business document header.
*   It includes manifest-block for describing the business document and other related documents.
*   All files except mimetype (having fixed name and value) and sbdh will be described in the manifest block.
*   The first file referred to in the manifest-block is the business document.

**Business documents**

*   Xml file containing the business document.
*   It is the first document described in the manifest-block of the sbdh.

**Additional documents**

*   One or more documents of different types e.g. xml, pdf, jpg, xls and vsd associated with the business document and that needs to be signed.

**META-INF/asicmanifest*.xml**

*   One or more files containing the hash values of all the documents (except mimetype) or the hash values of a subset of the data objects.
*   If Rootfile attribute present and set to "true"  it specify how to begin processing the container.
*   If one or more documents needs to be signed separately than the name should be suffixed by a number starting with 1\.

Example: asicmanifest**1**.xml, asicmanifest**2**.xml etc.

**META-INF/signature*.p7s** or **META-INF/signature*.p7m**

*   One or more files containing the signature of the **asicmanifest*.xml**.
*   If one or more documents needs to be signed separately than the name should be suffixed by a number starting with 1.

Example: signature**1**.xml, signature**2**.xml etc.

*   For each asicmanifest*.xml file exactly one associated signature file must be present.