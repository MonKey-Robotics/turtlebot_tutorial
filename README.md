
# monkey_turtlebot_tutorial

Dockerfile for MonKey Turtlebot ROS2 Tutorials.

## Docker Deployment

### Windows
To build docker image:
```bash
docker compose -f compose.windows.yaml build
```

To run docker image:
```bash
docker compose -f compose.windows.yaml up -d
docker compose -f compose.windows.yaml exec monkey-turtlebot bash
```

### Linux
To build docker image:
```bash
docker compose -f compose.ubuntu.yaml build
```

To run docker image:
```bash
docker compose -f compose.ubuntu.yaml up -d
docker compose -f compose.ubuntu.yaml exec monkey-turtlebot bash
```

## Authors

- [@LocoHao](https://github.com/LocoHao)

