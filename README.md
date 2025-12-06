<!-- =========================
     GitHub Profile README
     Style: Aesthetic & Colorful
     Username: Muhammed-Hassan-1
     Paste this file into the repo named "Muhammed-Hassan-1"
   ========================= -->

<div align="center">

# 👋 Hi — I'm **Mohamed Hassan Abd-Alsabour**
### DevOps & Cloud Engineer · AWS · Kubernetes · CI/CD · Terraform

<p>
  <a href="mailto:mohamed.hassan.abdalsabour@gmail.com">📧 mohamed.hassan.abdalsabour@gmail.com</a> •
  <a href="https://www.linkedin.com/in/mohamedabdalsabour">LinkedIn</a> •
  Egypt
</p>

</div>

---

## 🌈 About Me
I build automated, scalable, and production-grade cloud-native systems. My background in Communications & Electronics gives me strong systems thinking for networking, architecture, and signal-processing projects. I focus on infrastructure-as-code, container orchestration, CI/CD automation, and observability.

- ✅ Strong practical experience with **AWS**, **Kubernetes**, **Docker**, **Terraform**, **Ansible**, and CI/CD pipelines.  
- ✅ Built monitoring & logging solutions using **Prometheus**, **Grafana**, and **ELK**.  
- ✅ Implemented ML inference pipelines inside GNU Radio for real-time signal classification.

---

## 🧰 Tech Stack & Tools

**Cloud & Infra**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

**Containerization & Orchestration**
<img src="https://skillicons.dev/icons?i=docker,kubernetes" alt="docker kubernetes" />

**IaC & Configuration**
<img src="https://skillicons.dev/icons?i=terraform,ansible" alt="terraform ansible" />

**CI / CD & Automation**
<img src="https://skillicons.dev/icons?i=jenkins,github" alt="jenkins github" />

**Monitoring & Logging**
<img src="https://skillicons.dev/icons?i=prometheus,grafana,elastic" alt="prometheus grafana elk" />

**Scripting & ML**
<img src="https://skillicons.dev/icons?i=python" alt="python" />  
**Other:** Linux (Red Hat), TCP/IP, DNS, Load Balancers, Nginx, Apache, Mininet, GNU Radio

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Muhammed-Hassan-1&show_icons=true&theme=tokyonight" alt="GitHub Stats" />
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Muhammed-Hassan-1&layout=compact&theme=tokyonight" alt="Top Languages" />
</p>

---

## 🚀 Featured Projects

> Click a project name to open its repository (create repos with the exact names if you want these links to be live)

### 1. Landmine Detection — **`landmine-detection-gpr-ml`**
**Overview:** Multi-class ML pipeline for landmine classification using Ground-Penetrating Radar (GPR) signal features. Deployed the best-performing model inside GNU Radio for real-time field inference.

**Highlights**
- Feature engineering: amplitude, normalized amplitude, depth, entropy, total energy, flatness, dielectric (εᵣ), sigma, autocorrelation width, phase variance.
- Models evaluated: Logistic Regression, Decision Tree, Random Forest, SVM.
- Real-time deployment using Embedded Python blocks inside GNU Radio.

**Tech:** Python, Scikit-learn, GNU Radio, NumPy, Pandas

**Quick start**
```bash
# Clone (example)
git clone https://github.com/Muhammed-Hassan-1/landmine-detection-gpr-ml.git
cd landmine-detection-gpr-ml

# Create virtualenv and install
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

# Train model (example)
python train.py --data data/processed.csv --model_output models/best_model.pkl

# Run GNU Radio flowgraph (example)
gr-python run realtime_block.py --model models/best_model.pkl
