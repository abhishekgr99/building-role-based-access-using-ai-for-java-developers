# Building Role Based Access using AI for Java Developers
This is the repository for the LinkedIn Learning course `Building Role Based Access using AI for Java Developers`. The full course is available from [LinkedIn Learning][lil-course-url].

![lil-thumbnail-url]

## Course Description

In this intermediate-level course, instructor Harit Himanshu shows you how to implement a comprehensive role-based access control (RBAC) system inspired by GitHub's permission model using Java, Spring Boot, MongoDB, and Docker. Starting with core domain modeling, learn how to design and implement both personal and organization account structures with their respective permission hierarchies, develop secure authentication flows and resource management APIs, and create sophisticated authorization mechanisms that handle complex scenarios like role inheritance and resource sharing within organizations. Along the way, leverage the power of GitHub Copilot to accelerate development and testing processes, while learning industry best practices for security implementations. By the end of this course, you'll be equipped with the skills you need to build and test a production-ready RBAC system at scale.

# Developer Setup
- To ensure everything works, run `mvn clean install` in the root directory.
- To run the application, run `mvn exec:java -Dexec.mainClass="com.ll.App"` in the root directory. This should print out "Hello World!".

  
_See the readme file in the main branch for updated instructions and information._
## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

 ## Instructor

Harit Himanshu

Cofounder and CTO at BetterMenu

                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/harit-himanshu?u=104).


[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/building-role-based-access-using-ai-for-java-developers
[lil-thumbnail-url]: https://media.licdn.com/dms/image/v2/D4D0DAQGgdcuarTc-2g/learning-public-crop_675_1200/B4DZU_nMwgHIAY-/0/1740528996100?e=2147483647&v=beta&t=mpANNDzx3OeNVM_jFQEZZQaarf9biGmP3mArYg-iMfQ

