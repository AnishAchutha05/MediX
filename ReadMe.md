# MediX AI - Healthcare Accessibility Platform

## 📋 Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Use Cases](#use-cases)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [API Integration](#api-integration)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 Overview

**MediX AI** is an intelligent healthcare accessibility platform powered by Google's Gemini API that bridges the gap between rural communities and essential medical guidance. This project addresses a critical healthcare challenge by providing instant, AI-driven health recommendations and remedies through accessible channels like WhatsApp and SMS.

In rural areas where access to medical professionals is limited, MediX AI serves as a first-line support system—offering preliminary health advice, symptom assessment, and suggested remedies to help people manage minor health complications before they can reach professional medical care.

### Mission
Democratize healthcare access by leveraging AI technology to provide instant, reliable health guidance to underserved communities globally.

---

## ✨ Key Features

### 🤖 AI-Powered Assistance
- **Intelligent Chatbot**: Built on Google Gemini API for advanced natural language processing
- **Context Awareness**: Understands medical queries and provides contextually relevant responses
- **Multi-Language Support**: Capable of handling queries in multiple languages for broader accessibility

### 📱 Multi-Channel Access
- **WhatsApp Integration**: Connect directly through WhatsApp for familiar, widely-used interface
- **SMS Support**: Reach users without smartphones through traditional SMS channels
- **Real-time Response**: Instant replies to health queries 24/7

### 💊 Health Remedies & Guidance
- **Symptom-Based Recommendations**: Input symptoms and receive relevant remedy suggestions
- **Quick Solutions**: Focus on short-term, accessible remedies for immediate relief
- **Educational Content**: Learn about common health issues and prevention tips

### 🌍 Rural Community Focus
- **Low Bandwidth Compatible**: Optimized for slower internet connections
- **Simple User Interface**: Designed for users with varying levels of technical expertise
- **Local Language Support**: Available in regional languages for better accessibility

---

## 🎨 Use Cases

1. **Fever & Common Cold**: Get immediate suggestions for managing symptoms at home
2. **Minor Injuries**: Receive first-aid guidance and care instructions
3. **Digestive Issues**: Get dietary recommendations and natural remedies
4. **Headaches & Pain**: Discover non-pharmaceutical and medicinal relief options
5. **Preventive Health**: Learn about disease prevention and healthy lifestyle tips
6. **Post-Consultation Follow-up**: Access guidance between hospital/clinic visits

---

## 🛠️ Technology Stack

| Component | Technology |
|-----------|-----------|
| **AI Engine** | Google Gemini API |
| **Messaging** | WhatsApp Business API, Twilio (SMS) |
| **Backend** | Python (Primary) |
| **Frontend** | HTML5, CSS3, JavaScript |
| **Database** | Scalable storage for user interactions |
| **Deployment** | Cloud-ready architecture |

---

## 📦 Installation

### Prerequisites
- Python 3.8 or higher
- Google Gemini API Key
- WhatsApp Business Account (for WhatsApp integration)
- Twilio Account (for SMS integration)
- Node.js or similar for serving the web interface

### Setup Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/MediX-AI.git
   cd MediX-AI
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables**
   Create a `.env` file in the project root:
   ```
   GEMINI_API_KEY=your_gemini_api_key_here
   WHATSAPP_API_KEY=your_whatsapp_api_key_here
   TWILIO_AUTH_TOKEN=your_twilio_token_here
   TWILIO_ACCOUNT_SID=your_account_sid_here
   ```

4. **Initialize the Application**
   ```bash
   python app.py
   ```

---

## 🚀 Usage

### Accessing Through WhatsApp
- Save the MediX AI number to your contacts
- Send your health-related query or symptom description
- Receive instant AI-generated health recommendations
- Continue the conversation with follow-up questions

### Accessing Through SMS
- Send your query to the designated SMS number
- Response will arrive within seconds
- Compatible with any mobile phone, even without internet

### Web Interface
- Open `index.html` in your web browser
- Enter your symptoms or health query
- View comprehensive recommendations and remedies

---

## 🔌 API Integration

### Gemini API Integration
- **Purpose**: Natural language understanding and health recommendation generation
- **Authentication**: API key-based authentication
- **Rate Limiting**: Configured for optimal performance and cost management

### WhatsApp Business API
- **Message Types**: Text, media, templates
- **Webhook Integration**: Handles incoming and outgoing messages
- **Status Tracking**: Monitor message delivery status

### SMS Integration (Twilio)
- **Two-Way Messaging**: Send and receive SMS programmatically
- **Fallback Support**: Ensures reachability without internet

---

## 📁 File Structure

```
MediX-AI/
├── index.html          # Web interface
├── style.css           # Styling and responsive design
├── app.py              # Main Python application
├── config.py           # Configuration settings
├── api_handlers/       # API integration modules
│   ├── gemini.py      # Gemini API wrapper
│   ├── whatsapp.py    # WhatsApp integration
│   └── sms.py         # SMS integration
├── health_data/        # Health knowledge base
├── requirements.txt    # Python dependencies
├── .env               # Environment variables (not in repo)
├── ReadMe.md          # This file
└── assets/            # Images, logos, and resources
```

---

## 🤝 Contributing

We welcome contributions from developers, healthcare professionals, and community members!

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Areas for Contribution
- Expanding health knowledge base
- Multi-language support
- Improved UI/UX
- Performance optimization
- Testing and bug fixes

---

## ⚖️ Disclaimer

**Important**: MediX AI is an AI-powered assistance tool designed to provide general health information and preliminary guidance only. It is **not** a substitute for professional medical advice, diagnosis, or treatment. Always consult with qualified healthcare professionals for serious health concerns or emergencies. In case of medical emergencies, please contact emergency services immediately.

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 📧 Contact & Support

For questions, suggestions, or bug reports, please open an issue on GitHub or contact us at support@medixai.com

---

**Last Updated**: January 2026
**Version**: 1.0.0