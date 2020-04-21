# Definition of done

This document clarifies, when an product backlog item is done. During scrum development process this gives us a checklist,
what needs to be done.
The individual points are a basis for acceptance criteria and are shortened or appended by specific measures as needed.

## Documentation
* [ ] Public api
* [ ] API diagrams
* [ ] [Tutorials](https://wiki.ros.org/pilz_robots/Tutorials/)
* [ ] Readme
* [ ] ROS wiki
* [ ] Code (sphinx/doxygen)
* [ ] Good commit messages ([example](https://dev.to/jacobherrington/how-to-write-useful-commit-messages-my-commit-message-template-20n9
))
* [ ] Changelog.md updated
* [ ] Copyright headers

## Reviews
* [ ] Soft- and hardware architecture
* [ ] Code (coding rules, style guide)
* [ ] Test review (test plan and individual test cases)
* [ ] Documentation review

## Quality
* [ ] CI pass:
The travis job (for example in [pilz_robots](https://github.com/PilzDE/pilz_robots/blob/melodic-devel/.travis.yml)) checks full code coverage, successful test execution and code formatting using catkin_lint.

## Demo
* [ ] Example program / snippet prepared
* [ ] Ready for sprint review

## Release planning
* [ ] When is the new feature released?

## Cleanup
* [ ] [Squash-Merge](https://github.blog/2016-04-01-squash-your-commits/)
* [ ] Delete feature branch(es)
