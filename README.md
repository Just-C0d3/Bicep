This repository contains the code relative to a bicep deploy that classifies the resource types provided to deploy and after that deploys azure budgets consecuently. 


The pipeline contains several verifications to ensure the integrity of the provided json/bicep, this pipeline is designed for a self hosted agent deployed also in azure.

NOTE: For a bigger scale implementation its desirable to add a pwsh script that auto-generates json files with a template, otherwise you'll end up creating a json file for every budget enlarging unnecessarily your repository.
