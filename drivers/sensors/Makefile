#
# Makefile for the sensors drivers.
#

# Each configuration option enables a list of files.

obj-$(CONFIG_SENSORS_CORE)          += sensors_core.o

# accelerometer_sensor
obj-$(CONFIG_SENSORS_LSM6DSL)            += lsm6dsl_core.o
obj-$(CONFIG_SENSORS_LSM6DSL_I2C)        += lsm6dsl_i2c.o
obj-$(CONFIG_SENSORS_LSM6DSL_SPI)        += lsm6dsl_spi.o
obj-$(CONFIG_SENSORS_LIS2DS)            += lis2ds_core.o
obj-$(CONFIG_SENSORS_LIS2DS_I2C)            += lis2ds_i2c.o
obj-$(CONFIG_SENSORS_LIS2DS_SPI)            += lis2ds_spi.o
obj-$(CONFIG_SENSORS_K2HH)          += k2hh.o
# magnetic_sensor
obj-$(CONFIG_SENSORS_YAS539)		+= yas_mag_drv-yas539.o yas_mag_kernel.o
# optical_sensor
obj-$(CONFIG_SENSORS_GP2AP070S)	    += gp2ap070s.o
obj-$(CONFIG_SENSORS_STK3013)       += stk3013.o
obj-$(CONFIG_SENSORS_CM36686)       += cm36686.o
obj-$(CONFIG_SENSORS_CM36672P)	    += cm36672p.o
obj-$(CONFIG_SENSORS_TMD3725)       += tmd3725.o
#grip_sensor
obj-$(CONFIG_SENSORS_A96T3X6)		+= a96t3x6.o