FROM langflowai/langflow:1.0.19

USER root
WORKDIR /app

# Install graphrag
RUN pip install graphrag

CMD ["python", "-m", "langflow", "run", "--host", "0.0.0.0", "--port", "7860"]