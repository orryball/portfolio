## How to Delete an Amazon S3 Bucket ##

This guide will help you delete an Amazon S3 Bucket using the AWS Management Console. If you are not using the AWS Management Console to delete a bucket, note that a bucket must be emptied before being deleted. For more information on emptying a bucket, please see [How do I empty an S3 bucket?](https://docs.aws.amazon.com/AmazonS3/latest/user-guide-retired/empty-bucket.html)

 > **Warning**
 >
 > There are several considerations to keep in mind when deleting a bucket.
 > - Deleting a bucket will make the unique name available for others to use.
 > - Deleting a bucket that contains objects will be permanently delete all of those objects.
 > - Deleting a bucket that has versioning enabled will permanently delete all versions of each object in the bucket.


 1. Sign into your AWS account, and navigate to the AWS Management Console.

 2. Navigate to the [Amazon S3 console](https://console.aws.amazon.com/s3/).

 3. A list of all your Buckets is displayed. Each bucket will have a select box next to them. Select bucket that you want to delete, and then choose the **Delete** action located at the top, righthand side of the console page.

 4. You will be prompted with a confirmation wizard for deleting a bucket, asking you to enter the name of the bucket you want to delete. Enter the bucket's name in the text field and choose **Confirm**.
