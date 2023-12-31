# Medical/Biomedical Database Project

This is a sample project for creating and populating a medical/biomedical database using PostgreSQL.

## Project Overview

This project includes SQL files for:

- **Schema.sql**: Defines the database structure.
- **Seed.sql**: Populates the database with sample data.
- **Queries.sql**: Contains sample SQL queries for data retrieval.

## Getting Started

### Prerequisites

- PostgreSQL installed.

### Installation

1. Clone the repository.

2. Create a PostgreSQL database:

   ```bash
   createdb medical_db

3. Run the SQL files:

   ```bash
   psql -U your_username -d medical_db -a -f schema.sql
   psql -U your_username -d medical_db -a -f seed.sq
   psql -U your_username -d medical_db -a -f queries.sql

### Usage

Run SQL files to create schema, seed data, and perform queries.
