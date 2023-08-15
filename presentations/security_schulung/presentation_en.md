---
marp: false
theme: default
class: invert
style: |
  .columns {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 0.5rem;
  }
  .columns2 {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 3rem;
  }
  section ol {
    font-size: 25px;
  }
  @import 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css'
paginate: true  
---

<!--
_backgroundColor: #black
_color: white
-->
<!-- _paginate: skip -->

<div class="columns">

<div>

<img src="assets/white_occ.png" style="margin-bottom: 200px"/>

# Security Awareness Training

Carl Strömstedt


</div>
<div>
</div>
</div>

![bg](assets/titelbild.jpg)


---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Carl Strömstedt

- IT software developer
- Hobbies
  - Bouldering
  - Reading
  - Travel


![bg right:33%](assets/carl.jpg)

---
<!--
_backgroundColor: #0d3862
_color: white
-->


![bg center: 80%](assets/nzz.png)

---

<!-- 
_backgroundColor: #0d3862 
_color: white -->

# 3 Blocks

- ### Information Security
- ### Malware & Phishing
- ### Authentication & Behaviors

---

<!-- 
_backgroundColor: #0d3862 
_color: white 
-->
# Block 1
## Information Security

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# What is Information Security?

---


<!--
_backgroundColor: #0d3862
_color: white
-->

## Information Security

- Information security encompasses ensuring **confidentiality**, **integrity**, and **availability** of information.
- Information security is ensured when sufficient **technical**, **physical**, and **organizational** protective measures have been implemented.
- Information security is influenced, ensured, or improved by each individual.

---

<!--
_backgroundColor: #0d3862
_color: white
-->


<h1>
  <i class="fa-solid fa-mask fa-xl" style="margin-right: 15px"></i> Confidentiality
</h1>

<i class="fa-solid fa-pen-fancy fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Definition

Protection against unauthorized access to sensitive information to maintain privacy and confidentiality.

<i class="fa-solid fa-tools fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Example

The use of digital signatures guarantees that a document originates from a specific sender and remains unaltered.

---

<!--
_backgroundColor: #0d3862
_color: white
-->
<h1>
  <i class="fa-solid fa-file-shield fa-xl" style="margin-right: 15px"></i> Integrity
</h1>

<i class="fa-solid fa-pen-fancy fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Definition

Ensuring continuous access to information and resources to minimize interruptions and failures.

<i class="fa-solid fa-tools fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Example

Regular maintenance and redundant server infrastructure ensure constant accessibility of a website.

---

<!--
_backgroundColor: #0d3862
_color: white
-->
<h1>
  <i class="fa-solid fa-clock fa-xl" style="margin-right: 15px"></i> Availability
</h1>

<i class="fa-solid fa-pen-fancy fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Definition

Ensuring the constant accessibility of information and resources to minimize interruptions and failures.

<i class="fa-solid fa-tools fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Example

Regular maintenance and redundant server infrastructure ensure that a website is accessible at all times.

---

<!--
_backgroundColor: #0d3862
_color: white
-->

<h1 style="margin-bottom: -20px">
 Case studies
</h1>

1. An employee discovers an error in an approved protocol after a meeting. Rectifying this error would alter the content of the decision. Despite this, the employee makes the change, saves the modified protocol without informing colleagues, and without noting the change in the company repository.

2. A sales employee talks loudly about the details of an offer on a train. This discussion makes it possible for fellow passengers to know the affected company, key individuals, the scope, and the costs of the project.

3. Important business data becomes inaccessible due to an unplanned, short-notice maintenance window carried out by the IT service provider for software updates.

4. An employee clicks on a link in a message claiming they've won a lottery prize. They confirm the installation of a certificate in their browser to access the desired page. All data they send and receive is now decrypted, accessed, and altered by a third party for fraudulent purposes.


---

![bg](assets/case_study_1.png)

---

![bg](assets/case_study_1_solution.png)

---

![bg](assets/case_study_2.png)

---

![bg](assets/case_study_2_solution.png)

---

![bg](assets/case_study_3.png)

---

![bg](assets/case_study_3_solution.png)

---

![bg](assets/case_study_4.png)

---

![bg](assets/case_study_4_solution.png)


---

<!--
_backgroundColor: #0d3862
_color: white
-->

<h1 style="margin-bottom:20px; font-size:55px">
Beispiele für wertvolle und sensitive Informationen
</h1>

<div class="columns2" style="margin-left: 0px; padding-top: 75px">
<div>

<i class="fa-solid fa-credit-card fa-xl" style="font-size:100px"></i> 
<p style="margin-top: 40px; font-size: 40px">Payment data</p>


