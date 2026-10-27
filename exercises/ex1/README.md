# Exercise 1 - Invoke Agents by interacting with Joule Work

In this exercise, you will learn how to interact with agents via Joule Work and this will help you understand the broader picture on how end users would work with agents in an ineractive manner.

# Exercise 1.1 - Invoke Feedback Classifier Agent by interacting with Joule Work

1. Using a browser (preferably Chrome) launch Joule Work: https://747401964.eu10.sapdas.cloud.sap/new/conversations with user ad161-XXX and the password provided by the instructor. XXX is a placeholder for a number that the instructor assigned to you.

2. Select Joule Work > Conversations > + New and start a new Conversation. You will find the Conversations button in the left side pane.

3. In a new conversation ask Joule to classiy sentiment using an existing agent`use @sentiment-classifier-agent to classify sentiment "The latest application update causes the system to crash every time I open the reports tab. This bug is severely disrupting our daily workflow."`
   <br>
   <br>![](./images/1.ClassifySentiment.png)

4. Observe it's response
   <br>
   <br>![](./images/2.JouleResponse.png)

5. Explore the response details which includes the steps it took and the references it made use of
    <br>
    <br>![](./images/3.JouleResponse-Insights-Steps.png)
    <br>
    <br>![](./images/4.JouleResponse-Insights-References.png)


# Exercise 1.2 - Invoke  by interacting with Joule Work

1. Start a new Conversation by selecting Joule Work > Conversations > + New and start a new Conversation

3. In a new conversation ask Joule to list products using Product Information Agent `use @product-master-data-agent-72mj4 to list products`
   <br>
   <br>![](./images/5.listProducts.png)

4. Observe it's response, response details, steps it took and references it made use of


## Summary

You've now interacted with Joule to invoke agents that have been created and deployed. 

Continue to - [Exercise 2 - Monitor Solutions and Agents with Joule Studio](../ex2/README.md)
