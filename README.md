# Unleash-Self-Host
Host your own instance of unleash on your server

## Steps to Follow:

1. Clone the Unleash repository from [Unleash](https://github.com/Unleash/unleash).
2. Copy the `docker-compose.yml` file from this repository and paste it inside the cloned Unleash folder.
3. Edit the `docker-compose.yml` file to add your domain in labels and adjust your traffic if needed.
4. Run `docker-compose up` to start the containers with appropriate labels.
5. Once the containers are started, you can view your self-hosted Unleash instance on `your-custom-domain.com`.
