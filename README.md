# Community-Lending-Platform (In Progress)

## Overview
A fintech platform enabling communities to fund purpose-specific loans for life events such as medical, education, and emergencies. The system focuses on trust, transparency, and structured repayment.

## Problem
Millions of individuals lack access to quick, small loans for critical life events. Traditional credit systems exclude them due to lack of credit history or rigid underwriting.

## Solution
A community-backed lending platform where:
- Borrowers request loans for specific purposes
- Multiple lenders fund small portions of the loan
- Repayment is tracked transparently with risk indicators

## Key Features
- Purpose-based loan requests (Medical, Education, Emergency)
- Community-driven funding model
- Loan lifecycle tracking (Requested → Funded → Repaid/Defaulted)
- Transparent risk indicators

## Architecture
Microservices-based, event-driven system:

Event Flow:
- LoanCreated → LoanFunded → PaymentMade → LoanClosed

## Tech Stack
- Java (Spring Boot)
- REST APIs
- Kafka (event streaming)
- MySQL
- Docker

