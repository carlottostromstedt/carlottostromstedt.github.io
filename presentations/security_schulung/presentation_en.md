---
marp: true
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

  .footer-passive {
    color: grey;
  }
  
  .footer-outer {
    display: flex;
    flex-direction: row;
    font-size: 22px; 
    justify-content: center;
    position: absolute; 
    top: 665px; 
    right: 160px;
  }

  .text-dark {
    color: #5e5e5c;
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

![bg center: 70%](assets/dhl.jpeg)

<!--
Some of you have probably received an SMS like this or similar
-->


---

![bg center: 48%](assets/amaazon_1.PNG)

<!--
Many of you have probably received an email like this or similar
-->


---

![bg center: 80%](assets/guardian.png)

<!--
And have probably also read about ransomware or other cyber attacks online or in the newspaper
-->

---

![bg center: 70%](assets/attack.gif)

<!--
Fact is: There are thousands of cyber attacks happening every day
-->

---



<!-- 
_backgroundColor: #0d3862 
_color: white -->

# 3 Parts

- ### Information Security
- ### Malware & Phishing
- ### Authentication & Behaviors

<!--
Today we will take a look behind these attacks.

We will look at the theoretical parts of information sercurity in the first part

We will then look at malware and phishing with technical processes including social aspects

And to finishour training we will look at authentication & behaviours in digital spaces and in the workplace
-->

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
# Part 1
## Information Security

<div class="footer-outer">
  <p class="text-dark"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="text-dark" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors </p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# What is Information Security?


<!--
What do we actually mean when we are talking about information security?
-->

<div class="footer-outer">
  <p class="text-dark"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="text-dark" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---


<!--
_backgroundColor: #0d3862
_color: white
-->

## Information Security

- Information security encompasses ensuring **confidentiality**, **integrity**, and **availability** of information.
- Information security is ensured when sufficient **technical**, **physical**, and **organizational** protective measures have been implemented.
- Information security is influenced, ensured, or improved by each individual.

<!--
We usually define information Security as security centered around the three components Security, Confidentiality and Availability of information

We call it the CIA triad and it is a longstanding concept of Information Security.

And we can ensure that these security goals are met when we provide infrastructure. Infrastructure in the form of technical physical and organizational protective measures.

You as individuals however, also have a big influence on information security.

The goal of todays training is that you should at least be able to ensure information security and maybe even improve it?
-->

<div class="footer-outer">
  <p class="text-dark"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="text-dark" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

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

Employees outside of the financial department do not have access or only have restricted access to financial documents.
<!--

We can provice confidentiality if we protcet our information against unauthorized access

A concrete example would be that only employees that work for the financial department should have access to all financial documents.
-->

<div class="footer-outer">
  <p class="text-dark"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="text-dark" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->
<h1>
  <i class="fa-solid fa-file-shield fa-xl" style="margin-right: 15px"></i> Integrity
</h1>

<i class="fa-solid fa-pen-fancy fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Definition

Ensuring accuracy and consistency of data as well as the completeness and reliability of systems

<i class="fa-solid fa-tools fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Example

Digital signatures for emails ensure that a document originates from a specific sender

<!--
Integrity of Information is focuse on ensuring accuracy and consistenc of data, but also completeness and reliability of systems.

We want to ensure that Documents are in an origianl state and if they are changed, then we should be able to trace these changes
-->

<div class="footer-outer">
  <p class="text-dark"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="text-dark" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

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

<!--
Availability of information is based on ensuring that there is constant access to information and resources inside of a certain timeframe.

This does not have to be 24/7,but inside of the promised timeframe, we should be able to provide constant access.

An example is that we as an IT provider have regular maintenance and redundant infrastructure so that our customers have access to all their services
-->

<div class="footer-outer">
  <p class="text-dark"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="text-dark" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

<h2 style="margin-bottom: -20px">
Confidentiality / Integrity / Availability - Quiz
</h2>



<!-- # Zoom Poll / Quiz
-->
---

<!--
_backgroundColor: #0d3862
_color: white
-->

<!-- 
# Zoom Poll / Quiz
-->

<!--
So we will now go through each of the case studies and have look at what the answers would be
-->

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
Examples of sensitive and valuable data
</h1>

<div class="columns2" style="margin-left: 0px; padding-top: 75px">
<div>

<i class="fa-solid fa-credit-card fa-xl" style="font-size:80px"></i> 
<p style="margin-top: 40px; font-size: 30px">Payment data</p>


</div>
<div>
<i class="fa-solid fa-people-roof fa-xl" style="font-size:80px"></i>
<p style="margin-top: 40px; font-size: 30px">Personal data</p>


</div>
<div>

<i class="fa-solid fa-laptop-medical fa-xl" style="font-size: 80px"></i>
<p style="margin-top: 40px; font-size: 30px">Health data</p>

</div>
<div>


</div>

</div>

<!--
So we've established a defintion of Information Security and of it's components. Which i hope you were able to understand

Now that we have answered the question of **what** information security is? We will talk about the **why**

We have a lot of data nowadays and not only in quantity but the data we have is often also very valuable

So this can be for example:

- financial data
- personal data
- health data

The value of this data naturally provides an incentive and motivation
-->

<div class="footer-outer">
  <p class="text-dark"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="text-dark" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Motivation of Attackers

<div class="columns" style="margin-bottom:40px;">
<div>

<h2>
  Economic <i class="fa-solid fa-sack-dollar fa-xl" style="margin-left: 15px"></i> 
</h2>

- Personal Enrichment
- Elimination of Competitors
- Enhancement of Market Position

</div>
<div style="visibility: hidden;">
<h2>
  Political <i class="fa-solid fa-check-to-slot fa-xl" style="margin-left: 15px"></i> 
</h2>

- Influencing Elections
- Causing Reputation Damage
- Spreading Religious or Political Content

</div>
<div style="visibility: hidden;">

<h2>
  Personal <i class="fa-solid fa-user fa-xl" style="margin-left: 15px"></i> 
</h2>

- Validation
- "For the LULZ" (Amusement)

</div>
</div>


<!--

So we can defintely understand that there many incentives to conduct and attack

We have the economical motivators

And then especially with social media as well have political motivations

and personal motivations
-->

<div class="footer-outer">
  <p class="text-dark"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="text-dark" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
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
- Causing Reputation Damage
- Spreading Religious or Political Content

</div>
<div style="visibility: hidden;">

<h2>
  Personal <i class="fa-solid fa-user fa-xl" style="margin-left: 15px"></i> 
</h2>

- Validation
- "For the LULZ" (Amusement)

</div>

<div class="footer-outer">
  <p class="text-dark"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="text-dark" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Motivation of Attackers

<div class="columns">
<div style="margin-bottom:-20px;">

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
- Causing Reputation Damage
- Spreading Religious or Political Content

</div>
<div style="margin-bottom:40px;">

<h2>
  Personal <i class="fa-solid fa-user fa-xl" style="margin-left: 15px"></i> 
</h2>

- Validation
- "For the LULZ" (Amusement)

</div>
</div>


<!--

So we can defintely understand that there many incentives to conduct and attack

We have the economical motivators

And then especially with social media as well have political motivations

and personal motivations
-->

<div class="footer-outer">
  <p class="text-dark"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="text-dark" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---


<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/vulnerability_1.png)

