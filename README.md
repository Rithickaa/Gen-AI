Emoji to Story Generator

This Python code turns a sequence of emojis into a fun short story using the GPT-2 model from Hugging Face. It installs the needed library, loads the GPT-2 model for text generation, and sets a seed so the output stays the same each time.
The emoji_to_story function takes emojis, creates a story prompt starting with “Once upon a time,” and uses the model to generate a creative story. It uses settings like temperature and top-k to make the story interesting and not too long.

Finally, the prompt is removed from the result, and the code prints both the emoji input and the story in a clear format.


Image to text generator
This Python code generates image captions using a pre-trained Vision-Encoder-Decoder model (nlpconnect/vit-gpt2-image-captioning) from Hugging Face. It loads the model, processor, and tokenizer, then defines a generate_caption function that processes an image, generates a short caption, and displays the image with its caption. The code fetches an online image, saves it, and passes it to the function to demonstrate automatic image-to-text generation.
