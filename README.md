A real-time monitoring dashboard for AWS Lambda functions, tracking metrics like invocations, errors, duration, and cost. 

## Features

-  Metrics visualisation (not in real time)
-  Error tracking and monitoring
-  Cost analysis
-  Performance metrics
-  Historical data trends

## Tech Stack

- Frontend:
  - React
  - Recharts for data visualization
  - Tailwind CSS for styling
  - Shadcn/UI components

- Backend:
  - Node.js
  - Express
  - AWS SDK for CloudWatch metrics

## Prerequisites

- Node.js 16+
- AWS Account with appropriate IAM permissions
- AWS credentials configured locally

## Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/REPO_NAME.git
cd REPO_NAME
```

2. Install backend dependencies:
```bash
cd backend
npm install
```

3. Install frontend dependencies:
```bash
cd ../frontend
npm install
```

4. Create .env file in backend directory:
```
AWS_REGION=your-aws-region
AWS_ACCESS_KEY_ID=your-access-key
AWS_SECRET_ACCESS_KEY=your-secret-key
```

## Running the Application

1. Start the backend server:
```bash
cd backend
npm run dev
```

2. In a new terminal, start the frontend:
```bash
cd frontend
npm run dev
```

3. Open http://localhost:5173 in your browser

## Configuration

To monitor your AWS Lambda functions:

1. Ensure your AWS credentials are properly configured
2. Update the AWS region in the .env file
3. Add your function names to the configuration



## Please note - As I'm using AWS' limited free-tier, I'm not able to fully test/implement all features myself 
