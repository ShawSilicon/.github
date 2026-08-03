# ShawSilicon

**Proof of skill for engineering hiring, now that every resume is written by a model.**

For thirty years hiring ran on a document, because faking one convincingly took effort, and that effort was the filter. That effort is now zero. A perfect resume is evidence of access to a language model and nothing else, and every screening process still standing on that document sorts *for* people who write well about work and *against* the people who do it.

We replaced the document with evidence.

---

## How it works

Engineers complete a four-stage technical screen in their own specialization:

| Stage | What it tests |
|---|---|
| **1. Concepts** | Specialization fundamentals a resume cannot carry |
| **2. Work sample** | Applied evidence in their own discipline |
| **3. Design diagram** | They draw it, which exposes structural reasoning |
| **4. Recorded defence** | They defend that design under questioning, on camera |

Scored against a fixed rubric across five dimensions. A senior FPGA engineer reviews the recorded defence. The output is an anonymized scorecard, so employers see scored evidence before they see a name and before they spend a principal engineer's afternoon.

300 questions across the 9 specializations engineers can select: FPGA, ASIC/RTL, verification and UVM, formal verification, physical design, analog and mixed-signal, embedded hardware, AI chip architecture, and DFT.

**Engineers pay nothing. Ever.**

---

## Why the failure rate is the product

**30 engineers have completed the screen. 13 did not clear the bar.**

A screen almost everyone passes is a participation trophy. That failure rate is the only evidence the instrument discriminates, and it is why a passing scorecard is worth reading.

10 engineers are verified and live right now.

The full data, the method, and an honest account of what we cannot yet measure: **[screening-benchmark](https://github.com/ShawSilicon/screening-benchmark)**

---

## Why this is not an opinion

Operational validity for predicting job performance, from Sackett, Zhang, Berry and Lievens (2022), *Journal of Applied Psychology* 107(11), Table 3:

| Method | Validity |
|---|---|
| Structured interview | **.42** |
| Job knowledge test | **.40** |
| Work sample | **.33** |
| Unstructured interview | .19 |
| **Years of experience** | **.07** |

The two signals hiring trusts most are the two weakest ever measured. ShawSilicon is a structured interview plus a work sample plus a job knowledge probe, which is the top three rows, assembled, for a vertical nobody had instrumented.

And judgment does not rescue it. Combining identical candidate data by rule rather than by judgment predicts performance at .44 versus .28, better than 50% more accurate, and the loss happens even among experts who know the job and the company (Kuncel, Klieger, Connelly and Ones, 2013, *JAP* 98(6), Table 2).

---

## Working with us

**Hiring?** Browse anonymized scorecards, request an introduction through the consent gate. → [shawsilicon.ai](https://shawsilicon.ai)

**Need a second read before signoff?** Fixed-scope RTL audits at $9,995. One block, latency and correctness findings tied to real synthesis, simulation and executed-assertion evidence, delivered in a written format you can forward without translation. → [shawsilicon.ai/fpga-audit](https://shawsilicon.ai/fpga-audit)

**An engineer?** Prove it once. It travels. → [shawsilicon.ai](https://shawsilicon.ai)

---

## The engineering behind it

ShawSilicon was built by a practising FPGA engineer, and the open-source work is public and reproducible:

- [cxl-type3-formal-signoff](https://github.com/taitashaw/cxl-type3-formal-signoff) -- PCIe Gen5 / CXL Type-3 datapath verified to formal signoff. Unbounded k-induction, plus 85 deliberate RTL mutations to confirm the proofs fail when the design is wrong.
- [cxl-kv-forge-qos](https://github.com/taitashaw/cxl-kv-forge-qos) -- Multi-tenant LLM KV-cache QoS controller. 400 MHz post-route, WNS +0.033 ns, 0 of 77,540 endpoints failing.
- [fpga-ai-accelerator](https://github.com/taitashaw/fpga-ai-accelerator) -- INT8 systolic array, RTL to bitstream. 784 of 784 outputs matched across three simulators.
- [rtl-latency-audit](https://github.com/taitashaw/rtl-latency-audit) -- The audit method, demonstrated publicly on Corundum's PCIe Gen3 DMA engine.

Full portfolio: **[github.com/taitashaw](https://github.com/taitashaw)**

---

<sub>ShawSilicon Inc. Toronto, Ontario, Canada. john@shawsilicon.ai</sub>
