---
layout: page
title: Removal of CAs from Federal PKI
pubDate: 03/05/2019
archiveDate: 03/04/2020
removeDate: 03/04/2022
collection: fpki
category: Removal
permalink: fpki/announcements/2019removal/
description: This announcement provides information related to the Health IT CAs removed from the Federal PKI.
sidenav: fpkiarchivedannouncements
sticky_sidenav: true
status: Archive

subnav: 
  - text: What was the change?
    href: '#what-was-the-change'
  - text: What certification authorities were impacted?
    href: '#what-certification-authorities-were-impacted'
  - text: What should I do?
    href: '#what-should-i-do'
  - text: Who can I contact for help or more information?
    href: '#who-can-i-contact-for-help-or-more-information'
  - text: Additional Resources
    href: '#additional-resources'
---

Federal PKI teams performed two actions to remove fifty-nine (59) certification authorities (CAs) related to health IT use cases from the Federal PKI trust framework. This change is related to efforts to assess and maintain the mission scope for Federal PKI and reduce burden for commercial and non-profit organizations. This change is **not a distrust** action. 

This announcement provides details related to the CAs affected by this change. 

## What was the change?

- **February 28, 2019:** Federal PKI issued a cross-certificate from the Federal Bridge CA 2016 to DigiCert Federated ID L3 CA. 
  - The issuance of the new cross-certificate was to ensure operations for three (3) electronic prescriptions for controlled substance (EPCS) systems were not immediately impacted by the planned revocation of the Federal Bridge CA 2016 / DigiCert Federated ID CA-1 cross-certificate.  
- **March 4, 2019:** Federal PKI revoked the cross-certificate issued from the Federal Bridge CA 2016 to DigiCert Federated ID CA-1 CA.   

## What certification authorities were impacted?
The following CAs are still **active** and may be used for the intended purposes.  These CAs no longer have a trust relationship with - or are required to be audited for - Federal PKI compliance.  

