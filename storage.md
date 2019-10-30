# Google Storage Options

*   Diiferent Applications and workloads require different types of storage options.
*   GCP have different types of storage options to meet our need for
    *   Structure
    *   Unstructured
    *   Transactional
    *   Relational Data
*   Core Storage Options on GCP
    *   Cloud Storage
    *   Cloud Data Store
    *   Cloud Spanner
    *   Cloud SQL
    *   Google Big Table

## Cloud Storage
*   It is binary large object storage
*   High Performance, Internet Scale
*   Simple Administration Does not require capacity management.
*   Its not the same as file storage in which you manage your data as a hierarchy of folders, Its not the same as block storage in which your OS manages your data as chunks of Disk.
*   Object Storage means you save your storage here and keep the arbitary bunch of bytes and the storage will give you a unique key for all your files stored.
*   These unique keys are in form of URL which means they can work easily with Web platforms.
*   Cloud Storage is a fully managed scalable servers which means you dont need to provision capacity anytime its autoscallable.
*   Cloud Storage Applications
    *   Serving Website Contents
    *   Storing data for Archive and Disaster recovery
    *   Distributing your users via Direct donwload links
*   Note its not a file system they are just files, You can say files but it is not a file system you cannot use Cloud Storage for your Linux Root Directory.
*   Cloud Storage encrypts data on server side before it is written on the disks.
*   And data is Transfered over HTTPS

### Cloud Storage Buckets

*  In order to store data on Cloud Storage you need to create a bucket, note the bucket name should be globally unique and you choose a default storage class for that.
*   Pick a location which minimize the latency by choosing nearby Zones.

### Access Layers of Cloud Storage
*   There are several ways to control access to your objects and buckets.
*   Cloud IAM is suffiicient for most of the purposes, roles of a project is inherited to the bucket by default and you can manually configure them.
*   For more finer control you can use ACL Access Control Lists that offer finer control.
*   ACL define who has access to buckets and objects and as wekk as what level of access they have, each ACL consist of 2 piecies of information a scope which defines who can perform the specified actions. For Example
*   A specific user or group of users with permissions which defines what actions can be performed example read and write.

### Mutability and Versioning
* Cloud storage are immutable You can turn on onject versioning on Cloud storage, if you do cloud storage keeps a history of modifications.
* If you do, Cloud Storage keeps a history of modifications. That is, it overrides or deletes all of the objects in the bucket. 
* You can list the archived versions of an object, restore an object to an older state or permanently delete a version as needed. 
* If you don't turn on object versioning, new always overrides old. 
* Versioning sounds good but what about junk accumulating? Cloud Storage also offers lifecycle management policies. 
*   For example, you could tell Cloud Storage to delete objects older than 365 days. Or you could tell it to delete objects created before January 1, 2013 or keep only the three most recent versions of each object in a bucket that has versioning enabled.




