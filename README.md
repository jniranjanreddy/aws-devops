# aws-devops
```
Required IAM Roles
https://www.udemy.com/course/aws-ecs-fargate/learn/lecture/20611074#overview



How to create CodeCommit Repository.
aws codecommit create-repository --repository-name MyDemoRepo --repository-description "My demonstration repository" --tags Team=nirulabs

How to Delete Repository
aws codecommit delete-repository --repository-name MyDemoRepo


BuildSpec.yml Phases
Phases
  install
  pre_build
  build
  post_build

```

```
CodeBuild default Variables.
[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_BUILD_ID}
testing:7809ef2a-8888-4934-b09e-d095d865e4f7

[Container] 2022/03/17 12:24:39 Running command echo ${AWS_DEFAULT_REGION}
us-west-2

[Container] 2022/03/17 12:24:39 Running command echo ${AWS_REGION}
us-west-2

[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_BATCH_BUILD_IDENTIFIER}


[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_BUILD_ARN}
arn:aws:codebuild:us-west-2:101805901231:build/testing:7809ef2a-8888-4934-b09e-d095d865e4f7

[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_BUILD_ID}
testing:7809ef2a-8888-4934-b09e-d095d865e4f7

[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_BUILD_IMAGE}
aws/codebuild/standard:5.0

[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_BUILD_NUMBER}
5

[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_KMS_KEY_ID}
arn:aws:kms:us-west-2:101805901231:alias/aws/s3

[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_LOG_PATH}
7809ef2a-8888-4934-b09e-d095d865e4f7

[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_PUBLIC_BUILD_URL}


[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_RESOLVED_SOURCE_VERSION}
6727e634456427df2c91b389d0b51265ace7ef2f

[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_SOURCE_REPO_URL}
https://github.com/jniranjanreddy/aws-devops

[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_SOURCE_VERSION}


[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_SRC_DIR}
/codebuild/output/src664663263/src/github.com/jniranjanreddy/aws-devops

[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_START_TIME}
1647519846773

[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_WEBHOOK_ACTOR_ACCOUNT_ID}


[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_WEBHOOK_BASE_REF}


[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_WEBHOOK_EVENT}


[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_WEBHOOK_MERGE_COMMIT}


[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_WEBHOOK_PREV_COMMIT}


[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_WEBHOOK_HEAD_REF}


[Container] 2022/03/17 12:24:39 Running command echo ${CODEBUILD_WEBHOOK_TRIGGER}


[Container] 2022/03/17 12:24:39 Running command echo ${HOME}
/root

```
