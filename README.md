# 🛍️ E‑Commerce Chatbot

**Project Summary**
A lightweight, frontend-only chatbot that simulates customer support for an e-commerce site. Customers can register, log in, and ask common questions like "price", "delivery", "return", or "warranty". The bot replies with predefined helpful responses and tracks chat history.

---

## 🔧 Technology Stack

* **HTML5** – semantic structure and forms
* **CSS3** – Styling with flexbox, responsive design, themes
* **JavaScript (ES6)** – DOM manipulation, form behavior, chat logic

  * LocalStorage for user and chat history persistence
  * Modular functions for message flow
* (Optional) **Git & GitHub** – version control and collaboration

---

## ⚙️ Setup & Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/your-username/ecommerce-chatbot.git
   cd ecommerce-chatbot
   ```

2. **Serve the project**
   You can use the Live Server VSCode extension or a simple server:

   ```bash
   # Using Python 3
   python3 -m http.server 5500
   ```

   Navigate to `http://localhost:5500/frontend/index.html`.

3. **Register & Login**

   * Enter your email > click **Register**
   * Confirm registration alert
   * Use the same email to log in

4. **Begin Chatting**

   * Use chatbot input to ask questions like “price”, “delivery”, etc.
   * View chat responses and timestamps in the chat window
   * Save and review chat history

---
## Output Screenshot

**Signup**            - https://files.oaiusercontent.com/file-K6e1pYQVYB6YTnk2iPN7hV?se=2025-06-14T10%3A21%3A30Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D299%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3D2a637369-3377-41e5-9bd9-318f3eba5c11.png&sig=dc8f1G%2BTyKagj9ZJ3IpInNY/621uAJ2SW5Wh3O%2BtOPM%3D
                        https://files08.oaiusercontent.com/file-A3KmLtBZnm7zKy5to4zKXm?se=2025-06-14T10%3A21%3A30Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D299%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3D09f9d69a-1568-4e5b-8bff-b4219f087041.png&sig=kstb7QfdStzp/0D2qZvuf9AfS1oVveFfabLaAfsQQxE%3D
                        
**Login**             - https://files09.oaiusercontent.com/file-TjHpuuEFCrEjVAMiy6ZtyR?se=2025-06-14T10%3A21%3A30Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D299%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3Dad399bcf-93d2-4845-ad21-aeebfabfcba8.png&sig=26jBOcF5RaR4%2B1K%2B8zuSNZSkGGu3D5%2BQmAQ%2BLykqzi4%3D
                        https://files09.oaiusercontent.com/file-8oZW6jJziWoQkpMzRypVUw?se=2025-06-14T10%3A21%3A30Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D299%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3D9514448b-a1a2-42d7-bd09-6d2632dca81a.png&sig=cPefPoQOttstrd2ShQQeXztrBiABpMsgwntnXFWSrFY%3D
                        
**Ecommerce Chatbot** - https://files.oaiusercontent.com/file-7YouMJ9F6PUEJDPHzcGnhn?se=2025-06-14T10%3A21%3A30Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D299%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3D235dd0b0-56bb-449c-90ac-32e79609901b.png&sig=0Dj1syIYiaxOr8RgGxnJpN16MLzwRRnB5KBy2PKeFJM%3D

**User Enquiry**      - https://files.oaiusercontent.com/file-Tn3wiGDvXjubKni6sujZrC?se=2025-06-14T10%3A21%3A30Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D299%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3Ded586ec3-962d-4dab-aaac-19385b7f3b06.png&sig=O0%2BX5MFjyHIFfw7eHBjded/3cOF3XSNMUQ/1STzU4i0%3D

**Rest**              - https://files.oaiusercontent.com/file-7YouMJ9F6PUEJDPHzcGnhn?se=2025-06-14T10%3A21%3A30Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D299%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3D235dd0b0-56bb-449c-90ac-32e79609901b.png&sig=0Dj1syIYiaxOr8RgGxnJpN16MLzwRRnB5KBy2PKeFJM%3D

**History**           - https://files09.oaiusercontent.com/file-G1w6hqo7tKHWtGbKJfTwCt?se=2025-06-14T10%3A21%3A30Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D299%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3Dcf47889f-3052-41ba-863c-3aabdd409454.png&sig=MIrvFNoEQiLo87MPwYU4Os8PFfdyF2rE/8HWAqCwFeo%3D



## 🎯 Sample Queries & Bot Responses

| **User Input**             | **Bot Response**                                                                          |
| -------------------------- | ----------------------------------------------------------------------------------------- |
| "Hi" / "Hello"             | "Hello! How can I help you today?"                                                        |
| "price" / "cost"           | "Prices vary depending on the product. You can check our product page…"                   |
| "delivery time"            | "Delivery usually takes 3-5 business days."                                               |
| "return policy" / "refund" | "We offer a 7‑day easy return policy. Refunds are processed within 2-3 days."             |
| "warranty"                 | "Most products come with a 1‑year warranty. Please check the product description…"        |
| Anything else              | "Sorry, I didn't understand that. Please ask about price, delivery, return, or warranty." |

The chat window shows both sides of the conversation with timestamps, and users can click **History** to see a summary alert with all previous messages.

---

## 🚀 Project Demonstration (for Recruitment Presentations)

**Project Goal**

* Demonstrated ability to build an interactive UI with user authentication, dynamic messaging, and state persistence.

**Technical Highlights**

* Pure frontend—no backend dependency; all logic runs in the browser
* Clean component toggling: registration → login → chat interface
* Modular JavaScript: message creation, response logic, timestamp handling
* Use of LocalStorage for a smooth, stateful user experience

**Key Learnings**

* Real-time DOM updates and UI states (show/hide, append messages)
* Handling browser storage and serializing chat sessions
* Working with forms and validation (email format checks)
* Structuring code for maintainability and scalability

---

## 📝 Setup Summary for Panel

1. **Demo Flow**:

   * Open `index.html`
   * Show registration → login → chat
   * Ask questions, view responses and stored chat history

2. **Discuss Architecture**:

   * State transitions between views (JS + CSS)
   * Chatbot logic and response handlers
   * Persistent data storage and retrieval

3. **Talk about Enhancements**:

   * Adding backend integration (Node/Express + Mongo)
   * Enabling NLP (e.g., Dialogflow, OpenAI fallback)
   * Including real product retrieval via APIs
   * Richer UI/UX: interactive buttons, carousels, real-time input

---

## 📂 File Structure Overview

```
ecommerce-chatbot/
├── frontend/
│   ├── index.html         # UI structure for sign-in, login, and chat
│   ├── style.css          # Visual design, responsive layout
│   └── app.js             # Core chatbot logic, view switches, storage
└── README.md              # This documentation
```

---

## ✅ Next Steps & Roadmap

* **Backend logic**: user auth, real chatbot
* **Product integration**: dynamic responses via API
* **UI polish**: avatars, animations, improved mobile UX
* **Testing**: unit tests, form validations, browser compatibility


