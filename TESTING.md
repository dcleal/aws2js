## Requirements

 * AWS_ACCEESS_KEY_ID and AWS_SECRET_ACCESS_KEY environment variables which target to proper accessKeyId and secretAccessKey credentials. These are used for all the tests, therefore if the credentials are from a IAM user, they must be permissive enough in order to succesfully run all the tests.
 * AWS2JS_S3_BUCKET environment variable which indicates the S3 bucket where the tests should upload their contents.
 * The following *nix utils: dd, md5sum, cut with the existence of the /dev/urandom for the putFileMultipart test.
 * The tests directory must be writable by the system user that runs the tests.
