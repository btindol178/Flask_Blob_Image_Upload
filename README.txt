Photos App
################################################
Git repository of project built in this tutorial: https://tomlogs.github.io/build-a-photos-application-with-azure-blob-storage
#https://www.youtube.com/watch?v=wToHU8Hts9c

# Go to storage and create container
# Get keys
# Set enviornment variable like below:
    - Get azure connection string then set it by doing set AZURE_STORAGE_CONNECTION_STRING="connectionstring"
    - set AZURE_STORAGE_CONNECTION_STRING=DefaultEndpointsProtocol=https;AccountName=blobpythontestoutzzz;AccountKey=d9nf53ta08wHkK1YQE1wV6kzNx6cjT4hIexPfppDH9HE3JAZO02rWgHFBZABO3yJxV2hZ/hA6bd9I7F+3oNF5Q==;EndpointSuffix=core.windows.net

# Give flask app access to azure storage account to render picture in app
    - go to photos container then change access level to Blobs  ((this makes photo publicly available ))
