# Advance Directives: Creating a unified terminology for health professionals, patients, and data scientists

This project is designed to help build a set of unified, standardised terms and descriptions for advance directives. Advance directives are the instructions we give to medical professionals, family and friends for how we should be treated in the event that we temporarily or permanently lose decision-making capabilities. The most famous of these is DNR, or do not resuscitate, but there can be a wide variety of different directives based on our desires not to be ventilated, or receive organ transplants, and so on.

## Why is a standardised terminology necessary?
When communicating their needs to a healthcare professional, patients may have several instructions for the care they should receive in the event that they are not able to make decisions. These instructions may not be stored in a way that is legible by a medical professional, who should not have to guess the meaning behind them, or readable by decision support tools without analysing free text. The purpose of a unified terminology is to ensure that everyone involved in the patient's care can ensure that the patient's intentions are captured in data that can be easily interpreted by both humans and computers.

## What does this project entail?
There are several components to this project, which we are aiming to define:  
- Concepts: these represent distinct ideas within the terminology. For example, if someone wants to avoid being ventilated in the event of a terminal illness, these are two distinct concepts: invasive ventilation, and terminal illness.
- Each concept is categorised by its domain:
  - It may be a qualifier or a condition (e.g., in the event of terminal illness...), or
  - It may be an instruction (e.g., do not invasively ventilate).
- The relationships between concepts, as either siblings, parents, or children.
  - Sibling: Two concepts related on the same hierarchical level. For example, consent to tissue donation is a sibling to consent to organ donation.
  - Parent: A concept that may contain another concept would exhibit a parent/child relationship. For example, a conditional requirement of desiring to maintain "independence" can be considered a parent of being "able to feed self".
- The server. To make this a truly open-source project, all of the concepts and their relationships will be defined on a freely accessible server. This is so that it is possible for our terminology server to be accessed by anyone and everyone who wishes to ensure a more stable and useful way of defining advance directives.

## How can I contribute?
As with many terminology sets, it is important that each concept demonstrates a unique thought or intention, and each concept's relationship to its siblings or parents/children is defined.   
This is where you may be able to help! Please be mindful of the trade-offs: each concept must be unique and unambiguous, but it must also be able to fully represent an individual's intentions when combined with other concepts. We want to add concepts when this is not currently possible, and we want to define its relationship to other relevant concepts.  
  
If you think you have a contribution you would like to make, there are a few options:  
- If you are familiar with GitHub:
  - Create a pull request,
  - Update the relevant concepts in the Data folder, and
  - Submit the request.
  - We will try to review it within the next month.
- Email robin.blythe@qut.edu.au or reach out on LinkedIn: https://www.linkedin.com/in/robin-blythe-7428ba65/
