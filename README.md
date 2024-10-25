import openai

# Set up the API key
openai.api_key = 'your_api_key_here'

# Define a prompt for GPT-4
prompt = "Explain the theory of relativity in simple terms."

# Use the OpenAI API to generate a response
response = openai.ChatCompletion.create(
    model="gpt-4",
    messages=[
        {"role": "system", "content": "You are a helpful assistant."},
        {"role": "user", "content": prompt}
    ]
)

# Print the response
print(response['choices'][0]['message']['content'])
