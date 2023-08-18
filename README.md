# AzureML-Udemy
Machine Learning Model's development and deploy on AzureML

## Azure Storage

### Types:
- **Azure Disks:** Similar to physical discs
  - Disk size and type
- **Azure Blobs:** Object storage solution
  - Massive unstructured data such as texts and images
  - Uses containers of data (each container can store a type of data)
  - Can be accessed through HTTP protocol
- **Azure Files:** File share as a drive
  - Shared between machines
  - SMB protocol
- **Azure Queues:** Storing and retrieving messages
- **Azure Tables:** Used for structured but Non-Relational data
  - Uses the name-value for storing and retrieving data
  - Higher scalability and flexibility

**Obs:** On Azure you create one storage account and then create the type of storage you want. You can
have multiples types of storage inside one Storage Account

For managing this resources you can go to Storage Explorer and see all the Blob Containers, File Shares,
Queues and Tables inside it.

### Access Tiers
- **Hot:** Frequently accessed data
- **Cool:** Less frequently accessed data
- **Archive:** rarely accessed and stored offline

### Redundancy
- **Locally Redundant:** 3 copies in the same physical location
- **Zone Redundant:** Copies in different zones
- **Geo Redundant:** 3 copies in single physical location and another copy in Secondary region
- **Geo-Zone Redundant:** 3 copies in 3 zones in Primary region and another copy on a Secondary Region

### Performance Tiers
- **Standard**
- **Premium**

**Other Features**
You can manage acces control of the storage account
Can be managed through Azure Storage Explorer on a local machine



