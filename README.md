# Building a Domain Expert Model

This repository contains a demonstration of the fine-tuning process for the Meta Llama2 7B model. The process includes model evaluation before and after fine-tuning, as well as screenshots of the response before and after fine-tuning with an IT-specific data.

## sagemaker

To use AWS SageMaker, you need an AWS account. Once you have an account, you can follow these steps to try the code:

1. Open the AWS Management Console and navigate to the SageMaker service.
2. Create a new notebook instance or use an existing one.
3. Open the notebook instance and create a new notebook.
4. Copy and paste the code from the repository into the notebook or upload the two .ipynb files.
5. Run the code to execute it and see the results.

Make sure you have the necessary permissions and resources set up in your AWS account to use SageMaker effectively.
## Model Evaluation

Before fine-tuning the Llama2 model, an evaluation was performed to assess its performance on the given task. The evaluation results are documented in the [Model_evaluation.ipynb](Model_evaluation.ipynb) notebook. 
## Fine-tuning

The fine-tuning process involved training the Llama2 model on a domain-specific dataset to improve its performance on the target task. Details of the fine-tuning process can be found in the [Model_fineTuning.ipynb](Model_fineTuning.ipynb) notebook.

To visually demonstrate the impact of fine-tuning, screenshots of the model's response before and after fine-tuning are provided. 