</div>
<div>
<i class="fa-solid fa-people-roof fa-xl" style="font-size:100px"></i>
<p style="margin-top: 40px; font-size: 40px">Personal data</p>


</div>
<div>

<i class="fa-solid fa-laptop-medical fa-xl" style="font-size: 100px"></i>
<p style="margin-top: 40px; font-size: 40px">Health data</p>

</div>
<div>


</div>

</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Motivation of Attackers

<div class="columns">
<div>

<h2>
  Economic <i class="fa-solid fa-sack-dollar fa-xl" style="margin-left: 15px"></i> 
</h2>

- Personal Enrichment
- Elimination of Competitors
- Enhancement of Market Position

</div>
<div>
<h2>
  Political <i class="fa-solid fa-check-to-slot fa-xl" style="margin-left: 15px"></i> 
</h2>

- Influencing Elections
- Causing Reputation Damage to Competitors
- Spreading Religious or Political Content

</div>
<div>

<h2>
  Personal <i class="fa-solid fa-user fa-xl" style="margin-left: 15px"></i> 
</h2>

- Validation
- "For the LULZ" (Amusement)
- Gaining Unfair Advantages

</div>
</div>

---


<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/vulnerability_1.png)

---

<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/vulnerability_2.png)


---

<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/vulnerability_3.png)

---

<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/vulnerability_4.png)


---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Classification of assets

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Asset requirements

Confidentiality <i class="fa-solid fa-mask fa-xl" style="margin-left:20px"></i> 

Integrity <i class="fa-solid fa-file-shield fa-xl" style="margin-left:20px"></i> 

Availability <i class="fa-solid fa-clock-rotate-left fa-xl" style="margin-left:20px"></i> 

---
<!--
_backgroundColor: #0d3862
_color: white
-->

# Classifications


<div class="columns">
<div>

<h2>
  Why?
</h2>

Helps us define guidelines

</div>
<div>
<h2>
  What do we classify?
</h2>

All data and assets

</div>
<div>

<h2>
  Which classifications do we use?
</h2>

- Top Secret
- Confidential
- Internal
- Public


</div>
</div>

<!--
Top secret usually only for companies that work within e.g.
pharmaceutical / medical industries or military
-->

---

<!--
_backgroundColor: #0d3862
_color: white
-->

<h1>
  Confidential <i class="fa-solid fa-shield fa-xl" style="margin-left: 15px"></i> 
</h1>

## Storage

<i class="fa-solid fa-lock fa-xl" style="margin-right:20px"></i> Only authorized personnel have access 

## Transport

<i class="fa-solid fa-lock fa-xl" style="margin-right:20px"></i> Only encrypted and not via phone

## Processing

<i class="fa-solid fa-binoculars fa-xl" style="margin-right:20px"></i> Copying not allowed & printing is monitored

---

<!--
_backgroundColor: #0d3862
_color: white
-->

<h1>
  Internal <i class="fa-solid fa-shield-halved fa-xl" style="margin-left: 15px"></i> 
</h1>

## Storage

<i class="fa-solid fa-building-circle-check fa-xl" style="margin-right:20px"></i> All within the company have access

## Transport

<i class="fa-solid fa-unlock fa-xl" style="margin-right:20px"></i>  Unencrypted exchange is allowed

## Processing

<i class="fa-solid fa-pencil fa-xl" style="margin-right:20px"></i> Changes, copying, and printing allowed as needed

---

<!--
_backgroundColor: #0d3862
_color: white
-->

<h1>
  Public <i class="fa-solid fa-people-group fa-xl" style="margin-left: 15px"></i> 
</h1>

## Storage

<i class="fa-solid fa-box-open fa-xl" style="margin-right:20px"></i> Everyone has access


## Transport

<i class="fa-solid fa-people-group fa-xl" style="margin-right:20px"></i> Any type of exchange is allowed

## Processing

<i class="fa-solid fa-binoculars fa-check" style="margin-right:20px"></i> Changes must be traceable

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Information security incidents

---

<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/incident_1.png)

---

<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/incident_2.png)

---

<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/incident_3.png)

---

<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/incident_4.png)

---

<!--
_backgroundColor: #cf7030
_color: white
-->

# Responding to a Security Incident



---

<!--
_backgroundColor: #cf7030
_color: white
-->


<i class="fa-solid fa-user-shield fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 15px"></i> Suspicions

- If you observe anything suspicious, act without hesitation.
- Our experts will thoroughly investigate the situation on your behalf.

<i class="fa-solid fa-exclamation-triangle fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 15px"></i> Reporting

