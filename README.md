# Project 2 Report

Read the [project 2 specification](https://github.com/feit-comp30019/project-2-specification) for details on what needs to be covered here. You may modify this template as you see fit, but please keep the same general structure and headings.

Remember that you must also continue to maintain the Game Design Document (GDD) in the `GDD.md` file (as discussed in the specification). We've provided a placeholder for it [here](GDD.md).

---

## Table of Contents

- [Evaluation Plan](#evaluation-plan)
- [Evaluation Report](#evaluation-report)
- [Shaders and Special Effects](#shaders-and-special-effects)
- [Summary of Contributions](#summary-of-contributions)
- [References and External Resources](#references-and-external-resources)

---

## Evaluation Plan

### Observational Technique - Cooperative Evaluation

- Analyst and participant evaluate the game together.
- Identified problems and potential solutions are discussed together with participants.
- Questions to ask participants:
   - How did the atmosphere of the game make you feel throughout your gameplay experience?
   - What aspect of the game stood out to you the most?
   - Was there any moment where you felt confused or uncertain about what to do next?
   - How did the eerie elements (SFX) affect your exploration of the game environment?
   - How are the controls?
   - What do you like most about our game?
   - What do you think could be improved?
   - What do you think of the difficulty of the game?
   - What do you think the game is lacking to achieve a more eerie effect?
   - What part of the game do you think is the most engaging? What part feels boring?
   - Were there any moments where the atmosphere didn’t feel eerie/unsettling? What contributed to that?
   - What are your thoughts when balancing your sanity bar and crafting light sources in the game? Did you face any challenges?

### Protocol for Game Testing - Cooperative Evaluation 

#### Overview

This protocol outlines a process for conducting a cooperative evaluation of test players engaging with a game, focusing on collaborative assessment and feedback.

#### Objectives

- Observe player interactions.
- Identify issues and gather feedback.
- Discuss potential solutions together.

#### Preparation

1. **Select Participants:** 
   - Recruit at least 5 players representing your target audience.

2. **Set Up Environment:** 
   - Ensure a comfortable, distraction-free space with all necessary equipment.

3. **Materials:** 
   - Prepare observation checklists and recording tools (with consent).

#### Protocol Steps

1. **Introduction (5 min):**
   - Introduce participants and explain the purpose of the evaluation.

2. **Gameplay Session (15 min):**
   - Allow participants to play while analysts observe and take notes.

3. **Cooperative Discussion (10 min):**
   - Gather for a discussion, encouraging participants to share their experiences.
   - Analysts facilitate conversation about identified issues and potential solutions.

4. **Wrap-Up (5 min):**
   - Summarise findings and thank participants for their input.

#### Post-Session

1. **Analyse Notes:**
   - Review notes and recordings, compiling a report on key findings.

2. **Prioritise Issues:**
   - Rank issues based on how often they occur and their impact, discussing with the development team.

3. **Follow-Up:**
   - Share findings with everyone involved and plan future evaluations if necessary.

---

### Query Technique - Questionnaire

- Participants will play the game on WebGL and fill out a survey form.
- The survey form will include sections to rate various aspects of the gameplay and give text feedback.
-  Things we want feedback/ratings on:
   - How does the player feel whilst playing the game?
   - What do they think about the sanity system (does it stress them out)?
   - Does the player feel incentivized to craft light sources?
- Link to questionnaire: https://forms.gle/CN99nJRuxXeCCNT59

### Query Technique Protocol for Game Testing

#### Overview

This protocol outlines the process for using questionnaires to gather feedback from participants after playing a game on WebGL. The goal is to assess various aspects of the gameplay and collect both quantitative and qualitative feedback.

#### Objectives

- Gather participant ratings on different gameplay aspects.
- Collect textual feedback for each gameplay aspect and the overall game experience.

#### Preparation

1. **Select Participants:**
   - Recruit at least 5 players representing your target audience.

2. **Set Up Environment:**
   - Ensure a comfortable, distraction-free space with access to the game on WebGL.

3. **Materials:**
   - Prepare a questionnaire that includes:
     - Rating scales for different gameplay aspects.
     - Open-ended text fields for feedback.

#### Questionnaire Structure

1. **Gameplay Rating Section:**
   - Include a rating scale (e.g., 1 to 5) for each aspect, such as:
     - Graphics
     - Controls
     - Difficulty
     - Enjoyment

2. **Feedback Section:**
   - Provide text fields for participants to offer detailed feedback:
     - Comments on each gameplay aspect.
     - Overall feedback on the game.

#### Protocol Steps

1. **Introduction (5 min):**
   - Introduce participants to the study and explain the purpose of the questionnaire.

2. **Gameplay Session (15 min):**
   - Allow participants to play the game on WebGL for the allocated time.

3. **Questionnaire Completion (10 min):**
   - Direct participants to fill out the survey form after gameplay.
   - Encourage them to provide honest feedback and explanations for their ratings.

4. **Wrap-Up (5 min):**
   - Thank participants for their time and contributions.
   - Remind them of the importance of their feedback for game development.

#### Post-Session

1. **Analyse Responses:**
   - Review the completed questionnaires, compiling quantitative ratings and qualitative feedback.

2. **Identify Key Themes:**
   - Look for common trends in ratings and comments to highlight areas for improvement.

3. **Follow-Up:**
   - Share findings with the development team and plan for any necessary adjustments based on participant feedback.

---

### Participants

- **Target Audience**: Teenagers and young adults aged 15 - 28.
- **Recruitment Methods**:
  1. Ask university friends and family to volunteer.
  2. Post on social media/online platforms such as Reddit.

---

### Data Collection

- **Quantitative Data**:
  - Gameplay rating: Game mechanic / Graphic / Theme.
  - Satisfaction.
  
- **Qualitative Data**:
  - Feedback: What they like/dislike, and what could be improved.

- **Tools**: Use a questionnaire (survey) for both quantitative and qualitative data.

---

### Data Analysis

#### For Observational Technique:
- **Affinity Diagram**: Analyse main findings by grouping similar insights.

#### For Questionnaire:
- **Summary Statistics**: Analyse summary statistics of quantitative data (i.e. mean, median, standard deviation).
- **Visual Graphs**: Produce graphs of the scores for each aspect of the game to identify areas that need improvement.

---

### Timeline
![Evaluation-Timeline](./ReportImages/evaluation_plan_timeline.png)

---

### Responsibilities

Who is responsible for each task? How will you ensure that everyone contributes equally?

| Team member | Responsibility            |
|-------------|----------------------------|
| Tan         | Observational Technique    |
| Cala        | Query Technique            |
| Don Lam     | Observational Technique    |
| Giang       | Query Technique            |

---

## Evaluation Report

In total, we conducted 7 surveys for a query technique, and 7 cooperative evaluations for an observation technique.

**Quantitative Data**
This is the average score from the survey for each category. (1-5 scaling)

| Category   | Average Score | Scaling                   | Note                                        |
|------------|---------------|---------------------------|---------------------------------------------|
| Enjoyment  | 3.57/5        | Higher = Very enjoyable   |                                             |
| Difficulty | 4/5           | Higher = Difficult        |                                             |
| Control    | 3.14/5        | Higher = Easy control     | The major problem is the camera control     |
| UI Layout  | 3.29/5        | Higher = Easy to navigate | The layout is simple but has some problems. |
| Audio      | 3.57/5        | Higher = Satisfy          |                                             |
| Graphic    | 3.43/5        | Higher = Satisfy          |                                             |
| Story      | 3.43/5        | Higher = Like the story   |                                             |

To summarise, the score shows that we need to improve our game in many aspects. The difficulty is quite high which impacts the overall enjoyment of gameplay. The camera control has too high sensitivity and is difficult to control using right-click. We will discuss the problems with UI later in the next section. Audio, graphics, and story, overall are acceptable because these categories are subjective and it happened when the participants might not like the art style or did not even care about the story.

**Qualitative Data**
This data was gathered from the observation and survey questionnaires. We categorised the findings into 6 main themes.

<div align="center">
  <img src="./ReportImages/AD1.jpg" width="600"/>
</div>

The text in the tutorial was slow causing some participants to ignore the tutorial and the starting tutorial did not explain all the game mechanics. All details were in the guidebook which some participants were difficult to locate. We increased the text speed and we make pan the camera to the castle so the players know there is a castle to explore.

<div align="center">
  <img src="./ReportImages/AD2.jpg" width="600"/>
</div>

Most of the participants said that the game was quite difficult such as they needed more resources spawned near the start location or the sanity reduction from standing near ghosts was too high causing the players to lose the game easily. We scaled down the difficulty in the current version so the player can explore and enjoy the game with a bit less challenge, however, it was not easy to win the game too.

<div align="center">
  <img src="./ReportImages/AD3.jpg" width="600"/>
</div>

These are the overall graphics and UI layout problems encountered by the participants. Mostly about unclear resources needed to craft, no indication of sanity reduction when near the ghost, and crafting UI was not clear enough. 

<div align="center">
  <img src="./ReportImages/AD4.jpg" width="600"/>
</div>

These are game mechanics that were not properly explained in the tutorial. We added a clear guideline for these mechanics in the current version.

<div align="center">
  <img src="./ReportImages/AD5.jpg" width="600"/>
</div>

This is good feedback from the participants.

<div align="center">
  <img src="./ReportImages/AD6.jpg" width="600"/>
</div>

These are bugs that were encountered during testing.

## Shaders and Special Effects

TODO (due milestone 3) - see specification for details

## Summary of Contributions

| Team Member | Contribution                                            |
|-------------|---------------------------------------------------------|
| Cala        | UI, Crafting, Shader, Video editing, Gameplay logic     |
| Tan         | Environment, Inventory, Gameplay logic, Report          |
| Don Lam     | Lighting, Fire Particle, Item placement, Gameplay logic |
| Giang       | Character, Fog Particle, Gameplay logic, Sound effect   |

## References and External Resources

Unity. (2000a). Unity Asset Store - The Best Assets for Game Making. @UnityAssetStore; Unity Asset Store. https://assetstore.unity.com/

Unity. (2000b). Unity Documentation. Docs.unity.com. https://docs.unity.com/
