# Simply use Docker Image

🚀 Welcome to the Docker Hub repository for hfarkhari/text_web_ui! This repository hosts a Docker image designed for deploying the text-generation-webui v1.5 application.

### Key Features:

✅ Simplified Deployment: Quickly run text-generation-webui v1.5 with just a few commands.
✅ Version and Dependencies: Based on text-generation-webui v1.5 with various extensions.
✅ Customization: Easily enable specific features by passing command-line flags.
✅ Enhanced Performance: Utilizes caching for improved download and model loading times.
✅ User Security: Runs under a non-root user for added security.

**Get Started:**

1. [Clone the Git Repository](https://github.com/oobabooga/text-generation-webui): Clone the text-generation-webui Git repository to your system.

2. [Run the Docker Container](https://hub.docker.com/r/hfarkhari/text_web_ui): Execute the Docker run command to launch the text-generation-webui.

3. [Access the Web Application](https://hub.docker.com/r/hfarkhari/text_web_ui): Open your browser and explore text-webui at [http://127.0.0.1:7777](http://127.0.0.1:7777).

**Version Information:**

- Docker Image: [docker pull hfarkhari/text_web_ui:v1.5_gradio_3.43.2_user_p7777](https://hub.docker.com/r/hfarkhari/text_web_ui)
- GitHub Repository: [text-generation-webui](https://github.com/HFarkhari/Text_Generation_WebUI) OR [here](https://github.com/oobabooga/text-generation-webui)
- Additional Extensions: api, elevenlabs_tts, sd_api_pictures, send_pictures, silero_tts, whisper_stt

**Advanced Usage:**

- Customize your container by enabling specific features using command-line flags.
- Explore the full range of options for running the Docker container in the [Docker Hub repository](https://hub.docker.com/r/hfarkhari/text_web_ui).

**Recommended Full Command:**

```shell
docker run --gpus all --net=host --ipc=host --ulimit memlock=-1 --ulimit stack=67108864 -p 7777:7777 -it --rm --shm-size=16g -v $(realpath ~/Desktop/text-generation-webui):/workspace hfarkhari/text_web_ui:v1.5_gradio_3.43.2_user_p7777
```

Enhance your text-generation experience with this Docker image. For any questions or further assistance, please visit the [Docker Hub repository](https://hub.docker.com/r/hfarkhari/text_web_ui) or the [GitHub repository](https://github.com/oobabooga/text-generation-webui). Happy text generation! 📝🎉
