<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/farex-ai/.github/main/profile/assets/wordmark-dark.svg">
    <img src="https://raw.githubusercontent.com/farex-ai/.github/main/profile/assets/wordmark-light.svg" alt="Farex" width="226" height="48">
  </picture>
</p>

<p align="center"><b>Test the route, not just the answer.</b></p>

<br>

More AI systems split work between specialists, with a router deciding who gets each task. Farex is an open-source tool for finding out what happens when that router picks wrong.

It runs every task through the right specialist and a wrong one, then shows you what the wrong route cost in success, latency and tokens.

- **Scored by the task.** Each answer is checked against the task's own requirements.
- **Reviewed blind.** Answers are marked on a blinded sheet before anyone sees a number.
- **Repeatable.** Inputs are frozen and hashed. A run refuses to start if anything changed.
- **Sandboxed.** Model-written code only runs in a locked-down container.

We're starting with specialist prompts on one local model. The goal is to test routing across multiple models and agents.

<sub>Early days. The tool is in <a href="https://github.com/farex-ai/farex">farex</a>, earlier experiments are in <a href="https://github.com/farex-ai/research">research</a>. MIT licensed.</sub>
