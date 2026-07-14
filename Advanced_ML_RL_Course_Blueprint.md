# Advanced Machine Learning -- Reinforcement Learning

## Activity-Centric Course Blueprint (1-1-1 Model)

### Course Information

-   **Course:** Advanced Machine Learning -- Reinforcement Learning
-   **Programme:** B.Tech CSE
-   **Semester:** VI
-   **Pattern:** 1-1-1 (Lecture + Tutorial + Lab)
-   **Duration:** 15 Weeks
-   **Contact Hours:** 45 (15L + 15T + 15P)

## Vision

Students progressively build an intelligent reinforcement learning agent
throughout the semester. Every activity contributes to a single evolving
GitHub repository.

## Course Outcomes

1.  Explain reinforcement learning concepts and formulate sequential
    decision problems.
2.  Model environments as Markov Decision Processes and evaluate
    policies.
3.  Design RL solutions using Dynamic Programming, Monte Carlo and
    Temporal Difference learning.
4.  Implement and evaluate Deep Reinforcement Learning algorithms using
    modern frameworks.
5.  Critically analyse AI-generated RL implementations and communicate
    design decisions.

## Semester Modules

  Module      Weeks Theme                                 Activities
  -------- -------- ----------------------------------- ------------
  M1           1--2 RL Foundations                                 6
  M2           3--4 MDPs                                           6
  M3           5--6 Dynamic Programming                            6
  M4           7--8 Monte Carlo                                    6
  M5          9--10 Temporal Difference                            6
  M6         11--12 Deep Q Networks                                6
  M7         13--14 Policy Gradient & Actor-Critic                 6
  M8             15 Capstone, Ethics & AI-assisted RL              3

**Total Activities: 45**

------------------------------------------------------------------------

# Weekly Activity Template

Each week contains: - **Lecture:** Concept introduction +
misconception + worked example - **Tutorial:** Guided reasoning + AI
critique + retrieval quiz - **Lab:** Coding + experimentation + GitHub
submission

------------------------------------------------------------------------

# Activity Map (#commment: only design an activity which can be graded, also consider autograding)

## Module 1: Foundations of Reinforcement Learning (Weeks 1–2)

1.  #### Is Reinforcement Learning the Right Paradigm?; Driving Question: Why can't supervised or unsupervised learning solve every sequential decision problem?; Student Evidence: A comparative concept map, A one-page justification; Bloom Level: Analyze; Assessment: Rubric-based(conceptual accuracy, quality of reasoning, clarity of presentation); Feedback: Addressing Misconceptions, Highlighting strength in reasoning, suggesting improvements.
2.  #### Modeling the World as an RL Problem; Driving Question: Can every real-world problem be represented as a reinforcement learning problem?; Student Evidence: A formal RL representation of one real-world problem (e.g., autonomous driving, elevator scheduling, recommendation systems, traffic management), A one-page explanation justifying the choice of states, actions, rewards, and episode termination conditions; Bloom Level: Apply; Assessment: Rubric-based(Correct Indentification of RL components, Justification of modelling decisions, presentation Quality); Feedback: Modelling Assumptions and completeness.
3.  #### Investigating an Unknown Agent; Driving Question: Can we infer an agent's objective only by observing its behaviour?; Student Evidence: Observation log of at least 100 episodes of CartPole, Learning Journal describing behaviour patterns, A hypothesis explaining the agent;s objective and expected reward structure; Bloom Level: Analyze; Assessment: Rubric-based(Quality of observations, logical hypothesis formulation, evidence supporting conclusions); Feedback: Quality of observations, encouragement to refine their hypotheses
4.  #### Evaluating AI as a learning partner; Driving Question: Can we trust AI-generated explanations of Reinforcement Learning?; Student Evidence: An Annotated comparision between an AI-generated explanation and Sutton & Barto's explanation, Identification of at least five conceptual similarities or differences, Recommendation regarding the reliability of the AI explanation; Bloom Level: Evaluate; Assessment: Rubric-based(Identification of conceptual differences, Critical evaluation, Quality of Recommendation); Feedback: Common misconceptions identified by AI
5.  #### Constructing the Reinforcement Learning Knowledge Network; Driving Question: How are the fundamental concepts of Reinforcement learning connected?; Student Evidence: A concept network linking major RL concepts, Short explanations for every relationship shown; Bloom Level: Analyze; Assessment: Rubric-based(Completeness, Accuracy of Relationships, Visual Clarity); Feedback: Improving concept maps after peer discussion
6.  #### Builiding a Research Learning Portifolio; Driving Question: How can evidence collected throughout the semester demonstrate learning?; Student Evidence: Github respository, Portfolio template, reflection describing personal learning goals for the semester; Bloom Level: Create; Assessment: Rubric-based(Portfolio organization, Documentation quality, Reflection); Feedback: Repository Structure and suggestion for maintaining a professional learning portfolio

## Module 2: Markov Decision Processes (Weeks 3–4)

7.  #### Is the world really Markovian?; Driving Question: Do real-world decision-making problems satisfy the Markov Property?; Student Evidence: Analysis of two real-world systems, written argument discussing whether the Markov Property holds; Bloom Level: Analyze; Assessment: Rubric-based(Correct application of the Markov Property, Logical argumentation, clarity); Feedback: Alternative viewpoints and encourage revision
8.  #### Can policy values be computed without programming?; Driving Motivation: Can policy values be computed without programming?
9.  Bellman equation worksheet.
10. Implement policy evaluation.
11. AI-generated Bellman equations: detect mistakes.
12. Policy iteration implementation.

## Weeks 5--6 (Activities 13--18)

13. Value iteration walkthrough.
14. DP derivation exercise.
15. Implement value iteration.
16. FrozenLake optimisation challenge.
17. Debug a faulty DP implementation.
18. Retrieval quiz + reflection.

## Weeks 7--8 (Activities 19--24)

19. Monte Carlo intuition.
20. Blackjack return estimation.
21. First-visit vs Every-visit comparison.
22. Coding MC prediction.
23. AI review of MC implementation.
24. Peer review.

## Weeks 9--10 (Activities 25--30)

25. Temporal Difference intuition.
26. TD(0) calculations.
27. Implement SARSA.
28. Implement Q-learning.
29. Compare SARSA vs Q-learning.
30. Mini competition.

## Weeks 11--12 (Activities 31--36)

31. Neural approximation lecture.
32. Experience replay discussion.
33. Implement DQN.
34. Debug DQN instability.
35. AI-generated DQN review.
36. Hyperparameter tuning.

## Weeks 13--14 (Activities 37--42)

37. Policy Gradient derivation.
38. REINFORCE implementation.
39. Actor-Critic implementation.
40. PPO concept seminar.
41. Research paper discussion.
42. Performance benchmarking.

## Week 15 (Activities 43--45)

43. Final capstone integration.
44. Live demonstration and peer evaluation.
45. Reflective portfolio and viva.

------------------------------------------------------------------------

# Assessment

  Component                    Marks
  -------------------------- -------
  Weekly Retrieval Quizzes        15
  Tutorials                       10
  Labs                            15
  Semester Project                10
  SEE Theory                      20
  SEE Practical                   30

## AI Integration

-   Validate AI-generated code.
-   Compare multiple LLM solutions.
-   Document prompt engineering.
-   Explain why generated solutions succeed or fail.

## Semester Project Milestones

Random Agent → MDP Solver → DP Agent → Monte Carlo Agent → Q-Learning
Agent → DQN → Actor-Critic → Final Competition

## Deliverables

-   GitHub portfolio
-   Weekly reflections
-   Lab notebooks
-   Final report
-   Live demonstration
