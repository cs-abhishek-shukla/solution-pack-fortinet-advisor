# What's New

## Support for Voice Recognition in AI Assistant

- The new **Voice Recognition** feature helps streamline SOC tasks with hands-free interaction. This enhancement brings greater flexibility, enabling users to interact through voice commands efficiently.

- Translates natural language to a query that helps filter records in FortiSOAR, thereby enhancing the **FortiAI** solution pack's functionalities.

> [!Note]
> The *Voice Recognition* feature is currently unsupported on the Firefox browser as the webkit `SpeechRecognition` is not compatible with Mozilla Firefox. Hence, the mic button is not available when the FortiSOAR&trade; environment is accessed using the Firefox browser.

**Conversation Thread Management**

Previously, conversation threads were deleted from OpenAI whenever *Clear Conversation* was clicked, and a new thread was started with each new prompt.

Now, threads are retained within OpenAI, enabling improved historical reference and continuity. Each new prompt still initiates a fresh thread, while the user interface continues to clear conversation history after each prompt, ensuring a clean workspace.