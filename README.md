# instance_metadata_access
This code is attempting to access instance metadata from cloud providers AWS, GCP, and Azure. It does this by making HTTP GET requests to specific URL paths on the target IP address. If the request is successful (i.e. the status code is 200), it prints a message indicating that the metadata is available
