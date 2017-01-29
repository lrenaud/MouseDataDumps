# MouseDataDumps


g102/ - Logitech G102 Data Dumps
	01_logoOn_s.pcap:
		turn on the led
	02_logoRed_s.pcap:
		set the LED color to red
	03_logoBlue_s.pcap:
		set the color to a blue-mix
	04_sleepTimer_60_30_s.pcap:
		modify sleep timer 60minutes, 30minutes
	11_logooff_logoon_s.pcap:
		turn off and on the LED
	12_brightness_zero_quarter_half_three_full_whileBreathing_s.pcap:
		change LED brightness in the breathing mode. 0% 25% 50% 75% 100%
	13_rate_min_quarter_half_three_max_reference_whileBreathing_s.pcap:
		change cycle rate from "minimum" to "max" in 25% steps
	14_sleepTimer_uncheck_recheck_s.pcap:
		turn off and on the sleep timer
	15_sleep_timer_0_1-9_15_25_30_s.pcap:
		change sleep timer to various times: 0,1,2,3,4,5,6,7,8,9,15,25,30 minutes
	16_lightOff_colorCycle_breathing_repeatAllThree_s.pcap:
		change LED mode: fixed, cycle, breath, fixed, cycle, breath
	17_setReportRate_min125_250_500_1000_s.pcap:
		change report rate 125Hz, 250Hz, 500Hz, 1KHz
	21_UnplugReplug_s.pcap:
		Disconnect mouse, and reconnect mouse, logitech software in background
	22_Plugin_Wait_StartLogitechSoftware_s.pcap:
		Physically connect, then sometime later start the logitech software
