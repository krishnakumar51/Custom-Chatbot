# Custom Chatbot 

This model is a custom chatbot designed to interact with content extracted from a given website URL. It utilizes various natural language processing techniques to provide conversational responses based on the content available on the specified website.

## Features

- Extraction of textual content from the provided website URL.
- Chunking of the text into manageable segments for processing.
- Embedding of text chunks using Hugging Face embeddings.
- Indexing of embedded text chunks for efficient retrieval.
- Utilization of a language model for text generation and response generation.
- Integration of a retrieval-based question answering system for interactive queries.

## Dependencies

- [langchain](https://github.com/username/langchain): A library for natural language processing tasks.
- [transformers](https://github.com/huggingface/transformers): Library for state-of-the-art natural language processing models.
- [Hugging Face Hub](https://huggingface.co/huggingface_hub): Hub for sharing, discovering, and managing pretrained models and datasets.
- [Pinecone](https://www.pinecone.io/): A vector database for building scalable machine learning applications.
- [Accelerate](https://github.com/huggingface/accelerate): Library for efficient training and inference with PyTorch.
- [BitsAndBytes](https://github.com/huggingface/bitsandbytes): A library for quantization-aware training and deployment.

## Credits

This project makes use of the Pegasus model from the Hugging Face `transformers` library, developed by Google Research.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
