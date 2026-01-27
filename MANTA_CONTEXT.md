# MANTA Project Context

## What we're building
Multi-turn Adversarial Testing for Animal welfare - testing if AI models 
maintain animal welfare principles under escalating pressure.

## Current status
- ✅ Generated adversarial scenarios (manta_scenarios.json)
- ✅ 2/3/4-turn conversations with economic/social/authority pressure
- 🔄 Need to run evals through Inspect AI and manually assess

## Files in this repo
- generate_followups.py - generates adversarial follow-ups
- manta_samples.json - sampled AHB questions
- manta_scenarios.json - full scenarios with turns
- manta_eval.py - Inspect AI evaluation tasks
- multiturn_solver.py - Custom solver for multi-turn conversations

## Technical setup
- Using Inspect AI framework
- Model: claude-sonnet-4-20250514
- Environment: /Users/allenlu/Desktop/AIxAnimals/WelfareBenchmarkingRepo/manta
- API Key: Stored in /Users/allenlu/Desktop/AIxAnimals/WelfareBenchmarkingRepo/.env

## Next steps
1. Run evals through Inspect AI (generates .eval files)
2. Manually review eval files in Jupyter
3. Look for what doesn't fit expectations
4. Build intuition before automating judgment