# Use a base Python image
FROM python:3.9

# Set working directory
WORKDIR /app

# Copy application files
COPY app /app

# Install Flask
RUN pip install flask

# Expose the application port
EXPOSE 5000

# Run the application
CMD ["python", "server.py"]
