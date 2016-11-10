# Slackit

Pipe STDOUT and STDERR from other commands to Slack

## Installation

```
  pip install slackit
  slackit --init  # creates the settings file
```

## Usage

Pipe both STDOUT and STDERR to Slack:

```
  echo "hai" |& slackit
```

Pipe STDOUT to Slack:

```
  echo "hai" | slackit
```