<!--
So these attackers have their motivations and we have our information / our data.

The attackers try find vulnerabilities which they can exploit
-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/vulnerability_2.png)

<!--
So these attackers have their motivations and we have our information / our data.

The attackers try find vulnerabilities which they can exploit
-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/vulnerability_3.png)

<!--
We then take protective measurements to patch or to protect these vulnerabilities.
-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/vulnerability_4.png)

<!--
This then hinders further attacks. For the moment.But this is a cylical process.

We continuously want to ensure that we have the correct protective measurements applied.

What should be noted is that we try to deploy protective measurements proportionally, based on the value of our information / data.

And to help us with this we have classifications
-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Classification of information & data

<!--

It helps us group data based on different factors

-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Information  requirements

Confidentiality <i class="fa-solid fa-mask fa-xl" style="margin-left:20px"></i> 

Integrity <i class="fa-solid fa-file-shield fa-xl" style="margin-left:20px"></i> 

Availability <i class="fa-solid fa-clock-rotate-left fa-xl" style="margin-left:20px"></i> 


<!--
And once again we meet our lovely trio / triad CIA

We can apply these properties to help us define our requirements when it comes to classification
-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

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

- Confidential
- Internal
- Public


</div>
</div>

<!--
Today we will focus on 3 classifications according to ISO-Standards: Confidential Internal & Public. There is also the classification top secret, but that is mainly used in pharmaceutical companies and the military industy so we will not discuss that today.
-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

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

<!--
So we have three areas which we will look at which is Storage, transport and processing of data. 

And this is based on our classifcation

so for confidential:...

