# Installation

Before you start, make sure you
- have Docker installed and running on your machine.
- have Ollama installed.
- (optional) have Java 17 installed – only for building the project.
- (optional) have Maven 3.8.4 or later installed – only for building the project.

To import ollama models, extract them from the tar file and place them in a directory where Ollama can access them. For example, on Linux/macOS/Windows, you can place them in `~/.ollama/models/`.

To check if models are imported correctly, you can use the following command:
```shell
ollama ls
ollama run <model-name>
```

To import Docker images, run:
```shell
docker load -i message-template-images.tar
```

then run:
```shell
docker images
```
to check if the images are loaded correctly.
