# Ansible OpsSchool Session

# docker Folder:

SET UP THE REPOSITORY
- Install the required packages and update the package cache (steps 1 and 2)
- Add docker’s official GPG key and Verify the key with the finger print (steps 3)
- Add the repository (steps 4)

INSTALL DOCKER ENGINE - COMMUNITY
- Install the docker engine and update the package cache (steps 1 and 2)
- Restart the docker service only if the docker engine package gets updates
- Add ubuntu user to the docker group as in: sudo usermod -aG docker your-user


# ansible_docker_role Folder:

Using the playbook to install docker and converting it to an ansible role
Using conditions to make the role generic – the role install docker on either ubuntu or on redhat distributions

