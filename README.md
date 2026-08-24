# Project Check-ins: Fall 2026

Welcome to the semester project! As you review these milestones, please remember to stay on top of your deadlines, as they will come up much quicker than you might expect. Additionally, I highly recommend that you begin working on your mobile application in parallel with your database development. Even though the application itself isn't a formal requirement for the early submissions, building it side-by-side will ensure a much smoother integration phase and save you from a major time crunch at the end of the semester.

---

## Project Check-in 1: Scope, Schema, and Strategy (Due Week 7)

**Focus:** Problem definition, mobile platform constraints, relational algebra, and intentional AI usage.

**Deliverables:**

**Problem Definition and Mobile Scope:** 
Please clearly define the problem your application solves and establish a manageable scope for the semester. Your target platform should be either an iOS or Android mobile application. For example, if you were building an app like YourGains Tracker: Count Your Wins, you might note that your scope emphasizes tracking personal weight training progress over building social or gym-culture competition features.

**Initial Database Design and Mechanics:** 
Share your initial database design with the corresponding SQL. Include 5 example queries using relational algebra. Please ensure this design includes a minimum of two distinct tables, explicitly defining the primary keys for each and the specific foreign keys used to establish the relational links between them. I'd like to see you demonstrate the logical relationship between these tables and how your core queries will execute to support your app's main features.

**AI Utilization Plan:** 
Outline how you plan to interact with generative AI during the project. Please detail the specific agents you intend to use and provide a few example prompts. My goal is to help you develop long-term problem-solving mastery over simply delivering functioning code, so your plan should demonstrate how you will use AI to build self-reliance. For instance, your example prompts might show AI being used as a tutor to explain relational algebra concepts or help diagnose friction in SQL syntax, rather than just asking the agent to generate your entire schema.

---

## Project Check-in 2: Normalization and Architectural Evolution (Due Week 11)

**Focus:** Normalization (up to 3NF), anomaly resolution, Entity-Relationship (ER) modeling, and data integrity.

**Deliverables:**

**Schema Evolution and ER Modeling:** 
Take the foundational two-table schema from your first check-in and expand it to fully support your mobile app's growing needs. You'll map this updated architecture into a clear Entity-Relationship (ER) diagram to help visualize the new connections.

**Step-by-Step Normalization Demonstration:** 
Walk me through how you normalize your database up to 3rd Normal Form (3NF). Please include the intermediate steps (1NF and 2NF) so I can see your progression. To make sure everything is working as intended, keep your sample data values and facts consistent throughout the steps—this helps demonstrate that breaking down the tables doesn't lose any information or change your schema's core purpose!

**The Problem-Solving Journey:** 
Map out the functional dependencies in your data, and share some examples of insertion, deletion, or update anomalies you encountered in your early designs. Then, explain how your final 3NF structure resolves them. Please include a brief reflection on your troubleshooting process. I value seeing the mental effort and how you worked through the challenges to untangle the design just as much as the final diagram itself.

---

## Project Check-in 3: High-Level Integration & Demonstration (Due Week 16)

**Focus:** Object-Relational Mapping (ORM), APIs, application architecture, front-end validation, testing, and overcoming abstraction roadblocks.

**Deliverables:**

**Application Integration and Front-End Integrity:** 
It is time to connect your normalized database to your mobile application's higher-level interface! I'd like to see you implement the ORM or API layer and demonstrate how it interacts with your database to bring your app's core features to life. As part of this integration, please include front-end integrity and validation measures—such as catching invalid inputs before they reach the database—to ensure your app handles data securely and gracefully.

**Testing and Demo Video:** 
To show off your hard work, please record a demo video of your application working on either an iOS or Android device (or simulator). Along with the video, I'd like you to define a set of required test cases that cover your app's core functionalities. Please use these exact test cases to guide your demo video, walking me through how your app validates inputs and processes data step-by-step.

**Overcoming Abstraction Roadblocks:** 
High-level frameworks are incredibly helpful, but they can sometimes hide database errors or generate inefficient queries behind the scenes. Please isolate and share a specific roadblock where this happened during your development. Walk me through how you bypassed the abstraction layer to dig into and debug the underlying SQL. Documenting this troubleshooting process helps demonstrate your long-term problem-solving mastery and self-reliance—which I value much more than just seeing a perfectly functioning application layer!

[Hands-on Android Mobile Testing Tutorial](https://www.youtube.com/watch?v=tSVgS2eIpx0)
This tutorial provides practical guidance on recording and running automated mobile tests, which can be highly useful when planning and executing the test cases for your application demo.
