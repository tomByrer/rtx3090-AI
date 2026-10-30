# rtx3090-AI
Link farm &amp; notes for using RTX3090 for AI

## inference engines

## MOE

* https://github.com/VecSzn/PolyStrata/ [Strata](https://github.com/Niko1221/Strata) fork for several MoE models

### Qwen3.8-Flash-Next

 * https://github.com/Niko1221/Strata 12-24GB VRAM,  + 64GB sRAM, [prep helper](https://www.reddit.com/r/LocalLLM/comments/1xdkrt4/a_small_helper_to_run_your_own_qwen38flashnext/)

## dense

### Qwen3.8-27B+
(Maybe other models, & sometimes they have their own quants/finetunes)
 * https://github.com/iamwavecut/ninfer-all: NInfer for the RTX3090+t: GGUF block formats, ternary Bonsai 2, device route profiles, MTP and DFlash2
 * https://github.com/syv-ai/HyperQwen
 * https://github.com/JakeATX/llamAmpere
 * https://github.com/signalnine/q27 3090+Apple, author works at NVIDIA, used by [potemkin](https://github.com/signalnine/potemkin
 * https://github.com/Don-Chad/ninfer-3090
 * https://github.com/sybil-solutions/trellis-serve SGLang serving [EXL3](https://github.com/turboderp-org/exllamav3) quants for 3090 & B70

#### (too immature)
 * https://github.com/magnitudedev/magnitude
 * https://github.com/BlockWayz/agens-engine [heavily customized model](https://huggingface.co/Blockway/Agens-Volundr-32B-v1)

#### (not updated frequently)

 * https://github.com/Sandermage/sndr_core_engine
 * https://github.com/noonghunna/club-3090/)
 * https://github.com/r0b0tlab/qwen38-exl3-dflash2 DFlash2 for [ExLlamaV3](https://github.com/turboderp-org/exllamav3/tree/master), 262k context

### Models/finetunes/quants

#### Qwen3.8-27B

 * https://huggingface.co/ukisai/Swift-Qwen3.8-27B-GGUF [Reddit](https://www.reddit.com/r/LocalLLaMA/comments/1wrv6bp/swift_15_qwen38_27b_a_musthave_for_low_thinking/)
 * https://huggingface.co/Wa1k3r/Qwen3.8-27b-CODER-4q_xs-24GB-262k-Optimalcardfit#how-lexipanel-made-it fitted by LexiPanel
 * [Qwen3.8 27B GSQ-RCO IQ3_S for 16GB VRAM](https://www.reddit.com/r/LocalLLaMA/comments/1wzfv45/just_my_how_i_run_qwen38_27b_on_16gb_experience/) 

 #### small

  * https://huggingface.co/bartowski/MiMo-V2.6-Distill-Qwen-9B-GGUF
 

## tools

 * [LexiPanel](https://github.com/W61k3r/LexiPanel#lexipanel) captures local traffic to tune quants & engines
 * ROCm Strata for EXL3 quant https://github.com/nasone32/Strata-EXL3-fork

.
 
