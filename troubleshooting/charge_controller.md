Charge Controller NOT charging: Symptoms are there IS sun and NO led lights.
===========================================================================

Before you start, double check all breakers to make sure NONE are tripping. If one is tripping, there is a system fault that needs to be addressed. Turn OFF the system breaker before proceeding with the following workflow.


##  1. Check Battery Terminals
--------------------

* Check polarity
  - Polarity WRONG: Investigate and fix wiring from Battery to Charge Controller. WARNING: This condition could result in damage to wire and systems. Check over system before reconnecting. This is unlikely unless this is the initial state of installation.
  - Polarity OK: Check Voltage
    - Under 11.85v
      - NO Voltage: Likely cable problem. Trace cabling and fix.
      - 1v-11.85v: Batteries are below minimum functioning level. Allow charger to recharge to 12v before turning on. If charger is not working, connect charged 12v in parrellel.
    - Over 12.5v: Voltage appears to be OK. Problem likely on PV / solar side. If not. Charge controller could be bad.

## 2. Check PV Terminals
---------------

* Check polarity
  - Polarity WRONG: Investigate and fix wiring from Solar Panels. WARNING: This condition could result in damage to wire and systems. Check over system before reconnecting. This is unlikely unless this is the initial state of installation.
  - Polarity OK: Check PV Voltage
    - Voltage is below 17v (during sun)
      - Check panels for dust: clean
      - Check wiring for loose connections: reset all connections
      - Check wire for damage replace or repair
      - Check panels for damage: replace or repair. Note, a panel can be disconnected and the system should continue to charge without the damaged panel being connected.
    - Voltage is over 21v (should be ~30v). PV voltage appears to be OK. If PV voltage is over 21v, battery side is ok (above) and charge controller is not charging, The likely problem is the charge controller. Replace charge controller.