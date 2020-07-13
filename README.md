# screeps-foreman-bench
Benchmarking and experimentation tool for screeps-foreman.

# Usage
1. Edit main.rs to use correct shard and rooms. (TODO: Needs to be parameterized.)
2. Set desired logging level with: 'set RUST_LOG=<level>' i.e. 'set RUST_LOG=debug'.
3. Run using 'cargo run --release'
4. Output is placed in to the 'output folder' by room name. 
5. Plan json can be visualized in room planner here: https://screeps.admon.dev/
