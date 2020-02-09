# G Suite customSchemas mass updater

Install pre-requisites:

```bash
./install.sh
```

Open the following web page and click “Enable the Directory API”: 

https://developers.google.com/admin-sdk/directory/v1/quickstart/python

Login as G Suite administrator

Click DOWNLOAD CLIENT CONFIGURATION

Copy `credentials.json` to this folder

Create and configure `config.json` from `config.json.example`

Run:

```bash
./run.sh
```