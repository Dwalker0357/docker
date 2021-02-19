# Use Python 3.6 or later as a base image
from python:3.6
# Copy contents into image
copy . .
# Install pip dependencies from requirements
run pip3 install -r requirements.txt
# Set YOUR_NAME environment variable

# Expose the correct port
expose 5500
# Create an entrypoint
entrypoint ["python3", "app.py"]
