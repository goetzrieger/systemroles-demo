# system-roles Demo using Automation Controller

When using RHDP env
* Copy creds file template and change values in creds file
* Run create-demo.yml
* Enable node1/node2/node3 in AC
* Create survey with var "cockpit" and two values "true" and "false"

After running the Job Template show running container:
```
curl node1 8080
ssh node1
podman ps
```
