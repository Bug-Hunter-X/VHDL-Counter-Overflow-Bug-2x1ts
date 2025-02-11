# VHDL Counter with Overflow Bug
This repository demonstrates a common error in VHDL code: improper handling of counter overflow. The `buggy_counter.vhdl` file contains a counter that doesn't correctly reset when it reaches its maximum value under certain conditions. This can lead to unexpected behavior or simulation failures.

The `fixed_counter.vhdl` provides the corrected code.