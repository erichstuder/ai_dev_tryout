# ai_dev_tryout

A small Rust application developed with AI assistance at every step.

## Development

This project uses a [Dev Container](https://containers.dev/) to provide a consistent, reproducible development environment with the latest stable Rust toolchain pre-installed.

### Getting Started

1. Open this repository in [VS Code](https://code.visualstudio.com/) with the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) installed, or open it in [GitHub Codespaces](https://github.com/features/codespaces).
2. The container will automatically set up Rust and all recommended extensions.

### Building

```bash
cargo build
```

### Running

```bash
cargo run
```

### Testing

```bash
cargo test
```

### Linting

```bash
cargo clippy
cargo fmt --check
```

## CI

Every push and pull request to `main` is validated by a GitHub Actions workflow that checks formatting, runs Clippy, builds the project, and runs all tests.