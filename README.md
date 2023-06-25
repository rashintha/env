# ENV

![Go](https://img.shields.io/badge/GO-00ADD8?logo=go&logoColor=white&style=for-the-badge)

## Introduction

Env is a simple GO package to read environmental files.

## Getting Started

### Prerequisites

- **[Go](https://go.dev/)**

### Get the ENV

Simply run the following command to get the env package.

```bash
go get github.com/rashintha/env
```

### Basic Usage

```go
package main

import "github.com/rashintha/env"

func main() {
	HOST := env.CONF["HOST"]
}

```

## License

ENV is released under Apache-2.0 license. Please read [LICENSE](LICENSE) for more information.

## Contributing

I always appreciate help from the community to develop. Please send me an email to mail@rashintha.com to get started!