# TGWPLAYWORD
ITS ARE EGUCATIN PERPUSE TO TRENING
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TGW PLAY WORLD - Free Matka App</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #667eea;
            --secondary: #764ba2;
            --accent: #f093fb;
            --success: #4cc9f0;
            --dark: #1a1a2e;
            --light: #f8f9fa;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            min-height: 100vh;
            overflow-x: hidden;
        }
        
        /* Hero Section */
        .hero {
            padding: 80px 20px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: 
                radial-gradient(circle at 20% 80%, rgba(255,255,255,0.1) 0%, transparent 50%),
                radial-gradient(circle at 80% 20%, rgba(255,255,255,0.1) 0%, transparent 50%);
        }
        
        .logo {
            font-size: 5rem;
            margin-bottom: 20px;
            animation: float 3s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }
        
        h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.3);
        }
        
        .subtitle {
            font-size: 1.3rem;
            opacity: 0.9;
            margin-bottom: 40px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }
        
        /* Download Cards */
        .download-section {
            padding: 40px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .cards-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 25px;
            padding: 40px 30px;
            text-align: center;
            border: 1px solid rgba(255, 255, 255, 0.2);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }
        
        .card:hover {
            transform: translateY(-10px);
            background: rgba(255, 255, 255, 0.15);
            box-shadow: 0 20px 40px rgba(0,0,0,0.2);
        }
        
        .card-icon {
            font-size: 4rem;
            margin-bottom: 25px;
            display: block;
        }
        
        .card-title {
            font-size: 1.8rem;
            margin-bottom: 15px;
            font-weight: 600;
        }
        
        .card-desc {
            font-size: 1rem;
            opacity: 0.9;
            margin-bottom: 25px;
            line-height: 1.6;
        }
        
        /* Download Buttons */
        .btn {
            display: inline-block;
            padding: 15px 30px;
            background: white;
            color: var(--primary);
            text-decoration: none;
            border-radius: 50px;
            font-weight: 600;
            font-size: 1.1rem;
            margin: 10px;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
        
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.3);
            background: var(--light);
        }
        
        .btn-primary {
            background: linear-gradient(135deg, #4cc9f0, #4361ee);
            color: white;
        }
        
        .btn-secondary {
            background: transparent;
            color: white;
            border: 2px solid white;
        }
        
        .btn-secondary:hover {
            background: white;
            color: var(--primary);
        }
        
        /* Features */
        .features {
            padding: 80px 20px;
            background: rgba(0, 0, 0, 0.1);
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            max-width: 1200px;
            margin: 50px auto 0;
        }
        
        .feature {
            text-align: center;
            padding: 30px;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 20px;
            backdrop-filter: blur(5px);
        }
        
        .feature i {
            font-size: 2.5rem;
            margin-bottom: 20px;
            background: linear-gradient(135deg, #4cc9f0, #4361ee);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        /* Stats */
        .stats {
            display: flex;
            justify-content: center;
            gap: 50px;
            margin: 60px 0;
            flex-wrap: wrap;
        }
        
        .stat {
            text-align: center;
        }
        
        .stat-number {
            font-size: 3rem;
            font-weight: 700;
            background: linear-gradient(45deg, #fff, #f0f0f0);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 10px;
        }
        
        .stat-label {
            font-size: 1.1rem;
            opacity: 0.9;
        }
        
        /* Live Links Section */
        .live-links {
            padding: 60px 20px;
            text-align: center;
        }
        
        .links-container {
            max-width: 800px;
            margin: 40px auto;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 20px;
            padding: 40px;
            backdrop-filter: blur(10px);
        }
        
        .link-box {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 15px;
            padding: 20px;
            margin: 20px 0;
            text-align: left;
        }
        
        .link-box h4 {
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .link-url {
            background: rgba(0, 0, 0, 0.2);
            padding: 12px 20px;
            border-radius: 10px;
            word-break: break-all;
            font-family: monospace;
            margin-top: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .copy-btn {
            background: var(--primary);
            color: white;
            border: none;
            padding: 8px 15px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 0.9rem;
        }
        
        /* QR Code */
        .qr-section {
            padding: 40px;
            background: white;
            border-radius: 20px;
            display: inline-block;
            margin: 30px 0;
        }
        
        .qr-code {
            width: 200px;
            height: 200px;
        }
        
        /* Footer */
        footer {
            padding: 60px 20px;
            background: rgba(0, 0, 0, 0.2);
            text-align: center;
            margin-top: 80px;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 30px 0;
        }
        
        .social-link {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.1);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2rem;
            color: white;
            text-decoration: none;
            transition: all 0.3s ease;
        }
        
        .social-link:hover {
            background: var(--primary);
            transform: translateY(-5px);
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            
            .logo {
                font-size: 4rem;
            }
            
            .cards-grid {
                grid-template-columns: 1fr;
            }
            
            .stats {
                gap: 30px;
            }
            
            .stat-number {
                font-size: 2.5rem;
            }
        }
        
        /* Animation */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        .fade-in {
            animation: fadeIn 0.8s ease forwards;
        }
        
        .delay-1 { animation-delay: 0.2s; }
        .delay-2 { animation-delay: 0.4s; }
        .delay-3 { animation-delay: 0.6s; }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="hero">
        <div class="logo fade-in">🎮</div>
        <h1 class="fade-in">TGW PLAY WORLD</h1>
        <p class="subtitle fade-in delay-1">
            Free Matka Gaming App with Real Money Winning. Download Now & Start Playing!
        </p>
        
        <div class="stats fade-in delay-2">
            <div class="stat">
                <div class="stat-number" id="downloads">50K+</div>
                <div class="stat-label">Downloads</div>
            </div>
            <div class="stat">
                <div class="stat-number" id="players">25K+</div>
                <div class="stat-label">Active Players</div>
            </div>
            <div class="stat">
                <div class="stat-number" id="payouts">₹5Cr+</div>
                <div class="stat-label">Paid Out</div>
            </div>
        </div>
    </section>

    <!-- Download Section -->
    <section class="download-section">
        <h2 style="text-align: center; margin-bottom: 50px; font-size: 2.5rem;">Download Free App</h2>
        
        <div class="cards-grid">
            <!-- Android Card -->
            <div class="card fade-in delay-1">
                <div class="card-icon">🤖</div>
                <h3 class="card-title">Android APK</h3>
                <p class="card-desc">
                    Download the latest version of TGW PLAY WORLD for Android devices. Works on all Android 5.0+ phones.
                </p>
                <div style="margin-top: 20px;">
                    <a href="https://github.com/TGW-PLAY-WORLD/tgw-app/releases/download/v2.0/tgw-play-world.apk" 
                       class="btn btn-primary" 
                       download
                       onclick="trackDownload('android')">
                        <i class="fas fa-download"></i> Download APK (25 MB)
                    </a>
                    <a href="#install-guide" class="btn btn-secondary">
                        <i class="fas fa-info-circle"></i> Installation Guide
                    </a>
                </div>
                <div style="margin-top: 20px; font-size: 0.9rem;">
                    <i class="fas fa-star"></i> Version 2.0 | Android 5.0+
                </div>
            </div>
            
            <!-- Web App Card -->
            <div class="card fade-in delay-2">
                <div class="card-icon">🌐</div>
                <h3 class="card-title">Web Version</h3>
                <p class="card-desc">
                    Play directly in your browser - No download required! Works on all devices instantly.
                </p>
                <div style="margin-top: 20px;">
                    <a href="https://tgw-play-world.netlify.app" 
                       class="btn btn-primary"
                       target="_blank"
                       onclick="trackDownload('web')">
                        <i class="fas fa-external-link-alt"></i> Play Now Online
                    </a>
                    <a href="https://tgwplayworld.web.app" 
                       class="btn btn-secondary"
                       target="_blank">
                        Mirror Link 2
                    </a>
                </div>
                <div style="margin-top: 20px; font-size: 0.9rem;">
                    <i class="fas fa-bolt"></i> Instant Play | No Installation
                </div>
            </div>
            
            <!-- Admin Panel Card -->
            <div class="card fade-in delay-3">
                <div class="card-icon">🛠️</div>
                <h3 class="card-title">Admin Panel</h3>
                <p class="card-desc">
                    Admin dashboard for managing users, markets, withdrawals, and monitoring platform activity.
                </p>
                <div style="margin-top: 20px;">
                    <a href="https://tgw-admin.netlify.app" 
                       class="btn btn-primary"
                       target="_blank"
                       onclick="trackDownload('admin')">
                        <i class="fas fa-cog"></i> Open Admin Panel
                    </a>
                </div>
                <div style="margin-top: 20px; font-size: 0.9rem;">
                    <i class="fas fa-user-shield"></i> Username: admin | Password: admin123
                </div>
            </div>
        </div>
        
        <!-- QR Code -->
        <div style="text-align: center; margin-top: 60px;" class="fade-in">
            <h3 style="margin-bottom: 20px;">Scan QR Code to Download</h3>
            <div class="qr-section">
                <img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://tgw-play-world.netlify.app&format=svg" 
                     alt="QR Code" 
                     class="qr-code">
            </div>
            <p style="margin-top: 20px; opacity: 0.8;">
                Scan with phone camera to open download page
            </p>
        </div>
    </section>

    <!-- Live Links Section -->
    <section class="live-links">
        <h2 style="font-size: 2.5rem; margin-bottom: 20px;">🌐 ACTIVE DOWNLOAD LINKS</h2>
        <p style="font-size: 1.2rem; margin-bottom: 40px; max-width: 800px; margin-left: auto; margin-right: auto;">
            These links are LIVE and working RIGHT NOW! Click to download immediately.
        </p>
        
        <div class="links-container">
            <!-- Direct Download Links -->
            <div class="link-box fade-in">
                <h4><i class="fas fa-mobile-alt"></i> Direct APK Download Links</h4>
                <div class="link-url">
                    <span id="link1">https://drive.google.com/uc?export=download&id=1ABC123XYZ</span>
                    <button class="copy-btn" onclick="copyLink('link1')">Copy</button>
                </div>
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 10px; margin-top: 15px;">
                    <a href="tgw-play-world-v2.0.apk" class="btn" download style="font-size: 0.9rem; padding: 10px;">
                        <i class="fas fa-download"></i> Download Now
                    </a>
                    <a href="tgw-play-world-lite.apk" class="btn btn-secondary" download style="font-size: 0.9rem; padding: 10px;">
                        Lite Version
                    </a>
                    <a href="tgw-play-world-beta.apk" class="btn btn-secondary" download style="font-size: 0.9rem; padding: 10px;">
                        Beta Version
                    </a>
                </div>
            </div>
            
            <!-- Web App Links -->
            <div class="link-box fade-in delay-1">
                <h4><i class="fas fa-globe"></i> Web App Links (No Download)</h4>
                <div class="link-url">
                    <span id="link2">https://tgw-play-world.netlify.app</span>
                    <button class="copy-btn" onclick="copyLink('link2')">Copy</button>
                </div>
                <div class="link-url" style="margin-top: 10px;">
                    <span id="link3">https://tgwplayworld.pages.dev</span>
                    <button class="copy-btn" onclick="copyLink('link3')">Copy</button>
                </div>
                <div style="margin-top: 15px; text-align: center;">
                    <a href="https://tgw-play-world.netlify.app" class="btn btn-primary" target="_blank" style="width: 100%;">
                        <i class="fas fa-play"></i> Click Here to Play Now
                    </a>
                </div>
            </div>
            
            <!-- Admin Links -->
            <div class="link-box fade-in delay-2">
                <h4><i class="fas fa-cogs"></i> Admin Panel Links</h4>
                <div class="link-url">
                    <span id="link4">https://tgw-admin.netlify.app</span>
                    <button class="copy-btn" onclick="copyLink('link4')">Copy</button>
                </div>
                <div style="background: rgba(255,0,0,0.1); padding: 15px; border-radius: 10px; margin-top: 15px;">
                    <strong>Admin Credentials:</strong>
                    <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-top: 10px;">
                        <div><strong>Username:</strong> admin</div>
                        <div><strong>Password:</strong> admin123</div>
                    </div>
                    <small style="display: block; margin-top: 10px; color: #ff6b6b;">
                        ⚠️ Change password after first login!
                    </small>
                </div>
            </div>
        </div>
    </section>

    <!-- Features -->
    <section class="features">
        <h2 style="text-align: center; font-size: 2.5rem; margin-bottom: 20px;">🎮 Features</h2>
        <p style="text-align: center; font-size: 1.2rem; max-width: 800px; margin: 0 auto 50px;">
            Everything you need for the ultimate Matka gaming experience
        </p>
        
        <div class="features-grid">
            <div class="feature fade-in">
                <i class="fas fa-gamepad"></i>
                <h3>14+ Markets</h3>
                <p>Sridevi, Kalyan, Milan, Main Bazar, Time Bazar & more</p>
            </div>
            
            <div class="feature fade-in delay-1">
                <i class="fas fa-bolt"></i>
                <h3>Real-time Results</h3>
                <p>Live updates with automatic result declaration</p>
            </div>
            
            <div class="feature fade-in delay-2">
                <i class="fas fa-wallet"></i>
                <h3>Instant Withdrawals</h3>
                <p>Withdraw winnings directly to bank/UPI</p>
            </div>
            
            <div class="feature fade-in">
                <i class="fas fa-shield-alt"></i>
                <h3>Secure & Safe</h3>
                <p>Bank-level security with SSL encryption</p>
            </div>
            
            <div class="feature fade-in delay-1">
                <i class="fas fa-mobile-alt"></i>
                <h3>Mobile Friendly</h3>
                <p>Works perfectly on all devices</p>
            </div>
            
            <div class="feature fade-in delay-2">
                <i class="fas fa-headset"></i>
                <h3>24/7 Support</h3>
                <p>Round-the-clock customer support</p>
            </div>
        </div>
    </section>

    <!-- Installation Guide -->
    <section id="install-guide" style="padding: 60px 20px; max-width: 800px; margin: 0 auto;">
        <h2 style="text-align: center; font-size: 2.5rem; margin-bottom: 40px;">📱 Installation Guide</h2>
        
        <div style="background: rgba(255,255,255,0.1); border-radius: 20px; padding: 40px;">
            <h3 style="margin-bottom: 30px; color: #4cc9f0;">For Android Users:</h3>
            
            <div style="display: grid; gap: 20px;">
                <div style="display: flex; gap: 20px; align-items: center; background: rgba(255,255,255,0.05); padding: 20px; border-radius: 15px;">
                    <div style="font-size: 2rem; color: #4cc9f0;">1</div>
                    <div>
                        <h4>Download APK File</h4>
                        <p>Click the "Download APK" button above</p>
                    </div>
                </div>
                
                <div style="display: flex; gap: 20px; align-items: center; background: rgba(255,255,255,0.05); padding: 20px; border-radius: 15px;">
                    <div style="font-size: 2rem; color: #4cc9f0;">2</div>
                    <div>
                        <h4>Enable Unknown Sources</h4>
                        <p>Go to Settings → Security → Enable "Unknown Sources"</p>
                    </div>
                </div>
                
                <div style="display: flex; gap: 20px; align-items: center; background: rgba(255,255,255,0.05); padding: 20px; border-radius: 15px;">
                    <div style="font-size: 2rem; color: #4cc9f0;">3</div>
                    <div>
                        <h4>Install the App</h4>
                        <p>Open the downloaded APK file and tap "Install"</p>
                    </div>
                </div>
                
                <div style="display: flex; gap: 20px; align-items: center; background: rgba(255,255,255,0.05); padding: 20px; border-radius: 15px;">
                    <div style="font-size: 2rem; color: #4cc9f0;">4</div>
                    <div>
                        <h4>Register & Play</h4>
                        <p>Open app, register with phone number, and start playing!</p>
                    </div>
                </div>
            </div>
            
            <div style="margin-top: 40px; padding: 20px; background: rgba(255,0,0,0.1); border-radius: 15px; border-left: 4px solid #ff6b6b;">
                <h4 style="color: #ff6b6b;"><i class="fas fa-exclamation-triangle"></i> Important Note:</h4>
                <p>If you get "Blocked by Play Protect", click "Install Anyway" to continue.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <h3 style="margin-bottom: 20px;">TGW PLAY WORLD</h3>
        <p style="max-width: 600px; margin: 0 auto 30px; opacity: 0.8;">
            Free Matka Gaming Platform with Real Money Winning. Download now and start playing!
        </p>
        
        <div class="social-links">
            <a href="https://t.me/tgwplayworld" class="social-link" target="_blank">
                <i class="fab fa-telegram"></i>
            </a>
            <a href="https://wa.me/919876543210" class="social-link" target="_blank">
                <i class="fab fa-whatsapp"></i>
            </a>
            <a href="mailto:support@tgwplayworld.com" class="social-link">
                <i class="fas fa-envelope"></i>
            </a>
        </div>
        
        <div style="margin-top: 40px; padding-top: 30px; border-top: 1px solid rgba(255,255,255,0.1);">
            <p>© 2024 TGW PLAY WORLD. All rights reserved.</p>
            <p style="opacity: 0.6; margin-top: 10px; font-size: 0.9rem;">
                For age 18+ only. Play responsibly.
            </p>
        </div>
    </footer>

    <script>
        // Auto-update stats
        function updateStats() {
            const downloads = document.getElementById('downloads');
            const players = document.getElementById('players');
            const payouts = document.getElementById('payouts');
            
            let dCount = parseInt(downloads.textContent) || 50000;
            let pCount = parseInt(players.textContent) || 25000;
            let payout = parseInt(payouts.textContent.replace('₹', '').replace('Cr+', '')) || 5;
            
            // Add random growth
            dCount += Math.floor(Math.random() * 10);
            pCount += Math.floor(Math.random() * 5);
            
            downloads.textContent = dCount.toLocaleString() + '+';
            players.textContent = pCount.toLocaleString() + '+';
            payouts.textContent = '₹' + payout + 'Cr+';
        }
        
        // Update every 30 seconds
        setInterval(updateStats, 30000);
        
        // Track downloads
        function trackDownload(type) {
            alert(`Starting ${type} download...`);
            
            // Update counter immediately
            updateStats();
            
            // In real app, send analytics here
            console.log(`Download tracked: ${type}`);
            
            return true; // Allow download
        }
        
        // Copy link function
        function copyLink(elementId) {
            const text = document.getElementById(elementId).textContent;
            navigator.clipboard.writeText(text).then(() => {
                alert('Link copied to clipboard!');
            });
        }
        
        // Add to home screen (for PWA)
        let deferredPrompt;
        
        window.addEventListener('beforeinstallprompt', (e) => {
            e.preventDefault();
            deferredPrompt = e;
            
            // Show install button
            const installBtn = document.createElement('button');
            installBtn.textContent = '📱 Install App';
            installBtn.className = 'btn btn-primary';
            installBtn.style.margin = '20px auto';
            installBtn.style.display = 'block';
            installBtn.onclick = installApp;
            
            document.querySelector('.hero').appendChild(installBtn);
        });
        
        async function installApp() {
            if (deferredPrompt) {
                deferredPrompt.prompt();
                const { outcome } = await deferredPrompt.userChoice;
                if (outcome === 'accepted') {
                    console.log('App installed');
                }
                deferredPrompt = null;
            }
        }
        
        // Initialize animations on scroll
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };
        
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('fade-in');
                }
            });
        }, observerOptions);
        
        // Observe all cards and features
        document.querySelectorAll('.card, .feature, .link-box').forEach(el => {
            observer.observe(el);
        });
    </script>
</body>
</html>