- It's recommended to report via phone or create a support ticket.
- We're committed to assisting you and finding a resolution.

<i class="fa-solid fa-envelope fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 15px"></i> Forwarding

- Kindly forward suspicious phishing emails to support@open-circle.ch.
- You can enhance your report by attaching screenshots to the support ticket for added context.

<!--
Scheuhe nich davor zurrück dich dazu zu melden
-->


---

<!--
_backgroundColor: #187d4d
_color: white
-->


# How does Open Circle prevent inicidents?

<i class="fa-solid fa-window-maximize fa-2xl" style="margin-right:33px; margin-top: 25px; margin-bottom: 35px"></i> DNS-Filtering

<i class="fa-solid fa-envelope-open-text fa-2xl" style="margin-right:40px; margin-top: 25px; margin-bottom: 35px"></i>Spam-Filtering

<i class="fa-solid fa-sync fa-2xl" style="margin-right:40px; margin-top: 25px; margin-bottom: 35px"></i>Regular Server & Client Updates

<i class="fa-solid fa-user-shield fa-2xl" style="margin-right:25px; margin-top: 25px; margin-bottom: 35px"></i>2-Factor Authentication

<i class="fa-solid fa-user-pen fa-2xl" style="margin-right:20px; margin-top: 25px; margin-bottom: 35px"></i> Awareness Training

- Raise user awareness
- Promote threat awareness

<!--
Betonen dass wir vieles machen, aber schlussendlich ist es der User der den grössten unterschied macht

Darum diese Schulung
-->


---

<!--
_backgroundColor: #187d4d
_color: white
-->

# First block - Conclusions

---

<!--
_backgroundColor: #187d4d
_color: white
-->

# First block - Conclusions

<div class="columns">
<div>

## 3 security objectives

- Confidentiality
- Integrity
- Availability

</div>
<div>

## Risk

Secure vulnerabilities with protective measures

</div>
<div>

## 3 classifications

- Confidential
- Internal
- Public

</div>
<div>

## Security Incident

Feeling Uncertain? Suspicious?


<i class="fa-solid fa-arrow-right fa-xl" style="margin-right: 10px"></i> Report


</div>
</div>

<!-- 5 Minuten Pause
 -->


---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Block 2

## Malware



---

<!--
_backgroundColor: #0d3862
_color: white
-->


<div class="columns2" style="margin-left: 150px; padding-top: 75px">
<div>

<i class="fa-solid fa-virus-covid fa-xl" style="font-size:120px"></i> 
<p style="margin-top: 40px; font-size: 50px">Viruses</p>


</div>
<div>
<i class="fa-solid fa-horse fa-xl" style="font-size:120px"></i>
<p style="margin-top: 40px; font-size: 50px">Trojans</p>


</div>
<div>

<i class="fa-solid fa-user-secret fa-xl" style="font-size: 120px"></i>
<p style="margin-top: 40px; font-size: 50px">Spyware</p>

</div>
<div>

<i class="fa-solid fa-arrow-down-up-lock fa-xl" style="font-size: 120px"></i>
<p style="margin-top: 40px; font-size: 50px">Ransomware</p>
</div>

</div>


<!-- Zusammengesetztes Wort aus malicious (böse) software
Virus: häufigste Art, benötigt Userinteraktion  Danach selbstreplizierend. Wurm  Untergruppe von Virus (schlängelt sich durch Netzwerk)

Trojaner: Backdoor (hintertür) zieht weitere Malware nach oder stiehlt Daten

Spyware: Datendiebstal, oftmals lange unbemerkt

Ransomware: Deutlich auf Vormarsch  Cryptolocker Erpressung (Verschlüsselung)
 -->

 ---

 <!--
_backgroundColor: #0d3862
_color: white
-->

<h1>
  <i class="fa-solid fa-virus fa-xl" style="margin-right: 15px"></i> Viruses
</h1>

Malicious programs that attach to other files and can replicate themselves.

<i class="fa-solid fa-viruses fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Spread

Through infected files, email attachments, or infected websites.
<i class="fa-solid fa-house-chimney-crack fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Damage potential

Data destruction, system crashes, network propagation.

---

 <!--
_backgroundColor: #e74c3c
_color: white
-->
<h1>
  <i class="fa-solid fa-biohazard fa-xl" style="margin-right: 15px"></i> Case study: Stuxnet Virus
</h1>

<i class="fa-solid fa-virus-slash fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Stuxnet Virus

- Discovered in 2010
- A complex computer worm targeting industrial systems.

<i class="fa-solid fa-tools fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Ziel und Auswirkungen

- Mainly targeted Iranian nuclear reactors
- Manipulated control systems and caused damage to 1/5 of Irans reactors

