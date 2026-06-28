# N × 1 Multiplexer Simulation Using Icarus Verilog and GTKWave

| Details | Information |
|---|---|
| **Student Name** | Pranjal Barnwal |
| **Roll Number** | THA079BEI021 |
| **Lab Assignment** | Design and Simulation of an N × 1 Multiplexer |
| **Tools Used** | Icarus Verilog (`iverilog`) and GTKWave |

---

## Objective

The objective of this assignment is to design and verify a parameterized **N × 1 Multiplexer** using Verilog HDL. The multiplexer selects one of **N** input signals based on the binary value of the select line and forwards it to the output. The design is simulated using **Icarus Verilog**, and the resulting waveform is analyzed using **GTKWave**.

---

## Simulation Waveform

<p align="center">
  <img src="image.png" alt="N x 1 Multiplexer GTKWave Output" width="1000"/>
</p>

**Figure:** GTKWave simulation of the **32 × 1 Multiplexer**. The `sel` signal increments sequentially from `0` to `30`, and the output `d_out` changes accordingly by selecting the corresponding 8-bit input value from the combined `data_in` bus. This verifies that the multiplexer correctly routes the selected input to the output for each valid selection.

---

## Conclusion

The parameterized **N × 1 Multiplexer** was successfully implemented and simulated using Verilog HDL. The GTKWave results confirm that the output follows the selected input for every valid value of the select line, demonstrating the correct functionality of the design.
