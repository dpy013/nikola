# Nikola security issue policy

## The threat model

Before reporting a dubious security "vulnerability", please keep in mind what Nikola is:

1. Nikola is a command-line app, executed locally by the user.
2. Users of Nikola are mostly software engineers. Showing detailed technical errors is the expected behaviour.
3. Input is generally trusted, produced by the user.
4. The servers (`nikola auto` and `nikola serve`) are expected to be used in trusted local networks. They are not supposed to be exposed to the public Internet.

## No private reporting channel

Given our threat model, there is no private vulnerability reporting channel. If you find an actual security issue, please report it via GitHub Issues.

## No bug bounty

There are no bug bounties or other forms of compensation for vulnerability reports.

## LLM security reports not welcome

If you use an LLM ("AI") to find a "vulnerability", it will be closed without response, and your GitHub account will be blocked from the project without warning.

(We have seen slop security reports produced by LLMs, and they were complete nonsense.)
