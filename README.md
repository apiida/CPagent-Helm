# CPagent-Helm
This is the Helm Chart installation resource for the APIIDA Control Plane agent
Edit the values.yaml file and insert ALL values requested. The data.configFile base 64 can be created like this: "base64 < [env]Config.yaml"
Install the agent from within this working directory by issuing the command: "helm install [env]cpagent . -f values.yaml"

Further documentation can be found here: https://apiida.atlassian.net/wiki/spaces/AACP/pages/7907180545/Connecting+your+Environments
