---
description: >-
  Check out our example template at https://hackp.ac/judgingexample - Email
  league@mlh.io if you need any help!
---

# Judging Plan

Judging has always been the biggest pain point for every hackathon organizer. This is due to the fact that while planning out the event, other than recruiting and finalizing the judges, and assigning a certain time for judging, organizing teams do not plan anything further, assuming everything can be managed on the day-of. But, in reality, if planned right, judging can be one of the easiest and the most smooth aspect of any hackathon.

Our recommendation is always towards implementing a science-fair type of judging plan.&#x20;

Structurally, we recommend having hackers submit 2 minute videos on your submission platform for the judges to review. Make sure they put a lot of love and care into their submission. Their video should be a demo of their hack, not a presentation. This is not needed for judging when science fair style, but can be a reference during final deliberations, and is always a good future reference if they want to include it on their resumes.&#x20;

To avoid confusion, the key is to **make sure hackers know exactly where you are in the schedule for judging.** Tell them you’re advancing to the next stage of judging when you do, or if judging is taking longer than expected, tell them how far along you are. Giving quick updates like “Our judges have reviewed about 50% of the projects!” goes a long way in keeping hackers engaged.

### Shortlisting/elimination rounds.&#x20;

We have decided not to work with hackathons with elimination rounds before projects are due, resulting in hackers having to leave the venue earlier than expected. We recommend having one pre-event shortlisting round online instead. All hackers should make it to the first judging round after submissions are due. Many events only have one judging round, though some may pick finalists to show off during closing ceremony. Keep in mind you will need \~7 minutes per team if you do this, 3-5 for the presentation and 2 minutes to set up the next group.&#x20;

## 1. Set Up Science Fair Style Judging

In this particular judging style, assume your hackathon to be a science fair and every hacker team setting up their stall at assigned table numbers. Hackers present their hackathon project in front of the judges one by one as they arrive at their stalls, and judges score them accordingly. This way every hackathon attendee is getting a chance to demo in front of the judges and have the experience of presenting at the hackathon. Judges can also ask questions if they need clarifications on any part of the project.&#x20;

For this method you need to assign table numbers. Before the event, make a map of the room with numbers so that judges can easily see where to go once assigned projects. Also at each table have a piece of paper with the project number. Make sure teams know to keep this visible. For optional added visibility, you can add the number to a stick(think kite dowel about a yard long that you can get at places like Home Depot) that makes the number visible over the top of hacker's heads.&#x20;

### Why not Judging Rooms?

MLH does not recommend having teams come to judges in a room. Those format types frequently have a hard time being fair because teams are only judged against the projects that happened to have the same room. Even if you have a final deliberation discussion to compare rooms, since only 1 room saw a team, ever single finalist project has to be re-pitched which relies on judge memory and notes. It is also hard to followup with team who may need to be asked questions - like asking them to share their code that they forgot to add to Devpost or to ask followup questions based on what your team finds during a cheating check.&#x20;

### What about Gavel/Gavel 2.0/Jury/Building your own system?

While these methods can be functional, your team needs to be very familiar with the process. Make sure the team does test runs before the event with your other organizers as fake judges. Also that your team can export the data at any point in time/has backups in case they system crashes so you do not lose all judging progress. Use last year's Devpost data to test it. Reach out to league@mlh.io if you need help getting an example export.&#x20;

We recommend events use stack ranking (detailed below) as it is easier for organizers who have not handled judging before. It is also harder to break a google spreadsheet than a custom platform.&#x20;

## 2. Timing and Assigning Judges

### Time Requirement

Towards the end of the hackathon, take out some buffer time for the judging. This usually takes around 2 - 3 hours, depending on the number of submissions and judges.

### Calculating the required number of Judges

A typical calculation for the number of judges looks like follows:

$$J = ⌈(P * n * t )/ T⌉$$

Where,\
$$J =$$ Number of Judges\
$$P =$$ Number of Submitted Projects\
$$n =$$ Number of Judges for each project (or number of rounds of judging per project)\
(MLH recommendation: 3 rounds per project)\
$$t =$$ Time taken by a Judge per project (MLH recommendation: 3 mins per project)\
$$T =$$ Total time allocated for Judging (in minutes)

For eg.: Consider you have **150 projects submitted** at your hackathon and you have **allocated 2 hours for judging**. As per our recommendation, we are having **3 rounds of judging** per project and **3 minutes are allocated per project** for a judge to take their decision.

Now the calculation looks like:

J= (150\*3\*3)/120 = 11.25 = 12

Hence the number of **judges required is 12**. Look at our[ judge communication and recruiting page](booking-your-judges.md) to get enough judges for your event!

### A go to table to estimate the number of judges required:

