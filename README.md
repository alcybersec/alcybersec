# Hi there, I'm Aleksandr 👋

![Cyber Security](https://img.shields.io/badge/Cyber%20Security-Student-blue)
![Privacy Advocate](https://img.shields.io/badge/Privacy%20Advocate-Active-green)
![Programmer](https://img.shields.io/badge/Programmer-Python%20%7C%20JavaScript%20%7C%20C%2B%2B-orange)

Welcome to my GitHub profile! I'm a passionate Cyber Security student, privacy advocate, and programmer. I love exploring new technologies and finding ways to secure and protect data.

## 🚀 About Me

- 🔐 Cyber Security Enthusiast
- 🛡️ Privacy Advocate
- 💻 Programmer with experience in Python, C++ and JavaScript
- 📚 Always learning and growing

![Profile Views](https://komarev.com/ghpvc/?username=alcybersec&color=blue)

## 🛠️ Skills

- **Programming Languages:** Python, C++, JavaScript
- **Cyber Security:** Network Security, Ethical Hacking, Penetration Testing
- **Tools:** Wireshark, Metasploit, Burp Suite, Nmap

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=alcybersec&layout=compact&theme=radical)

## 📈 GitHub Stats

![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=alcybersec&show_icons=true&theme=radical)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=alcybersec&theme=radical)

## 📫 How to reach me

- [LinkedIn](https://www.linkedin.com/in/yourprofile)
- [Email](mailto:alworkm@proton.me)

## 📝 Latest Blog Posts

<!-- BLOG-POST-LIST:START -->
- [Post Title](https://yourblog.com/post-title)
- [Post Title](https://yourblog.com/post-title)
<!-- BLOG-POST-LIST:END -->

## 🧑‍💻 Projects

- [Project 1](https://github.com/yourusername/project1) - Description of project 1
- [Project 2](https://github.com/yourusername/project2) - Description of project 2

## 🤝 Support

If you like my work, consider buying me a coffee!
[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Support%20My%20Work-orange)](https://www.buymeacoffee.com/yourusername)

---

## ⚙️ GitHub Actions

### CI/CD Pipeline
```yaml
name: CI/CD Pipeline

on: [push, pull_request]

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
    - uses: actions/checkout@v2
    - name: Set up Python
      uses: actions/setup-python@v2
      with:
        python-version: '3.x'
    - name: Install dependencies
      run: |
        python -m pip install --upgrade pip
        pip install -r requirements.txt
    - name: Run tests
      run: |
        pytest
```

### Code Quality
```yaml
name: Code Quality

on: [push, pull_request]

jobs:
  lint:
    runs-on: ubuntu-latest

    steps:
    - uses: actions/checkout@v2
    - name: Set up Python
      uses: actions/setup-python@v2
      with:
        python-version: '3.x'
    - name: Install dependencies
      run: |
        python -m pip install --upgrade pip
        pip install flake8
    - name: Lint with flake8
      run: |
        flake8 .
```
