# Anscible_learning

# install python virtualenv (if you do not have it already)
pip3 install --user virtualenv

# create a python virtual environment called env
python3 -m virtualenv venv

source venv/bin/activate



ansible
ansible-core
google
google-api-core
google-api-python-client
google-auth
google-auth-httplib2
google-cloud-kms
googleapis-common-protos
httplib2
requests
EOF

pip3 install -r requirements.txt

# verify ansible installation 
ansible --version
ansible [core 2.14.5]
  config file = None
  configured module search path = ['/Users/daniel/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /private/tmp/project1/venv/lib/python3.11/site-packages/ansible
  ansible collection location = /Users/daniel/.ansible/collections:/usr/share/ansible/collections
  executable location = ./venv/bin/ansible
  python version = 3.11.2 (main, Feb 16 2023, 03:07:35) [Clang 14.0.0 (clang-1400.0.29.202)] (/private/tmp/project1/venv/bin/python)
  jinja version = 3.1.2
  libyaml = True
