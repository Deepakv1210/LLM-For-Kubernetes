# LLM4Kube
CSCE 670 project link: https://deepakv1210.github.io/LLM-For-Kubernetes/

## Team
Deepak Kumar
Shubham Parashar
Vivek Narukurthi
Sabuj Laskar

## Setup of Kubernetes and Open Telemetry Application.
Follow the official Open Telemetry Demo to setup a mock application on your local machine: https://opentelemetry.io/docs/demo/architecture/

## Diagram
<img width="595" alt="image" src="https://github.com/user-attachments/assets/c59d0867-5922-4b47-ad88-edeb936fe31b">

## Generating Logs
After setting up the application, you can start generating logs. This covers a vareity of services and the Open Telemetry website provides important information with regards to this.

## LLMs for Augmentation
We prompted GPT-3.5-Turbo with the logs generated for each application to generate more logs, we have collected around 400 logs covering multiple scenarios. 

We also create a simple test set for evaluation.

To the best of our knowledge we are the first to attempt this.

## LLMs for Analysis

For analysis we used ChatGPT API and Groq APIs, we directly access Gemini via UI.

1. To run these scripts, auth tokens need to be stored.
2. The scripts can be run from `chatgpt.py` and `groq-llama3.py`

## Experiments

We provide a reference to our experiments workbook in this repo.

## Results
<img width="587" alt="image" src="https://github.com/user-attachments/assets/be1c2fef-a5de-4cad-bcb4-f76c16df8bb6">


