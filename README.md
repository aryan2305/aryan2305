Hi, I'm Aryan Agrawal. I'm a software engineer on the Platform team at [Glean](https://www.glean.com/). I build developer infrastructure: remote development environments, CI compute, and build systems, plus the sandboxing layer that gives AI agents isolated environments to run code in.

### Work at Glean

- **Firecracker microVM sandboxing**: A Go-based platform for running untrusted, model-generated code in production, with snapshot restore for fast startup and resume.
- **Remote execution on Kubernetes (GKE)**: Designed and built a platform that runs concurrent isolated workspaces and CI workloads across clusters.
- **Build systems**: Re-architected Bazel build configuration across Java, Go, and Python in a large monorepo, with shared build caching for faster CI and local builds.
- **Remote development environments**: Dev boxes powered by [Coder](https://coder.com/) workspaces.
- **Platform reliability**: On-call responsibility for the reliability and scaling of the compute infrastructure supporting Glean's AI agents.

### Selected projects

- **[DevDock](https://github.com/aryan-agrawal-glean/devdock)**: A Rust CLI for managing local and remote development environments in Bazel monorepos. A single YAML profile runs the same stack locally, on remote workspaces, and in CI, with Tilt orchestration, a plugin system, and an MCP server for AI agents.
- **[DevDock Plugin Library](https://github.com/aryan-agrawal-glean/devdock-plugins-library)**: DevDock plugins in Rust, Python, Go, and Bash for environment validation, startup timing, logging, and notifications. Each plugin is also a starting point for extending your own workflow.
- **[Tilt MCP](https://github.com/aryan-agrawal-glean/tilt-mcp)**: A Python MCP server that gives AI assistants access to Tilt resource status and service logs, so they can inspect development environments and troubleshoot failing services.

I'm interested in developer infrastructure, build systems, compute, and databases—and in making AI agents useful in everyday engineering. Contributions, feedback, and conversations around these projects are always welcome.