Printing is allowed but copying is not. And when we print, the printing should be monitored.
-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

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

<!--

Transport: Unenencrypted and phone calls are allowed but not in public spaces.

And to note for processing is that it should be comprehensible and traceable


-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

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

<i class="fa-solid fa-binoculars fa-check" style="margin-right:20px"></i> Changes should be comprehensible and traceable

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Information security incidents

<!--
So what happens when we are actually attacked and 
have a security incident?
-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/incident_1.png)

<!--
We can define a compromise of information security based on our CIA triad / our security goals.

It can be a compromise of one area or multiple of these three areas at the same time
-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/incident_2.png)

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/incident_3.png)

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: white
_color: black
-->

![bg center: 99%](assets/incident_4.png)

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #cf7030
_color: white
-->

# Responding to a Security Incident

<!--
And if we have a Security incident, how do we respond?
-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #cf7030
_color: white
-->


<i class="fa-solid fa-user-shield fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 15px"></i> Suspicions

- If you observe anything suspicious, don't hesistate to report it to us

<i class="fa-solid fa-exclamation-triangle fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 15px"></i> Reporting

- It's recommended to report via phone or create a support ticket.

<i class="fa-solid fa-envelope fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 15px"></i> Forwarding

- Kindly forward suspicious phishing emails to support@open-circle.ch.

<!--
We are here for you

Our experts will take the necessary actions to deal with the incident

You can also add screenshots to a ticket to provide us with more information
-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

![bg center: 90%](assets/cyber_threats.png)

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
There are a lot of technical tools. but in the end you as individuals have a big influence on information security.

This is also the reason why we're having this training today:

To raise your awareness as a user and to give an understanding of some of the threats that exist.
-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>


---

<!--
_backgroundColor: #187d4d
_color: white
-->

# Part 1 - Conclusions

<!--
So we are concluding the first part
-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #187d4d
_color: white
-->

# Part 1 - Conclusions

<div class="columns" style="margin-bottom: 30px">
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

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #187d4d
_color: white
-->


# First part - Quiz

<!--
Do you have any questions for this first part of our training?
-->

<div class="footer-outer">
  <p class="footer-passive"></p>
  <p class="footer-active">Part 1 - Information Security</p>
  <p class="footer-passive" >&nbsp | Part 2 - Malware & Phishing | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Part 2

## Malware & Social Engineering

<!--
In our second part of this training we will look at technologies leveraged by attackers

What do they use? How does itwork and this also helps us to understand what we need to do to protect ourselves
-->

 <div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

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


<!-- 
So we will look at four groups of malware today. There are many subgroups and variants but we will focus on these as they are some of the most important ones to know
-->

 <div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

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

- infected files
- email attachments
- infected websites


<!--

The name virus itself indicates that there are similiarities to biological viruses,

Viruses are software that focus on infiltrating files and systems and to replicate themselves.


Damage: Data destruction, system crashes, network propagation.

-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

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

- infected downloads
- drive-by downloads


<!--
So most definitiely famous, at least when it comes to the namesake are trojans.

And as the name indicates, its about disguising an attack.

Data theft, identity theft, complete system takeovers
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

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

- software bundling
- drive-by downloads

<!--
Privacy breaches, identity theft, financial losses.
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

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

- infected email attachments
- exploit kits
- infected downloads

<!--
Data loss, financial losses, business interruptions.
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---

 <!--
_backgroundColor: #e74c3c
_color: white
-->


<h1> <i class="fa-solid fa-biohazard fa-xl" style="margin-right: 15px"></i> Example: WannaCry Virus </h1>

- Outbreak in May 2017
- Ransomware that infected Windows systems worldwide.

<i class="fa-solid fa-tools fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Purpose and Impact

- Exploitation of the Windows vulnerability "EternalBlue"
- Affected organizations such as the NHS (UK) and FedEx

<!-- 
Global Impact: WannaCry infected over 230,000 computers across 150 countries within days. It spread by exploiting a vulnerability in the Windows operating system called EternalBlue (a flaw that had already been patched by Microsoft but was unpatched in many systems).

Behavior: The ransomware encrypted users' files, demanding a ransom in Bitcoin to restore access. If users failed to pay the ransom, their data remained inaccessible.

Notable Targets: Several major institutions were severely impacted. For example:

The UK’s National Health Service (NHS) had to cancel surgeries and medical appointments because WannaCry disabled their computer systems.
Large corporations such as FedEx and Telefonica also faced major disruptions.

