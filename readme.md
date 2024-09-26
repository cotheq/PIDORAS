# PID Optimized Response Adjustment System (PIDORAS)

This program was created with ChatGPT.

**PIDORAS** (PID Optimized Response Adjustment System) is a dynamic visual tool designed to simulate and fine-tune the behavior of a PID controller. The application allows users to visualize how the Proportional (P), Integral (I), and Derivative (D) control parameters affect a system’s response in real time. This interactive interface enables experimentation with various settings and observation of how the system reacts to target value changes.

## Key Features

- **Real-Time Visualization**: Displays the current value, target value, and how the PID controller responds to changes via an animated dial gauge.
- **Adjustable PID Values**: Tweak the Proportional, Integral, and Derivative control values with sliders and see their effects on the system’s behavior.
- **Smooth Animations**: The pointer dynamically rotates to reflect the system’s current state based on the PID logic.
- **Interactive Target Setting**: Set various target values and watch as the system attempts to reach it with the configured PID parameters.
- **Progressive Error Correction**: Internal calculations handle proportional error corrections, integral summation of errors, and derivative error prediction to smooth out system response.

## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/pidoras.git
   ```

2. Open the `index.html` file in any web browser to launch the application.

3. Use the **Target Value** slider to set your desired value, and the system will aim to reach it using the tuned PID parameters.

4. Adjust the **P (Proportional)**, **I (Integral)**, and **D (Derivative)** sliders to tweak the controller’s behavior:
   - **P (Proportional)**: Adjusts how aggressively the system reacts to current errors.
   - **I (Integral)**: Corrects past errors by summing them over time.
   - **D (Derivative)**: Predicts future errors based on the rate of error change.

5. Watch as the **gauge arrow** moves in real time, reflecting the system’s current response.

6. The system’s current value and all PID parameters are displayed in real-time.

## Technologies

- **HTML/CSS**: For building the user interface and layout.
- **JavaScript**: For running the PID calculations and dynamically updating the interface.
- **CSS Animations**: For smooth transitions and visual feedback when managing PID control.

## Screenshot

![Screenshot of PIDORAS](https://sun9-80.userapi.com/impg/kCar5C7yZKR5z5KbKJssR5DN0gQQT-1vFyB-3g/bOTYDuX5fHo.jpg?size=1335x912&quality=95&sign=6b9e99ba72f4cb6aeb476cbf10c31d79&type=album)

## How PID Works

A PID controller adjusts the system’s output based on three components:
- **Proportional (P)**: Applies correction proportional to the current error.
- **Integral (I)**: Sums errors over time to correct systematic bias.
- **Derivative (D)**: Predicts future errors based on the rate of error change.

By adjusting these three values, you can control how quickly or smoothly the system reaches its target.

## Contribution

We welcome contributions! If you have suggestions for improvements or new features, feel free to open a pull request or create an issue.

1. Fork the repository
2. Create a branch for the new feature: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add new feature'`
4. Push the branch: `git push origin feature-name`
5. Open a pull request

---
