# Module build makefile
CUR_ROOT    := $(shell pwd)
REF_ROOT    ?= $(CUR_ROOT)/../../../..
OS_TYPE     := HuaweiLite
include $(REF_ROOT)/build/base.mak


MODULE_ROOT := $(CUR_ROOT)/..
MODULE_NAME := hitempcycle_server

SRC_ROOT    := $(MODULE_ROOT)/server
SRC_DIR     := $(SRC_ROOT)

OBJ_ROOT    := $(REF_OUT_COMMON_OBJ)/$(OS_TYPE)/$(MODULE_NAME)
LIB_ROOT    := $(REF_OUT_COMMON_LIB)/$(OS_TYPE)

include $(REF_ROOT)/build/modbuild.mak
