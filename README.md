django_sample
=============

Django sample project


After checkout you need to create your local settings and create a symbolic link so django will find them:

    cd django_sample
    cp settings/dev.py settings/settings_<MYNAME>.py
    # modify your setting accordingly
    ln -s settings/settings_<MYNAME>.py settings/local.py
