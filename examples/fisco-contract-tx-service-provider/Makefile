#!/usr/bin/make -f

export GO111MODULE = on

install:
	@echo "installing fisco contract tx service provider..."
	@go build -mod=readonly -o $${GOBIN-$${GOPATH-$$HOME/go}/bin}/fisco-contract-tx-sp github.com/bianjieai/bsnhub-service-demo/examples/fisco-contract-tx-service-provider/cmd
