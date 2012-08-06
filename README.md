# Check bandwidth plugin for Nagios

## Options

```
-iface/--interface)
   Interface name (eth0 by default)

-w/--warning)
   Warning value (KB/s)

-c/--critical)
   Critical value (KB/s)
```

## Usage

```bash
check_bandwidth -iface eth0 -w 5000 -c 6000
```