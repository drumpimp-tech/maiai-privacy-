[privacy.html](https://github.com/user-attachments/files/25673094/privacy.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MAIAI — Privacy Policy</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700;900&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --gold: #FFD700;
      --silver: #C0C0C0;
      --bg: #05080A;
      --surface: #0F1820;
      --surface2: #162030;
      --text: #ffffff;
      --muted: #8A96A8;
    }

    body {
      background-color: var(--bg);
      color: var(--text);
      font-family: 'DM Sans', sans-serif;
      font-weight: 300;
      line-height: 1.8;
      min-height: 100vh;
    }

    /* Background texture */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background:
        radial-gradient(ellipse 80% 40% at 50% -10%, rgba(255,215,0,0.07) 0%, transparent 70%),
        radial-gradient(ellipse 60% 30% at 80% 100%, rgba(192,192,192,0.04) 0%, transparent 60%);
      pointer-events: none;
      z-index: 0;
    }

    .container {
      position: relative;
      z-index: 1;
      max-width: 760px;
      margin: 0 auto;
      padding: 0 24px 80px;
    }

    /* Header */
    header {
      text-align: center;
      padding: 64px 0 48px;
      border-bottom: 1px solid rgba(255,215,0,0.15);
      margin-bottom: 56px;
    }

    .logo {
      font-family: 'Playfair Display', serif;
      font-size: clamp(48px, 8vw, 72px);
      font-weight: 900;
      color: var(--gold);
      letter-spacing: 6px;
      text-shadow: 0 0 40px rgba(255,215,0,0.25);
      margin-bottom: 8px;
    }

    .tagline {
      font-size: 11px;
      font-weight: 500;
      letter-spacing: 5px;
      color: var(--silver);
      text-transform: uppercase;
      margin-bottom: 28px;
    }

    .doc-title {
      font-size: 13px;
      font-weight: 500;
      letter-spacing: 3px;
      color: var(--muted);
      text-transform: uppercase;
    }

    .updated {
      display: inline-block;
      margin-top: 10px;
      font-size: 12px;
      color: var(--muted);
      background: var(--surface);
      border: 1px solid rgba(255,215,0,0.15);
      border-radius: 20px;
      padding: 4px 14px;
    }

    /* Sections */
    section {
      margin-bottom: 44px;
    }

    .section-number {
      font-size: 10px;
      font-weight: 500;
      letter-spacing: 3px;
      color: var(--gold);
      text-transform: uppercase;
      margin-bottom: 6px;
    }

    h2 {
      font-family: 'Playfair Display', serif;
      font-size: clamp(20px, 3vw, 26px);
      font-weight: 700;
      color: var(--text);
      margin-bottom: 16px;
      line-height: 1.3;
    }

    p {
      color: var(--muted);
      font-size: 15px;
      margin-bottom: 12px;
    }

    p:last-child { margin-bottom: 0; }

    ul {
      list-style: none;
      margin: 12px 0;
      padding: 0;
    }

    ul li {
      color: var(--muted);
      font-size: 15px;
      padding: 6px 0 6px 20px;
      position: relative;
    }

    ul li::before {
      content: '—';
      position: absolute;
      left: 0;
      color: var(--gold);
      font-weight: 700;
    }

    /* Card style for key sections */
    .card {
      background: var(--surface);
      border: 1px solid rgba(255,215,0,0.12);
      border-radius: 12px;
      padding: 28px 32px;
    }

    .card p, .card ul li { color: rgba(255,255,255,0.75); }

    /* Highlight box */
    .highlight {
      background: rgba(255,215,0,0.06);
      border-left: 3px solid var(--gold);
      border-radius: 0 8px 8px 0;
      padding: 16px 20px;
      margin: 20px 0;
    }

    .highlight p {
      color: rgba(255,255,255,0.8);
      font-size: 14px;
      margin: 0;
    }

    /* Divider */
    .divider {
      border: none;
      border-top: 1px solid rgba(255,255,255,0.06);
      margin: 0 0 44px;
    }

    /* Contact */
    .contact-box {
      background: var(--surface2);
      border: 1px solid rgba(255,215,0,0.2);
      border-radius: 12px;
      padding: 32px;
      text-align: center;
    }

    .contact-box h2 { margin-bottom: 10px; }

    .contact-box p { margin-bottom: 20px; }

    .email-link {
      display: inline-block;
      color: var(--gold);
      font-size: 15px;
      font-weight: 500;
      letter-spacing: 1px;
      text-decoration: none;
      border-bottom: 1px solid rgba(255,215,0,0.4);
      padding-bottom: 2px;
      transition: border-color 0.2s, color 0.2s;
    }

    .email-link:hover {
      color: #fff;
      border-color: #fff;
    }

    /* Footer */
    footer {
      text-align: center;
      padding-top: 48px;
      border-top: 1px solid rgba(255,255,255,0.06);
    }

    footer .logo-sm {
      font-family: 'Playfair Display', serif;
      font-size: 22px;
      font-weight: 900;
      color: var(--gold);
      letter-spacing: 4px;
      margin-bottom: 8px;
    }

    footer p {
      font-size: 12px;
      color: var(--muted);
      margin: 0;
    }
  </style>
