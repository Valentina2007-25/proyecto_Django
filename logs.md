(env) C:\Users\karen\PycharmProjects\proyecto_django\my_tennis_club>python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
November 12, 2025 - 07:17:17
Django version 5.2.8, using settings 'my_tennis_club.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.

WARNING: This is a development server. Do not use it in a production setting. Use a production WSGI or ASGI server instead.
For more information on production servers see: https://docs.djangoproject.com/en/5.2/howto/deployment/
Not Found: /
[12/Nov/2025 07:17:28] "GET / HTTP/1.1" 404 2422
Not Found: /
[12/Nov/2025 07:17:33] "GET / HTTP/1.1" 404 2422
Not Found: /
[12/Nov/2025 07:17:33] "GET / HTTP/1.1" 404 2422
Not Found: /
[12/Nov/2025 07:17:33] "GET / HTTP/1.1" 404 2422
Not Found: /
[12/Nov/2025 07:17:43] "GET / HTTP/1.1" 404 2422
[12/Nov/2025 07:18:02] "GET /members HTTP/1.1" 301 0
Internal Server Error: /members/
Traceback (most recent call last):
  File "C:\Users\karen\PycharmProjects\proyecto_django\env\Lib\site-packages\django\core\handlers\exception.py", line 55, in inner
    response = get_response(request)
  File "C:\Users\karen\PycharmProjects\proyecto_django\env\Lib\site-packages\django\core\handlers\base.py", line 197, in _get_response
    response = wrapped_callback(request, *callback_args, **callback_kwargs)
  File "C:\Users\karen\PycharmProjects\proyecto_django\my_tennis_club\members\views.py", line 6, in members
    template = loader.get_template('myfirst.html')
               ^^^^^^^^^^^^^^^^^^^
AttributeError: module 'unittest.loader' has no attribute 'get_template'
[12/Nov/2025 07:18:02] "GET /members/ HTTP/1.1" 500 66602
