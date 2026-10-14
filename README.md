# Dense UI Target Selection (HCI)

Project developed for the **Interação Pessoa-Máquina** (Human-Computer Interaction) course at **Instituto Superior Técnico (IST)**.

---

## 🎯 About the Project

An optimized interactive user interface created in **p5.js** to minimize target selection time in a dense grid of **80 targets** ($8 \times 10$), designed around human motor limits and cognitive UX principles.

---

## 💡 Challenge & Design Optimizations

* **The Problem**: Quickly locate and select randomly cued targets among 80 candidates using only a standard two-button mouse, balancing speed against accuracy penalties.
* **HCI Principles Applied**:
  * **Fitts's Law**: Expanding effective clickable target areas to speed up cursor movement.
  * **Visual Search & Categorization**: Color palettes, alphabetical or spatial grouping to reduce cognitive load and visual scanning time.
  * **Display Normalization**: Ensuring consistent physical target dimensions across different monitor resolutions using PPI/PPCM screen calibration.
  * **Error Prevention**: Visual cues and feedback mechanisms to minimize costly selection mistakes.

---

## 📊 Evaluation & Testing

* **Iterative Prototyping**: Developed across multiple iterations using feedback from in-class user testing ($N \ge 10$).
* **Statistical Analysis**: Validation of performance improvements across prototype versions using paired $t$-tests, confidence intervals, and ANOVA.
* **Telemetry**: Automated benchmarking of task duration and error rates logged to **Firebase**.

---

## 💻 Tech Stack
* **Frontend**: JavaScript, [p5.js](https://p5js.org/)
* **Telemetry & Storage**: Firebase
