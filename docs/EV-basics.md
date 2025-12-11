1. What an Electric Vehicle Really Is

Electric vehicles (EVs) may look similar to traditional cars from the outside, but internally they are much simpler.
There are fewer moving parts, no engine oil, no gear shifting — just electricity flowing through a motor.

A very simple EV flow looks like this:

Battery Pack → Inverter → Electric Motor → Wheels
                    ↑
              On-board Charger


This simplicity is one reason why EVs are reliable and ideal for autonomous robotaxi systems.

2. Core Components (Humanised Explanations)
🔋 Battery Pack (kWh)

The battery is the “fuel tank.” Its capacity (kWh) tells us how much energy the EV can store.
Example: A 60 kWh battery can output 60 kW for 1 hour, or 10 kW for 6 hours.

🧠 Battery Management System (BMS)

The BMS is the battery’s “brain.”
It continuously monitors:

State of Charge (SOC)

Temperature

Safety limits

Cell balancing

Without a BMS, batteries would degrade quickly or even become unsafe.

⚡ Inverter

The inverter converts the battery’s DC power into AC power for the motor.
It also manages regenerative braking:

During acceleration: Battery → Motor
During braking:      Motor → Battery

🌀 Electric Motor

Provides instant torque, smooth acceleration, and high efficiency — key traits for robotaxi fleets.

🔌 On-board Charger

When using AC charging (home or public AC chargers), this unit converts AC into DC for the battery.

🌡️ Thermal Management

Keeps the battery between 20–40°C, maintaining:

safety

performance

longer battery life

This is especially important for robotaxis operating continuously.

3. Key Terms You Must Know
State of Charge (SOC)

Percentage of battery available (similar to a phone battery %).

Consumption (kWh/km or kWh/100 km)

Energy needed to drive 1 km.
Lower consumption = more range.

Regenerative Braking

Energy recovered when slowing down.
Robotaxis in cities can recover 10–25% extra energy.

Usable Battery Capacity

Not the whole battery is available.
A 64 kWh pack may offer 58 kWh usable to protect battery health.

4. Important EV Formulas
Range Estimate
Range (km) = Usable Battery (kWh) / Consumption (kWh per km)

Energy Needed for a Trip
Energy (kWh) = Distance × Consumption

5. Example Calculation

Robotaxi prototype assumptions:

60 kWh usable battery

0.15 kWh/km consumption

Range:

Range ≈ 60 / 0.15 = 400 km


For a 50 km trip:

Energy used = 50 × 0.15 = 7.5 kWh
Remaining battery ≈ 52.5 kWh


These calculations are exactly what your simulation notebook will test.

6. Why This Matters for Robotaxi Systems

Understanding EV fundamentals helps you:

simulate battery % vs distance

predict operational hours

design charging strategies

compare EV platforms scientifically

communicate with engineers effectively

A robotaxi’s uptime, cost, and efficiency all depend on these factors.

7. References

TU Delft — Electric Cars: Introduction

U.S. Department of Energy — AFDC

Tesla Powertrain Overview

Nissan Leaf Technical Guide

Bosch EV Component Notes

