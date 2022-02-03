# Q-SYS CSS TimeMachines Clock (B Series)
Q-Sys User Component for the TimeMachines Synchronized Network Clock (B Series)
https://timemachinescorp.com/

-- Locator Protocol API version 1.0
    -- The request information response packet is 35 bytes and the "udp.Data = function(udp, packet)" function has been written based on this.
    -- API v1.0 is compatible with PoE clocks firmware v4.4 to v4.6.

-- Locator Protocol API version 2.0
    -- The request information response packet is 40 bytes. "udp.Data = function(udp, packet)" function updated when clock is on v4.8 firmware.
    -- Commands 'Execute Stored Program', 'Relay Close', 'Dimmer Set' and 'Color Set' were added to v2.0 of the API, requiring firmware update.
    -- 'Dimmer Set' on the B Series clocks doesn't support separate settings for brightness of the digits and the colons, just one overall brightness setting.

-- Maximum values that can be displayed on the Clock are 99:59:59:90:99 (HH:MM:SS:Tenths:Hundredths, Hex values: \x63\x3b\x3b\x09\x63)
