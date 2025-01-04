# Dockerfile Bug: Missing Application Code

This repository demonstrates a common error in Dockerfiles: forgetting to copy the application code into the image.  The provided `Dockerfile` correctly installs dependencies, but fails to run because the main application file (`main.py`) is not present in the image.

The solution demonstrates the correct way to copy the application code and ensures the application runs successfully within the Docker container.