# Distributed under the Boost Software License, Version 1.0.
# See http://www.boost.org/LICENSE_1_0.txt

include(Ryppl)
include(RypplTestSuite)

ryppl_find_and_use_package(BoostLogic)
ryppl_find_and_use_package(BoostTest)

ryppl_test_suite(
  RUN
    tribool_test.cpp
    tribool_rename_test.cpp
    tribool_io_test.cpp
  NO_SINGLE_TARGET
  )
  