</head>
<body>
  <div class="container">

    <header>
      <div class="logo">MAIAI</div>
      <div class="tagline">Pronounced "My-AI"</div>
      <div class="doc-title">Privacy Policy</div>
      <div class="updated">Last updated: March 1, 2026</div>
    </header>

    <section>
      <div class="section-number">01</div>
      <h2>Introduction</h2>
      <div class="card">
        <p>MAIAI ("the App") is developed and operated by <strong style="color:#fff;">Trevbeats Multimedia</strong>. This Privacy Policy explains what information we collect, how we use it, and your rights regarding that information.</p>
        <p>By using MAIAI, you agree to the practices described in this policy. If you do not agree, please discontinue use of the App.</p>
      </div>
    </section>

    <hr class="divider" />

    <section>
      <div class="section-number">02</div>
      <h2>Information We Collect</h2>
      <p>MAIAI is designed with your privacy in mind. We collect minimal data necessary to operate the App.</p>
      <ul>
        <li><strong style="color:#fff;">Session Name</strong> — A name you enter locally to personalize your session. This is stored only on your device.</li>
        <li><strong style="color:#fff;">Usage Preferences</strong> — Category selections and interest scores used to personalize your Daily Drop notification. Stored locally on your device via UserDefaults.</li>
        <li><strong style="color:#fff;">User Notes & Prompts</strong> — Notes and prompt text you write in the Workbench are stored locally on your device only.</li>
        <li><strong style="color:#fff;">AI Prompt Requests</strong> — When you use the Enhance feature, your prompt text is sent to our secure Firebase proxy server to generate a response via the Anthropic API. This data is not logged or stored after the response is returned.</li>
        <li><strong style="color:#fff;">Notification Preferences</strong> — Your chosen Daily Drop time is stored locally on your device.</li>
      </ul>
    </section>

    <hr class="divider" />

    <section>
      <div class="section-number">03</div>
      <h2>How We Use Your Information</h2>
      <p>We use the information described above solely to:</p>
      <ul>
        <li>Provide and improve core App functionality</li>
        <li>Personalize AI tool recommendations based on your interests</li>
        <li>Deliver your chosen Daily Drop notification</li>
        <li>Generate enhanced prompts via the MAIAI AI service</li>
      </ul>
      <div class="highlight">
        <p>We do <strong>not</strong> sell, rent, trade, or share your personal information with third parties for advertising or marketing purposes.</p>
      </div>
    </section>

    <hr class="divider" />

    <section>
      <div class="section-number">04</div>
      <h2>Third-Party Services</h2>
      <p>MAIAI uses the following third-party services to operate:</p>
      <ul>
        <li><strong style="color:#fff;">Firebase (Google)</strong> — Used as a secure proxy server to route AI requests. Firebase may collect standard server-side logs (IP address, timestamps). View Google's privacy policy at <a href="https://policies.google.com/privacy" target="_blank" style="color:var(--gold);">policies.google.com/privacy</a>.</li>
        <li><strong style="color:#fff;">Anthropic API</strong> — Powers the AI Enhance feature. Prompt text is transmitted to Anthropic's servers to generate responses. View Anthropic's privacy policy at <a href="https://www.anthropic.com/privacy" target="_blank" style="color:var(--gold);">anthropic.com/privacy</a>.</li>
        <li><strong style="color:#fff;">Apple (iOS Platform)</strong> — Standard iOS services including push notifications, speech recognition, and Spotlight indexing are subject to Apple's privacy policy.</li>
      </ul>
    </section>

    <hr class="divider" />

    <section>
      <div class="section-number">05</div>
      <h2>Data Storage & Security</h2>
      <p>The majority of your data — including your session name, notes, prompts, stacks, and preferences — is stored <strong style="color:#fff;">locally on your device</strong> and never transmitted to our servers.</p>
      <p>AI Enhance requests are transmitted over HTTPS to our Firebase proxy. We do not store these requests after processing. We implement industry-standard security practices to protect data in transit.</p>
    </section>

    <hr class="divider" />

    <section>
      <div class="section-number">06</div>
      <h2>Children's Privacy</h2>
      <p>MAIAI is not directed to children under the age of 13. We do not knowingly collect personal information from children. If you believe a child has provided us with personal information, please contact us and we will delete it promptly.</p>
    </section>

    <hr class="divider" />

    <section>
      <div class="section-number">07</div>
      <h2>Your Rights</h2>
      <p>Since most data is stored locally on your device, you have full control over it at any time. You may:</p>
      <ul>
        <li>Delete the App to remove all locally stored data</li>
        <li>Clear app data via iOS Settings</li>
        <li>Contact us to request information about any server-side data</li>
      </ul>
    </section>

    <hr class="divider" />

    <section>
      <div class="section-number">08</div>
      <h2>Changes to This Policy</h2>
      <p>We may update this Privacy Policy from time to time. When we do, we will update the "Last updated" date at the top of this page. Continued use of the App after any changes constitutes your acceptance of the new policy.</p>
    </section>

    <hr class="divider" />

    <section>
      <div class="contact-box">
        <div class="section-number" style="text-align:center;">09</div>
        <h2>Contact Us</h2>
        <p>If you have any questions or concerns about this Privacy Policy, please reach out:</p>
        <a href="mailto:trevbeatsmultimedia@gmail.com" class="email-link">trevbeatsmultimedia@gmail.com</a>
        <p style="margin-top:16px; font-size:13px;">Trevbeats Multimedia</p>
      </div>
    </section>

    <footer>
      <div class="logo-sm">MAIAI</div>
      <p>© 2026 Trevbeats Multimedia. All rights reserved.</p>
    </footer>

  </div>
</body>
</html>
