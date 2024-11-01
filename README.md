# Matthew's Work Health Analysis

## Introduction
After learning the basics of PowerBI and a bit of light experimenting, I felt it was time to start a project with the goal of creating a presentable dashboard, which I hadn't done before. Instead of looking for data on the internet, I wanted to produce something closer to my personal life. I started looking around at how I could get data from my environment, but being someone that rarely recorded events, it was hard to find. I was hopeless and close to going down the unoriginal road and doing a sales analysis dashboard... Then came, Matthew.

Now you might be wondering, who in the world is Matthew? Forgive me for the late introduction, Matthew is actually my roommate. I have shared a home with Matthew for 10 months as of this README, and having lived with him for this long, I can't help but notice some interesting quirks about him.
1. He is a lover of pasta, and MUST eat it at least twice a week. (Note: He once told me eating pasta was scientifically proven to make people happier, not sure how true that is...)
2. He is a true believer of dishwashers; he trusts that anything can be cleaned in a dishwasher.
3. He wears his Apple Watch religiously, and I mean RELIGIOUSLY. He takes it off once a day to charge, and wears it 23/7 to work, sleep, etc.

One day, a thought came across my mind. Given all the time he wears his Apple Watch, there must be a lot of data recorded in it. And sure enough, when I got him to export it, it was heaps! I had always been a fitness enthusiast, tracking calories in and out, taking notes of my workouts, but the one thing I never had was the consistency (patience) to wear my Apple Watch as much as Matthew does. And this was the start of it all.

## Documentation
Using a free Apple Health XML to CSV converter (https://www.ericwolter.com/projects/apple-health-export/), I was able to safely convert and retrieve all the data. Once I had exported the data out of the Apple Health app, there were 30-40 datasets available. Some interesting ones I found were: 
- Height (irrelevant since Matthew is neither growing nor shrinking)
- Body Mass (A good one to track, if only Matthew would..)
- Oxygen Saturation (What how?)
- Walking Asymmetry Percentage (sure)

The Apple Watch had data on all sorts of things, but I gathered the ones that I could effectively use to deliver pertinent information;
- Sleep Analysis
- Active & Basal Calories Burned
- Step Count
- Walk Speed
- Stand Time

Matthew was not someone who often exercised, so I knew I couldn't make a fitness dashboard, but virtually all that the Apple Watch detected and collected were fitness related. The only times he would move a lot were at his job, Woolworths. He is a Team Member/Duty Manager, and was basically moving constantly during his shifts.
