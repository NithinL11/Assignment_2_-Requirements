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

----

###Requirement 2: 

As an AI developer, I want to ensure that my training data is unbiased so that the AI model can make fair and accurate predictions.

###Assumptions & Validation:

-Bias exists due to overrepresentation or underrepresentation of certain data.

Method 1. Review past AI model predictions for biased trends.

-Developers need an automated bias detection system to identify and correct imbalances before AI model training.

Method 2. Run statistical analysis on dataset distribution.

-Statistical analysis is the best way to quantify bias.

Method 3. Gather developer feedback on biased AI outputs.

###Follow-up Questions:

-What types of biases have been observed in past training data?

-How frequently do developers encounter bias-related issues in AI outputs?

-What tools or methods are currently used to detect bias in AI training data?

-How does bias affect the overall accuracy and fairness of AI models?

-What statistical techniques are most effective for bias detection?



###Preliminary Tasks:

-Collect past AI training results and analyze bias patterns.

-Implement a bias detection algorithm to flag issues.

-Develop a bias report generator with visual insights.

-Create a user dashboard for viewing bias metrics.

-Test and refine the bias detection model.

----

###Requirement 3: 

As an AI developer, I want the training data to be analyzed for balance across different categories so that the AI model does not favor certain inputs over others.

###Assumptions & Validation:

-AI model performance declines when trained on skewed datasets.

Method 1. Compare AI performance on balanced and unbalanced datasets to measure data.

-A dataset balance-checking tool is required.

Method 2. Conduct surveys to assess how dataset balance impacts training.

-Developers need a visual tool to assess and correct dataset balance.

Method 3. Analyze existing datasets for imbalances.

###Follow-up Question:

-How does dataset imbalance currently affect AI model predictions?

-How often should dataset balance be re-evaluated?

-What past fixes for dataset balance have worked, and which ones failed?

-How do different AI models react when trained on balanced vs. unbalanced datasets?


###Preliminary Tasks:

-Develop a data distribution analysis tool.

-Create a dataset balance visualization dashboard.

-Implement an imbalance detection system.

-Set up alerts for dataset balance thresholds.

----

###Requirement  4:

As an AI developer, I want to ensure that the training data collected through web scraping is clean and consistent so that AI models can be trained without errors caused by duplicate data.

###Assumptions & Validation:

-Web scraping often results in duplicate, missing, or incorrect data.

Method 1: Identify inconsistencies in the dataset using statistical checks to detect missing or incorrect data.

-Inconsistent data can negatively impact AI model accuracy.

Method 2: Run a duplicate detection algorithm on the training data to ensure data consistency and integrity.

-A data-cleaning and validation process will improve the reliability of the training dataset.

Method 3: Compares AI performance on cleaned vs. uncleaned data, proving that data cleaning enhances reliability.


###Follow-up Question:

-How often do developers notice duplicate or incorrect data in scraped datasets?

-What is the most common type of inconsistency found in training data—duplicates, missing values, or formatting errors?

-Do developers manually clean data before training AI models, and how long does that process take?

-Would developers prefer an automated cleaning tool, or do they need manual oversight to review flagged data?

###Preliminary Tasks:

-Implement data to remove duplicates and incorrect data.

-Develop automated validation scripts for checking data consistency.

-Create logging and reporting tools to flag incorrect entries.

----

###Requirement 5

As an AI developer, I want to track the source and history of training data so that I can verify its reliability and ensure compliance with ethical AI standards.

###Assumptions & Validation:

-Developers need to know where data is scraped from to avoid legal or ethical issues.

Method 1: Verify that each data entry has an associated source record to ensure traceability and compliance.

-Tracking the modifications made to the dataset is essential for debugging AI model performance.

Method 2: Check whether the system logs modifications and updates to training data.

-A data provenance system will improve transparency and trustworthiness.

Method 3: Conduct a developer review to ensure the provenance system meets their needs.

###Follow-up questions:

-How often do developers need to check the source of training data?

-Would developers have manual control over data verification?

-How does tracking data history improve model retraining and long-term AI development?

-What challenges have developers faced in ensuring data transparency?

###Preliminary Tasks:

-Implement metadata tracking for each dataset entry.

-Develop an audit log to track data modifications and updates.

-Create a user-accessible dashboard to review data provenance.

----

###System Requirements

-The system should handle large-scale data processing efficiently.

-The system should provide real-time data retrieval.

-Implement a dashboard for managing datasets and viewing reports.

-The system should support exporting datasets in different formats.
