# Uncharted Demo
Uncharted is a simple ***Elixir*** charting library that generates easy to customize charts.

This demo is a working example of each of the [Uncharted Phoenix](https://github.com/unchartedelixir/uncharted_phoenix) chart types.

Build status: [![CircleCI](https://circleci.com/gh/unchartedelixir/demo/tree/master.svg?style=svg)](https://circleci.com/gh/unchartedelixir/demo/tree/master)

***Charts Included***:
- The Pie Chart
- The Column Chart
- The Progress Chart
- The Line Chart
- The Bar Chart

![Chart Examples Image](/assets/static/images/uncharted.jpg?raw=true "Bar Chart")

To start the demo Phoenix server:

  * Install dependencies with `mix deps.get`
  * Install Node.js dependencies with `npm install` inside the `assets` directory
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser to see the charts.

## Contributing

We appreciate any contribution to Uncharted!

To contribute feedback, please open a GitHub issue.

To contribute a specific feature or bugfix, please open a PR. Before submitting your PR, we ask you to run the Elixir
tests, lint, and formatting tools we use on the project. If you have a contribution to make but don't know how to run
the tools below, go ahead and open it and we will help you. For larger changes, open an issue first so that we can have
a discussion before you put a lot of work into a PR.

To run the tests and formatting tools:

```
$ mix deps.get
$ mix test
$ mix format
$ mix credo--strict
 ```
