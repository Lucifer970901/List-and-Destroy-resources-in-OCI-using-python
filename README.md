# List-and-Destroy-resources-in-OCI-using-python
this script lists and destroys the resources of particular set of users when needed mass deletion


Whenever we need to destroy resources of the users who have left the organization and the resources are just piling up, destroying them can be a very tedious task. this python script will help in listing and destroying those resources.

The scripts is designed to read the list of users for whom the resources must be destroyed.
once the list is ready, this list is read by the script which list the resources of that users which must be destroyed also destroys the resources of those set of users.

it uses following packages
openpyxl  - library to read and write to excel
oci.      - library for using oci api and manage the resources
pandas    -  BSD based library to handle data structures and analysis.
