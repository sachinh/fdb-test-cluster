BOLD=$(shell tput bold)
ERROR=$(shell tput setaf 1)
RESET=$(shell tput sgr0)

build: ## Build FDB AMI with Packer
	@AWS_REGION=eu-west-1 packer build packer.json

