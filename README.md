**Trello-API Testing with Postman**

This project demonstrates testing Trello's API using Postman for managing boards, lists, cards, and checklists.

**Overview**

This project showcases how to interact with Trello's REST API to perform basic operations like creating, updating, and deleting boards, lists, cards, and checklists using Postman.

**Features**

- **Boards:** Create, update, get and delete Trello boards
- **Lists:** Create, update and get Trello lists.
- **Cards:** Add, update, get and delete cards.
- **Checklists:** Create, update, get and delete checklists.
  
**Prerequisites**

- Postman
- Trello API key and token (available from Trello API documentation: https://developer.atlassian.com/cloud/trello/rest/api-group-actions/#api-group-actions)
  
**Getting Started**

**1. Import the Postman Collection:**

Open Postman and import the provided collection (trello-postman-collection.json) which includes all Trello API requests.

**2. Set Up Variables:**

Create a new variables in Postman:

- **apiKey:** Trello API key
- **token:** Trello API token
- **baseUrl:** https://api.trello.com/

**3. Run API Requests:**

Use the imported collection to perform various actions like creating boards, managing lists, working with cards, and adding checklists.

**Validate Responses:**

Use Postman’s features to validate status codes, response bodies, and confirm successful execution of actions.

**Technologies Used**

Postman
