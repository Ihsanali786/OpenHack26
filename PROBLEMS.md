
<div align="center">

<img src="assets/logo.png" alt="OpenHack'26" width="180"/>

# 💡 Problem Statements

### Think. Build. **Push.**

![Problems](https://img.shields.io/badge/PROBLEMS-15-bd00ff?style=for-the-badge&labelColor=0b0b0f)
![Categories](https://img.shields.io/badge/CATEGORIES-5-9dff00?style=for-the-badge&labelColor=0b0b0f)
<!-- ![Release](https://img.shields.io/badge/RELEASE-13_OCT_2026_•_11:00_AM-bd00ff?style=for-the-badge&labelColor=0b0b0f) -->

[🏠 Home](README.md) · [📜 Rules](RULES.md) · [📋 Submission Guide](SUBMISSION_GUIDELINES.md) · [⚖️ Judging](JUDGING.md)

</div>

<img src="assets/divider.png" width="100%" height="4" alt=""/>

### 🔥 5 Categories × 3 Problems = 15 Problems

 <!-- > [!NOTE]
> Problem statements will be released at the start of the hackathon:
> **13 October 2026 — 11:00 AM** -->





---

# 🏥 Category 1: HealthTech

*Improving healthcare access, patient support, and healthcare resource management.*

## HT-01 | Multilingual Medication Adherence Assistant

### Problem
Patients managing long-term conditions may forget medication schedules or struggle to understand prescription instructions, especially when information is not available in their preferred language.

### Challenge
Build a multilingual medication assistant that converts prescription information into an understandable medication schedule and helps patients and caregivers keep track of doses.

### Expected MVP
- Upload a prescription image and extract medication information using OCR, with manual correction.
- Create an editable medication schedule with reminders.
- Track scheduled and completed doses.
- Provide optional missed-dose notifications to a caregiver.
- Support English, Urdu, or Sindhi for essential instructions.

### Suggested Technology Focus
OCR, text processing, scheduling, notifications, and mobile-first web development.

### Scope and Safety
Use sample prescriptions and browser-based notifications if external messaging services are unavailable. **Never invent dosage instructions or change a clinician-prescribed schedule.** Extracted information must be reviewable and correctable by the user.

## HT-02 | Offline-First Maternal Health Referral Assistant

### Problem
Community health workers in areas with unreliable internet may face difficulties recording pregnancy-related information, identifying warning signs, and referring patients to appropriate healthcare facilities.

### Challenge
Develop an offline-capable application that records relevant maternal health information, highlights predefined warning indicators using transparent rules, and generates a referral summary for a qualified healthcare professional.

### Expected MVP
- Record basic patient information and relevant health indicators.
- Store records locally when internet connectivity is unavailable.
- Display explainable warning indicators based on documented clinical guidance.
- Generate a referral summary for healthcare staff.
- Display a directory of healthcare facilities using sample or available location data.

### Suggested Technology Focus
Progressive web apps, local storage, synchronization, rule-based systems, and mapping.

### Scope and Safety
Demonstrate offline data entry and synchronization using a small sample dataset. The application supports clinical referral; it must not claim to diagnose conditions or replace medical professionals. Use fictional data in demos.

## HT-03 | Smart Hospital Emergency Resource Manager

### Problem
During emergencies, hospital staff may struggle to coordinate patient priorities, available beds, doctors, and ambulances when information is scattered across different systems.

### Challenge
Build an emergency management dashboard that provides a consolidated view of patient cases and available resources, helping authorized staff identify suitable allocation options.

### Expected MVP
- Register emergency cases with configurable priority categories.
- Display available and occupied beds using live or simulated data.
- Track doctor availability and ambulance status.
- Recommend suitable resource allocations based on priority and availability.
- Show an emergency dashboard with status updates.

### Suggested Technology Focus
Real-time databases, scheduling algorithms, resource allocation, REST APIs, and dashboards.

### Scope and Safety
Use simulated hospital data and a transparent allocation algorithm. Clinical triage and final resource decisions must remain under qualified human supervision.

---

# 🎓 Category 2: EdTech

*Making learning more personalized, effective, accessible, and career-oriented.*

## ED-01 | Adaptive Learning Path Generator

### Problem
Students often follow the same learning sequence despite having different knowledge levels. They may spend too much time revising familiar topics while overlooking important weaknesses.

### Challenge
Build a personalized learning platform that assesses a student's current knowledge, identifies weak topics, and adapts a learning roadmap as the student progresses.

### Expected MVP
- Conduct a short diagnostic quiz.
- Display topic-wise strengths and weaknesses.
- Generate a personalized learning sequence with relevant resources.
- Recommend practice questions for weaker topics.
- Update the learning roadmap based on assessment results.

### Suggested Technology Focus
Adaptive assessment, recommendation systems, learning analytics, and AI-assisted content generation.

### Scope
Start with one subject and a small, structured question bank. Demonstrate how a student's next learning activity changes according to their answers.

## ED-02 | AI Assignment Feedback Assistant

### Problem
Students may receive delayed or limited feedback on their assignments, while teachers spend considerable time identifying recurring mistakes and explaining how students can improve.

### Challenge
Develop an assistant that evaluates student submissions against a teacher-defined rubric and provides specific, actionable feedback for students and instructors to review.

### Expected MVP
- Accept a text-based assignment or document.
- Allow teachers to define or select rubric criteria.
- Generate criterion-based feedback and identify missing concepts.
- Suggest practical improvements with supporting examples.
- Provide an instructor review and editing interface.

### Suggested Technology Focus
Large language models, natural language processing, document processing, and rubric-based evaluation.

### Scope
Support one assignment type and a small set of rubric criteria. Generated feedback should remain editable and should not be presented as an unquestionable grade.

## ED-03 | Career and Skill-Gap Navigator

### Problem
University students may struggle to understand which skills employers expect and how to turn their current academic knowledge and projects into a career-ready profile.

### Challenge
Build a career guidance platform that compares a student's skills with selected job requirements and produces a personalized roadmap for professional development.

### Expected MVP
- Create a student profile containing skills, courses, projects, and career interests.
- Compare the profile with selected job descriptions or predefined role requirements.
- Identify missing or underdeveloped skills.
- Recommend learning resources and portfolio projects.
- Display milestones and track progress toward a selected career goal.

### Suggested Technology Focus
CV parsing, NLP, recommendation systems, job descriptions, and analytics.

### Scope
Support three to five predefined career roles or a small set of collected job descriptions. Clearly distinguish verified job requirements from generated recommendations.

---

# 🌾 Category 3: AgriTech & Food

*Using technology to support farmers, conserve resources, and reduce food losses.*

## AG-01 | AI Crop Disease Scout

### Problem
Farmers may struggle to identify crop diseases at an early stage, while access to agricultural experts can be limited in rural communities.

### Challenge
Develop a mobile-friendly application that analyzes crop leaf photographs, identifies possible disease symptoms, and provides understandable preventive guidance.

### Expected MVP
- Upload a crop leaf photograph.
- Identify a healthy condition or possible disease from at least three supported classes.
- Display the predicted class and confidence score.
- Highlight affected regions where feasible.
- Provide preventive guidance in English, Urdu, or Sindhi.

### Suggested Technology Focus
Computer vision, image classification, transfer learning, and multilingual interfaces.

### Scope and Safety
Use an existing pretrained model or a suitable public dataset. Clearly communicate uncertainty and avoid presenting predictions as confirmed diagnoses.

## AG-02 | Smart Irrigation Optimizer

### Problem
Farmers may waste scarce water or damage crop productivity because they lack accessible information about irrigation timing, crop water requirements, and upcoming weather conditions.

### Challenge
Build a decision-support tool that recommends when and how much to irrigate based on crop requirements, growth stage, soil conditions, and weather information.

### Expected MVP
- Collect crop type, growth stage, soil information, and previous irrigation details.
- Display current or forecast weather information.
- Calculate an estimated irrigation requirement using documented rules or an established agricultural method.
- Recommend an irrigation schedule and explain the factors behind it.
- Estimate potential water savings against a clearly defined baseline.

### Suggested Technology Focus
Weather APIs, agricultural calculations, optimization, data visualization, and optional IoT integration.

### Scope
Support at least two crops with documented assumptions. A simulated soil-moisture reading is acceptable if hardware is unavailable.

## AG-03 | Food Waste Prediction and Reduction

### Problem
Restaurants, grocery stores, and university canteens may prepare or purchase more food than they can sell, resulting in avoidable waste and financial losses.

### Challenge
Develop a system that estimates demand, identifies potential surplus, and recommends preparation or purchasing quantities to help food businesses reduce waste.

### Expected MVP
- Enter historical sales, current inventory, and expiry information.
- Estimate demand for selected food items.
- Identify items at risk of becoming surplus or expiring.
- Recommend preparation or purchasing quantities.
- Display estimated waste reduction and potential cost savings.

### Suggested Technology Focus
Forecasting, machine learning, inventory analytics, and dashboards.

### Scope
Use a small sample dataset and a baseline forecasting method. Clearly label predicted savings as estimates rather than proven outcomes.

---

# 🌍 Category 4: Climate & Disaster Resilience

*Building community resilience through environmental intelligence, preparedness, and coordinated emergency response.*

## CL-01 | Flood Risk and Evacuation Planner

### Problem
Communities near rivers, canals, and flood-prone settlements may lack accessible information about local hazards, nearby shelters, and possible evacuation routes.

### Challenge
Develop a map-based decision-support platform that identifies potential flood-risk areas using available environmental data and displays shelter locations and possible evacuation routes.

### Expected MVP
- Display an interactive map with sample or sourced flood-risk information.
- Visualize risk zones using documented scoring rules or available datasets.
- Show designated shelters and relief points.
- Recommend routes that avoid known or simulated blocked roads.
- Generate safety messages in English, Urdu, or Sindhi.

### Suggested Technology Focus
Geospatial analysis, mapping APIs, routing algorithms, weather data, and risk visualization.

### Scope and Safety
Use a small geographic area and public or simulated data. Clearly distinguish official warnings from model estimates and simulated incidents. Do not present prototype routes or risk scores as official emergency instructions.

## CL-02 | Heatwave Safety Intelligence System

### Problem
Extreme heat can threaten outdoor workers, older adults, and other vulnerable residents who may lack timely safety information or easy access to cooling facilities and drinking water.

### Challenge
Build a platform that uses weather information and heat-related indicators to communicate risk levels and connect residents with relevant community resources.

### Expected MVP
- Display current weather conditions and forecasts.
- Calculate or present a documented heat-risk indicator.
- Highlight periods when heat risk is elevated.
- Provide practical safety guidance and multilingual alerts.
- Display a directory of cooling centers, water points, or community assistance locations.

### Suggested Technology Focus
Weather APIs, risk scoring, mapping, notification systems, and dashboards.

### Scope and Safety
Use one selected location and a weather API or sample dataset. Do not present the prototype as a substitute for official warnings or professional medical advice.

## CL-03 | Disaster Relief Resource Optimizer

### Problem
During floods and other emergencies, relief supplies may be distributed inefficiently because information about community needs, available inventory, and delivery capacity is scattered.

### Challenge
Build a coordination platform that matches requests for relief with available resources and recommends how limited supplies should be allocated across affected locations.

### Expected MVP
- Register assistance requests with location, urgency, and required supplies.
- Record available inventory and delivery capacity.
- Prioritize requests using transparent criteria such as urgency and affected population.
- Recommend resource allocations based on stock, demand, and distance.
- Display allocation status and delivery progress on a dashboard or map.

### Suggested Technology Focus
Optimization algorithms, resource allocation, mapping, and operational dashboards.

### Scope
Use simulated requests, inventory, and locations. Demonstrate how allocation recommendations change when supplies or community needs change.

---

# 🏙️ Category 5: Smart Communities & Public Services

*Improving civic accountability, accessibility, and the efficiency of everyday public services.*

## SC-01 | Smart Civic Complaint Triage System

### Problem
Residents may struggle to report broken streetlights, damaged roads, overflowing bins, water leakage, and blocked drains. Meanwhile, authorities may lack an effective system for prioritizing complaints and communicating progress.

### Challenge
Develop a transparent civic complaint platform that categorizes reports, identifies potential duplicates, prioritizes issues, and allows residents to track their resolution.

### Expected MVP
- Submit complaints using text and photographs.
- Record the approximate location and issue category.
- Automatically classify complaints and detect potential duplicates.
- Prioritize reports using configurable rules.
- Provide an administrative dashboard, status tracking, and resolution evidence.

### Suggested Technology Focus
NLP, computer vision, geolocation, similarity detection, and workflow automation.

### Scope
Support at least three complaint categories. Use sample civic reports and simulated departmental workflows if real municipal integration is unavailable.

## SC-02 | Accessibility-Aware Route Planner

### Problem
People with mobility or visual impairments may find it difficult to plan journeys because maps often lack reliable information about ramps, stairs, accessible entrances, footpaths, and other obstacles.

### Challenge
Create a navigation platform that considers user accessibility requirements and recommends suitable routes using available map information and community contributions.

### Expected MVP
- Display accessible locations and reported obstacles on a map.
- Allow users to select accessibility preferences, such as step-free routes.
- Recommend routes based on available accessibility information.
- Enable users to report barriers and accessibility features.
- Indicate missing, outdated, or unverified accessibility information.

### Suggested Technology Focus
Mapping APIs, graph algorithms, accessibility-aware routing, crowdsourced data, and accessible UI design.

### Scope
Demonstrate routing within a campus or a small neighborhood. Use a limited set of verified or clearly labeled sample accessibility points.

## SC-03 | Public Service Queue and Wait-Time Optimizer

### Problem
Long and unpredictable queues at hospitals, banks, and government service counters waste citizens' time and make it difficult for staff to manage demand efficiently.

### Challenge
Build a queue management platform that issues digital tokens, estimates waiting times, and helps service operators manage counters and distribute demand.

### Expected MVP
- Generate digital tokens through a web interface or QR code.
- Display queue position and estimated waiting time.
- Provide a staff dashboard for counter allocation and queue updates.
- Notify users when their turn is approaching.
- Show basic analytics such as average waiting time, completed tokens, and queue length.

### Suggested Technology Focus
Queueing theory, forecasting, real-time databases, notifications, and operational analytics.

### Scope
Use simulated service counters and customer arrivals. Demonstrate how estimated waiting times change as staff open counters, serve customers, or experience increased demand.

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b0b0f,100:bd00ff&height=100&section=footer" width="100%" alt="footer"/>
