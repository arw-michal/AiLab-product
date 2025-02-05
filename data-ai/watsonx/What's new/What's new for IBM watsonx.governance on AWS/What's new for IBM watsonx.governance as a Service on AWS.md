What's new for IBM watsonx.governance as a Service on AWS
Last updated: Dec 12, 2024
Check back each week to learn about new features and updates for IBM watsonx.governance as a Service on AWS.

For information about watsonx.ai and watsonx.governance on IBM Cloud, see What's new.

Week ending 13 December 2024
Enhancements to the integration with Amazon SageMaker
Cross account roles: You can now use a cross-account role instead of access keys to connect to Amazon SageMaker.
Multiple accounts: You can now set up multiple connections to a single Amazon SageMaker. Each connection is to an account. You can create up to ten connections, each connected to a separate account.
Model Registry: The integration now uses the model registry. Model cards are no longer required.
Model groups: When a use case is approved, a model group is now created automatically in Amazon SageMaker. As a result, models that are created in Amazon SageMaker for a use case are now automatically associated with the use case in IBM watsonx.governance.
Model Lifecycle: The workflows in watsonx.governance now support the model lifecycle statuses and stages in Amazon SageMaker.
For more information, see Integrating watsonx.governance as a Service on AWS with Amazon SageMaker.

Enhancements to the watsonx.governance Model Risk Governance solution
The new AI Model Onboarding Risk Identification questionnaire template is used during the model onboarding process to help identify the risks associated with a model. This questionnaire template is used in the Foundation Model Onboarding workflow.
The new AI Use Case Risk Identification questionnaire template is used to help identify the risks associated with AI use cases. This questionnaire template is used in the Use Case Review workflow. This new questionnaire is intended to replace the AI Risk Identification Questionnaire.
The new AI Use Case and Model Risk Identification questionnaire template is used to help identify the risks that are associated with the combination of an AI use case and a model. This questionnaire template is used in the Use Case Development and Documentation workflow.
The AI Assessment Workflow is now disabled by default. It is replaced by the Questionnaire Assessment Workflow. You can now set questionnaire templates directly in the Use Case workflow.
The workflows, views, and dashboards were updated.
For more information, see Solution components in Governance console.

Bug fixes and security fixes
Bug fixes and security fixes were applied.

Week ending 8 November 2024
Region support
You can now deploy in the AWS Europe (Frankfurt) region.
Bug fixes and security fixes
Bug fixes and security fixes were applied.
Week ending 28 October 2024
Bug fixes and security fixes
Bug fixes and security fixes were applied.
Week ending 27 September 2024
Enhancements to watsonx.governance as a Service on AWS
This release includes enhancements and bug fixes.

Custom tabs on the dashboard
The dashboard can now contain up to three custom tabs.
Stacked bar charts
You can now configure a stacked bar chart on the dashboard and in the View Designer.
Using expressions to set field values based on a questionnaire respondent's answers
You can now enter an expression for the value of a field. For example, you can enter [$TODAY$] for the current date,[$END_USER$] for the name of the signed on user, or [$System Fields:Description$] to set the field to the value of the Description field of the object.
Bug fixes and security fixes
Bug fixes and security fixes were applied.
Week ending 28 June 2024
Govern use cases and models with watsonx.governance as a Service on AWS
You can now use watsonx.governance as a Service on Amazon Web Services (AWS).

You can also use the Governance console capabilities of watsonx.governance for Amazon SageMaker models. With this integration, you can bring the advanced AI governance capabilities of the Model Risk Governance solution to your Amazon SageMaker predictive machine learning and generative AI models.

For more information, see watsonx.governance on AWS.

Parent topic: https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/whats-new-wx.html?context=wx&locale=en
