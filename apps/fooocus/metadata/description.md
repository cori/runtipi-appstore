# metadata/description.md
Fooocus is a self-hosted service that allows you to generate images from text descriptions. It supports various models and styles, providing a simple web interface for entering text prompts and generating corresponding images.

To use Fooocus, access the web interface at the provided URL and enter a text description of the image you want to generate. Fooocus will process the prompt and generate an image based on your description.

The service requires two volumes to be mapped:
- `/app/models`: Directory for storing the image generation models
- `/app/uploads`: Directory for storing the generated images

Make sure to provide the necessary storage paths for these volumes during the installation process.

