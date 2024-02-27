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
