| [Home](../README.md) |
|----------------------|

# Troubleshooting

## FortiAI bot not visible

The FortiAI bot is not visible after installing the **FortiAI** solution pack.

**Resolution**

To resolve this issue, you can either force a browser refresh or log out and log back in, to your FortiSOAR instance.

## FortiAI bot doesn't display mic

The *Voice Recognition* feature is currently unsupported on the Firefox browser as the webkit `SpeechRecognition` is not compatible with Mozilla Firefox. Hence, the mic button is not available when the FortiSOAR&trade; environment is accessed using the Firefox browser.

## FortiAI flyout does not open

The FortiAI flyout does not launch, or the FortiAI does not display any response for the playbook outline.

**Resolution**

To resolve this issue, check if the user is assigned appropriate permissions. To utilize the FortiAI solution pack, users must have the following permissions, along with other appropriate permissions:

- Read and Usage permissions on Widgets
- Read and Execute permissions on Playbooks

## FortiAI is unable to generate playbook steps

Based on your prompt, the FortiAI cannot generate the playbook steps.

**Resolution**

To resolve this issue, try the following:

- Try to regenerate the steps.
- Rephrase the prompt and try to generate the playbook steps, see [Prompting tips](#prompting-tips).
- Verify that your OpenAI account is operational and has enough credit.

## FortiAI does not create or update record

FortiAI does not create or update record as per specified fields in FortiSOAR.

**Resolution**

- Prompt the FortiAI 

    >*What parameter did you pass to create/update field.*

- Correct the parameters as per field API names as mentioned in FortiSOAR settings.

## Renaming OpenAI Connector Configuration

Sometimes, on changing the configuration name of OpenAI connector, it may not correctly render the updated name.

1. Press the **Back** button to return to the **LLM Configuration** page.

2. Click **Next** to advance to the **Connector Configuration** page.

## Response not as Expected

The prompt may not always be as expected, in such cases you may:

1. Send the prompt again

2. Rephrase the prompt to send a more targeted request.

## Response delay

After entering the prompt the text may still be visible; however, the text input field appears disabled and with 3-dot loader gif on screen.

**Resolution**

- The prompt has not passed to the LLM. Refresh the page and try again with the same prompt.

## OpenAI Error Messages

Cannot add messages to `thread_123ndasda341` while a run thread `run_134314hh1` is active.

**Resolution**
- Try to cancel the RUN on OpenAI platform - while loading the same thread on assistant using URL - https://platform.openai.com/playground/assistants?mode=assistant&assistant=asst_id&thread=thread_id and cancel the run

OR

- Clear the Conversation

# Next Steps

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) | [Contents](./contents.md) |
| --------------------------------------- | ----------------------------------------- | ------------------- | ------------------------- |
