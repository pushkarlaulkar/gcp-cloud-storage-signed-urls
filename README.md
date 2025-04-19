1. Create a bucket, upload an object
2. Create a service account with storage object viewer role
3. Grant a specific user access to this service account and Service Account Token Creator role
4. Run ‘ gcloud storage sign-url gs://bucket_name/object_name --duration=1m --impersonate-service-account=service_account_email --region=bucket_region ’
