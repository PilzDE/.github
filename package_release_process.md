# How-to release a PILZ-ROS package
(The general ROS package release process is described here: http://wiki.ros.org/bloom/Tutorials/ReleaseCatkinPackage)
- Create a new branch derived from the current `melodic-devel` branch named like this:  
  `release/NEW_RELEASE_NUMBER` (`NEW_RELASE_NUMBER` e.g. `1.0.7`)
- Push the newly created branch to the GitHub server via:  
  `git push origin release/NEW_RELEASE_NUMBER --set-upstream`
- Execute `catkin_generate_changelog` to update CHANGELOG.rst. Check all changed `CHANGELOG.rst` files after execution of command.
- Execute `catkin_prepare_release`. Check all requests by the command and confirm the requests.
- Merge new branch `release/NEW_RELEASE_NUMBER` into `melodic-devel` via Pull Request.  
  **Please note:** Avoid `Squash and merge` or `Rebase and merge` because it leads to errors with the tag for the next release (due to changed commit id's). If you want to 'Squash and merge' or 'Rebase and merge' then update the remote tag for the release after the execution of `Squash and merge` or `Rebase and merge`!
- Execute command `bloom-release MY_PACKAGE_NAME --rosdistro melodic`. Check and confirm all requests of the command.  
 **Please note:** Before you execute the `bloom-release` command, ensure that your system is correctly set-up. For more information on how-to setup you system see: http://wiki.ros.org/bloom/Tutorials/GithubManualAuthorization 
