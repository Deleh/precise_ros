^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package precise_driver
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.2 (2021-05-10)
------------------
* Merge pull request `#22 <https://github.com/mojin-robotics/precise_ros/issues/22>`_ from fmessmer/fix/roscontrol_boilerplate
  fix/roscontrol boilerplate
* dual-distro compatibility
* Revert "replaced boost with std shared_ptr"
  This reverts commit 6260f2e1251f8f6e3f1243737fa1779b13a7f619.
* replaced boost with std shared_ptr
* Merge pull request `#21 <https://github.com/mojin-robotics/precise_ros/issues/21>`_ from benmaidel/fix/controller_name
  fix JointTrajectoryController name
* fix JointTrajectoryController name
* Merge pull request `#17 <https://github.com/mojin-robotics/precise_ros/issues/17>`_ from benmaidel/feature/doosan_hack
  Feature/doosan hack
* add gripper joint_state to JointPositions
* add ugly doosan like hack for trajectory execution
* Merge pull request `#13 <https://github.com/mojin-robotics/precise_ros/issues/13>`_ from fmessmer/kevin_ipa
  Updates from testing at IPA
* testing at IPA
* Merge pull request `#10 <https://github.com/mojin-robotics/precise_ros/issues/10>`_ from fmessmer/test_noetic
  test noetic
* Bump CMake version to avoid CMP0048 warning
* Merge pull request `#9 <https://github.com/mojin-robotics/precise_ros/issues/9>`_ from floweisshardt/kevin_ipa
  updates from testing at IPA
* fix error handling
* Merge pull request `#8 <https://github.com/mojin-robotics/precise_ros/issues/8>`_ from benmaidel/feature/gripper_control
  Add gripper control
* considered PR comments
* add comments
* add recover functionality
* debug read write timing
* update robot states in read method
* use ROS_DEBUG_NAMED
* init state variables
* added error codes enum class
* refactored file and class naming
* adapt members to ros style naming
* refactored device code
* fix grasp and release plate
* gripper srvs:
  - add graspPlate releasePlate service
  - modified gripper service
  - updated waitForEom
* graspPlate and releasePlate fixup
* clear command queue on controller reset
* start/stop fjt controller on teachmode
* add open/close gripper service
* add resetController method
* add missing deps
* add gripper srv and fix CMakeLists
* Merge pull request `#6 <https://github.com/mojin-robotics/precise_ros/issues/6>`_ from fmessmer/testing
  Testing on HW
* pid gains not needed
* add missing dependencies
* add roslaunch checks
* fix license
* add missing install tags
* enable disable write joint_commands
* fix use transformed joint datas
* remove debug logging from queue
* add additional logging
* fix socket ports
* add missing dependencies
* fixes
* add second TCP Connection for status updates (joint_states)
* add thread safe queue to decouple arm communication from realtime loop. (Consumer Producer pattern)
* fixup command service
* refactor service callback method names
* add command service
* fix getSysState return value
* add command method
* use const reference method parameters
* remove mockup tcp interface
* update controller configuration
* fix CMakeLists
* update launch file
* updated hardware interface
* add Response type
* indentation fix
* update precise implementation
* use PreciseTCPInterface
* updated controller config
* add todos that needs to be considered
* return received joints
* wip precise ros driver
* add c++11 compile option
* add simple TCP communication
* add template for TCP interface
* wip pflex device class
* fix linter errors
* add parameters pflex
* add services for init, teachmode, home, power and attach
* update license
* add initial driver package
* Contributors: Benjamin Maidel, Felix Messmer, deleh, fmessmer, mojin@cob4-20
