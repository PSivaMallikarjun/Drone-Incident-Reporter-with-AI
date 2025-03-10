# Drone-Incident-Reporter-with-AI
"We need a drone-based AI system that can simulate incident reporting in such hazardous locations."

# Drone Controller Simulation Web App

## Overview
This web application simulates a **drone controller** for detecting and reporting issues in dangerous areas, such as **radiation zones, fire zones, and hazardous incidents**. It allows users to **interact via prompts**, acting as a reporter to gather information on critical incidents.

## Features
- **Drone Incident Detection:** Detects issues in radiation zones and hazardous areas.
- **Gradio + Streamlit UI:** Provides an interactive web interface for user-friendly reporting.
- **Small Dataset Integration:** Uses pre-defined datasets for simulation.
- **Hugging Face Spaces Deployment:** Runs on Hugging Face for easy cloud-based access.

## Installation
To run this project locally, install the required dependencies:

```bash
pip install gradio streamlit huggingface_hub pandas
```

## Running the Application
Run the following command to start the **Gradio UI**:

```bash
python gradio_app.py
```

For **Streamlit UI**, execute:

```bash
streamlit run streamlit_app.py
```

## Deploying on Hugging Face Spaces
1. **Login to Hugging Face**:
   ```bash
   huggingface-cli login
   ```
2. **Create a new Space on Hugging Face** (Select **Streamlit/Gradio** as the framework).
3. **Push Code to Hugging Face**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git clone https://huggingface.co/spaces/SivaMallikarjun/drone-simulation-app
   git push -u origin main
   ```

## Usage Guide
1. **Enter a prompt** describing an incident (e.g., "Report radiation levels in Zone A").
2. The drone **simulates scanning the area** and returns a **detailed report**.
3. View the **real-time analysis** and suggested actions.

## Future Improvements
- **Live data integration** from IoT-enabled drones.
- **Machine Learning enhancements** for real-time decision-making.
- **Multilingual support** for wider accessibility.

## Contributing
Feel free to **fork** the repository and submit **pull requests** for improvements!

## License
This project is licensed under the **MIT License**.

## Contact
For queries or collaboration, reach out via **[Hugging Face](https://huggingface.co/your-profile)**.

