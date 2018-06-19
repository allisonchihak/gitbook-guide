# PCI Compliance

The Payment Card Industry \(PCI\) Data Security Standards \(DSS\) is a global information security standard designed to prevent fraud through increased control of credit card data. Organizations must follow PCI DSS standards if they accept payment cards from the five major credit card brands—Visa, MasterCard, American Express, Discover, and the Japan Credit Bureau \(JCB\). Compliance with PCI DSS is required for any organization that stores, processes, or transmits payment and cardholder data.

## Card Storage

All card data \(such as card numbers, expiration dates, etc.\) should be stored on a server separate from other property data. This means that properties must have more than one server to be fully compliant, without exception. The complete set of specifications can be found on the [PCI Council’s website](https://www.pcisecuritystandards.org). 

## Mews PCI Compliance

The PCI DSS designates four levels of compliance based on transaction volume. Mews Commander uses Microsoft Azure infrastructure, which is [certified as compliant](https://www.microsoft.com/en-us/trustcenter/compliance/pci) under PCI DSS version 3.2 at Service Provider Level 1 \(the highest volume of transactions—more than 6 million a year\).

Similarly, Mews Merchant does not need to have the PCI compliant certification because our payment gateway provider—Stripe—has been audited by a PCI-certified auditor and is [certified to PCI Service Provider Level 1](https://stripe.com/docs/security/stripe). More information about Stripe PCI compliance can be found on [Visa's website](https://www.visa.com/splisting/searchGrsp.do?companyNameCriteria=stripe).

## PCI Breaches

Although individual clients are not usually fined for PCI breaches, they can expect the costs of such breaches to be passed down in terms of higher fees over time. 

Furthermore, under the General Data Protection Regulation \(GDPR\), on-premise solutions \(such as the storing of all data on one server\) will be considered as a data breach. In this case, Mews clients could be fined for both a data breach and a PCI breach.   


