# Cyber Security 1 — Exam 1 Study Guide

**Tampere University | Comp.Sec.100-02 | Maso Pages 1–33**

> **Exam 1 format:** 32 MCQ questions | Passing: 22/32 correct | Time: 1 hour | Wrong answer: −1/3 point

---

## Table of Contents

- [Page 1: First Concepts — Cyber, Security, CIA, DoS, DDoS](#maso-page-1)
- [Page 2: Some Victims and Attackers — Script Kiddies, Identity Theft, Social Engineering](#maso-page-2)
- [Page 3: Not Only Breaking Ciphers — Eavesdropper, Dictionary Attack, Backdoor, Ransomware, Passive Attack](#maso-page-3)
- [Page 4: Not Only Viruses — Malware, Trojan Horse, Macro Virus, Exposure, Buffer Overflow, Zero-day](#maso-page-4)
- [Page 5: Networked Robots and Men — Botnet, Man in the Middle](#maso-page-5)
- [Page 6: Risk and Three A-Properties — Assurance, Authentication, Availability, Risk](#maso-page-6)
- [Page 7: Policies and Models Do Not Protect — Access Control, Accountability, Non-repudiation, Defence in Depth](#maso-page-7)
- [Page 8: Credentials — 2FA, Credentials, Data Ownership, Shared Secret](#maso-page-8)
- [Page 9: Special Basic Protections — CA, Challenge-Response, Digital Signature, Firewall, Separation of Duties, Steganography](#maso-page-9)
- [Page 10: Repair and Punishment — Backup, Integrity, Privacy, GDPR](#maso-page-10)
- [Page 11: More Than GDPR — Data Protection, GDPR, PCI-DSS](#maso-page-11)
- [Page 12: Anonymity — Anonymity, Privacy, Pseudonym](#maso-page-12)
- [Page 13: IPR — Intellectual Property, Copyright, DRM](#maso-page-13)
- [Page 14: Social Media — Fake News, Background Checks, Misinformation Responsibility](#maso-page-14)
- [Page 15: Ethics — Ethics in InfoSec, Anonymity of Browsing, TOR](#maso-page-15)
- [Page 16: Security Issues on Personal Devices — Cookie, Entropy, Firewall, USB](#maso-page-16)
- [Page 17: Risk Management, Policy — Security Policy, Risk Analysis, Risk Treatments](#maso-page-17)
- [Page 18: Non-disclosure, but Public Keys — NDA, PKI](#maso-page-18)
- [Page 19: Password — Entropy, Password Rules](#maso-page-19)
- [Page 20: Cookie — Web Browser Cookies](#maso-page-20)
- [Page 21: CAPTCHA — CAPTCHA, Spam, Email Obfuscation](#maso-page-21)
- [Page 22: Crypto Procedures — Cryptography, Primitive, Algorithm, Protocol, Plaintext](#maso-page-22)
- [Page 23: Keys and Chunks or Streams — Encryption, Key Length, Block Cipher, Stream Cipher](#maso-page-23)
- [Page 24: One-time Pad, DES, AES — Encryption, AES, One-time Pad](#maso-page-24)
- [Page 25: Public Key — Private Key, Public Key, RSA](#maso-page-25)
- [Page 26: Hash — Checksum, Hash, Keyed Hash](#maso-page-26)
- [Page 27: Most Common Protocols — KEX, SSH, TLS, IPsec](#maso-page-27)
- [Page 28: Nature and Devices — Fire, Smart Card](#maso-page-28)
- [Page 29: Filtering — DMZ, Packet Filter](#maso-page-29)
- [Page 30: Secure Connection — IPsec, TLS, VPN, Remote Use](#maso-page-30)
- [Page 31: Mobile Authentication — Cellular, WiFi, WLAN, WPA](#maso-page-31)
- [Page 32: Start Running Programs — Login, Single Sign-on, Operating System, Sandbox](#maso-page-32)
- [Page 33: A Spectrum of Storage Issues — Database, Overwriting, Password Salt](#maso-page-33)

---

## Maso Page 1: First Concepts — Cyber, Security, CIA, DoS, DDoS {#maso-page-1}

### Q1: What is required of an attack to be regarded as a cyber attack?

✅ **Correct Answer:** 1. The target relies on an electronic information system.

💡 **Explanation:** A cyber attack simply requires that the target is an electronic information system. Nation state involvement, substantial loss and large groups are common but NOT necessary.

### Q2: Denial of service is a term...

✅ **Correct Answer:** 3. That refers to a service not being able to operate because of malicious requests.

💡 **Explanation:** DoS means malicious traffic overwhelms the service. Option 2 is too broad. Option 1 is too specific. Option 4 describes admin action not an attack.

### Q3: What makes a DoS a distributed DoS?

✅ **Correct Answer:** 4. The attacking traffic comes to the server from several computers simultaneously.

💡 **Explanation:** Distributed means attack traffic originates FROM many sources simultaneously. Option 1 confuses many hackers with many computers.

### Q4: The term attack vector...

✅ **Correct Answer:** 3. Refers to the method of an attack — one that happened or is possible.

💡 **Explanation:** Attack vector is the method or path used in an attack. Not the attack itself, not the attacker's view of defenses, not a list of vulnerabilities.

### Q5: Confidentiality is one of the three basic CIA goals...

✅ **Correct Answer:** 3. But it is usually not sufficient without integrity and availability.

💡 **Explanation:** All three CIA goals work together. Confidentiality alone is insufficient.

---

## Maso Page 2: Some Victims and Attackers — Script Kiddies, Identity Theft, Social Engineering {#maso-page-2}

### Q1: Script kiddie — what is typical from a defender's perspective?

✅ **Correct Answer:** 1. Essentially similar scripts to several other attackers.

💡 **Explanation:** Script kiddies use the same ready-made tools so attacks are recognizable and blockable.

### Q2: Attackers called script kiddies are characterized by...

✅ **Correct Answer:** 1. Using scripts written by others.

💡 **Explanation:** Script kiddies use attack tools written by more skilled hackers without understanding how they work.

### Q3: Identity theft...

✅ **Correct Answer:** 1. Happens when someone maliciously uses identifying data of another person.

💡 **Explanation:** Identity theft requires malicious intent. Can happen without financial loss.

### Q4: How many user-spread entities are NOT direct risks to computing: spam, hoax, ransomware, meme virus, Nigerian letter, troll?

✅ **Correct Answer:** 1. 4

💡 **Explanation:** Ransomware is a direct risk. Hoax, meme virus, Nigerian letter and troll are NOT direct computing risks. That gives 4 entities.

### Q5: Which description gives the best coverage for social engineering?

✅ **Correct Answer:** 4. Exercising the art of influencing people to act against their security policy.

💡 **Explanation:** Social engineering is the broad concept of manipulating people psychologically. Options 1, 2 and 3 are specific techniques not the full concept.

### Q6: Successful impersonation means that...

✅ **Correct Answer:** 4. Somebody/something has been cheated to act as if in contact with someone else than the attacker.

💡 **Explanation:** Impersonation means fooling someone into thinking they deal with a trusted party. About deception not identity assignment.

---

## Maso Page 3: Not Only Breaking Ciphers — Eavesdropper, Dictionary Attack, Backdoor, Ransomware, Passive Attack {#maso-page-3}

### Q1: Attacker who attempts to know conversation contents without being a legitimate party?

✅ **Correct Answer:** 4. Eavesdropper.

💡 **Explanation:** Eavesdropper listens without being a legitimate party. Honest but curious is a legitimate party trying to learn more than they should.

### Q2: What is a dictionary attack?

✅ **Correct Answer:** 2. A sophisticated brute-force attack against passwords, taking into account that they were invented by users of natural languages.

💡 **Explanation:** Dictionary attack tries common words instead of random combinations. Option 3 describes rainbow tables.

### Q3: Backdoor?

✅ **Correct Answer:** 4. Is an intentionally made or maliciously installed method of bypassing normal authentication or encryption.

💡 **Explanation:** A backdoor bypasses normal security controls. Option 2 describes Trojan horse payload.

### Q4: Ransomware is?

✅ **Correct Answer:** 2. A program that makes your data inaccessible to you and asks for money to restore access.

💡 **Explanation:** Ransomware encrypts files and demands payment. Data is locked not destroyed.

### Q5: How can an attack be passive?

✅ **Correct Answer:** 3. A passive attack does not interfere with the integrity or availability of the victim's computing.

💡 **Explanation:** A passive attack only observes data without modifying anything. Eavesdropping is the classic example.

---

## Maso Page 4: Not Only Viruses — Malware, Trojan Horse, Macro Virus, Exposure, Buffer Overflow, Zero-day {#maso-page-4}

### Q1: Malware that does not replicate, pretends to be legitimate but does something else?

✅ **Correct Answer:** 4. A Trojan horse.

💡 **Explanation:** Trojan horse disguises itself as legitimate but performs malicious actions. Does NOT replicate unlike virus or worm.

### Q2: Common feature of all malicious programs?

✅ **Correct Answer:** 1. They are capable of similar actions as other programs in their running environment.

💡 **Explanation:** All malware runs in the same environment as legitimate software and can do anything that environment allows.

### Q3: A macro virus is malware that...

✅ **Correct Answer:** 4. Runs on many different platforms because it is interpreted by its host program.

💡 **Explanation:** Macro viruses run in host programs like Word or Excel. Cross-platform ability is the key characteristic.

### Q4: Term for a vulnerability meaning something coming out of covering?

✅ **Correct Answer:** 3. Exposure.

💡 **Explanation:** Exposure is the security term for a vulnerability that reveals something hidden. Disclosure means revealing intentionally.

### Q5: Attack causing data written outside allowed memory area?

✅ **Correct Answer:** 3. Buffer overflow.

💡 **Explanation:** Buffer overflow occurs when a program writes more data than a buffer can hold, spilling into adjacent memory.

### Q6: The term zero-day applies to...

✅ **Correct Answer:** 3. A vulnerability in software not yet exploited but found and kept secret by a malicious party.

💡 **Explanation:** Zero-day vulnerability is unknown to the vendor — they have had zero days to fix it.

---

## Maso Page 5: Networked Robots and Men — Botnet, Man in the Middle {#maso-page-5}

### Q1: Which fits most poorly to the concept of a bot network?

✅ **Correct Answer:** 1. Users of machines on the bot network have agreed to work with the network administrator.

💡 **Explanation:** A botnet is built from compromised machines whose owners do NOT know. If users agreed it would be a legitimate distributed network not a botnet.

### Q2: Man in the middle is an attack type where...

✅ **Correct Answer:** 2. The attacker or his process relays modified messages between two unknowing communication parties.

💡 **Explanation:** In MITM the attacker positions between two parties, intercepts and can modify messages. Option 1 describes a rootkit. Option 3 describes a cryptographic attack.

### Q3: A botnet is...

✅ **Correct Answer:** 2. A group of dispersed, compromised machines controlled remotely for illicit purposes.

💡 **Explanation:** A botnet is compromised computers controlled by an attacker without owners' knowledge. Used for DDoS, spam, credential theft.

---

## Maso Page 6: Risk and Three A-Properties — Assurance, Authentication, Availability, Risk {#maso-page-6}

### Q1: Assurance is just part of information security, namely...

✅ **Correct Answer:** 3. Evidence that security mechanisms are efficient.

💡 **Explanation:** Assurance is confidence or evidence that security measures actually work. Not a synonym for authentication or accountability.

### Q2: Authentication is the...

✅ **Correct Answer:** 4. Process of verifying an identity.

💡 **Explanation:** Authentication verifies that someone is who they claim to be. Option 1 describes identification. Option 2 describes authorization. Option 3 describes an access management decision.

### Q3: Availability protects from some but not all — how many are excluded from: DoS, fire, flood, unauthorized transaction, unreadable backup tape?

✅ **Correct Answer:** 4. 3

💡 **Explanation:** Fire, flood and unauthorized transaction are excluded. Fire and flood are physical/disaster threats. Unauthorized transaction is an integrity issue. So 3 are excluded.

### Q4: Which coupling best defines risk?

✅ **Correct Answer:** 1. Threat and vulnerability.

💡 **Explanation:** Risk = Threat x Vulnerability. Without a vulnerability a threat cannot succeed. Without a threat a vulnerability does not matter.

---

## Maso Page 7: Policies and Models Do Not Protect — Access Control, Accountability, Non-repudiation, Defence in Depth {#maso-page-7}

### Q1: Access control means...

✅ **Correct Answer:** 3. Measures, usually automatic, taken to decide whether access to a resource must be granted or denied, based on a policy.

💡 **Explanation:** Access control is the enforcement mechanism. Option 2 describes policy. Option 4 is too broad. Option 1 is too narrow.

### Q2: Accountability is close to Authenticity combined with which CIA goal?

✅ **Correct Answer:** 1. I (Integrity)

💡 **Explanation:** Accountability requires authenticity combined with integrity of audit records. Without integrity of logs, accountability is meaningless.

### Q3: How many of 7 terms mean roughly the same as Security control: mechanism, model, policy, service, protection, countermeasure, safeguard?

✅ **Correct Answer:** 4. 5

💡 **Explanation:** Mechanism=yes, model=NO, policy=NO, service=yes, protection=yes, countermeasure=yes, safeguard=yes. That gives 5.

### Q4: The strategy of forming layers of protection around an asset is known as...

✅ **Correct Answer:** 2. Defence-in-depth.

💡 **Explanation:** Defence-in-depth uses multiple layers so if one fails others still protect. Other options are not standard security terms.

### Q5: Non-repudiation as a security objective means that...

✅ **Correct Answer:** 4. The person to whom the information relates has no grounds for claiming that there is no connection.

💡 **Explanation:** Non-repudiation means a party cannot deny having sent or received a message. Evidence is so strong that denial is impossible.

### Q6: Non-repudiation is...

✅ **Correct Answer:** 1. A special security goal.

💡 **Explanation:** Non-repudiation is a security goal ensuring parties cannot deny their actions. It sits alongside the CIA triad as a separate special goal.

---

## Maso Page 8: Credentials — 2FA, Credentials, Data Ownership, Shared Secret {#maso-page-8}

### Q1: Which counts as two factor authentication?

✅ **Correct Answer:** 4. A PIN and a hard token.

💡 **Explanation:** 2FA requires two DIFFERENT factor types: something you know (PIN), something you have (hard token). Option 1: both something you have. Option 2: username is not a factor. Option 3: both something you know.

### Q2: Collections of data a person can use to prove identity?

✅ **Correct Answer:** 4. Credentials.

💡 **Explanation:** Credentials are the data used to prove identity. Attributes are characteristics. Certificates are a specific type. Shared secrets are a specific authentication mechanism.

### Q3: Decisions on who can access certain data are best made by...

✅ **Correct Answer:** 1. Data owner.

💡 **Explanation:** The data owner knows the sensitivity and value of their data best. This is the principle behind discretionary access control.

### Q4: Shared secret usually refers to...

✅ **Correct Answer:** 1. A result of protocols like IKE (Internet Key Exchange) of IPsec.

💡 **Explanation:** A shared secret is a value known only to communicating parties, established through key exchange protocols like IKE.

---

## Maso Page 9: Special Basic Protections — CA, Challenge-Response, Digital Signature, Firewall, Separation of Duties, Steganography {#maso-page-9}

### Q1: One task of a certification authority is...

✅ **Correct Answer:** 4. To publish a list of revoked certificates or provide a service that returns the certificate status.

💡 **Explanation:** CA tasks include issuing, signing and managing certificate revocation through CRL or OCSP. CAs do NOT maintain private keys.

### Q2: Challenge-response is a protocol such that...

✅ **Correct Answer:** 4. A challenges B to respond with something that no one else than A — and possibly B itself — would be able to produce.

💡 **Explanation:** Challenge-response sends an unpredictable challenge only the legitimate party can answer using their secret.

### Q3: A digital signature is made with...

✅ **Correct Answer:** 4. A hash function and an asymmetric cryptoalgorithm.

💡 **Explanation:** Digital signature: hash the message then encrypt with private key. Recipient decrypts with public key and compares hashes.

### Q4: At what phase of a product's life cycle is it most expensive to improve security?

✅ **Correct Answer:** 1. Implementation.

💡 **Explanation:** The later in the development lifecycle you fix security the more expensive it is. Implementation is the latest stage among the options.

### Q5: What does a firewall prevent from functioning in the way they were intended to?

✅ **Correct Answer:** 4. Packets.

💡 **Explanation:** A firewall inspects and filters network packets. Ports, IP addresses and protocols are rule attributes but packets are what get blocked.

### Q6: Which security concept is violated by one person inserting vendors AND paying them?

✅ **Correct Answer:** 3. Separation of duties.

💡 **Explanation:** Separation of duties requires critical tasks be divided among different people so no single person can commit fraud alone.

### Q7: Steganography is...

✅ **Correct Answer:** 2. An art of embedding data into a larger quantity of other data.

💡 **Explanation:** Steganography hides a secret message within ordinary data like images or audio. Message is hidden not encrypted. Different from digital watermarking.

---

## Maso Page 10: Repair and Punishment — Backup, Integrity, Privacy, GDPR {#maso-page-10}

### Q1: Which statement about backups is true?

✅ **Correct Answer:** 2. Removable flash memories are suitable as backup media.

💡 **Explanation:** Flash drives are valid backup media. Option 1 wrong — printing IS valid for some data. Option 3 wrong — weekly backups are better than none. Option 4 wrong — incremental copies only copy changes.

### Q2: Why is off-site backup important?

✅ **Correct Answer:** 4. Prevent the loss of data in the event of a fire.

💡 **Explanation:** Off-site backup protects against physical disasters that destroy both primary data and on-site backups simultaneously.

### Q3: Most concrete concept for repairing broken integrity?

✅ **Correct Answer:** 4. Redundancy.

💡 **Explanation:** Redundancy means having extra copies or checksums that allow detection and restoration of corrupted data.

### Q4: If your personal data is unduly disclosed by an EU service...

✅ **Correct Answer:** 3. The responsible company may have to pay a fine of millions of euros.

💡 **Explanation:** Under GDPR, fines up to 20 million euros or 4% of global annual turnover. Company is responsible even if attacker is not caught.

---

## Maso Page 11: More Than GDPR — Data Protection, GDPR, PCI-DSS {#maso-page-11}

### Q1: The central meaning of data protection is in protecting...

✅ **Correct Answer:** 2. The information that individuals disclose to different data collectors.

💡 **Explanation:** Data protection is about protecting personal information that individuals share with organizations.

### Q2: GDPR defines several roles but NOT the role of data...

✅ **Correct Answer:** 2. Object.

💡 **Explanation:** GDPR defines: data subject, data controller, data processor. Data object is a technical database term not a GDPR legal concept.

### Q3: GDPR mainly covers...

✅ **Correct Answer:** 2. The duties of organizations when they handle data from individuals.

💡 **Explanation:** GDPR primarily places obligations on organizations. Not just cross-border exchange. Not about encryption standards.

### Q4: PCI-DSS is...

✅ **Correct Answer:** 3. Is, as its name says, a standard created by an industry branch.

💡 **Explanation:** PCI-DSS was created by major card brands (Visa, Mastercard, Amex, Discover, JCB) not by a government. Industry standard not a law.

---

## Maso Page 12: Anonymity — Anonymity, Privacy, Pseudonym {#maso-page-12}

### Q1: Anonymity has different degrees depending on...

✅ **Correct Answer:** 3. What data should not be disclosed and to whom.

💡 **Explanation:** Anonymity depends on WHAT information should be hidden AND WHO it should be hidden from. Country and age are irrelevant.

### Q2: Privacy is synonymous to...

✅ **Correct Answer:** 3. None of these.

💡 **Explanation:** Privacy is distinct from secrecy, anonymity and privilege. Privacy is the right to control your own personal information.

### Q3: Pseudonym is...

✅ **Correct Answer:** 4. An artificial name that replaces the real name of a user.

💡 **Explanation:** A pseudonym is a false name used instead of a real name. Not a filesystem term. Not inherently part of an attack.

---

## Maso Page 13: IPR — Intellectual Property, Copyright, DRM {#maso-page-13}

### Q1: Copyright is originally a property of...

✅ **Correct Answer:** 2. The creators of an artefact.

💡 **Explanation:** Copyright belongs to the creator by default. Publishers may acquire rights through contracts but do not own copyright originally.

### Q2: One purpose of DRM is...

✅ **Correct Answer:** 1. To provide access control to digital media for protection of copyrights.

💡 **Explanation:** DRM controls how digital content can be accessed, copied and distributed. Option 2 describes anti-circumvention laws. Option 3 wrong — DRM restricts not promotes access.

### Q3: What is NOT a way to protect intellectual property?

✅ **Correct Answer:** 1. Privacy regulations.

💡 **Explanation:** Privacy regulations like GDPR protect personal data not intellectual property. DRM, patents and licensing are all genuine IP protection mechanisms.

---

## Maso Page 14: Social Media — Fake News, Background Checks, Misinformation Responsibility {#maso-page-14}

### Q1: What can go wrong when including social media links in a job application?

✅ **Correct Answer:** 2. The recruiter follows what is linked to those postings, and finds something unfavourable of you.

💡 **Explanation:** Your social media may contain posts or connections that create a negative impression. Following public links is not a privacy offense.

### Q2: What kind of update is poorly taken care of in social media?

✅ **Correct Answer:** 1. Rectifying of fake news or alternative truths.

💡 **Explanation:** Social media spreads content quickly but is very slow to correct misinformation. False information stays up and is rarely retracted.

### Q3: What kind of update is usually poorly handled?

✅ **Correct Answer:** 1. Links to sites that have published new pages that correct earlier mistakes in their news.

💡 **Explanation:** Corrections to previously shared false information are almost never propagated. Original posts remain unchanged.

### Q4: Who is responsible if you share something legal but untrue that causes harm?

✅ **Correct Answer:** 2. You, without conditions.

💡 **Explanation:** If you share false information that causes harm you bear responsibility whether you created it or reshared it.

---

## Maso Page 15: Ethics — Ethics in InfoSec, Anonymity of Browsing, TOR {#maso-page-15}

### Q1: Ethics is an important topic in information systems...

✅ **Correct Answer:** 1. And some aspects of it extending to the area of information security include treatment of privacy and IPR.

💡 **Explanation:** Ethics in information security covers privacy, IPR, responsible disclosure and fair use. Option 2 too narrow. Option 3 wrong — ethics plays a major role. Option 4 wrong — ethical hacking is just one aspect.

### Q2: What is NOT a topic of ethical considerations?

✅ **Correct Answer:** 3. Wasting your own and others' time by writing in social media long explanations of questionable quality.

💡 **Explanation:** This is a matter of quality and courtesy but not a genuine ethical dilemma in information security. Options 1, 2 and 4 all involve real ethical questions.

### Q3: If you need to browse the internet anonymously...

✅ **Correct Answer:** 2. The TOR network is an option you can seriously consider.

💡 **Explanation:** TOR is a legitimate and legal tool routing traffic through multiple encrypted layers. Option 1 wrong — public machines may log activity. Option 3 wrong — private mode only prevents local browser history. Option 4 wrong — TOR and VPNs are legal in Finland.

---

## Maso Page 16: Security Issues on Personal Devices — Cookie, Entropy, Firewall, USB {#maso-page-16}

### Q1: You get logged in automatically next day without entering credentials — what can you infer?

✅ **Correct Answer:** 4. The site uses a login cookie that persists even if the browser is not running.

💡 **Explanation:** A persistent login cookie stored on your computer is sent automatically when you revisit the site. Browsers do not send passwords automatically.

### Q2: USB stick with 10-digit keyboard, longest passcode is 10 digits — worst case attempts?

✅ **Correct Answer:** 1. 10^10

💡 **Explanation:** You chose only 10-digit codes so attacker needs to try all 10-digit combinations. Each position has 10 values (0-9) giving 10^10. Option 2 wrong — attacker only tries 10-digit codes. Option 3 wrong — attacker attacks the passcode not the AES key.

### Q3: A personal computer firewall is typically...

✅ **Correct Answer:** 2. One process among others.

💡 **Explanation:** On a personal computer a firewall is a software process running alongside other processes. Not hardware on the network card. Not an accessory on the power cord.

### Q4: Which USB connection has the least information security risk?

✅ **Correct Answer:** 3. Charging the new camping shower you just bought from a Chinese web shop.

💡 **Explanation:** A simple water pump only needs power and has no data capability. Option 1 has document malware risk. Option 2 risks juice jacking. Option 4 risks compromise despite IT check.

---

## Maso Page 17: Risk Management, Policy — Security Policy, Risk Analysis, Risk Treatments {#maso-page-17}

### Q1: What control mechanisms can be left out of risk analysis?

✅ **Correct Answer:** 3. Mechanisms that do not control threats to the system under consideration.

💡 **Explanation:** Risk analysis should only include controls relevant to the threats being analyzed. Controls addressing threats outside the system scope are irrelevant.

### Q2: Which does NOT need to be considered in risk analysis?

✅ **Correct Answer:** 1. How much is invested in information security in competing companies.

💡 **Explanation:** What competitors spend on security is irrelevant to your own risk analysis. Your analysis is about YOUR assets, YOUR threats and YOUR controls.

### Q3: Overall risk is reduced if...

✅ **Correct Answer:** 4. The value of an asset is found to be smaller than before.

💡 **Explanation:** Risk = Threat x Vulnerability x Asset Value. If an asset is worth less than previously estimated the real risk is genuinely lower.

### Q4: Alice implements security controls to protect email — this is...

✅ **Correct Answer:** 1. Risk mitigation.

💡 **Explanation:** Risk mitigation means taking active steps to reduce risk by implementing controls. The four risk treatments are: mitigation, acceptance, transference and avoidance.

---

## Maso Page 18: Non-disclosure, but Public Keys — NDA, PKI {#maso-page-18}

### Q1: Usual purpose of a non-disclosure agreement?

✅ **Correct Answer:** 2. To prevent an employee or visitor from revealing sensitive information of an organization.

💡 **Explanation:** An NDA is a legal contract binding a person to keep organizational information confidential. Option 1 describes data protection/GDPR. Option 3 describes a classification policy. Option 4 describes an encryption policy.

### Q2: Basic goal of a public key infrastructure is to...

✅ **Correct Answer:** 2. Bind the public key to the entity to which the key belongs.

💡 **Explanation:** PKI creates a trusted link between a public key and the identity of its owner. Option 1 wrong — private and public keys are already mathematically linked. Options 3 and 4 describe structural features not the basic goal.

### Q3: A certificate for K is generated when...

✅ **Correct Answer:** 1. Someone else uses his private key for a signature that binds K and the identity of B.

💡 **Explanation:** A certificate is created when a trusted third party (CA) uses its OWN private key to sign a binding between public key K and the identity of B. The someone else is the CA not B.

---

## Maso Page 19: Password — Entropy, Password Rules {#maso-page-19}

### Q1: Most important for security question/answer from authentication point of view?

✅ **Correct Answer:** 2. The entropy of the answer.

💡 **Explanation:** From an authentication perspective the answer must be unpredictable — high entropy means hard to guess. The question is often visible to attackers so its entropy matters less.

### Q2: Most important condition for accepting browser password save?

✅ **Correct Answer:** 3. The passwords in your browser are protected from others.

💡 **Explanation:** If someone else can access your browser they see all your saved passwords. This is the critical security condition.

### Q3: First a prohibition you MUST NOT relax, then one you CAN relax?

✅ **Correct Answer:** 1. (ii) and (iii)

💡 **Explanation:** You must NEVER tell your password to anyone (ii). But you CAN save your password (iii) in a trusted password manager.

### Q4: Most dangerous password behavior?

✅ **Correct Answer:** 1. Uses the same password in several places.

💡 **Explanation:** Password reuse is most dangerous because one breach compromises ALL accounts sharing that password — credential stuffing attacks.

### Q5: How many features does the toothbrush analogy represent?

✅ **Correct Answer:** 2. Two.

💡 **Explanation:** A toothbrush represents: (iii) personal use only — never share it, and (iv) change it often enough. Does NOT represent entropy (i) or usability (ii).

---

## Maso Page 20: Cookie — Web Browser Cookies {#maso-page-20}

### Q1: A web browsing cookie cannot break...

✅ **Correct Answer:** 3. Either the integrity or confidentiality of your files.

💡 **Explanation:** A cookie is a small piece of data stored in the browser — it cannot directly access or modify files on your computer. It affects your session and web data not your local file system.

### Q2: In original usage, a cookie is created by...

✅ **Correct Answer:** 4. The web server, which gets it back from the browser without changes.

💡 **Explanation:** The web server creates the cookie, sends it to the browser, the browser stores it, and sends it back unchanged with subsequent requests. This allows the server to maintain session state.

### Q3: Purpose of a web browsing cookie is to transmit to the server information...

✅ **Correct Answer:** 1. That is the same as the server has earlier transmitted to the browser.

💡 **Explanation:** The cookie sends back to the server the same information the server originally sent. This is how the server maintains state.

---

## Maso Page 21: CAPTCHA — CAPTCHA, Spam, Email Obfuscation {#maso-page-21}

### Q1: CAPTCHA is...

✅ **Correct Answer:** 2. Is an example of authentication that does not involve identification.

💡 **Explanation:** CAPTCHA proves you are human without knowing WHO you are (no identification). Option 1 wrong — CAPTCHAs can be attacked by human farms and AI. Option 3 wrong — it IS a form of authentication.

### Q2: Why write email as john.doePOISTA@MINUTtuni.fi?

✅ **Correct Answer:** 1. To avoid spammers harvesting your real address so easily.

💡 **Explanation:** This is email address obfuscation. Spambots scan web pages for email patterns. Adding Finnish words POISTA MINUT (Remove me) breaks the standard email pattern so bots cannot harvest it.

---

## Maso Page 22: Crypto Procedures — Cryptography, Primitive, Algorithm, Protocol, Plaintext {#maso-page-22}

### Q1: Cryptographic primitives are mainly...

✅ **Correct Answer:** 3. Procedures that a cryptology practitioner can view like indivisible blocks.

💡 **Explanation:** Primitives are the basic building blocks of cryptographic systems — like hash functions, block ciphers, stream ciphers. They are treated as indivisible black boxes combined to build larger protocols.

### Q2: Which is mainly a task performed using a cryptographic protocol?

✅ **Correct Answer:** 4. Agreeing on an encryption key.

💡 **Explanation:** A cryptographic protocol involves multiple parties exchanging messages to achieve a goal. Key agreement (like Diffie-Hellman) requires communication between parties.

### Q3: Crypto algorithms are either symmetric, asymmetric or signature — true or false?

✅ **Correct Answer:** 1. False because the list lacks algorithms that do not use a key.

💡 **Explanation:** Hash functions are cryptographic algorithms but use no key. The statement is false because it omits keyless algorithms.

### Q4: Which is NOT covered by the concept of a cryptographic algorithm?

✅ **Correct Answer:** 2. Challenge-response method.

💡 **Explanation:** Challenge-response is a PROTOCOL not an algorithm — it involves multiple steps and parties exchanging messages.

### Q5: Implementation of ____ containing all software, protocols, algorithms and keys is called ____.

✅ **Correct Answer:** 2. Cryptography, a cryptosystem.

💡 **Explanation:** Cryptography is the practice/science. A cryptosystem is a complete implementation containing all necessary components.

### Q6: The term plaintext...

✅ **Correct Answer:** 4. Is a synonym for cleartext and the concept is used in cryptography.

💡 **Explanation:** Plaintext in cryptography means unencrypted data. It is the data BEFORE encryption. Its counterpart is ciphertext.

---

## Maso Page 23: Keys and Chunks or Streams — Encryption, Key Length, Block Cipher, Stream Cipher {#maso-page-23}

### Q1: Two classes of symmetric cryptographic methods — blank and blank ciphers.

✅ **Correct Answer:** 2. Block, stream.

💡 **Explanation:** Block ciphers process plaintext in fixed-size blocks (e.g. 128 bits at a time). Stream ciphers process data bit by bit.

### Q2: Encryption requires a key that...

✅ **Correct Answer:** 4. Can even be computed from a human-memorable password if the data is not to be sent anywhere but protected in local storage.

💡 **Explanation:** This describes password-based encryption. Key derivation functions (KDF) convert passwords into encryption keys.

### Q3: Doubling symmetric key length — brute force time T becomes...

✅ **Correct Answer:** 4. T squared.

💡 **Explanation:** If original key is n bits, brute force tries 2^n = T keys. Doubling to 2n bits means 2^(2n) = (2^n)^2 = T squared. Doubling key LENGTH squares the brute force effort.

### Q4: Stream ciphers — the other class of symmetric methods is...

✅ **Correct Answer:** 4. Block algorithms.

💡 **Explanation:** The two classes of symmetric cryptographic methods are stream ciphers and block ciphers.

---

## Maso Page 24: One-time Pad, DES, AES — Encryption, AES, One-time Pad {#maso-page-24}

### Q1: Most popular symmetric cryptosystem currently?

✅ **Correct Answer:** 1. AES.

💡 **Explanation:** AES (Advanced Encryption Standard) replaced DES and is now the most widely used symmetric encryption algorithm worldwide. DES is obsolete. RSA is asymmetric. TLS is a protocol.

### Q2: DES was for a long time the state-of-the-art method to...

✅ **Correct Answer:** 3. Produce confidentiality of communications.

💡 **Explanation:** DES was the standard symmetric encryption algorithm. Eventually broken due to its short 56-bit key length.

### Q3: What is a one-time pad?

✅ **Correct Answer:** 2. A single-use key together with the method of using it to encrypt and decrypt a message.

💡 **Explanation:** A one-time pad is a theoretically unbreakable encryption method where the key is truly random, at least as long as the message, and used only ONCE. Provides perfect secrecy.

### Q4: AES is a...

✅ **Correct Answer:** 2. Block cipher.

💡 **Explanation:** AES is a symmetric block cipher processing data in 128-bit blocks using keys of 128, 192 or 256 bits. Option 1 wrong — AES is a block cipher not a stream cipher.

---

## Maso Page 25: Public Key — Private Key, Public Key, RSA {#maso-page-25}

### Q1: Public key for _____ is like a physical key that can SHUT (lock) a padlock?

✅ **Correct Answer:** 1. Encryption.

💡 **Explanation:** In asymmetric encryption anyone can use the public key to lock (encrypt) data, but only the private key holder can unlock (decrypt) it.

### Q2: Public key for _____ is like a physical key that can OPEN a padlock locked with a private key?

✅ **Correct Answer:** 3. Verifying signatures.

💡 **Explanation:** In digital signatures the sender signs with their private key and anyone can verify using the public key.

### Q3: Which does NOT apply about RSA? (first set)

✅ **Correct Answer:** 1. If the RSA decryption exponent is d, then the RSA decryption program has to do d-1 modular multiplications.

💡 **Explanation:** FALSE. RSA uses square-and-multiply fast exponentiation requiring approximately log(d) multiplications, NOT d-1.

### Q4: Which does NOT apply about RSA? (second set)

✅ **Correct Answer:** 3. An RSA signature cannot be made unless you know the two prime numbers that make up the public modulus n.

💡 **Explanation:** FALSE. RSA signing only requires private exponent d and modulus n — NOT the prime factors p and q.

---

## Maso Page 26: Hash — Checksum, Hash, Keyed Hash {#maso-page-26}

### Q1: Typical of checksums for preventing typing errors in digit strings?

✅ **Correct Answer:** 2. They are calculated from all the characters.

💡 **Explanation:** A checksum must cover all characters in the string to detect errors anywhere in the input.

### Q2: Cryptographic hash represents the entire message in the sense that...

✅ **Correct Answer:** 2. It is very unlikely to find any other message with the same hash.

💡 **Explanation:** This describes collision resistance. Option 3 is opposite — avalanche effect means LARGE hash changes from small message changes.

### Q3: How does a cryptographic hash protect a message?

✅ **Correct Answer:** 3. The message cannot be changed without breaking the correspondence with the value.

💡 **Explanation:** Any change to the message produces a completely different hash, revealing tampering. This is integrity protection.

### Q4: Which does NOT apply to keyed cryptographic hashes?

✅ **Correct Answer:** 2. They are also called Cyclic Redundancy Checks.

💡 **Explanation:** CRCs are non-cryptographic error detection checksums — completely different from keyed cryptographic hashes (MACs).

### Q5: Bit strings of length 100 giving H(m) starting with 40 zeros?

✅ **Correct Answer:** 4. 2^60.

💡 **Explanation:** There are 2^100 possible 100-bit strings. Probability of hash starting with 40 zeros = 1/2^40. Expected count = 2^100 / 2^40 = 2^60.

### Q6: Bit strings of length 40 giving H(m) starting with 100 zeros?

✅ **Correct Answer:** 1. Most likely none.

💡 **Explanation:** There are only 2^40 possible 40-bit strings. Probability = 1/2^100. Expected count = 2^40 / 2^100 = essentially zero.

---

## Maso Page 27: Most Common Protocols — KEX, SSH, TLS, IPsec {#maso-page-27}

### Q1: IPsec...

✅ **Correct Answer:** 1. Provides mechanisms for authentication and encryption.

💡 **Explanation:** IPsec is a suite of protocols providing both authentication and encryption at the IP layer. Used in VPNs. Works with both IPv4 and IPv6.

### Q2: What does key exchange mean in cryptographic protocols?

✅ **Correct Answer:** 4. A symmetric key is agreed upon.

💡 **Explanation:** Key exchange means two parties agreeing on a shared symmetric key (like Diffie-Hellman) without it ever being transmitted directly.

### Q3: Protocol and program for remote command line use?

✅ **Correct Answer:** 2. SSH.

💡 **Explanation:** SSH (Secure Shell) is the standard protocol for securely connecting to a remote computer command line.

### Q4: The T in TLS stands for...

✅ **Correct Answer:** 3. Transport.

💡 **Explanation:** TLS stands for Transport Layer Security. It replaced SSL and secures communications at the transport layer.

---

## Maso Page 28: Nature and Devices — Fire, Smart Card {#maso-page-28}

### Q1: What is true about fires?

✅ **Correct Answer:** 3. It is not so much the computers that catch fire, but the batteries and their charging are causing risks especially in mobile devices.

💡 **Explanation:** Lithium-ion batteries in mobile devices are a genuine fire risk. IT systems have special fire suppression requirements (gas not water).

### Q2: Why cannot digital cash bits be extracted and copied from a smart card?

✅ **Correct Answer:** 4. The card processor only transacts with processors of the right kind and even then spending happens inside the card.

💡 **Explanation:** Smart cards have a secure processor that handles all transactions internally. Bits never leave the card in a usable form.

---

## Maso Page 29: Filtering — DMZ, Packet Filter {#maso-page-29}

### Q1: A DMZ means a part of an organization network that...

✅ **Correct Answer:** 1. Resides between two filtering devices.

💡 **Explanation:** A DMZ sits between two firewalls — one facing the internet and one facing the internal network. It hosts public-facing servers.

### Q2: Which should mainly be able to filter packets like a dedicated firewall?

✅ **Correct Answer:** 3. Router.

💡 **Explanation:** Routers operate at the network layer (Layer 3) and can perform packet filtering based on IP addresses and port numbers.

### Q3: What can a packet filter do: anti-virus, delete oversized attachments, encrypt/decrypt?

✅ **Correct Answer:** 1. None of these.

💡 **Explanation:** A packet filter operates at the network layer inspecting only packet headers. It cannot inspect content for viruses, read email attachments, or encrypt/decrypt traffic.

### Q4: How does a packet filter react to TCP and UDP port numbers?

✅ **Correct Answer:** 4. It passes through the packet if and only if those numbers are equal.

💡 **Explanation:** A packet filter uses port numbers to decide — it passes packets whose port numbers match the configured allowed ports in the rules.

### Q5: Tasks of a packet filter may include...

✅ **Correct Answer:** 4. Writing logs.

💡 **Explanation:** Packet filters CAN log traffic. They CANNOT perform user authentication, anti-virus scanning or spam filtering.

---

## Maso Page 30: Secure Connection — IPsec, TLS, VPN, Remote Use {#maso-page-30}

### Q1: IPsec adds to each data packet a field with...

✅ **Correct Answer:** 4. A hash calculated from the packet and a symmetric key.

💡 **Explanation:** IPsec Authentication Header (AH) adds an HMAC — a hash calculated from packet contents using a shared symmetric key. Provides integrity and authentication.

### Q2: IPsec encrypts at a layer that is... compared to TLS?

✅ **Correct Answer:** 3. Lower than in TLS.

💡 **Explanation:** IPsec operates at Layer 3 (Network/IP layer). TLS operates between Layer 4 (Transport) and the Application layer. Layer 3 is lower than Layer 4.

### Q3: If user fails to authenticate target machine, which threat is most serious?

✅ **Correct Answer:** 1. Give the user authentication information to an attacker.

💡 **Explanation:** If the user connects to a fake server without authenticating it, the user enters credentials which the attacker captures. This compromises all services where those credentials are used.

### Q4: Because TLS works below the application layer, it...

✅ **Correct Answer:** 1. Does not know what kind of data it protects.

💡 **Explanation:** TLS encrypts whatever the application sends without knowing whether it is HTTP, email, FTP or any other type. It is transparent to the application protocol.

### Q5: What is more important in a VPN for remote worker security?

✅ **Correct Answer:** 2. Encryption.

💡 **Explanation:** The fundamental security requirement of a VPN for remote workers is encryption — protecting data as it travels over the public internet.

---

## Maso Page 31: Mobile Authentication — Cellular, WiFi, WLAN, WPA {#maso-page-31}

### Q1: What mechanism authenticates the SIM card in cellular networks?

✅ **Correct Answer:** 2. Challenge-response method, with a symmetric key system.

💡 **Explanation:** GSM and cellular networks use challenge-response authentication with a shared symmetric key stored on the SIM card. No public key system involved.

### Q2: How do 2G, 3G, 4G systems authenticate the subscriber?

✅ **Correct Answer:** 4. By applying a cryptographic hash function to a shared secret.

💡 **Explanation:** Mobile networks apply a hash/HMAC to a shared secret combined with a random challenge. The shared secret is NEVER transmitted. Cellular auth uses symmetric not PKI.

### Q3: Relation between WiFi, WLAN, VLAN and WPA?

✅ **Correct Answer:** 1. WPA is the protection method for a WLAN, which uses the WiFi protocol, and can be one of the VLANs in an organization network.

💡 **Explanation:** WiFi is the wireless networking protocol. WLAN is the network type. WPA is the security protocol. VLAN is a separate network segmentation concept.

### Q4: WPA protects which wireless technologies: NFC, ZigBee, Bluetooth, WiFi?

✅ **Correct Answer:** 2. (iv) WiFi only.

💡 **Explanation:** WPA was specifically designed to protect WiFi/WLAN communications only. NFC, ZigBee and Bluetooth all have their own separate security mechanisms.

---

## Maso Page 32: Start Running Programs — Login, Single Sign-on, Operating System, Sandbox {#maso-page-32}

### Q1: What is NOT used as a term for logging into a system?

✅ **Correct Answer:** 2. Pass in.

💡 **Explanation:** Log in, sign in and log on are all common synonymous terms. Pass in is not a standard term used for this purpose.

### Q2: Login is exceptional because...

✅ **Correct Answer:** 2. It need not know whether it is launched by a legitimate user or an attacker.

💡 **Explanation:** Login must handle authentication requests from anyone. It processes whatever credentials are presented and grants or denies access.

### Q3: Most essential protection for your computing is provided by...

✅ **Correct Answer:** 2. The operating system.

💡 **Explanation:** The operating system is the foundation of all security — it controls access to hardware, manages memory isolation, enforces permissions. Everything else depends on and runs within the OS.

### Q4: Sandboxing is a security mechanism where...

✅ **Correct Answer:** 1. New untrusted software is run in a disconnected test system to check it for malicious behaviour.

💡 **Explanation:** Sandboxing isolates untrusted code in a restricted environment. The sandbox limits what resources and system calls the code can access.

### Q5: Single sign-on...

✅ **Correct Answer:** 1. Can provide access to multiple resources, but it is only valid for a limited session or duration.

💡 **Explanation:** SSO allows a user to authenticate once and gain access to multiple systems. The session is time-limited for security.

### Q6: Single sign-on is characterized by...

✅ **Correct Answer:** 4. Security is improved compared to a user having the same password for multiple services.

💡 **Explanation:** With SSO users only need one strong password rather than reusing the same password across multiple services.

---

## Maso Page 33: A Spectrum of Storage Issues — Database, Overwriting, Password Salt {#maso-page-33}

### Q1: Specific security requirements for databases concern more than other options...

✅ **Correct Answer:** 2. The data that your (future) employer has about its employees.

💡 **Explanation:** Employee databases contain structured sensitive personal data with complex dependencies. A folder of papers is not a database. A photo album has minimal structured dependencies.

### Q2: Why write zeros and ones over and over again on a file on disk?

✅ **Correct Answer:** 4. So that the earlier contents of the file could not be read at all.

💡 **Explanation:** Overwriting data multiple times is a secure deletion technique. Magnetic storage retains traces of previous data even after deletion. Multiple overwrites make recovery extremely difficult.

### Q3: Password salt is...

✅ **Correct Answer:** 4. The random number stored without encryption together with each hashed password.

💡 **Explanation:** A salt is a random value added to each password before hashing, stored alongside the hashed password in plaintext. It ensures two users with the same password have different hashes, defeating rainbow table attacks.

---
