
### 0.5.0 
- (Feature) New example based on datavault modelling.
- (Feature) Validations for metadata.
- (Feature) Creation of schemas and databases if needed.
- (Feature) Add new columns if needed.
- (Feature) Select process to execute with dependencies if needed.
- (Feature) Configuration hashes for Datavault module.
- (Feature) Execution with threads.
- (Feature) Primary Key on create table.
- (Feature) Delete, Update, Merge strategies.
- (Bugfix) Fixed some small bugs.

### 0.4.4.2
- *(Bugfix)* Execute any commands without any config file.
- *(Bugfix)* Errors on NULL or None values on metadata entry.
- *(Bugfix)* Errors on column detection on complex mappings.
- *(Bugfix)* 'Files' command not using the correct target path connection.
- *(Bugfix)* Error on historical metadata when delete some entities in special casuistics.
- *(Feature)* Added 'if is null' logic on all hashes.
- *(Feature)* The user can change column names on Datavault Engine - Mappings.
- *(Feature)* Added duplicate control on Datavault Engine - Satellites.

### 0.4.4.1
- *(Feature)* **Datavault** module to speed up the creation of a Datavault Model. New metadata entry was added.
- *(Feature)* File loader to upload csv files to the data database.
- *(Feature)* Added compatibility to PostgreSQL and MySQL for metadata and data databases.
- *(Feature)* Added compatibility to Linux OS.

### 0.4.3.1
- *(Bugfix)* on installation with some packages.