# cicd-laravel

Laravel project ci/cd

# Usage
  - Manually deploy your project in server using git clone, git pull, composer install, etc. Ensure your server has access to your git project
  - Add .github/workflows to the project that need to use ci/cd
  - Add SERVER_ADDRESS (server IP address), SERVER_PORT, SERVER_USER, SERVER_PRIVATE_KEY (server private SSH key) to the github action secret at your_github_project_url/settings/secrets/actions ex: https://github.com/dimasdhimek/cicd-laravel/settings/secrets/actions
  - After that, for every push to main action will trigger github action script that deploy your project

# Author
Dimas Setiawan
dimasdhimek@gmail.com