FROM hashicorp/terraform:0.11.11

LABEL "com.github.actions.name"="terraform apply"
LABEL "com.github.actions.description"="Run terraform apply"
LABEL "com.github.actions.icon"="download-cloud"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="https://github.com/hashicorp/terraform-github-actions"
LABEL "homepage"="http://github.com/hashicorp/terraform-github-actions"
LABEL "maintainer"="HashiCorp Terraform Team <terraform@hashicorp.com>"

RUN apk --no-cache add jq

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
