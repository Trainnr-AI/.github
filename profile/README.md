
# Trainnr AI

**The end-to-end robotics platform: a self-improving loop for robots,
run from your coding agent.** Real-to-sim from the robot's own telemetry,
datasets, training, evaluation, sim-to-real gating, deployment telemetry
and drift, every record queryable by the agent. [trainnr.ai](https://trainnr.ai)

- [`trainnr`](https://github.com/Trainnr-AI/trainnr): the pipeline (Python
  packages `trainnr` and `trainnr-mjlab`), the desktop app, the `trainnr`
  command and MCP server, the Claude Code plugin, the docs and the paper's
  records. Apache-2.0.
- [`rig`](https://github.com/Trainnr-AI/rig): the 2025–26 rover and arm rig
  the toolchain grew up on: 14 Rust crates and the Pico firmware. Archived.

Install the plugin in Claude Code:

```sh
claude plugin marketplace add Trainnr-AI/trainnr
claude plugin install trainnr@trainnr
```

Issues and pull requests are welcome in the product repository; see its
`CONTRIBUTING.md`. Security reports go through GitHub's private
vulnerability reporting there.
