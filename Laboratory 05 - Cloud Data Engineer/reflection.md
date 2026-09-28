## 1. Why is object storage better suited for storing millions of photos compared to a traditional block storage hard drive?

This laboratory activity helped me understand why **object storage** is a good option for applications that need to store a huge number of files, especially photos. It is designed to handle unstructured data and can store millions of files efficiently. Using buckets and objects also makes it easier to organize and manage the stored files.

## 2. How did using Docker make it easier to deploy the MinIO storage server?

Docker made setting up MinIO much simpler for me. Instead of going through a manual installation process, I was able to start MinIO inside a Docker container using a single command. Through this activity, I also learned how **port mapping** and **environment variables** are used to configure a Docker container.

## 3. What is a "bucket" in the context of cloud storage?

A **bucket** can be thought of as a container used to store objects in an object storage system. For this activity, I created a bucket named `client-photos`, where I stored the sample file that I uploaded. This gave me a better understanding of how files are organized in object storage.

## 4. How do you think large enterprise companies ensure their object storage data is not lost if the physical server crashes?

Large companies can protect their data by creating backups and keeping multiple copies of important files. They can also use **data replication and redundant storage** so that when one physical server encounters a problem, another copy of the data can still be accessed or restored.

## 5. How is your confidence in navigating the Linux command line growing?

My confidence in using the **Linux command line** has improved through this activity. At first, the Docker commands seemed complicated because they contained several options and configurations. After practicing commands like `docker run` and `docker ps`, I became more familiar with using the terminal. I also learned that if a Docker image does not work, I should first check the output and available images rather than assuming that Docker itself has a problem.

