Cloud storage can be divided into different types depending on how the data needs to be stored and accessed. The three common types are **Block Storage, File Storage, and Object Storage**.

| **Storage Type**   | **Description**                                                                                       | **Primary Use Case**                                                                            | **Cloud Provider Example** |
| ------------------ | ----------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | -------------------------- |
| **Block Storage**  | Stores data in separate blocks and works similar to a disk that can be connected to a server.         | Commonly used for operating systems, databases, and applications that require fast data access. | AWS EBS                    |
| **File Storage**   | Organizes data into files and folders within a shared file system.                                    | Useful when multiple users or servers need to access and share the same files and folders.      | AWS EFS                    |
| **Object Storage** | Saves files as individual objects along with their metadata inside storage containers called buckets. | Best for photos, videos, documents, backups, and other types of large unstructured data.        | Amazon S3                  |

## Why Object Storage is Suitable

For the client's photo-sharing application, **Object Storage** would be a suitable choice because it is made for storing a large number of files, especially images and other media. It can handle many objects and can easily expand as more users upload photos. This makes it practical for an application that is expected to store and manage a growing collection of images.

