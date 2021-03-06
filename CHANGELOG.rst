Change Log
==========

0.5.2 (2020-07-09)
------------------
* Check for wrong field types when converting from dict to ros msg
* Check for missing fields when converting from dict to ros msg
* Contributors: Martin Günther, alecarnevale

0.5.1 (2020-05-25)
------------------
* Initial release into Noetic
* Decode base64-encoded byte arrays as unicode
* Make tests compatible with python3
* add check for python3 str serializing `#33 <https://github.com/uos/rospy_message_converter/issues/33>`_ (`#34 <https://github.com/uos/rospy_message_converter/issues/34>`_)
* efficient conversion of primitive array to ros type (`#31 <https://github.com/uos/rospy_message_converter/issues/31>`_)
* efficient conversion of primitive array
* removed unused _convert_from_ros_primitive
* optionally ignore extra fields when deserializing (`#29 <https://github.com/uos/rospy_message_converter/issues/29>`_)
* Remove EOL distros indigo + lunar from CI
* travis CI: Use matrix to split ROS distros
* Update README (convert to md, add build status)
* Contributors: Martin Günther, George Hartt, Jannik Abbenseth, Omri Rozenzaft

0.5.0 (2019-01-17)
------------------
* Initial release into Lunar and Melodic
* Remove support for Jade (EOL)
* Change maintainer from Brandon Alexander to Martin Günther
* Move repo from baalexander to uos
* Add serialize_deserialize to unit tests, fix incorrect tests caught by this
* Remove dependency on ROS master in tests; all tests are now unit
  tests  (`#18 <https://github.com/uos/rospy_message_converter/issues/18>`_)
* Add service request/response support (`#17 <https://github.com/uos/rospy_message_converter/issues/17>`_)
* Fix fixed-size uint8 array conversion failure (`#15 <https://github.com/uos/rospy_message_converter/issues/15>`_)
* Fix unicode handling in string fields (`#13 <https://github.com/uos/rospy_message_converter/issues/13>`_)
* Enable testing only if CATKIN_ENABLE_TESTING is set (`#9 <https://github.com/uos/rospy_message_converter/issues/9>`_)
* Contributors: Martin Günther, Brandon Alexander, George Laurent, Jean-Baptiste Doyon, Viktor Schlegel, Rein Appeldoorn, Will Baker, neka-nat

0.4.0 (2015-12-13)
------------------
* Adds support for ROS Jade
* Removes support for ROS Groovy and Hydro (EOL)
* Uses single branch for all ROS versions
* Docker support for local development and Travis CI

0.3.0 (2014-06-03)
------------------
* Adds support for ROS Indigo

0.2.0 (2013-07-15)
------------------
* Updates to ROS Hydro
* Builds and runs tests with Travis CI
* Adds CHANGELOG

0.1.4 (2013-04-16)
------------------
* Documents Python functions
* Throws error if invalid JSON or dictionary

0.1.3 (2013-03-04)
------------------
* Adds rostest dependency

0.1.2 (2013-03-04)
------------------
* Adds missing build_depends and run_depends

0.1.1 (2013-03-01)
------------------
* Adds message_generation dependency to fix build

0.1.0 (2013-02-27)
------------------
* Initial release of rospy_message_converter
