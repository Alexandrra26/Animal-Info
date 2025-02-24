# Animal Info

## Project Overview

This project focuses on the theme of **"Animals"**, specifically featuring the **koala**. The application provides information about koalas and follows a structured development process using **Flask**, **Docker**, **Jenkins**, and **pytest**.

## Steps for Project Development

### 1. Setting Up the Development Environment
- Installed **VirtualBox** to work in a Linux environment.
- Set up a virtual machine and installed essential tools:
  - **Git**
  - **Gedit**
  - **Docker**
  - **Jenkins**
  - **Python3**
  - **pytest**

### 2. Installing Required Packages
- **Git installation**:
  ```bash
  sudo apt install git
  ```
- **Gedit installation**:
  ```bash
  sudo apt install gedit
  gedit 442D_koala.py
  ```
- **Python3 installation**:
  ```bash
  sudo apt install python3
  ```
- **Docker installation**:
  Followed the official [DigitalOcean guide](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-22-04).
- **Jenkins installation**:
  Used the official [Jenkins installation guide](https://www.jenkins.io/doc/book/installing/linux/).

### 3. Project Implementation
- Created the necessary project files, including:
  - Python script for koala information.
  - Flask application for serving the web interface.
  - Configuration files for **Jenkins** and **Docker**.
- Tested all scripts using **pytest**.

### 4. Deploying and Testing the Application
- Uploaded all files to **GitHub**.
- Configured **Jenkins** in the browser to:
  - Build the application.
  - Display a **pipeline diagram** showing all application stages.
  - Detect and report errors in different stages of the application.

## Technologies Used
- **Python 3** - Core programming language.
- **Flask** - Web framework for serving the application.
- **Docker** - Containerization of the application.
- **Jenkins** - CI/CD automation tool for building and testing.
- **pytest** - Used for automated testing.
- **Git & GitHub** - Version control and repository management.

## Running the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Curs_VCGJ_24_animale.git
   cd Curs_VCGJ_24_animale
   ```

2. **Run the Flask application**:
   ```bash
   python3 app.py
   ```

3. **Run the tests**:
   ```bash
   pytest
   ```

4. **Deploy with Docker**:
   ```bash
   docker build -t koala_app .
   docker run -p 5000:5000 koala_app
   ```

5. **Monitor the pipeline with Jenkins**:
   - Open Jenkins in the browser.
   - Navigate to the project pipeline.
   - Observe the status of each stage.


