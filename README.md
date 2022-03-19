# nodenv
Nodeenv setup

Setting up a virtualenv with Node.js
The following steps will: create a virtualenv, named myenv, in the current directory; activate the virtualenv; and install npm inside the virtualenv using nodeenv:

python3 -m venv myenv          # For Python 2: python2 -m virtualenv myenv
source myenv/bin/activate
pip install nodeenv
nodeenv -p
