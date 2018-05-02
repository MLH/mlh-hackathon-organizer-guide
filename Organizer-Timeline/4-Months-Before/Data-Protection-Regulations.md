# Data Protection Regulations
**Before reading this, please do note that the information here has not been added by a lawyer. This is instead a series of guidelines. If in doubt, always seek professional legal advice.**

This is the excitement you came for - data protection regulations! Unfortunately, every single hackathon that stores data on hackers needs to make sure they have policies on how that data is used and stored. Whilst this sounds like a dull task, it's an important one, and these guidelines should help to make sure you're all set.

## [General Data Protection Regulation (GDPR)](https://www.eugdpr.org/)

The biggest thing at the moment is the General Data Protection Regulation, or GDPR for short. Coming into action from May 25th, 2018, GDPR is a set of data protection regulations similar to, but more stringent than the Data Protection act in the UK, or HIPAA in the US.

These regulations protect all EU citizens, and **apply to anybody holding data on EU citizens, including entities not in the EU but with EU attendees.** This means that if you're running your awesome hackathon in New York but want to invite some of the cool folks from the EU, you will have to make sure their data is held and processed in compliance with GDPR.

Here's a list of tasks you can follow to make sure your event is GDPR compliant. If you want to read more on each element, we've linked out to a guide, and also explained a few of the key concepts below.

## Once you know you're running an event

- [ ] Have a plan set up to erase somebody's personal data if they ask
- [ ] Have a plan set up to give somebody all the personal data you hold on them if they ask
- [ ] Make sure to keep a record of all the ways you're going to store personal data, and justifications for why you're doing it
- [ ] If you're sending emails, they should only be to people who have actively consented to you having their email address

## When you set up the website / registration

- [ ] Ask clearly for consent, do not pre-tick consent boxes, be clear about what somebody's data will be used for
  - [ ] Do not make it mandatory to sign up to a mailing list in order to attend an event
- [ ] Have a page up with a Privacy Policy (you can find an example [here](https://github.com/MLH/hackathon-organizer-guide/blob/master/Organizer-Resources/Example-Privacy-Policy.md)) detailing what data you ask for, and why

## Once you have gathered personal data through registration etc

- [ ] Be very careful about how this data is shared. Sharing includes:
  - [ ] Printing out an attendee's details without having their prior consent
  - [ ] Sending CV's to sponsors without an attendee's consent
  - [ ] Giving access to the data store to unauthorised users
- [ ] Make sure you store this data in a machine readable format (XML, JSON, CSV)
- [ ] Make sure the data is stored securely
- [ ] Make sure you delete all personal data once you no longer have a use for it
- [ ] Make sure to update the data you hold on somebody if they ask
- [ ] Make sure to be secure with the data you hold

If you follow these rules, you should be absolutely fine - but if you're interested in reading more, here is some more context, using SharkHacks as an example

## The Core Principles

### [Active Consent](https://ico.org.uk/for-organisations/guide-to-the-general-data-protection-regulation-gdpr/lawful-basis-for-processing/consent/)

This is a general term that we’ll use to cover a few things, but ultimately is one of the biggest points in GDPR. Any consent has to be explicit, informed, and freely given - if consent is mandatory, for the functioning of the event, it also has to be for legitimate use. Let’s run through SharkHack's checklist for when you sign up:

**Explicit**
- I am ticking a box to say that I consent to the MLH Code Of Conduct
- **I am ticking a separate box to say that I consent to the the Privacy Policy operated by SharkHacks**
- **I am ticking a separate box to say that I consent to being put on SharkHack’s tech society’s mailing list**
- **I am ticking a separate box to explicity consent to having SharkHacks share my data with Major League Hacking**
- **I am ticking a separate box to consent to having SharkHacks share my CV with sponsors.**

SharkHacks cannot bundle two of these points together, so that consenting to the Code of Conduct also means that I consent to sharing my CV, as blanket consent is not allowed under GDPR.


**Freely Given**

You cannot pre-tick any of these boxes for the applicant, as this becomes *passive* consent, which is also not allowed.

**Informed**

When I tick any of the above boxes, I have been told what it means to agree to the code of conduct, I know what data is being shared with Major League Hacking ( and why! ), I know what the mailing list is for, and why it’s relevant to me.

**Legitimate Use**

SharkHacks also cannot remove my access to SharkHacks based on my not consenting to share my CV, or have my email put on the society’s mailing list, as these are not required for the functioning of the event.

The code of conduct, however is required for me to access the event with a legitimate reason.

**Protips for organisers**

Separate fields to consent to separate points, make sure the hacker is informed on what each consent implies, and never assume consent through lack of saying 'no'. Be prepared for a hacker to withdraw consent that they have already given.

### [Fairness and Transparency](https://ico.org.uk/for-organisations/guide-to-data-protection/privacy-notices-transparency-and-control/?q=consent)
This means that when SharkHacks asks for my personal data when I sign up, they must clearly notify me what information they collect from me, as well as how SharkHacks plans to use that information. For example, SharkHacks must let me know that they will be storing my check-in data, t shirt size, dietary requirements etc.

They must also let me know if, as an MLH member event, they will be passing any of that information ( like my check-in data ) along. This can all be stored in your *privacy notice* that is linked to as part of the form.

**Protips for organisers**

Have a page with your privacy notice, detailing all the information you ask for, and why you ask for it. This is especially important in cases like asking for CVs, but also think about check-in data.

### [Purpose Limitation](https://ico.org.uk/for-organisations/guide-to-data-protection/principle-2-purposes/)
SharkHacks can collect personal data only for specified, explicit, and legitimate purposes. They cannot process personal data in a manner that’s incompatible with those purposes.

So when I sign up for SharkHacks, they have to let me know about any processing it plans to do with my data ( for marketing purposes, for t-shirt size estimation ) in that privacy notice we mentioned earlier. If the privacy notice does not mention handing checkin data to Major League Hacking, then SharkHacks cannot hand that data over.

**Protips for organisers**

Always check your privacy notice when asking for new information. If the new information isn’t mentioned, either remove the request for new information, or update your privacy policy.

### [Data Minimisation](https://ico.org.uk/for-organisations/guide-to-data-protection/principle-3-adequacy/)
SharkHacks can collect only personal data that’s adequate, relevant, and limited to what’s necessary for the intended purpose.

When I sign up for SharkHacks, it’s important that they’re not asking for irrelevant information. I’m okay with them asking about my name, dietary requirements, and where I go to university, but is it relevant to ask about my religious beliefs? Is a CV absolutely necessary?

**Protips for organisers**

Constantly challenge why you’re asking for personal details. Do you really need to give sponsors CVs as incentive? Does a hacker’s religious beliefs affect their ability to attend the hackathon? Be conscientious and minimalist, and always justify the data you ask for.

### [Accuracy](https://ico.org.uk/for-organisations/guide-to-data-protection/principle-4-accuracy/)
This is an easy one - if a personal detail about myself changes ( name, address, gender, etc ), and I notify SharkHacks, they must update that information.

**Protips for organisers**
If a hacker asks you to change a record you have on them, change it.

### [Data Deletion](https://ico.org.uk/for-organisations/guide-to-data-protection/principle-5-retention/)
This covers my ‘right to be forgotten’. If I ask SharkHacks to delete my data, they have to delete all the data they have stored on me. It also covers the length of time in which personal data about somebody can be kept - 'as long as reasonable' - meaning that as soon as you no longer have use for the data, it should be deleted

**Protips for organisers**

If a hacker asks you to delete the data you have on them, delete it and notify any third parties that this request has been made.

### [Security](https://ico.org.uk/for-organisations/guide-to-data-protection/principle-7-security/)
I want to be sure that SharkHacks is keeping my personal data secure. At the very least, you want to try and follow basic security guidelines - HTTPS on any forms, restriction of access to only necessary users, make sure that data is stored as securely as possible etc. If you’re hosting the data yourself, make sure it’s encrypted.

### Accountability
A data controller is responsible for implementing measures to ensure that the personal data it controls is handled in compliance with the principles of GDPR. Essentially, when recording data, an organisation must keep a record of how and why it collected the data.

**Protips for organisers**

Record and justify your signup process and the data it gathers.

## [ My individual rights as a hacker](https://ico.org.uk/for-organisations/guide-to-the-general-data-protection-regulation-gdpr/individual-rights/)

**Data Access:** I can confirm if SharkHacks are processing my data, if they are, I can request information about processing ( including data processed ), purposes of processing, and any parties with which the information was shared.

**Right to object:** I can object to SharkHacks using my data for certain cases, for example, direct marketing purposes.

**Data Rectification:** I can request that SharkHacks update the data they have on me.

**Restriction of Processing:** I can request that SharkHacks stop access to, or modification of my personal data - including marking it so that it will not be further processed by any party.

**Data Portability:** In certain cases, I can request that SharkHacks provide my data in an easily consumed format ( for example, a .csv file ).

**Right to Erasure:** Or the right to be forgotten, means that I can request the deletion of any data regarding me in situations such as:
- When the data is no longer needed for the purpose it was originally designated
- When I withdraw consent
- When I object to processing where SharkHacks can not prove a legitimate overriding interesting the processing
  - So I would not be able to object to having my check-in data collected, as SharkHacks has a key interest in using that data to determine whether or not I’m a bad actor, unless I decided that I no longer wanted to attend the event

## Other Resources

- https://ti.to/gdpr/ - a handy guide for conference organisers!
