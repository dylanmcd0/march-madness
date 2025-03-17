# March Madness Bracket Simulation

This project downloads historical NCAA basketball data and simulates the March Madness tournament using various statistical models.

## Features
- Fetch **historical datas**
- Build **this year's official bracket**
- Simulate the tournament using **Monte Carlo, Elo ratings, and machine learning**

## Data Sources
- [March Machine Learning Mania](https://www.kaggle.com/c/march-machine-learning-mania-2025) - Kaggle Competition Dataset
- [March Madness 2025](https://www.kaggle.com/datasets/jonathanpilafas/2024-march-madness-statistical-analysis) - Kaggle Dataset (has kenpom)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/march-madness-sim.git
   cd march-madness-sim
   ```
2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate  # On Windows
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Set up API keys for SportsDataIO and The Odds API in a `.env` file:
   ```
   SPORTS_DATA_IO_KEY=your_api_key
   ODDS_API_KEY=your_api_key
   ```

## Usage
Run the data retrieval script:
```sh
python fetch_data.py
```

Run the simulation:
```sh
python simulate_bracket.py
```

## Next Steps
- Add real-time updates during the tournament (eh, maybe)
- Develop a web dashboard for visualization
- Integrate Vegas odds data to determine EV

