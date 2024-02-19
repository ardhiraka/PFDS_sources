# Athena Search Engine Changelog & Datasets

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Dataset List

- SMLink
- SAPJam
  - AIR_IPL
  - AJB_PBB_PBG
  - Event Sinar Mas Land
  - FASILITAS
  - FORMULIR
  - Gangguan
  - LINGKUNGAN
  - List Furniture, Ukur Ulang Kavling, Dimensi Kavling, Access Card
  - Project Joint Venture (JV)
  - RENOVASI_PERBAIKAN_PBG
  - SALES & PROMOTION
  - Serah Terima
  - SMART HOME
  - SOP
- Research
  - BN
  - CR
  - SR
- Testing
  - Biaya Ganti Meter Air.pdf
  - FAQ Smart Move.pdf
  - Jadwal & Tarif Bus Sinar Jaya Trans BSD 2022.pdf
  - Last Call Double Dream.pdf
- Excluded Document (Invalid Format):
  - Tarif Air BSD Timur Per Februari 2024
  - Auth Policy Project Structure for Upload
  - KF The Wealth Report
  - CR Colliers 2022
  - CR Colliers 2021
  - KPI Directory Section Below
  - Peraturan Perusahaan PT. BKS
  - CIMB Agribusiness
  - BN 2021 Innovative Construction
  - BN 2021 Gen Z The World Brain
  - BN 2021 Agritech
  - Tarif Service IPL Kawazan Mozia
  - Tarif Service IPL Cluster Jadeite
  - BN 2022 Climate Change Behavior
  - SOP Ketentuan Pemakaian Searagam
  - SOP on the requisition and stock opname
  - SOP TRM Tender
  - SOP on Sales Cancellation
  - SOP on sale of east indonesia
  - SOP on Golf Membership
  - SOP on External Sales Agent Commission
  - SOP on Application of New HGB
  - Policies and Procedures on Submission and Reimbursement
  - SOP on Preparation and Approval of Contract Plan
  - SOP on Internal Sales Commission
  - SOP on Handover
  - SOP on Evaluation of New Vendor
  - Whistleblowing
  - Policy on Recruitment Management
  - Policy on Mendical Health Care
  - Form Peminjaman Kendaraan Sinar Mas Land
  - SOP of Notarization
  - Newsletter Digital Hub Q4 2023

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

## [Alpha Release]

## [0.2.1] - 2024-02-14

### Added
- Streaming Response!
- Log all user activities to Mongo Atlas and Azure Datalake
- Adding user feedback button and functionality
- Adding copy button
- Function to save log and feedback as csv to Azure Datalake
- User initial dummy request for first time visit to improve response time
- UserId generation and logging
### Fixed
- Fixing column name for database
- Value for feedback and log: adding response time and userId
- Fixing FaB sizing for responsiveness
### Changed
- Major revamp of user interface (ChatGPT look-alike), improving ux.
- Change ip to userId
- Revamp user interface for FaB version
### Removed
- 

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
