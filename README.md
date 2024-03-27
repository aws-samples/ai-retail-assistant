# AI Retail Assistant

This sample guides you through setting up a product catalog using the Amazon Reviews fashion dataset available [here](https://amazon-reviews-2023.github.io/). It covers pre-processing the metadata, inserting data into an [Amazon RDS Aurora PostgreSQL](https://aws.amazon.com/rds/aurora/) database using the [RDS Data API](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/data-api.html), and creating a managed Retrieval Augmented Generation (RAG) knowledge base with [Amazon Bedrock](https://aws.amazon.com/bedrock).

We also go through how you can use Claude 3 language models to select the best product images, construct search queries for the knowledge base based on user input, augment query context with web searches, generate prompts for user-authored content, and analyze product reviews. 

We provide examples of zero-shot, one-shot, and few-shot learning techniques to extract topics, sentiments, and other insights from reviews using large language models. The goal is to showcase how to build engaging retail experiences by leveraging AWS services like SageMaker, RDS, Bedrock, and cloud-based language models.

This sample has been tested on the new [Amazon SageMaker](https://aws.amazon.com/pm/sagemaker) Studio UI using a JupyterLab Space created using the SageMaker Distribution 1.4 image on a t3.medium instance in the IPython Kernel, and using Data Science 3.0 kernel on a t3.medium instance in the SageMaker Classic UI. Before you begin, we recommend that you [create and onboard to a SageMaker Studio Domain](https://docs.aws.amazon.com/sagemaker/latest/dg/gs-studio-onboard.html). This requires an AWS Account, and a user with access to create the Domain. You can refer to the prerequisites [here](https://docs.aws.amazon.com/sagemaker/latest/dg/gs-set-up.html). Once that has been completed, launch [SageMaker Studio](https://docs.aws.amazon.com/sagemaker/latest/dg/machine-learning-environments.html) and open a "System Terminal" from the launcher, from which you can clone this repository

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

