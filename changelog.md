# Athena Search Engine Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Features:​

1. Conversational Search​\
  Leverage OpenAI's natural language processing to enable employees to search for documents using conversational language, making the search process more intuitive and user-friendly​
1. Azure Search AI Integration​\
  Harness the power of Azure Search AI to provide lightning-fast and accurate document retrieval, ensuring that employees can quickly access the information they need, including SOPs, promotions, guidelines, and more​
1. React-Powered User Interface\
   Utilize React to create a responsive and dynamic user interface, enhancing the user experience and allowing seamless interaction with the conversational search engine across various devices​
1. FastAPI Backend for Efficient Operations\
   ​
  Implement FastAPI as the backend to handle concurrent requests efficiently, ensuring optimal performance and responsiveness for users accessing and searching documents​
1. PWA Capabilities​\
  Transform our web-based application into a Progressive Web App (PWA), enabling employees to access critical documents even in low-connectivity scenarios​
1. Axios for Robust API Communication\​
  Utilize Axios for making secure and efficient HTTP requests between the React frontend and FastAPI backend, ensuring seamless communication and data retrieval​
1. JWT Authentication for Security​
1. Mobile Responsiveness (Stand-alone Apps)​

## [Unreleased]

## [0.1.2] - 2024-01-24

### Added
- Error handling when OpenAI return zero result
- Adding Axios for API request
- Initial System Message when user first interact with Athena
- Adding Error Message in Chat when Network Error
- Tooltip when hover to Athena FAB
- Prompt Flow functionality
- SAPJam and BIRD datasets
### Fixed
- Remove Card Footer with citation when return zero result
### Changed
- Update `max_tokens` to 800
- Revamp Card color; User: red.500, outline, 25 radius; System: blackAlpha.50, boxShadow md, 25 radius
- Refactor API request syntax
### Removed
- 
