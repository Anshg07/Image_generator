# Text to Image Generation with DreamShaper XL

This project utilizes the DreamShaper XL model for text-to-image generation. Given a text prompt, the model generates an image corresponding to the input text. The project employs the `diffusers` library for efficient generation and utilizes GPU acceleration for faster processing.

## Setup Instructions
1. Ensure you have Python installed on your system.
2. Install the required libraries:
    ```
    pip install matplotlib torch diffusers
    ```

## Usage
1. Run the provided script in your Python environment.
2. Enter your desired text prompt when prompted.
3. The script will generate and display the corresponding image.

## Note
- Ensure you have a CUDA-enabled GPU for faster image generation.
- Adjust `num_inference_steps` and `guidance_scale` parameters for different image generation settings.
- For any issues or inquiries, please refer to the documentation of `diffusers` or the respective model documentation.

## Some Generated Examples

![image](https://github.com/Anshg07/Image_generator/assets/96684989/078c33a5-aa70-4f65-9641-d3d7a736c68a)
![download](https://github.com/Anshg07/Image_generator/assets/96684989/9fcfdc7d-af74-4183-9591-3809eb4038ae)
![download](https://github.com/Anshg07/Image_generator/assets/96684989/d52cabd8-b620-405a-a8a3-feb1684499b5)
