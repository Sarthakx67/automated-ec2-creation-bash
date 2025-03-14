# AWS EC2 Instance Launcher

This script automates the creation of an Amazon EC2 instance using the AWS CLI. It's designed for quick deployments and learning purposes.

## Features

* Launches an EC2 instance with configurable parameters.
* Waits for the instance to reach the 'running' state.
* Simple and easy to understand.

## Usage

1.  **Clone the repository:**

    ```bash
    git clone [repository-url]
    cd ec2-launcher
    ```

2.  **Make the script executable:**

    ```bash
    chmod +x launch-instance.sh
    ```

3.  **Configure the script:**

    Edit `launch-instance.sh` and set the following variables:

    * `AMI_ID`: The Amazon Machine Image ID.
    * `INSTANCE_TYPE`: The EC2 instance type (e.g., `t2.micro`).
    * `SECURITY_GROUP_ID`: The security group ID.
    * `KEY_NAME`: The key pair name.

4.  **Run the script:**

    ```bash
    ./launch-instance.sh
    ```

## Prerequisites

* AWS CLI configured with appropriate credentials.
* An AWS account with permissions to launch EC2 instances.

## Example Output
