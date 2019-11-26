# Practicing PSIP for the first time on your own: how to create progress tracking cards (PTC)

If you haven't already, take a look at [why practice PSIP ](why_practice_PSIP.md), [Step 1](how_to.md), and [Step 2](how_to_set_goals.md) to get started on your own. The explanation below includes excerpts from the [BSSw PSIP Overview](https://github.com/betterscientificsoftware/PSIP-Tools/blob/master/PSIP-Overview.md):

Assuming you've completed [Step 1](how_to.md) and [Step 2](how_to_set_goals.md) of PSIP, you are ready to create your first progress tracking card.

## Step 3: Construct a Progress Tracking Card (PTC).

A PTC is a brief document containing the target, or goal of the planning activity, title of the topic of improvement, and a step-by-step list of activities or outcomes. Each planning activity will have its own PTC. You can use any of the existing PTCs in the [PTC catalog](https://github.com/bssw-psip/ptc-catalog); or define your own PTC or modify PTCs found in the catalog. The purpose of the PTC is to help you and your team set and achieve improvement goals. The PTC is not a tool for external assessment or comparison with other projects. In fact, since PTCs are custom-designed for each project, comparisons are typically not possible, so don't worry if your PTC ends up becoming one of a kind. 

To walk through the process of creating a PTC, open a new tab so you can follow the steps in the [ptc template](https://github.com/bssw-psip/ptc-catalog/blob/master/.github/ISSUE_TEMPLATE/card-submission.md) while considering the following scenario:

*Your team is planning a significant refactoring of your software base. As part of the refactoring, you want to introduce unit testing, applying it to the newly refactored code. You'd also like to establish a new policy for the way your team introduces unit testing. Presently you do not have unit testing in place.* 

### Name your PTC, and provide a short description.

Create a short name that covers the topic of your card. In this scenario the name "UnitTesting" would be appropriate. Then provide a brief description of the the goal (target) that you are trying to reach with this card. In this case, "apply unit testing policy to newly refactored code" would be a good description of your goal.

### Create a user story.

Generating a user story will help you keep you focused on your goal, and provide context. A user story is a statement that can be phrased as "As a _____, I want _____ so that _____." In this case a good user story may be:

*As a **software developer**, I want to **create a unit testing policy covering refactored code for my team** so that **I can verify that certain functions of my code are working as expected."***

### Create a numbered list that reflects the scores (often from zero to five) you will give yourself as you achieve specific stages toward your goal. 

Two guidelines for creating PTCs are: 1) create steps that involve agreement from your team, and 2) try to have an artifact, or measurable outcome for each step like a policy, document, etc. In addition each item in the list is a qualitative description that illustrates what it means to reach that score. Zero should represent a starting state, and the highest number should represent fully achieving the overall goal, keeping in mind that each step may also incorporate outcomes or artifacts along the way to completion. See the example below for a PTC which can also be found at [Step 3: Construct PTC](https://github.com/betterscientificsoftware/PSIP-Tools/blob/master/PSIP-Overview.md):

Name: Unit Testing. Target: Create unit testing policy covering refactored code. Score (0 – 5) descriptions below.	
- [ ] 0 	No unit testing.
- [ ] 1 	Unit testing implemented for one example refactored class.
- [ ] 2 	Two developers using unit testing process.
- [ ] 3 	Unit testing developer documentation completed.
- [ ] 4 	All developer trained to write unit tests.
- [ ] 5 	New policy established: All refactored code is covered by unit tests.

## Step 4: Record Current PTC Values.

Now that you have your PTC, you can Use your PTC in meetings with your team to remind everyone of your goals, and to determine whether you have met them. As seen below, you can record baseline capabilities and track progress (0-5 are suggested) for each PTC.

- [x] 0 	No unit testing.
- [ ] 1 	Unit testing implemented for one example refactored class.

...and so on.

### Include any comments that will clarify definitions and terms used in your PTC. 
Include links to materials that may provide additional context. For example, you may eventually decide to define the terms of the policy that has been established, or provide a link to the policy itself.

Next, you will create and execute your [practice improvement plan](how_to_execute_plan.md).






