# Overview

- cookbook name :  ``user_mngt``
- apply : ``chef-client --local-mode --runlist 'recipe[user_mngt]'``
- inspect data bag data :   ``chef-client --local-mode --runlist 'recipe[user_mngt]'`` 
- ``depends`` none 


# Repository Directories

- `cookbooks/` - Cookbooks 
- `data_bags/` - Store user and ssh key data

# TODO

- ``encrypt`` all data_bag data
- ``unit test`` with chefspec

