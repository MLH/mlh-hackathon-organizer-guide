# Judging Plan

Judging has always been the biggest pain point for every hackathon organizer. This is due to the fact that while planning out the event, other than recruiting and finalising the judges, assign a certain time for judging, organising do not plan anything further, assuming everything can be managed on the day-of. But, in reality, if planned right, judging can be one of the easiest and the most smooth aspect of any hackathon.

At digital events, we've seen hackers working on smaller teams, resulting in a larger number of projects overall. As for any hackathon, our recommendation is always towards implementing a science-fair type of judging plan. This helps in saving time but is a little bit heavier on the logistics side.

## Science Fair Style Judging

In this particular judging style, assume your hackathon to be a science fair and every hacker team setting up their stall at assigned table numbers. Hackers present their hackathon project in front of the judges one by one as they arrive at their stalls, and judges score them accordingly. This way every hackathon attendee is getting a chance to demo in front of the judges and have the experience of presenting at the hackathon. To implement this in a digital world we would recommend you follow the below-mentioned steps.

### Time Requirement

Towards the end of the hackathon, take out some buffer time for the judging. This usually takes around 2 - 3 hours, depending on the number of submissions and judges.

### Calculating the required number of Judges

A typical calculation for the number of judges looks like follows:

$$J = ⌈(P * n * t )/ T⌉$$

Where,  
$$J =$$ Number of Judges  
$$P =$$ Number of Submitted Projects  
$$n =$$ Number of Judges for each project \(or number of rounds of judging per project\)  
\(MLH recommendation: 3 rounds per project\)  
$$t =$$ Time taken by a Judge per project \(MLH recommendation: 5 mins per project\)  
$$T =$$ Total time allocated for Judging \(in minutes\)

For eg.: Consider you have **150 projects submitted** at your hackathon and you have **allocated 2 hours for judging**. As per our recommendation, we are having **3 rounds of judging** per project and **5 minutes are allocated per project** for a judge to take their decision.

Now the calculation looks like:

$$J = ⌈(150 * 3 * 5) / 120⌉ = ⌈18.75⌉ = 19$$

Hence the number of **judges required is 19**.

### Allocating Projects

Allocating projects is more logistically heavy in a science fair style of judging because each judge cannot see every project.

To most efficiently allocate projects, I’d recommend manually dividing the total number of projects by the number of judges and multiplying the result by the rounds of judging per project. Then taking the upper limit of the result is how many projects each judge will see during the judging period.

Calculating this based on our last example:

$$N = ⌈(P * n )/ J⌉ = ⌈(150 * 3) / 19⌉ = ⌈23.68⌉= 24$$

Now using an Excel Sheet, assign all the projects a table number and accordingly assign each of your judges 24 table numbers such that each project is seen by 3 judges.

Now every judge will be having an allocated project they'll be looking at during the course of the whole judging process!

### Choosing Winners:

There're plenty of options with finalizing winners, but at MLH, we love to use Stack Ranking because it reduces a judges’ previous biases.

**Stack Ranking:** To run stacking ranking, you'll be needing to the following steps:

* Allocate projects to every judging according to what we discussed above.
* Ask each judge to view their projects and report back their top 3 best/favorite projects.
* Assign the top three following points:
  * 3 points \(First Place\) 
  * 2 points \(Second Place\)
  * 1 point \(Third Place\)

Now, you'll have a list of the project that appeared across multiple judges' top three favourites!

After all of the scores have come in, you’ll sort all of the scores in descending order. Then, the projects at the top will be your winning projects!

### A goto table to estimate the number of judges required:

|  | **Number of attendees** |  |  |  |  |  |  |
| :--- | :--- | :---: | :--- | :--- | :--- | :--- | :--- |
| **Time Allocated for Judging \(mins\)** |  | **45** | **60** | **90** | **120** | **150** | **180** |
|  | **100** | 9 | 7 | 5 | 5 | 4 | 4 |
|  | **200** | 15 | 12 | 9 | 7 | 6 | 5 |
|  | **300** | 22 | 17 | 12 | 10 | 8 | 7 |
|  | **400** | 29 | 22 | 15 | 12 | 10 | 9 |
|  | **500** | 35 | 27 | 19 | 15 | 12 | 10 |
|  | **600** | 42 | 32 | 22 | 17 | 14 | 12 |
|  | **700** | 49 | 37 | 25 | 20 | 16 | 14 |
|  | **800** | 55 | 42 | 29 | 22 | 18 | 15 |
|  | **900** | 62 | 47 | 32 | 25 | 20 | 17 |
|  | **1000** | 69 | 52 | 35 | 27 | 22 | 19 |
|  | **1100** | 75 | 57 | 39 | 30 | 24 | 20 |
|  | **1200** | 82 | 62 | 42 | 32 | 26 | 22 |

Any questions? Feel free to shoot an email to _league@mlh.io_ to discuss your Judging Plans!

