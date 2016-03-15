## Customization ID {#customization-id}

The eSENS eTendering Customization ID identifies the specification of content and rules that apply to the transaction.

This BIS has required some minor additions and changes to the CEN BII transaction. Following the CENBII methodology any extension must be communicated by adding an extension ID onto the Customization ID.

The Document ID used in the SBDH contains the Customization ID as part of the string value.

The full value of the Document ID is:

&lt;InstanceIdentifier&gt;urn:oasis:names:specification:ubl:schema:xsd:CallForTenders::

CallForTenders##_urn:www.cenbii.eu:transaction:biitrdm083:ver3.0_::2.1&lt;/InstanceIdentifier&gt;

In the example above the Customization ID is equal to:

_urn:www.cenbii.eu:transaction:biitrdm083:ver3.0_

For implementers: Please note that CustomizationID element in the document instance MUST correspond to the Customization ID of the SMP Document Identifier.