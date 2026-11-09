# Split-KB — Wireless Split Keyboard

A low-profile wireless split keyboard with 21 Kailh Choc keys per half
(5×4 grid + 1 thumb key), built on Hack Club Blueprint's split keyboard guide.
Each half runs a Seeed XIAO nRF52840 over Bluetooth with its own LiPo battery,
charged over USB-C, with battery level reporting through a voltage divider.
Hotswap sockets let switches be swapped without soldering, and both halves
are made as one panel that snaps apart along mousebites.

Firmware: ZMK (in this repo — `boards/`, `config/`, `build.yaml`).

BOM
Part	Qty	Cost	Seller	Link
Seeed XIAO nRF52840	2	$19.80	Seeed Studio	link
Kailh Choc V1 switches	42	$25.20	Keebio	link
Choc hotswap sockets (10-pack)	5 packs	$12.50	Adafruit	link
Choc V1 blank keycaps	42	$6.30	Keebio	link
1N5819HW diode, SOD-123	60	$1.77	LCSC	link
806kΩ + 2MΩ resistors, 0805	2 each	~$1 (est.)	LCSC	search “806k 0805” / “2M 0805”
301230 LiPo battery, 110mAh	2	$13.98	Keebmaker	link
M2 heat-set inserts (150 pcs)	1 pack	$8.98	Amazon	link
M2×5 screws	10	~$6 (est.)	Amazon	any M2×5 socket-head kit
PCB panel (233×89 mm, 2-layer, 5 pcs)	1 order	~$15–25 (est.)	JLCPCB	jlcpcb.com (upload Gerbers for an exact quote)
Case print (2 trays)	1	~$10–20 (est.)	JLC3DP / local	depends on printer
