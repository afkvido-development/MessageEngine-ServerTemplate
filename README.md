# MessageEngine Server Template
A template for you to create your own MessageEngine servers

## How to make your MessageEngine server

### Step 1: Use the template
https://github.com/afkvido-development/MessageEngine-ServerTemplate/generate
Name the repository what you want your server address to be.
Make sure your branch is named `main`

A server address will always be `[UserName]/[RepoName].msgeng`

### Step 2: Configure
Your server will not work if the configs are not set up correctly.

`/src/Main.yml`
Make sure that:
- `serverAddress: [UserName]/[RepoName].msgeng`
- `disabled: false` If disabled is true, then good luck with your server. Disabled is a useful tool for when you want to close a server.
- `serverName: [Server Name]` Pick whatever you want your server to be called!
- `serverUrl: https://github.com/[UserName]/[RepoName]/tree/main/server.msgeng`
- `version: v0.0.0-Type` Choose the version you want your server to run on ([Latest Alpha](https://github.com/afkvido-development/MessageEngine-API/blob/master/src/api/versions/latest/Alpha.yml), [Latest PTB](https://github.com/afkvido-development/MessageEngine-API/blob/master/src/api/versions/latest/PTB.yml), [Latest Stable](https://github.com/afkvido-development/MessageEngine-API/blob/master/src/api/versions/latest/Stable.yml), [Latest LITE](https://github.com/afkvido-development/MessageEngine-API/blob/master/src/api/versions/latest/LITE.yml))

### Step 3: Enable

Almost done! Now, go to `(root)/server.msgeng`.
It's value is probbably `false`.
Replace `false` with `true`.

**Your server is now ready**
