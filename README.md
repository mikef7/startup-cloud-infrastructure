# startup-cloud-infrastructure
Cloud Computing Internship Task
# Startup Cloud Infrastructure Design

## Cloud Provider
Amazon Web Services (AWS)

## Compute
Amazon EC2 will host the web application

## Storage
Amazon RDS for database  
Amazon S3 for file storage

## Networking
Elastic Load Balancer  
Amazon CloudFront CDN  
VPC for security

## Backup Strategy
Daily backups  
Automated snapshots  
Multi Availability Zone deployment

## Architecture

Users  
↓  
CloudFront  
↓  
Load Balancer  
↓  
EC2  
↓  
RDS  
↓  
S3
