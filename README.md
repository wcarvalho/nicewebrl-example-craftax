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
We provide two examples for defining a web app. 
* One that uses `nicewebrl.run_experiment` which does most of the work of setting up the interface for you.
* Another that let's you define your own custom interface. They have the same logic.

```bash
# Run the web app using nicewebrl.run_experiment
uv run python web_app_auto.py

# Run the web app with a manually defined interface
uv run python web_app_manual.py
```