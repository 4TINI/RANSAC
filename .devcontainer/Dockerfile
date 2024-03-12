FROM python:3.8

# Copy requirements.txt from the parent directory to the container
COPY ../requirements.txt /tmp/

# Install Python dependencies from requirements.txt
RUN pip install --no-cache-dir -r /tmp/requirements.txt

# Clean up
RUN rm /tmp/requirements.txt