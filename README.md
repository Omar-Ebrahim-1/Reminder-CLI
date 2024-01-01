# Reminder-CLI

A simple command-line reminder tool for setting time-based alerts using the terminal.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Installation](#installation)
- [License](#license)

## Overview

Reminder-CLI is a lightweight command-line tool that allows you to set time-based reminders in your terminal. It utilizes the `beeep` library to display desktop notifications.

## Features

- Set reminders for future times.
- Display desktop notifications when reminders trigger.
- Simple and easy-to-use command-line interface.

## Usage

To set a reminder, run the following command:

```bash
go run main.go <hh:mm> <message>
```
## Installation

### Prerequisites

Make sure you have Go installed on your machine. If not, you can download and install it from [https://golang.org/](https://golang.org/).

1. Clone the repository:

    ```bash
    git clone https://github.com/Omar-Ebrahim-1/Reminder-CLI.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Reminder-CLI
    ```

3. Run command

    ```bash
    go mod tidy && \
    go run main.go
    ```

4. If you prefer, you can also build the binary and move it to a directory in your system's PATH:

    ```bash
    go build -o reminder-cli && \
    sudo mv reminder-cli /usr/local/bin/
    ```

## License

This project is licensed under the terms of the [GNU General Public License (GPL) version 3.0](LICENSE).

You can find a copy of the license in the [LICENSE](LICENSE) file included with this distribution.
