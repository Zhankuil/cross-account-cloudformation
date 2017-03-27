Steps:
1. Create the pipeline in the pipeline account. Specify the parameter 'DeployAccountId' when creating or updating the stack. It also creates a CodeCommit repository 'CrossAccountCloudFormationDemo'.
2. In the deployment account, create the stack using 'deploy.yaml'. Specify the parameter 'PipelineAccountId'.
3. Push the files in ./source directory into the CodeCommit repositoy. The pipeline will start to run once it detects the change.
