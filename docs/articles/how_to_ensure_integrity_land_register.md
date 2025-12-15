---
title: "How to Ensure the Integrity of the Electronic Land Register and Digital Archives?"
layout: default
---

# How to Ensure the Integrity of the Electronic Land Register and Digital Archives?

*By Ingmar Vali and Piret Saartee*

## 1. Introduction

We live in a time and space where paper documents are being replaced by electronic ones and handwritten signatures with digital ones. It is not quite safe to keep paperwork and paper registers nowadays, as paper is jeopardised by fire and water as well as unnoticeable changes or ill-intentioned disappearance. On the other hand, it is much easier to make backup copies of electronic documents and keep them somewhere else; it is also much more difficult to make secret changes in them, provided that they are well protected. Safety is one of the most important challenges in administering the land register which is one of the fundamental state registers. Unfortunately, digital record implementation has its drawbacks and we would like to address these in this article. Good practices and bad practices are worth sharing.   

## 2. Overview of the land register

Land register is one of the state registers, where information about real estate immovables is held, information about ownership, rights, encumbrances and restrictions. This information is supported by technical information about cadaster maps, buildings, flats etc. All this data is in electronic information system and it is presumed to be correct; this means it has legal value. Paper documents are history. Owners are insured that their property is legally protected and everyone can relay on the information presented in the electronic online land register. Of course the information is available free of charge to everyone and it can be used to make online e-conveyancing transactions between seller and buyer. And if needed, a notary, mediator or a registrar can be involved to the process online. However, most of the transactions are done between seller and buyer without any mediators. The e-conveyancing system enables to pay state fees via online banking and make deposits for the transaction. The conveyancing process is automatic and almost in real time. After signing the transaction with electronic signature, entries are made to the land register and deposit is delivered to the sellers’ bank account. Nowadays, registrars have only supervisory role over the technology. As well as buyers and sellers, a bank official can make mortgage transaction and enter new entries to the land register title. Does this sound too ideal? Too frightening? 

Whether we like it or not, we land registrars are moving toward this goal with fastening speed. The time when all transactions are done in electronic world and system security is guaranteed with electronic signatures and cryptographic algorithms is not far away. Security is specifically what the land register has to guarantee and technology makes it possible to lay off personnel and improve the process speed. As a result, the service that in some cases took months and years is swift – done in minutes. And this is what the users, citizens want.   

If you think that paper is more secure, you are mistaken. Security in the sense of availability, integrity and confidentiality is a topic that all registrars should understand. Especially availability, which in some cases is the only protection against fraud and unnoticeable changes in the register. You all probably have a few stories to tell on this matter, as do I. The best way to improve land register security and keep track of new developments in this field is to exchange experiences. 
 
Technological improvements in land register management have been noticeable in recent years. More and more land register conferences consider electronic signature to be in the agenda. And every second presenter mentions electronic signature at least once during the presentation. Electronic signature and electronic register security are topics that most of the registrars have information about. As do we in Estonia, we have good and bad practices – this is worth sharing!

In Estonia, the land register is the register of immovables and related real rights and it is maintained by the land registry departments of county courts. The land register is maintained electronically, which in turn means that electronic titles and data entered have legal effect, submitted registration applications are processed electronically, entries are made in the information system and communication with persons is also electronic whenever possible. The archives of land registry departments, which mainly consist of land registry files, are hybrid archives which maintain both paper and electronic documents. On 1 July 2006, public notaries started to submit documents to land registry departments electronically by using the e-Notary information system and since then the share of electronically submitted documents has been increasing gradually. The paper archives of land registry departments have not grown since 1 July 2010 and this means that about 99% of the documents are submitted electronically directly into land register information system and about 1% of electronic documents are submitted by email or on paper. Documents submitted on paper are immediately saved in digital archives by scanning them and paper copies are returned to persons submitting them.


## 3. Electronic land register management and security

