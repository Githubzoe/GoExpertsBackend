Repo for GoExperts backend sources without a pipeline. You need to construct a new one.

1. The resources for deployment the frontend should be first constructed by IaC tools like Terraform, CloudFormation, Ansible etc.
2. **DO NOT** operate on the `main` branch directly. Checkout your own branch instead, e.g. feature/new_pipeline
3. Compose your pipeline file and put them into `cicd`
4. Build up a pipeline on cicd platforms like Jenkins, Travis CI, Github Actions and have a test.

**IMPORTANT**:
The `.env` file contains some secrets which are concealed. You need to contact JR Academy to get the information, or the backend service will work improperly.
