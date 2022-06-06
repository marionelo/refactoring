Rafactoring project
---

This project is in docker so, please firt you have to copy the env.example to .env 

Then you have to assign some variables, to run correctly this project

```env
PROJECT_NAME=name_of_project
HTTP_PORT=http_normal_port
DB_PORT_EXT=db_port
DB_ROOT_PASS=database_root_pass
DB_NAME=database_name
```

After reasign this variables, you can run this command

```sh
docker-compose up -d
```

Finally, you can enter to

https://localhost:http_normal_port

for exmaple, if you assign http_normal_port like 8080

[https://localhost:8080](https://localhost:8080)