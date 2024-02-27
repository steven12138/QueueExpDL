# Deep Learning Agent

This project is goal to development a Simple Deep Learning Experiment Queuing System.

it should allow you to:

1. Registry your job, create a job template.
   - CLI interface
   - auto detect  conda environments
   - define code home directory and the entry-point(Startup command).
   - YAML-based configuration file.
2. Fetch the unfinished job from the Master node, auto execute based on some predefined strategy.
   - Graphics card occupied status detect, only execute when left memory over the threshold
   - Concurrency Limit
   - Only Runs on Predefined Graphics card
   - Priority defines
3. Idle graphics card notification.
   - Email
   - Web-Hook
4. Beautiful Web-based Dashboard

**Principle:**

- Simple, light-weight. used combined with some experiment management tools like `wandb` and`mlflow`.
- Easy to use, ergonomically designed panel and CLI 

## Development Progress:

Daily Update:

### 2024-02-28

Initial this Project, Set my goal.
