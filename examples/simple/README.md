## Example instantiation of the App module

### Interact with the application:
- To interact with the Application the following URL can be used:
```
export app_public_ip=terraform-app-public-ip-output
open "http://${app_public_ip}"
```
- A Markdown viewer can be used as below:
```
opem "https://stackedit.io/viewer#!url=${app_public_ip}"
```