---

 <!--
_backgroundColor: #e74c3c
_color: white
-->

<i class="fa-solid fa-user-secret fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Complexity

- Exploited zero-day vulnerabilities
- Utilized multiple attack vectors

<i class="fa-solid fa-shield-alt fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Lehren

- Demonstrates the potential for targeted attacks on critical infrastructure
- Emphasizes the importance of security awareness and protective measures

<!-- 
Stuxnet, discovered by Sergey Ulasen, initially spread via Microsoft Windows, and targeted Siemens industrial control systems.

Stuxnet has three modules: a worm that executes all routines related to the main payload of the attack; 

a link file that automatically executes the propagated copies of the worm; 

and a rootkit component responsible for hiding all malicious files and processes, to prevent detection of Stuxnet.[11] 

It is typically introduced to the target environment via an infected USB flash drive, thus crossing any air gap. The worm then propagates across the network, scanning for Siemens Step7 software on computers controlling a PLC

Stuxnet reportedly compromised Iranian PLCs, collecting information on industrial systems and causing the fast-spinning centrifuges to tear themselves apart.

PLC (Programmable Logic Controllers)
-->


---

<iframe width="1100" height="800" src="https://www.youtube.com/embed/7VgIayOpjEc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<!-- 
Stuxnet, discovered by Sergey Ulasen, initially spread via Microsoft Windows, and targeted Siemens industrial control systems.

Stuxnet has three modules: a worm that executes all routines related to the main payload of the attack; 

a link file that automatically executes the propagated copies of the worm; 

and a rootkit component responsible for hiding all malicious files and processes, to prevent detection of Stuxnet.[11] 

It is typically introduced to the target environment via an infected USB flash drive, thus crossing any air gap. The worm then propagates across the network, scanning for Siemens Step7 software on computers controlling a PLC

Stuxnet reportedly compromised Iranian PLCs, collecting information on industrial systems and causing the fast-spinning centrifuges to tear themselves apart.

PLC (Programmable Logic Controllers)
-->

---

 <!--
_backgroundColor: #0d3862
_color: white
-->

<h1>
  <i class="fa-solid fa-horse fa-xl" style="margin-right: 15px"></i> Trojans
</h1>

Malicious programs that disguise themselves as legitimate software to infiltrate systems unnoticed.

<i class="fa-solid fa-viruses fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Spread

Can spread through fake email attachments, infected downloads, or drive-by downloads.

<i class="fa-solid fa-house-chimney-crack fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Damage potential

Data theft, identity theft, complete system takeovers

---

 <!--
_backgroundColor: #0d3862
_color: white
-->

<h1>
  <i class="fa-solid fa-user-secret fa-xl" style="margin-right: 15px"></i> Spyware 
</h1>

Secretly gathers information about users and their activities.

<i class="fa-solid fa-viruses fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Spread

Through software bundling, infected links, or drive-by downloads.

<i class="fa-solid fa-house-chimney-crack fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Damage potential

Privacy breaches, identity theft, financial losses.

---

 <!--
_backgroundColor: #0d3862
_color: white
-->

<h1>
  <i class="fa-solid fa-arrow-down-up-lock fa-xl" style="margin-right: 15px"></i> Ransomware
</h1>

Locks or encrypts data, demands ransom for restoration.

<i class="fa-solid fa-viruses fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Spread

Through infected email attachments, exploit kits, or malicious downloads.

<i class="fa-solid fa-house-chimney-crack fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Damage potential

Data loss, financial losses, business interruptions.

---

![bg center: 80%](assets/blackcat.png)

<!-- link: https://www.microsoft.com/en-us/security/blog/2022/06/13/the-many-lives-of-blackcat-ransomware/
 -->

---

 <!--
_backgroundColor: #0d3862
_color: white
-->


# Attack components

What do attackers use for their attacks?

---


 <!--
_backgroundColor: #0d3862
_color: white
-->


# Technical aspects

- Drive-by Download
- Drive-by Installer
- Email Attachments
- Software Bundling

# Social aspects

- Social Engineering
---


 <!--
_backgroundColor: #0d3862
_color: white
-->


# Technical aspects

- Drive-by-Download <i class="fa-solid fa-globe fa-xl" style="margin-left: 15px"></i>
- Drive-by-Installer <i class="fa-solid fa-arrow-down fa-xl" style="margin-left: 15px"></i>
- Email Attachments <i class="fa-solid fa-envelope fa-xl" style="margin-left: 15px"></i>
- Software Bundling <i class="fa-solid fa-box fa-xl" style="margin-left: 15px"></i>

