INCLUDES = -I/opt/local/boost/include/boost-1_44

CXXFLAGS += -Wall -static -g -O2 -fPIC

noinst_PROGRAMS = chaos_task_service

chaos_task_service_SOURCES = chaos.cpp \
							 ../misc_impl.cpp

#chaos_task_service_LDFLAGS =  -L/opt/local/boost.1.44/lib/
#chaos_task_service_LDFLAGS =  -L/opt/local/boost.1.44/lib

chaos_task_service_LDADD = \
			  $(top_srcdir)/chaos/libchaos_je.a \
			  -lpthread
#-lboost_system -lboost_thread -lboost_regex

