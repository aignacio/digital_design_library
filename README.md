<img src="https://github.com/aignacio/design_vault/assets/5991372/34fe6ef0-a7c0-4de1-bc16-aa71bb4e707a" width="200" height="200" />

# Digital Design Library

List of several designs/tools I have worked on over the years to avoid reinventing the wheel.

## Table of Contents
* [IPs](#ips)
* [Tools](#tools)
* [Software](#sw)

___

## <a name="ips"></a> IPs

* [RaveNoC](https://github.com/aignacio/ravenoc): Configurable Network-on-Chip described in SystemVerilog.
* [NoX](https://github.com/aignacio/nox): Soft-core RISC-V RV32I with AMBA compatible interfaces and FreeRTOS port.
* [DMA](https://github.com/aignacio/axi_dma): DMA engine based on AMBA AXI protocol, fully configurable.
* [Skid Buffer](https://github.com/aignacio/skid_buffer): Skid buffer is to break the combinatorial path between the sender and receiver interfaces, also known as `register slices` (AMBA convention).
* [Simple interrupt controller](https://github.com/aignacio/soc_components/blob/master/axi_irq_ctrl.sv): Generic interrupt controller with configurable fifo size and fixed priority.
* [SPI Master](https://github.com/aignacio/soc_components/blob/master/axi_spi_master.sv): AXI SPI design with programmable FIFO buffer size and external IOs.
* [M-TIMER RISC-V](https://github.com/aignacio/soc_components/blob/master/axi_timer.sv): Simple machine timer design fully compatible with privileged RISC-V specification.
* [Reset controller](https://github.com/aignacio/soc_components/blob/master/axi_rst_ctrl.sv): Reset controller used to define start vector value for general purpose CPUs and software controllable reset output.
* [Synchronous general-purpose FIFO](https://github.com/aignacio/soc_components/blob/master/sync_gp_fifo.sv): Synchronous FIFO design.
* [Asynchronous general-purpose FIFO](https://github.com/aignacio/soc_components/blob/master/async_gp_fifo.sv): Asynchronous FIFO design.
* [CDC 2-FF](https://github.com/aignacio/soc_components/blob/master/cdc_2ff_sync.sv): General clock-crossing 2FF design.
* [AXI ROM wrapper](https://github.com/aignacio/soc_components/blob/master/axi_rom_wrapper.sv): General ROM wrapper design for auto-generated images.
* [Ethernet AXI](https://github.com/aignacio/ethernet_axi): Ethernet R/GMII wrapper design.
* [Bus arch pkg](https://github.com/aignacio/bus_arch_sv_pkg): SV packages for common AMBA interfaces.
* [RR arbiter](https://github.com/aignacio/rr_arbiter): Generic Round-Robin arbiter.
* [CDC components](https://github.com/aignacio/cdc_components): Generic clock-crossing designs.
* [MPSoC example design](https://github.com/aignacio/mpsoc_example): Multi-Processor System-on-Chip example design with 100x RISC-V (VeX) cores.
* [Test of HWACHA Vector accel](https://github.com/aignacio/hwacha_vvadd_benchmark): Test of hwacha vector design for rocket-chip.
* [IIR Filter](https://github.com/aignacio/iir_filter): Simple Infinite impulse response (IIR) in verilog.
* [PCIe small design](https://github.com/aignacio/pcie_example): PCIe example project for Xilinx FPGAS.
* [RISC-V SoC model](https://github.com/aignacio/riscv_verilator_model): Generic SoC using RI5CY CPU.
* [Cocotb template repo](https://github.com/aignacio/cocotb_design_playground): Template repository to test designs using cocotb framework.
  
## <a name="tools"></a> Tools

* [Cocotbext-AHB](https://github.com/aignacio/cocotbext-ahb): AHB Bus driver for Cocotb cosimulation framework.
* [IPSoCGen](https://pypi.org/project/ipsocgen/): MP/SoC generation framework built in python.
* [IPSoCGen Template](https://github.com/aignacio/ipsocgen_template): Reference design repository for the [IPSoCGen](https://pypi.org/project/ipsocgen/) framework.

## <a name="sw"></a> Software (Embedded/Linux...)

* [NoX FreeRTOS port](https://github.com/aignacio/nox_freertos): Port of FreeRTOS for [NoX](https://github.com/aignacio/nox) CPU.
* [MQTT-SN port for 6lowpan](https://github.com/aignacio/homestark_mqtt_6lowpan_port): MQTT-SN port for the 6lowpan for ARM Tiva series from TI.
* [Bootloader for NoX CPU](https://github.com/aignacio/nox/tree/master/sw/bootloader): Simple bootloader using UART as interface to transfer program files.
* [Bootloader script in python](https://github.com/aignacio/nox/blob/master/sw/bootloader_elf.py): Complementary bootloader script in python to transfer .elf files.
* [MPSoC examples - Histogram, Filter...](https://github.com/aignacio/ipsocgen_template/tree/mpsoc_filter/sw): Few examples for MPSoCs apps running on FreeRTOS.


