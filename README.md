# Cybera Tool

## Requirements
Install Go through Homebrew.

```bash
brew install go
```

## Installation

```bash
go get github.com/cybera/cybera-tool
```

## Usage

Login:

```bash
cybera-tool -c <username>:<password> | tail -1 | pbcopy
export CYBERA_KEY=$(pbpaste)
```

Log:

```bash
cybera-tool log DevOps "I've spent today working on cybera-tool"
```

Also:

```bash
cybera-tool help
```
