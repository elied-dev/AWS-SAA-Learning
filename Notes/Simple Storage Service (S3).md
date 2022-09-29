![S3-logo](https://fathomtech.io/blog/using-aws-s3-and-cloudfront-for-fast-static-web-sites/amazon-s3.png)
# Simple Storage Service (S3)

This is an **object based service**. 
Serverless storage in the cloud.

## Object-based storage
OBS is a data storage architecture that manages data as objects as opposed to other storage architectures such as **file systems** (manages data as a files and fire hierarchy) or **block storage** (manages data as blocks within sectors and tracks).

## Concepts
S3 provides **UNLIMITED STORAGE**.
We don't need to think about the underlying architecture => *serverless*
S3 console provides an interface to upload, access and manage the data.

### Objects
| Concept | Description |
| -- | -- |
| Key | Object name |
| Value | data itself (sequence of bytes) |
| Version ID | Object version |
| Metadata | Additionnal information attached to object |

We can store up to  **5TB** of data per object.

### Buckets
