# OpenWebUI Functions

> All functions in this repository can be found at [github.com/crooy/opewebui-extras](https://github.com/crooy/opewebui-extras)

## Memory Management Functions

### Auto Memory
Automatically identifies and stores important information from user messages. Uses OpenAI's API to:
- Detect memorable information from user messages
- Retrieve relevant memories based on context
- Avoid storing duplicate memories
- Add memory context to conversations

### Add Memories
Allows manual saving of conversation snippets to memory.
- Stores both user message and assistant response
- Provides status updates during memory operations
- Handles errors gracefully with user feedback

## Configuration
Both memory functions can be configured through their respective valve settings:
- Enable/disable functionality
- Adjust OpenAI API settings (auto-memory)
- Control number of related memories to include
- Set memory relevance thresholds

## Repository
All code is available at [github.com/crooy/opewebui-extras](https://github.com/crooy/opewebui-extras). Feel free to:
- Submit issues
- Create pull requests
- Fork the repository
- Contribute improvements
