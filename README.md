# *This is a Pipeline Repo for creating End to End ML Pipeline with S3 Bucket and DVC*

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/8/87/DVC_logo.png" width="140" />
  <img src="https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png" width="160" />
</p>

<h1 align="center">🛠️ MLOps: End-to-End ML Pipeline with DVC & AWS S3</h1>

<p align="center">
  <img src="https://img.shields.io/badge/MLOps-End%20to%20End-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/DVC-Enabled-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AWS-S3-yellow?style=for-the-badge" />
</p>

---

## 📌 <span style="color:#f39c12">Agenda</span>

> Building a modular, configurable, and production-ready ML pipeline with modern MLOps tools.

---

### 🔍 <span style="color:#2980b9">1. Create an End-to-End ML Pipeline</span>

- Logging
- Exception Handling
- Modular Structure
- CI/CD Friendly

```python
try:
    run_pipeline()
except Exception as e:
    logger.error(f"Pipeline failed: {e}")
