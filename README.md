# scala-intro

## An introduction to Scala language

The Jupyter notebooks covers introductory topics. The content has been divided in three modules/workshops. 

Module 1 (notebooks 01-05) covers:
Introduction to Scala, definition of variables and functions, working with collections (Lists, Map, Set, Tuples...) and exercises.

The notebooks related to modules 2 and 3 will be released in coming days.

We encourage you to use Docker image: "jupyter/all-spark-notebook" in order to run a local Jupyter instance. 

A command should like:
~~~
sudo docker run -v /home/daniel/docs/repos/scala-intro.git:/home/jovyan/work -it -p 8888:8888 jupyter/all-spark-notebook start-notebook.sh --NotebookApp.token=''
~~~

After that, you only have to type in a browser the url: 
~~~
http://localhost:8888/
~~~

Any comment is welcomed!

Enjoy it!

Daniel Castro
dcmorell@gmail.com