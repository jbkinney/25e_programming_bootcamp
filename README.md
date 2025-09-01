# 2024 Quantitative Biology Bootcamp

Welcome to the 2024 QB Bootcamp of the School for Biological Sciences at Cold Spring Harbor Laboratory! This Github repository contains the Jupyter notebooks, shell scripts, and datasets that we will work through in this bootcamp. 

## Summary

Repository URL: https://github.com/jbkinney/24e_qbbootcamp

Instructors: 
- Justin Kinney (<jkinney@cshl.edu>)
- Ivan Iossifov (<iossifov@cshl.edu>)

Teaching assistants:
- Aria Benjamin (<benjami@cshl.edu>)
- Kaiser Loell (<loell@cshl.edu>)

Schedule:
- Day 1: Tuesday, 3 September 2024, 10am - 6pm, Plimpton Conference Room, Beckman Bldg.
- Day 2: Wednesday, 4 September 2024, 1pm - 6pm, Plimpton Conference Room, Beckman Bldg.
- Day 3: Thursday, 5 September 2024, 10am - 5pm, Plimpton Conference Room, Beckman Bldg.

## Installing Python 3.12 

Students are asked to install the Anaconda distribution of Python 3.12, on their own computers. This is available at https://www.anaconda.com/products/distribution. 

## Windows laptops

Students with Windows laptops must also install the "Git BASH" tool to prepare for the Bootcamp. You can download it by going to https://gitforwindows.org and clicking the Download button. The installation asks many questions but fortunately provides default answers that work well for the course.

We will use GitBash for the "The Unix command line" section and for logging into Elzar, the high-performance computing cluster on campus.

## Elzar exercise

To log into the Elzar cluster, execute this at your command line:

```ssh [user]@bamdev2.cshl.edu```

where ``[user]`` is your CSHL username (e.g. mine is ``jkinney``). Then enter your CSHL password. 

To download elzar_exercise.tar.gz to Elzar, execute:

```wget --no-check-certificate "https://github.com/jbkinney/24e_qbbootcamp/raw/main/elzar_exercise.tar.gz"```

Then to unpack, execute:

```tar -zxvf elzar_exercise.tar.gz```

