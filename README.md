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

![Op amp Symbol Setup](op_amp_symbol.png.jpg.png)

INTRODUCTION 
An operational amplifier is a direct coupled high gain amplifier usually consisting of one or more differential amplifiers and followed by a level translator and an output stage. The output stage is generally a push-pull or push-pull complementary-symmetry pair. An operational amplifier is available as a single integrated circuit package.
The operational amplifier is a versatile device that can be used to amplify dc as well as ac input signals and was originally designed for performing mathematical operations such as addition, subtraction, multiplication and integration. Thus, the word operational amplifier stems for its original use for these mathematical operations and is abbreviated to op-amp. With the addition of suitable external feedback components, the modern day op-amp can be used for a variety of applications, such as ac and dc signal amplification, active filters, oscillators, comparators, regulators and others

### Internal Functional Blocks

![Block Diagram Setup](block_diagram.png.jpg.png)

1. **Input Stage** – Differential amplifier with high input impedance  
2. **Intermediate Stage** – Provides additional gain  
3. **Level Shifting Stage** – Adjusts DC level  
4. **Output Stage** – Push-pull amplifier with low output impedance  

---

## 📌 Ideal Characteristics
Characteristics of an ideal op-amp:
An ideal op-amp would exhibit the following electrical characteristics:
• Infinite voltage gain A.
• Infinite input resistance Ri, so that almost any signal source can drive it and there is no loading of the preceding stage.
• Zero output resistance Ro, so that the output can drive an infinite number of other devices.
• Zero output voltage when input voltage is zero.
• Infinite bandwidth, so that any frequency signal from 0 to ∞ Hz can be amplified without attenuation.
• Infinite common-mode rejection ratio (CMRR), so that the output common mode noise voltage is zero.
• Infinite slew rate, so that output voltage changes occur simultaneously with input voltage changes.  

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
