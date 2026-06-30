<div align="center">

# ⚡ TNA-Power — Full PSU Intelligence for TNA-OS

**Real-time telemetry and control of your power supplies — built right into the firmware.**


</div>

---

## What is TNA-Power?

TNA-Power is a new capability coming to **TNA-OS** that lets your miner talk directly to its
power supply — reading live telemetry and taking control, all from the firmware you already run.
No extra hardware boxes, no external monitors, no guesswork.

Your PSU has always been a black box. TNA-Power opens it up.

---

## 📊 What you'll be able to see

Live, continuously, straight from the PSU's own brain:

| Reading | What it tells you |
|---|---|
| **Input voltage** | Your real mains voltage at the PSU |
| **Input current & power** | What you're actually pulling from the wall |
| **Output voltage** | The exact rail voltage feeding your miner |
| **Output current & power** | Real load on the supply |
| **Efficiency** | Input vs output — see where your watts go |
| **Temperatures** | Intake and internal PSU temps |
| **Fan speed** | Live RPM |
| **Energy used** | Cumulative watt-hours over time |
| **Peak / min history** | Worst-case current and power the PSU has seen |
| **Status & fault flags** | Health, alarms, protection trips |

All surfaced in TNA-OS — at a glance, logged over time, and available to your dashboards.

---

## 🎛 What you'll be able to control

TNA-Power isn't just a window — it's a steering wheel:

- **Fan control** — set PSU fan speed for quieter running or harder cooling
- **Power on/off** — enable and disable the PSU output directly from TNA-OS
- **Protection limits** — read and tune over-voltage / over-current thresholds
- **Calibration** — fine-tune readings to your exact unit
- **Reset counters** — clear peak/energy history on demand

---

## 🔌 Supported power supplies

TNA-Power launches with support for popular, affordable server-grade PSUs — the same
high-efficiency hardware data-centres trust, at a fraction of retail PSU prices:

- **HP HSTNS-PL11** (1200W, 80+ Platinum/Silver common-slot)
- **HP DPS-1200FB-A** (1200W)
- **HP DPS-750RB-A** (750W)

…with the architecture in place to add more models over time.

---

## 💡 Why it matters

- **Run cheap, efficient server PSUs with full visibility.** These supplies are 94%-efficient
  workhorses available used for a fraction of new mining PSUs — TNA-Power gives them the
  monitoring and control you'd expect from premium gear.
- **Catch problems before they cost you.** Live temps, fault flags, and efficiency trends mean
  you see a failing supply, a hot intake, or a sagging rail *before* it takes down a run.
- **Tune for your environment.** Dial fan speed for noise vs cooling, set protection limits,
  and calibrate to your hardware.
- **One pane of glass.** It's part of TNA-OS — no separate apps, no extra controllers.

---

## 🛠 How it works (in plain terms)

Every one of these PSUs has a small onboard microcontroller that the original server used to
monitor and manage it. TNA-Power speaks that controller's language directly over the existing
power connector — so TNA-OS reads and commands the PSU exactly the way an enterprise server
would, no modifications to the supply required.

We reverse-engineered the full communication protocol down to the firmware level, so the
support is complete and accurate — not just "read the voltage and hope."

---

<div align="center">

### Coming to TNA-OS

*Turn your power supply from a black box into a fully-monitored, fully-controlled part of your rig.*

**Built by **
*Nikos*

</div>
