# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
<!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Coding Competition - Events</title>
      <link rel="stylesheet" href="styles.css">
    </head>
    <body>
      <div class="container">
        <div class="phone-frame">
          <div class="page events-page">
            <header>
              <div class="logo-section">
                <div class="college-logo">SAVEETHA ENGINEERING COLLEGE</div>
                <div class="badge">1216</div>
              </div>
            </header>

            <main class="content">
              <h1 class="page-title">COMPETITION CATEGORIES</h1>
              <p class="page-subtitle">Choose Your Challenge</p>

              <div class="events-list">
                <div class="event-item" data-difficulty="easy">
                  <div class="event-icon">🎯</div>
                  <div class="event-details">
                    <a href="register.html?event=algorithm-challenge" class="event-link">ALGORITHM CHALLENGE</a>
                    <span class="difficulty easy">Beginner</span>
                  </div>
                </div>

                <div class="event-item" data-difficulty="medium">
                  <div class="event-icon">🧩</div>
                  <div class="event-details">
                    <a href="register.html?event=data-structures" class="event-link">DATA STRUCTURES</a>
                    <span class="difficulty medium">Intermediate</span>
                  </div>
                </div>

                <div class="event-item" data-difficulty="medium">
                  <div class="event-icon">🌐</div>
                  <div class="event-details">
                    <a href="register.html?event=web-development" class="event-link">WEB DEVELOPMENT</a>
                    <span class="difficulty medium">Intermediate</span>
                  </div>
                </div>

                <div class="event-item" data-difficulty="hard">
                  <div class="event-icon">🤖</div>
                  <div class="event-details">
                    <a href="register.html?event=ai-ml-challenge" class="event-link">AI/ML CHALLENGE</a>
                    <span class="difficulty hard">Advanced</span>
                  </div>
                </div>

                <div class="event-item" data-difficulty="hard">
                  <div class="event-icon">🔐</div>
                  <div class="event-details">
                    <a href="register.html?event=cybersecurity" class="event-link">CYBERSECURITY</a>
                    <span class="difficulty hard">Advanced</span>
                  </div>
                </div>

                <div class="event-item" data-difficulty="medium">
                  <div class="event-icon">📱</div>
                  <div class="event-details">
                    <a href="register.html?event=mobile-app-dev" class="event-link">MOBILE APP DEV</a>
                    <span class="difficulty medium">Intermediate</span>
                  </div>
                </div>

                <div class="event-item" data-difficulty="hard">
                  <div class="event-icon">⚡</div>
                  <div class="event-details">
                    <a href="register.html?event=competitive-coding" class="event-link">COMPETITIVE CODING</a>
                    <span class="difficulty hard">Advanced</span>
                  </div>
                </div>
              </div>

              <div class="code-footer">
                <div class="terminal-line">
                  <span class="prompt">$</span>
                  <span class="command">register --now</span>
                  <span class="cursor">_</span>
                </div>
              </div>

              <a href="index.html" class="back-link">← Back to Home</a>
            </main>
          
    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Sports Day Events - Home</title>
      <link rel="stylesheet" href="styles.css">
    </head>
    <body>
      <div class="phone-frame">
        <div class="page home-page">
          <header>
            <div class="logo-container">
              <img src="https://via.placeholder.com/200x80/0066cc/ffffff?text=SAVEETHA+ENGINEERING+COLLEGE" alt="College Logo" class="college-logo">
              <div class="college-badge">1216</div>
            </div>
          </header>

          <main class="home-content">
            <div class="gear-logo">
              <svg viewBox="0 0 200 200" class="gear-icon">
                <circle cx="100" cy="100" r="80" fill="#0066cc" opacity="0.1"/>
                <path d="M100 40 L110 60 L130 50 L120 70 L140 80 L120 90 L130">  </path>
                <path d="M100 160 L90 140 L70 150 L80 130 L60 120 L80 110 L70">  </path>
              </svg>  
              <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Event Registration Form</title>
      <link rel="stylesheet" href="styles.css">
    </head>
    <body>
      <div class="container">
        <div class="phone-frame">
          <div class="page register-page">
            <header>
              <div class="logo-section">
                <img src="https://via.placeholder.com/150x50/0066cc/ffffff?text=SAVEETHA+COLLEGE" alt="College Logo" class="college-logo">
                <div class="badge">1216</div>
              </div>
            </header>

            <main class="content">
              <h1 class="form-title">EVENT REGISTRATION FORM</h1>
              <p class="form-subtitle">Fill the details</p>

              <form id="registrationForm" class="registration-form">
                <div class="form-group">
                  <input type="text" id="fullName" name="fullName" placeholder="Full Name" required>
                </div>

                <div class="form-group">
                  <select id="gender" name="gender" required>
                    <option value="">Gender</option>
                    <option value="male">Male</option>
                    <option value="female">Female</option>
                    <option value="other">Other</option>
                  </select>
                </div>

                <div class="form-group">
                  <input type="number" id="age" name="age" placeholder="Age" required min="1" max="100">
                </div>

                <div class="form-group">
                  <input type="text" id="registerNumber" name="registerNumber" placeholder="Register Number" required>
                </div>

                <div class="form-group">
                  <input type="text" id="department" name="department" placeholder="Department" required>
                </div>

                <div class="form-group">
                  <input type="tel" id="mobile" name="mobile" placeholder="Mobile Number" required pattern="[0-9]{10}">
                </div>

                <div class="form-group">
                  <input type="email" id="email" name="email" placeholder="Email ID" required>
                </div>

                <div class="form-group">
                  <select id="event" name="event" required>
                    <option value="">Events To Register</option>
                    <option value="cricket">Cricket</option>
                    <option value="badminton">Badminton</option>
                    <option value="volleyball">Volley Ball</option>
                    <option value="100mts">100 MTS</option>
                    <option value="200mts">200 MTS</option>
                    <option value="400mts">400 MTS</option>
                    <option value="4x100relay">4×100 Relay</option>
                  </select>
                </div>

                <button type="submit" class="btn btn-submit">REGISTER</button>
              </form>

              <div class="sports-silhouette">
                <svg viewBox="0 0 300 100" class="sports-svg">
                  <ellipse cx="150" cy="90" rx="120" ry="8" fill="#000" opacity="0.2"/>
                  <circle cx="200" cy="40" r="15" fill="#000" opacity="0.8"/>
                  <path d="M 200 55 L 200 70 L 190 85 M 200 70 L 210 85" stroke="#000" stroke-width="3" fill="none" opacity="0.8"/>
                  <path d="M 200 60 L 185 65 M 200 60 L 215 65" stroke="#000" stroke-width="3" fill="none" opacity="0.8"/>
                  <circle cx="220" cy="50" r="8" fill="#666"/>
                  <path d="M 100 70 Q 120 50 140 70" fill="#000" opacity="0.6"/>
                  <circle cx="120" cy="45" r="10" fill="#000" opacity="0.7"/>
                </svg>
              </div>

              <a href="events.html" class="back-link">← Back to Events</a>
            </main>
          </div>
        </div>
      </div>

      <script src="script.js"></script>
    </body>
    </html>
