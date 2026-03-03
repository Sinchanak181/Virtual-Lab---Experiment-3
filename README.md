# EXPERIMENT – 03  
## Characteristics and Parameters of IC 741 Operational Amplifier

---

## 🎯 Aim

To study and determine the following parameters of IC 741 operational amplifier:

- Input Bias Current (Inverting Terminal)
- Input Bias Current (Non-Inverting Terminal)
- Input Offset Current
- Input Offset Voltage
- Slew Rate

---

## 🧰 Components Required

- IC 741 Op-Amp
- Breadboard
- DC Power Supply
- Function Generator
- CRO (Cathode Ray Oscilloscope)
- Digital Multimeter
- Resistors
- Capacitors
- Connecting Wires

---

## 📖 Theory

An operational amplifier (Op-Amp) is a high gain differential amplifier that amplifies the voltage difference between two input terminals.

### Internal Functional Blocks

1. **Input Stage** – Differential amplifier with high input impedance  
2. **Intermediate Stage** – Provides additional gain  
3. **Level Shifting Stage** – Adjusts DC level  
4. **Output Stage** – Push-pull amplifier with low output impedance  

---

## 📌 Ideal Characteristics

- Infinite Voltage Gain  
- Infinite Input Resistance  
- Zero Output Resistance  
- Infinite Bandwidth  
- Infinite CMRR  
- Zero Offset Voltage  

---

# 1️⃣ Input Bias Current (Inverting Terminal)

### Formula Used

IB = Vo / Rf

### Procedure

1. Connect the IC 741 as per circuit diagram.
2. Apply required DC supply.
3. Measure output voltage.
4. Calculate input bias current.

### 🔽 Circuit Screenshot

![Inverting Bias Current Setup](inverting_bias_current.png.jpg)

---

# 2️⃣ Input Offset Current

### Definition

Input offset current is the difference between bias currents at two input terminals.

Iio = | IB1 − IB2 |

### Formula

Iio = Vo / Rf

### 🔽 Circuit Screenshot

![Input Offset Current Setup](input_offset_current.png.jpg)

---

# 3️⃣ Input Offset Voltage

### Definition

Input offset voltage is the small DC voltage required between input terminals to make output zero.

For IC 741:
Maximum Vio ≈ 6mV

### Procedure

1. Configure the circuit.
2. Adjust potentiometer to null output.
3. Measure voltage across input terminals.

### 🔽 Circuit Screenshot

![Input Offset Voltage Setup](input_offset_voltage.png.jpg)

---

# 4️⃣ Slew Rate

### Definition

Slew Rate (SR) is the maximum rate of change of output voltage.

SR = (dVo/dt) max

Unit: V/µs

For IC 741:
Typical SR ≈ 0.5 V/µs

### Procedure

1. Apply square wave input.
2. Observe output on CRO.
3. Measure rise time.
4. Calculate slew rate.

SR = ΔV / Δt

### 🔽 Circuit Screenshot

![Slew Rate Setup](slew_rate.png.jpg)

![Slew Rate Setup](slew_rate1.png.jpg)

---

## 📊 Result

The parameters of IC 741 such as input bias current, input offset current, input offset voltage and slew rate were measured successfully. The obtained values are approximately close to the standard datasheet values.

---

## ✅ Conclusion

The characteristics and performance parameters of IC 741 operational amplifier were studied and verified using virtual lab simulation. The experimental results validate the theoretical concepts of operational amplifier operation.

---

## 📎 References

- IC 741 Datasheet
- Virtual Lab Simulation
