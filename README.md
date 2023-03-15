# Lab-5_202001112


Software Engineering
Lab 5

Name: Sahil Kothari
ID: 202001112
Date: 15-03-2023


We chose the tools pylint in python for static analysis of python projects.
Installed pylint using pip install pylint command in command prompt
Took sample codes from python files.
Ran the command py -m pylint filename.py in command prompt
Took screenshots of the errors.


1) music.py

C:\Users\student\Downloads>py -m pylint music.py
************* Module music
music.py:262:0: C0301: Line too long (147/100) (line-too-long)
music.py:278:0: W0311: Bad indentation. Found 3 spaces, expected 4 (bad-indentation)
music.py:281:0: W0311: Bad indentation. Found 3 spaces, expected 4 (bad-indentation)
music.py:282:0: W0311: Bad indentation. Found 3 spaces, expected 4 (bad-indentation)
music.py:315:0: C0303: Trailing whitespace (trailing-whitespace)
music.py:316:0: C0304: Final newline missing (missing-final-newline)
music.py:1:0: C0114: Missing module docstring (missing-module-docstring)
music.py:24:20: W0621: Redefining name 'scale' from outer scope (line 281) (redefined-outer-name)
music.py:29:11: C0123: Use isinstance() rather than type() for a typecheck. (unidiomatic-typecheck)
music.py:32:13: C0123: Use isinstance() rather than type() for a typecheck. (unidiomatic-typecheck)
music.py:24:0: R1710: Either all return statements in a function should return an expression, or none of them should. (inconsistent-return-statements)
music.py:37:18: C0103: Argument name "n" doesn't conform to snake_case naming style (invalid-name)
music.py:37:11: W0621: Redefining name 'scale' from outer scope (line 281) (redefined-outer-name)
music.py:42:14: W0621: Redefining name 'key' from outer scope (line 207) (redefined-outer-name)
music.py:85:22: W0621: Redefining name 'notes' from outer scope (line 8) (redefined-outer-name)
music.py:95:4: W0621: Redefining name 'make_intervals' from outer scope (line 235) (redefined-outer-name)
music.py:97:8: C0103: Variable name "c" doesn't conform to snake_case naming style (invalid-name)
music.py:95:4: W0612: Unused variable 'make_intervals' (unused-variable)
music.py:109:0: C0116: Missing function or method docstring (missing-function-docstring)
music.py:111:4: C0103: Variable name "c" doesn't conform to snake_case naming style (invalid-name)
music.py:123:17: W0621: Redefining name 'formula' from outer scope (line 209) (redefined-outer-name)
music.py:196:9: W0621: Redefining name 'scale' from outer scope (line 281) (redefined-outer-name)
music.py:201:27: C0209: Formatting a regular string which could be a f-string (consider-using-f-string)
music.py:207:0: C0206: Consider iterating with .items() (consider-using-dict-items)
music.py:225:0: C0116: Missing function or method docstring (missing-function-docstring)
music.py:225:9: W0621: Redefining name 'scale' from outer scope (line 281) (redefined-outer-name)
music.py:235:0: C0116: Missing function or method docstring (missing-function-docstring)
music.py:235:19: W0621: Redefining name 'key' from outer scope (line 207) (redefined-outer-name)
music.py:245:4: W0621: Redefining name 'intervs' from outer scope (line 131) (redefined-outer-name)
music.py:262:18: C0209: Formatting a regular string which could be a f-string (consider-using-f-string)
music.py:265:12: W0702: No exception type(s) specified (bare-except)
music.py:274:14: E0602: Undefined variable 'make_intervals_standard' (undefined-variable)
music.py:276:0: C0103: Constant name "formula" doesn't conform to UPPER_CASE naming style (invalid-name)
music.py:278:36: E0602: Undefined variable 'make_intervals_standard' (undefined-variable)
music.py:281:33: E0602: Undefined variable 'make_intervals_standard' (undefined-variable)
music.py:282:9: C0209: Formatting a regular string which could be a f-string (consider-using-f-string)
music.py:285:0: C0206: Consider iterating with .items() (consider-using-dict-items)
music.py:289:14: C0209: Formatting a regular string which could be a f-string (consider-using-f-string)
music.py:294:0: C0206: Consider iterating with .items() (consider-using-dict-items)
music.py:296:10: C0209: Formatting a regular string which could be a f-string (consider-using-f-string)
music.py:310:4: C0206: Consider iterating with .items() (consider-using-dict-items)