Prevention & Aftermath: The attack highlighted the importance of keeping systems updated with security patches, as well as implementing backup and recovery plans. It also showcased the need for increased international cooperation to combat cybercrime.
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---

 <!--
_backgroundColor: #e74c3c
_color: white
-->

<i class="fa-solid fa-user-secret fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Spread and Complexity

- Spread rapidly worldwide, affecting over 230,000 systems in 150 countries
- Encrypted data and demanded Bitcoin ransom

<i class="fa-solid fa-shield-alt fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Lessons Learned

- Importance of regular updates and backups
- Highlights the vulnerability of systems without security patches

<!-- 
Global Impact: WannaCry infected over 230,000 computers across 150 countries within days. It spread by exploiting a vulnerability in the Windows operating system called EternalBlue (a flaw that had already been patched by Microsoft but was unpatched in many systems).

Behavior: The ransomware encrypted users' files, demanding a ransom in Bitcoin to restore access. If users failed to pay the ransom, their data remained inaccessible.

Notable Targets: Several major institutions were severely impacted. For example:

The UK’s National Health Service (NHS) had to cancel surgeries and medical appointments because WannaCry disabled their computer systems.
Large corporations such as FedEx and Telefonica also faced major disruptions.

Prevention & Aftermath: The attack highlighted the importance of keeping systems updated with security patches, as well as implementing backup and recovery plans. It also showcased the need for increased international cooperation to combat cybercrime.
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---



![bg center: 70%](assets/wannacry.png)

<!-- link: https://www.microsoft.com/en-us/security/blog/2022/06/13/the-many-lives-of-blackcat-ransomware/
 
Die ist ein Beispiel einer Nachricht die von einer Ransomware gruppe eingebelendet wird wenn mit black cat, Ransomware, was eine variante von Ransomware ist
-->

---

 <!--
_backgroundColor: #0d3862
_color: white
-->


# Attack components

What do attackers use for their attacks?

<!--
So we talked about malware and i commented on the spread of it.

So attackers use different attack components to get malware on systems
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---


 <!--
_backgroundColor: #0d3862
_color: white
-->


<h1>
  Technical aspects <i class="fa-solid fa-cogs fa-xl" style="margin-right: 15px; margin-left: 20px; margin-bottom: 50px;"></i> 
</h1>

<h1>
  Social aspects <i class="fa-solid fa-users-line fa-xl" style="margin-right: 15px; margin-left: 20px"></i> 
</h1>

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---


 <!--
_backgroundColor: #0d3862
_color: white
-->


# Technical aspects

- Drive-by-Download <i class="fa-solid fa-globe fa-xl" style="margin-left: 15px"></i>
- Email Attachments <i class="fa-solid fa-envelope fa-xl" style="margin-left: 15px"></i>
- Software Bundling <i class="fa-solid fa-box fa-xl" style="margin-left: 15px"></i>


<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

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

<!--
So drive by downloads are downloads done in a drive by, well for browsing it would just be visiting a home page

Leveraging javascript

Unnoticed infection, propagation of viruses, trojans, or ransomware.
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---
<!--
_backgroundColor: #f4f1ec
_color: black
-->



![bg center: 70%](assets/drive_by_1.gif)

<!-- link: https://us.norton.com/blog/malware/what-are-drive-by-downloads
 -->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #f4f1ec
_color: black
-->


![bg center: 70%](assets/drive_by_2.png)

<!--
So the recommendation here for unauthorized drive by downloads, since they work without direct interactions, is to update and especially update the browser as often as possible or at least as often as it prompts you to
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

<h1>
  <i class="fa-solid fa-envelope fa-xl" style="margin-right: 15px"></i> Email Attachments
</h1>

Attachments that exploit vulnerabilities in software (such as document readers) when opened, to install malware.

<i class="fa-solid fa-cogs fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Mechanism

Exploiting software vulnerabilities, executing macros.

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

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

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

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

<!--
A technical tool used often in combination with other tools are rootkits.

They basically use the different levels of access which come with different users, such as the root user where the name comes from, to get authorization to execute certain commands.

It is often used to disguised, to hide other malware and their action
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

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

<div style="margin-bottom: 40px;">
<h1>
  <i class="fa-solid fa-shield-alt fa-xl" style="margin-right: 15px"></i> Protection against Malware
</h1>

<i class="fa-solid fa-arrow-rotate-left fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 35px"></i> Software updates

<p style="margin-top: -15"> Keep your operating system and all software up to date to protect against known security vulnerabilities.</p>

