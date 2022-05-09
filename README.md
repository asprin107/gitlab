### 1. Install and configure the necessary dependencies
```
sudo apt-get update
sudo apt-get install -y curl openssh-server ca-certificates tzdata perl
```

### 2. Add the GitLab package repository and install the package
```
curl https://packages.gitlab.com/install/repositories/gitlab/gitlab-ee/script.deb.sh | sudo bash
```

### 3. Host enrollment
```
sudo EXTERNAL_URL="http://gitlab.example.com" apt-get install gitlab-ee
# sudo EXTERNAL_URL="https://gitlab.example.com" apt-get install gitlab-ee
```

password generated randomly saved at `/etc/gitlab/initial_root_password` for `root` user.
