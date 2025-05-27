# AI Agents with Semantic Kernel

AI Agents implementation using Microsoft Semantic Kernel framework for building intelligent, plugin-based applications.

## Features

- 🤖 Multi-agent orchestration
- 🔌 Plugin-based architecture
- 🧠 Memory and planning capabilities
- 🔄 Chain-of-thought reasoning
- 📊 Built-in observability

## Quick Start

1. Clone the repository
```bash
git clone https://github.com/veeraa23/ai-agents-semantic-kernel.git
cd ai-agents-semantic-kernel
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Set up environment variables
```bash
cp .env.example .env
# Edit .env with your API keys
```

4. Run the example
```bash
python examples/basic_agent.py
```

## Project Structure

```
ai-agents-semantic-kernel/
├── src/
│   ├── agents/          # Agent implementations
│   ├── plugins/         # Custom plugins
│   └── utils/           # Utility functions
├── examples/            # Example implementations
├── tests/              # Unit tests
└── docs/               # Documentation
```

## Documentation

See the [docs](./docs/) folder for detailed documentation.

## Contributing

Contributions are welcome! Please read our [contributing guidelines](CONTRIBUTING.md).

## License

MIT License - see [LICENSE](LICENSE) file for details.