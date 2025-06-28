# Static Website CI/CD with GitHub Actions + AWS S3

🚀 This project sets up a CI/CD pipeline to deploy a static HTML site to AWS S3 using GitHub Actions.

## 🔧 Tools Used

- GitHub Actions (for CI/CD)
- AWS S3 (static website hosting)
- AWS IAM (secure credentials via secrets)
- HTML/CSS

## 📦 How It Works

1. Push to `main` branch
2. GitHub Actions runs a workflow
3. It syncs files to `sahils3` S3 bucket
4. Static site becomes live (temporarily public)

## 🔐 Secrets Required

In GitHub:
- `AWS_ACCESS_KEY_ID`
- `AWS_SECRET_ACCESS_KEY`

---

🌐 *Live URL was disabled to save AWS Free Tier budget.*