<i class="fa-solid fa-envelope fa-2xl" style="margin-right:20px; margin-top: 20px; margin-bottom: 35px"></i> Caution with emails

<p style="margin-top: -15">Do not open email attachments or click on links from unknown or suspicious senders. </p>

<i class="fa-solid fa-user-shield fa-2xl" style="margin-right:20px; margin-top: 20px; margin-bottom: 35px"></i> Behavioral Awareness

<p style="margin-top: -15px"> Be cautious when downloading files from the internet and avoid questionable websites.</p>

<!--
What can we do to protcet ourselves

As i said before with the browsers, but also for other software and the os in general.
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Social aspects

<!--
Also used by attackers are social tactics which are pretty much equally as important and dangerous.

-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Social Engineering

Manipulation of individuals by exploiting trust, curiosity, or pressure to reveal confidential information or perform unauthorized actions.

## Methods

- Phishing
- Vishing (Phone)

<!--
We see this with phishing and with vishing which is phishing but with voice so by telephone
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->
<h1>
  <i class="fa-solid fa-fish fa-xl" style="margin-right: 15px"></i> Phishing
</h1>

Deception of users to steal confidential information such as passwords or financial data.

<i class="fa-solid fa-viruses fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Methods

Fake emails, websites, or social media that appear genuine to build trust.

<!--
Identity theft, financial losses, unauthorized access to personal accounts.
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #f4f1ec
_color: white
-->

![bg center: 90%](assets/phictionary_1.png)

<!--
We will look at some differnt types groupings of phishing just to see what forms of it exist. These are of course not all types of phishing but some of the more prevalent tactics

Account information alerts:

This is usually about missing information, could be payment data or other information

Also popular with things like netflix, amazon etc is account suspension based on different reasons

-->

---


<!--
_backgroundColor: #f4f1ec
_color: white
-->

![bg center: 90%](assets/phictionary_2.png)


<!--
We have account verification phishing which is when the want you to verify your account. Often from well known companies which provide services that many users use. Gives them a big net
-->

---


![bg center: 40%](assets/amazon_2.PNG)

---


<!--
_backgroundColor: #f4f1ec
_color: white
-->

![bg center: 90%](assets/phictionary_3.png)

---


![bg center: 40%](assets/paypal_attempt.png)

---

<!--
_backgroundColor: #f4f1ec
_color: white
-->

![bg center: 90%](assets/phictionary_6.png)

---

![bg center: 70%](assets/paypal_suspicious.png)



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

![bg center: 90%](assets/overdue.jpeg)

---

![bg center: 80%](assets/dhl.jpeg)

---

<!--
_backgroundColor: #f4f1ec
_color: white
-->


![bg center: 90%](assets/ncsc_en.png)

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

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->
<h1>
  <i class="fa-solid fa-dumpster fa-xl" style="margin-right: 15px"></i> Dumpster Diving
</h1>

Searching for sensitive information in physical trash to gain unauthorized access to confidential data.

<i class="fa-solid fa-crosshairs fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> Goal

Examining paper documents, outdated hardware, overlooked information.

<i class="fa-solid fa-check fa-2xl" style="margin-right:20px; margin-top: 75px; margin-bottom: 35px"></i> How to avoid


Dispose old hardware and documents according to company standards

<!--
Potential theft of confidential data, risk of identity theft.
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

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

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

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

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: white
_color: white
-->

![bg center: 85%](assets/bank_en_1.png)


---

<!--
_backgroundColor: white
_color: white
-->

![bg center: 85%](assets/bank_en_2.png)

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

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #3498db
_color: white
-->
<h1>
  <i class="fa-solid fa-certificate fa-xl" style="margin-right: 15px"></i> SSL- & TLS Certificates
</h1>

<i class="fa-solid fa-stamp fa-2xl" style="margin-right:20px; margin-top: 45px; margin-bottom: 20px"></i> Function

- SSL certificates are used for the security and encryption of data transmissions on the internet.

<i class="fa-solid fa-check-circle fa-2xl" style="margin-right:20px; margin-top: 5px; margin-bottom: 20px"></i> Trust and Validation

- Browsers trust websites with valid SSL certificates.
- Certificates are issued and validated by Certification Authorities (CAs).

<i class="fa-solid fa-lock fa-2xl" style="margin-right:20px; margin-top: 5px; margin-bottom: 20px"></i> Visual Indications

- Browsers provide visual cues for secure connections, such as a closed padlock or "https" in the URL.

