# Storing Django Static and Media Files on Amazon S3

## Want to learn how to build this?

Check out the [post]().

## Want to use this project?

1. Fork/Clone

1. Create an IAM group with the `AmazonS3FullAccess` policy, create an IAM user and add the user to the group, create an S3 bucket. Update the following environment variables on the *docker-compose.yml* file:

    - AWS_ACCESS_KEY_ID=UPDATE_ME
    - AWS_SECRET_ACCESS_KEY=UPDATE_ME
    - AWS_STORAGE_BUCKET_NAME=UPDATE_ME

1. Build the images and run the containers:

    ```sh
    $ docker-compose up -d --build
    ```

1. Test it out at [http://localhost:1337](http://localhost:1337)
