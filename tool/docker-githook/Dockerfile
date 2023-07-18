FROM    golang:1.21rc3-alpine

RUN     apk --no-cache add bash make git
RUN     go get \
          golang.org/x/lint/golint \
          golang.org/x/tools/cmd/goimports
