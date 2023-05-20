## Module: Introduction to Calling HTTP APIs with JavaScript

**Module Description:** This module will introduce you to the fundamentals of calling HTTP APIs using JavaScript. You will learn the basics of making HTTP requests, handling responses, and working with different types of APIs. The module will progress from using fetch and async/await for HTTP requests. You will also practice calling the GitHub API to retrieve popular repositories related to AI.

**Module Duration:** Approximately 4-6 hours

**Learning Objectives:**
By the end of this module, you will be able to:
1. Understand the concepts of HTTP and APIs.
2. Make HTTP requests using fetch and async/await.
3. Handle API responses and extract relevant data.
4. Authenticate and access APIs that require different types of authentication.
5. Apply your knowledge to call the GitHub API and retrieve popular repositories related to AI.

### Activities:

1. **Activity: Introduction to HTTP and APIs**
   - Learn the basics of HTTP, RESTful APIs, and the different HTTP methods (GET, POST, etc.).
   - Practice making HTTP requests using tools like cURL and Insomnia to interact with APIs.
   - Understand the structure of API endpoints, query parameters, and request headers.

2. **Activity: Making GET Requests to the GitHub API**
   - Learn how to use fetch and async/await to make GET requests to the GitHub API.
   - Explore the GitHub API documentation and learn about its endpoints and authentication requirements.
   - Practice calling the GitHub API to retrieve popular repositories related to AI.
   - Handle the JSON responses and extract relevant information from the retrieved repositories.

3. **Activity: API Authentication with API Keys**
   - Learn how to authenticate with APIs that require API keys.
   - Understand the importance of keeping API keys secure and avoiding exposing them in your code.
   - Explore the usage of environment variables to store sensitive information, such as API keys.
   - Practice accessing environment variables in your script to retrieve API keys securely.
   - Understand how to include the API key in request headers or query parameters while keeping it protected.
   - Learn about best practices for securely managing and rotating API keys.
   - Practice calling APIs that utilize API keys for authentication, using the secure storage of API keys through environment variables.

4. **Activity: Create and Update Repository Description**
   - Learn how to create a new repository on GitHub using a POST request.
   - Use the `POST /user/repos` endpoint from the GitHub REST API to create the repository.
   - Authenticate your request using a personal access token.
   - Write a script to send a POST request with the repository name and other optional parameters as the payload.
   - Verify that the repository gets successfully created on GitHub.
   - Once the repository is created, proceed to update its description using a PATCH request.
   - Use the `PATCH /repos/{owner}/{repo}` endpoint to update the repository's description.
   - Send a POST request with the new description as the payload.
   - Verify that the repository description gets successfully updated.

5. **Activity: API Authentication with OAuth**
   - Dive deeper into API authentication by learning about OAuth.
   - Understand the OAuth flow and how to obtain access tokens.
   - Practice authenticating and making requests to APIs that require OAuth.

6. **Activity: Interact with OAuth-Authenticated APIs and Count Unread Emails**
   - Learn how to interact with OAuth-authenticated APIs to access data programmatically.
   - Review the documentation of the specific API you choose to work with and understand the OAuth authentication process.
   - Set up OAuth 2.0 authentication for your script to access the chosen API.
   - Write a script in your chosen programming

