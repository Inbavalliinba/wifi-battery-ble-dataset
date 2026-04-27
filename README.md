 Battery CSV

Contains battery monitoring readings:

voltage – measured battery voltage values
rate_of_change – difference in voltage between consecutive readings
is_attack – binary label indicating normal (0) or attack (1)

 BLE CSV

Contains Bluetooth communication activity data:

adv_pkts_per_sec – number of advertising packets per second
conn_reqs_per_sec – number of connection requests per second
is_attack – binary label indicating normal (0) or attack (1)

 WiFi CSV

Contains wireless network performance metrics:

pps_mean – average packets per second
pps – packets per second
pps_var – variance in packet rate
bps – bits per second (data rate)
cpu_idle – percentage of CPU idle time
rssi_mean – average signal strength
rssi_var – variance in signal strength
label – binary label indicating normal (0) or attack (1)
