# 🎧 Headphone Latency Tester

A precise, browser-based tool for measuring audio latency in headphones and audio systems. This application helps you determine the delay between when audio is generated and when you actually hear it through your audio equipment.

## 🎯 What Does This App Do?

This tool measures **audio latency** - the time delay between when a sound is produced by your computer and when it reaches your ears through your headphones or speakers. This is crucial for:

- **Musicians** using digital audio workstations (DAWs)
- **Audio engineers** setting up recording systems  
- **Gamers** who need responsive audio feedback
- **Content creators** working with real-time audio
- **Anyone** curious about their audio system's performance

## 🔬 How It Works

1. **Generates precise audio beats** at exactly 120 BPM using the Web Audio API
2. **Records your tap timing** when you hear each beat
3. **Calculates the latency** by comparing audio generation time vs. your response time
4. **Averages 20 measurements** for accurate, stable results
5. **Shows comprehensive statistics** including average latency, standard deviation, and range

## ✨ Features

- **Precise timing** using Web Audio API for drift-free beat generation
- **Pure audio testing** with optional visual indicators (disabled by default for accuracy)
- **Drum-like sound** that's easy to hear and sync with
- **Real-time graph** showing your latency measurements
- **Professional statistics** including average, std deviation, and range
- **Responsive design** that works on desktop and mobile
- **No installation required** - runs directly in your browser

## 🚀 How to Use

1. **Start the test** by clicking "Start Test"
2. **Listen carefully** to the 120 BPM drum beats
3. **Press SPACEBAR** (or click "Tap Beat") exactly when you hear each beat
4. **Wait for results** - measurements appear after 10+ beats for accuracy
5. **Review your latency** in the statistics and graph

## 📊 Understanding Results

- **Audio Latency**: Average delay in milliseconds
- **Std Deviation**: How consistent your measurements are  
- **Range**: Difference between your fastest and slowest measurements
- **Beats Recorded**: Number of valid measurements collected

**Typical Values:**
- **0-20ms**: Excellent (professional level)
- **20-40ms**: Good (suitable for most applications)
- **40-80ms**: Noticeable delay
- **80ms+**: Significant latency issues

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - no frameworks or dependencies
- **Web Audio API** for precise audio generation and timing
- **Performance API** for high-resolution timing measurements
- **AudioContext scheduling** ensures exact 120 BPM timing without drift
- **Cross-browser compatible** with modern browsers

## 🔗 Related Tools

For additional audio latency testing tools, check out: [deftio.github.io/web-audio-latency-tester](https://deftio.github.io/web-audio-latency-tester)

## 🎵 Why Audio Latency Matters

Audio latency affects:
- **Music production**: High latency makes real-time recording difficult
- **Gaming**: Delayed audio cues can impact performance
- **Video calls**: Audio sync issues in communication
- **Live performance**: Musicians need immediate audio feedback

## 📱 Browser Support

Works on all modern browsers that support:
- Web Audio API
- Performance API  
- Canvas API

## 🔧 Local Development

1. Clone or download this repository
2. Serve the files using any web server (e.g., `python -m http.server`)
3. Open in your browser and start testing

## 📄 License

This project is open source. Feel free to use, modify, and distribute.

---

**Note**: This tool measures the combined latency of your audio system (audio drivers, hardware, headphones, etc.) plus your reaction time. For pure system latency, subtract your typical reaction time (~150-250ms for most people).