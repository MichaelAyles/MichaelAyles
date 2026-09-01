# Mike Ayles

Head of Product Development at addvantage Global (Tribune Group). We build dual-fuel diesel-LPG conversion systems for commercial fleets. I run hardware, embedded firmware, data systems and homologation: ASIL B ECUs on S32K, CAN/J1939, MISRA C. Approaching 30 million miles deployed. Co-inventor on a combustion efficiency patent.

Background is sport science. Got into embedded by accident in 2014. Self-taught from there.

## Currently

**[On-chip LLM on a $250 FPGA](https://mikeayles.com/blog/on-chip-llm-kv260/).** A 3.16M-parameter INT4 transformer running entirely in the on-chip memory of a Kria KV260. Zero DRAM in the token loop, ~60k tok/s on the fabric, bit-exact against the reference. You can [chat with it live](https://chat.mikeayles.com). Five-part writeup covering the datapath, the serving stack, and the things that went wrong.

**FPGA stereo depth camera** targeting ISO 13849 PLd Cat 3 for collaborative robotics. Custom SGM in Verilog on the same K26, OV9281 cameras, R5 lockstep safety monitor. Not public yet.

**[Phaestus](https://phaestus.app).** Built for the Gemini 3 hackathon. Free-form LLM hardware design didn't hold up, so I constrained the model to assembling fixed, pre-verified design blocks instead. That worked well enough to manufacture a battery powered BLE remote: two PCBs, power management, 3D printed enclosure and firmware.

## Things that escaped onto the internet

- [KiDOOM & ScopeDOOM](https://mikeayles.com/blog/kidoom/). DOOM wireframe renderer implemented in KiCad, with a side quest through a MacBook headphone jack onto an oscilloscope. #1 on Hacker News for the best part of a day, picked up by [Hackaday, Tom's Hardware, Adafruit and others](https://mikeayles.com/featured/kidoom/).
- [CircuitSnips](https://circuitsnips.com). Shareable KiCad subcircuits. Thingiverse, but for electronics.
- [TOKN](https://mikeayles.com/blog/tokn). Token-Optimised KiCad Notation. Schematic compression format for LLM context, 92% token reduction, with benchmark suite.
- [bitwise-mcp](https://github.com/MichaelAyles/bitwise-mcp). MCP server that ingests 1000-page reference manuals and serves register definitions to coding agents without eating the context window.
- [search-bench](https://mikeayles.com/blog/rag-coding-tools/). Does RAG actually help coding agents? Benchmarked Claude Code and Copilot across 60 queries. Retrieval quality barely moved, token use dropped ~23%.
- [goformer](https://pkg.go.dev/github.com/MichaelAyles/goformer) & [goformersearch](https://pkg.go.dev/github.com/MichaelAyles/goformersearch). BERT inference and HNSW vector search in pure Go. Built to see what I could do in Go. Outperformed by ONNX and FAISS on every metric, but it's neat, it works and has zero deps.

[mikeayles.com](https://mikeayles.com) for longer writing. [LinkedIn](https://linkedin.com/in/mayles). mike@mikeayles.com.