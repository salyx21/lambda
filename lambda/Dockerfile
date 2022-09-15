FROM public.ecr.aws/lambda/python:1.1.2
COPY requirements.txt ${LAMBDA_TASK_ROOT}
RUN pip3 install --no-cache-dir -r requirement.txt
COPY aws-lambda-url.py ${LAMBDA_TASK_ROOT}