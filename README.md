# Fetch JSON Todo (TypeScript)

A simple TypeScript example that fetches JSON data from a public API using Axios, applies strong typing with an interface, and logs formatted output to the console.

## What This Project Does

- Sends an HTTP GET request to a sample API
- Uses a TypeScript interface to type the response
- Extracts values from the response object
- Logs formatted output to the console

Data source:
https://jsonplaceholder.typicode.com/todos/1

## Tech Stack

- Node.js
- TypeScript
- Axios
- tsx

## Project Structure

```
fetchjson/
├── index.ts
├── package.json
└── README.md
```

## Steps to Run the Project

1. Clone the repository

git clone <your-repo-url>
cd fetchjson

2. Install dependencies

npm install

3. Run the TypeScript file

npx tsx index.ts

## Example Output

The Todo with ID: 1
Has a title of: delectus aut autem
Is it finished? false
