
PULP_APP = cnn_layer
PULP_APP_FC_SRCS = cnn_layer.c cnn_kernels.c
PULP_APP_HOST_SRCS = cnn_layer.c cnn_kernels.c
PULP_CFLAGS = -O3 -g
#-DDOTP

PULP_FC_ARCH_CFLAGS = -march=rv32imcxpulpv2 -D__riscv__
#zero-riscy:   -march=rv32imcxpulpslim -DRV_ISA_RV32=1 -D__riscv__
#riscy:        -march=rv32imcxpulpv2 -D__riscv__

include $(PULP_SDK_HOME)/install/rules/pulp_rt.mk
