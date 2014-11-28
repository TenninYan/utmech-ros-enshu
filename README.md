utmech-ros-enshu
============

ROS pkgs used in the class.


How to use these ROS pkgs in your catkin workspace
---
このROSパッケージを自分の環境で使うときの設定。
```bash
# clone this repo to the src directory in your catkin workspace
$ mkdir -p ~/catkin_ws/ros-enshu/src
$ cd ~/catkin_ws/ros-enshu/src
$ git clone https://github.com/utmech-2014/utmech-ros-enshu.git

# make it
$ cd ..
$ catkin_make
$ catkin_make install
$ source ~/catkin_ws/ros-enshu/devel/setup.bash

# run samples
$ rosrun ytk-check3-1.l
$ roseus ytk-check3-2.l
```

How to contribute to this repository
---
contributeの仕方。
* First, fork this repository.
* Setup the git remote target in your local workspace __like below__.
* Change the sources in the branch and send pull requests!
```bash
$ cd ~/catkin_ws/ros-enshu/src/utmech-ros-enshu
$ git branch YOUR-GITHUB-USERNAME
$ git checkout YOUR-GITHUB-USERNAME
$ git remote add YOUR-GITHUB-USERNAME git@github.com:YOUR-GITHUB-USERNAME/utmech-ros-enshu
```

Information for git & GitHub
---
Git tutorial video in Japanese
* [git入門 (全22回) - プログラミングならドットインストール](http://dotinstall.com/lessons/basic_git)

Git Documentation
* [Git -Book](http://git-scm.com/book/ja/v1)

Cheat Sheet
* [GitHub - GIT CHEAT SHEET](https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf)
* [Git Cheatsheet • NDP Software](http://ndpsoftware.com/git-cheatsheet.html)
