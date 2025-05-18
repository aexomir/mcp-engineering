# Multi-Context Processing (MCP) Project

This project is based on the [Build Rich Context AI Apps with Anthropic](https://learn.deeplearning.ai/courses/mcp-build-rich-context-ai-apps-with-anthropic) course from DeepLearning.AI. The course teaches how to build sophisticated AI applications using Anthropic's Claude model and the Multi-Context Processing (MCP) framework.

## Course Credits

Special thanks to:

- [DeepLearning.AI](https://www.deeplearning.ai/) for providing the comprehensive course
- [Anthropic](https://www.anthropic.com/) for their Claude model and MCP framework
- The course instructors for their excellent teaching materials

## Project Structure

The project consists of several key components:

### Core Notebooks

- `mcp_prompt_resource.ipynb` - Demonstrates prompt engineering and resource management
- `classic_tool_calling.ipynb` - Shows traditional tool calling approaches
- `mcp_multi_server.ipynb` - Implements multi-server architecture
- `mcp_client_fastMCP.ipynb` - Client implementation using FastMCP
- `mcp_server_fastMCP.ipynb` - Server implementation using FastMCP
- `deploy.ipynb` - Deployment and production considerations

### Project Directories

- `mcp_project/` - Main project directory containing core implementations
- `mcp/` - MCP framework related files
- `images/` - Project-related images and assets

## Dependencies

The project requires the following Python packages:

```
anthropic>=0.51.0
arxiv>=2.2.0
mcp>=1.7.1
pypdf2>=3.0.1
python-dotenv>=1.1.0
uv
```

## Key Features

1. **Multi-Context Processing**

   - Advanced context management
   - Parallel processing capabilities
   - Efficient resource utilization

2. **FastMCP Implementation**

   - High-performance client-server architecture
   - Optimized for production environments
   - Scalable design patterns

3. **Tool Integration**
   - Classic tool calling patterns
   - Modern API integrations
   - Resource management

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your environment variables (create a `.env` file with your Anthropic API key)
4. Run the notebooks in sequence to understand the implementation

## Best Practices

- Always use environment variables for sensitive information
- Follow the notebook sequence for proper understanding
- Test thoroughly before deployment
- Monitor resource usage in production

## License

This project is for educational purposes and follows the licensing terms of the original course materials.

## Contributing

Feel free to submit issues and enhancement requests!
