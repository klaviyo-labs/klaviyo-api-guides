# Klaviyo API Guides

Klaviyo released a new generation of API in October of 2022. This repository is meant for external developers building on top of Klaviyo to better understand how these new APIs work.

The format of these guides is Jupyter notebooks with a mixture of written explanations, screenshots, and code snippets of real-world examples. The guides use Python, but developers should know that Klaviyo's APIs and SDKs support a broad range of languages.

These guides are meant both for new and experienced Klaviyo developers.

## Features

Currently, there are two guides in this repository: **Understanding customer data** and **Understanding client-side requests**. You can see a preview below of the material covered in each guide. 

### Understanding customer data

Learn how Klaviyo data is structured into events, profiles, and metrics. The guide covers a range of use cases from using Klaviyo's APIs to pull customer profiles, to more advanced examples such as identifying customers who made their first purchase during Black Friday / Cyber Monday.

FAQs covered:
* Who is this guide meant for?
* What do I need to follow along?
* What's an SDK?
* How can I set up an SDK?
* What's an API private key?
* What is the structure of API responses?
* How is customer profile data structured?
* How are events and customer profiles related?
* How can I get customer profile IDs?
* How can I get list or segment IDs?
* What is pagination?
* What's a simple example of pagination?
* What does the links argument mean?
* How does event filtering work?
* How can I filter for events based on date?

### Understanding client-side requests

Learn how to set up a custom integration sending data into Klaviyo. The guide covers examples ranging from how to upload an event to Klaviyo to an example of how client-side requests can be used to generate custom customer review events that can be used to trigger flows.

FAQs covered:
* Who is this guide meant for?
* What's a client-side request?
* What do I need to follow along?
* What's an SDK?
* Where can I find Klaviyo's SDKs?
* Why is this guide in Python and not JavaScript?
* Where can I find examples of custom integrations using JavaScript?
* Why do some metrics appear twice in my account?
* What's the difference between metrics and events
* Why is my API response a 202?
* Why is my API response a NoneType?
* Do I need to provide a schema for new event types?
* What happens if I upload events with the wrong data type?
* Why is Klaviyo rejecting a correctly formatted phone number?
* How can event data be used in Flows/Templates?
* How can rate limit issues be mitigated?

### These guides are best viewed on NBViewer

For the best user experience reading these guides, please view them on NBViewer rather than natively in Github. You can find [Klaviyo's API guides on NBViewer here](https://nbviewer.org/github/klaviyo-labs/klaviyo-api-guides-public).
