ccflags-y := -O3 -fgcse-sm -marm -mtune=cortex-a8 -mcpu=cortex-a8 -march=armv7-a -mfpu=neon
obj-$(CONFIG_ION) +=	ion.o ion_heap.o ion_system_heap.o ion_carveout_heap.o ion_iommu_heap.o ion_cp_heap.o
obj-$(CONFIG_CMA) += ion_cma_heap.o
obj-$(CONFIG_ION_TEGRA) += tegra/
obj-$(CONFIG_ION_MSM) += msm/
