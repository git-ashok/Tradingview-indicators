# Ultimate Trading Levels & Sessions Indicator - User Guide

## Overview
This comprehensive Pine Script indicator combines multiple trading tools into one powerful indicator for TradingView. It displays key levels, session highlights, technical indicators, and provides full customization control.

## Features Included

### 1. Previous Week High/Low (PWH/PWL)
- **Purpose**: Shows the high and low from the previous week
- **Usage**: Key levels for weekly analysis and potential support/resistance
- **Labels**: PWH (Previous Week High), PWL (Previous Week Low)

### 2. Yesterday Levels
- **Yesterday High (YH)**: Previous day's highest price
- **Yesterday Low (YL)**: Previous day's lowest price  
- **Yesterday Close (YC)**: Previous day's closing price
- **Yesterday Midpoint (YM)**: Average of yesterday's high and low
- **Usage**: Daily key levels for intraday trading

### 3. ICT Session Analysis
- **London Session**: Default 03:00-12:00 GMT with blue background highlight
- **Asia Session**: Default 20:00-05:00 GMT with red background highlight  
- **New York PM Session**: Default 13:30-20:00 GMT with green background highlight
- **Features**: Each session shows high/low levels and background coloring

### 4. Opening Range (9:30-9:45 NY Time)
- **Purpose**: Captures the first 15 minutes of NY market open
- **Customizable**: Adjust GMT offset for your timezone
- **Labels**: ORH (Opening Range High), ORL (Opening Range Low)

### 5. Technical Indicators
- **VWAP**: Volume Weighted Average Price
- **9 EMA & 21 EMA**: Exponential Moving Averages with cross signals
- **Standard Pivot Points**: PP, R1-R3, S1-S3 levels

## Customization Options

### Toggle Controls
Turn any feature on/off independently:
- Previous Week High/Low
- Yesterday Levels  
- London Session
- Asia Session
- New York PM Session
- VWAP
- EMAs
- Pivot Points
- Opening Range

### Session Time Customization
- **GMT Offset**: Adjust for your timezone (-12 to +12)
- **Session Times**: Modify start/end times for each session
- **London**: 03:00-12:00 (customizable)
- **Asia**: 20:00-05:00 (customizable)
- **NY PM**: 13:30-20:00 (customizable)

### Color Customization
**Level Colors**: Customize colors for all lines
- Previous Week: Purple (default)
- Yesterday: Yellow (default)
- London: Blue (default)
- Asia: Red (default)
- NY PM: Green (default)
- VWAP: Orange (default)
- 9 EMA: Lime (default)
- 21 EMA: Fuchsia (default)
- Pivots: Gray (default)
- Opening Range: Aqua (default)

**Background Colors**: Customize session background highlights
- London: Light Blue (95% transparency)
- Asia: Light Red (95% transparency)  
- NY PM: Light Green (95% transparency)

### Line Style Options
- **Width**: 1-5 pixels
- **Style**: Solid, Dashed, or Dotted lines

### EMA Settings
- **9 EMA Length**: Default 9 (customizable)
- **21 EMA Length**: Default 21 (customizable)
- **Cross Signals**: Toggle EMA cross alerts on/off

## How to Use

### Installation
1. Copy the Pine Script code from `trading_indicator.pine`
2. Open TradingView and go to Pine Editor
3. Paste the code and click "Add to Chart"

### Configuration
1. **Initial Setup**: The indicator works with default settings
2. **Customize Sessions**: Adjust GMT offset for your timezone
3. **Toggle Features**: Turn on/off only what you need
4. **Customize Colors**: Match your chart theme preferences
5. **Set Alerts**: Use built-in alerts for EMA crosses and session starts

### Trading Applications

#### Day Trading
- Use **Opening Range** for breakout trades
- **Yesterday levels** for support/resistance
- **Session backgrounds** to identify active trading periods
- **VWAP** for trend direction and mean reversion

#### Swing Trading  
- **Previous Week High/Low** for weekly analysis
- **Pivot Points** for target levels
- **EMA crosses** for trend changes
- **Yesterday Close** for gap analysis

#### Multi-Timeframe Analysis
- Works on all timeframes from 1-minute to daily
- Higher timeframes show cleaner level breaks
- Lower timeframes good for precise entries

## Label Reference
- **PWH/PWL**: Previous Week High/Low
- **YH/YL/YC/YM**: Yesterday High/Low/Close/Midpoint  
- **LH/LL**: London Session High/Low
- **AH/AL**: Asia Session High/Low
- **NH/NL**: NY PM Session High/Low
- **ORH/ORL**: Opening Range High/Low

## Alert Options
The indicator includes alerts for:
- EMA 9 crossing above/below EMA 21
- Session start notifications (London, Asia, NY PM)
- Opening Range start notification

## Tips for Best Results

1. **Start Simple**: Enable only essential features initially
2. **Color Coordination**: Use contrasting colors for easy identification
3. **Timeframe Selection**: Use 5-15 minute charts for intraday analysis
4. **Session Awareness**: Trade during active sessions for better volume
5. **Level Confluence**: Look for multiple levels converging for stronger signals

## Troubleshooting

### Common Issues
- **Lines not showing**: Check if toggle is enabled
- **Wrong session times**: Verify GMT offset setting
- **Too many lines**: Disable unused features to reduce clutter
- **Performance**: Reduce line count on lower timeframes if needed

### Performance Optimization
- Turn off unused features
- Use higher timeframes for cleaner display
- Limit to essential levels for active trading

This indicator provides institutional-grade level analysis with full customization control, making it suitable for any trading style or market condition.