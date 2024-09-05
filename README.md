
---

# ⚽ AI Football Tracker: Real-Time Match Insights


Welcome to **AI Football Tracker**! This project revolutionizes how football is analyzed, bringing the game to life through advanced computer vision techniques. Our AI system detects players, referees, goalkeepers, and the ball, offering real-time visualizations and insights into match dynamics. Whether you're a football fan, data enthusiast, or AI researcher, this project will ignite your passion for the sport and technology!
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://i.top4top.io/p_31703fjqi1.png">
  <source media="(prefers-color-scheme: light)" srcset="https://i.top4top.io/p_31703fjqi1.png">
  <img alt="AI Football Tracker: Real-Time Match Insights demo." src="https://i.top4top.io/p_31703fjqi1.png">
</picture>


## 🌟 Key Features

- **Player and Referee Detection**:  Track all players, referees, and the ball in real time using the YOLOv8n model paired with BoTSORT for precise identification.

- **Goalkeeper Recognition**:  Identify goalkeepers distinctively for specialized game analysis.

- **Teams Differentiation**: Separate the two teams on the field using PCA and KMeans clustering, simplifying performance analysis.

- **Live Visualizations:**: Generate dynamic, real-time visual representations of game states, helping to easily understand the flow and progress of the match.

## 📌 Project Enhancements

This project is inspired by a YouTube tutorial, but we've made several improvements:

- Faster Detection: Switched to YOLOv8n from YOLOv8x for improved speed without losing accuracy.
- Enhanced Keypoint Detection: Leveraged YOLOv8n Pose for more efficient pose recognition.
- Optimized Player Clustering: Refined player clustering using PCA and KMeans without the need for ReID.
- Improved Visualizations: Integrated more effective visualization techniques from the Supervision repository.

Tracking Model: BoTSORT is used for accurate multi-object tracking.
## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- OpenCV
- NumPy
- scikit-learn
- ONNXRuntime

### Installation

1. Clone the repository:
   ```bash
   git clone  https://github.com/Supernova1744/AI-Football-Tracker-Real-Time-Match-Insights.git
   ```
2. Navigate to the project directory:
   ```bash
   cd AI-Football-Tracker-Real-Time-Match-Insights
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Prepare your video files.
2. Run the main script:
   ```bash
   python main.py --video videos\match.mp4
   ```
3. View the results in the `output` directory.

### Demo Video

Check out a demo video of our system in action! Place your video oath in the `--video` flag for the main script to visualize the analysis.






---
