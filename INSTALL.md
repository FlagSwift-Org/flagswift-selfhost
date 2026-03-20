1. Install Docker
2. Login to container registry `echo PAT | ldocker login ghcr.io -u <YOUR_GITHUB_USERNAME> --password-stdin`
3. Copy .env.example to .env and input your custom variables
4. Run: docker compose up -d
5. Check the browser localhost:3000