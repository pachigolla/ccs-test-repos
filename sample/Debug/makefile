################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := C:/ti/ccsv7/tools/compiler/ti-cgt-c2000_16.9.6.LTS

GEN_OPTS__FLAG := 
GEN_CMDS__FLAG := 

ORDERED_OBJS += \
"./main.obj" \
"./source/adc.obj" \
"./source/asysctl.obj" \
"./source/can.obj" \
"./source/cla.obj" \
"./source/clb.obj" \
"./source/cmpss.obj" \
"./source/cputimer.obj" \
"./source/dac.obj" \
"./source/dcsm.obj" \
"./source/dma.obj" \
"./source/ecap.obj" \
"./source/emif.obj" \
"./source/epwm.obj" \
"./source/eqep.obj" \
"./source/flash.obj" \
"./source/gpio.obj" \
"./source/hrpwm.obj" \
"./source/i2c.obj" \
"./source/interrupt.obj" \
"./source/ipc.obj" \
"./source/mcbsp.obj" \
"./source/memcfg.obj" \
"./source/sci.obj" \
"./source/sdfm.obj" \
"./source/spi.obj" \
"./source/sysctl.obj" \
"./source/upp.obj" \
"./source/usb.obj" \
"./source/version.obj" \
"./source/xbar.obj" \
"../2837x_FLASH_lnk_cpu1.cmd" \
$(GEN_CMDS__FLAG) \
-llibc.a \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include source/subdir_vars.mk
-include subdir_rules.mk
-include source/subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(SV7A_DEPS)),)
-include $(SV7A_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
sample.out \

EXE_OUTPUTS__QUOTED += \
"sample.out" \

BIN_OUTPUTS += \
sample.hex \

BIN_OUTPUTS__QUOTED += \
"sample.hex" \


# All Target
all: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@$(MAKE) --no-print-directory -Onone "sample.out"

# Tool invocations
sample.out: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@echo 'Building target: "$@"'
	@echo 'Invoking: C2000 Linker'
	"C:/ti/ccsv7/tools/compiler/ti-cgt-c2000_16.9.6.LTS/bin/cl2000" -v28 -ml -mt --cla_support=cla1 --float_support=fpu32 --tmu_support=tmu0 --vcu_support=vcu2 -g --diag_warning=225 --diag_wrap=off --display_error_number -z -m"sample.map" --stack_size=0x200 --warn_sections -i"C:/ti/ccsv7/tools/compiler/ti-cgt-c2000_16.9.6.LTS/lib" -i"C:/ti/ccsv7/tools/compiler/ti-cgt-c2000_16.9.6.LTS/include" --reread_libs --diag_wrap=off --display_error_number --xml_link_info="sample_linkInfo.xml" --rom_model -o "sample.out" $(ORDERED_OBJS)
	@echo 'Finished building target: "$@"'
	@echo ' '

sample.hex: $(EXE_OUTPUTS)
	@echo 'Building files: $(strip $(EXE_OUTPUTS__QUOTED))'
	@echo 'Invoking: C2000 Hex Utility'
	"C:/ti/ccsv7/tools/compiler/ti-cgt-c2000_16.9.6.LTS/bin/hex2000"  -o "sample.hex" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $(strip $(EXE_OUTPUTS__QUOTED))'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(BIN_OUTPUTS__QUOTED)$(EXE_OUTPUTS__QUOTED)
	-$(RM) "main.obj" "source\adc.obj" "source\asysctl.obj" "source\can.obj" "source\cla.obj" "source\clb.obj" "source\cmpss.obj" "source\cputimer.obj" "source\dac.obj" "source\dcsm.obj" "source\dma.obj" "source\ecap.obj" "source\emif.obj" "source\epwm.obj" "source\eqep.obj" "source\flash.obj" "source\gpio.obj" "source\hrpwm.obj" "source\i2c.obj" "source\interrupt.obj" "source\ipc.obj" "source\mcbsp.obj" "source\memcfg.obj" "source\sci.obj" "source\sdfm.obj" "source\spi.obj" "source\sysctl.obj" "source\upp.obj" "source\usb.obj" "source\version.obj" "source\xbar.obj" 
	-$(RM) "main.d" "source\adc.d" "source\asysctl.d" "source\can.d" "source\cla.d" "source\clb.d" "source\cmpss.d" "source\cputimer.d" "source\dac.d" "source\dcsm.d" "source\dma.d" "source\ecap.d" "source\emif.d" "source\epwm.d" "source\eqep.d" "source\flash.d" "source\gpio.d" "source\hrpwm.d" "source\i2c.d" "source\interrupt.d" "source\ipc.d" "source\mcbsp.d" "source\memcfg.d" "source\sci.d" "source\sdfm.d" "source\spi.d" "source\sysctl.d" "source\upp.d" "source\usb.d" "source\version.d" "source\xbar.d" 
	-@echo 'Finished clean'
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets

