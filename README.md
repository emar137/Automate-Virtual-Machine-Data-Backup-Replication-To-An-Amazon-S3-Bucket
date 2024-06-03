## Automating Virtual Machine Backups & Replication To An Amazon S3 Bucket

## Task
*  Create a bash script that runs on a schedule to compress and backup critical data on a virtual machine (EC2 Instance) in AWS and  Automate the backup replication to an Amazon S3 Bucket
    ![image](https://github.com/emar137/Automate-Virtual-Machine-Data-Backup-Replication-To-An-Amazon-S3-Bucket/assets/84228720/313cca10-73f2-42bf-bef8-f49ad1a81ea4)
## Key Features:
* Backup Scheduling: Allow users to schedule backups at specific times or intervals (e.g., daily, weekly, or monthly)
* Backup Compression: Compress the backup files to save storage space using the tar command with gzip (tar -czf) or other compression methods.
* Logging: Create log files to record backup operations, including start time, end time, and any errors encountered during the backup.
* AWS Integration: Seamlessly integrate with the AWS Command Line  Interface (CLI) for secure and efficient uploads to Amazon S3.
  
