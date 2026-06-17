# 1  Safety

## 1.1 Emergency Stop Devices

Three emergency stop devices are installed on the Applicator: two on the
machine frame and one on the FEED-Z CONVEYOR (option). When pressed, any
device removes all motion from the Applicator. To reset, twist the actuator
clockwise 90 degrees until it releases.

After an emergency stop, wait a minimum of 1 minute before restoring control
power to allow all drive protection circuits to reset.

<figure markdown>
  <div class="figure-placeholder">Figure 1.1  Emergency Stop Locations</div>
  <figcaption>Figure 1.1  Emergency Stop Locations</figcaption>
</figure>

For the status of all emergency stop devices and guard switches, navigate to
the Safety PLC screen on the OI. See
[Section 12: OI Reference](12-oi-reference.md#safety-plc-screen).

---

## 1.2 Guard Switches

Seven safety guard switches are monitored by the safety PLC. The Applicator
will not run if any guard is open or removed.

| **Switch** | **Location** |
|---|---|
| ENTRY | Entry guard |
| MIDDLE | Middle guard |
| EXIT | Exit guard |
| PORTION 1 | Portion belt assembly |
| PORTION 2 | Portion belt assembly |
| SPINNER | Spinner area |
| HOPPER | Hopper area |

<figure markdown>
  <div class="figure-placeholder">Figure 1.2  Guard Switch Locations</div>
  <figcaption>Figure 1.2  Guard Switch Locations</figcaption>
</figure>

---

## 1.3 Safe State Definition

Pressing an emergency stop device or opening any guard switch places the
Applicator in a safe state. The following occur automatically:

- All motion commands are removed. Motors coast to stop.
- The RETRACTABLE CONVEYOR servo drive is disabled.
- The MACHINE ENABLE circuit must be reset before operation can resume.
  See [Section 3: Startup](03-startup.md).

!!! warning
    **Emergency stop devices are for emergency conditions only.**
    Repeated use as a normal stop degrades electronic components and drive
    protection circuits. For normal shutdown, use the STOP button on the OI.

!!! note
    Always use Lock-out/Tag-out procedures before removing any guard for
    maintenance or cleaning. See the machine safety placard for site-specific
    LOTO requirements.
