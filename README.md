# Financial Analysis Agents

A Python-based autonomous agent system that automates financial market analysis and trading strategy development using CrewAI. This project demonstrates how multiple specialized agents can collaborate to analyze market data, develop trading strategies, plan executions, and manage risks.

## 🚀 Features

- **Multi-Agent Trading System**: Four specialized agents work together to provide comprehensive financial analysis.
- **Real-Time Market Analysis**: Monitors and analyzes market data to identify trends and opportunities.
- **Strategy Development**: Creates and refines trading strategies based on market insights.
- **Risk Management**: Evaluates and provides detailed risk assessments for trading activities.
- **Trade Execution Planning**: Optimizes trade timing and execution methods.
- **Environment Configurable**: API keys and settings via `utils.py` or environment variables.

## 🧩 Main Agents

- **Data Analyst**: Monitors market data and identifies trends using statistical modeling and machine learning.
- **Trading Strategy Developer**: Creates and tests trading strategies based on market analysis.
- **Trade Advisor**: Plans optimal trade execution strategies and timing.
- **Risk Advisor**: Assesses potential risks and suggests mitigation strategies.

## 🏗️ How It Works

1. **Setup**: Configure your API keys in `utils.py` or as environment variables.
2. **Run the App**: Execute `main.py` to start the agent workflow.
3. **Agent Collaboration**: 
   - Data Analyst provides market insights
   - Strategy Developer creates trading plans
   - Trade Advisor optimizes execution
   - Risk Advisor assesses potential risks
4. **Output**: Generates comprehensive trading analysis and recommendations.

## 📦 Installation

```bash
git clone <repo-url>
cd financial-analysis-agents
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## ⚙️ Usage

1. Set up your API keys in `utils.py` or as environment variables.
2. Run the main script:
   ```bash
   python main.py
   ```
3. Customize inputs in `main.py`:
   - Stock selection
   - Initial capital
   - Risk tolerance
   - Trading strategy preference
   - News impact consideration

## 📝 Example

```
$ python main.py
[DataAnalyst] Analyzing AAPL market data...
[StrategyDeveloper] Developing day trading strategies...
[TradeAdvisor] Planning optimal execution...
[RiskAdvisor] Assessing trading risks...
Output: Comprehensive trading analysis and recommendations
```

## 🛠️ Customization

- Add new agents for specialized market analysis.
- Modify strategy development algorithms.
- Integrate with additional data sources or APIs.
- Customize risk assessment parameters.
- Add support for different asset classes.

## 📚 Dependencies

- Python 3.8+
- CrewAI
- langchain_openai
- crewai_tools (ScrapeWebsiteTool, SerperDevTool)
- Other packages in `requirements.txt`

## 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you want to change.

---
Feel free to modify or extend the agents for your own financial analysis and trading automation needs!
