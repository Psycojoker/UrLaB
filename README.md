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
