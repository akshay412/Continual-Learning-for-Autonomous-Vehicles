# Continual Learning for Autonomous Vehicle Steering

This repository contains the implementation of a continual learning system for autonomous vehicle steering control, developed as part of a project at New York University from January to May 2024.

## Project Overview

We explored and implemented various continual learning algorithms to improve steering control in autonomous vehicles, with a focus on enhancing prediction accuracy and drive smoothness while reducing memory usage.

## Features

- Implementation of multiple continual learning algorithms:
  - Elastic Weight Consolidation (EWC)
  - Experience Replay Buffer
  - Novel Temporal Consistency Regularization (TCR) with balanced buffer
- VisualBackProp implementation for feature importance visualization
- Steering control prediction model

## Temporal Consistency Regularization (TCR)

Our main innovation is the Temporal Consistency Regularization technique. TCR uses a balanced buffer taking advantage of the temporal nature of the problem to enhance prediction accuracy and drive smoothness. This method significantly outperformed traditional approaches in our tests.
