# Jenkins Task 2 - GitHub Automatic Build Trigger

## Objective

Create a simple script, push it to GitHub, connect the GitHub repository with Jenkins, automatically trigger a Jenkins build whenever a commit is pushed, and send the build output through email.

## Technologies Used

- AWS EC2
- Jenkins
- GitHub
- Git
- Shell Script
- Gmail SMTP

## Project Files

- `script.sh` - Shell script executed by Jenkins
- `screenshots/` - Screenshots showing the implementation and successful execution

## Jenkins Configuration

- Jenkins Job: `Jenkins-Task-2`
- GitHub Repository: `Jayaseelan7577/Jenkins-Task-2`
- Branch: `main`
- Build Trigger: GitHub hook trigger for GITScm polling

## Build Script

The Jenkins build executes:

```bash
chmod +x script.sh
./script.sh
