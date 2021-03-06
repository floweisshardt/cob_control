^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cob_control_mode_adapter
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.6.11 (2016-04-01)
-------------------
* remove support for interpol_position controller
* fix mode adapter shutdown
* fix typo
* add joint_group_interpol_position_controller to control_mode_adapter
* Contributors: Marco Bezzon, ipa-fxm

0.6.10 (2015-08-31)
-------------------

0.6.9 (2015-08-25)
------------------
* more dependency fixes according to review comments
* explicit dependency to boost
* more fixes for migration afer merge
* remove trailing whitespaces
* migrate to package format 2
* sort dependencies
* review dependencies
* code styling cob_control_mode_adapter
* Contributors: ipa-fxm

0.6.8 (2015-06-17)
------------------

0.6.7 (2015-06-17)
------------------
* beautify CMakeLists
* reduce output
* check which controllers are available
* Contributors: ipa-fxm

0.6.6 (2014-12-18)
------------------

0.6.5 (2014-12-18)
------------------

0.6.4 (2014-12-16)
------------------

0.6.3 (2014-12-16)
------------------

0.6.2 (2014-12-15)
------------------
* Merge branch 'indigo_dev' into indigo_release_candidate
* fix cppcheck errors
* set default timeout for switching back to JTC to 0.3sec
* uncommment non default controllers
* moved and fixed switch log message
* switched to enum instead of string
* mutex/locks for thread safety
* moved switch logic to update loop
* init timestamps to zero instead of current time, prevent timing problems at start-up
* Merge pull request `#9 <https://github.com/ipa320/cob_control/issues/9>`_ from thiagodefreitas/indigo_new_structure
  More detailed LOG information for the controllers switch
* More detailed LOG information for the controllers switch
* remove timeout and report with ROS_WARN
* Merge pull request `#4 <https://github.com/ipa320/cob_control/issues/4>`_ from ipa-fxm/indigo_new_structure
  update dependencies
* update dependencies
* Merge pull request `#3 <https://github.com/ipa320/cob_control/issues/3>`_ from ipa-fxm/indigo_new_structure
  Indigo new structure
* extend timeout
* adapt namespaces for cartesian_controller to new structure
* adapt control_mode_adapter to new structure
* merge_cm
* temporary commit
* publish to JointGroup controllers
* null-space syncMM
* cleanup, restructure and fix
* Contributors: Florian Weisshardt, Mathias Lüdtke, ipa-fmw, ipa-fxm, ipa-fxm-cm, thiagodefreitas

0.6.1 (2014-09-22)
------------------

0.6.0 (2014-09-18)
------------------
* resolve namespace problem with velocity controller topics hardware vs. simulation
* resolve namespace problem of controller_manager hardware vs. simulation
* new package cob_control_mode_adapter
* Contributors: ipa-fxm

0.5.4 (2014-08-26 10:26)
------------------------

0.1.0 (2014-08-26 10:23)
------------------------
