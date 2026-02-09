# Task Tracker Project Setup & Run Guide

## Prerequisites

Make sure you have the following installed:

- **Go**  
  Check installation:
  
  ```bash
  go --version
  ```
Download Go if not installed: https://go.dev/dl/

## Project Structure
   empty now I will edit later


## Setup Project
### 1. Clone Repository
```bash
git clone https://github.com/RohitSadawarte79/task-tracker.git
cd task-tracker
```
### 2. Download Dependencies
```bash
go mod tidy
```
### 3. Run the Project
Run single file
```bash
go run main.go
```
## OR
### Build Executable

```bash
go build -o app main.go
```

### Run Binary
- Linux/Mac
```bash
./app
```
- Windows
```bash
app.exe
```
  
