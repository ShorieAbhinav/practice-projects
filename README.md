# Practice Projects

Small, focused exercises for getting hands-on with new libraries, APIs, and workflows before combining them into bigger projects. Not portfolio-polished — the goal here is reps, not presentation.

## Areas

- **f1/** — FastF1 data pulling, quali vs. finish relationships, feature building for race prediction.
- **monte-carlo/** — simulating outcomes from probability distributions, building intuition before wiring a real model's output into a simulator.
- **ml/** — scikit-learn classifiers, regressors, the full train/test/fit/predict loop, feature importance.
- **data-cleaning/** — messy real-world datasets, handling missing values, normalization, outliers, reshaping.
- **quant/** — backtesting mechanics, signal generation, statistical tests (cointegration, z-scores), risk sizing (Kelly, etc.) in isolation before folding into live strategies.

## Roadmap

- [ ] **f1/01-fastf1-basics** — Pull a race session with FastF1, explore lap times, sectors, tire compounds, plot a stint's lap time degradation.
- [ ] **f1/02-quali-vs-finish** — Pull grid position vs. finish position across several races, plot the relationship, compute correlation.
- [ ] **ml/01-sklearn-classifier** — Train a RandomForestClassifier on historical race data to predict top-3 finishes.
- [ ] **monte-carlo/01-warmup** — Pure NumPy exercise: simulate a race 10,000 times from fixed win probabilities, look at the distribution of outcomes.
- [ ] **f1/03-dashboard-shell** — Build a simple multi-panel Matplotlib dashboard (win probability bar chart, finish position histogram).
- [ ] **data-cleaning/01-cleaning-drill** — Take a messy CSV, practice handling nulls, duplicates, type coercion, and outliers end to end.
- [ ] **quant/01-cointegration-zscore** — Practice pairs-trading mechanics: cointegration test, z-score signal generation on two correlated assets.

Each exercise is self-contained and meant to be finished in an hour or two.
