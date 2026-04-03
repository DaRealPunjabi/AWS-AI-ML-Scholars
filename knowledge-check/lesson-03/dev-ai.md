**Question 1**

A machine learning (ML) scientist is building an ML model for loan applications at a bank by using Amazon SageMaker AI. They want to mitigate bias in the data and increase visibility into model behavior.

Which AWS service or feature helps to meet these needs?
- [ ] Amazon Comprehend
- [ ] Amazon SageMaker JumpStart
- [ ] Amazon Augmented AI (Amazon A2I)
- [x] Amazon SageMaker AI Clarify

SageMaker AI Clarify provides purpose-built tools to gain greater insights into ML models and data based on metrics such as accuracy, robustness, toxicity, and bias to improve model quality and support responsible AI initiatives.

**Question 2**

A team is beginning to work with generative artificial intelligence (generative AI) and is concerned about implementing responsible AI. They want to use AWS AI tools and want to understand how to implement them responsibly.

Which tool is available to help the team make those decisions? 
- [ ] Responsible Use of Machine Learning whitepaper
- [ ] AWS Marketplace
- [x] AWS AI Service Cards
- [ ] AWS Machine Learning University

AI Service Cards are a form of documentation on responsible AI. They provide teams with a single place to find information on the intended use cases and limitations, responsible AI design choices, and deployment and performance optimization best practices for AWS AI services. 

**Question 3**

Monitoring is important to maintain high-quality machine learning (ML) models and help ensure accurate predictions.

Which AWS services or features help with monitoring and human review? (Select TWO.)
- [ ] Amazon SageMaker JumpStart
- [x] Amazon SageMaker Model Monitor
- [x] Amazon Augmented AI (Amazon A2I)
- [ ] Amazon SageMaker AI Clarify
- [ ] Amazon Bedrock

Monitoring is important to maintain high-quality ML models and help ensure accurate predictions. SageMaker Model Monitor automatically detects and alerts users to inaccurate predictions from deployed models. With Amazon A2I, users can implement a human review of ML predictions when human oversight is needed.

**Question 4**

A developer has been asked to build an artificial intelligence (AI) application that will be used to help a research team in their work. 

What should the developer ask the research team to do so that the best model can be selected for the AI application?
- [ ] Define the use case of the application broadly
- [x] Define the use case of the application narrowly
- [ ] Define the governance policies for the application
- [ ] Define which teams will be monitoring the model

Defining a narrow use case for the application can help you to select the best model for the application. Governance policies and accountability for monitoring a model are important, but they don't fundamentally impact which model to select for the application.

**Question 5**

A lending agency is using an artificial intelligence (AI) system so that customers can apply for a loan in Wyoming. However, the development team has tested the model and noticed that there is a bias against loan applicants that have lived in Wyoming for less than 10 years. The development team's research revealed that there is not a lot of data sample available for these groups of people.

What could the development team do to reduce the bias against applicants who have lived in Wyoming for less than 10 years?
- [ ] Use more inclusive data 
- [ ] Preprocess the data
- [x] Augment the data 
- [ ] Conduct regular audits on the data

Data augmentation can be used to generate new instances of underrepresented groups. This can help to balance the dataset and prevent biases towards more represented groups.

Because there are not a lot of samples for the people who have lived in Wyoming for less than 10 years, using more inclusive data is not an option. All the data for this group that is available is already used. Preprocessing data and conducting regular audits won't help in this situation either. 

**Question 6**

An organization is in the beginning stages of building an application that will use generative artificial intelligence (generative AI) technologies. The development team wants to use the best model for the application’s use case. But with the large selection of large language models (LLMs), the development team is not sure which model to select. Also, the application will be public facing, and the team is concerned about the potential of generating harmful content.

Which AWS solutions should the team use to address these concerns? (Select TWO).
- [ ] Amazon SageMaker Model Dashboard
- [x] Model Evaluation on Amazon Bedrock
- [ ] Amazon Augmented AI (Amazon A2I)
- [ ] Amazon SageMaker Data Wrangler
- [x] Guardrails for Amazon Bedrock

With Model Evaluation on Amazon Bedrock, the team can evaluate, compare, and select the best foundation model for their use case. With Guardrails for Amazon Bedrock, the team can implement safeguards for their generative AI applications. It can help to filter out any harmful content.

The following are incorrect because they are not used to choose a model or filter out harmful content that generative AI might generate:

- SageMaker Data Wrangler can be used to balance their data in cases of any imbalances.
- Amazon A2I can be used to build the workflows required for human review of ML predictions.
- SageMaker Model Dashboard can be used as a central place to keep the team informed on model behavior in production.
