
# AWS S3 Controller API

This API provides endpoints for managing files and buckets in AWS S3 using a Spring Boot application.

## Endpoints

### Show all files

- **Method:** GET
- **URL:** http://localhost:8081/s3/showFiles

### Upload file

- **Method:** POST
- **URL:** http://localhost:8081/s3/upload
- **Form Data:** `file`

### Download file

- **Method:** GET
- **URL:** http://localhost:8081/s3/download?fileName={fileName}

### Delete file

- **Method:** DELETE
- **URL:** http://localhost:8081/s3/delete?fileName={fileName}

### Delete all files

- **Method:** DELETE
- **URL:** http://localhost:8081/s3/deleteAll

### Copy file

- **Method:** PUT
- **URL:** http://localhost:8081/s3/copy?fileName={fileName}

### Show all buckets

- **Method:** GET
- **URL:** http://localhost:8081/s3/showAllBuckets

### Create bucket

- **Method:** POST
- **URL:** http://localhost:8081/s3/createBucket

### Delete bucket

- **Method:** DELETE
- **URL:** http://localhost:8081/s3/deleteBucket

## Getting Started

1. **Prerequisites:**
   - Java 17
   - Maven
   - AWS S3 Credentials

2. **Clone the repository:**
   ```bash
   git clone https://github.com/PBxYash/AwsS3.git)https://github.com/PBxYash/AwsS3.git
   cd aws-s3-controller-api
