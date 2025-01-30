# Git Instructions for New Users

## 1. Install Git
To install Git, follow these steps based on your operating system:

### Windows
1. Open PowerShell as an **Administrator**.
2. Run the following command to download and install Git:
   ```powershell
   winget install --id Git.Git -e --source winget
   ```

## 2. Clone a GitHub Repository
To clone the repository to a local directory named "exp_task":

Open Terminal or Command Prompt.  

Run the following command: 
```powershell
git clone https://github.com/Structure-Memory-Sleep/exp_task.git exp_task
```

## 3. Check Git Status
After making changes to the code, check the status of your repository:
```powershell
cd exp_task
git status
```
## 4. Stage Changes
To stage all changes for commit:
```powershell
git add .
```

## 5. Commit Changes
To commit the staged changes:
```powershell
git commit -m "Your commit message"
```

## 6. Push Changes
To push your changes to the remote repository:
```powershell
git push origin main
```

## 7. Pull Changes
If the remote repository has been changed by someone else, pull the latest changes:
```powershell
git pull
```