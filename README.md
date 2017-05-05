# Lauda Eco Silver thermostat helper library

A small helper module to control the Lauda-Brinkman ECO Silver thermostat, 
commonly found in the CMAC Labs

Usage is fairly obvious:

'
    import lauda

    lauda.set_pumping_speed(lauda.PumpingSpeed.a_Typical)
    lauda.set_temp(25.0)
    lauda.start()

    current_temp_readout = lauda.read_current_temp()
'
