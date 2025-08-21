# Craftax Example

This example demonstrates how to create a web interface for the [Craftax environment](https://github.com/MichaelTMatthews/Craftax), a JAX implementation of the Craftax environment. Craftax is a procedurally generated survival game where the agent needs to collect resources, craft tools, and avoid dangers.

![Craftax Environment](https://raw.githubusercontent.com/MichaelTMatthews/Craftax/main/images/building.gif)

## Features
- Grid-world Minecraft-like environment
- Procedurally generated worlds
- Multiple tasks: gathering resources, crafting tools, avoiding dangers
- Day/night cycle

## Installation

```bash
# Install uv if you haven't already
curl -LsSf https://astral.sh/uv/install.sh | sh

# Install dependencies
uv sync
```

## Running the Example
```bash
# Run the web app
uv run python web_app.py
``` 