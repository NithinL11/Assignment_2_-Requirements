# Assignment 2: AI Training Data Requirements


## Scenario
The client, an AI developer, uses web scraping to collect training data but faces some challenges:

1.Separating questions from answers to prevent AI from memorizing responses.
2.Ensuring balanced datasets to improve AI fairness and accuracy.

---

###Requirement 1:
 
As an AI developer, I want training questions to be categorized separately from answers so that AI models can be tested without being biased by pre-exposed answers.


###Assumptions & Validation:

-The current dataset does not separate questions from answers.

Method 1: Interview developers to determine if pre-exposed answers cause overfitting issues.

-Developers need access to questions only to prevent AI from memorizing answers.

Method 2: Analyze the current dataset structure to identify whether questions and answers are mixed.
Method 3: Test AI models with and without pre-exposed answers and compare performance metrics.

-A relational database will help structure and retrieve data efficiently.

Method 4: Review past AI model predictions for potential bias trends.
Method 5: Gather feedback from developers about their experiences with biased AI outputs.
Method 6: Conduct statistical analysis on dataset distribution to check for imbalances.


###Follow-up questions
-Have developers already implemented any manual workarounds to prevent AI from memorizing answers?
-What percentage of training data is affected by mixed question-answer formats?
-How much accurate improvement is expected after separating questions from answers?
-What statistical tools or techniques will be used to identify dataset imbalances?
-Were past AI models trained with mixed question-answer data, and if so, what biases were observed?
-What difficulties have developers faced in training unbiased AI models?


###Preliminary Tasks:
-Identify storage issues by analyzing the current dataset.
-Confirm developer workflows through interviews.
-Design a relational database schema for structured storage.
-Develop an API to retrieve only questions while restricting answer access.
-Implement a manual tagging system to categorize questions.
-Evaluate the system’s impact on AI model validation.
