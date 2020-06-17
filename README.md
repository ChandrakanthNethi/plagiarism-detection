# Plagiarism Detection
## Using AWS SageMaker
The notebook and Python files provided in this repository, result in a plagiarism detection model.

## Setup Instructions
The notebooks provided in this repository are intended to be executed using Amazon's SageMaker platform. The following is a brief set of instructions on setting up a managed notebook instance using SageMaker, from which the notebooks can be completed and run.

### Log in to the AWS console and create a notebook instance
Log in to the [AWS console](https://console.aws.amazon.com/) and go to the SageMaker dashboard. Click on 'Create notebook instance'.

- The notebook name can be anything and using ml.t2.medium is a good idea as it is covered under the free tier.
- For the role, creating a new role works fine. Using the default options is also okay.
- It's important to note that you need the notebook instance to have access to S3 resources, which it does by default. In particular, any S3 bucket or object, with “sagemaker" in the name, is available to the notebook.
- Use the option to git clone the project repository into the notebook instance by pasting `https://github.com/ChandrakanthNethi/plagiarism-detection.git`

## Resources
### SageMaker
- [SageMaker python SDK](https://sagemaker.readthedocs.io/en/stable/)

## SageMaker Configuration
Below [SageMaker ML instance types](https://aws.amazon.com/sagemaker/pricing/instance-types/) are used:
- Notebook: ml.t2.medium
- Training: ml.p2.xlarge
- Serving: ml.m4.xlarge

## Git Style Guide
[Udacity Git Commit Message Style Guide](http://udacity.github.io/git-styleguide/) is being used in this repository.

## License
The contents of this repository are covered under the [MIT License](https://github.com/ChandrakanthNethi/plagiarism-detection/blob/master/LICENSE)
