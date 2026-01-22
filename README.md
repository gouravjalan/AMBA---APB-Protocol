# AMBA---APB-Protocol
The APB protocol is a low-cost interface, optimized for minimal power consumption.
The APB interface is not pipelined and is a simple, synchronous protocol. 
Every transfer takes at least two cycles to complete. 
APB peripherals are typically connected to the main memory system using an APB bridge. For example, a bridge from AXI to APB could be used to connect a number of APB peripherals to an AXI memory system.
APB transfers are initiated by an APB bridge, which can also be called as "Requester" & APB Peripherals are also called as "Completer".
