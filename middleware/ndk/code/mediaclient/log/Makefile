LOCAL_DIR := $(shell pwd)
NDK_PATH := $(LOCAL_DIR)/../../..
MC_PARAM_FILE:=../Makefile.param
include $(MC_PARAM_FILE)

#*************************************************************************
# all source file in this module
SRCS := mapi_log_client.c


#*************************************************************************
TARGET := $(HIARCH)_log_client

#*************************************************************************
# compile linux or HuaweiLite
include $(PWD)/../Make.$(OSTYPE)