Each CA is listed by common name with a link to additional CA certificate details in the [Additional Resources](#additional-resources) section. 

**CA Certificates _Issued By_ DigiCert Federated ID CA-1 CA**  

- [DigiCert Federated Trust CA](#digicert-federated-trust-ca)  
- [DigiCert Federated Trust CA-1](#digicert-federated-trust-ca-1)  
- [DigiCert Federated ID L1 CA](#digicert-federated-id-l1-ca)  
- [DigiCert Federated ID L2 CA](#digicert-federated-id-l2-ca)  
- [DigiCert Federated ID L3 CA](#digicert-federated-id-l3-ca)  
- [DigiCert Federated ID L4 CA](#digicert-federated-id-l4-ca)  
- [DigiCert Federated ID US L3 CA](#digicert-federated-id-us-l3-ca)  
- [DigiCert Federated ID US L4 CA](#digicert-federated-id-us-l4-ca)  


**CA Certificates _Issued By_ DigiCert Federated Trust CA**  

- [AAMC Direct Intermediate CA](#aamc-direct-intermediate-ca)  
- [Allina Health Connect HIE Intermediate CA](#allina-health-connect-hie-intermediate-ca)  
- [Axesson Direct CA](#axesson-direct-ca)  
- [Care360 Direct Intermediate CA](#care360-direct-intermediate-ca)  
- [Cerner Corporation Direct Intermediate CA](#cerner-corporation-direct-intermediate-ca)  
- [Cerner Corporation Resonance Intermediate CA](#cerner-corporation-resonance-intermediate-ca)  
- [CompuGroup Medical Certificate Authority](#compugroup-medical-certificate-authority)  
- [Corepoint Direct Intermediate CA](#corepoint-direct-intermediate-ca)  
- [DigiCert Accredited Direct Med CA](#digicert-accredited-direct-med-ca)  
- [DigiCert Direct Non-Provider CA](#digicert-direct-non-provider-ca)  
- [DigiCert Federated Healthcare CA](#digicert-federated-healthcare-ca)  
- [DigiCert Governmental Direct CA](#digicert-governmental-direct-ca)  
- [DigiCert Provisional Direct Med CA](#digicert-provisional-direct-med-ca)  
- [Indian Health Service-RPMS DIRECT Messaging CA](#indian-health-service-rpms-direct-messaging-ca)  
- [Inpriva Direct Federated CA](#inpriva-direct-federated-ca)  
- [INTEGRIS Direct Intermediate CA](#integris-direct-intermediate-ca)  
- [iShare Medical Direct Intermediate CA](#ishare-medical-direct-intermediate-ca)  
- [MedicaSoft Direct Intermediate CA](#medicasoft-direct-intermediate-ca)  
- [Medicity Direct CA](#medicity-direct-ca)  
- [MHIN Direct CA](#mhin-direct-ca)  
- [Mirth Direct Intermediate CA](#mirth-direct-intermediate-ca)  
- [MobileMD Direct Intermediate CA](#mobilemd-direct-intermediate-ca)  
- [MRO Direct Intermediate CA](#mro-direct-intermediate-ca)  
- [Oregon Health Authority Direct CA](#oregon-health-authority-direct-ca)  
- [Orion Health Direct Secure Messaging CA](#orion-health-direct-secure-messaging-ca)  
- [RelayHealth Direct CA](#relayhealth-direct-ca)  
- [Rochester RHIO Intermediate CA](#rochester-rhio-intermediate-ca)  
- [SCHIEx Direct CA](#schiex-direct-ca)  


**CA Certificates _Issued By_ DigiCert Federated Trust CA-1**   
 
- [MIDIGATE CA](#midigate-ca)  
- [Trinity Health Direct CA](#trinity-health-direct-ca)  

**CA Certificates _Issued By_ Orion Health Direct Secure Messaging CA**  

- [Alaska eHealth Network CA](#alaska-ehealth-network-ca)  
- [Cal INDEX CA](#cal-index-ca)  
- [Catholic Health Initiatives CA](#catholic-health-initiatives-ca)  
- [Greenville Health System CA](#greenville-health-system-ca)  
- [Highmark Tapestry HIE CA](#highmark-tapestry-hie-ca)  
- [Huntsville Hospital System CA](#huntsville-hospital-system-ca)  
- [Inland Empire Health Information Exchange](#inland-empire-health-information-exchange)  
- [Jax HR Saint Vincents HIE CA](#jax-hr-saint-vincents-hie-ca)  
- [KeystoneHIE KeyHIE CA](#keystonehie-keyhie-ca)  
- [Louisiana Health Care Quality Forum CA](#louisiana-health-care-quality-forum-ca)  
- [Mary Washington Healthcare CA](#mary-washington-healthcare-ca)  
- [Mass HIway CA](#mass-hiway-ca)  
- [Mississippi Division of Medicaid CA](#mississippi-division-of-medicaid-ca)  
- [New Hampshire Health Information Organization CA](#new-hampshire-health-information-organization-ca)  
- [New Mexico Health Information Collaborative CA](#new-mexico-health-information-collaborative-ca)  
- [North Carolina Health Information Exchange CA](#north-carolina-health-information-exchange-ca)  
- [North Dakota Information Technology Department CA](#north-dakota-information-technology-department-ca)  
- [Oklahoma State Department of Health CA](#oklahoma-state-department-of-health-ca)  
- [Optioncare CA](#optioncare-ca)  
- [Orion Health Direct Secure Messaging Public HISP CA](#orion-health-direct-secure-messaging-public-hisp-ca)  
- [Rush Health CA](#rush-health-ca)  
- [Sutter Health CA](#sutter-health-ca)  
- [The Koble Group CA](#the-koble-group-ca)  
- [Western Connecticut Health Network CA](#western-connecticut-health-network-ca)  


## What should I do?
A majority of mission operational use cases will never encounter certificates issued from these CAs.   Certificates from these CAs are primarily used for nationwide healthcare information systems and electronic health records.  

You can remove these CAs from trust list configurations used for the following purposes: 

- Federal government enterprise virtual private network (VPN) configurations
- Federal government enterprise ICAM single-sign-on services
- Federal government enterprise network authentication configurations
- Federal government enterprise federation service configurations used for authentication of end users

Removing the CAs from these trust list configurations may improve performance and reduce maintenance overhead.  


## Who can I contact for help or more information?  
Email us at fpki@gsa.gov

## Additional Resources
Details of each CA affected by this change are listed below.  You can also download files with copies of the CA certificates.   

To download PEM files with these CA certificates:  

CA Certificates _Issued By_ |Download PEM File|
---|---|
CA Certificates _Issued By_ DigiCert Federated ID CA-1 CA |[Download ](../../docs/issuedByDigiCertFederatedIDCA-1.pem){:target="_blank"}| 
CA Certificates _Issued By_ DigiCert Federated Trust CA |[Download ](../../docs/issuedByDigiCertFederatedTrustCA.pem){:target="_blank"}|
CA Certificates _Issued By_ DigiCert Federated Trust CA-1 |[Download ](../../docs/issuedByDigiCertFederatedTrustCA-1.pem){:target="_blank"}|
CA Certificates _Issued By_ Orion Health Direct Secure Messaging CA |[Download ](../../docs/issuedByOrionHealthDirectSecureMessagingCA.pem){:target="_blank"}|
 
#### CA Certificates _Issued By_ DigiCert Federated ID CA-1 CA

##### DigiCert Federated Trust CA
-	Serial #: 0E569A999C8F5DDAF576E08A12759914 
-	Not Before: 11/18/2011 
-	Not After: 11/18/2023
-	AKI: D02B3BFF6871D6900CF7C47379C7997000E54740 
-	SKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	Thumbprint (SHA-1 Hash): A6B8FEE249869E52A3039CB86B97DE5EFB6E8EB4  
-	SPKI (SHA-256 Hash): BAE872B27520AF07BCEC1F276FAACF9A3F53793CC340D7C6ADC6D60F9D37D841

##### DigiCert Federated Trust CA-1
-	Serial #: 0E25E27258328AEBDA5BAE23412F0B83  
-	Not Before: 8/24/2017 
-	Not After: 1/14/2023 
-	AKI: D02B3BFF6871D6900CF7C47379C7997000E54740 
-	SKI: 6BD202D3D1A9638B394B45319A8F0CBE29E6012B 
-	Thumbprint (SHA-1 Hash): E29C44387F7BAA9F49EFCCAEA654BCE20CFF5FD3 
-	SPKI (SHA-256 Hash): 6473D4F3B628CD1A39AD7DD43D6EC4E85418154A64581EC8A5EB85CABD09235F  

##### DigiCert Federated ID L1 CA
-	Serial #: 0C7A7DCC53DDE3D580FC9688D3449627  
-	Not Before: 10/30/2012 
-	Not After: 10/30/2027
-	AKI: D02B3BFF6871D6900CF7C47379C7997000E54740 
-	SKI: DE9A5CAE53D3C97418000031921B4A2709C87948
-	Thumbprint (SHA-1 Hash): 629D8910A0342BF54BC81CE857B1CDE8F197FDE6 
-	SPKI (SHA-256 Hash): 3D40F285BCE77279A6510F123783B0663D35BA4CE5AABCA8FE412AB95584AD4A

##### DigiCert Federated ID L2 CA
-	Serial #: 0DBA21F019A2AF46C3614FE7E72721F8 
-	Not Before: 1/8/2014 
-	Not After: 1/8/2029
-	AKI: D02B3BFF6871D6900CF7C47379C7997000E54740  
-	SKI: 0A26205117910D71DB3B3E5E0200A0E803B65519 
-	Thumbprint (SHA-1 Hash): A6B6A96F9FE96A7ABD6D653F1C042B46DB997ABF 
-	SPKI (SHA-256 Hash): B8580D56E54732240057C330614D728E0FE31D4598671FEADAC59D7EA2743DFA  

##### DigiCert Federated ID L3 CA
-	Serial #: 0FDAC8733E6F53E33102675179703290 
-	Not Before: 1/8/2014
-	Not After: 1/8/2029
-	AKI: D02B3BFF6871D6900CF7C47379C7997000E54740 
-	SKI: 8F23D3C49CEBC2A6964E3AF1CE88B28BE2935412 
-	Thumbprint (SHA-1 Hash): B60E8344FC32949C23D31A294F867EA64A9BECF2
-	SPKI (SHA-256 Hash): 0FFCB556F276AA77482A6A89EB1708AFB08DC32EE3D2D67199F00BA98DC8F436  

##### DigiCert Federated ID L4 CA
-	Serial #: 0AE4FB7C15E43A90A753212AFFCFE140 
-	Not Before: 10/30/2012 
-	Not After: 10/30/2027
-	AKI: D02B3BFF6871D6900CF7C47379C7997000E54740 
-	SKI: E33A75499CDA442F6C86031C818B2857C8FFA232 
-	Thumbprint (SHA-1 Hash): D69D7163302134697AFFBDB934E40CAB6AD57795 
-	SPKI (SHA-256 Hash): E5F60FB3FCEA3DFB8BBF09B06F26077C46BFBB36966B611B6DCCCC0D2B591186 

##### DigiCert Federated ID US L3 CA
-	Serial #: 079E9B3BDD54A4449B220580F2602B97  
-	Not Before: 1/8/2014  
-	Not After: 1/8/2029
-	AKI: D02B3BFF6871D6900CF7C47379C7997000E54740 
-	SKI: 0A8FEE0166735DE223EDA829E85592525AD0BE88 
-	Thumbprint (SHA-1 Hash): 7FF5F80F53A0DF20C42A7D0DC544C68D684CD557  
-	SPKI (SHA-256 Hash): D78BD9425A708E062927E3FE396AC22DF1414B1AE926FB6E868165C039197CAC  

> **Note**: Federal Bridge CA 2016 issued a cross certificate to the DigiCert Federated ID L3 CA on February 28, 2019. This will ensure operations for three (3) Electronic Prescriptions for Controlled Substance (EPCS) customers are not immediately impacted while we continue to review these systems and the use case. 

##### DigiCert Federated ID US L4 CA
-	Serial #: 0288147B73BE38D74651E1DCA065CD08  
-	Not Before: 4/18/2013
-	Not After: 4/18/2028
-	AKI: D02B3BFF6871D6900CF7C47379C7997000E54740 
-	SKI: 9AC44371300E3025A54AE9B4234ED338F3373FA8 
-	Thumbprint (SHA-1 Hash): F7F5D745DB7AEADE2AA27E0D5AFAB9760BF8B8A4 
-	SPKI (SHA-256 Hash): 07CCF59B26C0559F70F16FB8876444394F7148569D62CC06B07B18EBB1ECCCFF


####  CA Certificates _Issued By_ DigiCert Federated Trust CA

#####  AAMC Direct Intermediate CA
-	Serial #: 0B6957DF612F5190A590DCA544B775A1
-	Not Before: 5/28/2015
-	Not After: 5/28/2025
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 4B322EA7FD956726D59CD8AE250C0C04284D71AD
-	Thumbprint (SHA-1 Hash): 3C2C135BC01B3DF5B2F85AB78BB83698F1377116
-	SPKI (SHA-256 Hash): 317D690B644ADFBF8D3EBE4F235421A6840ED49945A15C787805B24A125E830A 

#####  Allina Health Connect HIE Intermediate CA
-	Serial #: 0A2F68961CDF5A7205CC820AD212BF21
-	Not Before: 12/8/2015
-	Not After: 12/8/2025
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: B051F97D55E4B8729FD13A680AD085DADA850F90
-	Thumbprint (SHA-1 Hash): 97C378CD81E32241D903CCC546BA6AD9C5C5880A
-	SPKI (SHA-256 Hash): 92E2F8C212A70D9489D715A0D12379420ADAC5C4FBB551A4699E1B869FD11C4D 

#####  Axesson Direct CA
-	Serial #: 088F6B9D51E46E382D4D50F2F3FCF1C8
-	Not Before: 1/8/2014
-	Not After: 1/8/2024
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: BE8F4706EA5DBF8441C38E055111DAA347EF9CCB
-	Thumbprint (SHA-1 Hash): C0A5BB8F511AB6BE007E0A5502E2E2F3998F958A
-	SPKI (SHA-256 Hash): C76C23E36F825706D78B849E581CD1CB2BFBAC48D1BB500A177CB28FAFD536B3 

#####  Care360 Direct Intermediate CA
-	Serial #: 0E117F35E685C8377C967FE06C8CD0D9
-	Not Before: 8/25/2015
-	Not After: 8/25/2025
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 56901A6BF9F4429A64A6072F1524EE8C280E2A63
-	Thumbprint (SHA-1 Hash): 81C35E4E102FB6CCC52FAB22D3A193E0A63E5223
-	SPKI (SHA-256 Hash): E1573E8E0951404B724AF2AF5DD5760B29262F4DDF628B8BD1F752816EF0A894 

#####  Cerner Corporation Direct Intermediate CA
-	Serial #: 0ED8D84E972DB014A66912DFFE8FDA97
-	Not Before: 9/26/2014
-	Not After: 9/26/2024
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 52B72C85440C1F62F87B1C621ADD6C4DB98F0931
-	Thumbprint (SHA-1 Hash): 9C549F6C12662A37B0EDF91778444C1290D58D47
-	SPKI (SHA-256 Hash): B663DEB2964FE08D1485025A0469078E82BA828CF85C56A0E5D58CB1E39E0D09 

#####  Cerner Corporation Resonance Intermediate CA
-	Serial #: 0D535AE73B9D531AAFAAD8E02686F9F7
-	Not Before: 11/11/2015
-	Not After: 11/11/2021
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 5F2474960E21A88FCD98F0DAF610779428D58A36
-	Thumbprint (SHA-1 Hash): 0D535AE73B9D531AAFAAD8E02686F9F7
-	SPKI (SHA-256 Hash): E02D3B571F6878D487DE5E2788E8509BBD127199E611E83C3AA24C1078B8CFD5 

#####  CompuGroup Medical Certificate Authority
-	Serial #: 0898830DED1957A72AB05F28363241D5
-	Not Before: 12/8/2015
-	Not After: 12/8/2025
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 0D177F4A586EB40F15D1AAF3D1E486786C67E236
-	Thumbprint (SHA-1 Hash): 6A586F2CFCBED8C8C506A245AA59F329B45A84E5
-	SPKI (SHA-256 Hash): 8E215DE3D86027B3AABCA721136D295B33A5B8037C2F54C1C5ED18073379A0F7 

##### Corepoint Direct Intermediate CA
-	Serial #: 05B60D635544534278B24A48BCD8E8E3
-	Not Before: 1/14/2015
-	Not After: 1/14/2025
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 32688EEF55C5851961D2DB09D07EAE98912632BC
-	Thumbprint (SHA-1 Hash): 1A9B160563BC27E23F6CA9EA4C5D18F3DDA7D08D
-	SPKI (SHA-256 Hash): A5CC00D887AD3538AF5710CD60A985FDF35C9B036C201C69F3B0358BD7D6FE05 

##### DigiCert Accredited Direct Med CA
-	Serial #: 09547628F41064DB095087100950673E
-	Not Before: 8/6/2013
-	Not After: 8/6/2023
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 77AE03566D1250157FFE10AB79BA2CB68C6F49D6
-	Thumbprint (SHA-1 Hash): DD110A059FE70BD57A26CA466AD7AE5573FAAF1F
-	SPKI (SHA-256 Hash): 6C9292A402CC644B4DF0CB4BE498662ACE4A34000FDD9DE6FE869E4DAEC0F2F4 

##### DigiCert Direct Non-Provider CA
-	Serial #: 024F7D6040D5E5FA85D13EC99EC83152
-	Not Before: 2/11/2014
-	Not After: 2/11/2024
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: F98866882657FB27637B3F6343D18B01CA3A12F3
-	Thumbprint (SHA-1 Hash): F6AABDD56AA6333C4BEA891688E75141D4F82D77
-	SPKI (SHA-256 Hash): 3FE5DAB75E102E06E3523093EE6A42A518684B3D036C25A0731A8C27E374705E 

##### DigiCert Federated Healthcare CA
-	Serial #: 0656F256EAA1A6DFF943082ABAE7B4EA
-	Not Before: 2/11/2014
-	Not After: 2/11/2024
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 824D97867C04CFD31144D21C1263C889417E2D3E
-	Thumbprint (SHA-1 Hash): 0E694D69F792A2546B993D841A08AA4A85319C5B
-	SPKI (SHA-256 Hash): 7E53D9869A0F6978EEE006E73C8508FAF7475B887692C4762E494C9D5F4CA731 

##### DigiCert Governmental Direct CA
-	Serial #: 0916AC4212F94019E734F0630DBF095F
-	Not Before: 9/25/2015
-	Not After: 9/25/2025
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 702D4BA984011A8475F778A90949EC304BF96FEB
-	Thumbprint (SHA-1 Hash): F5F0A823699425DA59C5C48B1848F36CB78B1BB2
-	SPKI (SHA-256 Hash): E93A89E2D242026C0D06DE7889B06E963B3B286F85F0D4DB819E54E2072B6E79 

##### DigiCert Provisional Direct Med CA
-	Serial #: 0BEE774D81066945E4EB6DB18C39AE3B
-	Not Before: 6/3/2014
-	Not After: 6/3/2024
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 75AEE40F2EA9BEB233D9159AC994C1F730B435AA
-	Thumbprint (SHA-1 Hash): 40EF4AFD9E41C1A7CB19D7AC603CBDAF4A6B0639
-	SPKI (SHA-256 Hash): AAB8548337A1266A4B049391497C3946BEF805ED395357879EFD0F9C3357517E 

##### Indian Health Service-RPMS DIRECT Messaging CA
-	Serial #: 0933E5758078BBA93074A4D164FAA171
-	Not Before: 4/4/2014
-	Not After: 4/4/2024
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 1B73DB517EB2CDE145E054E06D2B9872F066C02A
-	Thumbprint (SHA-1 Hash): 2B1BDA3A2B2015CD00CD7DFCE9832ACA58FD92C9
-	SPKI (SHA-256 Hash): E5E29329C19A97086075EF390BC0CD6550BC44BA30DB711F65113D9CF1819259 

##### Inpriva Direct Federated CA
-	Serial #: 0EDEB3BAB925834900B297481174C4F0
-	Not Before: 11/18/2011
-	Not After: 11/18/2021
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 7D174A10701A3F153BB4837AAE9FF128613E9E23
-	Thumbprint (SHA-1 Hash): 0983E63BFDAC2240FF648C1521DEE226DAD1E447
-	SPKI (SHA-256 Hash): 11B3D11879E58617BAB9AEC5E2D0C7764F5BDB5B2EC3469D8012662EDEE366B9 

##### INTEGRIS Direct Intermediate CA
-	Serial #: 01E9F27D867B6F81937EF4720B17E660
-	Not Before: 11/18/2014
-	Not After: 11/18/2024
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: CA8782FBA642FF63A96C4451CF74F76E8936E6BC
-	Thumbprint (SHA-1 Hash): C28E0ADCB82438286285B2DA6BBCAB0980E30357
-	SPKI (SHA-256 Hash): 548AB06640FBDFC0902AA1B413031018C26AD8A3E219ADE869E99F49D64C1D05 

##### iShare Medical Direct Intermediate CA
-	Serial #: 0728BE4E2D23504FB44BB6D7ED21BAB7
-	Not Before: 1/14/2015
-	Not After: 1/14/2025
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 05A93FA6DE09C5DEB45DE9F2D0F94EFD3EE4B4DD
-	Thumbprint (SHA-1 Hash): AD7937A799CD888A08BAA603A253759FDF73253E
-	SPKI (SHA-256 Hash): C82A85BC54A85A5AE54A48584E5DBC4738C6DFCA242677AE5F2F1BE9C51F115D 

##### MedicaSoft Direct Intermediate CA
-	Serial #: 0FFCEBA644F85AAFFF1C45BCB2DD74C2
-	Not Before: 4/28/2015
-	Not After: 4/28/2025
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 3DB1C40E4E7E977BA56F8592E0C8968C42AB0896
-	Thumbprint (SHA-1 Hash): E9F761B8D2BE9BE719B7D4D37DDD2A193EA240A0
-	SPKI (SHA-256 Hash): 57C8C86D14D9D8973087EFB1AAB734ED6ABB835B17F2ACF89B6A5DCE401F59CF 

##### Medicity Direct CA
-	Serial #: 05376E815724C49DEC67CE208B8FA835
-	Not Before: 2/13/2014
-	Not After: 2/13/2024
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 59F455C75BEE76663263173997F79A74D86C0EB7
-	Thumbprint (SHA-1 Hash): 9278A953771BE9BDE82E37A9C19BDD29D974B907
-	SPKI (SHA-256 Hash): 29C6DEEA67531B3EE41905E2BAA91907E0B997DA5B346F41A4B2B2154EACF0C2 

##### MHIN Direct CA
-	Serial #: 029FAFE71A57144DAF7CB403031616AF
-	Not Before: 1/8/2014
-	Not After: 1/8/2024
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 39629D94ACF873DDB2FDA4D15C208641A497C6C9
-	Thumbprint (SHA-1 Hash): DCC8C9D8F2610843F5653876CF7E2879FC62CB41
-	SPKI (SHA-256 Hash): C8CEFF21E62EEC7B49D5C00B718A4B661223D52EE940DC5A1EDEEC21AAD298F9 

##### Mirth Direct Intermediate CA
-	Serial #: 094A57F3ED91461B4D4E47B015698B4F
-	Not Before: 9/26/2014
-	Not After: 9/26/2024
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: B25C27C56F7962A1FD3EB46683A440BCCA37E07D
-	Thumbprint (SHA-1 Hash): BB1B5A342AD6929AF28AAC038CF4ED8E5377FD3B
-	SPKI (SHA-256 Hash): 3FBD2D26E6A90688784E5EC17965109E997DBE7C9F84E426B9955F8F504B3C88 

##### MobileMD Direct Intermediate CA
-	Serial #: 0E14FC08CF32009C59C596A1AFEEE1B1
-	Not Before: 10/21/2014
-	Not After: 10/21/2024
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 055244C67830566C0471612C12C8A493E14452AC
-	Thumbprint (SHA-1 Hash): 633C3C8B7999E1D6998ECA1DB9D522961ED13379
-	SPKI (SHA-256 Hash): 285F267D69801CE8459D69A3C3BAA872EE8699F462F26ECB3F0C1C5604CC4BBB 

##### MRO Direct Intermediate CA
-	Serial #: 0EDF2AA525860365D47A0662D3C9A48D
-	Not Before: 10/21/2014
-	Not After: 10/21/2024
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: D245010C188D7330FCD40E2CFFA0E023E8B60CDB
-	Thumbprint (SHA-1 Hash): 29431E91F570B976DA3B9A104FBC4CAA77E86C69
-	SPKI (SHA-256 Hash): 309B9EC320A5757B18045977BAA8F3320423372A4934FECFED93CBC5EAF7D3D0 

##### Oregon Health Authority Direct CA
-	Serial #: 0FE3D8092A6D7DF40369050171AF1E8B
-	Not Before: 3/5/2014
-	Not After: 3/5/2024
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 6A4A9128687032385649F2BE4D5D09285131CC0D
-	Thumbprint (SHA-1 Hash): 0A57575F663467ECCE525284C84E7ADBB29BD8C6
-	SPKI (SHA-256 Hash): 0CD7582516043FDF87616AB4016F331E5EF1CC4B18B2C681D6F0941D48A94503 

##### Orion Health Direct Secure Messaging CA
-	Serial #: 0133727B8425DA865077348D70A96C03
-	Not Before: 10/21/2013
-	Not After: 10/23/2023
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	Thumbprint (SHA-1 Hash): C30BBDFA0C87E1F85D5C5F67315914305B88EA3B
-	SPKI (SHA-256 Hash): 6C3148A661509D57D73F18C7E644A6573C55ED215C9F28AFA849B059948F1775 

##### RelayHealth Direct CA
-	Serial #: 0A1EC50E115F965EECCFFE5246BE3563
-	Not Before: 4/4/2014
-	Not After: 4/4/2024
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 58E321F302914D72C610BE5E29F5F8724D7921F0
-	Thumbprint (SHA-1 Hash): A0B3E7213BC44939788EEC7647EC18D45EBBA335
-	SPKI (SHA-256 Hash): F2BFD6BC69CD63088991ABA3AA4A7DC3C0B1FF2743B5F1960FEBB82FF6550545 

##### Rochester RHIO Intermediate CA
-	Serial #: 0B8C2A7EF1543A0E64C54FE60F0A7FB6
-	Not Before: 10/21/2014
-	Not After: 10/21/2024
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: 39979F30AABA80BECD81463F31EBD49FA936DAD1
-	Thumbprint (SHA-1 Hash): 36197F60193DC00077E84AEB27DCAB5F835A2E61
-	SPKI (SHA-256 Hash): 390ED57A8EC33CD534AD7B98E32D52CC5C8A46B65CE13D12F2B5B0AEA6CA3D54 

##### SCHIEx Direct CA
-	Serial #: 05E21F7FE97524F25B84EFC29188FEB8
-	Not Before: 6/7/2016
-	Not After: 6/7/2026
-	AKI: 4608385AA98E20BB0CAF5E31BA89B328BFAC8C36
-	SKI: CEE902347DAA0638416D04D5CFBAF2F03AA4435C
-	Thumbprint (SHA-1 Hash): 0ECD0F4D9AB83326E91DC4CEC99C6FEFABDD3CCC
-	SPKI (SHA-256 Hash): 9493051083E71E3404D462B36C4E89CEC4A397FFCDFCD10504316A3AD36C9E32 

####  CA Certificates _Issued By_ DigiCert Federated Trust CA-1

##### MIDIGATE CA
-	Serial #: 0C436FDCE81703C46951EB97CF926806
-	Not Before: 11/6/2017
-	Not After: 1/13/2023
-	AKI: 6BD202D3D1A9638B394B45319A8F0CBE29E6012B
-	SKI: 240E400C2ED027DC1F2997EB1E9B2AC6D8E9A0C5
-	Thumbprint (SHA-1 Hash): FB597F2604CB7EEC8953935E2EF527CB83B67ECA
-	SPKI (SHA-256 Hash): 0F88A7105EBE623CAD76D22E7A0A4229A7BB43714ED06BB798D781500E9ABE07 

##### Trinity Health Direct CA
-	Serial #: 05511821092EC4F77D4836AF31BB170F
-	Not Before: 8/24/2017
-	Not After: 1/13/2023
-	AKI: 6BD202D3D1A9638B394B45319A8F0CBE29E6012B
-	SKI: A5C2E43A16B419C3E1FABC3E7EC758C353798BC1
-	Thumbprint (SHA-1 Hash): 91C374480ABA3BB9B46C8A870F95E0CA98CF0C70
-	SPKI (SHA-256 Hash): 5B7AAE96A364A9DEE4E69BD81A910B5E4AD11A0ACB153EB033657CF9C88179B5 

####  CA Certificates _Issued By_ Orion Health Direct Secure Messaging CA 

##### Alaska eHealth Network CA
-	Serial #: 07A42C0E8D2725E05DF2A012B520D378
-	Not Before: 10/22/2013
-	Not After: 10/22/2023
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: 3FC54CA205FF8E1C0EF1F6E9C36F05FC71CF2977
-	Thumbprint (SHA-1 Hash): 41C64D922958E527051246C6D26FB0A1C392A6EB
-	SPKI (SHA-256 Hash): 75F904F9B4876E6AE3441C24ACC1F93D0C1A210928B3F0267F010925760E21AD 

##### Cal INDEX CA
-	Serial #: 04E99C3BEA35EBC9C93115BB5873F769
-	Not Before: 7/12/2016
-	Not After: 7/12/2026
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: 8A713030C19507E7331887D1175656487894E608
-	Thumbprint (SHA-1 Hash): C7E2D4CEC6F65653956E4116D896691A18A13FCB
-	SPKI (SHA-256 Hash): F46B700EC8CCB400E860EC1BD517C9AEC697DDB25B4516478644004CD204260B 

##### Catholic Health Initiatives CA
-	Serial #: 5737EBA16AEBC582D962F2EA938CC59
-	Not Before: 8/19/2014
-	Not After: 8/19/2024
-	AKI: 0A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: 66D2726A1C675A9520BB6321E1D8E54C545242A2
-	Thumbprint (SHA-1 Hash): F32A0706A0632E565D79F317141619FF2D314562
-	SPKI (SHA-256 Hash): 7868086FD31FF11D876E7344CB545DC56716DB3C9C626A599A5DF7BFC214EB46 

##### Greenville Health System CA
-	Serial #: 039C60B26637C6B8E9B63B5A9EC588AA
-	Not Before: 3/5/2014
-	Not After: 3/5/2024
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: E0ADB796C1268C12FC470B8A85779EBFE1525C31
-	Thumbprint (SHA-1 Hash): AA1FF6AE9B3B3F437A887B806CEF53689FD70CBD
-	SPKI (SHA-256 Hash): C8FB8CC2924C78C2DAE2912AD02F052FFBA0A54EFFC77663FF97E63821ED4612 

##### Highmark Tapestry HIE CA
-	Serial #: 0B7D4F1EA2A013A2A1BE3AB00CD0407D
-	Not Before: 8/19/2014
-	Not After: 8/19/2024
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: BEB1DC3128BCB53142C45CCB287A3A3BBFEFFFBA
-	Thumbprint (SHA-1 Hash): E1CAD6EC91D6D1CFB2777AB023BEA496C2E2EDBE
-	SPKI (SHA-256 Hash): B6F3758082B347CEAA3D2436030AEABA098E8BA1ADAC8A681E499EEEC7A6F756 

##### Huntsville Hospital System CA
-	Serial #: 0F0CCD49BA7A570FB90C8108BF1693A2
-	Not Before: 3/5/2014
-	Not After: 3/5/2024
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: E86E22CAF499502F44F4D42D62E76C5975DCFA19
-	Thumbprint (SHA-1 Hash): B75219D4843296613B6369AFC628078CBC69DCFA
-	SPKI (SHA-256 Hash): E236742BE61F26AA1C35AE90DCEA25B920CD9128EAD32B69BC0B6B0E04EA2EE4 

##### Inland Empire Health Information Exchange
-	Serial #: 0F6D2AE4D2580E0CA9EB1D4E1EAD131D
-	Not Before: 1/8/2014
-	Not After: 1/8/2024
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: 0C95F04752DB4BA4EBE747D289B65CD1AF3A3010
-	Thumbprint (SHA-1 Hash): C68C49E448435DC6BD352A0CD05B157CD1D1E29C
-	SPKI (SHA-256 Hash): ABA80268F12EEA1037FBBF18A8253DED14316A7BFE84C2269802A8BBFE52DE09 

##### Jax HR Saint Vincents HIE CA
-	Serial #: 0C03AE8086FBACDDDD35ADF818F0979C
-	Not Before: 2/16/2015
-	Not After: 2/16/2025
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: 0E7E0E62F9F8B72F4FC6F4783EAC87D21790CE00
-	Thumbprint (SHA-1 Hash): EFABA80CF00268CE78B5F21C11CF3494FED2751C
-	SPKI (SHA-256 Hash): ED367E66155FD54C27842FAC81802DDB3839FC4E8569880592D6AE25BA9A7C74 

##### KeystoneHIE KeyHIE CA
-	Serial #: 02A537BC58D09EB0714B9004340C9504
-	Not Before: 8/19/2014
-	Not After: 8/19/2024
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: 976E49AA98A72FDABBA276C51EF206073DC70C22
-	Thumbprint (SHA-1 Hash): 62247623C912B6286AC3EFB0EA2E649720EAB7DE
-	SPKI (SHA-256 Hash): 06A14E63979CE1F42AED287C6E5BCFF6C5FF987B4CCEA622BC8E5A45B8FA2CC7 

##### Louisiana Health Care Quality Forum CA
-	Serial #: 0491751063891838340AD681034CF86A
-	Not Before: 10/22/2013
-	Not After: 10/22/2023
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: FB88E1E7C123C6EB6B11D3F224D42F11962DDC9C
-	Thumbprint (SHA-1 Hash): 9DB9E8FD19740D423B20E047FEDE8FCA03D6D599
-	SPKI (SHA-256 Hash): D2815EE9A325C079F3396BC9E8F24E5B5B194CC5E0CF2635FF48B39F07FC7E33 

##### Mary Washington Healthcare CA
-	Serial #: 0A3511BA0C581298F96CF119505F3FC3
-	Not Before: 3/5/2014
-	Not After: 3/5/2024
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: 302AF2922B485D0073E901735832EC0DC331D2FF
-	Thumbprint (SHA-1 Hash): F2E05E1647BB5948040127E8E5515A38B24D0434
-	SPKI (SHA-256 Hash): DDF659CACDE9095019CC622F16308DF6A3D301AFC767170716F1255DA2F4A04A 

##### Mass HIway CA
-	Serial #: 05A42A2A54A348EF8B10AAFCFDEDBB73
-	Not Before: 9/25/2015
-	Not After: 9/25/2025
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: 41F486F29C43C5AA9C525A7A3C7EF18431BC61BA
-	Thumbprint (SHA-1 Hash): 7B3CE1AA5B8CB71DD8E7609AC7D144760C93CF84
-	SPKI (SHA-256 Hash): 3D5116D3A253451C0CB0D17D3FA3AAD1E3D07C1EFE79AA90B73AA369465BAB76 

##### Mississippi Division of Medicaid CA
-	Serial #: 07B268D3565D4EA118524BFE1A3088DD
-	Not Before: 1/8/2014
-	Not After: 1/8/2024
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: B476B692CF0AF437BA2617FABF2011985A819271
-	Thumbprint (SHA-1 Hash): 03A88451EB50024EE1665F181BF511A623C724F3
-	SPKI (SHA-256 Hash): 4121DBF41295B77B1B6D97296EC621CDAEF8456618AC2C96D934623AE4589B6E 

##### New Hampshire Health Information Organization CA
-	Serial #: 0FC78FF0B25CE0F20630C639C5A08C5F
-	Not Before: 10/22/2013
-	Not After: 10/22/2023
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: 13CAA050FEDEAE9E4FDCAA61FDDC813C4BD7D695
-	Thumbprint (SHA-1 Hash): 6E2EF1187693A1C09E92DD083735BC7F39B3551E
-	SPKI (SHA-256 Hash): 15C69004AA0A3A876AE0B322485114CC225AD1D1482D9EADC6EC62BD4210580E 

##### New Mexico Health Information Collaborative CA
-	Serial #: 057E0CDCDDB211396AB5242B1839CC0E
-	Not Before: 9/26/2014
-	Not After: 9/26/2024
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: A331DD14B60608534B60294205572C40E1218C9E
-	Thumbprint (SHA-1 Hash): 71440E4192C9C5F916D1BAC809C09E52C77A9661
-	SPKI (SHA-256 Hash): D66EBFC9869A49975D37670D8E3D156B0691887A52EB80F3C2D869AD6923760F 

##### North Carolina Health Information Exchange CA
-	Serial #: 066B4604152D707EE44DD584B4EE81C4
-	Not Before: 3/5/2014
-	Not After: 3/5/2024
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: 0F16204B5D1DA1D4E50421288478FC6A472D11F3
-	Thumbprint (SHA-1 Hash): FF1414C895D1BC1EDC866BA333D2942B46EDCBCC
-	SPKI (SHA-256 Hash): B0A3302C22C10B9B713448CBE47B10489D40965B078ECADC19E7269D405D27FF 

##### North Dakota Information Technology Department CA
-	Serial #: 04357DD28DE9370678C5094E9940E821
-	Not Before: 1/10/2014
-	Not After: 1/10/2024
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: 95C5DFF9172828E13FF267EAD9113D43381C4BE1
-	Thumbprint (SHA-1 Hash): A295DF1D857F219D96A9EAAA8CB4DE725B634D63
-	SPKI (SHA-256 Hash): 7BA409DEE6B1B5D74AAE9C311A17432226D8F8BC02BC4690540F927B07031EEC 

##### Oklahoma State Department of Health CA
-	Serial #: 04793AAA351A61AE7F2756A5E524B014
-	Not Before: 2/16/2015
-	Not After: 2/16/2025
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: 0972F7657FC66F353FB4CF13823895BE1D80A986
-	Thumbprint (SHA-1 Hash): E1245959AF582F9AF0B101198CD85C97970765F9
-	SPKI (SHA-256 Hash): C50453968E8DF547E854C8E99C9199B6926BD3A2DD0C1A56A58FBC1027693A49 

##### Optioncare CA
-	Serial #: 074F2D04ADEBFC19884F420FFF9DF2CF
-	Not Before: 3/1/2016
-	Not After: 3/1/2026
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: AD758EFBA5158B51565195450D1A714BEC4F3E63
-	Thumbprint (SHA-1 Hash): A776F75611B2A7B548573DC29994F142DD363882
-	SPKI (SHA-256 Hash): D5CA301C0A1FF6A5E18A2B4537BAE2047AE6E757D432D82EADB40EB765DD4128 

##### Orion Health Direct Secure Messaging Public HISP CA
-	Serial #: 06406F00285529404B11F92A78E67DA9
-	Not Before: 10/22/2013
-	Not After: 10/22/2023
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: FBC2F9B415959A384D5574A0DFBD873BD5783D38
-	Thumbprint (SHA-1 Hash): DCDC844A0B183107A172802BF2489173A914B0C9
-	SPKI (SHA-256 Hash): FC3903663F33AABAADB3B9E047CBDE625DD02D088275A16F23B8F7A2F2C92E34 

##### Rush Health CA
-	Serial #: 04B43B1C31EAB7E37BEB31F0CC3DBADD
-	Not Before: 4/23/2014
-	Not After: 4/23/2024
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: BE66CD9A79849F1B023EDB3D1AD08F32164996E0
-	Thumbprint (SHA-1 Hash): EC5C1E327D71840FD108557031AEAB63E762A207
-	SPKI (SHA-256 Hash): 1F89679357E72BC42B1B977022EA54CE733ABE3D5268C8077B7B9781D48727EA 

##### Sutter Health CA
-	Serial #: 0C59E5800EE065EA52B5581A65775CC6
-	Not Before: 10/21/2014
-	Not After: 10/21/2024
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: DF2B01740E9469FA8F055F48EA1D986BACAEE5FC
-	Thumbprint (SHA-1 Hash): 6887CAE99ECD54FEC484A90294C45973FBC12A08
-	SPKI (SHA-256 Hash): E6D7D13A3FAB0C1123CFAFBEE3AE1621790AC39E5D86AAB33EC72FDE60528A93 

##### The Koble Group CA
-	Serial #: 01BC6B791447CDA90A8A14E8204957FD
-	Not Before: 6/21/2016
-	Not After: 6/21/2026
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: CF604AC6EDBDC504D9C96A179A34FCD3F9D4DE79
-	Thumbprint (SHA-1 Hash): 4D540D6E7BC3867D81178F98C5F21991247C2FBB
-	SPKI (SHA-256 Hash): F9BC6EFB2686D571B863BA7558B4CC37D55F90A384A419FF06CBBBB49B22D94E 

##### Western Connecticut Health Network CA
-	Serial #: 07295D1F92953D6776E2146E93A58957
-	Not Before: 3/5/2014
-	Not After: 3/5/2024
-	AKI: A56E22FF39693A23FB892417C66094001ADA8E9E
-	SKI: 5B4B77AF749FD4F36146FE93C5AF8151A118075B
-	Thumbprint (SHA-1 Hash): 948D1DAF1D124ACE83F6826192036EDC35C4D005
-	SPKI (SHA-256 Hash): 22AE4FFC23AEE5E6369025594C915F20B453E45EB058E2EC54CD7DD8AE6C0F5E 



