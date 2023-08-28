---
title: "Frij"
date: 2023-08-28T14:55:46-04:00
draft: false
categories: 
- "School Project"
---

###### [origin article](https://lydiascheng.notion.site/lydiascheng/Frij-5952e6328efb42d2bd232db8a126e6b3)

## What’s Frij?

************************Introduction & Value Proposition************************

![Untitled](img/articles/frij/Untitled.png)

**Frij is unlike any other fridge you’ve had before.** With a unique combination of online database and RFID technology, Frij helps you keep track of your food so you don’t have to. That being said, it makes it much easier to know which foods are about to spoil and gives you inspiration on how to use them, and notifies you when food has gone bad, so you can properly dispose of it.

---

## Why We Chose This Topic

**Motivation**

When thinking about some of the the larger issues in the world, a topic that came up was food waste. In fact, 108 billion pounds of food is wasted every year in the United States.

![Untitled](img/articles/frij/Untitled-1.png)

While 108 billion pounds is a ton of food, we also saw recognized this was an issue in our daily lives: whether it be forgetting to use up some lettuce we wanted to make a salad out of or seeing our friends throwing out leftovers because the simply forgot they existed.

Thus, we wanted to find a way to intervene at the consumer level and at throughout the various stages of food management.

---

## Determining Our Users, Pain Points, and Opportunities

************************Key Insights************************

### Observing Our Target Audience

**Contextual Inquiry**

We observed how users interacted with their food storage using contextual inquiry.

From which, we learned:

1. People want fresh vegetables when they cook
2. Fridge space is limited → makes it hard to organize
3. People struggle to find time to cook

![Untitled](img/articles/frij/Untitled-2.png)

---

![Untitled](img/articles/frij/Untitled-3.png)

### Exploring Users’ Daily Wants and Habits

**Diary Study**

We recruited 8 participants for our diary study and surveyed students and young working adults.

From which, we learned:

1. People cook fairly often—63.7% of participants cook multiple times a week
2. Individuals either create basic routines for preventing food waste or nothing
3. Access to ingredients at home is the most common factor that influences user experience

---

### Discovering User Pain Points

************************Journey Map************************

We mapped out users’ journey during their food storage process to determine user pain points.

From discovered the following pain points:

1. Users want to cook ← They struggle with time management
2. Users struggle to with knowing what to cook ← They are easily overwhelmed with too many options and have trouble with determining which ingredients to use first
3. Users struggle with limited food storage space ← This makes it incredibly hard to organize groceries, especially if the user has roommates.

![Untitled](img/articles/frij/Untitled-4.png)

---

### Testing Opportunties

******************************User Enactments******************************

Based on the previously determined pain points, we came up with the following user enactments that tested out a variety of concepts for grocery shopping, fridge organization, and tracking expiration.

![Untitled](img/articles/frij/Untitled-5.png)

User enactments taught our team the following insights:

1. Users prefer a combination of fridge organization and tracking expiration focused concepts.
2. Users prefer a moderate level of help from technology: for instance, while they tend to appreciate how much technology can make certain process easier, they still would like to go grocery shopping and pick exactly what they want to cook on their own.
3. Users’ favorite user enactment was perishable first, which created a kept track of the status of all of the items in the fridge, especially in terms of which items have already expired.

---

## The Answer to Our Research

****************************************Final System Concept****************************************

Based on our research insights, we came up with Frij.

![Untitled](img/articles/frij/Untitled-6.png)

---

### Reminds You What Foods to Throw Out

************************************************Expiration Notifications************************************************

Once an ingredient reaches its expiry date, users will be notified that it has gone bad.

These alerts can be expanded and dismissed.