<!--
SSL (Secure Sockets Layer) encryption, and its more modern and secure replacement, TLS (Transport Layer Security)

uses both asymmetric and symmetric encryption

Asymmetric encryption is used to establish a secure session between a client and a server 

symmetric encryption is used to exchange data within the secured session. 

Differences tls ssl:

Cipher suites

SSL protocol offers support for Fortezza cipher suite. TLS does not offer support. TLS follows a better standardization process that makes defining of new cipher suites easier like RC4, Triple DES, AES, IDEA, etc.
Alert messages

SSL has the “No certificate” alert message. TLS protocol removes the alert message and replaces it with several other alert messages.
Record Protocol

SSL uses Message Authentication Code (MAC) after encrypting each message while TLS on the other hand uses HMAC — a hash-based message authentication code after each message encryption.
Handshake process

In SSL, the hash calculation also comprises the master secret and pad while in TLS, the hashes are calculated over handshake message.
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---

![bg center: 100%](assets/ssl.png)

---
<!--
_backgroundColor: #3498db
_color: white
-->
# How Encryption Works

<i class="fa-solid fa-lock fa-xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 15px"></i> Encryption

- Safeguards confidential data
- Conversion into unreadable format

<i class="fa-solid fa-key fa-2xl" style="margin-right:20px; margin-top: 25px; margin-bottom: 15px"></i> Keys

- Encryption: Public key
- Decryption: Private key

<i class="fa-solid fa-code fa-2xl" style="margin-right:20px; margin-top: 25px; margin-bottom: 15px"></i> Techniques

- Symmetric Encryption: Same key for encrypting and decrypting.
- Asymmetric Encryption: Two keys, public and private.

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

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
  <i class="fa-solid fa-key fa-xl" style="margin-right: 15px"></i> Use cases for encryption
</h1>


<h3>
<i class="fa-solid fa-lock fa-xl" style="margin-right:20px; margin-top: 50px; margin-bottom: 50px"></i> SSL / TLS
</h3>

<h3>
  <i class="fa-solid fa-envelope fa-xl" style="margin-right:20px; margin-top: 15px; margin-bottom: 50px"></i> Encrypted E-Mails
</h3>

<h3>
  <i class="fa-solid fa-car-tunnel fa-xl" style="margin-right:20px; margin-top: 15px; margin-bottom: 15px"></i> VPN
</h3>


<div class="footer-outer">
  <p class="footer-passive">Part 1 - Informationssicherheit |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #187d4d
_color: white
-->

# Part 2 - Conclusions

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>

---

<!--
_backgroundColor: #187d4d
_color: white
-->

<h1 style="margin-bottom:-20px">
Part 2 - Conclusions
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
- Email Attachments 
- Software Bundling 

</div>
<div>

## Social Aspect

- Phishing
- Vishing (Phone)

</div>
<div>

## Social Engineering

Manipulation of people through exploitation of emotions

</div>
</div>

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>


---

<!--
_backgroundColor: #187d4d
_color: white
-->

<!-- # Zoom Poll / Quiz
-->

<!--
_backgroundColor: #187d4d
_color: white
-->

# Part 2 - Quiz

<!-- 5 Minuten Pause
 -->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security |</p>
  <p class="footer-active">&nbsp Part 2 - Malware & Phishing</p>
  <p class="footer-passive" >&nbsp | Part 3 - Authentication & Behaviors</p>
</div>


---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Part 3
## Authentication & Behaviors

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

## Authentication

Credentials such as a username and password are provided

Server then verifies the identity of the person, device, or system

## Authorization

What actions or resources a user or entity is allowed to access or perform

Permissions and privileges associated with a specific identity
<!--
If the verification is successful, the user or device is considered authentic and is granted access to the relevant resources or services.

There is also authorization after they have been authenticated. 

It defines the permissions and privileges associated with a specific identity. 
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

---


<!--
_backgroundColor: #2c3e50
_color: white
-->
<div style="margin-bottom: 50px;">
<h1>
  <i class="fa-solid fa-fingerprint fa-md" style="margin-right: 15px"></i> Forms of Authentication
</h1>

<i class="fa-solid fa-brain fa-xl" style="margin-right:20px; margin-top: 15px; margin-bottom: 35px"></i> Passwords

- Username and secret password
- Vulnerable to phishing and social engineering techniques

<i class="fa-solid fa-key fa-xl" style="margin-right:20px; margin-top: 15px; margin-bottom: 35px"></i> Physical Keys

