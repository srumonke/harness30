FROM python:3.10-slim

WORKDIR /app

# Copy the wheel from simple-python-ci/dist
COPY simple-python-ci/dist/*.whl /app/

# Install the wheel
RUN pip install *.whl

CMD ["python"]
