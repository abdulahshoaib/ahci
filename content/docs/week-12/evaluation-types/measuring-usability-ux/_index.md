---
title: Measuring Usability and UX
weight: 2
---

# Measuring Usability and UX

{{< katex />}}

Measuring usability and user experience helps determine whether an interactive system meets its design goals. Different measurement techniques are used depending on whether the focus is on task performance (**usability**) or user feelings and perceptions (**UX**).

Usability is usually measured using objective and quantitative metrics, while UX is often measured using subjective and qualitative methods. In practice, both should be evaluated together to gain a complete understanding of the system.

## Measuring Usability

Usability focuses on how effectively, efficiently, and accurately users can complete tasks.

### Common Usability Metrics

| Goal          | Measurement          | Example                               |
| ------------- | -------------------- | ------------------------------------- |
| Effectiveness | Task completion rate | 90% users successfully place an order |
| Efficiency    | Time on task         | Order completed in 2 minutes          |
| Safety        | Error rate           | 1 error per 50 uses                   |
| Utility       | Feature usage rate   | 75% of available features used        |
| Learnability  | Time to proficiency  | User learns system in 5 minutes       |
| Memorability  | Relearning time      | User relearns task in 1 minute        |
| Satisfaction  | SUS score or rating  | 87/100 usability score                |



### Quantitative Methods

#### Task Completion Time

Measures how long users take to complete a task.

Example:

* Find a restaurant
* Place an order
* Complete payment

Average completion time = 1.5 minutes

Formula:

$$
\text{Average Task Time} =
\frac{\sum \text{Task Completion Times}}
{\text{Number of Users}}
$$

Lower times generally indicate better efficiency.

#### Success Rate

Measures the percentage of users who successfully complete a task.

Formula:

$$
\text{Success Rate} =
\frac{\text{Successful Users}}
{\text{Total Users}}
\times 100
$$

Example:

* 100 users tested
* 90 users completed the task

Success Rate = 90%

#### Error Counting

Measures the number of mistakes users make.

Examples:

* Invalid form submissions
* Incorrect menu selections
* Failed payments

Formula:

$$
\text{Error Rate} =
\frac{\text{Number of Errors}}
{\text{Total Opportunities for Error}}
\times 100
$$

Lower error rates indicate better usability.

#### Feature Usage Rate

Measures how much of the available functionality users actually use.

Formula:

$$
\text{Feature Usage Rate} =
\frac{\text{Features Used}}
{\text{Total Available Features}}
\times 100
$$

#### Click Tracking

Measures:

* Number of clicks
* Navigation paths
* Interaction efficiency

Used to identify unnecessary steps in a workflow.

## Measuring User Experience (UX)

UX focuses on emotions, perceptions, satisfaction, trust, and enjoyment.

Because these factors cannot be measured directly with performance metrics, qualitative techniques are commonly used.

### Common UX Goals Measured

| UX Goal          | What is Measured                    |
| ---------------- | ----------------------------------- |
| Enjoyment        | Whether users like using the system |
| Engagement       | Level of user involvement           |
| Satisfaction     | Overall positive feeling            |
| Trust            | Confidence in the system            |
| Motivation       | Desire to continue using it         |
| Aesthetic Appeal | Perception of visual design         |



### Qualitative Methods

#### Interviews

Users are asked questions about their experience.

Examples:

* Was the system easy to use?
* What did you like most?
* What was frustrating?

Interviews provide detailed feedback and explanations.

#### Questionnaires

Users complete surveys after interacting with the system.

Example statement:

> The application was easy to use.

Responses are collected using rating scales.

#### Likert Scale

A common questionnaire format.

| Rating | Meaning           |
| ------ | ----------------- |
| 1      | Strongly Disagree |
| 2      | Disagree          |
| 3      | Neutral           |
| 4      | Agree             |
| 5      | Strongly Agree    |

Example:

"The app is easy to use."

Average score = 4.3

Formula:

$$
\text{Average Rating} =
\frac{\sum \text{User Ratings}}
{\text{Number of Responses}}
$$

This indicates a positive user experience.

#### Observation

Evaluators watch users interact with the system.

They observe:

* Hesitation
* Confusion
* Frustration
* Navigation difficulties

Observation often reveals issues users may not mention directly.

#### Think-Aloud Protocol

Users verbally describe their thoughts while completing tasks.

Example:

> "I can't find the checkout button."

> "I expected this icon to open the cart."

> "This page is confusing."

This method helps identify:

* Confusion points
* Mental models
* Incorrect assumptions
* Usability problems



## Example: Food Delivery App

### Usability Measurements

| Metric            | Result    |
| ----------------- | --------- |
| Success Rate      | 92%       |
| Average Task Time | 2 minutes |
| Error Rate        | 1.2%      |

### UX Measurements

| Method      | Result                                |
| ----------- | ------------------------------------- |
| Interview   | Users found ordering simple           |
| Survey      | Average rating 4.4/5                  |
| Observation | Some users struggled to find checkout |
| Think-Aloud | Payment page caused confusion         |



## Relationship Between Usability and UX

| Usability                   | UX                             |
| --------------------------- | ------------------------------ |
| Measures performance        | Measures feelings              |
| Objective                   | Subjective                     |
| Time, errors, success rates | Satisfaction, enjoyment, trust |
| Quantitative methods        | Qualitative methods            |

A successful interactive system should achieve both:

* High usability → users can complete tasks effectively.
* Positive UX → users enjoy the experience and feel satisfied.

