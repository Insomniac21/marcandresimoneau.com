---
title: "Send your first API request with Postman"
description: "Task documentation to learn how to send your first API request with Postman."
layout: "post"
version: "1.0.0"
last_updated: 2026-05-31
---

> ✏️ **Draft version**  
> This guide will be improved over time.

# Send your first API request with Postman.

After this guide, you’ll be able to send a request to any API and read the response.

## Purpose

With this knowledge you will be able to start testing your API.

## Prerequisites

- Basic understanding of what a request and a response are
- Postman installed

## Overview

You’ll learn how to enter an API URL, send a request, and read the response returned by the server.

## Steps

### 1. Create a new collection

Click on the Create button. Collections help you organize your requests.

![Click the Create button.](/images/ClickCreateCollection.png)


### 2. Add a new request to the collection

Click on the Add request button.

![Click the Add request button.](/images/ClickAddRequestButton.png)

### 3. Enter your API URL into the request URL bar

Enter your API URL in the bar. This is the address where your request will be sent.

![Write or copy/paste your URL into the bar](/images/CopyPasteURL.png)

*You can use this free API URL : https://jsonplaceholder.typicode.com/posts/1*

### 4. Click the send button

Send your request by clicking the send button. Postman will send the request and show the response at the bottom.

![Click the Send button](/images/ClickTheSendButton.png)

## Expected Result

You should see a response with a 200 OK status.
This means the server understood your request and returned data.
![Click the Add request button.](/images/200OkResponse.png)

## Troubleshooting

Common issues :

- Error adress not found : There may be a typo in the URL.
![Error adress not found](/images/ErrorAdressNotFound.png)

- 404 Not found : The URL or query string may be incorrect.
- 500 Internal Server Error : The API encountered an error while processing your request.
- 400 Bad request : The server is waiting for a request with specific data. 

## Next Steps

- Send a POST request with Postman. (In writing)
- Authentify to an API with Postman. (In writing)
