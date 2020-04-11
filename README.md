# App_Config_Server

check the properties of config server using      
~~~
http://localhost:8888/actuator/test
http://localhost:8888/actuator/dev
~~~

## Output of config server
~~~
{
    "name": "actuator",
    "profiles": [
        "test"
    ],
    "label": null,
    "version": "d1f1b5dc1f484543a7a073c2b32a1c300fca104a",
    "state": null,
    "propertySources": [
        {
            "name": "https://github.com/9040010697/App_Config_Server_Properties/application-test.yml",
            "source": {
                "spring.application.name": "SpringProfileExample_Test",
                "server.port": 8087
            }
        },
        {
            "name": "https://github.com/9040010697/App_Config_Server_Properties/application.yml",
            "source": {
                "spring.application.name": "SpringProfileExample",
                "server.port": 8085
            }
        }
    ]
}
~~~