* {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Courier New', 'Consolas', monospace;
      background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 20px;
    }

    .container {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 100%;
      max-width: 1400px;
    }

    .phone-frame {
      width: 375px;
      height: 812px;
      background: #000;
      border-radius: 45px;
      padding: 12px;
      box-shadow: 0 30px 80px rgba(0, 0, 0, 0.8), 
                  0 0 0 1px rgba(255, 255, 255, 0.1),
                  inset 0 0 0 2px rgba(0, 0, 0, 0.9);
      position: relative;
    }

    .phone-frame::before {
      content: '';
      position: absolute;
      top: 0;
      left: 50%;
      transform: translateX(-50%);
      width: 140px;
      height: 28px;
      background: #000;
      border-radius: 0 0 20px 20px;
      z-index: 10;
    }

    .phone-frame::after {
      content: '';
      position: absolute;
      top: 8px;
      left: 50%;
      transform: translateX(-50%);
      width: 60px;
      height: 5px;
      background: #1a1a1a;
      border-radius: 10px;
      z-index: 11;
    }

    .page {
      width: 100%;
      height: 100%;
      border-radius: 35px;
      overflow-y: auto;
      position: relative;
      box-shadow: inset 0 0 20px rgba(0, 0, 0, 0.3);
    }

    .page::-webkit-scrollbar {
      width: 6px;
    }

    .page::-webkit-scrollbar-track {
      background: rgba(0, 0, 0, 0.2);
    }

    .page::-webkit-scrollbar-thumb {
      background: rgba(0, 255, 255, 0.3);
      border-radius: 10px;
    }

    header {
      padding: 35px 20px 15px;
      text-align: center;
      position: relative;
    }

    .logo-section {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 12px;
      position: relative;
      animation: slideDown 0.6s ease-out;
    }

    @keyframes slideDown {
      from {
        opacity: 0;
        transform: translateY(-20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .college-logo {
      background: linear-gradient(135deg, #00d4ff 0%, #0099cc 100%);
      color: #000;
      padding: 10px 15px;
      border-radius: 8px;
      font-size: 9px;
      font-weight: bold;
      box-shadow: 0 4px 15px rgba(0, 212, 255, 0.5);
      letter-spacing: 0.5px;
    }

    .badge {
      background: linear-gradient(135deg, #00ff88 0%, #00cc6a 100%);
      color: #000;
      padding: 10px 18px;
      border-radius: 8px;
      font-weight: bold;
      font-size: 18px;
      box-shadow: 0 4px 15px rgba(0, 255, 136, 0.5);
      animation: pulse 2s ease-in-out infinite;
    }

    @keyframes pulse {
      0%, 100% {
        transform: scale(1);
        box-shadow: 0 4px 15px rgba(0, 255, 136, 0.5);
      }
      50% {
        transform: scale(1.05);
        box-shadow: 0 6px 20px rgba(0, 255, 136, 0.7);
      }
    }

    .content {
      padding: 20px;
      text-align: center;
    }

    /* Home Page Styles */
    .home-page {
      background: linear-gradient(180deg, #0a0e27 0%, #1a1a2e 50%, #16213e 100%);
      position: relative;
      overflow: hidden;
    }

    .home-page::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: 
        repeating-linear-gradient(0deg, transparent, transparent 2px, rgba(0, 255, 255, 0.03) 2px, rgba(0, 255, 255, 0.03) 4px),
        repeating-linear-gradient(90deg, transparent, transparent 2px, rgba(0, 255, 255, 0.03) 2px, rgba(0, 255, 255, 0.03) 4px);
      pointer-events: none;
    }

    .code-animation {
      margin: 40px auto;
      position: relative;
      z-index: 1;
    }

    .code-symbol {
      font-size: 80px;
      font-weight: bold;
      background: linear-gradient(135deg, #00d4ff 0%, #00ff88 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      animation: glow 2s ease-in-out infinite;
      filter: drop-shadow(0 0 20px rgba(0, 212, 255, 0.5));
    }

    @keyframes glow {
      0%, 100% {
        filter: drop-shadow(0 0 20px rgba(0, 212, 255, 0.5));
      }
      50% {
        filter: drop-shadow(0 0 30px rgba(0, 255, 136, 0.8));
      }
    }

    .binary-rain {
      display: flex;
      justify-content: center;
      gap: 15px;
      margin-top: 20px;
      font-size: 14px;
      color: #00ff88;
      opacity: 0.6;
    }

    .binary-rain span {
      animation: fall 2s ease-in-out infinite;
    }

    .binary-rain span:nth-child(1) { animation-delay: 0s; }
    .binary-rain span:nth-child(2) { animation-delay: 0.2s; }
    .binary-rain span:nth-child(3) { animation-delay: 0.4s; }
    .binary-rain span:nth-child(4) { animation-delay: 0.6s; }
    .binary-rain span:nth-child(5) { animation-delay: 0.8s; }
    .binary-rain span:nth-child(6) { animation-delay: 1s; }
    .binary-rain span:nth-child(7) { animation-delay: 1.2s; }
    .binary-rain span:nth-child(8) { animation-delay: 1.4s; }

    @keyframes fall {
      0% {
        transform: translateY(-10px);
        opacity: 0;
      }
      50% {
        opacity: 1;
      }
      100% {
        transform: translateY(10px);
        opacity: 0;
      }
    }

    .main-title {
      font-size: 32px;
      font-weight: 900;
      background: linear-gradient(135deg, #00d4ff 0%, #00ff88 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      margin: 30px 0 10px;
      letter-spacing: 2px;
      position: relative;
      z-index: 1;
      animation: fadeInUp 0.8s ease-out;
      text-shadow: 0 0 30px rgba(0, 212, 255, 0.5);
    }

    .subtitle {
      font-size: 14px;
      color: #00d4ff;
      margin-bottom: 40px;
      opacity: 0.8;
      animation: fadeInUp 0.8s ease-out 0.2s backwards;
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .button-group {
      display: flex;
      flex-direction: column;
      gap: 20px;
      margin: 50px auto;
      max-width: 250px;
      position: relative;
      z-index: 1;
    }

    .btn {
      padding: 18px 40px;
      border: 2px solid;
      border-radius: 50px;
      font-size: 18px;
      font-weight: bold;
      cursor: pointer;
      text-decoration: none;
      display: flex;
      align-items: center;
      justify-content: space-between;
      transition: all 0.3s ease;
      text-transform: uppercase;
      letter-spacing: 1px;
      position: relative;
      overflow: hidden;
      font-family: 'Courier New', monospace;
    }

    .btn::before {
      content: '';
      position: absolute;
      top: 0;
      left: -100%;
      width: 100%;
      height: 100%;
      background: rgba(255, 255, 255, 0.1);
      transition: left 0.5s ease;
    }

    .btn:hover::before {
      left: 100%;
    }

    .btn:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
    }

    .btn-login {
      background: transparent;
      border-color: #00d4ff;
      color: #00d4ff;
      box-shadow: 0 0 20px rgba(0, 212, 255, 0.3);
    }

    .btn-login:hover {
      background: #00d4ff;
      color: #000;
      box-shadow: 0 0 30px rgba(0, 212, 255, 0.6);
    }

    .btn-register {
      background: linear-gradient(135deg, #00ff88 0%, #00cc6a 100%);
      border-color: #00ff88;
      color: #000;
      box-shadow: 0 0 20px rgba(0, 255, 136, 0.3);
    }

    .btn-register:hover {
      box-shadow: 0 0 30px rgba(0, 255, 136, 0.6);
    }

    .btn-icon {
      font-size: 20px;
      transition: transform 0.3s ease;
    }

    .btn:hover .btn-icon {
      transform: translateX(5px);
    }

    .tech-icons {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin: 50px 0 30px;
      position: relative;
      z-index: 1;
    }

    .tech-icon {
      font-size: 28px;
      color: #00d4ff;
      opacity: 0.6;
      animation: float 3s ease-in-out infinite;
    }

    .tech-icon:nth-child(1) { animation-delay: 0s; }
    .tech-icon:nth-child(2) { animation-delay: 0.5s; }
    .tech-icon:nth-child(3) { animation-delay: 1s; }
    .tech-icon:nth-child(4) { animation-delay: 1.5s; }

    @keyframes float {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-10px);
      }
    }

    .tagline {
      margin-top: 30px;
      font-size: 18px;
      font-weight: 900;
      color: #00ff88;
      background: rgba(0, 0, 0, 0.5);
      padding: 15px 30px;
      border-radius: 30px;
      display: inline-block;
      border: 2px solid #00ff88;
      box-shadow: 0 0 20px rgba(0, 255, 136, 0.3);
      position: relative;
      z-index: 1;
      animation: bounce 2s ease-in-out infinite;
    }

    .tagline-icon {
      font-size: 20px;
      animation: spin 3s linear infinite;
    }

    @keyframes bounce {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-10px);
      }
    }

    @keyframes spin {
      0% {
        transform: rotate(0deg);
      }
      100% {
        transform: rotate(360deg);
      }
    }

    /* Events Page Styles */
    .events-page {
      background: linear-gradient(180deg, #0a0e27 0%, #16213e 50%, #1a1a2e 100%);
      position: relative;
      overflow: hidden;
    }

    .events-page::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: 
        repeating-linear-gradient(0deg, transparent, transparent 2px, rgba(0, 212, 255, 0.03) 2px, rgba(0, 212, 255, 0.03) 4px),
        repeating-linear-gradient(90deg, transparent, transparent 2px, rgba(0, 212, 255, 0.03) 2px, rgba(0, 212, 255, 0.03) 4px);
      pointer-events: none;
    }

    .page-title {
      font-size: 26px;
      font-weight: 900;
      background: linear-gradient(135deg, #00d4ff 0%, #00ff88 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      margin-bottom: 10px;
      letter-spacing: 1px;
      position: relative;
      z-index: 1;
      animation: fadeInUp 0.6s ease-out;
    }

    .page-subtitle {
      font-size: 14px;
      color: #00d4ff;
      margin-bottom: 30px;
      opacity: 0.8;
      animation: fadeInUp 0.6s ease-out 0.2s backwards;
    }

    .events-list {
      background: rgba(0, 0, 0, 0.5);
      border-radius: 20px;
      padding: 20px;
      margin: 20px 0;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
      border: 1px solid rgba(0, 212, 255, 0.2);
      position: relative;
      z-index: 1;
      animation: scaleIn 0.5s ease-out;
    }

    @keyframes scaleIn {
      from {
        opacity: 0;
        transform: scale(0.9);
      }
      to {
        opacity: 1;
        transform: scale(1);
      }
    }

    .event-item {
      display: flex;
      align-items: center;
      gap: 15px;
      padding: 18px;
      margin: 12px 0;
      background: rgba(0, 212, 255, 0.05);
      border-radius: 15px;
      border: 1px solid rgba(0, 212, 255, 0.2);
      transition: all 0.3s ease;
      animation: slideInLeft 0.5s ease-out backwards;
    }

    .event-item:nth-child(1) { animation-delay: 0.1s; }
    .event-item:nth-child(2) { animation-delay: 0.2s; }
    .event-item:nth-child(3) { animation-delay: 0.3s; }
    .event-item:nth-child(4) { animation-delay: 0.4s; }
    .event-item:nth-child(5) { animation-delay: 0.5s; }
    .event-item:nth-child(6) { animation-delay: 0.6s; }
    .event-item:nth-child(7) { animation-delay: 0.7s; }

    @keyframes slideInLeft {
      from {
        opacity: 0;
        transform: translateX(-30px);
      }
      to {
        opacity: 1;
        transform: translateX(0);
      }
    }

    .event-item:hover {
      transform: translateX(8px);
      background: rgba(0, 212, 255, 0.1);
      border-color: #00d4ff;
      box-shadow: 0 5px 20px rgba(0, 212, 255, 0.3);
    }

    .event-icon {
      font-size: 28px;
      animation: bounce 2s ease-in-out infinite;
    }

    .event-details {
      flex: 1;
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      gap: 5px;
    }

    .event-link {
      color: #00d4ff;
      text-decoration: none;
      font-weight: bold;
      font-size: 15px;
      transition: color 0.3s ease;
    }

    .event-link:hover {
      color: #00ff88;
    }

    .difficulty {
      font-size: 11px;
      padding: 4px 10px;
      border-radius: 12px;
      font-weight: bold;
    }

    .difficulty.easy {
      background: rgba(0, 255, 136, 0.2);
      color: #00ff88;
      border: 1px solid #00ff88;
    }

    .difficulty.medium {
      background: rgba(255, 193, 7, 0.2);
      color: #ffc107;
      border: 1px solid #ffc107;
    }

    .difficulty.hard {
      background: rgba(255, 82, 82, 0.2);
      color: #ff5252;
      border: 1px solid #ff5252;
    }

    .code-footer {
      margin: 40px 0 20px;
      position: relative;
      z-index: 1;
    }

    .terminal-line {
      background: rgba(0, 0, 0, 0.7);
      border: 1px solid #00d4ff;
      border-radius: 10px;
      padding: 15px;
      font-family: 'Courier New', monospace;
      color: #00ff88;
      text-align: left;
      box-shadow: 0 0 20px rgba(0, 212, 255, 0.2);
    }

    .prompt {
      color: #00d4ff;
      margin-right: 10px;
    }

    .command {
      color: #00ff88;
    }

    .cursor {
      animation: blink 1s step-end infinite;
    }

    @keyframes blink {
      0%, 50% {
        opacity: 1;
      }
      51%, 100% {
        opacity: 0;
      }
    }

    /* Register Page Styles */
    .register-page {
      background: linear-gradient(180deg, #0a0e27 0%, #1a1a2e 50%, #16213e 100%);
      position: relative;
      overflow: hidden;
    }

    .register-page::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: 
        repeating-linear-gradient(0deg, transparent, transparent 2px, rgba(0, 255, 136, 0.03) 2px, rgba(0, 255, 136, 0.03) 4px),
        repeating-linear-gradient(90deg, transparent, transparent 2px, rgba(0, 255, 136, 0.03) 2px, rgba(0, 255, 136, 0.03) 4px);
      pointer-events: none;
    }

    .form-header {
      margin-bottom: 25px;
      animation: fadeInUp 0.6s ease-out;
    }

    .form-icon {
      font-size: 50px;
      margin-bottom: 15px;
      animation: bounce 2s ease-in-out infinite;
    }

    .form-title {
      font-size: 24px;
      font-weight: 900;
      background: linear-gradient(135deg, #00d4ff 0%, #00ff88 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      margin-bottom: 8px;
      letter-spacing: 1px;
    }

    .form-subtitle {
      font-size: 14px;
      color: #00d4ff;
      opacity: 0.8;
    }

    .registration-form {
      background: rgba(0, 0, 0, 0.5);
      border-radius: 20px;
      padding: 25px;
      margin: 20px 0;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
      border: 1px solid rgba(0, 212, 255, 0.2);
      position: relative;
      z-index: 1;
      animation: scaleIn 0.5s ease-out;
    }

    .form-group {
      margin-bottom: 20px;
      text-align: left;
      animation: slideInLeft 0.5s ease-out backwards;
    }

    .form-group:nth-child(1) { animation-delay: 0.1s; }
    .form-group:nth-child(2) { animation-delay: 0.15s; }
    .form-group:nth-child(3) { animation-delay: 0.2s; }
    .form-group:nth-child(4) { animation-delay: 0.25s; }
    .form-group:nth-child(5) { animation-delay: 0.3s; }
    .form-group:nth-child(6) { animation-delay: 0.35s; }
    .form-group:nth-child(7) { animation-delay: 0.4s; }
    .form-group:nth-child(8) { animation-delay: 0.45s; }

    .form-group label {
      display: flex;
      align-items: center;
      gap: 8px;
      color: #00d4ff;
      font-size: 13px;
      font-weight: bold;
      margin-bottom: 8px;
    }

    .label-icon {
      font-size: 16px;
    }

    .form-group input,
    .form-group select {
      width: 100%;
      padding: 14px 18px;
      border: 2px solid rgba(0, 212, 255, 0.3);
      border-radius: 12px;
      font-size: 14px;
      transition: all 0.3s ease;
      background: rgba(0, 0, 0, 0.5);
      color: #fff;
      font-family: 'Courier New', monospace;
    }

    .form-group input:focus,
    .form-group select:focus {
      outline: none;
      border-color: #00d4ff;
      box-shadow: 0 0 15px rgba(0, 212, 255, 0.3);
      transform: translateY(-2px);
    }

    .form-group input::placeholder {
      color: rgba(255, 255, 255, 0.4);
    }

    .form-group select {
      cursor: pointer;
    }

    .form-group select option {
      background: #1a1a2e;
      color: #fff;
    }

    .btn-submit {
      background: linear-gradient(135deg, #00ff88 0%, #00cc6a 100%);
      border-color: #00ff88;
      color: #000;
      width: 100%;
      margin-top: 15px;
      box-shadow: 0 0 20px rgba(0, 255, 136, 0.3);
      animation: slideInLeft 0.5s ease-out 0.5s backwards;
    }

    .btn-submit:hover {
      box-shadow: 0 0 30px rgba(0, 255, 136, 0.6);
    }

    /* Thank You Page Styles */
    .thankyou-page {
      background: linear-gradient(180deg, #0a0e27 0%, #16213e 50%, #1a1a2e 100%);
      position: relative;
      overflow: hidden;
    }

    .thankyou-page::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: 
        repeating-linear-gradient(0deg, transparent, transparent 2px, rgba(0, 255, 136, 0.03) 2px, rgba(0, 255, 136, 0.03) 4px),
        repeating-linear-gradient(90deg, transparent, transparent 2px, rgba(0, 255, 136, 0.03) 2px, rgba(0, 255, 136, 0.03) 4px);
      pointer-events: none;
    }

    .thank-you-content {
      padding: 20px;
      position: relative;
      z-index: 1;
    }

    .success-animation {
      position: relative;
      width: 120px;
      height: 120px;
      margin: 30px auto;
    }

    .checkmark {
      font-size: 70px;
      color: #00ff88;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      animation: zoomIn 0.6s ease-out;
    }

    .success-circle {
      width: 120px;
      height: 120px;
      border: 4px solid #00ff88;
      border-radius: 50%;
      animation: drawCircle 1s ease-out;
    }

    @keyframes zoomIn {
      from {
        opacity: 0;
        transform: translate(-50%, -50%) scale(0);
      }
      to {
        opacity: 1;
        transform: translate(-50%, -50%) scale(1);
      }
    }

    @keyframes drawCircle {
      from {
        transform: scale(0);
        opacity: 0;
      }
      to {
        transform: scale(1);
        opacity: 1;
      }
    }

    .thank-you-title {
      font-size: 40px;
      font-weight: 900;
      background: linear-gradient(135deg, #00d4ff 0%, #00ff88 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      margin: 30px 0;
      letter-spacing: 3px;
      animation: fadeInUp 0.8s ease-out 0.2s backwards;
    }

    .thank-you-message {
      font-size: 15px;
      line-height: 1.8;
      color: #00d4ff;
      margin: 30px 0;
      background: rgba(0, 0, 0, 0.5);
      padding: 25px;
      border-radius: 20px;
      border: 1px solid rgba(0, 212, 255, 0.2);
      box-shadow: 0 8px 25px rgba(0, 0, 0, 0.3);
      animation: fadeInUp 0.8s ease-out 0.4s backwards;
    }

    .thank-you-message strong {
      color: #00ff88;
      font-size: 17px;
    }

    .competition-info {
      display: flex;
      flex-direction: column;
      gap: 15px;
      margin: 30px 0;
      animation: fadeInUp 0.8s ease-out 0.6s backwards;
    }

    .info-card {
      display: flex;
      align-items: center;
      gap: 15px;
      background: rgba(0, 0, 0, 0.5);
      padding: 15px;
      border-radius: 15px;
      border: 1px solid rgba(0, 212, 255, 0.2);
      transition: all 0.3s ease;
    }

    .info-card:hover {
      border-color: #00d4ff;
      box-shadow: 0 5px 20px rgba(0, 212, 255, 0.3);
      transform: translateX(5px);
    }

    .info-icon {
      font-size: 30px;
    }

    .info-text {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      gap: 5px;
    }

    .info-text strong {
      color: #00d4ff;
      font-size: 14px;
    }

    .info-text span {
      color: #00ff88;
      font-size: 13px;
    }

    .contact-section {
      background: rgba(0, 0, 0, 0.5);
      border-radius: 20px;
      padding: 25px;
      margin: 30px 0;
      border: 1px solid rgba(0, 212, 255, 0.2);
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
      animation: fadeInUp 0.8s ease-out 0.8s backwards;
    }

    .contact-title {
      font-size: 20px;
      font-weight: 900;
      color: #00d4ff;
      margin-bottom: 15px;
      letter-spacing: 1px;
    }

    .contact-info {
      font-size: 14px;
      line-height: 2;
      color: #fff;
    }

    .contact-info strong {
      color: #00ff88;
      font-weight: 700;
    }

    .preparation-tips {
      background: rgba(0, 0, 0, 0.5);
      border-radius: 20px;
      padding: 25px;
      margin: 30px 0;
      border: 1px solid rgba(0, 255, 136, 0.2);
      text-align: left;
      animation: fadeInUp 0.8s ease-out 1s backwards;
    }

    .preparation-tips h3 {
      color: #00ff88;
      font-size: 18px;
      margin-bottom: 15px;
    }

    .preparation-tips ul {
      list-style: none;
      padding: 0;
    }

    .preparation-tips li {
      color: #00d4ff;
      font-size: 13px;
      padding: 8px 0;
      padding-left: 25px;
      position: relative;
    }

    .preparation-tips li::before {
      content: '▹';
      position: absolute;
      left: 0;
      color: #00ff88;
      font-size: 18px;
    }

    .btn-home {
      background: linear-gradient(135deg, #00d4ff 0%, #0099cc 100%);
      border-color: #00d4ff;
      color: #000;
      margin-top: 25px;
      box-shadow: 0 0 20px rgba(0, 212, 255, 0.3);
      animation: fadeInUp 0.8s ease-out 1.2s backwards;
    }

    .btn-home:hover {
      box-shadow: 0 0 30px rgba(0, 212, 255, 0.6);
    }

    .back-link {
      display: inline-block;
      margin-top: 25px;
      color: #00d4ff;
      text-decoration: none;
      font-weight: bold;
      padding: 12px 25px;
      background: rgba(0, 0, 0, 0.5);
      border-radius: 25px;
      border: 1px solid rgba(0, 212, 255, 0.3);
      transition: all 0.3s ease;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
      position: relative;
      z-index: 1;
      font-size: 14px;
    }

    .back-link:hover {
      background: rgba(0, 212, 255, 0.1);
      border-color: #00d4ff;
      transform: translateY(-2px);
      box-shadow: 0 6px 20px rgba(0, 212, 255, 0.3);
    }

    /* Responsive Design */
    @media (max-width: 480px) {
      .phone-frame {
        width: 100%;
        height: 100vh;
        border-radius: 0;
        padding: 0;
      }

      .phone-frame::before,
      .phone-frame::after {
        display: none;
      }

      .page {
        border-radius: 0;
      }
    }
document.addEventListener('DOMContentLoaded', function() {
      const form = document.getElementById('registrationForm');
      
      if (form) {
        const urlParams = new URLSearchParams(window.location.search);
        const eventParam = urlParams.get('event');
        
        if (eventParam) {
          const eventSelect = document.getElementById('event');
          if (eventSelect) {
            eventSelect.value = eventParam;
          }
        }

        form.addEventListener('submit', function(e) {
          e.preventDefault();
          
          const formData = {
            fullName: document.getElementById('fullName').value,
            gender: document.getElementById('gender').value,
            age: document.getElementById('age').value,
            registerNumber: document.getElementById('registerNumber').value,
            department: document.getElementById('department').value,
            mobile: document.getElementById('mobile').value,
            email: document.getElementById('email').value,
            event: document.getElementById('event').value
          };

          console.log('Registration Data:', formData);
          
          localStorage.setItem('registrationData', JSON.stringify(formData));
          
          window.location.href = 'thankyou.html';
        });
      }
    });
```

## OUTPUT:
![screenshot6767](https://github.com/user-attachments/assets/e7d57685-c547-4b5a-8c5b-600ce7626015)
![screenshot4554](https://github.com/user-attachments/assets/8c06c270-79e1-4d64-917a-e892252bbb24)

![screen shot 43568](https://github.com/user-attachments/assets/f2096caf-9d5e-479b-91da-33224fc827ae)



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
