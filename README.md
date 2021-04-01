# tree_generator

Install the requirements:

    pip install walkdir

    python tree_gen.py.py -h
    usage: tree_gen.py.py [-h] [-d MAXDEPTH] [-H] [-S] path

    positional arguments:
      path                  Root directory of the tree

    optional arguments:
      -h, --help            show this help message and exit
      -d MAXDEPTH, --maxDepth MAXDEPTH
                            Max depth for the tree expansion
      -H, --includeHidden   Include hidden files
      -S, --includeSystem   Include system files
      
      
Output :-


          gs34
            |-- manage.py
            |-- db.sqlite3
            |-- gs34
            |   |-- wsgi.py
            |   |-- __init__.py
            |   |-- urls.py
            |   |-- settings.py
            |   |-- asgi.py
            |   '-- __pycache__
            |       |-- settings.cpython-36.pyc
            |       |-- wsgi.cpython-36.pyc
            |       |-- __init__.cpython-36.pyc
            |       '-- urls.cpython-36.pyc
            '-- enroll
                |-- forms.py
                |-- apps.py
                |-- models.py
                |-- __init__.py
                |-- tests.py
                |-- admin.py
                |-- views.py
                |-- templates
                |   '-- enroll
                |       '-- signup.html
                |-- __pycache__
                |   |-- views.cpython-36.pyc
                |   |-- models.cpython-36.pyc
                |   |-- forms.cpython-36.pyc
                |   |-- admin.cpython-36.pyc
                |   '-- __init__.cpython-36.pyc
                '-- migrations
                    |-- __init__.py
                    '-- __pycache__
                        '-- __init__.cpython-36.pyc
