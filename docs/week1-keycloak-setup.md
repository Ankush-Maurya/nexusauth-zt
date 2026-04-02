# Week 1 – Identity Infrastructure Setup using Keycloak

## Objective

The objective of Week 1 was to deploy a centralized Identity Provider using Keycloak and configure identity infrastructure required for Zero Trust Architecture.

---

## Tools Used

Docker Desktop  
Keycloak  
Windows PowerShell  
Browser Admin Console  

---

## Environment Setup

Operating System:

Windows 11

Container Platform:

Docker Desktop

Identity Provider:

Keycloak

---

## Step 1 – Docker Installation

Docker Desktop installed successfully.

Verification command:

docker --version

Purpose:

Used to deploy Keycloak container.

---
## Step 2 – Keycloak Container Deployment

Keycloak container pulled using Docker.

Command used:

docker pull quay.io/keycloak/keycloak

Container started using:

docker run -p 8080:8080 quay.io/keycloak/keycloak start-dev

Keycloak server available at:

http://localhost:8080

---

## Step 3 – Admin Console Login

Temporary admin user created.

Username:

admin

Password:

admin

Admin console accessed successfully.

---
