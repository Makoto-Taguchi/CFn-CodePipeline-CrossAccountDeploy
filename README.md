# CodePipelineで別AWSアカウントのS3にデプロイする構成を、CloudFormationで構築

## 構築手順
1. CodePipelineServiceRole.ymlをパイプラインアカウントに構築
2. CrossAccountAccessRole.ymlをS3デプロイ先アカウントに構築
3. CodePipeline.ymlをパイプラインアカウントに構築