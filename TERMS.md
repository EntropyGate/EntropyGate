<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="EntropyGate Terms of Service - Zero-knowledge password manager">
    <title>Terms of Service - EntropyGate</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        :root {
            --bg: #ffffff;
            --text: #1a1a1a;
            --secondary: #666666;
            --accent: #8b5cf6;
            --border: #e5e5e5;
            --code-bg: #f5f5f5;
        }
        
        @media (prefers-color-scheme: dark) {
            :root {
                --bg: #0a0a0a;
                --text: #ffffff;
                --secondary: #a0a0a0;
                --accent: #a78bfa;
                --border: #2a2a2a;
                --code-bg: #1a1a1a;
            }
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;
            background: var(--bg);
            color: var(--text);
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        
        header {
            text-align: center;
            margin-bottom: 60px;
            padding-bottom: 30px;
            border-bottom: 2px solid var(--border);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            background: linear-gradient(135deg, var(--accent), #ec4899);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .tagline {
            color: var(--secondary);
            font-size: 1.1rem;
            font-weight: 500;
            margin-top: 10px;
        }
        
        .meta {
            color: var(--secondary);
            font-size: 0.9rem;
            margin-top: 20px;
        }
        
        h2 {
            font-size: 1.8rem;
            margin-top: 50px;
            margin-bottom: 20px;
            color: var(--text);
        }
        
        h3 {
            font-size: 1.3rem;
            margin-top: 30px;
            margin-bottom: 15px;
            color: var(--text);
        }
        
        p, li {
            margin-bottom: 15px;
            color: var(--text);
        }
        
        ul, ol {
            margin-left: 30px;
            margin-bottom: 20px;
        }
        
        li {
            margin-bottom: 10px;
        }
        
        strong {
            color: var(--accent);
            font-weight: 600;
        }
        
        code {
            background: var(--code-bg);
            padding: 2px 6px;
            border-radius: 4px;
            font-family: 'Monaco', 'Courier New', monospace;
            font-size: 0.9em;
        }
        
        .highlight {
            background: var(--code-bg);
            border-left: 4px solid var(--accent);
            padding: 20px;
            margin: 30px 0;
            border-radius: 8px;
        }
        
        .warning {
            background: #fef3c7;
            border-left: 4px solid #f59e0b;
            padding: 20px;
            margin: 30px 0;
            border-radius: 8px;
            color: #92400e;
        }
        
        @media (prefers-color-scheme: dark) {
            .warning {
                background: #451a03;
                color: #fbbf24;
            }
        }
        
        .contact {
            background: var(--code-bg);
            padding: 30px;
            border-radius: 12px;
            margin: 40px 0;
        }
        
        a {
            color: var(--accent);
            text-decoration: none;
        }
        
        a:hover {
            text-decoration: underline;
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        
        th, td {
            border: 1px solid var(--border);
            padding: 12px;
            text-align: left;
        }
        
        th {
            background: var(--code-bg);
            font-weight: 600;
        }
        
        footer {
            text-align: center;
            margin-top: 80px;
            padding-top: 40px;
            border-top: 2px solid var(--border);
            color: var(--secondary);
            font-size: 0.9rem;
        }
        
        @media (max-width: 600px) {
            h1 {
                font-size: 2rem;
            }
            
            h2 {
                font-size: 1.5rem;
            }
            
            .container {
                padding: 20px 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Terms of Service</h1>
            <div class="tagline">Stop Guessing. Start Calculating.</div>
            <div class="meta">
                <strong>Effective Date:</strong> January 11, 2026<br>
                <strong>Last Updated:</strong> January 11, 2026
            </div>
        </header>

        <main>
            <p>By downloading, installing, or using EntropyGate ("the App"), you agree to these Terms of Service ("Terms"). If you do not agree, do not use the App.</p>

            <h2>1. Service Description</h2>
            <p>EntropyGate is a zero-knowledge password manager for iOS. The App allows you to:</p>
            <ul>
                <li>Store passwords encrypted with AES-256-GCM on your device</li>
                <li>Optionally sync encrypted data via cloud storage (Supabase)</li>
                <li>Access passwords using a master password or biometric authentication</li>
            </ul>
            
            <div class="highlight">
                <p><strong>Core Principle</strong>: Your master key never leaves your device. We cannot decrypt your passwords.</p>
            </div>

            <h2>2. Account Registration</h2>
            
            <h3>Free Tier</h3>
            <ul>
                <li>No account required for local-only password storage</li>
                <li>Limited to 5 passwords</li>
            </ul>

            <h3>Cloud Sync (Optional)</h3>
            <ul>
                <li>Requires email address for account creation</li>
                <li>Your encrypted data is stored on our Supabase backend</li>
                <li>You are responsible for maintaining the confidentiality of your master password</li>
            </ul>

            <h2>3. Subscription Terms</h2>

            <h3>EntropyGate Pro - Monthly Subscription</h3>
            <ul>
                <li><strong>Price</strong>: $4.99 per month (USD)</li>
                <li><strong>Billing</strong>: Charged to your Apple ID account at confirmation of purchase</li>
                <li><strong>Auto-Renewal</strong>: Subscription automatically renews unless canceled at least 24 hours before the end of the current period</li>
                <li><strong>Cancellation</strong>: Manage subscriptions in your iPhone Settings → Apple ID → Subscriptions</li>
            </ul>

            <h3>EntropyGate Pro - Lifetime Access</h3>
            <ul>
                <li><strong>Price</strong>: $99.99 (USD), one-time payment</li>
                <li><strong>Non-Refundable</strong>: Lifetime purchases are final (subject to Apple's refund policies)</li>
                <li><strong>Transferability</strong>: Tied to your Apple ID; transfers with account</li>
            </ul>

            <h3>Refunds</h3>
            <p>Refunds are handled by Apple. See <a href="https://support.apple.com/en-us/HT204084" target="_blank">Apple's refund policy</a>.</p>

            <h2>4. User Responsibilities</h2>
            <p>You agree to:</p>
            <ul>
                <li><strong>Secure Your Master Password</strong>: We cannot recover lost master passwords. If you forget it, your data is permanently inaccessible.</li>
                <li><strong>Comply with Laws</strong>: Use the App only for lawful purposes</li>
                <li><strong>One User Per Account</strong>: Do not share your account credentials</li>
                <li><strong>Backup Responsibility</strong>: While we provide cloud sync, you are responsible for exporting and backing up critical passwords</li>
            </ul>

            <h2>5. Prohibited Uses</h2>
            <p>You may NOT:</p>
            <ul>
                <li>Reverse engineer, decompile, or attempt to extract the App's source code</li>
                <li>Use the App to store illegal content</li>
                <li>Attempt to bypass security features or rate limits</li>
                <li>Violate any applicable laws or regulations</li>
            </ul>

            <h2>6. Data Security and Liability</h2>

            <h3>Our Zero-Knowledge Commitment</h3>
            <ul>
                <li>We encrypt your passwords on your device before cloud storage</li>
                <li>We do not have access to your master key</li>
                <li>In the event of a data breach, attackers would obtain only useless ciphertext</li>
            </ul>

            <div class="warning">
                <h3>⚠️ Limitation of Liability</h3>
                <p><strong>IMPORTANT</strong>: Because we use zero-knowledge encryption, <strong>we cannot recover your passwords if you lose your master password</strong>. You acknowledge this risk by using the App.</p>
            </div>

            <p>To the maximum extent permitted by law:</p>
            <ul>
                <li><strong>No Warranty</strong>: The App is provided "as is" without warranties of any kind</li>
                <li><strong>Liability Cap</strong>: Our total liability for any claim shall not exceed the amount you paid for the App in the past 12 months</li>
                <li><strong>No Consequential Damages</strong>: We are not liable for lost profits, data loss, or indirect damages</li>
            </ul>

            <h3>Force Majeure</h3>
            <p>We are not liable for failures caused by events beyond our control (e.g., server outages, natural disasters, third-party service failures).</p>

            <h2>7. Intellectual Property</h2>

            <h3>Our Rights</h3>
            <ul>
                <li>EntropyGate, its logo, and all related trademarks are owned by the developer</li>
                <li>The App's code, design, and documentation are protected by copyright</li>
            </ul>

            <h3>Your Rights</h3>
            <ul>
                <li>You retain ownership of your password data</li>
                <li>You may export your data at any time (Pro users)</li>
            </ul>

            <h2>8. Third-Party Services</h2>
            <p>The App integrates with:</p>
            <ul>
                <li><strong>Supabase</strong> (cloud database): <a href="https://supabase.com/terms" target="_blank">Supabase Terms</a></li>
                <li><strong>RevenueCat</strong> (subscription management): <a href="https://www.revenuecat.com/terms" target="_blank">RevenueCat Terms</a></li>
                <li><strong>Apple App Store</strong>: <a href="https://www.apple.com/legal/internet-services/itunes/dev/stdeula/" target="_blank">Apple Terms</a></li>
            </ul>
            <p>Your use of these services is subject to their respective terms.</p>

            <h2>9. Privacy</h2>
            <p>Your privacy is governed by our <a href="privacy.html">Privacy Policy</a>. Key points:</p>
            <ul>
                <li>We use zero-knowledge encryption</li>
                <li>We do not sell your data</li>
                <li>We cannot read your passwords</li>
            </ul>

            <h2>10. Termination</h2>

            <h3>By You</h3>
            <ul>
                <li>Delete your account via Settings → Account → Delete Account</li>
                <li>Cancel subscriptions via iPhone Settings → Apple ID → Subscriptions</li>
            </ul>

            <h3>By Us</h3>
            <p>We may suspend or terminate your account if you:</p>
            <ul>
                <li>Violate these Terms</li>
                <li>Engage in fraudulent activity</li>
                <li>Abuse our services (e.g., excessive API requests)</li>
            </ul>
            <p>Upon termination, your encrypted data will be deleted within 30 days.</p>

            <h2>11. Changes to Terms</h2>
            <p>We may update these Terms at any time. Changes will be communicated via:</p>
            <ul>
                <li>In-app notification</li>
                <li>Updated "Last Modified" date</li>
            </ul>
            <p>Continued use of the App after changes constitutes acceptance.</p>

            <h2>12. Governing Law</h2>
            <p>These Terms are governed by the laws of <strong>[Your State/Country]</strong> (e.g., "the State of California, USA"), without regard to conflict of law principles.</p>

            <h2>13. Dispute Resolution</h2>

            <h3>Informal Resolution</h3>
            <p>Before filing a claim, contact us at <a href="mailto:Entropy-Gate@proton.me">Entropy-Gate@proton.me</a> to resolve disputes informally.</p>

            <h3>Arbitration (Optional - Consult Legal Counsel)</h3>
            <p>If you are a U.S. user, disputes may be resolved through binding arbitration under the American Arbitration Association rules. You waive the right to a jury trial or class action lawsuit.</p>
            <p><em>(Note: Arbitration clauses should be reviewed by legal counsel. This is a placeholder.)</em></p>

            <h2>14. Severability</h2>
            <p>If any provision of these Terms is found invalid, the remaining provisions remain in effect.</p>

            <h2>15. Entire Agreement</h2>
            <p>These Terms, together with our Privacy Policy, constitute the entire agreement between you and EntropyGate.</p>

            <div class="contact">
                <h2>Contact Us</h2>
                <p>Questions about these Terms?<br>
                Email: <a href="mailto:Entropy-Gate@proton.me"><strong>Entropy-Gate@proton.me</strong></a></p>
            </div>

            <div class="highlight">
                <h2>Stop Guessing. Start Calculating.</h2>
                <p>Your security is mathematical, not aspirational.</p>
            </div>
        </main>

        <footer>
            <p><strong>EntropyGate</strong> | Stop Guessing. Start Calculating.</p>
            <p>This Terms of Service was last reviewed on January 11, 2026.</p>
        </footer>
    </div>
</body>
</html>
