# Lab-5_202001221

### Name: Shah Harsh Sudarshan

### SID:  202001221

#### Tool : Pylint

* I used Pylint to find error of the code of http://surl.li/fnbwu

* The errors are as shown below:

![image](https://user-images.githubusercontent.com/84762507/225581747-0662ba64-d3aa-4dff-9d32-8b5b1f57bef3.png)

#### Analysis of errors:

#### 1) audio.py:19:0: C0325: Unnecessary parens after 'not' keyword (superfluous-parens)
        This type of errors can be taken into account as warnings but for better practice we can solve this type of errors by trying to avoid declaring those type of parens


#### 2) audio.py:26:0: C0304: Final newline missing (missing-final-newline)
      It could be removed by giving a extra line.

#### 3) audio.py:1:0: C0114: Missing module docstring (missing-module-docstring)
      You can solve this error by adding a docstring at the top of the module

#### 4) audio.py:1:0: C0410: Multiple imports on one line (os, sys) (multiple-imports)
      To avoid this warning we could write import on different line

#### 5) audio.py:2:0: E0401: Unable to import 'pydub' (import-error)
      We could use this instead 

      import pydub
      pydub.AudioSegment.ffmpeg = "C:\ffmpeg\bin"

#### 6) audio.py:8:0: C0103: Constant name "filename" doesn't conform to UPPER_CASE naming style (invalid-name)
      Moving the definition of myprint to main() is one way to suppress the message

#### 7) audio.py:14:10: C0207: Use filename.rsplit('.', maxsplit=1)[-1] instead (use-maxsplit-arg)
       We should use rsplit instead of split to avoid this message





