Clone the repository:git clone https://github.com/impressai/quiz-bot
cd quiz-botSet up and run the bot:Using Docker:docker-compose build
docker-compose upWithout Docker:pip install -r requirements.txt
# Configure PostgreSQL and Redis as needed in `settings.py`
python manage.py runserverComplete the required functions in core/reply_factory.py:record_current_answer(): Validate and store user answers.get_next_question(): Present all quiz questions sequentially.generate_final_response(): Provide the quiz result with the final score.# GitHub-clone-
