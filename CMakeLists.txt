CMAKE_MINIMUM_REQUIRED(VERSION 3.10)
INCLUDE(cmake/python.cmake)

PROJECT(fake-ros)

PYTHON_INSTALL_ON_SITE(move_base_msgs __init__.py)
PYTHON_INSTALL_ON_SITE(move_base_msgs/msg __init__.py)
