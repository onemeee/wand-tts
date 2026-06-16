# WAND: Windowed Attention and Knowledge Distillation for Efficient Autoregressive Text-to-Speech Models

Project page and audio samples for our paper.

- 📄 **Paper:** https://arxiv.org/abs/2604.08558
- 🔊 **Demo & samples:** https://onemeee.github.io/wand-tts/

WAND adapts pretrained AR-TTS models to operate with constant compute and memory by
combining persistent global attention over conditioning tokens with local sliding-window
attention over generated tokens, a window curriculum, and knowledge distillation from a
full-attention teacher. Evaluated on CosyVoice 2, IndexTTS, and Spark-TTS, WAND preserves
quality while achieving up to **66.2% KV-cache memory reduction** and near-constant per-step latency.

## Code

The implementation is being cleaned up and will be released here upon publication. Stay tuned.

## Citation

```bibtex
@inproceedings{lee2026wand,
  title     = {WAND: Windowed Attention and Knowledge Distillation for
               Efficient Autoregressive Text-to-Speech Models},
  author    = {Lee, Hanna and Nguyen, Tan Dat and Kang, Jaehoon and Shim, Kyuhong},
  booktitle = {Proc. Interspeech 2026},
  year      = {2026}
}
```
