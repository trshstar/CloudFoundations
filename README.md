# CloudFoundations

This cloud infrastructure project implements a professional-grade web hosting solution using AWS's core services. The architecture is designed to provide secure access management, efficient content delivery, and isolated networking while maintaining high availability and performance.

## Diagram of Amazon Web Services (AWS) Technologies:

!["CloudFoundations Diagram"](https://github.com/trshstar/CloudFoundations/blob/main/diagram.png)



## Key Components:

<ol>
    <li>
        Identity and Access Management (IAM)
        <ul>
            <li>Implements three-tier access control system</li>
            <li>Admin, medium-access, and least-access user groups</li>
            <li>Follows the principle of least privilege</li>
            <li>Manages service-level permissions across the infrastructure</li>
        </ul>
    </li>
    <li>
        Virtual Private Cloud (VPC)
        <ul>
            <li>Custom network infrastructure with public subnet</li>
            <li>Configured with Internet Gateway for external connectivity</li>
            <li>Implemented security groups for access control</li>
            <li>Route tables for network traffic management</li>
        </ul>
    </li>
    <li>
        Elastic Compute Cloud (EC2)
        <ul>
            <li>Hosts Apache web server</li>
            <li>Deployed in public subnet</li>
            <li>Configured for web content hosting</li>
            <li>Secured through VPC networking</li>
        </ul>
    </li>
    <li>
        CloudFront
        <ul>
            <li>Content Delivery Network implementation</li>
            <li>Optimizes content delivery speed</li>
            <li>Reduces load on origin servers</li>
            <li>Integrates with S3 for asset delivery</li>
        </ul>
    </li>
    <li>
        Simple Storage Service (S3)
        <ul>
            <li>Stores static assets and images</li>
            <li>Integrated with CloudFront for content delivery</li>
            <li>Secured through IAM permissions</li>
            <li>Provides scalable storage solution</li>
        </ul>
    </li>
</ol>

## Technical Implementation

<ol>
    <li>Multi-tier security architecture</li>
    <li>Scalable web hosting infrastructure</li>
    <li>Optimized content delivery system</li>
    <li>Isolated network environment</li>
    <li>Role-based access control</li>
</ol>
