<p align="center">
  <img src="https://s19.postimg.org/x7tuqvk4z/screenshot_1493330027.png">
</p>

# ReadMe for Task 1
---------------

Chapter 1. File: Pandas\Obesity.py
`Error:Missing parentheses in call to 'print'(fixed)`
****Solved***

Chapter 1. File: Pandas\pandas_movie.py
`Error1:invalid syntax(fixed)`
***Solved***

`Error2:UnicodeDecodeError: 'utf-8' codec can't decode byte 0xe9 in position 3: invalid 

continuation byte(Fixed it, used  , encoding='latin-1'))`
Solution: http://stackoverflow.com/questions/5552555/unicodedecodeerror-invalid-continuation-byte
***Solved***

`
Warning 1: FutureWarning: by argument to sort_index is deprecated, pls use .sort_values(by=...)
Warning 2: FutureWarning: order is deprecated, use sort_values(...)
`
Solution: We need to use sort_values, everywhere
***Solved***

Chapter 2. File: machine\ml_main.py
`Error:Missing parentheses in call to 'print'(fixed)`
***Solved***

Chapter 3. File: Multiprocessing\gen_rand.py
`Error:Missing parentheses in call to 'print'(fixed)`
***Solved***

Chapter 4. Audio
***NO Errors***


Chapter 5. Plotting
***NO Errors***


Chapter 6. WordCount
***NO Errors***


Chapter 7. File: Image_Video/color_test.py", line 6, in <module>
`Error:from SimpleCV import *
ModuleNotFoundError: No module named 'SimpleCV
Solution=I installed the SimpleCV libraries in Ubuntu, but it seems something is still missing.
**As you said Shantnu i need to compile CV libraries manually**
`
***Issue unsolved=Image_Video***

------

==========Moving Forward=============
Chapter 8. rpi
File: rpi\webapp.py
Error:
`
raceback (most recent call last):
  File "/home/mantejsingh/Downloads/PyEng-master/rpi/webapp.py", line 28, in <module>
    app.run(host='0.0.0.0', port=80, debug=True)
  File "/home/mantejsingh/anaconda3/lib/python3.6/site-packages/flask/app.py", line 841, in run
    run_simple(host, port, self, **options)
  File "/home/mantejsingh/anaconda3/lib/python3.6/site-packages/werkzeug/serving.py", line 691, 

in run_simple
    s.bind((hostname, port))
PermissionError: [Errno 13] Permission denied
`
Solutions:
1.http://stackoverflow.com/questions/34801814/permissionerror-errno-13-permission-denied
2.http://stackoverflow.com/questions/34785690/execute-hello-world-with-flask-importerror-no-

module-named-flask

So what i did is, ran the file as a admin
`mantejsingh@ubuntu:~/Downloads/PyEng-master/rpi$ sudo python webapp.py`
then
Installed `flask` as global package:

`sudo pip install flask
`

