# NLW Ignite

## Installation

### Dependencies

1. Install NVM by running the following command in your terminal:
    ```shell
    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
    ```

2. Set the NVM environment variable by adding the following line to your shell profile (e.g., `.bashrc`, `.zshrc`, etc.):
    ```shell
    export NVM_DIR="$HOME/.nvm"
    [ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh"
    ```

3. Install Node.js by running the following command in your terminal:
    ```shell
    nvm install node
    ```

#### Server

1. Navigate to the `server` directory
2. Install the server dependencies by running the following command:
    ```shell
    npm i
    ```
3. Copy the `.env.template` to `.env` running the following command:
   ```shell
   cp .env.template .env
   ```
4. Replace <Github client_id> to your Github Client ID
5. Replace <Github client_secret> to your Github Secret
6. Start the server running the following command:
    ```shell
    npm run dev
    ```

#### Web Application

1. Navigate to the `web` directory
2. Install the server dependencies by running the following command:
    ```shell
    npm i
    ```
3. Copy the `.env.template` to `.env` running the following command:
   ```shell
   cp .env.template .env
   ```
4. Replace <public Github client_id> to your Public Github Client ID
5. Start the web running the following command:
    ```shell
    npm run dev
    ```

#### Mobile Application

1. Navigate to the `moblie` directory
2. Install the mobile dependencies by running the following command:
    ```shell
    npm i
    ```
3. To start the application there are some options:

    1. Choosing the simulator running the following command:
    ```shell
    npm run start
    ```
    2. Using IOS simulator running the following command:
    ```shell
    npm run ios
    ```
    3. Using Android simulator running the following command:
    ```shell
    npm run android
    ```