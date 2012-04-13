# Setup

    git clone git://github.com/Psycojoker/UrLaB.git
    cd UrLaB
    virtualenv --no-site-packages --distribute ve
    source ve/bin/activate
    pip install -r requirements.txt
    python manage.py syncdb

To launch the dev server:

    python manage.py runserver

Then go to http://0.0.0.0:8000

# How to use the virtualenv in a nutshell

Virtualenv is like an ultra minimaliste vm (not really in fact) only for
python. When you create it you will only use the python packages located in it.
They will be installed from pypi (then cpan of python) using pip, like that
everyone will run the same version and this will avoid you the cost of
installing additionnal packages on your computer.

Enter in it

    source ve/bin/activate

Got out of it

    deactivate

Create one if you haven't followed the setup

    virtualenv --no-site-packages --distribute ve
