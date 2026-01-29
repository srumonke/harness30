FROM python:3.10-slim

WORKDIR /app

# Copy wheel
COPY dist/*.whl /app/

# Install the wheel
RUN pip install *.whl

CMD ["python"]
