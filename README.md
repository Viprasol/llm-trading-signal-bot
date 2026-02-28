# 🤖 LLM Trading Signal Bot

An **AI-powered trading signal generator** combining LLM reasoning with technical analysis and market sentiment.

> Built by [Viprasol Tech](https://viprasol.com) — custom AI agent systems and MT4/MT5 EA development.

---

## How It Works

```
Market Data + News → Sentiment → LLM Reasoning → Signal → Telegram/MT4
```

1. Fetch price data, news, economic calendar
2. Analyse sentiment (bullish/bearish/neutral + confidence)
3. LLM reasons about technical confluence
4. Output structured signal: direction, entry, SL, TP
5. Deliver via Telegram, email, or MT4/MT5 EA

---

## Signal Output

```json
{
  "pair": "EURUSD",
  "direction": "SHORT",
  "confidence": 0.78,
  "entry_zone": [1.0850, 1.0865],
  "stop_loss": 1.0910,
  "take_profit": [1.0800, 1.0750],
  "reasoning": "Bearish divergence on 4H RSI...",
  "sentiment_score": -0.62
}
```

---

## Models Supported

OpenAI (GPT-4o), Anthropic (Claude), Mistral, local Ollama

---

## Need a Custom AI Trading System?

Built by [Viprasol Tech](https://viprasol.com).

👉 **[Build Your AI Trading Bot →](https://viprasol.com/services/trading-software)**

---

MIT License
