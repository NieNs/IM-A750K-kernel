# CPUfreq core
obj-$(CONFIG_CPU_FREQ)			+= cpufreq.o
# CPUfreq stats
obj-$(CONFIG_CPU_FREQ_STAT)             += cpufreq_stats.o

# CPUfreq governors 
obj-$(CONFIG_CPU_FREQ_GOV_PERFORMANCE)	+= cpufreq_performance.o
obj-$(CONFIG_CPU_FREQ_GOV_POWERSAVE)	+= cpufreq_powersave.o
obj-$(CONFIG_CPU_FREQ_GOV_USERSPACE)	+= cpufreq_userspace.o
obj-$(CONFIG_CPU_FREQ_GOV_ONDEMAND)	+= cpufreq_ondemand.o
obj-$(CONFIG_CPU_FREQ_GOV_CONSERVATIVE)	+= cpufreq_conservative.o
obj-$(CONFIG_CPU_FREQ_GOV_SMARTASS)	+= cpufreq_smartass.o
obj-$(CONFIG_CPU_FREQ_GOV_LAZY)    += cpufreq_lazy.o

# CPUfreq cross-arch helpers
obj-$(CONFIG_CPU_FREQ_TABLE)		+= freq_table.o

# Added by jwjeon100717@DS2
obj-$(CONFIG_CPU_FREQ_PERFLOCK_USERSPACE) += cpufreq_perflock_userspace.o