---


<!--
_backgroundColor: #0d3862
_color: white
-->
<h1>
  <i class="fa-solid fa-globe fa-xl" style="margin-right: 15px"></i> Drive-by-Download
</h1>


Automatic download of malware when visiting an infected website.

<i class="fa-solid fa-gears fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Mechanism

Exploiting security vulnerabilities in the browser or plugins to inject malicious code.

<i class="fa-solid fa-house-chimney-crack fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Risiks

Unnoticed infection, propagation of viruses, trojans, or ransomware.

---
<!--
_backgroundColor: #f4f1ec
_color: black
-->



![bg center: 70%](assets/drive_by_1.gif)

<!-- link: https://us.norton.com/blog/malware/what-are-drive-by-downloads
 -->

---

<!--
_backgroundColor: #f4f1ec
_color: black
-->


![bg center: 70%](assets/drive_by_2.png)

---
<!--
_backgroundColor: #0d3862
_color: white
-->
<h1>
  <i class="fa-solid fa-envelope fa-xl" style="margin-right: 15px"></i> Email Attachments
</h1>

Attachments that exploit vulnerabilities in software (such as document readers) when opened, to install malware.

<i class="fa-solid fa-viruses fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Mechanism

Exploiting software vulnerabilities, executing macros.

<i class="fa-solid fa-house-chimney-crack fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Risiken

Unnoticed infection, installation of rootkits, data theft.

---

<!--
_backgroundColor: #0d3862
_color: white
-->
<h1>
  <i class="fa-solid fa-box fa-xl" style="margin-right: 15px"></i> Software Bundling
</h1>

Malware is bundled with legitimate software and installed alongside it.

<i class="fa-solid fa-gears fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Mechanism

Users often do not notice the malware as it uses trusted software as a disguise.

<i class="fa-solid fa-house-chimney-crack fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Risiks

Unauthorized data access, spyware, trojan infections.

---

![bg](assets/drive_by_installer.png)

---


<!--
_backgroundColor: #0d3862
_color: white
-->
<h1>
  <i class="fa-solid fa-tree fa-xl" style="margin-right: 15px"></i> Rootkits
</h1>

Rootkits are malicious software that deeply infiltrates a computer system and gains access at various levels.

<i class="fa-solid fa-gears fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Mechanism

By accessing the system level, rootkits can acquire administrative privileges and compromise systems.

<i class="fa-solid fa-house-chimney-crack fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Risiks

Unauthorized data access, masking of malware.

---

<!--
_backgroundColor: #f4f1ec
_color: white
-->

![bg center: 60%](assets/rootkit.png)

---


<!--
_backgroundColor: #187d4d
_color: white
-->

<h1>
  <i class="fa-solid fa-shield-alt fa-xl" style="margin-right: 15px"></i> Protection against Malware
</h1>

<i class="fa-solid fa-arrow-rotate-left fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Software updates

Keep your operating system and all software up to date to protect against known security vulnerabilities.

<i class="fa-solid fa-envelope fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Caution with emails

Do not open email attachments or click on links from unknown or suspicious senders.

<i class="fa-solid fa-user-shield fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Behavioral Awareness

Be cautious when downloading files from the internet and avoid questionable websites.

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Social aspects

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Social Engineering

Manipulation of individuals by exploiting trust, curiosity, or pressure to reveal confidential information or perform unauthorized actions.

## Methoden

- Phishing
- Vishing (Phone)
- Pretexting (Faking identity)


---

<!--
_backgroundColor: #0d3862
_color: white
-->
<h1>
  <i class="fa-solid fa-fish fa-xl" style="margin-right: 15px"></i> Phishing
</h1>

Deception of users to steal confidential information such as passwords or financial data.

<i class="fa-solid fa-viruses fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Methoden

Fake emails, websites, or social media that appear genuine to build trust.

<i class="fa-solid fa-house-chimney-crack fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Gefahren

Identity theft, financial losses, unauthorized access to personal accounts.

---

<!--
_backgroundColor: #f4f1ec
_color: white
-->

![bg center: 90%](assets/phictionary_1.png)

---


<!--
_backgroundColor: #f4f1ec
_color: white
-->

![bg center: 90%](assets/phictionary_2.png)

---


<!--
_backgroundColor: #f4f1ec
_color: white
-->

![bg center: 90%](assets/phictionary_3.png)

---

<!--
_backgroundColor: #f4f1ec
_color: white
-->

![bg center: 90%](assets/phictionary_4.png)

---

<!--
_backgroundColor: #f4f1ec
_color: white
-->

![bg center: 90%](assets/phictionary_5.png)

---

