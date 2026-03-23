# go-projects-template

### Setting Up linters

``` bash
# You can install golangci-lint locally with:
go install github.com/golangci/golangci-lint/cmd/golangci-lint@latest
To check your code manually, run:
golangci-lint run
# Vet examines Go source code and reports suspicious constructs
go vet
# errcheck finds silently ignored errors in Go code.
go install github.com/kisielk/errcheck@latest
errcheck <path>
# Gocyclo calculates cyclomatic complexities of functions in Go source code.
go install github.com/fzipp/gocyclo/cmd/gocyclo@latest
gocyclo <flag> <filename>
# Find repeated strings that could be replaced by a constant.
go install github.com/jgautheron/goconst/cmd/goconst@latest
goconst ./...

```