-----------------------------------
Your code has been rated at 5.73/10



2) stream.py

C:\Users\student\Downloads>py -m pylint stream.py
************* Module stream
stream.py:28:0: C0301: Line too long (128/100) (line-too-long)
stream.py:71:0: C0304: Final newline missing (missing-final-newline)
stream.py:1:0: C0114: Missing module docstring (missing-module-docstring)
stream.py:3:0: E0401: Unable to import 'cv2' (import-error)
stream.py:4:0: E0401: Unable to import 'numpy' (import-error)
stream.py:5:0: E0401: Unable to import 'zmq' (import-error)
stream.py:7:0: E0401: Unable to import 'constants' (import-error)
stream.py:8:0: E0401: Unable to import 'utils' (import-error)
stream.py:11:0: C0115: Missing class docstring (missing-class-docstring)
stream.py:54:0: C0116: Missing function or method docstring (missing-function-docstring)

-----------------------------------
Your code has been rated at 2.50/10

3) cowin.py

C:\Users\student\Downloads>py -m pylint cowin.py
************* Module cowin
cowin.py:20:0: C0301: Line too long (121/100) (line-too-long)
cowin.py:23:0: C0301: Line too long (140/100) (line-too-long)
cowin.py:27:0: W0311: Bad indentation. Found 14 spaces, expected 16 (bad-indentation)
cowin.py:28:0: W0311: Bad indentation. Found 14 spaces, expected 16 (bad-indentation)
cowin.py:29:0: W0311: Bad indentation. Found 14 spaces, expected 16 (bad-indentation)
cowin.py:30:0: W0311: Bad indentation. Found 16 spaces, expected 20 (bad-indentation)
cowin.py:31:0: W0311: Bad indentation. Found 18 spaces, expected 24 (bad-indentation)
cowin.py:32:0: W0311: Bad indentation. Found 20 spaces, expected 28 (bad-indentation)
cowin.py:33:0: W0311: Bad indentation. Found 22 spaces, expected 32 (bad-indentation)
cowin.py:34:0: W0311: Bad indentation. Found 22 spaces, expected 32 (bad-indentation)
cowin.py:35:0: W0311: Bad indentation. Found 22 spaces, expected 32 (bad-indentation)
cowin.py:36:0: W0311: Bad indentation. Found 22 spaces, expected 32 (bad-indentation)
cowin.py:37:0: W0311: Bad indentation. Found 22 spaces, expected 32 (bad-indentation)
cowin.py:38:0: W0311: Bad indentation. Found 22 spaces, expected 32 (bad-indentation)
cowin.py:39:0: C0301: Line too long (103/100) (line-too-long)
cowin.py:39:0: W0311: Bad indentation. Found 22 spaces, expected 32 (bad-indentation)
cowin.py:40:0: C0301: Line too long (103/100) (line-too-long)
cowin.py:40:0: W0311: Bad indentation. Found 22 spaces, expected 32 (bad-indentation)
cowin.py:41:0: W0311: Bad indentation. Found 22 spaces, expected 32 (bad-indentation)
cowin.py:42:0: W0311: Bad indentation. Found 22 spaces, expected 32 (bad-indentation)
cowin.py:44:0: W0311: Bad indentation. Found 14 spaces, expected 16 (bad-indentation)
cowin.py:46:0: W0311: Bad indentation. Found 6 spaces, expected 8 (bad-indentation)
cowin.py:48:0: W0311: Bad indentation. Found 6 spaces, expected 8 (bad-indentation)
cowin.py:49:0: C0301: Line too long (117/100) (line-too-long)
cowin.py:49:0: W0311: Bad indentation. Found 6 spaces, expected 8 (bad-indentation)
cowin.py:50:0: W0311: Bad indentation. Found 6 spaces, expected 8 (bad-indentation)
cowin.py:56:0: C0304: Final newline missing (missing-final-newline)
cowin.py:56:0: W0311: Bad indentation. Found 6 spaces, expected 8 (bad-indentation)
cowin.py:1:0: C0114: Missing module docstring (missing-module-docstring)
cowin.py:1:0: E0401: Unable to import 'requests' (import-error)
cowin.py:5:0: E0401: Unable to import 'playsound' (import-error)
cowin.py:8:0: C0103: Constant name "age" doesn't conform to UPPER_CASE naming style (invalid-name)
cowin.py:10:0: C0103: Constant name "num_days" doesn't conform to UPPER_CASE naming style (invalid-name)
cowin.py:17:4: C0103: Constant name "cnt" doesn't conform to UPPER_CASE naming style (invalid-name)
cowin.py:20:18: C0209: Formatting a regular string which could be a f-string (consider-using-f-string)
cowin.py:28:14: C0103: Constant name "flag" doesn't conform to UPPER_CASE naming style (invalid-name)
cowin.py:2:0: C0411: standard import "import time" should be placed before "import requests" (wrong-import-order)
cowin.py:3:0: C0411: standard import "import json" should be placed before "import requests" (wrong-import-order)
cowin.py:4:0: C0411: standard import "from datetime import datetime, timedelta" should be placed before "import requests" (wrong-import-order)
cowin.py:3:0: W0611: Unused import json (unused-import)

