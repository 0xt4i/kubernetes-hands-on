# Kubernetes Hands-On - Học Kubernetes Thực Hành

Repository này chứa các bài lab và ví dụ thực hành để học Kubernetes từng bước một, được tổ chức theo các module riêng biệt.

## 📋 Mục Lục

- [Giới thiệu](#giới-thiệu)
- [Cấu trúc Repository](#cấu-trúc-repository)
- [Yêu cầu](#yêu-cầu)
- [Cách sử dụng](#cách-sử-dụng)
- [Các Module Học Tập](#các-module-học-tập)

## 🎯 Giới thiệu

Repository này được thiết kế để giúp bạn học Kubernetes thông qua thực hành. Mỗi thư mục đại diện cho một module học tập cụ thể, chứa các bài lab, ví dụ và tài liệu hướng dẫn.

## 📁 Cấu trúc Repository

```
kubernetes-hands-on/
│
├── kubernetes/              # Các module học Kubernetes core
│   ├── 01_Storage/         # Module về Storage trong Kubernetes
│   ├── 02_Workloads_Scheduling/  # Module về Workloads và Scheduling
│   ├── 03_Servicing_Networking/  # Module về Services và Networking
│   ├── 04_Troubleshooting/      # Module về Troubleshooting
│   ├── 05_Cluster_Architecture/ # Module về kiến trúc Cluster
│   └── setup/              # Scripts setup môi trường lab
│
├── ansible/                # Automation với Ansible
├── helm/                   # Package management với Helm
├── jenkins/                # CI/CD với Jenkins
└── cicd/                   # CI/CD pipelines
```

## 🔧 Yêu cầu

Trước khi bắt đầu, bạn cần cài đặt:

- **Kubernetes cluster** (có thể sử dụng Minikube, Kind, hoặc K3s cho môi trường local)
- **kubectl** - Kubernetes command-line tool
- **Docker** - Container runtime
- **Git** - Version control

### Optional Tools:
- **Helm** - Kubernetes package manager
- **Ansible** - Configuration management tool
- **Jenkins** - CI/CD automation server

## 🚀 Cách sử dụng

1. **Clone repository:**
   ```bash
   git clone https://github.com/0xt4i/kubernetes-hands-on.git
   cd kubernetes-hands-on
   ```

2. **Chạy setup scripts (nếu cần):**
   ```bash
   cd kubernetes/setup
   ./01_setup_storage_lab.sh
   ```

3. **Bắt đầu với module đầu tiên:**
   ```bash
   cd kubernetes/01_Storage
   # Đọc README trong thư mục để biết hướng dẫn chi tiết
   ```

## 📚 Các Module Học Tập

### Module Kubernetes Core

#### 1. **Storage (01_Storage)**
Học về các khái niệm storage trong Kubernetes:
- Volumes
- Persistent Volumes (PV)
- Persistent Volume Claims (PVC)
- Storage Classes
- StatefulSets

#### 2. **Workloads & Scheduling (02_Workloads_Scheduling)**
Tìm hiểu về các workload resources và scheduling:
- Pods
- Deployments
- ReplicaSets
- DaemonSets
- Jobs và CronJobs
- Node Selector, Affinity & Anti-affinity
- Taints và Tolerations

#### 3. **Services & Networking (03_Servicing_Networking)**
Nắm vững networking trong Kubernetes:
- Services (ClusterIP, NodePort, LoadBalancer)
- Ingress và Ingress Controllers
- Network Policies
- DNS trong Kubernetes
- Service Mesh basics

#### 4. **Troubleshooting (04_Troubleshooting)**
Học cách debug và khắc phục sự cố:
- kubectl debugging commands
- Logs và Events
- Resource monitoring
- Common issues và solutions
- Best practices

#### 5. **Cluster Architecture (05_Cluster_Architecture)**
Hiểu về kiến trúc Kubernetes:
- Control Plane components
- Node components
- etcd
- API Server
- Scheduler và Controller Manager
- High Availability

### Module DevOps Tools

#### **Ansible**
Tự động hóa cấu hình và deployment với Ansible

#### **Helm**
Package management và templating cho Kubernetes applications

#### **Jenkins**
Thiết lập CI/CD pipelines cho Kubernetes deployments

#### **CI/CD**
Các pipeline và workflows để tự động hóa deployment

## 💡 Lộ trình học tập đề xuất

1. Bắt đầu với **Storage** để hiểu cách Kubernetes quản lý dữ liệu
2. Tiếp theo **Workloads & Scheduling** để nắm vững cách deploy applications
3. Học **Services & Networking** để connect các components
4. Thực hành **Troubleshooting** để có thể tự giải quyết vấn đề
5. Tìm hiểu **Cluster Architecture** để hiểu sâu hơn về Kubernetes
6. Cuối cùng, tích hợp với **Ansible**, **Helm**, và **Jenkins** để tự động hóa

## 📝 Ghi chú

- Mỗi module có thể có README riêng với hướng dẫn chi tiết
- Các bài lab được thiết kế để thực hành hands-on
- Khuyến khích thử nghiệm và modify các examples
- Tham khảo Kubernetes documentation chính thức khi cần

## 🤝 Đóng góp

Nếu bạn muốn đóng góp hoặc tìm thấy lỗi, vui lòng tạo issue hoặc pull request.

## 📖 Tài nguyên tham khảo

- [Kubernetes Official Documentation](https://kubernetes.io/docs/)
- [Kubernetes by Example](http://kubernetesbyexample.com/)
- [Helm Documentation](https://helm.sh/docs/)
- [Ansible Documentation](https://docs.ansible.com/)

## 📄 License

MIT License

---

**Happy Learning! 🎓**
