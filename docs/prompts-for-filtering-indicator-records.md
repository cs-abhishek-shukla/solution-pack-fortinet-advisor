| [Home](../README.md) |
|----------------------|

# Filtering indicators through prompts

This guide contains prompts for efficiently filtering indicators using the FortiAI Assistant. Each prompt focuses on some possible filtering criteria to streamline threat investigation and response.

### Example: Retrieve Incidents with ID Greater Than 400

This example demonstrates how to filter incidents based on their ID, allowing users to focus on incidents with an ID value exceeding a specific threshold.

* **Prompt**:  
   > _"Give me all indicators of type URL."_

* **Expected Outcome**:  
   Lists all indicators of *type* **URL**.

### Review Results

Verify that the results include only incidents with an ID greater than 400, ensuring no incidents with a lower ID are included.

### Other examples

Similarly, you can use the following prompts to filter indicator records.

1. Give me all indicators of type URL or IP
 
2. Give me all blocked indicators.
 
3. Fetch all the indicators with Good Reputation
 
4. Filter out all the indicators having reputation either Suspicious or Malicious.

# Next Steps

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) | [Contents](./contents.md) |
| --------------------------------------- | ----------------------------------------- | ------------------- | ------------------------- |
