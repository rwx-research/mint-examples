# Get Started with Mint

[Mint](https://rwx.com/mint) is a comprehensive CI/CD platform designed to move you beyond inefficient and simplistic workflows.

Mint re-envisions every step of CI/CD so that you’re no longer running the same tasks over and over or combing through log files to find bugs.
Move beyond the limitations of legacy tools and code how you want with Mint.

## Step 1: Install the CLI

With Mint, you can run tasks without having to push to a git repository.
The easiest way to get started is by using the CLI to initiate runs locally.

### Mac OS

Install via homebrew:

```
brew install rwx-research/tap/mint
```

### Windows Subsystem for Linux (WSL)

Install via homebrew:

```
brew install rwx-research/tap/mint
```

### Linux

Download the [latest release](https://github.com/rwx-research/mint-cli/releases) on GitHub for your platform and architecture.
Move the binary into a directory on your `PATH` and make it executable.

## Step 2: Authenticate with the Mint CLI

You'll need to log in to use the CLI. To initiate the authentication process, run:

```
mint login
```

You can verify you've authenticated successfully by running:

```
mint whoami
```

## Step 3: Kick of your first Mint run

Clone this repository and run the sample-run.yml workflow. Or if you'd prefer, check out the [documentation](https://www.rwx.com/docs/mint/guides/ci) to learn how to write your own workflows.

```
git clone git@github.com:rwx-research/mint-examples.git
```
```
cd mint-examples
```
```
mint run -f .mint/sample-run.yml --title "Sample Run" --open    
```
