# Multipass-Docker
Install & manage Docker environments using Multipass Ubuntu LXC solution. 🐳🚀

## Getting Started

1. Visit the Multipass installation page: [https://multipass.run/install](https://multipass.run/install).
2. Follow the instructions provided on the website to download and install Multipass on your Windows machine.

## Launching an Instance

3. Open a command prompt or terminal and launch a default instance using the following command:

    ```bash
    multipass launch --name foo
    ```

   Replace "foo" with the desired name for your instance.

4. To create a customized instance with specific resources, you can use the following command as an example:

    ```bash
    multipass launch --name custom-instance --cpus 2 --disk 15G --memory 2G
    ```

   Adjust the options (`--cpus`, `--disk`, `--memory`) based on your requirements.

## Viewing Your Instances

5. To see a list of your instances, run:

    ```bash
    multipass list
    ```

   This will display information about the currently running instances.

## Managing Multipass Instances

### Stopping Instances


To stop specific instances, run:

```bash
multipass stop foo bar
```

## Install Docker and Portainer

1. Run the `docker-install.sh` script to install Docker.

   ```bash
   ./docker-install.sh

   ```
2. Execute the `portainer-install.bash` script to install Portainer.

   ```bash
   ./portainer-install.bash
   ```
# Step 3: Check info file for relevant links and information

3. Get your local IP address using ifconfig
```bash
cat info

