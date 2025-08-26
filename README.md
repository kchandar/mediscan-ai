# mediscan-ai

Build a system that allows healthcare providers (clinics/hospitals) to upload patient reports (PDFs/images) to an S3 bucket. The system then:
Extracts and summarizes the medical information using Generative AI.
Stores and serves that summary via a REST API.
Sends asynchronous notifications (e.g. to clinicians or patients) when summaries are ready using SQS/Kafka.
Incorporates IAM, CloudWatch, and Guardrails to ensure the system is secure, monitored, and reliable.
