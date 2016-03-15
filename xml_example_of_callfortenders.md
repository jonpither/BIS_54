# XML Example of CallForTenders {#xml-example-of-callfortenders}

<?xml version="1.0" encoding="UTF-8" standalone="yes" ?>

<ns4:CallForTenders xmlns="urn:X-test:UBL:Pre-award:CommonBasic" xmlns:ns2="urn:oasis:names:specification:ubl:schema:xsd:CommonExtensionComponents-2" xmlns:ns3="urn:X-test:UBL:Pre-award:CommonAggregate" xmlns:ns4="urn:X-test:UBL:Pre-award:CallForTenders">

  &lt;CustomizationID&gt;urn:www.cenbii.eu:transaction:biitrdm083:ver3.0&lt;/CustomizationID&gt;

  &lt;ProfileID&gt;urn:www.cenbii.eu:profile:bii47:ver3.0&lt;/ProfileID&gt;

  <ID schemeURI="**urn:uuid**">bddd9596-7bfc-430e-b8c1-12fb32100dba&lt;/ID&gt;

  &lt;ContractFolderID&gt;128&lt;/ContractFolderID&gt;

  &lt;IssueDate&gt;2015-10-09+02:00&lt;/IssueDate&gt;

  &lt;IssueTime&gt;14:13:45.674+02:00&lt;/IssueTime&gt;

<ns3:AdditionalDocumentReference>

  &lt;ID&gt;klein.zip&lt;/ID&gt;

  &lt;IssueDate&gt;2015-09-20+02:00&lt;/IssueDate&gt;

  <DocumentTypeCode listID="**MIMEMediaType**">application/zip&lt;/DocumentTypeCode&gt;

  <LocaleCode listID="**urn:un:unece:uncefact:identifierlist:standard:ISO:ISOAlpha2LanguageCode**">NL&lt;/LocaleCode&gt;

  <DocumentStatusCode listID="**urn:eu:esens:cenbii:documentStatusType**">NO RETURN&lt;/DocumentStatusCode&gt;

</ns3:AdditionalDocumentReference>

<ns3:ContractingParty>

<ns3:Party>

<ns3:PartyIdentification>

<ID schemeID="**iso6523-actorid-upis**">9956:DE:EPROC:BMIEVG:BeschA&lt;/ID&gt;

</ns3:PartyIdentification>

<ns3:PartyName>

  &lt;Name&gt;Ministerie van Buitenlandse Zaken&lt;/Name&gt;

</ns3:PartyName>

<ns3:PartyLegalEntity>

<ns3:RegistrationAddress>

<ns3:Country>

  <IdentificationCode listID="**urn:un:unece:uncefact:identifierlist:standard:5:ISO316612A**">NL&lt;/IdentificationCode&gt;

</ns3:Country>

</ns3:RegistrationAddress>

</ns3:PartyLegalEntity>

  </ns3:Party>

</ns3:ContractingParty>

<ns3:TenderingTerms>

&lt;VariantConstraintIndicator&gt;false&lt;/VariantConstraintIndicator&gt;

<ns3:CallForTendersDocumentReference>

 <ID schemeURI="**urn:uuid**">bddd9596-7bfc-430e-b8c1-12fb32100dba&lt;/ID&gt;

</ns3:CallForTendersDocumentReference>

<ns3:DocumentProviderParty>

  &lt;EndpointID&gt;http://www.tenderned.nl&lt;/EndpointID&gt;

</ns3:DocumentProviderParty>

</ns3:TenderingTerms>

<ns3:TenderingProcess>

  <ProcedureCode listID="**PR_PROC**">1&lt;/ProcedureCode&gt;

<ns3:TenderSubmissionDeadlinePeriod>

  &lt;EndDate&gt;2015-10-09+02:00&lt;/EndDate&gt;

  &lt;EndTime&gt;14:13:45.579+02:00&lt;/EndTime&gt;

</ns3:TenderSubmissionDeadlinePeriod>

<ns3:ParticipationRequestReceptionPeriod>

  &lt;EndDate&gt;2015-10-09+02:00&lt;/EndDate&gt;

  &lt;EndTime&gt;14:13:45.579+02:00&lt;/EndTime&gt;

</ns3:ParticipationRequestReceptionPeriod>

</ns3:TenderingProcess>

<ns3:ProcurementProject>

 &lt;Description&gt;010.16&lt;/Description&gt;

 <ProcurementTypeCode listID="**PROJECT_TYPE**">1&lt;/ProcurementTypeCode&gt;

<ns3:MainCommodityClassification>

 <ItemClassificationCode listID="**CPV**">03113100-7&lt;/ItemClassificationCode&gt;

</ns3:MainCommodityClassification>

<ns3:AdditionalCommodityClassification>

  <ItemClassificationCode listID="**CPV**">BA04-1&lt;/ItemClassificationCode&gt;

</ns3:AdditionalCommodityClassification>

<ns3:RealizedLocation>

  <ID schemeID="**NUTS**">NL01&lt;/ID&gt;

</ns3:RealizedLocation>

</ns3:ProcurementProject>

  </ns4:CallForTenders>