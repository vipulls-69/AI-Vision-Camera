## Project
Integrating Vision AI with home security cameras offers powerful capabilities, but making it affordable and reliable presents a significant technical challenge. Continuous API polling—sending video frames to a cloud-based AI service every second—is highly cost-prohibitive. Conversely, relying on fixed-interval checks often results in missing the exact, crucial events you want to capture.

```home-camera-vlm``` addresses this by introducing a smart, hybrid architecture. By implementing an OpenCV pre-processing layer before the Vision-Language Model (VLM), the system intelligently filters camera feeds locally. Using lightweight computer vision techniques like pixel diffing and distance approximation, it acts as a "smart gatekeeper." The expensive VLM API is only triggered when a meaningful spatial or motion event actually occurs.

## Key Features
Cost-Optimized Inference: Drastically reduces AI API costs by preventing redundant cloud pings, without missing critical events.

Natural Language Rules: Define custom, intuitive triggers for each individual camera feed using plain text (e.g., "Alert me if a dog enters the porch").

Centralized Platform: A single-pane-of-glass dashboard to unify, monitor, and configure all of your connected security cameras in one place.

Hardware Agnostic: Leverage your existing IP/security cameras without needing to purchase proprietary AI hardware.

## Setup
Navigate to frontend and backend folders to setup project and start running the project.
