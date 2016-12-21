# Constrained Devices

## What are constraints?

In order to save cost, engineers typically have to work within certain constraints, or limitiations. Typically these constraints break down into the following categories:

1. Network and Bandwidth
2. Power consumption
3. Computing resources (CPU, Memory, Storage)
4. Reliability (Uptime, Security, Real-Time, Rugged, Lifetime)

Constraints are also a matter of perspective. For a web developer used to developing complex Web Applications, having only 1 Megabyte of memory would be an unthinkable nightmare. However, for an embedded engineer developing small devices such as a motion sensor, thermometer, or coffee machine, a whole Megabyte may feel like a luxury!

For the sake of this discussion, I will make comparisons against the average PC or Smartphone of a few years ago, using the following specifications:

* **CPU:** A single or dual core CPU, >= 1GHz clock speed
* **RAM:** >=1GB
* **Storage**: 16-32GB of solid state storage (hard disk)
* **Network**: Wired ethernet or WiFi with >= 10Mbps connection
* **Power**: Connected to power all of the time, or at least once a day

Anything that has much less than this, I will consider a "constrained device", and anything near or above this limit, I will consider an "unconstrained device".

## Why are constraints necessary?

In a single word? Money.