<!--
_backgroundColor: #f4f1ec
_color: white
-->

![bg center: 90%](assets/phictionary_6.png)

---

<!--
_backgroundColor: #c78928
_color: white
-->
<h1>
  <i class="fa-solid fa-phone-volume fa-xl" style="margin-right: 15px"></i> Vishing: Voice Phishing
</h1>

<i class="fa-solid fa-info-circle fa-2xl" style="margin-right:20px; margin-top: 45px; margin-bottom: 30px"></i> What is Vishing?

Vishing, short for "Voice Phishing," involves scammers impersonating legitimate organizations over the phone to extract confidential information.

<i class="fa-solid fa-shield-alt fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 30px"></i> Safeguarding

- Approach unexpected calls with skepticism.
- Verify the caller's identity.
- Avoid revealing sensitive information over the phone.


---


<!--
backgroundColor: #0d3862
color: white
-->
# Baiting: Tempting Exploits
<i class="fa-solid fa-drumstick-bite fa-xl" style="margin-right: 15px"></i>

Luring users with enticing promises of rewards or benefits to spread malware.

<i class="fa-solid fa-cogs fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Tactics

Using infected USB drives, deceptive software downloads, alluring offers.

<i class="fa-solid fa-house-chimney-crack fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Risks

Unnoticed malware installation, potential loss of confidential data.

---

<!--
backgroundColor: #0d3862
color: white
-->
# Watering-Hole Attacks

<i class="fa-solid fa-water fa-xl" style="margin-right: 15px"></i>

Compromising frequently visited websites of targeted individuals to introduce malware.

<i class="fa-solid fa-cogs fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Strategies

Identifying high-value targets, infecting trusted websites.

<i class="fa-solid fa-house-chimney-crack fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Risks

Undetected malware distribution, covert surveillance of targeted audience.

---

<!--
_backgroundColor: #0d3862
_color: white
-->
<h1>
  <i class="fa-solid fa-dumpster fa-xl" style="margin-right: 15px"></i> Dumpster Diving
</h1>

Searching for sensitive information in physical trash to gain unauthorized access to confidential data.

<i class="fa-solid fa-crosshairs fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Focus

Examining paper documents, outdated hardware, overlooked information.

<i class="fa-solid fa-house-chimney-crack fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Risks

Potential theft of confidential data, risk of identity theft.



---

<!--
_backgroundColor: #cf7030
_color: white
-->

<h1>
  <i class="fa-solid fa-shield-alt fa-xl" style="margin-right: 15px"></i> Phishing Detection
</h1>

<i class="fa-solid fa-pencil fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Grammar and Greetings

Be alert to incorrect grammar and generic salutations such as "Dear Sir or Madam."

<i class="fa-solid fa-gift fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Unrealistic Promises

If an offer seems too good to be true, it's likely not genuine.

<i class="fa-solid fa-envelope fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Requests for Confidential Data

Never share sensitive information in response to email requests. Legitimate institutions typically don't ask for such details through email.

---

<!--
_backgroundColor: #cf7030
_color: white
-->

<i class="fa-solid fa-user-friends fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Unknown Senders

Delete unsolicited emails from unfamiliar senders or services you're not familiar with. Refrain from opening them or clicking on links or attachments.

<i class="fa-solid fa-clock fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Time Constraints

Exercise caution with emails that pressure you for urgent actions. Scammers often create artificial urgency to coerce quick responses.

<i class="fa-solid fa-at fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Incorrect Email Addresses and Domain Names

Inspect suspicious emails for accurate sender addresses and domain names. Acting impulsively might cause you to overlook subtle details.

---

<!--
_backgroundColor: #27ae60
_color: white
-->
# Why Use Email Signatures?

<i class="fa-solid fa-pen-fancy fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 15px"></i> Verification

- Email signatures confirm the sender's identity.
- Recipients can validate the message's authenticity.

<i class="fa-solid fa-fingerprint fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 15px"></i> Trust

- Enhances recipients' confidence in the message's source.
- Helps detect phishing and counterfeit emails.

<i class="fa-solid fa-file-signature fa-xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 15px"></i> Integrity

- Guards against unauthorized changes to the message.
- Ensures the message remains unaltered for recipients.

---

<!--
_backgroundColor: #3498db
_color: white
-->
# How Encryption Works

<i class="fa-solid fa-lock fa-xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 15px"></i> Encryption

- Safeguards confidential data from unauthorized access.
- Messages are converted into an unreadable format.

<i class="fa-solid fa-key fa-2xl" style="margin-right:20px; margin-top: 25px; margin-bottom: 15px"></i> Keys

