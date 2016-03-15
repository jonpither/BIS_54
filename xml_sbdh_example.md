# XML SBDH example {#xml-sbdh-example}

<?xml version="1.0" encoding="UTF-8" standalone="yes" ?>

&lt;StandardBusinessDocumentHeader xmlns="http://www.unece.org/cefact/namespaces/StandardBusinessDocumentHeader"&gt;  &lt;HeaderVersion&gt;1.0&lt;/HeaderVersion&gt;

**-** &lt;Sender&gt;

  <Identifier Authority="**iso6523-actorid-upis**">0106:27366538&lt;/Identifier&gt;

  &lt;/Sender&gt;

**-** &lt;Receiver&gt;

  <Identifier Authority="**iso6523-actorid-upis**">9956:DE:EPROC:BMIEVG:BeschA&lt;/Identifier&gt;

  &lt;/Receiver&gt;

**-** &lt;DocumentIdentification&gt;

  &lt;Standard&gt;UBL&lt;/Standard&gt;

  &lt;TypeVersion&gt;2.1&lt;/TypeVersion&gt;

  &lt;InstanceIdentifier&gt;bddd9596-7bfc-430e-b8c1-12fb32100dba&lt;/InstanceIdentifier&gt;

  &lt;Type&gt;CallForTenders&lt;/Type&gt;

  &lt;MultipleType&gt;false&lt;/MultipleType&gt;

  &lt;CreationDateAndTime&gt;2015-10-09T14:13:45.666+02:00&lt;/CreationDateAndTime&gt;

  &lt;/DocumentIdentification&gt;

**-** &lt;Manifest&gt;

  &lt;NumberOfItems&gt;1&lt;/NumberOfItems&gt;

**-** &lt;ManifestItem&gt;

  &lt;MimeTypeQualifierCode&gt;application/zip&lt;/MimeTypeQualifierCode&gt;

  &lt;UniformResourceIdentifier&gt;cid:klein.zip&lt;/UniformResourceIdentifier&gt;

  &lt;Description&gt;Just a test file&lt;/Description&gt;

  &lt;/ManifestItem&gt;

  &lt;/Manifest&gt;

**-** &lt;BusinessScope&gt;

**-** &lt;Scope&gt;

  &lt;Type&gt;PROCESSID&lt;/Type&gt;

  &lt;InstanceIdentifier&gt;urn:www.cenbii.eu:profile:bii47:ver3.0&lt;/InstanceIdentifier&gt;

  &lt;/Scope&gt;

**-** &lt;Scope&gt;

  &lt;Type&gt;DOCUMENTID&lt;/Type&gt;

  &lt;InstanceIdentifier&gt;urn:oasis:names:specification:ubl:schema:xsd:CallForTenders::CallForTenders##urn:www.cenbii.eu:transaction:biitrdm083:ver3.0::2.1&lt;/InstanceIdentifier&gt;

  &lt;Identifier&gt;128&lt;/Identifier&gt;

**-** &lt;BusinessService&gt;

  <ServiceTransaction IsApplicationErrorResponseRequested="**false**" IsIntelligibleCheckRequired="**false**" IsNonRepudiationOfReceiptRequired="**false**" IsAuthenticationRequired="**false**" IsNonRepudiationRequired="**false**" />

  &lt;/BusinessService&gt;

  &lt;/Scope&gt;

  &lt;/BusinessScope&gt;

  &lt;/StandardBusinessDocumentHeader&gt;

  &lt;sh:HeaderVersion&gt;1.0&lt;/sh:HeaderVersion&gt;

&lt;sh:Sender&gt;

  <sh:Identifier Authority="**iso6523-actorid-upis**">0106:30058019&lt;/sh:Identifier&gt;

&lt;/sh:Sender&gt;

&lt;sh:Receiver&gt;

  <sh:Identifier Authority="**iso6523-actorid-upis**">0096:10213231-1&lt;/sh:Identifier&gt;

  &lt;/sh:Receiver&gt;

