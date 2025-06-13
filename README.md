# VANI - Versatile API Native Integrator

![VANI Logo](https://github.com/ManojhM-Work/VANI-V2/blob/main/public/Vani_logo.png?raw=true)

VANI is an advanced API testing platform that provides AI-powered API conversion, comprehensive testing capabilities, and seamless CI/CD integration for modern development workflows.

## 🌟 Key Features

### 🔄 AI-Powered API Conversion
- Convert between 12+ API formats including Postman, Swagger, JMeter, Playwright, and more
- AI-assisted schema transformation and validation
- Smart endpoint mapping between different formats
- Batch conversion for large collections

### 🧪 Functional Testing
- Automated test case generation from API specifications
- Visual test scenario builder
- Assertion library with 50+ built-in validations
- Test data management with variables and environments

### ⚡ Performance Testing
- Convert API specs directly to JMeter load tests
- AI-suggested performance thresholds
- Real-time metrics dashboard
- Distributed load testing capabilities

### 🚀 CI/CD Integration
- Native GitHub Actions support
- JUnit/XUnit test reporting
- Performance regression tracking
- Slack/Teams notification hooks

## 🛠️ Tech Stack

**Frontend:**
- React + TypeScript
- ShadCN UI Components
- Vite Build System
- Playwright Test Runner

**Backend:**
- Python Flask
- AI Conversion Engine
- JMeter Integration
- Docker Containerization

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- Python 3.10+
- Docker (optional)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ManojhM-Work/VANI-V2.git
   cd VANI-V2

2. **Install frontend dependencies:**

   ```bash
   cd frontend
   npm install
   ```

3. **Install backend dependencies:**

   ```bash
   cd ../backend
   pip install -r requirements.txt
   ```

4. **Set up environment variables:**

Create .env files in both frontend and backend directories based on the provided .env.example files.


##  🔄 CI/CD Pipeline

VANI comes with pre-configured GitHub Actions workflows:

1. **CI Pipeline - Runs on every PR:**
 - Linting checks
 - Unit tests
 - Integration tests
 - Build verification

2. **CD Pipeline - Runs on merge to main:**
 - Docker image build
 - Deployment to staging
 - Smoke tests
 - (Optional) Production deployment

 ## 📈 Performance Metrics

VANI tracks these key metrics during performance tests:
 - Throughput: Requests per second
 - Response Time: P95 latency
 - Error Rate: Failed requests percentage
 - Resource Usage: CPU/Memory consumption

## 🤖 AI Conversion Features

| Feature                  | Description                                      |
|--------------------------|--------------------------------------------------|
| 🔍 Smart Format Detection | Automatically identifies source API format       |
| 🔄 Schema Transformation  | Converts between different schema standards      |
| 🚀 Endpoint Optimization  | AI-suggests optimal endpoint structures         |
| ✏️ Error Correction       | Fixes common API specification errors           |

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📬 Contact

**Project Maintainer:** Manojh Muthusamy  
**Email:** [manojh1530@gmail.com](mailto:manojh1530@gmail.com)  
**GitHub:** [@ManojhM-Work](https://github.com/ManojhM-Work)
