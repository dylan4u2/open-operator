# UI-TARS

## Overview
UI-TARS is an open-source autonomous agent system developed by ByteDance Seed & Tsinghua University that achieves state-of-the-art performance on the OSWorld benchmark.

## Key Features
- Multiple model sizes (7B and 72B)
- DPO and SFT training approaches
- Support for varying step lengths
- A11y tree based interaction

## Performance
### OSWorld Results
- UI-TARS-72B-DPO (50 steps): 24.6% (best overall)
- UI-TARS-72B-DPO (15 steps): 22.7%
- UI-TARS-72B-SFT (15 steps): 18.8%
- UI-TARS-7B-DPO (15 steps): 18.7%
- UI-TARS-7B-SFT (15 steps): 17.7%

## Technical Details
- Model Sizes: 7B and 72B parameters
- Training Methods: DPO (Direct Preference Optimization) and SFT (Supervised Fine-Tuning)
- Input: A11y tree based
- Step Configurations: 15 and 50 steps

## References
- Code: https://github.com/bytedance/UI-TARS
- Paper: [UI-TARS paper]