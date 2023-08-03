FROM    golang:1.19.11-alpine

RUN     apk --no-cache add bash make git
RUN     go get \
          golang.org/x/lint/golint \
          golang.org/x/tools/cmd/goimports
