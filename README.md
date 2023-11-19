# Log Ingester and Query Interface

## Features

### 1. Add Logs

- Description: This feature allows users to add new logs to the system.
- Usage: Developers can use the provided API endpoint or user interface to add logs.

### 2. Get All Logs

- Description: Fetches all logs present in the system.
- Usage: Access the provided API endpoint or user interface to retrieve all logs.

### 3. Get Filtered Logs

- Description: Retrieves logs based on specified filters such as level, message, resourceId, timestamp, etc.
- Usage: Use the API endpoint with filters or the provided user interface to get logs based on filter criteria.

## Usage for Developers

### Clone the Repository

```bash
git clone git@github.com:PrateekSrivastava1/Log-Ingestor-and-Query-Interface.git
```

### Navigate to 'log-ingester' and 'query-interface' folders.

```
cd Log-ingester
```

```
npm install
```

```
cd query-interface
```

```
npm install
```

## MongoDB Configuration

- Install MongoDB Compass or use any preferred MongoDB management tool.
- Create a .env file in the 'log-ingester' folder.
- Add the MongoDB URL in the .env file.

```
DB_URL=mongodb://localhost:27017/log-ingester
```

### App Screenshots for your referrence
