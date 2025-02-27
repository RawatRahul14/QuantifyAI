# AI-Powered Financial Report Analysis SaaS

## Overview

This project is an AI-powered SaaS application that processes financial reports (PDF/CSV), extracts relevant data using OCR and NLP techniques, calculates financial KPIs, and allows users to interact with the data via an AI-based Q&A system. The project is built using the MERN stack for the frontend and FastAPI (Python) for the backend. The goal is to automate the extraction and analysis of financial data, making it easier for users to gain insights and make data-driven decisions.

## Features

- **Financial Report Upload**: Users can upload PDF/CSV financial reports for analysis.
- **AI-based Table and Text Extraction**: Extract tables and text from the uploaded reports using OCR (Tesseract) and NLP (PyMuPDF, LayoutLMv3).
- **Financial KPI Calculation**: Calculate key financial metrics such as Revenue Growth, Debt-to-Equity, Net Profit Margin, etc.
- **Q&A System**: AI-powered Q&A system for users to ask finance-related questions, with responses derived from the uploaded financial reports.
- **Dashboard**: Visual representation of financial KPIs using charts and graphs (Chart.js).
- **Downloadable Summary**: Download a summary of the financial report with insights.
- **User Authentication & Role Management**: User login system with role-based access control for different features.

## Tech Stack

### Frontend
- **React.js** (UI Framework)
- **MUI/Tailwind** (Styling)
- **Chart.js** (Data visualization)

### Backend
- **Express.js** (Node.js)
- **FastAPI** (Python for AI processing)

### AI & NLP
- **PyMuPDF, Tesseract, LayoutLMv3** (OCR and Text Extraction)
- **Pandas, NumPy, Scikit-learn** (Financial Analysis and KPI Calculation)
- **GPT-4 / FinBERT + Pinecone** (Q&A System)

### Database & Storage
- **MongoDB** (For user and report data)
- **PostgreSQL** (For storing financial records)
- **Pinecone/FAISS** (For vector-based search and retrieval in Q&A system)
- **AWS S3** (For storing uploaded reports)

### Security
- **Firebase/Auth0** (User Authentication)
- **JWT, bcrypt** (JWT-based authentication and password hashing)

## Setup

### Prerequisites

- **Node.js** (for frontend and backend)
- **Python 3.8+** (for AI processing)
- **MongoDB & PostgreSQL** (for databases)
- **AWS S3** (for file storage)