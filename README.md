This document provides details on how to set up and use the Jenkins pipeline for automating the build, test, and deployment processes of a Python web application. The pipeline is configured to trigger on changes to the main branch, run tests, and deploy the application if tests pass. It also includes email notifications for build status.

Prerequisites
Before setting up the Jenkins pipeline, ensure the following:

Jenkins Installation:

Jenkins should be installed on a virtual machine or use a cloud-based Jenkins service.
Required Jenkins plugins:
Git Plugin
Pipeline Plugin
Email Extension Plugin
Python Environment:

Python 3.x installed on the Jenkins server.
Pip for managing Python packages.
Source Code Repository:

A GitHub repository with the Python web application source code.
SMTP Server:

Access to an SMTP server for sending email notifications. For Gmail, use an App Password if 2FA is enabled.
Repository Setup
Fork the Repository:

Fork the sample Python web application repository from this link.
Clone the Repository:

Clone your forked repository to your Jenkins server
