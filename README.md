# cloud-custodian
cloud custodian


# links
https://cloudcustodian.io/
https://github.com/cloud-custodian/cloud-custodian

# installation
virtualenv custodian
source custodian/bin/activate
pip install c7n

# dry run
custodian run --dryrun -s out policy_example2.yml
