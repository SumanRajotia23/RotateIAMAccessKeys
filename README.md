AWS IAM Key Rotation
This set of shell scripts will set up an auto-rotation function that will automatically rotate your AWS IAM User Access Keys every 07 days. At 07 days it will then disable the old Access Keys and create new Access key and secret key. It will srore the new access key and secret key in a csv format in the artifact tab under the same run of Codecatalyst.
