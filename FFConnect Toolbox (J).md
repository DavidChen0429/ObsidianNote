Label: Journal
Goal:
* Enable implementation of farm-level control strategy in FAST.Farm in an iterative way

To do:
* [x] Expand Super Controller to include IPC 
* [x] Test IO passage correct
	* [x] yaw
	* [x] pitch
	* [x] torque
	* [x] output
	* [x] collective pitch
* [x] from global flag to per-turbine flag
* [x] expand fixed-bottom controller to include IPC
	* [x] DISCON
	* [x] SC_DLL 
* [x] Expand super controllers to include sufficient variables (QBlade as reference)
	* [x] DISCON 
	* [x] DISCON OC3
	* [x] SC DLL
	* [x] ffconnect interface
	* [x] test
		* [x] fixed-bottom (IPC does not work)
		* [x] floating
		* [x] Azimuth (reduce DT = 1)
* [x] Ensure higher resolution simulation
* [x] Expand to entire averMatrix
	* [x] Supercontroller (DISCON, DISCON_OC3, SC_DLL)
	* [x] Interface
	* [x] Test
* [ ] Read through the readme & claude
* [ ] Make it user-friendly