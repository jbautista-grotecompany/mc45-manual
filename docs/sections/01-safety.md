# 1  Safety

## 1.1 Emergency Stop Devices

The MC-45 Spot Depositor has two E-STOP push buttons located on the machine frame.
An additional E-STOP is located on the FEED-Z CONVEYOR (option). When pressed, any
E-STOP removes power from all devices capable of motion.

!!! warning
    **E-STOP is for emergencies only.**
    Repeated use of the E-STOP as a normal stop degrades electronic components. Use
    the STOP button on the OI to stop the Applicator during normal operation.

To reset an E-STOP: twist the button head clockwise 90 degrees until it releases.

After an E-STOP, wait a minimum of 1 minute before restoring control power to allow
all drive protection circuits to reset.

For E-STOP and guard switch status, refer to the **Safety PLC screen** in the OI.
See [Section 12: OI Reference](12-oi-reference.md#safety-plc-screen).

---

## 1.2 Guard Switches

The Applicator has seven safety guard switches monitored by the safety PLC. The
machine will not run if any guard is open or removed.

| **Switch** | **Location** |
|---|---|
| ENTRY | Entry guard |
| MIDDLE | Middle guard |
| EXIT | Exit guard |
| PORTION 1 | Portion belt assembly |
| PORTION 2 | Portion belt assembly |
| SPINNER | Spinner area |
| HOPPER | Hopper area |

!!! warning
    **Never bypass a guard switch.**
    Guards protect operators from moving belts, the retractable conveyor, and rotating
    assemblies. Always use Lock-out/Tag-out procedures before removing any guard for
    maintenance.

---

## 1.3 Lockout / Tagout

Before performing any maintenance, cleaning, or guard removal:

1. Press the E-STOP button.
2. Turn the ELECTRICAL DISCONNECT to the OFF position.
3. Lock the disconnect with a personal padlock.
4. Close the pneumatic isolation valve and lock it.
5. Verify all motion has stopped before proceeding.

---

## 1.4 General Safety Precautions

- Keep hands away from moving conveyor belts and rotating assemblies at all times.
- Load product in small amounts (3–5 kg / 6–11 lb) to avoid back injury.
- Use two people or mechanical assistance to lift heavy assemblies such as the BUCKET
  and SPINNER MOTOR.
- Do not stand or climb on the machine.
- The RETRACTABLE CONVEYOR moves at high velocity during operation. Never reach into
  the machine while it is enabled.
