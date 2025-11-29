# SookMissing_k8s

### 📂 Directory 구조

```text
kubernetes/
├── common/               
│   ├── configmap.yaml
│   ├── secrets.yaml
│   └── ingress.yaml
│
├── database/            
│   ├── db-cronjob.yaml
│   ├── db-pvc.yaml
│   ├── db-service.yaml
│   └── db-statefulset.yaml
│
├── api-server/           
│   ├── api-deployment.yaml
│   ├── api-hpa.yaml
│   └── api-service.yaml
│
├── analyzer/             
│   ├── analyzer-deploy.yaml
│   └── analyzer-service.yaml
│
└── frontend/            
    ├── frontend-deployment.yaml
    └── frontend-service.yaml
