# Docker Basic Linux Commands Demo


## Question 1: Five DevOps Concepts

1. **Continuous Integration (CI):** Automates code integration and testing, reducing integration issues and errors.  
2. **Continuous Delivery/Deployment (CD):** Ensures code changes are deployed safely and reliably to staging or production environments.  
3. **Containerization:** Docker allows packaging applications with all dependencies in a single container, ensuring consistency across environments.  
4. **Version Control & Collaboration:** Git and GitHub help manage code history, enable collaboration, branching, and merging efficiently.  
5. **Monitoring & Logging:** Tools like Prometheus, Grafana, or ELK Stack monitor systems and applications, helping detect and solve issues quickly.

---

## Question 2: How I Completed This Assignment

**Step 1: Project Setup**  
- Created project folder `docker-basic-linux-ops`.  
- Added files: `Dockerfile`, `run_commands.sh`, `.dockerignore`, `README.md`.  
- Made the script executable:  
```bash
chmod +x run_commands.sh
Step 3: GitHub Repository

Created a repository named docker-basic-linux-ops on GitHub.

git remote add origin https://github.com/<github-username>/docker-basic-linux-ops.git
git branch -M main
git push -u origin main


Step 4: Docker Image Build and Run

docker build -t docker-basic-linux-ops:1.0 .
docker run --rm docker-basic-linux-ops:1.0


Executed basic Linux commands: date, whoami, hostname, uname -a, df -h, free -h, ps aux, ip addr, ls, printenv, curl.

Step 5: Docker Hub Push

docker login
docker tag docker-basic-linux-ops:1.0 <dockerhub-username>/docker-basic-linux-ops:1.0
docker push <dockerhub-username>/docker-basic-linux-ops:1.0

Question 3: How This Helps Learn DevOps, Linux, Git, and Docker

Docker:
Builds images and runs containers, practicing containerization and reproducible environments.

Linux:
Running run_commands.sh reinforces command-line skills: process management, disk and memory usage, network info, environment variables, and HTTP requests.

Git & GitHub:
Practiced version control: commits, branching, pushing, and collaboration workflows.

DevOps Concepts:
Simulates CI/CD pipelines: code → build → container → test → push.
Demonstrates containerization and system monitoring principles.