- A decryption key is required to revert encrypted messages.
- Public keys for encryption, private keys for decryption.

<i class="fa-solid fa-code fa-2xl" style="margin-right:20px; margin-top: 25px; margin-bottom: 15px"></i> Techniques

- Symmetric Encryption: Same key for encrypting and decrypting.
- Asymmetric Encryption: Two keys, public and private.



---

<!--
_backgroundColor: #f4f3f3
_color: white
-->

![bg center 65%](assets/symmetric_asymmetric.png)

---

<!--
_backgroundColor: #3498db
_color: white
-->
<h1>
  <i class="fa-solid fa-envelope fa-xl" style="margin-right: 15px"></i> Emails & Postcards
</h1>

<i class="fa-solid fa-envelope-open-text fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Standard Emails

- Similar to postcards: Contents can be accessed by third parties.
- Unencrypted emails can be intercepted and read during transmission.

<i class="fa-solid fa-lock fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Encrypted Emails

- Encrypted mails comparable to personal deliveries.
- Ensures identity verification before content is accessed.

---
<!--
_backgroundColor: black
_color: white
-->

<img src="assets/white_color_occ.png" style="height:80px"></img> 

<h1 style="margin-bottom: -20px" > Secure-E-Mail </h1>
<h3> Communicate Securely via Email </h3>


With Secure Email, you can easily send signed and encrypted emails.

- Email Signing
- Spam Filter
- Outlook Add-In

![bg right:40%](assets/secure.svg)


---

<!--
_backgroundColor: #187d4d
_color: white
-->

# Second block - Conclusions

---

<!--
_backgroundColor: #187d4d
_color: white
-->

<h1 style="margin-bottom:-20px">
Zweiter Block - Conclusions
</h1>

<div class="columns">
<div>


## Malware

- Viruses
- Trojans
- Spyware
- Ransomware

</div>
<div>

## Technology

- Drive-by Download 
- Drive-by Installer 
- Email Attachments 
- Software Bundling 

</div>
<div>

## Social Aspect

- Phishing
- Vishing (Phone)
- Pretexting (Using false identities)

</div>
<div>

## Social Engineering

Manipulation of people through exploitation of emotions

</div>
</div>

<!-- 5 Minuten Pause
 -->


---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Block 3
## Authentification & Behaviors

---

<!--
_backgroundColor: #0d3862
_color: white
-->

## Authentication

User inputs username and password

Verification of identity

## Authorization

Server checks authorizations based your verified identity


---


<!--
_backgroundColor: #2c3e50
_color: white
-->
<h1>
  <i class="fa-solid fa-fingerprint fa-xl" style="margin-right: 15px"></i> Forms of Authentication
</h1>

<i class="fa-solid fa-brain fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Knowledge (Passwords)

- Username and secret password
- Vulnerable to phishing and social engineering techniques

<i class="fa-solid fa-key fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Possession (Physical Keys)

- Hardware tokens, smartcards, USB keys
- Enhanced security, requires physical access

<i class="fa-solid fa-eye-slash fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Biometrics

- Fingerprint, facial recognition, iris scan
- Unique physical characteristics for identification
---

<!--
_backgroundColor: #2c3e50
_color: white
-->
<h1>
  <i class="fa-solid fa-hammer fa-xl" style="margin-right: 15px"></i> Brute Forcing
</h1>

<i class="fa-solid fa-clock fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> What is Brute Forcing?

- Method of trying all possible combinations
- Objective: Guessing passwords or secret information

<i class="fa-solid fa-hourglass-half fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Example

- Password: "secure123"
- Estimated time to crack: Weeks to months

<i class="fa-solid fa-triangle-exclamation fa-2xl" style="margin-top:25px; margin-left:25px; margin-right:15px"></i> Wordlists significantly reduce this time





---



<!--
_backgroundColor: #d16258
_color: white
-->
<h1>
  <i class="fa-solid fa-lines-leaning fa-xl" style="margin-right: 15px"></i> Domino Effect
</h1>


<i class="fa-solid fa-lock fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 25px"></i> What is the Domino Effect?

- Reusing the same password for different accounts.
- Compromising one account jeopardizes others.

<i class="fa-solid fa-warning fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 25px"></i> Risks

- A cracked password grants access to multiple accounts.
- Attackers exploit this vulnerability.

<i class="fa-solid fa-user-lock fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 25px"></i> Example

- Account A shares a password with Account B.
- If Account A is breached, attackers access Account B.

---

<!--
_backgroundColor: #187d4d
_color: white
-->

<h1>
<i class="fa-solid fa-circle-check fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Password recommendations
</h1>

