# Basics commands

To build image from dockerfile:
```bash
docker build -t 'my_node_img' .
```

To run your image and expose port 3000 and define name of container:
```bash
docker run -dp 3000:3000 --name my_node my_node_img
```

