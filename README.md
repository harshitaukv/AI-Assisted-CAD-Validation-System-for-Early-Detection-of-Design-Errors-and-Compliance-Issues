# AI-Assisted-CAD-Validation-System-for-Early-Detection-of-Design-Errors-and-Compliance-Issues

## Overview

The AI-Assisted CAD Validation System is a web-based application designed to support engineers during the design phase by automatically analyzing CAD drawings and detecting potential errors, inconsistencies, and compliance issues in real time. By combining computer vision techniques with rule-based validation, the system provides instant, actionable feedback, reducing manual effort and improving overall design quality.

---

## System Architecture & Components

### 1. **User Interface (Frontend Layer)**

* Built using HTML, CSS, and JavaScript
* Provides an interactive CAD-like environment
* Supports image upload, visualization, and real-time feedback
* Displays:

  * Validation score
  * Error/warning indicators
  * Compliance metrics
  * Visual markers on design

---

### 2. **Image Processing Module**

* Utilizes browser-based Canvas API
* Performs:

  * Grayscale conversion
  * Edge detection
  * Pixel-level analysis
* Extracts geometric features from CAD images

---

### 3. **Feature Extraction Engine**

* Identifies key design elements:

  * Edges and contours
  * Shapes (circles, lines)
  * Symmetry patterns
* Converts raw image data into structured feature points

---

### 4. **Validation Engine (Rule-Based System)**

* Applies engineering constraints such as:

  * Hole spacing and alignment
  * Edge distance rules
  * Structural consistency
* Detects:

  * Errors (critical violations)
  * Warnings (potential risks)
  * Passed checks

---

### 5. **Scoring & Analytics Module**

* Generates a dynamic validation score (0–100)
* Calculates:

  * Error count
  * Warning count
  * Compliance percentages (ISO, ASME, DIN)
* Updates UI in real time

---

### 6. **Visualization & Feedback System**

* Overlays markers directly on the design:

  * Errors
  * Warnings
  * Information
* Provides intuitive visual guidance for corrections

---

## Tech Stack

### Frontend

* HTML5 (structure)
* CSS3 (UI styling, layout)
* JavaScript (logic, interactivity)

### Processing & Analysis

* Canvas API (image processing)
* Custom JavaScript algorithms (edge detection, feature extraction)

### Architecture Style

* Client-side processing (no backend dependency)
* Modular design for scalability
* Event-driven updates for real-time interaction

---

## Workflow

1. User uploads a CAD design image
2. System preprocesses the image using Canvas API
3. Features are extracted (edges, shapes, symmetry)
4. Validation engine applies design rules
5. Issues and compliance metrics are generated
6. Results are visualized with markers and scores

---

## Key Advantages

* Real-time feedback during design stage
* Cost-effective (no external APIs required)
* Easy integration into existing workflows
* Interactive and user-friendly interface
* Early detection of design flaws

---

## Future Scope

* Integration with CAD tools (AutoCAD, SolidWorks)
* Advanced AI/ML-based feature detection
* 3D model validation support
* Automated report generation (PDF/Excel)

---

## Author

**Harshita U**


