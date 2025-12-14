# Rick and Morty GraphQL — Character by ID

This task demonstrates how to query a specific character from the Rick and Morty GraphQL API using the `character(id: ID!)` field.

## Objective
Retrieve character details for IDs 1, 2, 3, and 4 while requesting only the required fields to avoid over-fetching.

## Fields Retrieved
- id
- name
- status
- species
- type
- gender

## API Endpoint
https://rickandmortyapi.com/graphql

## Files
Each `.graphql` file contains a query for a specific character ID, and each corresponding `.json` file contains the API response returned by the GraphQL server.

## How to Test
1. Open https://rickandmortyapi.com/graphql
2. Paste the contents of any `.graphql` file
3. Run the query
4. Copy the response into the matching `-output.json` file

## Status
Task completed successfully.
