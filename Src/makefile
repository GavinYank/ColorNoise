



TOP = .


SUB_DIRS += Ap
SUB_DIRS += GofPattern
SUB_DIRS += FreeRTOS
SUB_DIRS += Algorithm
SUB_DIRS += Test
SUB_DIRS += DataStructure
SUB_DIRS += Module

.PHONY: FirstTarget

ifeq ($(MAKECMDGOALS), all)
LINK_CMD = link
endif

FirstTarget: Ap
	@$(MAKE) -s link



include $(TOP)/compile/common.mf





