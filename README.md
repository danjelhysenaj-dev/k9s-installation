# k9s-installation

To install K9s on your machine on Windows you need to follow these steps below:

1. Install Chocolatey (if not already installed): Open PowerShell as an administrator.
Run the following command to install Chocolatey:
---
    Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
---

2. Install K9s using Chocolatey: After Chocolatey is installed, you can use it to install K9s by running:
---
    choco install k9s
---
3. Verify K9s Installation: To verify that K9s is installed correctly, you can run:
---
    k9s version
---
4. Set Up Kubeconfig: Make sure you have your Kubernetes cluster configured and have the kubeconfig file set up. By default, K9s uses the ~/.kube/config file.
5. Launch K9s: Open a PowerShell or Command Prompt window. Simply run the following command to start K9s:
---
    k9s
---
This will open the K9s interface in your terminal.

6. Using K9s: You can navigate through your Kubernetes cluster using K9s. It provides an interactive interface with various features for viewing and managing your resources.
