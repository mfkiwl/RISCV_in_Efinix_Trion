PROJ_NAME=uartDemo
DEBUG=yes
MULDIV=yes
COMPRESSED=yes
STANDALONE = ..

SRCS = 	${shell find src -type f -name *.c} \
		${shell find src -type f -name *.cpp}  \
		${shell find src -type f -name *.S}

LDSCRIPT = ${STANDALONE}/common/linker_ram.ld

CFLAGS += -I${STANDALONE}/include

include ${STANDALONE}/common/riscv64-unknown-elf.mk
include ${STANDALONE}/common/standalone.mk

