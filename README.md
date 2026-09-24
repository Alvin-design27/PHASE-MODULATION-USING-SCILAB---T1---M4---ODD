8# PHASE-MODULATION-USING-SCILAB---T1---M4---ODD


## Aim
To implement and analyze Phase Modulation (PM) using Scilab.

## Apparatus Required
1. **Software:** Scilab environment
2. **Hardware:** Personal Computer

---

## Theory
Phase Modulation (PM) is a technique where the phase of the carrier wave is varied in proportion to the instantaneous amplitude of the input signal (message signal). Unlike Frequency Modulation (FM), where the frequency is varied, in Phase Modulation, the phase angle of the carrier wave changes with the amplitude of the message signal.

### Mathematical Representation
The general form of a Phase Modulated signal $s(t)$ is given by:

$$s(t) = A_c \cos(2\pi f_c t + k_p m(t))$$

Where:
* $A_c$ : Amplitude of the carrier wave
* $f_c$ : Carrier frequency
* $m(t)$ : Message signal, typically $m(t) = A_m \cos(2\pi f_m t)$
* $k_p$ : Phase deviation sensitivity (in radians/volt)

---

## Algorithm
1. **Initialize Parameters:**
   * Define carrier amplitude ($A_c$), carrier frequency ($f_c$), message frequency ($f_m$), sampling frequency ($f_s$), and phase sensitivity ($k_p$).
2. **Generate Time Axis:**
   * Create a time array $t$ with suitable sampling steps over the signal duration.
3. **Generate Message Signal:**
   * Compute the message signal vector $m(t)$ using the cosine function.
4. **Generate Carrier Signal:**
   * Compute the unmodulated carrier signal vector $c(t) = A_c \cos(2\pi f_c t)$.
5. **Generate PM Signal:**
   * Compute the phase-modulated signal $s(t) = A_c \cos(2\pi f_c t + k_p m(t))$.
6. **Plot the Signals:**
   * Use Scilab's plotting commands (`subplot`, `plot`, `xtitle`, `xgrid`) to display message, carrier, and modulated signals.
  
# TABULATION
<img width="1280" height="662" alt="image" src="https://github.com/user-attachments/assets/308d71ba-100a-45e6-9715-47f8f0ef65d0" />

# CALCULATION
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/e0707017-9c5b-4bf1-9e6c-201ac0186d71" />

# GRAPH
<img width="1280" height="714" alt="image" src="https://github.com/user-attachments/assets/ff695be3-9d10-40cb-8067-2ca480601830" />

# CODE
<img width="1063" height="974" alt="image" src="https://github.com/user-attachments/assets/26ea7628-6356-4cd3-8d5f-aad672e4b4ef" />
<img width="1080" height="946" alt="image" src="https://github.com/user-attachments/assets/8158e7bf-4fe8-4508-82c9-782787b209e5" />

# MARK SPLIT-UP
<img width="1045" height="537" alt="image" src="https://github.com/user-attachments/assets/35459ace-e017-4f55-bb2b-5edd2a4208d1" />

# RESULT
<img width="1080" height="515" alt="image" src="https://github.com/user-attachments/assets/0175641e-f27d-4744-a6e3-0789395f79df" />