-----------------------------------
Your code has been rated at 0.00/10


4) algorithm.py

C:\Users\student\Downloads>py -m pylint algorithm.py
************* Module algorithm
algorithm.py:15:37: C0303: Trailing whitespace (trailing-whitespace)
algorithm.py:19:0: C0303: Trailing whitespace (trailing-whitespace)
algorithm.py:1:0: C0114: Missing module docstring (missing-module-docstring)
algorithm.py:5:0: C0115: Missing class docstring (missing-class-docstring)
algorithm.py:10:4: C0116: Missing function or method docstring (missing-function-docstring)
algorithm.py:11:8: C0415: Import outside toplevel (visualizer) (import-outside-toplevel)
algorithm.py:11:8: E0401: Unable to import 'visualizer' (import-error)
algorithm.py:14:4: C0116: Missing function or method docstring (missing-function-docstring)
algorithm.py:21:4: C0116: Missing function or method docstring (missing-function-docstring)
algorithm.py:22:24: W1309: Using an f-string that does not have any interpolated variables (f-string-without-interpolation)
algorithm.py:15:8: W0201: Attribute 'start_time' defined outside __init__ (attribute-defined-outside-init)
algorithm.py:25:0: C0115: Missing class docstring (missing-class-docstring)
algorithm.py:30:8: C0200: Consider using enumerate instead of iterating with range and len (consider-using-enumerate)
algorithm.py:39:0: C0115: Missing class docstring (missing-class-docstring)
algorithm.py:51:0: C0115: Missing class docstring (missing-class-docstring)
algorithm.py:56:8: C0200: Consider using enumerate instead of iterating with range and len (consider-using-enumerate)
algorithm.py:66:0: C0115: Missing class docstring (missing-class-docstring)
algorithm.py:70:4: W0102: Dangerous default value [] as argument (dangerous-default-value)
algorithm.py:80:4: C0116: Missing function or method docstring (missing-function-docstring)
algorithm.py:97:0: C0115: Missing class docstring (missing-class-docstring)
algorithm.py:101:4: W0102: Dangerous default value [] as argument (dangerous-default-value)
algorithm.py:110:4: C0116: Missing function or method docstring (missing-function-docstring)
algorithm.py:111:8: C0103: Variable name "x" doesn't conform to snake_case naming style (invalid-name)

-----------------------------------
Your code has been rated at 7.22/10
