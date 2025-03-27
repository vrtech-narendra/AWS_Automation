

---

# 🛠 Installing Boto3 and AWS CLI v2


## 📦 Windows

### ✅ Install Boto3

1. **Verify Python & pip installation:**
   ```bash
   python --version
   pip --version
   ```
2. **Check Boto3 version compatibility** at: [https://pypi.org/project/boto3](https://pypi.org/project/boto3)  
3. **Install Boto3:**
   ```bash
   pip install boto3
   ```
4. **Upgrade Boto3 (if already installed):**
   ```bash
   pip install --upgrade boto3
   ```
5. **Install a specific version (optional):**
   ```bash
   pip install boto3==1.28.72
   ```
6. **Verify Boto3 installation:**
   ```bash
   pip show boto3
   ```

### ✅ Install AWS CLI v2

> Note: Installing via `pip install awscli` installs **AWS CLI v1**, which is deprecated.

- **Download & Install AWS CLI v2 using MSI:**
  [AWS CLI v2 MSI Installer](https://awscli.amazonaws.com/AWSCLIV2.msi)

- **Verify installation:**
  ```bash
  aws --version
  ```

---

## 🐧 Linux

### ✅ Install Boto3

1. **Verify Python & pip installation:**
   ```bash
   python3 --version
   pip3 --version
   ```
   > If `pip3` is not installed:
   ```bash
   sudo yum install python3-pip  # (for RHEL/CentOS)
   ```

2. **Check Boto3 version compatibility:**  
   [https://pypi.org/project/boto3](https://pypi.org/project/boto3)

3. **Install/Upgrade Boto3:**
   ```bash
   pip3 install boto3
   pip3 install --upgrade boto3
   ```

4. **Install specific version (optional):**
   ```bash
   pip3 install boto3==1.28.72
   ```

5. **Verify Boto3 installation:**
   ```bash
   pip3 show boto3
   ```

### ✅ Install AWS CLI v2

> Avoid installing via pip to ensure v2 is installed.

1. **Download & install AWS CLI v2:**
   ```bash
   curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
   unzip awscliv2.zip
   sudo ./aws/install
   ```

2. **Verify installation:**
   ```bash
   aws --version
   ```

---

## 🍎 macOS

### ✅ Install Boto3

1. **Verify Python & pip installation:**
   ```bash
   python3 --version
   pip3 --version
   ```

2. **Check Boto3 version compatibility:**  
   [https://pypi.org/project/boto3](https://pypi.org/project/boto3)

3. **Install/Upgrade Boto3:**
   ```bash
   pip3 install boto3
   pip3 install --upgrade boto3
   ```

4. **Install specific version (optional):**
   ```bash
   pip3 install boto3==1.28.72
   ```

5. **Verify Boto3 installation:**
   ```bash
   pip3 show boto3
   ```

### ✅ Install AWS CLI v2

> Avoid `pip install awscli` to ensure you're using **v2**.

1. **Download & install AWS CLI v2:**
   ```bash
   curl "https://awscli.amazonaws.com/AWSCLIV2.pkg" -o "AWSCLIV2.pkg"
   sudo installer -pkg AWSCLIV2.pkg -target /
   ```

2. **Verify installation:**
   ```bash
   aws --version
   ```
