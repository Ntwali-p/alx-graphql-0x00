# Rick and Morty GraphQL — Episode by ID

This task demonstrates how to retrieve details of a specific episode from the Rick and Morty GraphQL API using the `episode(id: ID!)` field.

## Objective
Fetch episode details for episode IDs 1, 2, 3, and 4 while requesting only the required fields.

## Fields Retrieved
- id
- name
- air_date
- episode

## API Endpoint
https://rickandmortyapi.com/graphql

## Files
Each `.graphql` file contains a query for a specific episode ID, and each `.json` file contains the corresponding API response.

## How to Test
1. Open https://rickandmortyapi.com/graphql
2. Paste a `.graphql` query
3. Execute the query
4. Save the response into the matching `-output.json` file

## Status
Task completed successfully.
