RUDDER efficiently learns optimal policies in finite Markov decision processes with delayed rewards.
With the following links you can find:
- Main repository: https://github.com/ml-jku/rudder
- Our RUDDER paper: https://arxiv.org/abs/1806.07857
- RUDDER blog: https://www.jku.at/index.php?id=16426
- Code for RUDDER demonstration on example-task in blog: https://github.com/ml-jku/rudder-demonstration-code
- A practical step-by-step guide to applying RUDDER in PyTorch: https://github.com/widmi/rudder-a-practical-tutorial

**Important: Deprecated version. Update to latest arxiv version coming soon. Please use the resources in our [main repository](https://github.com/ml-jku/rudder) in the meanwhile.**

# Baselines incl. RUDDER

Uses RUDDER on PPO to solve environments with delayed rewards. Our RUDDER paper is available at [https://arxiv.org/abs/1806.07857](https://arxiv.org/abs/1806.07857). 

**See https://github.com/widmi/rudder-a-practical-tutorial for a quick tutorial on reward redistribution using a pytorch implementation and code-snippets that you can run on your CPU.**

Our code is based on the [OpenAI Baselines](https://github.com/openai/baselines) package, in which we included our implementation of RUDDER for PPO for ATARI games with delayed rewards.
Additionally, the [Tensorflow Layer Library (TeLL)](https://github.com/bioinf-jku/tensorflow-layer-library) package (v1.0.0) is required for RUDDER.

RUDDER for PPO2 and documentation for the configuration is located in the folder [baselines/ppo2_rudder](baselines/ppo2_rudder).

Modified/new files:
- baselines/common/atari_wrappers.py
- baselines/common/distributions.py
- baselines/common/vec_env/vec_frame_stack.py
- baselines/ppo2_rudder/
- logger.py
- README.md

Videos are available at:

[![RUDDER - Venture](https://img.youtube.com/vi/CAcDkQsxjgA/0.jpg)](https://www.youtube.com/watch?v=CAcDkQsxjgA&index=2&list=PLDfrC-Vpg-CzVTqSjxVeLQZy3f7iv9vyY "RUDDER - Venture")

[![RUDDER - Bowling](https://img.youtube.com/vi/-NZsBnGjm9E/0.jpg)](https://www.youtube.com/watch?v=-NZsBnGjm9E&list=PLDfrC-Vpg-CzVTqSjxVeLQZy3f7iv9vyY "RUDDER - Bowling")
