<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cockroach Janata Party (CJP) - Tiku Nath</title>
    <style>
        :root {
            --bg-cream: #EFECE1;
            --card-bg: #FDFBF7;
            --party-orange: #D35400;
            --party-green: #1E5631;
            --text-dark: #1A1A1A;
            --text-muted: #555555;
            --ashoka-blue: #002147;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Georgia', serif;
            background-color: var(--bg-cream);
            color: var(--text-dark);
            line-height: 1.6;
            padding: 0 0 80px 0;
            /* Subtly embedded Indian Flag tricolor gradient lines at the absolute edges */
            border-top: 15px solid var(--party-orange);
            border-bottom: 15px solid var(--party-green);
        }

        .wrapper {
            max-width: 550px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        /* Top Header Area */
        .header-meta {
            font-size: 0.85rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: var(--text-muted);
            margin-bottom: 15px;
        }

        h1.hero-title {
            font-size: 3.2rem;
            font-weight: 900;
            line-height: 1.1;
            margin-bottom: 20px;
            font-family: 'Impact', 'Arial Black', sans-serif;
            color: var(--text-dark);
        }

        h1.hero-title span.orange-text {
            color: var(--party-orange);
        }

        h1.hero-title span.green-text {
            color: var(--party-green);
            font-style: italic;
        }

        .lead-p {
            font-size: 1.15rem;
            color: var(--text-muted);
            margin-bottom: 25px;
        }

        /* Primary Call to Action Button */
        .btn-primary {
            display: inline-block;
            background-color: var(--party-green);
            color: white;
            padding: 14px 28px;
            font-weight: bold;
            text-decoration: none;
            border-radius: 4px;
            font-family: sans-serif;
            font-size: 1rem;
            border: none;
            cursor: pointer;
            margin-bottom: 35px;
        }

        /* Live Tracker Metrics Row */
        .stats-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-bottom: 40px;
            border-top: 1px solid rgba(0,0,0,0.1);
            padding-top: 20px;
        }

        .stat-box {
            text-align: left;
        }

        .stat-num {
            font-size: 2rem;
            font-weight: bold;
            font-family: sans-serif;
            color: var(--text-dark);
        }

        .stat-label {
            font-size: 0.8rem;
            color: var(--text-muted);
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* Propaganda Poster Art Frame */
        .poster-frame {
            background-color: #F4EAD4;
            border: 2px solid #C5B489;
            padding: 20px;
            margin-bottom: 50px;
            text-align: center;
            position: relative;
        }

        .poster-graphic {
            width: 100%;
            height: auto;
            max-width: 320px;
            margin: 0 auto 15px auto;
            display: block;
        }

        .poster-caption {
            font-size: 0.9rem;
            font-style: italic;
            color: #444;
            border-top: 1px dashed #C5B489;
            padding-top: 10px;
        }

        /* Sections Layout */
        .section-tag {
            color: var(--party-orange);
            font-size: 0.8rem;
            text-transform: uppercase;
            font-weight: bold;
            letter-spacing: 1.5px;
            margin-bottom: 5px;
            display: block;
        }

        h2.section-heading {
            font-size: 2.2rem;
            font-weight: bold;
            margin-bottom: 20px;
            line-height: 1.2;
        }

        h2.section-heading span.green-text {
            color: var(--party-green);
            font-style: italic;
        }

        /* List Cards Style (Manifesto & Eligibility) */
        .card-stack {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-top: 25px;
            margin-bottom: 50px;
        }

        .info-card {
            background-color: var(--card-bg);
            border: 1px solid #D6D1C2;
            border-bottom: 4px solid #C2BCAC;
            padding: 20px;
            border-radius: 6px;
            display: flex;
            gap: 15px;
            text-align: left;
        }

        .card-index {
            font-size: 1.2rem;
            font-weight: bold;
            color: var(--party-orange);
            font-family: sans-serif;
        }

        .card-content h4 {
            font-size: 1.1rem;
            font-weight: bold;
            margin-bottom: 5px;
        }

        .card-content p {
            font-size: 0.95rem;
            color: var(--text-muted);
        }

        /* Footer Section */
        .about-party-box {
            background-color: var(--card-bg);
            border: 1px solid #D6D1C2;
            padding: 25px;
            border-radius: 6px;
            margin-top: 40px;
            text-align: left;
        }

        /* Bottom Floating Sticky Bar */
        .sticky-footer {
            position: fixed;
            bottom: 0;
            left: 0;
            width: 100%;
            background-color: #111111;
            color: white;
            padding: 12px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 9999;
            box-shadow: 0 -4px 20px rgba(0,0,0,0.3);
        }

        .sticky-text {
            font-size: 0.85rem;
            font-family: sans-serif;
        }

        .sticky-btn {
            background-color: var(--party-green);
            color: white;
            border: none;
            padding: 8px 16px;
            font-weight: bold;
            border-radius: 4px;
            cursor: pointer;
            font-size: 0.85rem;
            font-family: sans-serif;
            transition: 0.2s ease;
        }

        .sticky-btn.followed {
            background-color: var(--party-orange);
        }
    </style>
</head>
<body>

    <div class="wrapper">
        <div class="header-meta">CJP National Campaign • Authorized by Tiku Nath</div>
        
        <h1 class="hero-title">
            Voice of the <br>
            <span class="orange-text">Lazy</span> & <br>
            <span class="green-text">Unemployed.</span>
        </h1>

        <p class="lead-p">
            Founded by <strong>Tiku Nath</strong>, the Cockroach Janata Party (CJP) is the official digital collective fighting for the foundational rights of screen-agers across the nation.
        </p>

        <button class="btn-primary" onclick="triggerFollow()">Follow the Movement</button>

        <div class="stats-grid">
            <div class="stat-box">
                <div class="stat-num" id="liveFollowers">32,507</div>
                <div class="stat-label">Active Followers</div>
            </div>
            <div class="stat-box">
                <div class="stat-num">11 hrs</div>
                <div class="stat-label">Min Screen Time</div>
            </div>
            <div class="stat-box">
                <div class="stat-num">0%</div>
                <div class="stat-label">Employment Rate</div>
            </div>
            <div class="stat-box">
                <div class="stat-num">Gen Z</div>
                <div class="stat-label">Demographic Core</div>
            </div>
        </div>

        <div class="poster-frame">
            <svg class="poster-graphic" viewBox="0 0 200 160" xmlns="http://www.w3.org/2000/svg">
                <rect width="200" height="160" fill="#E6C9A8" stroke="#1E5631" stroke-width="2"/>
                <circle cx="100" cy="75" r="45" fill="#D35400" opacity="0.8"/>
                <path d="M100,30 C95,30 92,45 92,65 C92,90 96,115 100,115 C104,115 108,90 108,65 C108,45 105,30 100,30 Z" fill="#1A1A1A"/>
                <path d="M96,35 Q75,15 60,25" stroke="#1A1A1A" stroke-width="1.5" fill="none"/>
                <path d="M104,35 Q125,15 140,25" stroke="#1A1A1A" stroke-width="1.5" fill="none"/>
                <path d="M75,110 L125,110 L135,140 L65,140 Z" fill="#1E5631"/>
                <line x1="100" y1="110" x2="100" y2="140" stroke="#E6C9A8" stroke-width="2"/>
            </svg>
            <div class="poster-caption">Official Emblem of the Cockroach Janata Party — "Together We Crawl, Together We Survive."</div>
        </div>

        <span class="section-tag">Our Mandate</span>
        <h2 class="section-heading">The Movement's <span class="green-text">Vision.</span></h2>
        <p class="lead-p">
            While others preach hustle culture and 70-hour work weeks, CJP stands resiliently in the corners of the room. We honor the true survivors of modern economic trends.
        </p>

        <span class="section-tag">The Ideology</span>
        <h2 class="section-heading">The <span class="green-text">Manifesto.</span></h2>
        <p>Official cockroach maxims and philosophical core truths:</p>

        <div class="card-stack">
            <div class="info-card">
                <div class="card-index">01</div>
                <div class="card-content">
                    <h4>Atomic Resilience</h4>
                    <p>"Governments may come, governments may go, but cockroaches survive nuclear blasts. We are permanent structural pillars."</p>
                </div>
            </div>
            <div class="info-card">
                <div class="card-index">02</div>
                <div class="card-content">
                    <h4>Screen Liberation</h4>
                    <p>"Why stress over career ladders when you can focus completely on your handheld screen interface for 11 glorious hours straight?"</p>
                </div>
            </div>
            <div class="info-card">
                <div class="card-index">03</div>
                <div class="card-content">
                    <h4>The Survival Strategy</h4>
                    <p>"Crushed today under the thumb of society, crawling back completely unfazed tomorrow. That is the authentic CJP way."</p>
                </div>
            </div>
        </div>

        <span class="section-tag">Membership Validation</span>
        <h2 class="section-heading">Are you eligible to <span class="green-text">follow?</span></h2>
        <p class="lead-p">Check your layout criteria before validating your alliance with National President Tiku Nath.</p>

        <div class="card-stack">
            <div class="info-card">
                <div class="card-index">✓</div>
                <div class="card-content">
                    <h4>Completely Unemployed</h4>
                    <p>Must have zero corporate commitments or side hustles running.</p>
                </div>
            </div>
            <div class="info-card">
                <div class="card-index">✓</div>
                <div class="card-content">
                    <h4>11+ Hours Device Intake</h4>
                    <p>Daily phone statistics must reflect extreme digital endurance.</p>
                </div>
            </div>
            <div class="info-card">
                <div class="card-index">✓</div>
                <div class="card-content">
                    <h4>Gen Z Ancestry</h4>
                    <p>Must inherently understand deep internet lore, brainrot terms, and heavy cynicism.</p>
                </div>
            </div>
        </div>

        <div class="about-party-box">
            <span class="section-tag">Administration Profile</span>
            <h3 style="font-size: 1.4rem; margin-bottom:10px;">About the Cockroach Janata Party</h3>
            <p style="font-size: 0.95rem; color: var(--text-muted);">
                CJP is a non-serious political platform conceptualized to organize the unorganized digital masses under the leadership of <strong>Founder Tiku Nath</strong>. Designed explicitly for elite-level phone scrollers across India.
            </p>
        </div>
    </div>

    <div class="sticky-footer">
        <div class="sticky-text">
            <strong>CJP Live Follow Tracker:</strong> <span id="stickyCounter">32,507</span> members
        </div>
        <button class="sticky-btn" id="floatingFollowBtn" onclick="triggerFollow()">+ Follow Channel</button>
    </div>

    <script>
        // Interactive counter management state
        let counts = 32507;
        let userFollowed = false;

        function triggerFollow() {
            const displayMain = document.getElementById('liveFollowers');
            const displaySticky = document.getElementById('stickyCounter');
            const actionBtn = document.getElementById('floatingFollowBtn');

            if (!userFollowed) {
                counts++;
                actionBtn.textContent = "✓ Joined Party";
                actionBtn.classList.add('followed');
                userFollowed = true;
            } else {
                counts--;
                actionBtn.textContent = "+ Follow Channel";
                actionBtn.classList.remove('followed');
                userFollowed = false;
            }

            // Render updated counter string to DOM strings
            displayMain.textContent = counts.toLocaleString();
            displaySticky.textContent = counts.toLocaleString();
        }
    </script>
</body>
</html>
