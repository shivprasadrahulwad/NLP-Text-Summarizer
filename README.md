# 🤖 End - End NLP Text Summarizer Project

A powerful end-to-end Natural Language Processing (NLP) project that automatically generates concise summaries from large texts using state-of-the-art deep learning techniques.

## 🛠️ Key Technologies

- 🐍 Python 3.8
- 🔥 PyTorch & TensorFlow
- 🚀 MLOps practices
- 💾 SQL databases
- 🐧 Linux environment
- 📂 Git version control
- 💻 Bash scripting
- ⚡ CI/CD pipelines

## 📁 Project Structure

The project follows a modular architecture with the following components:

1. Configuration management
2. Data ingestion and validation
3. Text preprocessing pipeline
4. Model training and evaluation
5. API service layer
6. Docker containerization



![Screenshot 2025-01-22 100039](https://github.com/user-attachments/assets/ee15e390-25ef-42e4-b794-88060f65df46)





## 🚀 Installation Steps

### Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/entbappy/End-to-end-Text-Summarization
   cd End-to-end-Text-Summarization
   ```

2. **Create and activate conda environment**
   ```bash
   conda create -n summary python=3.8 -y
   conda activate summary
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   python app.py
   ```

## 🐳 Docker Setup

### Prerequisites
- Docker installed on your Linux system

### Build and Run with Docker
```bash
# Build the Docker image
docker build -t text-summarizer .

# Run the container
docker run -p 8080:8080 text-summarizer

# Check container status
docker ps

# View logs
docker logs text-summarizer
```

## 🔄 Project Workflows

1. Update `config.yaml`
2. Update `params.yaml`
3. Update entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline
7. Update `main.py`
8. Update `app.py`

## 💻 Development Commands

### 📂 Git Version Control
```bash
# Initialize repository
git init

# Create new branch
git checkout -b feature/text-processing

# Check status
git status

# Add changes
git add .

# Commit changes
git commit -m "Add text processing pipeline"

# Push changes
git push origin feature/text-processing
```

### 🐧 Linux Commands for Development
```bash
# Navigate to project directory
cd text-summarizer

# Check running processes
ps aux | grep python

# Monitor system resources
top

# View logs
tail -f logs/app.log

# Set permissions
chmod +x scripts/*.sh
```

### ⚡ CI/CD Pipeline
The project includes a CI/CD pipeline that handles:
- ✅ Code linting and testing
- 🐳 Docker image building
- 🚀 Container deployment
- 🔍 Automated testing
- 📊 Continuous monitoring



## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
