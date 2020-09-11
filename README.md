# GCPpractice-project
GADS learning phase 2 practice project

# gads-2020-practice-project

## QwikLabs Completed

<details>
  <!-- The complete lab title goes here 👇🏾-->
  <summary>Lab 1: How to create Virtual Machines</summary>
  <!-- Provide path to the screenshot here. Example 👇🏾-->
  <img src="screenshots/lab_creating_virtual_machines.png">
</details>

## Translation code

```
gcloud compute instances create gcelab2 --machine-type n1-standard-2 --zone us-central1-c
```


<details>
  <!-- The complete lab title goes here 👇🏾-->
  <summary>Lab 2: Cloud Storage</summary>
  <!-- Provide path to the screenshot here. Example 👇🏾-->
  <img src="screenshots/Cloud_Storage.png">
</details>

## Translation code

```
Create a bucket
Run the gsutil mb command and replace with a unique name to create a bucket:
gsutil mb gs://YOUR-BUCKET-NAME/

Now upload an object into a bucket.
Use the gsutil cp command to upload the image from the location where you saved it to the bucket you created:
gsutil cp image.jpg gs://YOUR-BUCKET-NAME

List contents of a bucket or folder
Use the gsutil ls command to list the contents of the bucket:
gsutil ls gs://YOUR-BUCKET-NAME

List details for an object
Use the gsutil ls command, with the -l flag to get some details about the image file you uploaded to your bucket:
gsutil ls -l gs://YOUR-BUCKET-NAME/image.jpg

Make your object publicly accessible
Use the gsutil acl ch command to grant all users read permission for the object stored in your bucket:
gsutil acl ch -u AllUsers:R gs://YOUR-BUCKET-NAME/image.jpg

Remove public access
To remove this permission, use the command:
gsutil acl ch -d AllUsers gs://YOUR-BUCKET-NAME/image.jpg

Delete objects
Use the gsutil rm command to delete an object - the image file in your bucket:
gsutil rm gs://YOUR-BUCKET-NAME/image.jpg

```