[Link to Prototyped Flow](https://www.figma.com/proto/PGw57LaedoxS0gIW9gtsMu/Prototype?page-id=1%3A2&node-id=54%3A294&viewport=1328%2C-389%2C0.08&scaling=scale-down&starting-point-node-id=54%3A294)

![Untitled](img/articles/frij/Untitled-7.png)

---

![Untitled](img/articles/frij/Untitled-8.png)

### Keeps Track of All Your Food For You

**RFID Food Recognition**

With easy scrolling and simple categorization, view all of the items of your fridge.

Simply place any item in your fridge and it can add it to the system.

[Link to Prototyped Flow](https://www.figma.com/proto/PGw57LaedoxS0gIW9gtsMu/Prototype?page-id=1%3A2&node-id=54%3A148&viewport=1328%2C-389%2C0.08&scaling=scale-down&starting-point-node-id=54%3A148)

---

### Become Inspired When You’re Feeling a Little Lost

**Explore Inspiration**

When you’re worried about how to use up food that is about to expire, explore inspiration on ways to use certain ingredients.

[Link to Prototyped Flow](https://www.figma.com/proto/PGw57LaedoxS0gIW9gtsMu/Prototype?page-id=1%3A2&node-id=54%3A148&viewport=1328%2C-389%2C0.08&scaling=scale-down&starting-point-node-id=54%3A148)

![Untitled](img/articles/frij/Untitled-9.png)

---

## Video

{{< video src="/videos/Frij_Final_Video.mp4" type="video/mp4">}}

---

## What We Actually Made

**Prototype Shots + Key Prototyped Features**

![Untitled](img/articles/frij/Untitled-10.png)

### The Fridge

For the prototype, we built a fridge out of foam core, white duct tape, a particle photon, and an iPad. 

After deciding on the fridge prototype design, we cut all of the foam core pieces out and put them together with the help of duct tape.

After which, we utilized Particle Photon to add an LED which lights up when an RFID for a food item is recognized by the fridge system. This would be particularly helpful if the system is struggling to connect to the server or the screen is having issues.

### The Screens

Using Figma, we designed all of the screens and screen interactions for the fridge. Feel free to further explore the prototyped flows, using [this link](https://www.figma.com/proto/PGw57LaedoxS0gIW9gtsMu/Prototype?page-id=1%3A2&node-id=54%3A294&viewport=1328%2C-389%2C0.08&scaling=scale-down&starting-point-node-id=54%3A294).

![Untitled](img/articles/frij/Untitled-11.png)

---

## How it Would Ideally Work

**Ideal System Proposal**

All food items from the grocery store would already include an RFID tag. Thus, when a user places an item in the fridge, the LED lights up showing how the system recognized RFID tag from the food item. 

The database and cooking inspiration would be located on the internet. Thus, the fridge would use WiFi to access the database containing all the information regarding food item’s expiration dates and update it accordingly.

To determine when food has gone bad, the fridge would use the expiration date from the RFID tags as the default value. However, to account for inaccuracies regarding the expiration dates, there would be a chemical sensor in the fridge, which would update the expiration date for the corresponding food item accordingly.

![Untitled](img/articles/frij/Untitled-12.png)

---

## Reflection

### Limitation for Our Design

In terms of limitations, Frij is mainly designed for groceries rather than leftovers. Thus, if a user adds leftovers or meal prep to the fridge there is no way of adding it to the fridge system, unless the user somehow adds an RFID tag along with the expiration information to the food item. This also applies for reusable container since the food item within the container will vary and thus the corresponding expiration date will also vary.

### Next Step to Realize the System

Frij will be realized in ~10 years. The next steps to realize this system will be to place RFID scanner within the fridge and for every item from the grocery to come with an RFID. Additionally, this design is also reliant on a chemical sensor that can determine when food is going bad and what food is going bad. 

### Learning from Prototyping and Video Development

In terms of prototyping, it helped us learn how to build physical objects and think about it from a human factors perspective, rather than only considering the UX of the screens and the screen interactions. Learning how to build a physical prototype was very new to our team and learning not only how to do so, but to iterate on our designs was a learning experience.

---

## Appendix

- [Milestone 1 | Concept Proposal](https://docs.google.com/document/d/1seHi7GhH83VqxiFtZh3REv1MQuOCpSWblKk4P6SenhU/edit?usp=sharing)
- [Milestone 2 | Survey & Diary Study](https://www.figma.com/proto/zbNNmFwzmYrhHbGvdq9oLw/Milestone-2?page-id=1633%3A28&node-id=1633%3A34&viewport=539%2C453%2C0.04&scaling=contain&starting-point-node-id=1633%3A34) ([Empathy Map](https://www.figma.com/file/D9cNgmmfrEXluFkKROeSEW/Empathy-Map?node-id=0%3A1), [Journey Map](https://www.figma.com/file/CRzzXWybehCjoXxbaZJapV/Journey-Map?node-id=0%3A1))
- [Milestone 3 | Experience Prototyping & Demo Plans](https://docs.google.com/document/d/1TpKmkM447UWoAMvd63YULGHWxq2r0DfvKOXP-3NpwtU/edit?usp=sharing)
- [Milestone 4 | Prototype, Presentation, & Demo](https://www.figma.com/proto/Gtgkh2JlJbDeqmNr7lpQ9t/Final-Presentation?page-id=7956%3A2&node-id=7959%3A24&viewport=194%2C-363%2C0.11&scaling=scale-down-width&starting-point-node-id=7959%3A24)
