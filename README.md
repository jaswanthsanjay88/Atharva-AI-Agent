# 🤖 Atharva Agent & Browser 

## 1. Problem Statement

The increasing complexity of web interactions and the need for efficient data extraction and automation tasks demand intelligent solutions that go beyond traditional scripting. Current automation tools often lack the adaptability and robustness required to handle dynamic web environments and complex user objectives. This project addresses these limitations through two interconnected components: an AI-powered web automation agent (Atharva Agent) and an innovative open-source web browser (Atharva Browser), both designed to run AI agents natively, positioning them as a privacy-first alternative to existing solutions.

## 2. Detailed Proposal & Prototype Plan

This project is structured around two main components, each with its own development plan, but designed to work in synergy:

### 2.1. Atharva Agent Proposal & Prototype Plan

Atharva Agent is an AI-powered browser automation tool that leverages Google Gemini to understand user objectives expressed in natural language and Selenium WebDriver to interact with web pages.

**Phase 1: Core Functionality (MVP)**

*   **Objective:** Implement basic navigation and element interaction based on natural language instructions.
*   **Key Components:**
    *   Selenium WebDriver setup and basic actions (navigation, clicking, typing).
    *   Integration with Google Gemini for objective understanding.
    *   Simple element identification using basic Selenium selectors.
    *   Basic logging and screenshot capture.
*   **Timeline:** 2 Weeks

**Phase 2: Advanced Visual Analysis and Element Identification**

*   **Objective:** Enhance element identification using visual analysis and confidence scoring.
*   **Key Components:**
    *   Advanced element analysis based on heuristics and attributes (visibility, type, confidence).
    *   Image processing to identify elements from screenshots.
    *   Implementation of human-like cursor movement.
*   **Timeline:** 3 Weeks

**Phase 3: Atharva Agent as a Solution**

*   **Objective:** Enhance the Agent to offer a complete solution for any kind of problems.
*   **Key Components:**
    *   Increase efficiency.
    *   Refine to be user interactive
    *   Error handling optimization
*   **Timeline:** 3 Weeks

### 2.2. Atharva Browser Proposal & Prototype Plan

Atharva Browser is a Chromium fork specifically designed to run AI agents natively. Unlike browser extensions, AI capabilities are built into the browser core, ensuring a privacy-first approach.

**Phase 1: Core Integration and Rebranding**

*   **Objective:** Complete rebranding from "BrowserOS" to "Atharva" and establish a functional build system.
*   **Key Components:**
    *   Update all file references to reflect the new branding.
    *   Implement automated build scripts (build_atharva.py, setup_atharva.py).
    *   Configure a pure black UI theme.
    *   Update AI Side Panel and feedback systems.
    *   Document build guides and architecture.
*   **Timeline:** Completed

**Phase 2: Chromium Source and AI Integration**

*   **Objective:** Download Chromium source code and begin customizing AI integration features.
*   **Key Components:**
    *   Download the Chromium source code (~20GB).
    *   Implement the MCP (Model Context Protocol) store for one-click AI tool installation.
    *   Integrate local AI model support with Ollama.
*   **Timeline:** In Progress

**Phase 3: Atharva Browser Development**

*   **Objective:** Develop and refine the Atharva Browser for enhanced functionality and user experience.
*   **Key Components:**
    *   Implement a built-in AI ad blocker with advanced scenario coverage.
    *   Enhance automation capabilities within the browser.
    *   Test and validate browser functionality and AI agent performance within the browser environment.
*   **Timeline:** Planned

## 3. Features to be Implemented

*   **🤖 AI-Native Architecture (Both Agent & Browser):**
    *   AI agents run directly in the browser, not in the cloud.
    *   Privacy-first approach - users bring their own API keys or use local models with Ollama.
    *   Built-in AI integration at the core level.
*   **🔒 Privacy & Security (Both Agent & Browser):**
    *   Data stays on the user's computer.
    *   Open-source and community-driven.
    *   Option to use local AI models (Ollama) instead of cloud APIs.
