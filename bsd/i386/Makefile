export MakeInc_cmd=${SRCROOT}/makedefs/MakeInc.cmd
export MakeInc_def=${SRCROOT}/makedefs/MakeInc.def
export MakeInc_rule=${SRCROOT}/makedefs/MakeInc.rule
export MakeInc_dir=${SRCROOT}/makedefs/MakeInc.dir

include $(MakeInc_cmd)
include $(MakeInc_def)

DATAFILES = \
	endian.h fasttrap_isa.h param.h \
	profile.h signal.h limits.h _limits.h \
	types.h vmparam.h _types.h _param.h \
	_mcontext.h

PRIVATE_DATAFILES = \
	disklabel.h

KERNELFILES = \
	endian.h param.h \
	profile.h signal.h limits.h _limits.h \
	types.h vmparam.h _types.h _param.h \
	_mcontext.h

INSTALL_MD_LIST = ${DATAFILES}
INSTALL_MD_LCL_LIST = ${PRIVATE_DATAFILES}

INSTALL_MD_DIR = i386

EXPORT_MD_LIST = ${KERNELFILES}

EXPORT_MD_DIR = i386

include $(MakeInc_rule)
include $(MakeInc_dir)