|                                       | **Number of attendees** |        |        |        |         |         |         |
| ------------------------------------- | ----------------------- | :----: | ------ | ------ | ------- | ------- | ------- |
| **Time Allocated for Judging (mins)** |                         | **45** | **60** | **90** | **120** | **150** | **180** |
|                                       | **100**                 |    9   | 7      | 5      | 5       | 4       | 4       |
|                                       | **200**                 |   15   | 12     | 9      | 7       | 6       | 5       |
|                                       | **300**                 |   22   | 17     | 12     | 10      | 8       | 7       |
|                                       | **400**                 |   29   | 22     | 15     | 12      | 10      | 9       |
|                                       | **500**                 |   35   | 27     | 19     | 15      | 12      | 10      |
|                                       | **600**                 |   42   | 32     | 22     | 17      | 14      | 12      |
|                                       | **700**                 |   49   | 37     | 25     | 20      | 16      | 14      |
|                                       | **800**                 |   55   | 42     | 29     | 22      | 18      | 15      |
|                                       | **900**                 |   62   | 47     | 32     | 25      | 20      | 17      |
|                                       | **1000**                |   69   | 52     | 35     | 27      | 22      | 19      |
|                                       | **1100**                |   75   | 57     | 39     | 30      | 24      | 20      |
|                                       | **1200**                |   82   | 62     | 42     | 32      | 26      | 22      |

### Allocating Projects

Allocating projects for overall judging is more logistically heavy in a science fair style of judging because each judge cannot see every project. The goal is to have each project seen at least 3 times, but not have judges see the same "sets". For example, we do not want teams 1-10 only judged against teams 1-10, so we stagger the teams the judges see. Spacing out projects helps make it more fair for overall judging.&#x20;

For categories that have fewer submissions(like AI or Hardware challenges/tracks), you can instead have 1-2 subject matter experts who are familiar with the category view just those projects and pick the winner that best fits the category. Your subject matter expert for a hardware category might be the president of the IEEE club on campus or a teacher familiar with hardware. If you have a large category(like best design), use overall judging to narrow down top teams then see who among them best fit the criteria for the category.

Check out the Readme on our [Judging Example Sheet](https://docs.google.com/spreadsheets/d/1eyfZmUMA63oG\_89l6n6zpHj\_o5V2xwS-gyndmTl5Z24/edit#gid=1202683513) for allocating judges to projects! This example process makes sure each team is seen by at least 3 different judges.&#x20;

### Judging Debrief

Once you assign your judges projects you are ready to release them to start visiting teams! Before they head out into the crowd, remind them of these key points:

* **They only have 3 minutes per team**. You want the process to be fair, and have time to see every team enough times, so keep to a strict timeline.
* **Focus on learning over profit.** Sorry to break it to you, but 99% of hackers are going to hackathons to have fun and learn something. It is rare that anyone goes to a hackathon to bootstrap a startup (Startup Weekend/StartupBus are not hackathons), and rarely do those people win hackathons because they spent their time creating a product rather than awesome technology. Occasionally, cool hacks (like [Grooply](https://www.twilio.com/blog/2010/05/live-from-the-techcrunch-disrupt-hackathon-demos.html), which became GroupMe) become products over time but rarely do they start out that way. Hacks are built as creative solutions to problems or simply for fun, not to make money.
* **They need to bring back top 3 projects of the set assigned.** Once they do this, they will be assigned additional sets as needed.
* **If they need help, go to X location.** Your helpdesk, your judging room on the side, a space by the front stage. Have a designated space to go to for help or to flag project they think might be cheating.

## 3. Choosing Winners

There're plenty of options with finalizing winners, but at MLH, we love to use Stack Ranking because it normalizes scores across judges. Some judges are super nice, and might give higher scores overall than a stricter judge. By using stack ranking, you eliminate the point variation and make it so teams earn points based on how they rank with each judge instead of as an overall score that depends on what the judge considers a 5/8/10.

**Stack Ranking:** To run stacking ranking, you'll be needing to the following steps:

* Allocate projects to every judging according to what we discussed above.
* Ask each judge to view their projects and report back their top 3 best/favorite projects.
* Assign the top three following points:
  * 15 points (First Place)
  * 10 points (Second Place)
  * 5 point (Third Place)

Now, you'll have a list of the project that appeared across multiple judges' top three favorites! After you've bubbled up your top projects, you should validate the results. Go check out the top 3-5 projects and make a final decision about winners. This is your hackathon. Make sure you're proud of the final results! Do a cheating check on all winners before you announce.

### Resources:

* Template: [Judging Expo Process ](https://docs.google.com/spreadsheets/d/1eyfZmUMA63oG\_89l6n6zpHj\_o5V2xwS-gyndmTl5Z24/edit?usp=sharing)

Any questions? Feel free to shoot an email to _league@mlh.io_ to discuss your Judging Plans!
