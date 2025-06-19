
# 📧 Email Assistant

A full-stack Email Assistant Crome Extension built with:

- 🔧 **Backend**: Java Spring Boot
- 💻 **Frontend**: JavaScript (Vanilla/Extension)

This extension uses AI (like Gemini) to help users compose professional email replys faster and more efficiently.
<br>
It adds a button left to send button on your gmail interface by clicking on this button you can auto generate a reply for your following mail

![Screenshot 2025-06-19 182207](https://github.com/user-attachments/assets/45c4ac98-c9c6-40b3-bcef-cd0030ac70f1)

---

## 📁 Project Structure
<br>
email-assistant/
<br>
├── backend/ → Spring Boot backend (email generation, API logic)
<br>
├── frontend/ → JavaScript frontend (extension or web UI)

---


### ⚙️ Backend (Spring Boot)

1. Open the `backend/` directory in your IDE (Eclipse/IntelliJ).
2. Configure application properties (e.g., API keys, ports).
3. Run the main class:

```bash
./gradlew bootRun   # If using Gradle
# or
mvn spring-boot:run # If using Maven

---

#### 🌐 Frontend (JavaScript)
Open the frontend/ directory in VS Code.

# If it's a web app:

npm install
npm run dev  # Or npm run start


---

Browser extension, load it manually in Chrome:

Go to chrome://extensions/

Enable "Developer mode"

Click "Load unpacked" and select the frontend/ folder

--- 

##### 🔑 Environment Variables
<br>

Make sure to add your API keys (like Gemini/OpenAI) in the appropriate config file:

backend/src/main/resources/application.properties

.env for frontend if needed



