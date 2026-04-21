# Module 05: Python Programming - Study Notes

## Overview
This section covers the fundamentals of Python programming with a focus on automation and cloud integration using the AWS SDK (Boto3).

## Key Concepts
* **Data Types:** Strings, Integers, Floats, Booleans, Lists, and Dictionaries.
* **Control Flow:** If/Else statements, For loops, and While loops.
* **Functions:** Defining reusable blocks of code.
* **Error Handling:** Try/Except blocks to manage exceptions.

## AWS Integration (Boto3)
To interact with AWS services using Python, we use the **Boto3** library.
- **Client:** Low-level service access.
- **Resource:** Higher-level, object-oriented service access.

### Basic Script Example (List S3 Buckets):
```python
import boto3

# Initialize an S3 resource
s3 = boto3.resource('s3')

# Print all bucket names
for bucket in s3.buckets.all():
    print(bucket.name)
```