<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Emoji Match - Support</title>
    <meta name="description" content="Support and help for Emoji Match - the fun physics-based emoji matching game for iOS">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background: #f5f5f7;
        }

        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 60px 20px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .header h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }

        .header p {
            font-size: 1.2em;
            opacity: 0.95;
        }

        .container {
            max-width: 900px;
            margin: -30px auto 0;
            padding: 0 20px 60px;
        }

        .card {
            background: white;
            border-radius: 12px;
            padding: 40px;
            margin-bottom: 30px;
            box-shadow: 0 2px 20px rgba(0,0,0,0.08);
        }

        .card h2 {
            color: #667eea;
            margin-bottom: 20px;
            font-size: 1.8em;
            border-bottom: 2px solid #f0f0f0;
            padding-bottom: 10px;
        }

        .card h3 {
            color: #333;
            margin-top: 25px;
            margin-bottom: 10px;
            font-size: 1.3em;
        }

        .card p {
            margin-bottom: 15px;
            color: #555;
            line-height: 1.8;
        }

        .card ul {
            margin-left: 20px;
            margin-bottom: 15px;
        }

        .card li {
            margin-bottom: 8px;
            color: #555;
        }

        .faq-item {
            margin-bottom: 25px;
            border-left: 3px solid #667eea;
            padding-left: 20px;
        }

        .faq-question {
            font-weight: 600;
            color: #333;
            font-size: 1.1em;
            margin-bottom: 8px;
        }

        .faq-answer {
            color: #555;
        }

        .contact-info {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            margin-top: 20px;
        }

        .contact-info p {
            margin-bottom: 10px;
        }

        .contact-info a {
            color: #667eea;
            text-decoration: none;
            font-weight: 600;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .feature {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
        }

        .feature-icon {
            font-size: 3em;
            margin-bottom: 10px;
        }

        .feature h4 {
            color: #333;
            margin-bottom: 8px;
        }

        .feature p {
            font-size: 0.9em;
            color: #666;
        }

        .app-store-badge {
            display: inline-block;
            margin-top: 20px;
        }

        .app-store-badge img {
            height: 50px;
        }

        .footer {
            text-align: center;
            padding: 40px 20px;
            color: #999;
            font-size: 0.9em;
        }

        .footer a {
            color: #667eea;
            text-decoration: none;
        }

        .footer a:hover {
            text-decoration: underline;
        }

        .button {
            display: inline-block;
            background: #667eea;
            color: white;
            padding: 12px 30px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 600;
            transition: all 0.3s;
            margin-top: 10px;
        }

        .button:hover {
            background: #5568d3;
            transform: translateY(-2px);
            box-shadow: 0 4px 12px rgba(102, 126, 234, 0.3);
        }

        .version-info {
            background: #fff3cd;
            border-left: 4px solid #ffc107;
            padding: 15px;
            border-radius: 4px;
            margin-top: 20px;
        }

        @media (max-width: 768px) {
            .header h1 {
                font-size: 2em;
            }

            .card {
                padding: 25px;
            }

            .feature-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>🎮 Emoji Match</h1>
        <p>Support & Help Center</p>
    </div>

    <div class="container">
        <!-- About the Game -->
        <div class="card">
            <h2>About Emoji Match</h2>
            <p>Emoji Match is a fun, physics-based puzzle game where you match groups of three identical emojis in a tumbling, gravity-affected environment. Test your reflexes and pattern recognition as emojis bounce, collide, and settle in this unique matching experience!</p>
            
            <div class="feature-grid">
                <div class="feature">
                    <div class="feature-icon">🎯</div>
                    <h4>Match 3 Emojis</h4>
                    <p>Find and tap three matching emojis to clear them</p>
                </div>
                <div class="feature">
                    <div class="feature-icon">🌊</div>
                    <h4>Physics-Based</h4>
                    <p>Emojis tumble and bounce with realistic gravity</p>
                </div>
                <div class="feature">
                    <div class="feature-icon">📈</div>
                    <h4>Progressive Levels</h4>
                    <p>Difficulty increases as you advance</p>
                </div>
            </div>
        </div>

        <!-- How to Play -->
        <div class="card">
            <h2>How to Play</h2>
            
            <h3>🎮 Basic Gameplay</h3>
            <ul>
                <li><strong>Tap to Match:</strong> The target emoji is shown at the top of the screen. Find and tap all 3 instances of that emoji among the tumbling pile.</li>
                <li><strong>Watch Them Fall:</strong> Emojis drop and bounce with realistic physics. They settle over time but can shift when you tap or remove others.</li>
                <li><strong>Complete All Matches:</strong> Once you've found all three of the target emoji, a new target will appear. Clear all emoji types to complete the level.</li>
                <li><strong>Level Up:</strong> Each new level adds more emojis and emoji types, making the challenge progressively harder.</li>
            </ul>

            <h3>💡 Tips & Tricks</h3>
            <ul>
                <li>Wait a moment for emojis to settle before starting to tap</li>
                <li>Watch for emojis hiding underneath the pile - they'll tumble down when others are removed</li>
                <li>Try to spot all three matches before tapping to work more efficiently</li>
                <li>Incorrect taps don't penalize you, so feel free to tap quickly!</li>
            </ul>
        </div>

        <!-- FAQ -->
        <div class="card">
            <h2>Frequently Asked Questions</h2>

            <div class="faq-item">
                <div class="faq-question">Q: What happens if I tap the wrong emoji?</div>
                <div class="faq-answer">A: Don't worry! Tapping incorrect emojis has no penalty. The emoji will shake slightly to let you know it wasn't a match, and you can keep trying.</div>
            </div>

            <div class="faq-item">
                <div class="faq-question">Q: Does the game save my progress?</div>
                <div class="faq-answer">A: Yes, your current level is automatically saved. You can close the app and continue where you left off anytime.</div>
            </div>

            <div class="faq-item">
                <div class="faq-question">Q: Is there a time limit?</div>
                <div class="faq-answer">A: No, there's no time limit! Take as long as you need to find all the matches in each level.</div>
            </div>

            <div class="faq-item">
                <div class="faq-question">Q: Will there be updates with new features?</div>
                <div class="faq-answer">A: Yes! We're constantly working on improvements and new features based on player feedback. Keep your app updated to get the latest enhancements.</div>
            </div>
        </div>

        <!-- Troubleshooting -->
        <div class="card">
            <h2>Troubleshooting</h2>

            <h3>🐛 Common Issues</h3>

            <div class="faq-item">
                <div class="faq-question">The game is running slowly or lagging</div>
                <div class="faq-answer">
                    <p>Try these solutions:</p>
                    <ul>
                        <li>Close other apps running in the background</li>
                        <li>Restart your device</li>
                        <li>Make sure you have the latest version of iOS installed</li>
                        <li>Update Emoji Match to the latest version from the App Store</li>
                    </ul>
                </div>
            </div>

            <div class="faq-item">
                <div class="faq-question">The app crashes or won't open</div>
                <div class="faq-answer">
                    <p>Try these steps:</p>
                    <ul>
                        <li>Force close the app and reopen it</li>
                        <li>Restart your device</li>
                        <li>Delete and reinstall the app (your progress is saved)</li>
                        <li>Check for iOS updates</li>
                    </ul>
                </div>
            </div>

            <div class="faq-item">
                <div class="faq-question">Touch controls aren't responding</div>
                <div class="faq-answer">
                    <p>Make sure:</p>
                    <ul>
                        <li>Your screen is clean and dry</li>
                        <li>You're tapping directly on the emojis (not between them)</li>
                        <li>You don't have a screen protector that's interfering with touch</li>
                    </ul>
                </div>
            </div>

            <h3>📱 System Requirements</h3>
            <ul>
                <li><strong>iOS Version:</strong> iOS 14.0 or later</li>
                <li><strong>Devices:</strong> iPhone, iPad, iPod touch</li>
                <li><strong>Storage:</strong> Approximately 50 MB</li>
            </ul>
        </div>

        <!-- Privacy & Data -->
        <div class="card">
            <h2>Privacy & Data</h2>
            
            <h3>🔒 Your Privacy Matters</h3>
            <p>Emoji Match respects your privacy and does not collect or share personal information. Here's what you should know:</p>
            
            <ul>
                <li><strong>No Personal Data Collection:</strong> We don't collect names, emails, or other personal information</li>
                <li><strong>Local Storage Only:</strong> Your game progress and high scores are stored locally on your device</li>
                <li><strong>No Third-Party Tracking:</strong> Your gameplay is private and not shared with anyone</li>
            </ul>
            
        </div>

        <!-- Contact -->
        <div class="card">
            <h2>Contact & Support</h2>
            <p>Need help? Have feedback or suggestions? We'd love to hear from you!</p>

            <div class="contact-info">
                <p><strong>📧 Email:</strong> <a href="mailto:joelariz@gmail.com">joelariz@gmail.com</a></p>
                <p><strong>⏱️ Response Time:</strong> We typically respond within 24-48 hours</p>
                <p><strong>🌐 Website:</strong> <a href="https://joedogg.github.io/emoji-match-site>https://joedogg.github.io/emoji-match-site</a></p>
            </div>

            <p style="margin-top: 20px;">When contacting support, please include:</p>
            <ul>
                <li>Your device model (e.g., iPhone 14, iPad Pro)</li>
                <li>iOS version</li>
                <li>App version (found in Settings)</li>
                <li>A description of the issue</li>
                <li>Screenshots if applicable</li>
            </ul>

            <h3>💬 Leave a Review</h3>
            <p>Enjoying Emoji Match? We'd greatly appreciate a review on the App Store! Your feedback helps us improve the game and reach more players.</p>
            <a href="#" class="button">⭐ Rate on App Store</a>
        </div>

        <!-- Version Info -->
        <div class="card">
            <h2>Version Information</h2>
            <div class="version-info">
                <p><strong>Current Version:</strong> 1.0.0</p>
                <p><strong>Last Updated:</strong> November 2025</p>
            </div>

            <h3>📋 What's New in v1.0.0</h3>
            <ul>
                <li>🎉 Initial release!</li>
                <li>🎮 Physics-based emoji matching gameplay</li>
                <li>📈 Progressive difficulty</li>
                <li>💾 Automatic progress saving</li>
            </ul>
        </div>
    </div>
</body>
</html>
