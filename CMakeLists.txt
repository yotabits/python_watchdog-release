cmake_minimum_required(VERSION 2.8.3)
project(python_watchdog)

find_package(catkin REQUIRED COMPONENTS
             pathtools
             catkin_pip
  )

catkin_pip_package(pyhton_watchdog)

## Add folders to be run by python nosetests
#catkin_add_nosetests(tests)
