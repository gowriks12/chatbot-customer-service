# chatbot-customer-service
Customer Service chatbot implementation

Using Hugging face, fine tuned flan-t5-large model with "bitext/Bitext-customer-support-llm-chatbot-training-dataset" that includes customer service questions and responses. The resulting chatbot functions as a customer service chatbot that can reply to customer or user queries.

The model is loaded and fine tuned using the LORA a type PEFT method to fine tune the parameters of an LLM without changing the base model weights. The theory and the concepts of the tasks performed in this project are discussed in the coursera course Generative AI with LLMs [https://www.deeplearning.ai/courses/generative-ai-with-llms/]




