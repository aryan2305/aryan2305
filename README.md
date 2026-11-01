Hi, I'm Aryan Agrawal. I like making complicated developer workflows feel boring. In a good way.

I'm on the Platform team at [Glean](https://www.glean.com/), where I work on the machinery behind writing and running code: remote dev environments, compute, databases, Docker, Kubernetes, and Bazel builds. I also build sandboxes with **Firecracker microVMs**, giving AI agents isolated places to run their code. Humans get dev boxes; agents get microVMs.

### Some projects I loved working on

- **[DevDock](https://github.com/aryan-agrawal-glean/devdock)**: Because “getting the environment running” shouldn't be the day's main accomplishment. A Rust CLI that brings up development stacks locally, remotely, and in CI using the same YAML profile. Powered by Tilt, with plugins and an MCP server for AI agents.
- **[DevDock Plugin Library](https://github.com/aryan-agrawal-glean/devdock-plugins-library)**: The little helpers around the main event: checking your environment, timing startup, collecting logs, and letting you know when everything's ready. Written in Rust, Python, Go, and Bash; borrow one or build your own.
- **[Tilt MCP](https://github.com/aryan-agrawal-glean/tilt-mcp)**: So your AI assistant can read the service logs too. A Python MCP server that exposes Tilt resources, status, and logs for debugging development environments.

Always happy to talk developer tools, build systems, compute, and databases. Found something useful or something broken? Open an issue or send a PR.
