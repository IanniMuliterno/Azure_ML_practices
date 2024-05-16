# How I did each challenge

## Challenge 1

- in azure cli
  - create resource group
	- ML workspace
	- ML compute
	- ML data asset with path from storage
az ml data create --name diabetes-dev-folder --version 1 --path https://challengstorage38636f82d.file.core.windows.net/code-391ff5ac-6576-460f-ba4d-7e03433c68b6/Users/iannimuliterno/Azure_ML_practices/experimentation/data/diabetes-dev.csv --resource-group mlchallenge --workspace-name challengeworkspace

- in ML compute
  - clone git repo (before creating data asset) 
