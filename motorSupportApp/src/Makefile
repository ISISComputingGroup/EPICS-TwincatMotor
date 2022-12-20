TOP=../..

include $(TOP)/configure/CONFIG

LIBRARY_IOC += adsMotorSupport

adsMotorSupport_SRCS += devMotorController.cpp
adsMotorSupport_SRCS += devMotorAxis.cpp

DBD += adsMotorSupport.dbd
adsMotorSupport_DBD += devMotorController.dbd

# Finally link to the EPICS Base libraries
adsMotorSupport_LIBS += asyn
adsMotorSupport_LIBS += motor
adsMotorSupport_LIBS += $(EPICS_BASE_IOC_LIBS)

#===========================

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

