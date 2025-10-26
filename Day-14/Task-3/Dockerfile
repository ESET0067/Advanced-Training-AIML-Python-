# Use an official Python image
FROM python:3.9-slim

# Set working directory
WORKDIR /app


# Copy files
COPY . .

# Install Python packages
RUN pip install --no-cache-dir -r requirment.txt

# Run the script
CMD ["python", "main.py"]