Electronic land register is an information system, which is integrated with the secure state information system data exchange layer (X-road) . Through this X-road, government databases are securely exchanging information. Once this information passes the X-road, it receives a hash-time stamp (blockchain) and therefore all the information can be evidence in court of law in case of argument over data integrity. Although all data exchange between government information systems is regulated, every register has to manage its own security requirements. It is quite obvious that the rules regulating the preservation of the land register maintained on paper (including land registry files) do not ensure the preservation of the electronic land register or digital archives if those rules are not updated; in other words, the integrity of the database is at risk. The government of the Republic of Estonia has established a system to secure the maintenance of databases: the ISKE ,  three-level IT security guideline which is mandatory in maintaining state databases, i.e. it must be also implemented in maintaining the electronic land register.

The system of security measures consists of the procedure for specifying security requirements and the description of organisational, physical and information technology-related data security measures. In order to implement the system of security measures, it is necessary to define a security class based on the goals of information security and to select corresponding security measures from the ISKE manual.

To define a security class, the responsible specialist performs a security analysis by determining independent parts of security classes according to the goals of information security and by considering their importance. Based on the analyses, a security class is defined. Security classes are identified by letters referring to relevant information security goals and security level numbers.

There are three security levels – high, medium and low. In order to define a security level, the following parameters are used:
1)	Integrity – guarantee on the correctness, completeness and authentic origin of data and the absence of unauthorised changes;
2)	Confidentiality – data can be accessed only by authorised persons or technical tools; and
3)	Availability – properly organised data can be accessed timely and with ease by authorised persons or technical tools at an agreed time.

In determining the above parameters, a four-degree scale (0-3) is used, where the first is the lowest and the last is the strictest.

Based on the defined security level, audits are performed on the implementation of the system of security measures. Auditing covers the compliance of hardware to requirements, the correctness of defining security classes and security levels, the selection and implementation of security measures taken. The person responsible for the electronic register must make sure that the auditor has obtained the certificate of Certified Information Systems Auditor (CISA) granted by the Information Systems Audit and Control Association or the certificate of ISO 27001 Lead Auditor granted by the British Standards Institute or the Certified Auditor’s certificate granted by the German Bundesamt für Sicherheit in der Informationstechnik based on the ISO 27001 IT Grundschutz.

## 4. Land register as a high security‑class database

The ISKE security class of electronic land register is K2T3S1, which means that the system cannot be down for more than 2 hours per week (K2); the information source, the fact of its changing or destroying has evidential value; the correctness, completeness and relevance of information is validated in real time (T3); and access to data is granted to persons applying for it only if they have legitimate interest (S1). It is important to note, however, that the data on the real property are public information and everyone can see it, while the documents in a land register file (contracts, applications, etc.) can be accessed in case of legitimate interest only.

The highest level of integrity and the resulting high security level were prescribed to the information system due to the fact that the land register is one of the fundamental state registers and the electronic data entered into it have legal effect and are used in civil circulation. The maintenance of paper register was stopped for environmental and practical reasons as keeping two parallel registers is both expensive and ineffective and a waste of natural resources. In assessing possible consequences, it can be said that if anything should happen to the information system of the land register or its data, it would be a national disaster with terrible consequences (e.g. imagine what would happen if one day a John Smith were the owner of every immovable or there were no registered properties in the land register or all properties had the same data and so on and so forth).

So, what does the highest security class of integrity of the land register actually mean? This means that the integrity of relational electronic data and electronic documents, i.e. their unchanged state must be ensured. Requirements for integrity set out in the ISKE implementation manual can be divided into seven categories:

1)	Requirements for infrastructure;
2)	Requirements for organisation;
3)	Requirements for staff;
4)	Requirements for hardware;
5)	Requirements for software;
6)	Requirements for telecommunications; and
7)	Requirements for emergency preparedness.

Most of these requirements are procedural or easily implementable if sufficient financial means are available, but there are also some ‘tricky’ ones that cannot be met so easily. As mentioned above, we have given up maintaining paper register. We keep the electronic data and changes made to them safe and intact. Every operation with these data is logged and saved.

