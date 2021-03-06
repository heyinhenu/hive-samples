hive-samples
============

hive-samples is a project that demonstrates various features of Apache Hive.

Dependencies
------------

* Apache Hadoop 2.x.y
* Apache Hive 0.13.x

Usage
-----

* Clone the repository
* Edit conf/hive-site.xml, and set javax.jdo.option.ConnectionURL to point to a path of your choice.
* Set HADOOP_HOME, HIVE_HOME and add Hadoop and Hive bin locations to the system OS path
* cd bin
* Execute run.sh &lt;subdirectory-name-under-scripts-directory&gt;, e.g. run.sh external_table_crud

License
-------
Copyright (c) 2015 Hemanth Yamijala

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
