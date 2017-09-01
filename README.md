Project 0 CUDA Getting Started
====================

**University of Pennsylvania, CIS 565: GPU Programming and Architecture, Project 0**

* Anton Khabbaz
* Tested on: Windows 10 surface book i7-6600u at 2.66 GHz with a GPU GTX 965M
Personal computer

### (TODO: Your README)

I finished all parts of this assignment, without needing to know much about CUDA.  I was able to install VS 2015, Cuda 8, Cmake
and Git Hub and I figured out how to fork. 

I had a real problem with Cmake.  The difficulty was that I had a previous installation of 
Visual Studio, 2017 that was enterprise.  I didn't try to install cuda 8 on that because I believe cuda 8 does not support
VS 2017 yet.  Anyway, I then had two versions 2015 and 2017.  When I ran Cmake, it would find the VS 2017 compiler right away, but wouldn't be able to complete the project.  I didn't try to get that to work too hard.

With VS 2015 it never found the compiler.  I told it where the compiler was I got a large kryptic message that I posted on the google group.  The suggestion offered didn't help either.  I came to the sig lab and with Josh and another student, they also couldn't sort it out.  I then uninstalled VS2017 and then it all went ahead as in the instructions.  I think that when a later version of VS is installed, Cmake does not easily accept using the earlier version.

I took a screen shot of the colored images.  The build and run were straighforward.
![](images/ColoredWindowAntonKhabbaz.png)