<i class="fa-solid fa-dice-one fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 25px"></i> Employ a unique password for each account.

<i class="fa-solid fa-list-check fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 25px"></i> Use password managers for effective management.

<i class="fa-solid fa-key fa-xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 25px"></i><i class="fa-solid fa-key fa-xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 25px"></i> Use Multi-Factor Authentication (MFA) if available.


---


<iframe width="1100" height="800" src="https://www.youtube.com/embed/opRMrEfAIiI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

<h1>
  <i class="fa-solid fa-key fa-xl" style="margin-right: 15px"></i> Passwort-Manager
</h1>

<i class="fa-solid fa-question fa-2xl" style="margin-right:20px; margin-top: 35px; margin-bottom: 25px"></i> What is a Password Manager?

- Stores and manages secure passwords
- Generates random, complex passwords

<i class="fa-solid fa-plus fa-2xl" style="margin-right:20px; margin-top: 35px; margin-bottom: 25px"></i> Benefits

- No need to memorize
- Prevents password reuse

<i class="fa-solid fa-gears fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 25px"></i> How They Work

- Master password for access
- Secure storage of encrypted password data

---

<!--
_backgroundColor: black
_color: white
-->

<img src="assets/white_color_occ.png" style="height:80px"></img> 

# Password-Manager

With the Password Manager Safe, you can save, manage, and share logins, passwords, and other sensitive data.

- Browser Plugin

- Hosted in Switzerland

- 2-Factor Authentication

![bg right:40%](assets/vault.png)

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Behaviors

## Behavior in Public Networks <i class="fa-solid fa-wifi fa-xl" style="margin-left: 15px"></i>

## Clean Desk Policy <i class="fa-solid fa-spray-can-sparkles fa-xl" style="margin-left: 15px"></i>

---

<!--
_backgroundColor: #2980b9
_color: white
-->
<h1>
  <i class="fa-solid fa-wifi fa-xl" style="margin-right: 15px"></i> Behavior in public networks
</h1>

<i class="fa-solid fa-lock fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 25px"></i> Using Public Networks

- Risk of Man-in-the-Middle attacks and data snooping.
- Avoid online banking and sensitive activities.

<i class="fa-solid fa-user-shield fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 25px"></i> Tips

- Disable file and network sharing.
- Use secure websites (HTTPS).
- Employ VPN for encrypted connection.

<i class="fa-solid fa-car-tunnel fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 25px"></i> Virtual Private Network (VPN)

- Encrypts internet traffic through a secure tunnel.




---

<!--
_backgroundColor: #5f8f9e
_color: white
-->
<h1>
  <i class="fa-solid fa-spray-can-sparkles fa-xl" style="margin-right: 15px"></i> Clean Desk Policy
</h1>

<i class="fa-solid fa-question-circle fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Purpose of a Clean Desk Policy

The Clean Desk Policy upholds the CIA principles:

- Confidentiality
- Integrity
- Availability

<i class="fa-solid fa-lock fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Security Concerns

An unorganized workspace can pose security risks:

- Unauthorized use of logged-in user accounts
- Access to sensitive documents

---

<!--
_backgroundColor: #5f8f9e
_color: white
-->

<i class="fa-solid fa-trash fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Implementation

The policy encompasses:

- Regular workspace cleaning
- Logging out before leaving
- Concealing confidential data

<i class="fa-solid fa-user-secret fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Defense against Espionage

Safeguards against:

- Employees
- Third-party personnel (e.g., cleaning staff)
- Misuse of identities



---

<!--
_backgroundColor: #187d4d
_color: white
-->

# Third block - Conclusion

---

<!--
_backgroundColor: #187d4d
_color: white
-->

# Third block - Conclusion

<div class="columns">
<div>

## Password Recommendations

- Use a unique password for each account
- Utilize password managers for management
- Employ Multi-Factor Authentication (MFA)

</div>
<div>

## Clean Desk Policy

- The Clean Desk Policy supports the VIV principles

</div>
<div>
</div>
<div>
</div>
</div>

<!-- 5 Minuten Pause
 -->


---


<!--
_backgroundColor: #187d4d
_color: white
-->


# Links

- Check Email Address
https://haveibeenpwned.com
- Check Password
https://haveibeenpwned.com/passwords
- National Cybersecurity Centre:
https://www.melani.admin.ch/melani/en/home.html
- Password Safe
https://www.open-circle.ch/passwort-manager/
- Information is Beautiful
    https://www.informationisbeautiful.net/visualizations/worlds-biggest-data-breaches-hacks/


--- 

![bg](assets/open_circle_stef.png)

---

![bg](assets/open_circle_end.png)