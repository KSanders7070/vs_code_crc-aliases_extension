# How to Update and Publish the CRC-Aliases VSCode Extension

Instructions for updating and publishing the CRC-Aliases VSCode extension.

## Step 1: Edit Your Extension

1. Make the necessary changes to your extension's code.
2. Save all changes.

## Step 2: Update `package.json`

1. Open `package.json`.
2. Increment the version number. For example, if the current version is `1.0.0`, update it to `1.0.1`:

    ```json
    {
      "name": "crc-aliases",
      "version": "1.0.1", // Increment the version number
      // other fields...
    }
    ```

3. Save the `package.json` file.

## Step 3: Compile Your Extension

1. Open a terminal or command prompt.
2. Navigate to the root directory of your extension project:

    ```sh
    cd path/to/your/extension/project
    ```

3. Run the compile command:

    ```sh
    npm run compile
    ```

## Step 4: Package Your Extension

1. Ensure you have VSCE (Visual Studio Code Extension Manager) installed. If not, install it globally:

    ```sh
    npm install -g @vscode/vsce
    ```

2. Package your extension:

    ```sh
    vsce package
    ```

3. This command will create a `.vsix` file in the current directory, which is your packaged extension.

## Step 5: Publish Your Extension

1. Login to VSCE (if you haven't already):

    ```sh
    vsce login KyleSanders
    ```

    When prompted, enter your Personal Access Token (PAT).

2. Publish your extension:

    ```sh
    vsce publish
    ```
