add_lldb_unittest(ProcessGdbRemoteTests
  GDBRemoteClientBaseTest.cpp
  GDBRemoteCommunicationClientTest.cpp
  GDBRemoteTestUtils.cpp

  LINK_LIBS
    lldbCore
    lldbHost
    lldbPluginPlatformMacOSX
    lldbPluginProcessUtility
    lldbPluginProcessGDBRemote
  LINK_COMPONENTS
    Support
  )
