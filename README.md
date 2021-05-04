# mlonggit.github.io
 mlong website

https://github.com/mlonggit/mlonggit.github.io

https://mlonggit.github.io/

https://docs.microsoft.com/en-us/azure/static-web-apps/getting-started?tabs=vanilla-javascript

URL
https://gentle-ground-0a673c410.azurestaticapps.net

index  main
index2 modify resume work experience

Add an API
https://docs.microsoft.com/en-us/azure/static-web-apps/add-api

{
    "liveServer.settings.port": 5501,
    "staticWebApps.appSubpath": "/",
    "staticWebApps.apiSubpath": "api",
    "staticWebApps.outputSubpath": "/"
}


{
  "bindings": [
    {
      "authLevel": "anonymous",
      "type": "httpTrigger",
      "direction": "in",
      "name": "req",
      "methods": [
        "get",
        "post"
      ],
      "route": "message"
    },
    {
      "type": "http",
      "direction": "out",
      "name": "res"
    }
  ]
}
function.json


With Core Tools running, navigate to the following URL to verify the API is running correctly:
 http://localhost:7071/api/message.




Unable to find project root. Expecting to find one of host.json, local.settings.json in project root.
The terminal process "C:\WINDOWS\SysNative\WindowsPowerShell\v1.0\powershell.exe -Command func host start" terminated with exit code: 1.


(Ver 4.3.2)
(Ver 4.4.1)

