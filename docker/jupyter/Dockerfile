# Dockerfile
FROM tensorflow/tensorflow:latest-gpu

# Install JupyterLab
RUN pip install jupyterlab

# Install some libs
RUN pip install keras-cv pycocotools tensorflow_datasets pandas
RUN pip install --upgrade tensorflow

# Expose the port for JupyterLab
EXPOSE 8888

# Set working directory
WORKDIR /tf/notebooks

# Run JupyterLab without a browser and with no authentication
CMD ["jupyter", "lab", "--ip=0.0.0.0", "--no-browser", "--allow-root", "--NotebookApp.token=''", "--NotebookApp.password=''"]