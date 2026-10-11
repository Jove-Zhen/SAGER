# SAGER

Community reimplementation of SAGER for studying per-user reasoning skills in recommendation agents.

## Paper

**Personalizing How Recommendation Agents Reason: Self-Evolving Per-User Skills for Recommendation Agents**

EMNLP 2026

The [arXiv preprint](https://arxiv.org/abs/2604.14972) is available under the earlier title, *SAGER: Self-Evolving User Policy Skills for Recommendation Agent*.

Conference paper link: pending.

## Abstract

Recommendation agents often keep user-specific memories while applying the same reasoning rules to everyone. SAGER represents each user's decision policy as an evolving set of natural-language skills. Feedback from interactions is used to revise those skills, so personalization affects how candidates are compared as well as which preferences are remembered. A compact skill representation is then supplied to the agent during recommendation.

## Method

- Maintain a per-user policy skill alongside the interaction history.
- Compare chosen and unchosen items to diagnose reasoning errors and update the skill while retaining useful prior rules.
- Inject the condensed skill into listwise reasoning over recommendation candidates.

## Code

The implementation is in preparation. Code and running instructions will be added soon.

## Citation

The citation below is for the arXiv version.

```bibtex
@article{tao2026sager,
  title={SAGER: Self-Evolving User Policy Skills for Recommendation Agent},
  author={Tao, Zhen and Lai, Riwei and Yu, Chenyun and Chen, Weixin and Chen, Li and Kong, Beibei and Cheng, Lei and Zhuo, Chengxiang and Li, Zang and Sun, Qingqiang},
  journal={arXiv preprint arXiv:2604.14972},
  year={2026},
  url={https://arxiv.org/abs/2604.14972}
}
```