- Hardware tokens, smartcards, USB keys
- Enhanced security, requires physical access

<i class="fa-solid fa-eye-slash fa-xl" style="margin-right:20px; margin-top: 15px; margin-bottom: 35px"></i> Biometrics

- Fingerprint, facial recognition, iris scan
- Unique physical characteristics for identification

</div>

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

---

<!--
_backgroundColor: #2c3e50
_color: white
-->
<h1>
  <i class="fa-solid fa-hammer fa-xl" style="margin-right: 15px"></i> Brute Forcing
</h1>

<i class="fa-solid fa-clock fa-2xl" style="margin-right:20px; margin-top: 45px; margin-bottom: 35px"></i> What is Brute Forcing?

- Method of trying all possible combinations
- Objective: Guessing passwords or secret information

<i class="fa-solid fa-hourglass-half fa-2xl" style="margin-right:20px; margin-top: 35px; margin-bottom: 35px"></i> Example

- Password: "Secure123-"
- Estimated time to crack: Seconds

<i class="fa-solid fa-triangle-exclamation fa-2xl" style="margin-top:25px; margin-left:25px; margin-right:15px"></i> Wordlists significantly reduce brute force time

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

<!--

Passwords we said are vulnerable to phishing and social engineering, but they can also be vulnerable to brute forcing

I wont provide any concrete times on password brute forcing since it can change very quickly in either direction.

What i will say, is that wordlists have a significant influence on the time it takes to brute force

-->

---

![bg center: 90%](assets/brute_1.png)

---

![bg center: 90%](assets/brute_2.png)

---


![bg center: 110%](assets/773.png)

<!--
in January 2019, a large collection of credential stuffing lists (combinations of email addresses and passwords used to hijack accounts on other services) was discovered being distributed on a popular hacking forum. The data contained almost 2.7 billion records including 773 million unique email addresses alongside passwords

Some Passwordmanagers have a function built in which lets you check if your password is in a leaked list.
-->

---

![bg center: 80%](assets/pwned.png)

---


<!--
_backgroundColor: #d16258
_color: white
-->
<h1>
  <i class="fa-solid fa-lines-leaning fa-xl" style="margin-right: 15px"></i> Domino Effect
</h1>


<i class="fa-solid fa-lock fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 25px"></i> What causes the Domino Effect?

- Reusing the same password for different accounts


<i class="fa-solid fa-warning fa-2xl" style="margin-right:20px; margin-top: 30px; margin-bottom: 25px"></i> Risks

- Attackers exploit this vulnerability.
- A cracked password grants access to multiple accounts.

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

---

<!--
_backgroundColor: #187d4d
_color: white
-->

<h1>
<i class="fa-solid fa-circle-check fa-2xl" style="margin-right:20px; margin-top: 25px; margin-bottom: 35px"></i> Password recommendations
</h1>

<i class="fa-solid fa-1 fa-2xl" style="margin-right:4px; margin-top: 40px; margin-bottom: 25px"></i><i class="fa-solid fa-2 fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 25px"></i> Use at least 12 characters

<i class="fa-solid fa-hashtag fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 25px"></i> Combination of uppercase letters, lowercase letters, numbers, and symbols.

<i class="fa-solid fa-bridge fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 25px"></i> Use mnemonics instead of Words

<i class="fa-solid fa-dice-one fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 25px"></i> Employ a unique password for each account.

<i class="fa-solid fa-list-check fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 25px"></i> Use password managers for effective management.

<i class="fa-solid fa-key fa-xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 25px"></i><i class="fa-solid fa-key fa-xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 25px"></i> Use Multi-Factor Authentication (MFA) if available.

<!--
mnemonic

So you could use: my favorite movie is top gun 2 from 2023 + Tom Cruise

MYFMITG2F2023+tc

a device such as a pattern of letters, ideas, or associations that assists in remembering something, for example Richard Of York Gave Battle In Vain for the colours of the spectrum (red, orange, yellow, green, blue, indigo, violet).
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

---


<!--
_backgroundColor: #0d3862
_color: white
-->

<h1>
  <i class="fa-solid fa-key fa-md" style="margin-right: 15px"></i> Password-Manager
</h1>

<i class="fa-solid fa-question fa-2xl" style="margin-right:20px; margin-top: 15px; margin-bottom: 25px"></i> What is a Password Manager?

- Stores and manages secure passwords
- Generates random, complex passwords

<i class="fa-solid fa-plus fa-2xl" style="margin-right:20px; margin-top: 15px; margin-bottom: 25px"></i> Benefits

