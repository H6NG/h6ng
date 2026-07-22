```
   ┌─────────────────────────────────────────────┐
   │  $ whoami                                     │
   │  > hang liu — computer engineering @ ubc      │
   │  > status: fetch → decode → execute → repeat  │
   └─────────────────────────────────────────────┘
```

## // Hang Liu

I build things across the whole stack — and I mean the *whole* stack: from logic gates and RISC-V pipelines up through the OS, and out to the web app on top. I like the layer where software stops being an abstraction and starts being voltage.

Most of my curiosity lives in that gap between `1`s and `0`s and the thing the user actually sees.

```verilog
module hang (
    input  wire clk,
    output reg  learning
);
    always @(posedge clk)
        learning <= 1'b1;   // never gates off
endmodule
```

---

### `> tech.stack`

```text
LOW-LEVEL / HW   SystemVerilog · RISC-V · ARM64 asm · FPGA · Arduino · Questa · Quartus
SYSTEMS          C · C++ · Linux · Git
SOFTWARE         Python · Java · JavaScript · React · Node.js · Flask · MongoDB
ML / VISION      PyTorch · NumPy · OpenCV · MediaPipe
```

### `> currently`

```text
[x] getting RISC-V cores to behave on real silicon
[x] poking at CV pipelines with OpenCV + MediaPipe
[ ] sleep()                        // deprecated
[>] OPEN TO INTERNSHIPS — let's build something
```

---

### `> interrupt_handler`

Got a project at the hardware/software boundary? Raise an IRQ:

**[LinkedIn](https://www.linkedin.com/in/h4ng/)** · Vancouver, BC

```text
// 0x2A: I debug waveforms and CSS with the exact same face
```