*   **🎨 User Experience (Browser):**
    *   Familiar Chrome-like interface.
    *   Compatible with existing Chrome extensions.
    *   Pure black theme implementation.
*   **MCP (Model Context Protocol) store (Browser):** One-click AI tool installation.
*   **Built-in AI ad blocker (Browser):** Advanced scenario coverage.
*   **Enhanced automation capabilities (Browser):** Streamlined web interactions.
*   **Natural Language Understanding (Agent):** Interprets user objectives in natural language.
*   **Advanced Element Identification (Agent):** Accurate web element identification.
*   **Comprehensive Action Execution (Agent):** Wide range of actions including clicking, typing, etc.

## 4. Tech Stack Used

*   **Programming Language:** Python (Agent), C++ (Browser - Chromium base)
*   **AI Model:** Google Gemini (Agent), User-selected local or cloud models (Browser)
*   **Web Automation:** Selenium WebDriver (Agent)
*   **Web Driver Manager:** WebDriverManager (Agent)
*   **Image Processing:** Pillow, OpenCV (cv2) (Agent)
*   **HTTP Requests:** Requests, Urllib3 (Agent)
*   **Database:** SQLite (Agent)
*   **UI Framework:** JavaScript, HTML, CSS (Agent - Chat Interface), Chromium UI (Browser)
*   **Environment Management:** Dotenv (Agent)
*   **Async Operations:** Asyncio (Agent)
*   **Code Structure:** dataclasses (Agent)
*   **Code Optimization:** ThreadPoolExecutor, HTTPAdapter (Agent)
*   **Base (Browser):** Chromium 137.0.7151.69
*   **Build Tools (Browser):**
    *   Google's depot_tools for Chromium development
    *   Custom Python build scripts for automation
    *   YAML-based configuration system

## 5. Contribution Details

**Team Lead Details:**

*   **First Name:** Jaswanth Sanjay
*   **Last Name:** Nekkanti
*   **College:** Parul University
*   **Email:** 2403031460945@paruluniversity.ac.in
*   **State:** Gujarat
*   **Mobile:** 8088997070
*   **Responsibilities:**
    *   Overall Project Management and Coordination.
    *   AI Strategy and Native AI Integration.
    *   Chromium Customization and Configuration (Browser).
    *   AI Integration with Google Gemini (Agent).
    *   Testing and Quality Assurance for both components.
    *   Code Review and Refactoring.
    *   Element Interaction Logic (Agent).
    *    MCP Store Integration and Management (Browser).

**Team Member 1:**

*   **First Name:** Bhavana
*   **Last Name:** Petla
*   **College:** Parul University
*   **Email:** 2403031240129@paruluniversity.ac.in
*   **State:** Gujarat
*   **Mobile:** 7075167074
*   **Responsibilities:**
    *   Build System and Automation (Browser).
    *   UI/UX Development and Theme Configuration (Browser).
    *   Extension Compatibility and Integration (Browser).
    *   Selenium WebDriver Implementation (Agent)
    *   Handling Exceptions (Agent).
    *   Creation of action functions (Agent)

**Team Member 2:**

*   **First Name:** Nagalaxmi
*   **Last Name:** Bodapudi
*   **College:** Parul University
*   **Email:** 2403031240033@paruluniversity.ac.in
*   **State:** Gujarat
*   **Mobile:** 8688560193
*   **Responsibilities:**
    *   Privacy and Security Enhancements (Browser).
    *   Database Design and Implementation (Agent).
    *   Logging and Reporting Mechanisms (Agent).
    *   Assisting with code implementation for both projects.
    *   Local AI Model Integration Support (Browser)

Atharva Agent & Browser represent an ambitious project that combines modern web browser technology with cutting-edge AI capabilities, all while maintaining user privacy and control. We are building the future of AI-integrated web browsing and automation!