&lt;sh:DocumentIdentification&gt;

  &lt;sh:Standard&gt;UBL&lt;/sh:Standard&gt;

  &lt;sh:TypeVersion&gt;2.1&lt;/sh:TypeVersion&gt;

  &lt;sh:InstanceIdentifier&gt;5469cc5c-f15d-4631-b47d-a348f646ab7a&lt;/sh:InstanceIdentifier&gt;

  &lt;sh:Type&gt;CallForTenders&lt;/sh:Type&gt;

  &lt;sh:MultipleType&gt;false&lt;/sh:MultipleType&gt;

  &lt;sh:CreationDateAndTime&gt;2015-05-08T17:30:00+01:00&lt;/sh:CreationDateAndTime&gt;

&lt;/sh:DocumentIdentification&gt;

&lt;sh:Manifest&gt;

  &lt;sh:NumberOfItems&gt;3&lt;/sh:NumberOfItems&gt;

&lt;sh:ManifestItem&gt;

  &lt;sh:MimeTypeQualifierCode&gt;application/xml&lt;/sh:MimeTypeQualifierCode&gt;

  &lt;sh:UniformResourceIdentifier&gt;cid:biitrdm083.xml&lt;/sh:UniformResourceIdentifier&gt;

  &lt;sh:Description&gt;Business Document&lt;/sh:Description&gt;

  &lt;sh:LanguageCode&gt;EN&lt;/sh:LanguageCode&gt;

&lt;/sh:ManifestItem&gt;

&lt;sh:ManifestItem&gt;

  &lt;sh:MimeTypeQualifierCode&gt; application/xml&lt;/sh:MimeTypeQualifierCode&gt;

  &lt;sh:UniformResourceIdentifier&gt;cid:datafile.xml&lt;/sh:UniformResourceIdentifier&gt;

  &lt;sh:Description&gt;xml file with data&lt;/sh:Description&gt;

  &lt;sh:LanguageCode&gt;EN&lt;/sh:LanguageCode&gt;

&lt;/sh:ManifestItem&gt;

&lt;sh:ManifestItem&gt;

  &lt;sh:MimeTypeQualifierCode&gt; application/pdf&lt;/sh:MimeTypeQualifierCode&gt;

  &lt;sh:UniformResourceIdentifier&gt;cid:datafile.pdf&lt;/sh:UniformResourceIdentifier&gt;

  &lt;sh:Description&gt;pdf file with data&lt;/sh:Description&gt;

  &lt;sh:LanguageCode&gt;EN&lt;/sh:LanguageCode&gt;

&lt;/sh:ManifestItem&gt;

 &lt;/sh:Manifest&gt;

&lt;sh:BusinessScope&gt;

&lt;sh:Scope&gt;

** ** &lt;sh:Type&gt;**PROCESSID**&lt;/sh:Type&gt;

** ** &lt;sh:InstanceIdentifier&gt;**urn:www.cenbii.eu:profile:bii47:ver3.0**&lt;/sh:InstanceIdentifier&gt;

  &lt;sh:Type&gt;PROCESSID&lt;/sh:Type&gt;

  &lt;sh:InstanceIdentifier&gt;urn:www.cenbii.eu:profile:bii46:ver3.0&lt;/sh:InstanceIdentifier&gt;

  &lt;/sh:Scope&gt;

&lt;sh:Scope&gt;

&lt;sh:Scope&gt;

 &lt;sh:Type&gt;DOCUMENTID&lt;/sh:Type&gt;

 &lt;sh:InstanceIdentifier&gt;urn:oasis:names:specification:ubl:schema:xsd:CallForTenders::CallForTenders##urn:www.cenbii.eu:transaction:biitrdm083:ver3.0::2.1&lt;/sh:InstanceIdentifier&gt;

  &lt;sh:Identifier&gt;[https://www.ethics.dk/asp7/tender/esens_0101_20150304.nsf/</sh:Identifier](https://www.ethics.dk/asp7/tender/esens_0101_20150304.nsf/%3C/sh:Identifier)>

&lt;sh:BusinessService&gt;

  <sh:ServiceTransaction IsApplicationErrorResponseRequested="**false**" IsAuthenticationRequired="**false**" IsIntelligibleCheckRequired="**false**" IsNonRepudiationOfReceiptRequired="**false**" IsNonRepudiationRequired="**false**" />

&lt;/sh:BusinessService&gt;

&lt;/sh:Scope&gt;

  &lt;/sh:BusinessScope&gt;

  &lt;/sh:StandardBusinessDocumentHeader&gt;