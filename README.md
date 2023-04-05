# ds_task_1b_Khuzaima

We can make this approach more good and reliable if we use the document_scores generating from our index and then filtering out only the top most similar context to user query and then passing it as a prompt to our gpt model. We can get better results as our prompt would contain the context quite similar to user_query.

## Writing Massive rules in Chatgpt
1. Identify the topics or areas you want to cover with your rules.
2. Create a list of rules that cover each of these topics or areas. Try to create a comprehensive set of rules that address common questions or issues related to each topic.
3. Organize the rules into a structured format such as a spreadsheet or JSON file. This will make it easier to input them into the Chat GPT API.
4. Use appropriate formatting for the rules. For example, if you are using a spreadsheet, use separate columns for the input and output of each rule. If you are using a JSON file, use the appropriate syntax for defining rules and their corresponding responses.

## Making it cost-effective

Prioritize the most important rules: Focus on the rules that are most likely to be used frequently by your users. By prioritizing the most important rules, you can reduce the number of tokens needed to cover the most common scenarios.

Use a machine learning approach: Instead of providing a large number of rules, you can use a machine learning approach to allow the Chat GPT API to learn from examples and generate responses based on patterns and relationships it finds in the data. This can be more cost-effective in the long run because the AI model can continue to learn and improve over time.

Use a hybrid approach: You can use a combination of rule-based and machine learning approaches to reduce the number of tokens needed. For example, you can input a set of high-priority rules and use a machine learning model to generate responses for less common scenarios.

Group similar rules together: If you have many similar rules, you can group them together to reduce the number of tokens needed. For example, if you have a set of rules related to product features, you can group them together into a single rule that covers all possible scenarios related to product features.
