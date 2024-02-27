# Deep Learning Agent

This project is goal to development a Simple Deep Learning Experiment Queuing System.

it should allows you to:

1. Registry your jobs, create a job template.
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

## Development Progress:

Daily Update:

### 2024-02-28

Initial this Project, Set my goal.
