## How to Create an Amazon S3 Bucket ##

An Amazon S3 bucket is a cloud storage resource available in Amazon Web Service. Buckets are used to store objects. They work similar to folders that hold files or pictures, but are not limited to just the two. This guide will help you create and configure an Amazon S3 Bucket.

1. Sign into your AWS account, and navigate to the AWS Management Console.

 > **Note**
 >
 > An AWS Account is required to creating an Amazon S3 bucket. If you do not have an AWS Account, please create an account at [AWS Free Tier Sign-up](https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc) and selecting **Create a Free Account**

2. Navigate to the [Amazon S3 console](https://console.aws.amazon.com/s3/).

3. Choose the **Create Bucket** action.

4. You will be prompted with a setup wizard, asking you to enter a **Bucket Name** and **Region**.

   The bucket name must:

   - Have a unique name across all Amazon AWS S3 accounts (not just your own account).
   - Start with a lowercase alphanumeric letter.
   - Between 3 and 63 characters long.
   - Have no uppercase characters.
   - Have a name that is DNS-compliant (contains no spaces and uses '-' instead of '.').
   <br />

   > **Warning**
   >
   > You can't rename a bucket after it's creation. For more information, please see [Bucket restrictions and limitations](https://docs.aws.amazon.com/AmazonS3/latest/userguide/BucketRestrictions.html#bucketnamingrules).

   The Region is the AWS Region where you want your bucket to reside.

   > **Warning**
   >
   > You should select a Region located close to your location. This will help to ensure minimal latency and costs. For more information, please see [Managing AWS Regions](https://docs.aws.amazon.com/general/latest/gr/rande-manage.html).

5. Next, the setup wizard will ask for **Configuration Options**.

   - **Versioning** are used to keep a history of an object (created, updated, deleted, etc).
   - **Server access logs** provides detailed log records for requests made to your bucket.
   - **Tags** use a Key, Value pair to help allocate costs assigned to your bucket.
   - **Object-level logging** provides audit logging for objects in AWS CloudTrail at an additional cost. (For more information on AWS CloudTrail, please see [What Is AWS CloudTrail?](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-user-guide.html))
   - **Default Encryption** will automatically encrypt all objects stored in your bucket.

 For more information on Configuration Options, please see [Viewing the properties for an S3 bucket](https://docs.aws.amazon.com/AmazonS3/latest/userguide/view-bucket-properties.html).

6. After Configuration Settings are the **Permission settings** for your bucket. By default your bucket is set to private, these permission settings are where you can provide public access to your bucket. It is recommend that you leave all settings enabled.

7. **Review** your buckets settings and select **Create bucket**.

For further information regarding S3 bucket creation, please see [Creating, configuring, and working with Amazon S3 buckets](https://docs.aws.amazon.com/AmazonS3/latest/userguide/creating-buckets-s3.html).
