---
hackname: PoliticalPartyAgreementCalculator
quicksummary: Question and Answer form to calculate agreement with political parties
resource: true
categories: [hack]
---


Motivation
========
I believe that most people in democracy choose their vote based on emotions and it is 
difficult for them to understand which political party is closer to their mindset.

This project tries to help people to choose the right decision.

PoliticalPartyAgreementCalculator
========

**Are you not sure which political party to vote for?**

Imagine there are two political parties: Cat Party and Mouse Party. 

Then as a possible voter you land into the Question And Answer Form and you have to reply
to these two questions:

* Do you agree to prohibit that mice make holes in the walls to keep safe?  
* Do you agree to prohibit cats to run?

You can reply Yes, I don't care or No.  
 
Once you answer to all questions the agreement is calculated. 

We have the answers to each question for each political party: Cat Party voted
in favour of the first decision, but voted against the second one. Mouse Party the opposite. 

Given a voter that would have replied Yes to the first question and No the second one.

Then we would say to the voter:

You agreed the most with Cat Party because:

For question "Do you agree to prohibit that mice make holes in the walls to keep safe?", you
voted yes and Cat Political Party did the same. It sums +1.
For question "Do you agree to prohibit cats to run?", you
voted no and Cat Political Party did the same. It sums +1.

And so on for the rest of political parties, explaining the score and the agreements and 
disagreements.

Plan
======

* Iteration1
  * Build the form with the hardcoded questions and answers of one example
* Iteration2
  * Allow to create questions and political parties and answer from the political
    parties to the questions. 


Who's Participating?
--------------------

* [David Clavijo](/tamedia-hackdays/whoami/davidclavijo)
* Further help/ideas welcome...
