# test-course
Repository showing general structure og a course

The course in this repository is in the folder `course`. This
means that the instructor should configure this course as
follows:

```
{
    url : "git@github.com:openteach/test-course.git/course"
}
```

There are numerous reasons for this structure:

* Integrated well with leanpub: the book in `manuscript` and the
  corresponding course in `course` in the same repository.
* Multiple courses in same repository
* Courses in the same repository as the instructor files