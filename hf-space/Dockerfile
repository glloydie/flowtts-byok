FROM python:3.10-slim

WORKDIR /app

RUN pip install --no-cache-dir \
    gradio==3.50.2 \
    huggingface_hub==0.20.3 \
    tencentcloud-sdk-python>=3.0.1200

COPY app.py .

EXPOSE 7860

CMD ["python", "app.py"]
