# CloudFoundations

This cloud infrastructure project implements a professional-grade web hosting solution using AWS's core services. The architecture is designed to provide secure access management, efficient content delivery, and isolated networking while maintaining high availability and performance.

Key Components:

    Identity and Access Management (IAM)
        Implements three-tier access control system
        Admin, medium-access, and least-access user groups
        Follows the principle of least privilege
        Manages service-level permissions across the infrastructure

    Virtual Private Cloud (VPC)
        Custom network infrastructure with public subnet
        Configured with Internet Gateway for external connectivity
        Implemented security groups for access control
        Route tables for network traffic management

    Elastic Compute Cloud (EC2)
        Hosts Apache web server
        Deployed in public subnet
        Configured for web content hosting
        Secured through VPC networking

    CloudFront
        Content Delivery Network implementation
        Optimizes content delivery speed
        Reduces load on origin servers
        Integrates with S3 for asset delivery

    Simple Storage Service (S3)
        Stores static assets and images
        Integrated with CloudFront for content delivery
        Secured through IAM permissions
        Provides scalable storage solution

Technical Implementation

    Multi-tier security architecture
    Scalable web hosting infrastructure
    Optimized content delivery system
    Isolated network environment
    Role-based access control

