# Orchestration
├── README.md
├── Jenkinsfile
├── docker/
│   ├── frontend/
│   │   └── Dockerfile
│   └── backend/
│       └── Dockerfile
├── helm/
│   └── mern-app/
│       ├── Chart.yaml
│       ├── values.yaml
│       └── templates/
│           ├── _helpers.tpl
│           ├── frontend-deployment.yaml
│           ├── frontend-service.yaml
│           ├── backend-deployment.yaml
│           └── backend-service.yaml
└── docs/
    └── architecture-diagram.png
