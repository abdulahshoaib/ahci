---
title: Use Cases
weight: 7
---

# Use Cases

Use cases are used to capture interactions between users and a system.

They focus primarily on **functional requirements** and describe how users and the product interact to achieve a goal.

Use cases can be used during both requirements gathering and design.

## Purpose

Use cases help to:

- Capture functional requirements.
- Describe user-system interactions.
- Clarify system behavior.
- Identify required system functionality.
- Communicate requirements to stakeholders and developers.

## Characteristics

- Focus on interactions.
- Describe tasks step-by-step.
- Show how users achieve goals using the system.
- Can be written with different levels of detail.

## Types of Use Cases

### Essential Use Cases

Essential use cases focus on user intentions and system responsibilities.

They:

- Divide interactions into tasks.
- Avoid implementation details.
- Describe what happens rather than how it is implemented.

### Detailed Use Cases

Detailed use cases provide a more complete description of interactions.

They include:

- Normal course of events
- Alternative courses
- Error handling
- Additional interaction details

## Essential Use Case Example

### Retrieve Visa Requirements

| User Intention | System Responsibility |
|----------------|----------------------|
| Find visa requirements | Request destination and nationality |
| Supply required information | Obtain appropriate visa information |
| Obtain a copy of visa information | Offer information in different formats |
| Choose a suitable format | Provide information in the selected format |

## Detailed Use Case Example

### Retrieve Visa Requirements

#### Normal Course

1. The product asks for the destination country.
2. The user enters the country name.
3. The product validates the country.
4. The product asks for the user's nationality.
5. The user enters their nationality.
6. The product checks visa requirements.
7. The product displays the visa requirements.
8. The product asks whether the information should be shared on social media.
9. The user provides the necessary social media information.

## Alternative Courses

### Invalid Country Name

4.1 The product displays an error message.
4.2 The process returns to Step 1.

### Invalid Nationality

6.1 The product displays an error message.
6.2 The process returns to Step 4.

### No Visa Information Found

7.1 The product displays an appropriate message.
7.2 The process returns to Step 1.

## Benefits of Use Cases

- Capture functional requirements clearly.
- Show how users interact with a system.
- Help identify system responsibilities.
- Support requirements analysis and design.
- Provide a structured description of user tasks.
- Help uncover alternative and error situations.
