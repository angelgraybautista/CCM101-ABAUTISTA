# Reflection — Cloud Data Engineer

Object Storage is far better suited for millions of photos than block storage because photos are unstructured, unique files that benefit from being stored independently rather than in fixed disk blocks. Object storage assigns each photo a unique ID and metadata, making it instantly accessible over the web and allowing the system to grow without limit—something traditional block disks cannot match.

Docker made deploying MinIO extremely fast. Instead of installing dependencies, configuring services, and managing versions manually, one command pulled the image and started the server with all settings preconfigured. This eliminated “it works on my machine” issues and ensured consistency.

In cloud storage, a bucket is a top‑level container—like a drive or root folder—where objects are stored. Unlike folders, buckets have globally unique names and can be set with permissions and lifecycle rules. They are the starting point for organising data in S3‑compatible systems.

Enterprises protect against data loss through replication—copying objects to multiple servers, zones, or even regions. They also use versioning to keep old copies and backups for disaster recovery. This way, no single physical failure can destroy the data.

I feel much more confident with Linux commands now. I’m comfortable navigating directories, checking running containers, and understanding what each flag in a command does. It feels less like memorising syntax and more like controlling the system.
