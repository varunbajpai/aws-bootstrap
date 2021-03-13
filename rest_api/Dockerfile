FROM tiangolo/uvicorn-gunicorn-fastapi:python3.7

COPY ./ /app


CMD ["uvicorn", "service:app", "--host", "0.0.0.0", "--port", "8000"]
