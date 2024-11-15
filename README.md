
# Pixel Puranas: History Revived

This web application generates historical content based on user prompts, including images, PDFs, audio narrations, and simple animation videos.

## Features

- Image generation using Hugging Face API
- PDF generation with historical content
- Audio narration of generated content
- Simple animation video creation
- Contact form with feedback stored in MongoDB
- Simple chatbot for user interactions

## Setup

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/pixel-puranas.git
   cd pixel-puranas
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   - `HUGGINGFACE_API_TOKEN`: Your Hugging Face API token
   - `MONGODB_URI`: Your MongoDB connection string (default: "mongodb://localhost:27017/")

4. Run the application:
   ```
   python app.py
   ```

5. Open a web browser and navigate to `http://localhost:5000` to use the application.

## Project Structure

- `app.py`: Main Flask application
- `pdf_generation.py`: PDF generation functionality
- `audio_generation.py`: Audio narration generation
- `video_creation.py`: Simple animation video creation
- `db_operations.py`: MongoDB operations for storing feedback
- `chatbot.py`: Simple rule-based chatbot logic
- `templates/`: HTML templates for the web pages
- `static/`: Static files (CSS, generated content)

## Contributing

Feel free to submit issues and pull requests to improve the project.

## License

This project is licensed under the MIT License.
