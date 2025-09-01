# 2025 Programming Bootcamp

Welcome to the 2025 Programming Bootcamp of the School for Biological Sciences at Cold Spring Harbor Laboratory! This Github repository contains the Jupyter notebooks, shell scripts, and datasets that we will work through in this bootcamp. 

## Summary

Repository URL: https://github.com/jbkinney/25e_programming_bootcamp

Instructors: 
- Justin Kinney (<jkinney@cshl.edu>)
- Ivan Iossifov (<iossifov@cshl.edu>)
- Hannah Meyer, (<hmeyer@cshl.edu>)

Teaching assistants:
- Alan Murphy, (<amurphy@cshl.edu>)
- Stan Kerstjens, (<kerstje@cshl.edu>)

## Installing Python 3.13 

Students are asked to install the Anaconda distribution of Python 3.13, on their own computers. This is available at https://www.anaconda.com/download.

## Windows laptops

Students with Windows laptops must also install the "Git BASH" tool to prepare for the Bootcamp. You can download it by going to https://gitforwindows.org and clicking the Download button. The installation asks many questions but fortunately provides default answers that work well for the course.

We will use GitBash for the "The Unix command line" section and for logging into Elzar, the high-performance computing cluster on campus.

## Elzar exercise

To log into the Elzar cluster, execute this at your command line:

```ssh [user]@bamdev2.cshl.edu```

where ``[user]`` is your CSHL username (e.g. mine is ``jkinney``). Then enter your CSHL password. 

To download elzar_exercise.tar.gz to Elzar, execute:

```
wget --no-check-certificate "https://github.com/jbkinney/25e_programming_
bootcamp/raw/main/elzar_exercise.tar.gz"
```

Then to unpack, execute:

```tar -zxvf elzar_exercise.tar.gz```