The basic means of ensuring the integrity of data on paper is: certificate paper, stamp and signature. In electronic register it is a digital signature, which enables identifying the person who made the change, while protecting the data or document by not allowing them to be changed without violating validity confirmation. The General Part of Civil Code Act sets out formats of transactions, applications and other documents. According to article 80, a document in electronic format is deemed to be equal to a document in written format unless otherwise provided by law. In order to comply with the requirements for the electronic format, a transaction or application must:
1)  Be entered into in a format enabling repeated reproduction; and
2)  Contain the names of the persons entering into the transaction; and
3)  Be electronically signed by the persons entering into the transaction.

An electronic signature must be given in a manner which allows the signature to be associated with the content of the transaction, the person entering into the transaction and the time of entry into the transaction. The procedure for attributing an electronic signature to a person and for giving electronic signatures is regulated by the Digital Signature Act. A digital signature is also an electronic signature.

As a registration application can be either authenticated by a notary public or signed digitally, documents are signed digitally and sent by e-Notary (tool for notaries for communicating with the state) via X-road or via other information systems. All electronically submitted documents are saved in the information system of the electronic land register with their digital signatures and thus their integrity is ensured. According to the Notarisation Act, a notarial deed, except an authorisation document, is prepared as one original which shall be deposited with the notary. With regard to notarial deeds, except authorisation documents, possession of an electronic of paper copy of the notarial deed substitutes for possession of the original notarial deed in legal acts. In case the original document is issued by public authority, the electronic copy of the document may also be certified by that authority. 

Unfortunately, digital signing involves some problems too. Although verifying documents with a digital signature does ensure their integrity for a comparatively long time, it is not as simple as that regarding entries in the database – these must be accessible in real time and kept in unchanged state. How to ensure that unauthorised changing and changes in the database entries are immediately identified? How to develop the database and information system further so that the integrity of entries would be maintained after the developments as well? How do we know that the right document is related to the right database entry? Is the integrity of digitally signed documents preserved forever and what can we do to improve the security of electronic data in a long term? These are the questions we seek answers today.

It may sound easy when someone says that the security of the land register is guaranteed with an electronic signature. Behind this simple sentence there are many analyses and experiments. The dilemma is that there are many ways to achieve the goal that the security guidelines are requiring. Usually it comes down to price. Unfortunately, most of the solutions that use electronic signatures have high price for development or high running costs. Therefore, unconsidered decisions may in the long run cost more than registrars have prepared for. Therefore, it is very important to know all the options in this field. When sharing the knowledge, enormous amount of money and effort can be saved and results reused. 

In Estonia we are currently using signatures in one end of the e-conveyancing process. 
 
Notaries, who make most of the real estate transactions, prepare them in a process management system called E notary. When contract is signed on paper, a notary will make the electronic copy of the original, signed with electronic signature and equipped with notary statements, and send it to land register via electronic X-road system. Other parties who have the right to send documents to land register use the public internet portal of the land register where they also sign applications electronically. This way ca 100% of applications arrive electronically signed. 

The validity confirmation service of Certification Authority (CA) gives the digital signature a legal basis. With the help of the service, a notation that records the time of signature and the validity of the certificate of the undersigned at the time of signature is added to the digital signature. The validity confirmation service is also used for verification of the validity of certificates in real time, thus ensuring secure electronic identification of persons.
The validity confirmation service is suitable for public e-services that can be used by an ID card, Mobile ID or digital stamp and that can be signed digitally. Validity confirmations of certificates issued are preserved in a secure database that allows for verifying them for certification purposes, where necessary. 

When a document is signed with an electronic signature, it needs no additional integrity mechanism and therefore can be stored in archive for relatively long time. If the Public Key Infrastructure is in use, the signature certificate validation is done only at the time of signature creation. After that, the validation system knows that the signature is valid. And when signature contains time stamping, we can be sure that it stays valid.    

In the other end, in registrars’ system, electronic signatures are validated. Like notaries, registrars are planning to use electronic signatures when making entries to the register, but this development is postponed until economically right technical solution is found. New analyses are on the way. 


## 5. Transition to digital archives

