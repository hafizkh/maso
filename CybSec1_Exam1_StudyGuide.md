# Cyber Security 1 - Exam 1 Study Guide

**Tampere University | Comp.Sec.100-02 | Maso Pages 1–33**

> **Exam 1:** 32 MCQ | Pass: 22/32 | Time: 1 hour | Wrong answer: −1/3 point

---

## Table of Contents

- [Page 1: First Concepts](#page-1)
- [Page 2: Some Victims and Attackers](#page-2)
- [Page 3: Not Only Breaking Ciphers](#page-3)
- [Page 4: Not Only Viruses](#page-4)
- [Page 5: Networked Robots and Men](#page-5)
- [Page 6: Risk and Three A-Properties](#page-6)
- [Page 7: Policies and Models Do Not Protect](#page-7)
- [Page 8: Credentials](#page-8)
- [Page 9: Special Basic Protections](#page-9)
- [Page 10: Repair and Punishment](#page-10)
- [Page 11: More Than GDPR](#page-11)
- [Page 12: Anonymity](#page-12)
- [Page 13: IPR](#page-13)
- [Page 14: Social Media](#page-14)
- [Page 15: Ethics](#page-15)
- [Page 16: Security Issues on Personal Devices](#page-16)
- [Page 17: Risk Management, Policy](#page-17)
- [Page 18: Non-disclosure, but Public Keys](#page-18)
- [Page 19: Password](#page-19)
- [Page 20: Cookie](#page-20)
- [Page 21: CAPTCHA](#page-21)
- [Page 22: Crypto Procedures](#page-22)
- [Page 23: Keys and Chunks or Streams](#page-23)
- [Page 24: One-time Pad, DES, AES](#page-24)
- [Page 25: Public Key](#page-25)
- [Page 26: Hash](#page-26)
- [Page 27: The Most Common Protocols](#page-27)
- [Page 28: Nature and Devices](#page-28)
- [Page 29: Filtering](#page-29)
- [Page 30: Secure Connection](#page-30)
- [Page 31: Mobile Authentication](#page-31)
- [Page 32: Start Running Programs](#page-32)
- [Page 33: A Spectrum of Storage Issues](#page-33)

---

## Page 1: First Concepts {#page-1}

### Q1: What is required of an attack to be regarded as a cyber attack?

- **✅ 1. The target relies on an electronic information system.**
- 2. The attack happens on behalf of a nation state.
- 3. The target suffers a substantial loss.
- 4. The attacker is not acting alone but in a large coherent group.

> 💡 **Explanation:** A cyber attack simply requires that the target is an electronic information system. Nation state involvement, substantial loss and large groups are common but NOT necessary characteristics.

### Q2: Denial of service is a term

- 1. for a specific attack where the attacker modifies the responses from a www server to display HTTP 404.
- 2. used of any situations where the user or a process is not granted the service he, she or it would be authorized to get.
- **✅ 3. that refers to a service not being able to operate because of malicious requests.**
- 4. used mainly of such situations where a cracked service has been taken down for repair by administrators.

> 💡 **Explanation:** DoS means malicious traffic makes a service unable to operate. Option 2 is too broad. Option 1 is too specific. Option 4 describes admin action not an attack.

### Q3: What makes a denial of service attack (DoS) a distributed DoS?

- 1. There are many hackers working in consort to gain access to the attacked service.
- 2. The attacked server spreads the unavailability to a large community of other servers and services.
- 3. The whole farm of load-balancing and resilience-providing computers are attacked to make the service unavailable.
- **✅ 4. The attacking traffic comes to the server from several computers simultaneously.**

> 💡 **Explanation:** Distributed means the attack traffic originates FROM many sources simultaneously. Option 1 confuses many hackers with many computers attacking simultaneously.

### Q4: The term attack vector

- 1. is just a more fancy way of referring to a particular attack that has happened.
- 2. refers to the attacker's point of view to the chain of protections that implement the defence-in-depth approach.
- **✅ 3. refers to the method of an attack - one that happened or is possible.**
- 4. refers to the combination of all vulnerabilities that exist in a particular information system.

> 💡 **Explanation:** Attack vector is the method or path used in an attack. Not the attack itself, not the attacker's view of defenses, not a list of vulnerabilities.

### Q5: Confidentiality is one of the three basic goals ("C-I-A") of information security,

- 1. but it is hardly ever as important as integrity.
- 2. and it is nearly always more important than availability.
- **✅ 3. but it is usually not sufficient without integrity and availability.**
- 4. and lack of confidentiality would lead to similar problems as lack of either integrity or availability.

> 💡 **Explanation:** All three CIA goals work together. Confidentiality alone is insufficient. The other options make false absolute claims about relative importance.

---

## Page 2: Some Victims and Attackers {#page-2}

### Q1: The term script kiddie is used for certain types of attackers. What is typical of them from a defender's perspective?

- **✅ 1. Essentially similar scripts to several other attackers.**
- 2. Unpredictably modified scripts, which can therefore be particularly dangerous.
- 3. They cannot be held liable because they are minors.
- 4. Youth and incompetence, which is why their attacks are not very dangerous.

> 💡 **Explanation:** Script kiddies use the same ready-made tools as many others so attacks are recognizable and blockable. Option 4 is wrong - automated scripts can still cause serious damage.

### Q2: Attackers that are called script kiddies are characterized by

- **✅ 1. using scripts written by others.**
- 2. acting as apprentices and assistants to more experienced actors.
- 3. underage and immature morality.
- 4. installing malicious software on the machines of several other users from which the attack continues automatically.

> 💡 **Explanation:** Script kiddies use attack tools written by more skilled hackers without understanding how they work. Option 4 describes botnet operators not script kiddies.

### Q3: Identity theft

- **✅ 1. happens when someone maliciously uses identifying data of another person.**
- 2. means that an attacker changes someones credentials at a service so that the victim is blocked out.
- 3. is never a theft of identity alone; it also involves causing some loss or other disadvantage to the owner.
- 4. can happen accidentally, i.e. someone can end up stealing someone else's identity without intending to do so.

> 💡 **Explanation:** Identity theft is the malicious use of someone else's identifying data. Option 3 wrong - it can happen without financial loss. Option 4 wrong - it requires malicious intent.

### Q4: There are many digitals entities that spread mainly by the forwarding action of people. Some of them are not direct risks to computing. How many of that kind of user-spread entities are in this list: spam, hoax, ransomware, meme virus, Nigerian letter, troll?

- **✅ 1. 4**
- 2. 3
- 3. 2
- 4. 1

> 💡 **Explanation:** Ransomware is a direct computing risk. Hoax, meme virus, Nigerian letter and troll are NOT direct computing risks. That gives 4 entities.

### Q5: All of the following attacks have some social aspect, but which description gives the best coverage for the concept of social engineering?

- 1. Soliciting sensitive personal or organizational information by persuasive or masquerading emails.
- 2. Inferring sensitive personal or organizational information from discarded papers and media together with public sources.
- 3. Getting physically close and even familiar to people in order to see what they input as credentials to information systems.
- **✅ 4. Exercising the art of influencing people to act against their security policy.**

> 💡 **Explanation:** Social engineering is the broad concept of manipulating people psychologically. Options 1, 2 and 3 are specific techniques (phishing, dumpster diving, shoulder surfing), not the full concept.

### Q6: Successful impersonation means that

- 1. an identity has been confiscated.
- 2. a new identity has been assigned to a user.
- 3. a new role has been assigned to a user.
- **✅ 4. somebody/something has been cheated to act as if he/it is in contact with someone else than the attacker.**

> 💡 **Explanation:** Impersonation means fooling someone into thinking they deal with a trusted party when actually dealing with the attacker.

---

## Page 3: Not Only Breaking Ciphers {#page-3}

### Q1: An attacker, who is not a legitimate party of a conversation, but still attempts to know its contents, is called

- 1. honest but curious.
- 2. phisher.
- 3. intruder.
- **✅ 4. eavesdropper.**

> 💡 **Explanation:** An eavesdropper listens to communications without being a legitimate party. Honest but curious refers to a legitimate party who tries to learn more than they should.

### Q2: What is a description of a dictionary attack?

- 1. It is a form of social engineering where an AI system blends the victim's new responses with earlier data and common phrases and assists the attacker to select the most suitable expressions to continue.
- **✅ 2. It is a "sophisticated" brute-force attack against passwords, taking into account that they were invented by users of natural languages.**
- 3. The rainbow table method for recovering passwords is modified by using a large but fixed word list to do the transformation between each hash operation.
- 4. Observations of the victim's eye movements are transformed to profiling words when she is reading a public advertisement board or a shopping cart display.

> 💡 **Explanation:** A dictionary attack tries common words and phrases instead of random combinations, exploiting the fact that humans use real words as passwords. Option 3 describes rainbow tables.

### Q3: Backdoor

- 1. is the authentication module of a rootkit program.
- 2. is in a Trojan horse the program module that executes the malicious behaviour.
- 3. means the parameters used to create the private key in a PKI system - allowing decryption of messages encrypted with the public key.
- **✅ 4. is an intentionally made or maliciously installed method of bypassing normal authentication or encryption in an information system.**

> 💡 **Explanation:** A backdoor is a hidden way to bypass normal security controls. Can be built by developers or installed by attackers. Option 2 describes Trojan horse payload.

### Q4: Ransomware is

- 1. a term that refers to anything concrete lost by a victim and obtained by the attacker.
- **✅ 2. a program that makes your data inaccessible to you and asks for money to restore access.**
- 3. software that an attacker has been able to destroy by changing random bits during its download but still matching the checksum.
- 4. software whose download to a customer from a vendor has been blocked by an attacker until either party pays a fee to the attacker.

> 💡 **Explanation:** Ransomware encrypts your files and demands payment for the decryption key. Data is locked not destroyed.

### Q5: How can an attack be passive?

- 1. The attack happens from a compromised slave maching owned by an unknowing user.
- 2. The attacker just puts up a web-site asking for donations and starts receiving money.
- **✅ 3. A passive attack is such that does not interfere with the integrity or availability of the victim's computing.**
- 4. Actually it cannot be. An attack is by definition active.

> 💡 **Explanation:** A passive attack only observes or intercepts data without modifying anything. Eavesdropping is the classic example. Option 4 is completely wrong.

---

## Page 4: Not Only Viruses {#page-4}

### Q1: Malware that does not replicate, pretends to be performing a legitimate action, but does something else in the background is called

- 1. a logic bomb.
- 2. a trapdoor.
- 3. a virus or a worm.
- **✅ 4. a Trojan horse.**

> 💡 **Explanation:** A Trojan horse disguises itself as legitimate software but performs malicious actions. Key: does NOT replicate unlike virus or worm.

### Q2: What is a common feature of all malicious programs?

- **✅ 1. They are capable of similar actions as other programs in their running environment.**
- 2. They are aimed at achieving some financial goal.
- 3. They spread through vulnerabilities in software.
- 4. They are aimed at one target, although they usually spread elsewhere.

> 💡 **Explanation:** All malware runs as a program in the same environment as legitimate software and can do anything that environment allows. Option 2 wrong - some malware is politically motivated.

### Q3: A macro virus is malware that

- 1. has a very large spread.
- 2. runs its code from a large set of non-contiguous memory locations.
- 3. spreads by masquerading itself as backward compatibility test code for software updates.
- **✅ 4. runs on many different platforms (OS's) because it is interpreted by its host program.**

> 💡 **Explanation:** Macro viruses are written in macro languages like VBA and run inside host programs like Word or Excel. Cross-platform ability is the key characteristic.

### Q4: There are many terms that mean some sort of showing or coming out of a covering. The term that is used to mean such kind of a vulnerability in an information system is

- 1. revelation.
- 2. unveiling.
- **✅ 3. exposure.**
- 4. disclosure.

> 💡 **Explanation:** Exposure is the security term for a vulnerability that reveals something hidden. Disclosure means revealing information intentionally.

### Q5: What is the term used for an attack or error that causes data to be written in memory locations that are outside the allowed area?

- 1. Stack bloat.
- 2. Division by near-zero.
- **✅ 3. Buffer overflow**
- 4. Flooding.

> 💡 **Explanation:** Buffer overflow occurs when a program writes more data than a buffer can hold, spilling into adjacent memory. Attackers exploit this to overwrite program control data.

### Q6: The term zero-day applies for instance to

- 1. DRM protection that is broken and published before the media, e.g. a game, is launched.
- 2. the beginning of the "life" of an identity thief under the new identity.
- **✅ 3. a vulnerability in software not yet exploited but found and kept secret by a malicious party.**
- 4. an attack where a user of a limited-time-free trial version of software can keep his computer on the same day for an unlimited length of time.

> 💡 **Explanation:** A zero-day vulnerability is unknown to the software vendor - they have had zero days to fix it.

---

## Page 5: Networked Robots and Men {#page-5}

### Q1: Which of the following fits most poorly to the concept of a bot network?

- **✅ 1. Users of machines on the bot network have agreed to work with the network administrator.**
- 2. The machines on the bot network have a remote access program.
- 3. Bot network machines are rarely owned by the same organization.
- 4. A bot network can be used to implement a denial of service attack.

> 💡 **Explanation:** A botnet is built from compromised machines whose owners do NOT know. If users agreed to participate it would be a legitimate distributed computing network not a botnet.

### Q2: Man in the middle is an attack type where

- 1. a process captures system calls, modifies them, sends them to the OS kernel, and likewise filters the responses to the calling procedure.
- **✅ 2. the attacker or his process relays modified messages between two unknowing communication parties.**
- 3. a cryptographic algorithm is broken at about a square root of effort by working both from the start and end toward the middle.
- 4. a process listens to a program's system calls and their responses, and sends the divulged sensitive data to the attacker.

> 💡 **Explanation:** In MITM the attacker positions between two parties, intercepts and can modify messages. Option 1 describes a rootkit. Option 3 describes a cryptographic attack.

### Q3: A botnet is

- 1. a network used solely for internal communications.
- **✅ 2. a group of dispersed, compromised machines controlled remotely for illicit purposes.**
- 3. a complete network built for the same purpose as single "honeypot" computers.
- 4. a tool for automating security alerts in a corporate network.

> 💡 **Explanation:** A botnet is a network of compromised computers controlled by an attacker without owners' knowledge.

---

## Page 6: Risk and Three A-Properties {#page-6}

### Q1: Information assurance is sometimes considered a wider term than information security. On the other hand, assurance is just part of information security, namely

- 1. a synonym for authentication.
- 2. a synonym for accountability.
- **✅ 3. evidence that security mechanisms are efficient.**
- 4. the level up to which risk management has been able to transfer information security risks.

> 💡 **Explanation:** Assurance is the confidence or evidence that security measures actually work as intended. Not a synonym for authentication or accountability.

### Q2: Authentication is the

- 1. assertion of a unique identity.
- 2. process of defining the resources and type of access a user needs.
- 3. decision by management that a user should be given access to a system.
- **✅ 4. process of verifying an identity.**

> 💡 **Explanation:** Authentication verifies that someone is who they claim to be. Option 1 describes identification. Option 2 describes authorization.

### Q3: The objective of Availability is to make information accessible by protecting it from some but not all of these: (i) denial of service, (ii) fire, (iii) flood, (iv) unauthorized transaction, (v) unreadable backup tape. How many of these are excluded?

- 1. 4
- 2. 1
- 3. 2
- **✅ 4. 3**

> 💡 **Explanation:** Fire, flood and unauthorized transaction are excluded - 3 items. Fire and flood are physical disasters. Unauthorized transaction is an integrity issue not availability.

### Q4: Which of the following couplings best defines risk?

- **✅ 1. Threat & vulnerability**
- 2. Threat & breach of security
- 3. Vulnerability & attack
- 4. Vulnerability & lack of protection

> 💡 **Explanation:** Risk = Threat x Vulnerability. Without a vulnerability a threat cannot succeed. Without a threat a vulnerability does not matter.

---

## Page 7: Policies and Models Do Not Protect {#page-7}

### Q1: Access control means

- 1. a method to block connections to an information system from the network.
- 2. principles concerning how to allocate access rights to users.
- **✅ 3. measures, usually automatic, taken to decide whether access to a resource must be granted or denied, based on a policy.**
- 4. the entirety of identification, authentication, access decision and then either blocking or enabling access.

> 💡 **Explanation:** Access control is the enforcement mechanism that grants or denies access based on policy. Option 2 describes policy. Option 4 is too broad.

### Q2: The security goal Accountability lies outside the ordinary C-I-A triad, but it is reasonable to say that Accountability is close to the combination of Authenticity with

- **✅ 1. I**
- 2. A
- 3. C and A
- 4. C

> 💡 **Explanation:** Accountability requires authenticity combined with integrity (I) of audit records. Without integrity of the logs, accountability is meaningless.

### Q3: Assume "S." stands for "Security", and count how many of the following 7 terms mean roughly the same as S. control in the field of information security: S. mechanism, S. model, S. policy, S. service, protection, countermeasure, safeguard.

- 1. 3
- 2. 4
- 3. 6
- **✅ 4. 5**

> 💡 **Explanation:** Mechanism=yes, model=NO, policy=NO, service=yes, protection=yes, countermeasure=yes, safeguard=yes. That gives 5.

### Q4: The strategy of forming layers of protection around an asset or facility is known as

- 1. cascade zoning.
- **✅ 2. defence-in-depth.**
- 3. secured perimeter.
- 4. onion thresholding.

> 💡 **Explanation:** Defence-in-depth uses multiple layers of security so if one fails others still protect. The other options are not standard security terms.

### Q5: Non-repudiation as a security objective means that

- 1. one of the parties to the contract has tried to disclaim the information, but it has been possible to prove that it was a mistake.
- 2. accidental or intentional changes to the data after their acceptance can be corrected.
- 3. the information (e.g., contract) to which it relates has been understood and accepted.
- **✅ 4. the person to whom the information relates has no grounds for claiming that there is no connection.**

> 💡 **Explanation:** Non-repudiation means a party cannot deny having sent or received a message. The evidence is so strong that denial is impossible.

### Q6: Non-repudiation is

- **✅ 1. a special security goal.**
- 2. an attack against privacy.
- 3. the term used for cancelling some of a user's rights in an information system.
- 4. the time shortly before a public key certificate expires and a new one should be ordered.

> 💡 **Explanation:** Non-repudiation is a security goal ensuring parties cannot deny their actions. It sits alongside the CIA triad as a separate special goal.

---

## Page 8: Credentials {#page-8}

### Q1: Which counts as two factor authentication?

- 1. A hard token and a smart card.
- 2. A user name and a PIN.
- 3. A password and a PIN.
- **✅ 4. A PIN and a hard token.**

> 💡 **Explanation:** 2FA requires two DIFFERENT factor types: something you know (PIN) + something you have (hard token). Options 1, 2 and 3 mix factors of the same type.

### Q2: What is the term used for such collections of data that a person can use to prove his or her identity?

- 1. attributes
- 2. certificates
- 3. shared secrets
- **✅ 4. credentials**

> 💡 **Explanation:** Credentials are the data used to prove identity. Attributes are characteristics. Certificates are a specific type. Shared secrets are a specific authentication mechanism.

### Q3: Decisions on who can access certain data, like documents or databases, are best made by

- **✅ 1. data owner.**
- 2. senior management.
- 3. application developers.
- 4. administrators responsible for the user database.

> 💡 **Explanation:** The data owner knows the sensitivity and value of their data best. This is the principle behind discretionary access control.

### Q4: Shared secret is an InfoSec term that usually refers to

- **✅ 1. a result of protocols like IKE (Internet Key Exchange) of IPsec.**
- 2. personal sensitive data that cannot be only private but must be known to someone else, too, than the owner.
- 3. the random bit sequences that two parties send to a trusted server for the purpose of authenticating each other.
- 4. the commands and passwords that allow a backdoor entry to an information system by a group of hackers.

> 💡 **Explanation:** A shared secret is a value known only to communicating parties, typically established through a key exchange protocol like IKE.

---

## Page 9: Special Basic Protections {#page-9}

### Q1: One of the tasks of a certification authority is

- 1. to maintain a database of those private and public keys, the correspondence of which it has certified.
- 2. to calculate the corresponding public key at the request of a certified customer who provides a new private key.
- 3. to update the certificates that have been revalidated, to accommodate a new expiry date.
- **✅ 4. to publish a list of revoked certificates or provide a service that returns the certificate status.**

> 💡 **Explanation:** CA tasks include issuing, signing and managing certificate revocation through CRL or OCSP. CAs do NOT maintain private keys.

### Q2: Challenge-response is a protocol between two parties A and B such that

- 1. A challenges B with an easy-to-check computational task that anyone can do but which takes time to solve.
- 2. A challenges B with a task that supposedly only a human user can answer.
- 3. A and B receive a random challenge from the other party and then use a shared secret to calculate a response which acts as a mutual authenticator and session key.
- **✅ 4. A challenges B to respond with something that no one else than A - and possibly B itself - would be able to produce.**

> 💡 **Explanation:** Challenge-response sends an unpredictable challenge that only the legitimate party can answer. Option 1 describes proof-of-work. Option 2 describes CAPTCHA.

### Q3: A digital signature is made with

- 1. symmetric cryptography.
- 2. a message authentication code.
- 3. a public key certificate.
- **✅ 4. a hash function and an asymmetric cryptoalgorithm.**

> 💡 **Explanation:** A digital signature works by hashing the message then encrypting the hash with the sender's private key. The recipient decrypts with the public key and compares hashes.

### Q4: At what phase of a product's life cycle is it likely to be most expensive to improve security?

- **✅ 1. implementation**
- 2. rapid prototyping
- 3. testing
- 4. design

> 💡 **Explanation:** The later in the development lifecycle you find and fix security problems the more expensive it is. Among these options implementation is the latest stage.

### Q5: What does a firewall prevent from functioning in the way they were intended to?

- 1. ports
- 2. IP-addresses
- 3. protocols
- **✅ 4. packets**

> 💡 **Explanation:** A firewall works by inspecting and filtering network packets. Ports, IP addresses and protocols are attributes used in rules but packets are what actually get blocked.

### Q6: What security concept is violated by the following: One person in the finance department is able to insert vendors to the vendor database and subsequently pay to the vendors?

- 1. Well-formed transactions
- 2. Least privilege
- **✅ 3. Separation of duties**
- 4. Database normalization

> 💡 **Explanation:** Separation of duties requires that critical tasks be divided among different people so no single person can commit fraud alone.

### Q7: Steganography is

- 1. a special branch of cryptographic hash functions.
- **✅ 2. an art of embedding data into a larger quantity of other data.**
- 3. an obsolete method of protecting secret messages.
- 4. synonymous to digital watermarking.

> 💡 **Explanation:** Steganography hides a secret message within ordinary-looking data like images or audio. Still actively used. Digital watermarking is a related but different concept.

---

## Page 10: Repair and Punishment {#page-10}

### Q1: Which of the following statements is true?

- 1. Printing on paper is not a serious method to back up data.
- **✅ 2. Removable flash memories are suitable as backup media.**
- 3. Backups are useless if copies are made only once a week.
- 4. The method of incremental copies in backup means the same as making consecutive full copies.

> 💡 **Explanation:** Flash drives are valid backup media. Option 1 wrong - printing IS valid for some data. Option 3 wrong - weekly backups are better than none. Option 4 wrong - incremental copies only copy changes since last backup.

### Q2: It is important to have an off-site backup copy of files to

- 1. improve accessibility of files from other locations.
- 2. speed up the process of accessing files at any time.
- 3. reduce the possibility of data theft.
- **✅ 4. prevent the loss of data in the event of a fire.**

> 💡 **Explanation:** Off-site backup protects against physical disasters that could destroy both primary data and any on-site backups simultaneously.

### Q3: All of the following may be needed to repair broken integrity, but what is the most concrete concept?

- 1. detection
- 2. policy
- 3. proactivity
- **✅ 4. redundancy**

> 💡 **Explanation:** Redundancy is the most concrete concept - having extra copies or checksums allows detection and restoration of corrupted data.

### Q4: If you are a EU citizen and your personal data has been unduly disclosed by a service in EU,

- 1. you must still sue the company running the service in order to get any compensation.
- 2. the GDPR stipulates a formula for a compensation the responsible company must pay to you.
- **✅ 3. the responsible company may have to pay a fine of millions of euros.**
- 4. nobody will be held responsible if the data has been leaked through hacking and the attacker is not caught.

> 💡 **Explanation:** Under GDPR, fines up to 20 million euros or 4% of global annual turnover. Option 4 wrong - the company can still be held responsible even if the attacker is not caught.

---

## Page 11: More Than GDPR {#page-11}

### Q1: The central meaning of data protection is in protecting

- 1. the secret information of individuals.
- **✅ 2. the information that individuals disclose to different data collectors.**
- 3. the information companies provide to various data collectors.
- 4. the confidential information of companies.

> 💡 **Explanation:** Data protection is about protecting personal information that individuals share with organizations. Option 3 wrong - about company data. Option 4 wrong - GDPR does not primarily cover confidential company info.

### Q2: GDPR defines several roles with respect to a person's personal data, but not the role of data

- 1. subject.
- **✅ 2. object.**
- 3. controller.
- 4. processor.

> 💡 **Explanation:** GDPR defines: data subject, data controller, data processor. Data object is a technical database term not a GDPR legal concept.

### Q3: The European Union has enacted General Data Protection Regulation that mainly covers

- 1. the exchange of data between the EU and countries outside the EU.
- **✅ 2. the duties of organizations when they handle data from individuals.**
- 3. the rules for encrypting and authenticating data when it is communicated between organizations or between individuals and organizations.
- 4. the rights and duties that EU citizens have with respect to their private data.

> 💡 **Explanation:** GDPR primarily places obligations on organizations. Option 1 wrong - not just cross-border. Option 3 wrong - not about encryption standards.

### Q4: Payment card industry data security standard, PCI-DSS

- 1. is included in GDPR.
- 2. is the equivalent of GDPR in the USA.
- **✅ 3. is, as its name says, a standard created by an industry branch.**
- 4. is not related to GDPR by purpose or origin.

> 💡 **Explanation:** PCI-DSS was created by major card brands (Visa, Mastercard, Amex etc.) not by a government. Industry standard not a law.

---

## Page 12: Anonymity {#page-12}

### Q1: When studying anonymity as a security goal it is natural to define it to have different degrees depending on

- 1. the country where you reside.
- 2. what data should not be disclosed and by whom.
- **✅ 3. what data should not be disclosed and to whom.**
- 4. the age of the person whose anonymity is in question.

> 💡 **Explanation:** Anonymity depends on WHAT information should be hidden AND TO WHOM it should be hidden. Note: TO WHOM not BY WHOM - this is a common trap.

### Q2: Privacy is synonymous to

- 1. secrecy.
- 2. anonymity.
- **✅ 3. none of these.**
- 4. privilege.

> 💡 **Explanation:** Privacy is distinct from secrecy, anonymity and privilege. Privacy is the right to control your own personal information - overlaps with all three but identical to none.

### Q3: Pseudonym is

- 1. a general term that refers to various sorts of aliases in filesystems and databases.
- 2. a part of an impersonation attack.
- 3. a human-readable indirection to a username in an information system.
- **✅ 4. an artificial name that replaces the real name of a user.**

> 💡 **Explanation:** A pseudonym is a false name used instead of a real name. Not a filesystem term. Not inherently part of an attack.

---

## Page 13: IPR {#page-13}

### Q1: Copyright is originally a property of

- 1. an artefact.
- **✅ 2. the creators of an artefact.**
- 3. the publisher of an artefact.
- 4. the buyer of an artefact.

> 💡 **Explanation:** Copyright belongs to the creator of a work by default. Publishers may acquire rights through contracts but do not own copyright originally.

### Q2: One purpose of DRM is

- **✅ 1. to provide access control to digital media for protection of copyrights.**
- 2. to prevent production and distribution of software that can break copy protections of media files.
- 3. to promote equal-opportunity rights to digital contents, in opposition to digital divide.
- 4. to maintain a directory of copyrights and their delegations.

> 💡 **Explanation:** DRM controls how digital content can be accessed, copied and distributed. Option 2 describes anti-circumvention laws. Option 3 wrong - DRM restricts access.

### Q3: What is not a way to protect intellectual property?

- **✅ 1. privacy regulations**
- 2. DRM, digital rights management
- 3. patents
- 4. licensing

> 💡 **Explanation:** Privacy regulations like GDPR protect personal data not intellectual property. DRM, patents and licensing are all genuine IP protection mechanisms.

---

## Page 14: Social Media {#page-14}

### Q1: When you craft a job application you can include links to your social media postings. What can go wrong, in the sense of information security?

- 1. The recruiter may think you allow him to see what is linked to those postings, for instance with whom you are connected, but such activity is an offense to your privacy.
- **✅ 2. The recruiter follows what is linked to those postings, and finds something unfavourable of you.**
- 3. The recruiter thinks that by providing links you are trying to hide something on other platforms. His searches indeed find much more information, but he doesn't realize it is about someone else having the same name as you.
- 4. If the other job applicants are not at all active in social media, the recruiter might think that you are not a good choice because you may spend also work time there.

> 💡 **Explanation:** Your social media may contain posts or connections that create a negative impression. Option 1 wrong - following public links is not a privacy offense.

### Q2: Social media is in constant motion and update is a buzzword there. What kind of update, however, is poorly taken care of - if at all?

- **✅ 1. Rectifying of fake news or "alternative truths".**
- 2. Client side scripts of the platform.
- 3. Software that the platform servers are running.
- 4. Terms and conditions of the platform.

> 💡 **Explanation:** Social media spreads content quickly but is very slow or unwilling to correct misinformation after it spreads.

### Q3: Social media is a "lively place" and update is a buzzword there. What kind of update, however, is usually poorly handled?

- **✅ 1. Links to sites that have published new pages that correct earlier mistakes in their news.**
- 2. Changes in a user's profile or credentials.
- 3. Algorithms and software of the platform.
- 4. Memberships in groups.

> 💡 **Explanation:** Corrections to previously shared false information are almost never propagated. When a news story is corrected the original shared post remains unchanged.

### Q4: Who is responsible if you share in social media something that is legal but not true and this causes harm to someone who reads it?

- 1. The reader, who took the post for true.
- **✅ 2. You, without conditions.**
- 3. You, but only if you created the post yourself or reposted something that was not published for the same reader earlier.
- 4. No one.

> 💡 **Explanation:** If you share false information that causes harm you bear responsibility whether you created it or reshared it.

---

## Page 15: Ethics {#page-15}

### Q1: Ethics is an important topic in information systems,

- **✅ 1. and some aspects of it extending to the area of information security include treatment of privacy and IPR.**
- 2. and in information security its most vital application is in forecasting attacks by understanding the hackers' ethics.
- 3. but in information security its role is negligible with the exception of hacking aspects.
- 4. but in information security it only occurs in ethical hacking.

> 💡 **Explanation:** Ethics in information security covers privacy, IPR, responsible disclosure and fair use. Options 3 and 4 greatly understate its role.

### Q2: What is not a topic of ethical considerations?

- 1. Using a foreign VPN to access information that is illegal in your country but legal almost everywhere else.
- 2. Searching for vulnerabilities in a web service by sending broken data packets to it.
- **✅ 3. Wasting your own and others' time by writing in social media long explanations of questionable quality.**
- 4. Working out ways to block advertisements on web sites that get their income from displaying those ads.

> 💡 **Explanation:** This is a matter of quality and courtesy but not a genuine ethical dilemma in information security. Options 1, 2 and 4 all involve real ethical questions.

### Q3: If you need to browse the internet anonymously,

- 1. you have no choice but do that on a public machine - in a library for instance.
- **✅ 2. the TOR network is an option you can seriously consider.**
- 3. you can simply set your browser to the privacy preserving mode.
- 4. you must be cautious because most services for that purpose are against the law, at least in Finland.

> 💡 **Explanation:** TOR is a legitimate and legal tool for anonymous browsing. Option 3 wrong - private mode only prevents local browser history. Option 4 wrong - TOR and VPNs are legal in Finland.

---

## Page 16: Security Issues on Personal Devices {#page-16}

### Q1: Assume you have logged in to a web site with your registered username and password. Then you close your browser and switch off the computer. The next day you launch the browser and navigate to the same site. If you get directly logged in without entering any credentials, what can you infer?

- 1. You did not close your browser the first day, after all.
- 2. There is no way to log out from the site.
- 3. Your browser sends your password automatically to the site.
- **✅ 4. The site uses a login cookie that persists even if the browser is not running.**

> 💡 **Explanation:** A persistent login cookie is stored on your computer and sent automatically when you revisit the site. Browsers do not send passwords automatically.

### Q2: Assume you buy a USB memory stick that has internal 256-bit AES encryption. The stick has a small keyboard (0..9) where you can choose a passcode of length 8, 9 or 10 key presses for accessing your data. You take the longest code into use, but then an attacker gets hold of our stick. He doesn't try to press the keys, but opens the stick and can enter codes electronically. How many attempts does he have to make in the worst case (his worst, not yours)?

- **✅ 1. 10^10**
- 2. 10^8+10^9+10^10
- 3. 2^256
- 4. 3*10^10

> 💡 **Explanation:** You chose the 10-digit code. The attacker only needs to try all 10-digit combinations: 10^10. Option 2 wrong - attacker only tries the length you chose. Option 3 wrong - attacker attacks the passcode not the AES key.

### Q3: If your personal computer has a firewall, it is typically

- 1. an accessory on the power cord.
- **✅ 2. one process among others.**
- 3. hardware on the network card.
- 4. an add-on to the browser process.

> 💡 **Explanation:** On a personal computer a firewall is a software process running alongside other processes. Not hardware. Not tied to the browser.

### Q4: There is a vast variety of things that can be connected to the USB port of a computer. Ignoring problems with electricity, which of the following connections has the least risks in information security?

- 1. Your private memory stick when you read and write document files for long term storage.
- 2. Your own mobile phone when you only charge its battery in a locked box at a local supermarket.
- **✅ 3. Charging the new camping shower you just bought from a Chinese web shop. (This is a little pump with a hose.)**
- 4. The optical mouse that your IT staff checked for you to bring home from your office for remote work.

> 💡 **Explanation:** A simple water pump only needs power and has no data capability at all. Option 1 has document malware risk. Option 2 risks juice jacking at a compromised port.

---

## Page 17: Risk Management, Policy {#page-17}

### Q1: What control mechanisms can be left out of the risk analysis?

- 1. The types of mechanisms that do not yet exist in the target system.
- 2. Risk analysis does not include the handling of control mechanisms.
- **✅ 3. Mechanisms that do not control threats to the system under consideration.**
- 4. Those that solve the same problem as the mechanisms already addressed in the analysis.

> 💡 **Explanation:** Risk analysis should only include controls relevant to the threats being analyzed. Controls addressing out-of-scope threats are irrelevant.

### Q2: Which of the following does not need to be considered in the risk analysis?

- **✅ 1. How much is invested in information security in competing companies.**
- 2. Impact of security breaches on the company's reputation or public image.
- 3. How difficult or expensive it would be for an attacker to carry out certain types of threats.
- 4. Company's data resources and their value.

> 💡 **Explanation:** What competitors spend on security is irrelevant to your own risk analysis. Options 2, 3 and 4 are all relevant.

### Q3: Compared to a previous estimate, the overall risk is reduced if

- 1. the probability of the threat associated with a particular risk is set lower in the calculations than it actually is.
- 2. the existence of a control mechanism is ignored in the calculations.
- 3. the value of an asset is marked in the calculations larger than it actually is.
- **✅ 4. the value of an asset is found to be smaller than before.**

> 💡 **Explanation:** Risk = Threat x Vulnerability x Asset Value. If an asset is genuinely worth less the real risk is lower. Option 1 just underestimates - does not reduce real risk.

### Q4: Alice has been tasked with implementing several security controls to protect the company's email system. This shows that the company's approach to email risks is

- **✅ 1. risk mitigation.**
- 2. risk acceptance.
- 3. risk transference.
- 4. risk avoidance.

> 💡 **Explanation:** Risk mitigation means taking active steps to reduce risk by implementing controls. The four treatments are: mitigation, acceptance, transference and avoidance.

---

## Page 18: Non-disclosure, but Public Keys {#page-18}

### Q1: A non-disclosure agreement may have many forms, but its usual purpose is

- 1. to protect the customer's or employee's personal data against too wide usage by the organization.
- **✅ 2. to prevent an employee or visitor from revealing sensitive information of an organization.**
- 3. to provide a confidentiality classification of information that an organization shares with its members.
- 4. to set rules for encryption for sensitive data of an organization.

> 💡 **Explanation:** An NDA binds a person to keep certain organizational information confidential. Option 1 describes GDPR. Option 3 describes a classification policy.

### Q2: The basic goal of a public key infrastructure is to

- 1. bind a private key to a corresponding public key.
- **✅ 2. bind the public key to the entity to which the key belongs.**
- 3. allow for a reasonably short and easy-to-find chain of certificates.
- 4. enable a wide user base by using a hierarchical structure.

> 💡 **Explanation:** PKI's fundamental purpose is to create a trusted link between a public key and the identity of its owner. Options 3 and 4 describe structural features not the basic goal.

### Q3: Assume K is a public key and S is the corresponding private key, and they belong to person B. A certificate for K is generated when

- **✅ 1. someone else uses his private key for a signature that binds K and the identity of B.**
- 2. using S, a signature is calculated that binds K and S.
- 3. a trusted party creates a digital signature that binds K with S.
- 4. a signature is created which can be verified with S and which binds the identity of B to K.

> 💡 **Explanation:** A certificate is created when a trusted third party (CA) uses its OWN private key to sign a binding between public key K and the identity of B. The someone else is the CA not B.

---

## Page 19: Password {#page-19}

### Q1: If you need to come up with a question and answer in a web service for the case of forgetting your password, which of the following is most important from the authentication point of view?

- 1. the memorability of the answer
- **✅ 2. the entropy of the answer**
- 3. the entropy of the question
- 4. the compatibility of the question and the answer

> 💡 **Explanation:** From an authentication perspective the answer must be unpredictable - high entropy means hard to guess. Memorability is a usability concern not a security concern.

### Q2: If your browser offers you the option to save for future use the password you just entered for some web service, which of the following conditions is most important for you to accept the offer?

- 1. There is nothing valuable behind the password.
- 2. You do not need the password from any other machine.
- **✅ 3. The passwords in your browser are protected from others.**
- 4. The password is so entropic that you would not be able to remember it.

> 💡 **Explanation:** If someone else can access your browser they see all your saved passwords. This is the critical security condition.

### Q3: The instructions concerning the use of a password can be condensed into five prohibitions: Do not (i) show, (ii) tell, (iii) save, (iv) allow to age, (v) recycle. In the case of a personal password, you must not bargain on some points, whereas you can do it on others. Which of the following mentions first a prohibition that you must not and then one that you can relax?

- **✅ 1. (ii) & (iii)**
- 2. (iii) & (iv)
- 3. (i) & (ii)
- 4. (iv) & (v)

> 💡 **Explanation:** You must NEVER tell your password (ii). But you CAN save it (iii) in a trusted password manager. Option 3 wrong - both show and tell cannot be relaxed.

### Q4: Which of the following is generally the most dangerous with passwords? The user

- **✅ 1. uses the same password in several places.**
- 2. selects a password with low entropy.
- 3. never changes his password.
- 4. writes the password on paper.

> 💡 **Explanation:** Password reuse is most dangerous because one breach compromises ALL accounts sharing that password - credential stuffing attacks.

### Q5: It has been said of the password that it should be treated like your own toothbrush. How many of the following password-related features does this statement represent? (i) Entropy, (ii) usability, (iii) keeping it for personal use only, (iv) changing it often enough.

- 1. none
- **✅ 2. two**
- 3. all
- 4. one

> 💡 **Explanation:** A toothbrush represents: (iii) personal use only - never share it, and (iv) change it often enough. It does NOT represent entropy (i) or usability (ii). Exactly two features.

---

## Page 20: Cookie {#page-20}

### Q1: With the exception of the cookie itself or other cookies, a web browsing cookie cannot break

- 1. the availability of your files, but it may break their confidentiality or integrity.
- 2. the integrity of your files, but it may break their confidentiality.
- **✅ 3. either the integrity or confidentiality of your files.**
- 4. the confidentiality of your files, but it may break their integrity.

> 💡 **Explanation:** A cookie cannot directly access or modify files on your computer. It cannot break the confidentiality or integrity of your local files.

### Q2: In the original and still most common usage, the web browsing cookie is created by the

- 1. browser, which gets it back from the server without changes.
- 2. browser, but the server modifies it and sends back to the browser.
- 3. web server, but the browser modifies it and sends back to the server.
- **✅ 4. web server, which gets it back from the browser without changes.**

> 💡 **Explanation:** The web server creates the cookie, sends it to the browser, the browser stores it, and sends it back unchanged with subsequent requests.

### Q3: The purpose of a web browsing cookie is to transmit to the web server information

- **✅ 1. that is the same as the server has earlier transmitted to the browser.**
- 2. collected by the browser from other servers.
- 3. about browser security settings.
- 4. collected by the browser from the user.

> 💡 **Explanation:** The cookie sends back to the server the same information the server originally sent - this is how the server maintains session state.

---

## Page 21: CAPTCHA {#page-21}

### Q1: CAPTCHA or "Completely Automated Public Turing test to tell Computers and Humans Apart"

- 1. is a security mechanism that, by definition, cannot be attacked by human force.
- **✅ 2. is an example of authentication that does not involve identification.**
- 3. cannot be interpreted as authentication.
- 4. is authentication based on either knowledge, ownership, or location.

> 💡 **Explanation:** CAPTCHA proves you are human without knowing WHO you are - no identification involved. Option 1 wrong - CAPTCHAs can be attacked by human farms and AI. Option 3 wrong - it IS authentication.

### Q2: Why would you bother to write your email address in the form of john.doePOISTA@MINUTtuni.fi? ("Poista minut" is Finnish for "Remove me".)

- **✅ 1. To avoid spammers harvesting your real address so easily.**
- 2. To announce your desire to get away from a mailing list.
- 3. To hide your domain (location) from automatic scanning by authorities.
- 4. To prevent excessive contacts from others than those who know Finnish.

> 💡 **Explanation:** This is email address obfuscation. Spambots scan for email patterns. Adding POISTA MINUT breaks the pattern so bots cannot harvest it. A human reader understands to remove those words.

---

## Page 22: Crypto Procedures {#page-22}

### Q1: Cryptographic primitives are mainly

- 1. such basic mechanisms, that can be found in all cryptographic algorithms and protocols.
- 2. prime numbers from which keys are formed.
- **✅ 3. procedures that a cryptology practitioner can view like indivisible blocks.**
- 4. base numbers that generate all other numbers in modular arithmetic.

> 💡 **Explanation:** Primitives are the basic building blocks of cryptographic systems treated as indivisible black boxes - like hash functions, block ciphers, stream ciphers.

### Q2: Which of the following is mainly a task that can be performed using a cryptographic protocol?

- 1. Secure storage of an encryption key.
- 2. Converting an email message to ciphertext.
- 3. Generating an encryption key based on good random numbers.
- **✅ 4. Agreeing on an encryption key.**

> 💡 **Explanation:** A cryptographic protocol involves multiple parties exchanging messages. Key agreement (Diffie-Hellman) requires communication between parties. The other options are algorithm tasks.

### Q3: Investigate the argument: Crypto algorithms are either symmetric encryption algorithms, or asymmetric encryption or signature algorithms. It is

- **✅ 1. false because the list lacks algorithms that do not use a key.**
- 2. true, because the digital signature that has been introduced alongside the traditional encryption is done with an encryption-like algorithm, which is not symmetric.
- 3. false, but the inclusion of steganography would make the claim true.
- 4. true, because it does not make sense to mention separately decryption or signature verification.

> 💡 **Explanation:** Hash functions are cryptographic algorithms but use no key. The statement is false because it omits keyless algorithms.

### Q4: Which of the following is not covered by the concept of a cryptographic algorithm?

- 1. message authentication code
- **✅ 2. challenge-response method**
- 3. hash function
- 4. random number generator

> 💡 **Explanation:** Challenge-response is a PROTOCOL not an algorithm - it involves multiple steps and parties exchanging messages.

### Q5: An implementation of ____ that contains all the necessary software, protocols, algorithms and keys, is called ______ .

- 1. a cryptosystem, cryptanalysis
- **✅ 2. cryptography, a cryptosystem**
- 3. cryptanalysis, cryptology
- 4. cryptology, cryptanalysis

> 💡 **Explanation:** Cryptography is the practice/science. A cryptosystem is a complete implementation. Cryptanalysis is breaking cryptography.

### Q6: The term plaintext

- 1. means ASCII-text without any formatting or markup.
- 2. is used for human readable sequences of characters.
- 3. refers to documents that do not contain any executable content like macros.
- **✅ 4. is a synonym for cleartext and the concept is used in cryptography.**

> 💡 **Explanation:** Plaintext means unencrypted data - does not need to be human-readable or ASCII. It is the data BEFORE encryption. Its counterpart is ciphertext.

---

## Page 23: Keys and Chunks or Streams {#page-23}

### Q1: There are two classes of symmetric cryptographic methods, the _____ ciphers process the plaintext a fixed number of bits (e.g. 128) at a time and the _____ ciphers proceed bit by bit.

- 1. chunk, flow
- **✅ 2. block, stream**
- 3. stop-go, continuous
- 4. packet, flux

> 💡 **Explanation:** Block ciphers process fixed-size blocks. Stream ciphers process data bit by bit. Options 1, 3 and 4 use non-standard terminology.

### Q2: Encryption is a method for protecting confidentiality of data, and it requires a key, that

- 1. is different for each message or chunk of data.
- 2. has the same length in bits as the data.
- 3. can be sent along the message as such because the communicating parties must have agreed on such parameters for the algorithm that makes it secret.
- **✅ 4. can even be computed from a human-memorable password if the data is not to be sent anywhere but protected in local storage.**

> 💡 **Explanation:** This describes password-based encryption using key derivation functions. Option 3 wrong - sending the key with the message defeats encryption.

### Q3: As a result of doubling the length of a symmetric encryption key, the time required for a brute force attack, if originally T, becomes

- 1. 4xT.
- 2. Tk where k > 2.
- 3. at least 2xT, but less than 4xT.
- **✅ 4. T2.**

> 💡 **Explanation:** If original key is n bits, brute force tries 2^n = T keys. Doubling to 2n bits means 2^(2n) = T squared. Doubling key LENGTH squares the brute force effort.

### Q4: Stream ciphers are one of the two classes of symmetric cryptographic methods, the other one being

- 1. cryptographic hashing.
- 2. public key cryptography.
- 3. authentication algorithms.
- **✅ 4. block algorithms.**

> 💡 **Explanation:** The two classes of symmetric cryptographic methods are stream ciphers and block ciphers. The other options are separate categories.

---

## Page 24: One-time Pad, DES, AES {#page-24}

### Q1: The most popular symmetric cryptosystem currently is

- **✅ 1. AES.**
- 2. DES.
- 3. RSA.
- 4. TLS.

> 💡 **Explanation:** AES replaced DES and is now the most widely used symmetric encryption algorithm. DES is obsolete. RSA is asymmetric. TLS is a protocol.

### Q2: DES, the Digital Encryption Standard, was for a long time the state-of-the-art method to

- 1. carry out the exchange of cryptographic keys.
- 2. authenticate the owner of the secret encryption key.
- **✅ 3. produce confidentiality of communications.**
- 4. transform digital images to contain a watermark.

> 💡 **Explanation:** DES was the standard symmetric encryption algorithm for keeping communications confidential. Eventually broken due to its short 56-bit key length.

### Q3: What is a one-time pad?

- 1. A cascading network attack type where the intruder uses each compromised computer only once to evade detection.
- **✅ 2. A single-use key together with the method of using it to encrypt and decrypt a message.**
- 3. A method of generating truly random numbers.
- 4. A tablet computer equipped with spying software used for attacks by "forgetting" it at a place where the victim can find it.

> 💡 **Explanation:** A one-time pad is theoretically unbreakable - the key is truly random, at least as long as the message, and used only ONCE. Provides perfect secrecy.

### Q4: AES is a

- 1. stream cipher.
- **✅ 2. block cipher.**
- 3. a mode of using DES.
- 4. symmetric method for authenticated exchange of secrets.

> 💡 **Explanation:** AES is a symmetric block cipher processing data in 128-bit blocks using keys of 128, 192 or 256 bits. Option 1 wrong - AES is a block cipher not a stream cipher.

---

## Page 25: Public Key {#page-25}

### Q1: A public key for ______ is a cryptographic analogue of a physical key available to anyone that can be used to shut a padlock on a box in such a way that it can only be opened with a different key.

- **✅ 1. encryption**
- 2. decryption
- 3. signature verification
- 4. digital signature

> 💡 **Explanation:** Anyone can use the public key to lock (encrypt) data, but only the private key holder can unlock (decrypt) it - like a padlock anyone can snap shut but only one key opens.

### Q2: A public key for ______ is a cryptographic analogue of a physical key available to anyone that can be used to open a padlock on a box after someone has locked it with a different private key.

- 1. encrypting secret messages
- 2. decrypting secret messages
- **✅ 3. verifying signatures**
- 4. signing messages

> 💡 **Explanation:** In digital signatures anyone can verify (open/check) using the public key what the sender locked with their private key.

### Q3: Which of the following does not apply?

- **✅ 1. If the RSA decryption exponent is d, then the RSA decryption program has to do d-1 modular multiplications.**
- 2. The RSA decryption algorithm does not need to know the two prime numbers that make up the modulus n.
- 3. An RSA signature can be made even if you do not know the two prime numbers that make up the public modulus n.
- 4. If you raise a number x smaller than the RSA modulus n to the public RSA exponent (e) and then to the private exponent (d) and only then reduce the result modulo n, you obtain x.

> 💡 **Explanation:** FALSE. RSA uses square-and-multiply fast exponentiation requiring approximately log(d) multiplications, NOT d-1.

### Q4: Which of the following does not apply?

- 1. If you raise a number x smaller than the RSA modulus n to the private RSA exponent (d) and then to the public exponent (e) and only then reduce the result modulo n, you obtain x.
- 2. The RSA decryption algorithm does not need to know the two prime numbers that make up the modulus n.
- **✅ 3. An RSA signature cannot be made unless you know the two prime numbers that make up the public modulus n.**
- 4. RSA encryption can be calculated for a larger number than the public modulus, but decryption still produces a smaller number than the modulus.

> 💡 **Explanation:** FALSE. RSA signing only requires private exponent d and modulus n - NOT the prime factors p and q. Once d is known, signing works with just d and n.

---

## Page 26: Hash {#page-26}

### Q1: Which of the following is typical of checksums intended to prevent typing errors in the input of character strings that mainly contain digits?

- 1. They are calculated by summing the digits.
- **✅ 2. They are calculated from all the characters.**
- 3. They are always placed at the beginning of the original string.
- 4. They contain several characters which are scattered in non-adjacent positions in the orginal string.

> 💡 **Explanation:** A checksum must cover all characters to detect errors anywhere in the input.

### Q2: The cryptographic hash value calculated from a message represents the entire message in the sense that

- 1. it cannot be obtained from any other message.
- **✅ 2. it is very unlikely to find any other message with the same hash.**
- 3. small changes in the message change the value only slightly.
- 4. a change at any location in the message can be corrected based on the hash.

> 💡 **Explanation:** This describes collision resistance. Option 3 is opposite of truth - avalanche effect means LARGE hash changes from small message changes.

### Q3: How does a cryptographic hash value protect a message?

- 1. It ensures that the message is not a copy of any previous message.
- 2. The message cannot be interpreted without knowing the hash value.
- **✅ 3. The message cannot be changed without breaking the correspondence with the value.**
- 4. The message cannot be changed without knowing the hash value.

> 💡 **Explanation:** Any change to the message produces a completely different hash, revealing tampering. This is integrity protection.

### Q4: Which of the following does not apply to keyed cryptographic hashes?

- 1. They can be used to authenticate a message.
- **✅ 2. They are also called Cyclic Redundancy Checks.**
- 3. Keyless hash functions such as SHA-1 can be used to calculate them.
- 4. They must be well over 24 bits long.

> 💡 **Explanation:** CRCs are non-cryptographic error detection checksums - completely different from keyed cryptographic hashes (MACs).

### Q5: Assume H is a good cryptographic hash function. How many bit strings m of length 100 are there approximately that give an H(m) that starts with 40 zeros?

- 1. most likely none
- 2. 225
- 3. 240
- **✅ 4. 260**

> 💡 **Explanation:** There are 2^100 possible 100-bit strings. Probability = 1/2^40. Expected count = 2^100 / 2^40 = 2^60. Answer is 2^60 (written as 260).

### Q6: Assume H is a good cryptographic hash function. How many bit strings m of length 40 are there approximately that give an H(m) that starts with 100 zeros?

- **✅ 1. most likely none**
- 2. 225
- 3. 240
- 4. 260

> 💡 **Explanation:** There are only 2^40 possible 40-bit strings. Probability = 1/2^100. Expected count = 2^40 / 2^100 = essentially zero. Input space is far too small.

---

## Page 27: The Most Common Protocols {#page-27}

### Q1: IPsec

- **✅ 1. provides mechanisms for authentication and encryption.**
- 2. only authenticates clients toward a server.
- 3. can only be deployed with IPv6.
- 4. provides mechanisms for nonrepudiation.

> 💡 **Explanation:** IPsec provides both authentication and encryption at the IP layer. Works with both IPv4 and IPv6. Does not primarily provide non-repudiation.

### Q2: What does key exchange mean in the sentence: "Key exchange is one of the most important cryptographic protocols."?

- 1. A public key is revoked and replaced by a new one which is authenticated.
- 2. The parties authenticate their public keys to each other.
- 3. An old symmetric key is being updated.
- **✅ 4. A symmetric key is agreed upon.**

> 💡 **Explanation:** Key exchange means two parties agreeing on a shared symmetric key without it ever being transmitted directly.

### Q3: The protocol and program of choice for setting up a window for command line use of a remote computer is called

- 1. TLS.
- **✅ 2. SSH.**
- 3. PGP.
- 4. IMAP.

> 💡 **Explanation:** SSH (Secure Shell) is the standard protocol for securely connecting to a remote computer's command line. TLS is transport security. PGP is email encryption. IMAP is email retrieval.

### Q4: TLS is a very common cryptographic protocol. The T in its name comes from the word

- 1. trusted.
- 2. transmission.
- **✅ 3. transport.**
- 4. total.

> 💡 **Explanation:** TLS stands for Transport Layer Security. It replaced SSL (Secure Sockets Layer).

---

## Page 28: Nature and Devices {#page-28}

### Q1: What is true about fires?

- 1. The risk of fire is the foremost reason why backups must be made.
- 2. Fire detection and suppression must be taken care of by the ordinary facilities management and there are no special demands from the information technology point of view.
- **✅ 3. It is not so much the computers that catch fire, but the batteries and their charging are causing risks especially in mobile devices.**
- 4. The increase in processing power of computers and in their memory sizes has come with the elevated risk of overheating and fire.

> 💡 **Explanation:** Lithium-ion batteries in mobile devices are a genuine fire risk. Option 2 wrong - IT systems have special fire suppression requirements (gas not water).

### Q2: The digital cash bits on a smart card cannot be extracted from the card and copied for reuse. Only one of the following is a reasonable, though partial, explanation. Which?

- 1. During the payment transaction a cryptographically protected label is attached to them indicating that they have been used.
- 2. The card's file system is randomized.
- 3. All cards are manufactured to be different in such a way that the bits copied from one to another would not work the same way.
- **✅ 4. The card's processor only transacts with processors of the right kind and even then spending happens inside the card.**

> 💡 **Explanation:** Smart cards have a secure processor - the actual cryptographic operations happen inside the tamper-resistant chip and bits never leave the card in a usable form.

---

## Page 29: Filtering {#page-29}

### Q1: A demilitarized zone, DMZ, means a part of an organization's network that

- **✅ 1. resides between two filtering devices.**
- 2. has no workstations.
- 3. does not contain any facilities for virus-scanning, intrusion detection or logging.
- 4. has no servers.

> 💡 **Explanation:** A DMZ sits between two firewalls - one facing the internet and one facing the internal network. It hosts public-facing servers.

### Q2: Which of the following should mainly be able to filter packets like a dedicated firewall machine does?

- 1. modem
- 2. switch
- **✅ 3. router**
- 4. repeater

> 💡 **Explanation:** Routers operate at Layer 3 and can perform packet filtering based on IP addresses and port numbers. Modems convert signals, switches operate at Layer 2, repeaters amplify signals.

### Q3: Which of the following can a packet filter do: (i) anti-virus, (ii) delete oversized email attachments, (iii) encrypt or decrypt?

- **✅ 1. none of these**
- 2. only (iii)
- 3. only (i) and (ii)
- 4. only (ii) and (iii)

> 💡 **Explanation:** A packet filter operates at the network layer inspecting only headers. It cannot inspect content for viruses, read email attachments, or encrypt/decrypt traffic.

### Q4: How does a packet filter react to TCP and UDP port numbers?

- 1. It doesn't take them into account.
- **✅ 2. It rejects the packet if either number is invalid.**
- 3. It returns the packet if either number is invalid.
- 4. It passes through the packet if and only if those numbers are equal.

> 💡 **Explanation:** A packet filter rejects packets if either port number is invalid (not allowed per the rules). Option 1 wrong - packet filters definitely use port numbers.

### Q5: The tasks of a packet filter may include

- 1. user authentication.
- 2. anti-virus.
- 3. spam filtering.
- **✅ 4. writing logs.**

> 💡 **Explanation:** Packet filters CAN log traffic. They CANNOT perform user authentication, anti-virus scanning or spam filtering - those require deep content inspection.

---

## Page 30: Secure Connection {#page-30}

### Q1: One possible action of IPsec is to add to each data packet a field with

- 1. a signature calculated from the packet with the sender's key.
- 2. the sender's public key and its certificate.
- 3. a certificate calculated from header fields of the packet.
- **✅ 4. a hash calculated from the packet and a symmetric key.**

> 💡 **Explanation:** IPsec Authentication Header adds an HMAC - a hash calculated from packet contents using a shared symmetric key. Provides integrity and authentication.

### Q2: IPsec encrypts data packets on a protocol layer that is

- 1. the same as TLS.
- 2. in some functions the same, in some lower than in TLS.
- **✅ 3. lower than in TLS.**
- 4. higher than in TLS.

> 💡 **Explanation:** IPsec operates at Layer 3 (Network layer). TLS operates between Layer 4 (Transport) and Application layer. Layer 3 is lower than Layer 4.

### Q3: If a remote user's machine fails to authenticate the target machine, it may be a wrong one and all of the following are potential threats. Which one is the most serious? The target machine can

- **✅ 1. give the user's authentication information to an attacker.**
- 2. be a bot network server.
- 3. send malware to the user's machine.
- 4. target the user with a DoS attack.

> 💡 **Explanation:** If the user connects to a fake server and enters credentials, the attacker captures them - compromising all services using those credentials. More serious than malware or DoS.

### Q4: Because TLS works below the application layer, it

- **✅ 1. does not know what kind of data it protects.**
- 2. is unable to protect a password entered in the browser as it travels to the server.
- 3. can connect applications on several servers to protect a complex business transaction for the client.
- 4. cannot establish an encrypted connection between two applications.

> 💡 **Explanation:** TLS encrypts whatever the application sends without knowing whether it is HTTP, email, FTP or any other type.

### Q5: Which of the following is more important in a VPN that must meet the security needs of the network connection for a remote worker?

- 1. virtuality
- **✅ 2. encryption**
- 3. transparent functionality of the network
- 4. tunneling, and hiding the endpoints

> 💡 **Explanation:** Encryption is the fundamental security requirement - protecting data as it travels over the public internet.

---

## Page 31: Mobile Authentication {#page-31}

### Q1: In the cell phone system the network authenticates the phone or actually the SIM card in it. What mechanism is in place here?

- 1. One-time password
- **✅ 2. Challenge-response method, with a symmetric key system.**
- 3. Fixed password
- 4. Challenge-response method that applies a public key system.

> 💡 **Explanation:** GSM uses challenge-response with a shared symmetric key stored on the SIM card. No public key system involved.

### Q2: The mobile phone systems 2G, 3G, 4G, ... authenticate the subscriber

- 1. with a PKI based protocol.
- 2. by using an authenticated Diffie-Hellman key exchange.
- 3. by encrypting and transmitting a shared secret from the SIM card to the network.
- **✅ 4. by applying a cryptographic hash function to a shared secret**

> 💡 **Explanation:** Mobile networks apply a cryptographic hash/HMAC to a shared secret combined with a random challenge. The shared secret is NEVER transmitted over the network.

### Q3: What is the relation between WiFi, WLAN, VLAN and WPA?

- **✅ 1. WPA is the protection method for a WLAN, which uses the WiFi protocol, and can be one of the VLANs in an organization's network.**
- 2. WPA is an advanced version of WiFi, which is one type of WLAN. VLAN is not at all related to the others.
- 3. WLAN is a wireless version of a VLAN, which is an implementation of the WiFi protocol, and any VLAN can be protected by WPA.
- 4. WiFi is the protection method for a WLAN, which is a form of a VLAN. WPA is not related to the others.

> 💡 **Explanation:** WiFi is the protocol. WLAN is the network type using WiFi. WPA is the security protocol protecting the WLAN. VLAN is a separate network segmentation concept.

### Q4: WPA is a cryptographic protocol for protecting wireless communications. Which of the following: (i) NFC, (ii) ZigBee, (iii) Bluetooth, (iv) WiFi?

- 1. (i) - (iv)
- **✅ 2. (iv)**
- 3. (iii)
- 4. (ii) - (iv)

> 💡 **Explanation:** WPA protects WiFi/WLAN only. NFC, ZigBee and Bluetooth have their own separate security mechanisms.

---

## Page 32: Start Running Programs {#page-32}

### Q1: What is not used as a term for the act of a computer system making a new entry to the log file of active users?

- 1. log in
- **✅ 2. pass in**
- 3. sign in
- 4. log on

> 💡 **Explanation:** Log in, sign in and log on are all standard terms. Pass in is not used for this purpose.

### Q2: Login is an exceptional program in the sense that

- 1. its actions are completely reversible, by virtue of the logout program.
- **✅ 2. it need not know whether it is launched by a legitimate user or an attacker.**
- 3. it cannot complete without a human user acting in person.
- 4. it can be run, "retried", over and over again without any change in the system.

> 💡 **Explanation:** Login must handle authentication requests from anyone - it cannot pre-screen who is attempting. Failed logins can trigger lockouts and other system changes.

### Q3: Regardless of which programs you are running on your computer the most essential protections for your computing is provided by

- 1. the memory resident malware scanner.
- **✅ 2. the operating system.**
- 3. those device drivers that are running at any moment.
- 4. all filtering programs that are run by the operating system, the firewall at a minimum.

> 💡 **Explanation:** The operating system is the foundation of all security - controls hardware access, manages memory isolation, enforces permissions. Everything else depends on the OS.

### Q4: Sandboxing is a security mechanism, where

- **✅ 1. new untrusted software is run in a disconnected test system to check it for malicious behaviour.**
- 2. untrusted code, which is not signed, is continuously restricted from accessing system resources.
- 3. a new version of software is tested by scrutinizing all memory accesses it does that the earlier version did not do.
- 4. a new version of software is installed into a production system but is kept from doing anything that the earlier version did not do.

> 💡 **Explanation:** Sandboxing isolates untrusted code in a restricted environment where it cannot affect the rest of the system.

### Q5: Single sign-on

- **✅ 1. can provide access to multiple resources, but it is only valid for a limited session or duration.**
- 2. is an insecure mechanism because it confuses the granting of access rights with the authentication phase.
- 3. provides access to any one resource for a single use.
- 4. is an unnecessary mechanism because one-time authentication can be handled already at the authorization stage.

> 💡 **Explanation:** SSO allows a user to authenticate once and access multiple systems. Session is time-limited for security.

### Q6: Single sign-on is characterized by the fact that

- 1. the user has a different ID for different services, even though the password he or she must remember for them is the same.
- 2. there is no need to store log information about the use and operation of the services elsewhere than in a centralized login service.
- 3. the password a user must remember is different for different services, even if the username for each is the same.
- **✅ 4. security is improved compared to a user having the same password for multiple services.**

> 💡 **Explanation:** With SSO users only need one strong password rather than reusing the same password across multiple services.

---

## Page 33: A Spectrum of Storage Issues {#page-33}

### Q1: A database is an organized collection of data. The organization usually means delicate dependencies between parts of that collection, and this is a main reason for specific security requirements for databases. More than the other options, such requirements concern

- 1. your Google search results.
- **✅ 2. the data that your (future) employer has about its employees.**
- 3. the photo album on your phone.
- 4. your medical records, that you collect in a folder of papers.

> 💡 **Explanation:** Employee databases contain structured sensitive personal data with complex dependencies. A folder of papers is not a database. A photo album has minimal structured dependencies.

### Q2: Why do you sometimes need to write zeros and ones over and over again on a file on disk?

- 1. So that the magnetic field is reset enough and the new data written in the same place is better kept intact.
- 2. To ensure that the code of any computer virus is erased from the disk.
- 3. So that the deterioration of the magnetic field over time does not affect the integrity of the data stored on the disk.
- **✅ 4. So that the earlier contents of the file could not be read at all.**

> 💡 **Explanation:** Overwriting multiple times is secure deletion. Magnetic storage retains traces of previous data even after deletion - multiple overwrites make recovery extremely difficult.

### Q3: Password salt is

- 1. the small variation allowed in password systems that use very long passphrases.
- 2. the method to make fixed passwords variable by requiring to insert time dependent punctuations.
- 3. the secret constant that a password checking procedure uses as an input together with the password.
- **✅ 4. the random number stored without encryption together with each hashed password.**

> 💡 **Explanation:** A salt is a random value added to each password before hashing, stored in plaintext alongside the hash. It ensures two users with the same password have different hashes, defeating rainbow table attacks.

---
