# Module 6: Adding Tools to Your Agent

## Understanding Tool Capabilities

Tools extend the functionality of your AI agent by enabling it to perform specific tasks, such as fetching data, interacting with APIs, or executing custom logic. In WatsonX Agent Lab, tools can be:

- **Pre-built**: Ready-to-use tools provided by IBM (e.g., search, weather, calculator).
- **Custom**: Developed by you to meet specific requirements.

## Configuring Built-In Tools

1. **Access Tool Palette**:
   - Open the **Tool Palette** in the Agent Lab interface.

2. **Add a Built-In Tool**:
   - Drag and drop a pre-built tool (e.g., **Search Tool** or **Weather Tool**) onto the **Agent Canvas**.

3. **Configure Tool Parameters**:
   - Set up tool-specific parameters (e.g., API keys, search queries, location data).
   - Example: For the Weather Tool, specify the API endpoint and required credentials.

4. **Connect to Workflow**:
   - Link the tool to the appropriate node in your agent's workflow (e.g., after user input processing).

## Creating Custom Tools

1. **Define Tool Logic**:
   - Write Python code or use low-code options to implement the tool's functionality.
   - Example: A custom tool to fetch data from a specific database.

2. **Register the Tool**:
   - Add the custom tool to the **Tool Palette** by providing a name, description, and input/output parameters.

3. **Integrate with Agent**:
   - Drag and drop the custom tool onto the **Agent Canvas** and connect it to the workflow.

## Testing Tool Integration

1. **Use Preview Pane**:
   - Test your agent's interaction with tools in the **Preview Pane**.
   - Example: Ask a weather-related question and verify the agent uses the Weather Tool correctly.

2. **Debug and Refine**:
   - Check tool outputs and error logs to ensure proper functionality.
   - Adjust tool configurations or logic as needed.

## Key Takeaways

- **Tool Capabilities**: Tools enhance agents by enabling specific tasks, either pre-built or custom.
- **Configuring Built-In Tools**: Drag and drop pre-built tools, configure parameters, and connect to the workflow.
- **Creating Custom Tools**: Develop custom tools using Python or low-code options, register them, and integrate into the agent.
- **Testing Integration**: Use the Preview Pane to test tool functionality and refine as necessary.

## Further Reading

- [Develop and Deploy Custom AI Agents to watsonx.ai on IBM Cloud](https://suedbroecker.net/2025/02/25/develop-and-deploy-custom-ai-agents-to-watsonx-ai-on-ibm-cloud/)
- [Build and deploy Agents to watsonx.ai from your IDE](https://www.ibm.com/new/announcements/build-and-deploy-agents-to-watsonx-ai-from-your-ide)
- [Agent Lab (beta) | IBM watsonx](https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/fm-agent-lab.html?context=wx&pos=2)

---

**Previous Module:** [Module 5: Creating Your First Agent in Agent Lab](https://github.com/Jewelzufo/Ibm-agent-lab/blob/8f55ea5328fc42340c0a57cadc14ec47a164d172/Module5.md)  
**Next Module:** [Module 7: Customizing Agent Behavior](https://github.com/Jewelzufo/Ibm-agent-lab/blob/8f55ea5328fc42340c0a57cadc14ec47a164d172/Module7.md)