- No need to memorize
- Prevents password reuse

<i class="fa-solid fa-gears fa-2xl" style="margin-right:20px; margin-top: 10px; margin-bottom: 25px"></i> How They Work

- Master password for access
- Secure storage of encrypted password data

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

---

<!--
_backgroundColor: #0d3862
_color: white
-->

# Behaviors

## Behavior in Public Networks <i class="fa-solid fa-wifi fa-xl" style="margin-left: 15px"></i>

## Clean Desk Policy <i class="fa-solid fa-spray-can-sparkles fa-xl" style="margin-left: 15px"></i>

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

---

<!--
_backgroundColor: #2980b9
_color: white
-->
<h1>
  <i class="fa-solid fa-wifi fa-xl" style="margin-right: 15px"></i> Behavior in public networks
</h1>

<i class="fa-solid fa-lock fa-2xl" style="margin-right:20px; margin-top: 15px; margin-bottom: 25px"></i> Using Public Networks

- Risk of Man-in-the-Middle attacks and data snooping.
- Avoid online banking and sensitive activities.

<i class="fa-solid fa-user-shield fa-2xl" style="margin-right:20px; margin-top: 20px; margin-bottom: 25px"></i> Tips

- Disable file and network sharing.
- Use secure websites (HTTPS).
- Employ VPN for encrypted connection.

<i class="fa-solid fa-car-tunnel fa-2xl" style="margin-right:20px; margin-top: 20px; margin-bottom: 25px"></i> Virtual Private Network (VPN)

- Encrypts internet traffic through a secure tunnel.

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

---

<!--
_backgroundColor: #5f8f9e
_color: white
-->
<h1>
  <i class="fa-solid fa-spray-can-sparkles fa-xl" style="margin-right: 15px"></i> Clean Desk Policy
</h1>

<i class="fa-solid fa-question-circle fa-2xl" style="margin-right:20px; margin-top: 15px; margin-bottom: 35px"></i> Purpose of a Clean Desk Policy

The Clean Desk Policy upholds the CIA principles:

- Confidentiality
- Integrity
- Availability

<i class="fa-solid fa-lock fa-2xl" style="margin-right:20px; margin-top: 15px; margin-bottom: 35px"></i> Security Concerns

An unorganized workspace can pose security risks:

- Unauthorized use of logged-in user accounts
- Access to sensitive documents

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

---

<!--
_backgroundColor: #5f8f9e
_color: white
-->

<i class="fa-solid fa-trash fa-2xl" style="margin-right:20px; margin-top: 20px; margin-bottom: 35px"></i> Implementation

The policy encompasses:

- Regular workspace cleaning
- Logging out before leaving
- Concealing confidential data

<i class="fa-solid fa-user-secret fa-2xl" style="margin-right:20px; margin-top: 40px; margin-bottom: 35px"></i> Defense against Espionage

Safeguards against:

- Employees
- Third-party personnel
- Misuse of identities

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

---

![bg center: 100%](assets/lock_screen.png)

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

---

<!--
_backgroundColor: #187d4d
_color: white
-->

# Part 3 - Conclusion

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

---

<!--
_backgroundColor: #187d4d
_color: white
-->

# Part 3 - Conclusion

<div class="columns">
<div>

## Password Recommendations

- Use a unique password for each account
- Utilize password managers for management
- Employ Multi-Factor Authentication (MFA)


</div>
<div>

## Clean Desk Policy

- The Clean Desk Policy supports the CIA principles

## Lock your screen!
</div>
<div>
</div>
<div>
</div>
</div>

<!-- 5 Minuten Pause
 -->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

---

<!--
_backgroundColor: #187d4d
_color: white
-->

<!--
# Zoom Poll / Quiz
-->

# Part 3 - Quiz

<!--
_backgroundColor: #187d4d
_color: white
-->

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

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
https://www.ncsc.admin.ch/ncsc/en/home.html
- Information is Beautiful
    https://www.informationisbeautiful.net/visualizations/worlds-biggest-data-breaches-hacks/
- Phishing quiz 
https://phishingquiz.withgoogle.com/

<div class="footer-outer">
  <p class="footer-passive">Part 1 - Information Security  | Part 2 - Malware & Phishing |</p>
  <p class="footer-active">&nbsp Part 3 - Authentication & Behaviors</p>
  <p class="footer-passive" ></p>
</div>

--- 

![bg](assets/open_circle_end.png)