Preparations for switching over to electronic land registry files started in 2008, when the work on developing a scanning application began in order to digitalise the entire paper archives of the land registry department. Before that, only title pages were electronic. The National Archives of Estonia were also involved in developing the technical solution. The latter has worked out several guidelines on how to protect and store digital data, etc. Although the system of copies used by the National Archives did not accord with the electronic land register one-to-one, its staff helped a lot in designing the technical solution.

Protecting scanned old documents in digitalised archives with the scanner’s personal digital signature was not a suitable solution as it would have required too much money and time, and it would have been too time-consuming for users who would have had to enter their password every time in order to give their digital signature (as of 1 July 2010, the archives of the land register department contained more than 900,000 files, all in all over 8,000 shelf metres ). In addition, this might have created the problem of how to validate automatically that the person was working or had worked as a scanner in the land registry department at a given time. Therefore it was decided to implement a relatively new solution in digitalising land registry files a digital stamp that is yet another type of electronic signature besides digital signature. 

A digital stamp that is used for certifying digital documents certifies that electronically sent documents or other information really originates from the institution that sent them. A digital stamp certifies that the respective institution is associated with the specific document and the document has not been altered in the meantime.  

The certificate of digital stamp is issued to the land registry department and the trueness and conformity of the document to the original is confirmed by the land registry department’s machine. From the perspective of a reader of documents signed with a stamp, it is not important who digitalised the given document but rather that it would correspond to the original and be integral. Similarly to digital signature, the digital stamp meets this goal. If necessary, the information system allows identification of the person who gave the digital stamp. A digital stamp is given to the document automatically by the system at the moment of transferring it to the information system, i.e. the user does not have to do anything else to stamp the document digitally. Every document in the paper file is digitalised as a separate PDF file and locked with a stamp container .

Persons who read digital files or the documents contained in these will first see the container confirming the validity of electronic signature (digital stamp) and the time of giving it. A container can include a file of one or several documents. The container furnished with electronic signature contains the signatory’s certificate and its validity confirmation at the moment of signing and this ensures that documents cannot be changed unnoticed. The time label in the container confirms that the signatory’s certificate was valid at the moment of signing and therefore further validity check is not necessary. This means that signed documents can be safely stored in the archives and there is no need to renew them in the future or make enquiries on their validity in the server of the certification body.

Along with developing the digitalisation application, citizens, entrepreneurs and public officials got the opportunity to read the documents in files without leaving their home. This new service makes it possible to order the digitalisation of paper documents via the query system of the land register and submit register consultation requests, and if necessary, state the grounds for one's legitimate interest. The owners of immovables can consult the files on their property without proving their legitimate interest. The land register’s internet portal uses eID (smart card) authentication, therefore users can request and read scanned documents online. Over 95% of Estonians have eID, therefore service usage does not require pre-registration.  

For us, paper archive is left in the past. Archivists call it a dead archive and in the end, all paper documents submitted to the land register will be handed over to the National Archives of Estonia. 
 

## 6. Conclusions and international cooperation
As the issues of transition to electronic land registers and maintaining it concern or will concern all registrars, it is important to share one's experience in this area. With this in mind, we propose to start exchanging this kind of information with all land registrars in the world. A virtual network has been established to comment and share the topics addressed in this document. Among other topics, the network group focuses on the issues of electronic land register management, archiving and security. The main purpose of that network could be to create a vision of secure solution by gathering good and bad experiences of countries all over the world and to set out common rules for secure maintaining of electronic archives. For that purpose we have started a LinkedIn (www.linkedin.com) group called Land Register Security Network. Everyone with same interests is welcome to join! If we know the challenges encountered by others in developing and implementing electronic land registers and digital archives and how they ensure the integrity of electronic land registers both technically and procedurally, we can contribute to creating a better and more secure land register world. 

Your comments and contributions are welcome to Land Register Security Network in LinkedIn.

Ingmar Vali
Head of Court Registers Department
Centre of Registers and Information Systems
ingmar.vali@just.ee
www.tulepaak.ee

Piret Saartee
www.ega.ee

 

---

## References and useful links

- X‑road information  
- ISKE IT baseline security framework  
- Certification Authority validity‑confirmation services  
- Digital stamp service documentation  
