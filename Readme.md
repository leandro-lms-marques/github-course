Multi-Terraform workspace with matrix jobs

This example shows how to run Infracost in GitHub Actions against a Terraform project that uses multiple workspaces using parallel matrix jobs. The first job uses a matrix to generate the plan JSONs and the second job uses another matrix to generate multiple Infracost output JSON files. infracost comment command in the last job combines the Infracost JSON files and posts a single comment.


Adicionando linha para teste