# Docker Task Management

## Description

This project is a task management application designed to run with Docker. It includes the following components:

- **Postgres**: Database service to store task data
- **Backend**: Built with Spring Boot
- **Frontend**: Built with Angular

---

## Installation

To set up the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone [repository_url]
   ```

2. Navigate to the project directory:
   ```bash
   cd [repository_name]
   ```

3. Ensure the `docker-compose.yaml` file is present in the repository.

4. The repository includes empty `backend-task-management` and `frontend-task-management` directories for backend and frontend development. Clone or initialize them as needed.

    - To clone the backend package:
      ```bash
      git clone [backend_package_url] ./backend-task-management
      ```

    - To clone the frontend package:
      ```bash
      git clone [frontend_package_url] ./frontend-task-management
      ```

---

## Usage

To manage the application, use the following `docker-compose` commands:

### Build and start the services:
```bash
docker-compose up --build
```

### Stop the services:
```bash
docker-compose down
```

### View logs from all services:
```bash
docker-compose logs -f
```

### Restart the services:
```bash
docker-compose restart
```

---

## Contributing

Feel free to submit issues or pull requests for improvements or fixes.



