# ICT Momentum - TradingView Pine Script Indicator

A comprehensive TradingView Pine Script indicator that combines multiple ICT (Inner Circle Trader) concepts and methodologies into one powerful trading tool.

## 🎯 Overview

The **ICT Momentum** indicator provides institutional-grade market analysis by implementing key ICT concepts including Fair Value Gaps, Silver Bullets, session analysis, and liquidity levels. This indicator is designed for traders who follow ICT methodologies and want a complete solution for market structure analysis.

## ✨ Key Features

### 📊 ICT Fair Value Gaps (FVG) & Inverse Fair Value Gaps (IFVG)
- **Bullish/Bearish FVG Detection**: Automatic identification of fair value gaps
- **Inverse FVG Analysis**: Detects price rejections within gap areas
- **Midpoint Lines**: Precision 50% levels for each FVG/IFVG
- **Timeframe Specific**: Only shows FVGs on selected timeframes (1m, 5m, 15m, 1h, 4h, 1D)
- **Customizable Count**: Display last 1-10 FVGs with automatic cleanup

### 🎯 ICT Silver Bullets
- **London Silver Bullet**: 03:00-04:00 GMT high-probability window
- **NY AM Silver Bullet**: 13:30-14:30 GMT market open volatility
- **NY PM Silver Bullet**: 18:30-19:30 GMT late session moves
- **Background Highlighting**: Visual session identification
- **High/Low Tracking**: Precise level marking for each Silver Bullet period

### 🌍 Session Analysis
- **London Session**: 03:00-12:00 GMT with background highlighting
- **Asia Session**: 20:00-05:00 GMT with range tracking
- **NY PM Session**: 13:30-20:00 GMT institutional flow
- **Session High/Low**: Automatic level detection and display

### 📈 Key Levels & Ranges
- **Previous Week High/Low**: Weekly key levels
- **Yesterday Levels**: High, Low, Close, and Midpoint
- **Opening Range**: 9:30-9:45 NY time with GMT offset adjustment
- **VWAP**: Volume Weighted Average Price
- **EMAs**: 9 & 21 period with cross signals
- **Standard Pivot Points**: PP, R1-R3, S1-S3 levels

## 🛠️ Installation

1. **Download**: Copy the code from `ICT_momentum.pine`
2. **Open TradingView**: Go to Pine Editor
3. **Import**: Paste the code and click "Add to Chart"
4. **Customize**: Adjust settings in the indicator inputs panel

## ⚙️ Customization Options

### Toggle Controls
- Independent on/off switches for every feature
- Clean interface with organized settings groups
- Optimized performance by disabling unused features

### Color Customization
- **Level Colors**: Customize all line colors
- **Background Colors**: Session and Silver Bullet backgrounds
- **FVG Colors**: Separate colors for bullish/bearish FVGs and IFVGs
- **Midpoint Colors**: Customizable FVG midpoint line colors

### Advanced Settings
- **Timeframe Filtering**: FVG detection for specific timeframes only
- **Line Styles**: Solid, Dashed, or Dotted options
- **GMT Offset**: Adjust for your timezone
- **Session Times**: Customize all session start/end times
- **Alert System**: Built-in alerts for all major events

## 📋 Label Reference

| Label | Description |
|-------|-------------|
| **PWH/PWL** | Previous Week High/Low |
| **YH/YL/YC/YM** | Yesterday High/Low/Close/Midpoint |
| **LH/LL** | London Session High/Low |
| **AH/AL** | Asia Session High/Low |
| **NH/NL** | NY PM Session High/Low |
| **ORH/ORL** | Opening Range High/Low |
| **LSB-H/LSB-L** | London Silver Bullet High/Low |
| **AM-SB-H/AM-SB-L** | NY AM Silver Bullet High/Low |
| **PM-SB-H/PM-SB-L** | NY PM Silver Bullet High/Low |
| **FVG↑/FVG↓** | Bullish/Bearish Fair Value Gap |
| **IFVG↑/IFVG↓** | Bullish/Bearish Inverse Fair Value Gap |

## 🎯 Trading Applications

### ICT Silver Bullets Strategy
- **High-Probability Windows**: Focus trading during Silver Bullet periods
- **Breakout Trading**: Trade breaks of Silver Bullet high/low levels
- **Reversal Strategy**: Look for rejections at Silver Bullet extremes

### Fair Value Gaps Strategy
- **Gap Fill Trading**: Price often returns to fill FVGs as magnets
- **Midpoint Trading**: Use 50% levels for precise entries
- **Support/Resistance**: FVGs act as institutional S/R levels
- **Confluence Analysis**: Combine FVGs with session levels

### Session-Based Trading
- **London Bias**: Early European momentum setting daily direction
- **Asia Range**: Overnight consolidation levels
- **NY Institutional Flow**: Market open and PM session analysis

## 🚀 Performance Features

- **Optimized Code**: Efficient array management and memory usage
- **Scalable Design**: Works on all timeframes from 1-minute to daily
- **Resource Management**: Automatic cleanup of old levels and boxes
- **Alert System**: Comprehensive notifications for all key events

## 📖 Documentation

For detailed setup instructions, trading strategies, and troubleshooting, see the complete [User Guide](Trading_Indicator_Guide.md).

## 🔧 Requirements

- **TradingView**: Pro, Pro+, or Premium account recommended
- **Pine Script**: Version 5 compatible
- **Chart Setup**: Works best on 5-15 minute timeframes for intraday analysis

## 📊 Version Info

- **Current Version**: 1.0
- **Pine Script Version**: 5
- **Last Updated**: January 2024
- **Compatibility**: All TradingView plans

## 🤝 Contributing

Feel free to submit issues, feature requests, or improvements. This indicator follows ICT methodologies and aims to provide institutional-grade analysis for retail traders.

## 📄 License

This project is open source. Please provide attribution when using or modifying the code.

## ⚠️ Disclaimer

This indicator is for educational and informational purposes only. Trading involves substantial risk, and past performance does not guarantee future results. Always conduct your own analysis and risk management.

---

**Built for traders who understand that market structure reveals institutional intent.**