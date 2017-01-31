**GPU Computing**

**27 October 2016**

**Limitations of CPU:**

* Power = Frequency * Voltage^2.

* Moore’s law says nothing about performance. It’s about the number of transistors in a chip.

**CUDA:**

* Programming language.

* Program runs on CPU but compute intensive parts are sent to GPU (explicitly).

* CUDA software model: grid of thread blocks. Each thread maps onto a CUDA core.

* CUDA introduces new types: dim2, dim3, dim4.

