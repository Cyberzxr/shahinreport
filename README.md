<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=yes" />
    <title>⚔️ شمشیرعلی – ۲۰۰ گزارش</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Inter:wght@300;400;600;700;800&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', 'Segoe UI', sans-serif;
            background: #0a0a0f;
            color: #e0e0e0;
            min-height: 100vh;
            padding: 16px;
            background-image:
                radial-gradient(ellipse at 10% 20%, rgba(128, 0, 255, 0.05) 0%, transparent 50%),
                radial-gradient(ellipse at 90% 80%, rgba(128, 0, 255, 0.05) 0%, transparent 50%);
        }

        .container {
            max-width: 1100px;
            width: 100%;
            margin: 0 auto;
            background: rgba(12, 8, 20, 0.97);
            backdrop-filter: blur(16px);
            border-radius: 36px;
            padding: 44px 38px;
            border: 2px solid rgba(128, 0, 255, 0.3);
            box-shadow: 0 30px 70px rgba(0, 0, 0, 0.85), 0 0 0 1px rgba(128, 0, 255, 0.1) inset,
                0 0 60px rgba(128, 0, 255, 0.04);
        }

        .header {
            text-align: center;
            margin-bottom: 28px;
            border-bottom: 2px solid rgba(128, 0, 255, 0.15);
            padding-bottom: 20px;
        }

        .flag-icon {
            font-size: 52px;
            display: inline-block;
            margin: 0 10px;
            filter: drop-shadow(0 0 20px rgba(128, 0, 255, 0.3));
            animation: flagPulse 3s ease-in-out infinite;
        }

        @keyframes flagPulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }

        .title {
            font-family: 'Orbitron', monospace;
            font-size: 40px;
            font-weight: 700;
            background: linear-gradient(135deg, #b388ff, #7c4dff, #b388ff);
            background-size: 300% 300%;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: shimmer 4s ease-in-out infinite;
            letter-spacing: 3px;
            display: inline-block;
            text-shadow: 0 0 40px rgba(128, 0, 255, 0.15);
        }

        @keyframes shimmer {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .iran-flag {
            display: inline-block;
            background: linear-gradient(to bottom, #b388ff 33%, #ffffff 33%, #ffffff 66%, #7c4dff 66%);
            padding: 8px 32px;
            border-radius: 40px;
            color: #000;
            font-weight: 800;
            font-size: 16px;
            border: 2px solid #b388ff;
            text-shadow: 0 0 20px rgba(255, 255, 255, 0.3);
            margin-top: 10px;
            letter-spacing: 2px;
            box-shadow: 0 0 30px rgba(128, 0, 255, 0.15);
        }

        .badge {
            display: inline-block;
            background: rgba(128, 0, 255, 0.08);
            border: 1px solid rgba(128, 0, 255, 0.2);
            border-radius: 100px;
            padding: 6px 22px;
            font-size: 12px;
            letter-spacing: 2.5px;
            color: #b388ff;
            text-transform: uppercase;
            font-weight: 700;
            margin-bottom: 12px;
        }

        .info-box {
            background: rgba(128, 0, 255, 0.03);
            border-radius: 16px;
            padding: 16px 20px;
            margin-bottom: 14px;
            border: 1px solid rgba(128, 0, 255, 0.08);
            font-size: 14px;
        }

        .info-box strong {
            color: #b388ff;
        }

        .to-box {
            background: rgba(128, 0, 255, 0.03);
            border-radius: 16px;
            padding: 14px 20px;
            margin-bottom: 14px;
            border: 1px solid rgba(128, 0, 255, 0.08);
            font-size: 13.5px;
            color: #8892b0;
            text-align: center;
        }

        .to-box .addr {
            color: #4488ff;
            font-weight: 600;
            direction: ltr;
            display: inline-block;
            margin: 0 4px;
        }

        .to-box .addr-main {
            color: #b388ff;
            font-weight: 700;
            direction: ltr;
            display: inline-block;
            margin: 0 4px;
            background: rgba(128, 0, 255, 0.08);
            padding: 2px 12px;
            border-radius: 20px;
            border: 1px solid rgba(128, 0, 255, 0.2);
            font-size: 17px;
        }

        .to-box .label-main {
            color: #e0e0e0;
            font-weight: 600;
            font-size: 14px;
        }

        .id-box {
            background: rgba(128, 0, 255, 0.04);
            border-radius: 12px;
            padding: 10px 18px;
            border: 1px solid rgba(128, 0, 255, 0.08);
            font-size: 14px;
            text-align: center;
            margin-bottom: 14px;
            color: #b388ff;
        }

        .id-box strong {
            color: #fff;
        }

        .email-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-top: 15px;
        }

        .email-card {
            background: rgba(255, 255, 255, 0.02);
            border-radius: 18px;
            padding: 20px;
            border: 1px solid rgba(128, 0, 255, 0.08);
            transition: all 0.3s ease;
        }

        .email-card:hover {
            border-color: rgba(128, 0, 255, 0.3);
            background: rgba(128, 0, 255, 0.03);
            box-shadow: 0 8px 35px rgba(0, 0, 0, 0.4), 0 0 30px rgba(128, 0, 255, 0.04);
        }

        .email-card .num {
            color: #b388ff;
            font-weight: 700;
            font-size: 13px;
            margin-bottom: 4px;
        }

        .email-card .subject {
            color: #e6f1ff;
            font-weight: 700;
            font-size: 15px;
            margin: 4px 0 8px;
            line-height: 1.4;
        }

        .email-card .body-preview {
            color: #c9d1d9;
            font-size: 12px;
            direction: ltr;
            text-align: left;
            font-family: 'Courier New', monospace;
            white-space: pre-wrap;
            word-break: break-word;
            line-height: 1.8;
            max-height: 180px;
            overflow-y: auto;
            padding: 12px 14px;
            background: rgba(0, 0, 0, 0.35);
            border-radius: 10px;
            margin-bottom: 10px;
            border: 1px solid rgba(128, 0, 255, 0.04);
        }

        .email-card .body-preview::-webkit-scrollbar {
            width: 3px;
        }
        .email-card .body-preview::-webkit-scrollbar-thumb {
            background: #b388ff;
            border-radius: 10px;
        }

        .email-card .links {
            font-size: 10px;
            color: #b388ff;
            margin: 6px 0;
            direction: ltr;
            text-align: left;
        }

        .email-card .links a {
            color: #b388ff;
            text-decoration: none;
        }

        .email-card .links a:hover {
            text-decoration: underline;
            color: #d1c4e9;
        }

        .btn-group {
            display: flex;
            gap: 6px;
            flex-wrap: wrap;
            margin-top: 10px;
        }

        .btn-gmail {
            background: linear-gradient(135deg, #7c4dff, #651fff);
            color: #fff;
            padding: 6px 14px;
            border-radius: 8px;
            font-size: 11px;
            font-weight: 700;
            border: none;
            cursor: pointer;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            transition: all 0.2s ease;
            flex: 1;
            justify-content: center;
            min-width: 80px;
            box-shadow: 0 0 15px rgba(128, 0, 255, 0.1);
        }

        .btn-gmail:hover {
            transform: scale(0.95);
            box-shadow: 0 0 30px rgba(128, 0, 255, 0.2);
        }

        .btn-email {
            background: linear-gradient(135deg, #536dfe, #304ffe);
            color: #fff;
            padding: 6px 14px;
            border-radius: 8px;
            font-size: 11px;
            font-weight: 700;
            border: none;
            cursor: pointer;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            transition: all 0.2s ease;
            flex: 1;
            justify-content: center;
            min-width: 80px;
        }

        .btn-email:hover {
            transform: scale(0.95);
            box-shadow: 0 0 20px rgba(83, 109, 254, 0.3);
        }

        .btn-copy {
            background: linear-gradient(135deg, #ce93d8, #ab47bc);
            color: #fff;
            padding: 6px 14px;
            border-radius: 8px;
            font-size: 11px;
            font-weight: 700;
            border: none;
            cursor: pointer;
            display: inline-flex;
            align-items: center;
            gap: 4px;
            transition: all 0.2s ease;
            flex: 1;
            justify-content: center;
            min-width: 80px;
            box-shadow: 0 0 15px rgba(206, 147, 216, 0.1);
        }

        .btn-copy:hover {
            transform: scale(0.95);
            box-shadow: 0 0 30px rgba(206, 147, 216, 0.2);
        }

        .status-msg {
            text-align: center;
            font-size: 12px;
            color: #8892b0;
            margin-top: 6px;
            min-height: 18px;
        }

        .pagination {
            display: flex;
            justify-content: center;
            gap: 6px;
            flex-wrap: wrap;
            margin: 15px 0;
        }

        .page-btn {
            background: rgba(128, 0, 255, 0.04);
            color: #8892b0;
            border: 1px solid rgba(128, 0, 255, 0.08);
            padding: 4px 14px;
            border-radius: 6px;
            font-size: 12px;
            cursor: pointer;
            transition: 0.2s;
        }

        .page-btn:hover {
            background: rgba(128, 0, 255, 0.08);
            color: #fff;
        }

        .page-btn.active {
            background: #7c4dff;
            color: #fff;
            border-color: #7c4dff;
            font-weight: 700;
        }

        .counter {
            text-align: center;
            color: #8892b0;
            font-size: 13px;
            margin: 10px 0;
        }

        .footer {
            text-align: center;
            font-size: 12px;
            color: #495670;
            margin-top: 28px;
            border-top: 1px solid rgba(128, 0, 255, 0.06);
            padding-top: 22px;
        }

        .footer-links {
            display: flex;
            justify-content: center;
            gap: 24px;
            flex-wrap: wrap;
            margin-top: 10px;
        }

        .search-box {
            width: 100%;
            padding: 12px 18px;
            border-radius: 12px;
            border: 1px solid rgba(128, 0, 255, 0.08);
            background: #0d1117;
            color: #c9d1d9;
            font-size: 14px;
            margin-bottom: 15px;
        }

        .search-box:focus {
            outline: none;
            border-color: #7c4dff;
            box-shadow: 0 0 20px rgba(128, 0, 255, 0.05);
        }

        .nav-bar {
            display: flex;
            justify-content: center;
            gap: 12px;
            margin: 10px 0;
        }

        .nav-btn {
            background: rgba(128, 0, 255, 0.04);
            color: #c9d1d9;
            border: 1px solid rgba(128, 0, 255, 0.08);
            padding: 6px 20px;
            border-radius: 8px;
            font-size: 13px;
            font-weight: 600;
            cursor: pointer;
            transition: 0.2s;
        }

        .nav-btn:hover {
            background: rgba(128, 0, 255, 0.08);
        }

        .nav-btn:disabled {
            opacity: 0.3;
            cursor: not-allowed;
        }

        @media (max-width: 768px) {
            .email-grid {
                grid-template-columns: 1fr;
            }
            .container {
                padding: 20px 16px;
            }
            .title {
                font-size: 28px;
            }
            .email-card .body-preview {
                font-size: 11px;
                max-height: 150px;
            }
            .btn-gmail,
            .btn-email,
            .btn-copy {
                font-size: 10px;
                padding: 5px 10px;
                min-width: 60px;
            }
        }
    </style>
</head>
<body>

    <div class="container">

        <!-- HEADER -->
        <div class="header">
            <div class="badge">⚡ 200 Reports | Shamshir Ali</div>
            <div>
                <span class="flag-icon">🇮🇷</span>
                <span class="title">⚔️ Shamshir Ali</span>
                <span class="flag-icon">🇮🇷</span>
            </div>
            <div class="iran-flag">جمهوری اسلامی ایران</div>
            <p class="sub">200 Unique Reports – Based on Telegram International Rules</p>
        </div>

        <!-- INFO -->
        <div class="info-box">
            <strong>📌 Target Channel:</strong> شناسایی مزدوران &nbsp;|&nbsp;
            <strong>🆔 Username:</strong> @hadafmohakeme2<br />
            <strong>⚠️ Violations Found:</strong> Doxing, Spam, Privacy Violation
        </div>

        <div class="to-box">
            <span class="label-main">📨 Send to:</span><br />
            <span class="addr-main">grievance-in@telegram.org</span><br /><br />
            <span style="color:#495670; font-size:13px;">✧ Backup:</span><br />
            <span class="addr">abuse@telegram.org</span> &nbsp;|&nbsp;
            <span class="addr">dmca@telegram.org</span> &nbsp;|&nbsp;
            <span class="addr">security@telegram.org</span>
        </div>

        <input class="search-box" id="searchBox" type="text" placeholder="🔍 Search emails..." oninput="renderPage()">

        <div class="counter" id="counterDisplay">Showing 1-20 of 200 emails</div>

        <div class="nav-bar">
            <button class="nav-btn" onclick="prevPage()">◀ Prev</button>
            <span id="pageInfo" style="color:#8b949e;display:flex;align-items:center;font-size:13px;">Page 1 of 10</span>
            <button class="nav-btn" onclick="nextPage()">Next ▶</button>
        </div>

        <div class="email-grid" id="emailGrid"></div>

        <div class="pagination" id="pagination"></div>

        <div class="footer">
            📨 Send to: grievance-in@telegram.org (Primary) | abuse@telegram.org | dmca@telegram.org |
            security@telegram.org
            <div class="footer-links">
                <span>© 2026 Shamshir Ali</span>
                <span style="color:#b388ff;">🇮🇷</span>
            </div>
        </div>
    </div>

    <script>
        // ============================================================
        // CONFIGURATION
        // ============================================================
        const TO_EMAILS = ["grievance-in@telegram.org", "abuse@telegram.org", "dmca@telegram.org",
            "security@telegram.org"
        ];
        const CHANNEL_NAME = "شناسایی مزدوران";
        const CHANNEL_USERNAME = "@hadafmohakeme2";

        const VIOLATION_LINKS = [
            "https://t.me/hadafmohakeme2/7389",
            "https://t.me/hadafmohakeme2/7387",
            "https://t.me/hadafmohakeme2/7385",
            "https://t.me/hadafmohakeme2/7382",
            "https://t.me/hadafmohakeme2/7378",
            "https://t.me/hadafmohakeme2/7376",
            "https://t.me/hadafmohakeme2/7375",
            "https://t.me/hadafmohakeme2/7373",
            "https://t.me/hadafmohakeme2/7370",
            "https://t.me/hadafmohakeme2/7367",
            "https://t.me/hadafmohakeme2/7366",
            "https://t.me/hadafmohakeme2/7365",
            "https://t.me/hadafmohakeme2/7363",
            "https://t.me/hadafmohakeme2/7360",
            "https://t.me/hadafmohakeme2/7353",
            "https://t.me/hadafmohakeme2/7352",
            "https://t.me/hadafmohakeme2/7350",
            "https://t.me/hadafmohakeme2/7349",
            "https://t.me/hadafmohakeme2/7346",
            "https://t.me/hadafmohakeme2/7343",
            "https://t.me/hadafmohakeme2/7341",
            "https://t.me/hadafmohakeme2/7340",
            "https://t.me/hadafmohakeme2/7338",
            "https://t.me/hadafmohakeme2/7337",
            "https://t.me/hadafmohakeme2/7335",
            "https://t.me/hadafmohakeme2/7333",
            "https://t.me/hadafmohakeme2/7330",
            "https://t.me/hadafmohakeme2/7325",
            "https://t.me/hadafmohakeme2/7323",
            "https://t.me/hadafmohakeme2/7322",
            "https://t.me/hadafmohakeme2/7319",
            "https://t.me/hadafmohakeme2/7318",
            "https://t.me/hadafmohakeme2/7317",
            "https://t.me/hadafmohakeme2/7316",
            "https://t.me/hadafmohakeme2/7315",
            "https://t.me/hadafmohakeme2/7314",
            "https://t.me/hadafmohakeme2/7312",
            "https://t.me/hadafmohakeme2/7309",
            "https://t.me/hadafmohakeme2/7308",
            "https://t.me/hadafmohakeme2/7307",
            "https://t.me/hadafmohakeme2/7303",
            "https://t.me/hadafmohakeme2/7301",
            "https://t.me/hadafmohakeme2/7294",
            "https://t.me/hadafmohakeme2/7293",
            "https://t.me/hadafmohakeme2/7292",
            "https://t.me/hadafmohakeme2/7290",
            "https://t.me/hadafmohakeme2/7287",
            "https://t.me/hadafmohakeme2/7285",
            "https://t.me/hadafmohakeme2/7283",
            "https://t.me/hadafmohakeme2/7280",
            "https://t.me/hadafmohakeme2/7276",
            "https://t.me/hadafmohakeme2/7274",
            "https://t.me/hadafmohakeme2/7268",
            "https://t.me/hadafmohakeme2/7267",
            "https://t.me/hadafmohakeme2/7266",
            "https://t.me/hadafmohakeme2/7265",
            "https://t.me/hadafmohakeme2/7264",
            "https://t.me/hadafmohakeme2/7261",
            "https://t.me/hadafmohakeme2/7258",
            "https://t.me/hadafmohakeme2/7257",
            "https://t.me/hadafmohakeme2/7254",
            "https://t.me/hadafmohakeme2/7250",
            "https://t.me/hadafmohakeme2/7248",
            "https://t.me/hadafmohakeme2/7247",
            "https://t.me/hadafmohakeme2/7244",
            "https://t.me/hadafmohakeme2/7242",
            "https://t.me/hadafmohakeme2/7233",
            "https://t.me/hadafmohakeme2/7230",
            "https://t.me/hadafmohakeme2/7229",
            "https://t.me/hadafmohakeme2/7222",
            "https://t.me/hadafmohakeme2/7219",
            "https://t.me/hadafmohakeme2/7218",
            "https://t.me/hadafmohakeme2/7216",
            "https://t.me/hadafmohakeme2/7214",
            "https://t.me/hadafmohakeme2/7213",
            "https://t.me/hadafmohakeme2/7209",
            "https://t.me/hadafmohakeme2/7208",
            "https://t.me/hadafmohakeme2/7204",
            "https://t.me/hadafmohakeme2/7203",
            "https://t.me/hadafmohakeme2/7202",
            "https://t.me/hadafmohakeme2/7201",
            "https://t.me/hadafmohakeme2/7200",
            "https://t.me/hadafmohakeme2/7196",
            "https://t.me/hadafmohakeme2/7190",
            "https://t.me/hadafmohakeme2/7183",
            "https://t.me/hadafmohakeme2/7181",
            "https://t.me/hadafmohakeme2/7179",
            "https://t.me/hadafmohakeme2/7174",
            "https://t.me/hadafmohakeme2/7173",
            "https://t.me/hadafmohakeme2/7168",
            "https://t.me/hadafmohakeme2/7164"
        ];

        // ============================================================
        // 200 UNIQUE EMAIL TEMPLATES
        // ============================================================
        const templates = [];

        const identities = [
            "a concerned global citizen", "a human rights defender", "a journalist", "a lawyer",
            "a university professor", "a doctor", "a student", "a researcher", "a writer",
            "a community leader", "a peace activist", "a humanitarian", "a psychologist",
            "a social worker", "a volunteer", "a nurse", "a counselor", "a mentor",
            "a guide", "a helper", "a friend", "a neighbor", "a colleague",
            "a partner", "a teammate", "a classmate", "a roommate", "a world citizen",
            "a justice advocate", "a truth seeker", "a freedom defender",
            "a protector of the vulnerable", "a voice for the voiceless", "a rights fighter",
            "a peace lover", "a oppression hater", "a dreamer of a better world",
            "an artist", "a musician", "a scientist", "a philosopher", "a historian",
            "a poet", "an engineer", "a programmer", "a designer", "a photographer",
            "a filmmaker", "a journalist", "an editor", "a publisher", "a librarian",
            "a teacher", "a sports coach", "a farmer", "a worker", "an industrialist",
            "a trader", "a merchant", "an entrepreneur", "an investor", "an analyst",
            "a financial advisor", "an accountant", "a manager", "a supervisor", "an employee",
            "a retired officer", "a soldier", "a police officer", "a firefighter", "a paramedic",
            "a forensic expert", "a psychiatrist", "a dentist", "a pharmacist", "a physiotherapist",
            "a pediatric nurse", "a midwife", "an orderly", "a technician", "a software engineer",
            "a hardware engineer", "an electrical engineer", "a mechanical engineer", "an architect", "an urban planner",
            "a geographer", "a geologist", "a meteorologist", "a biologist", "a chemist",
            "a physicist", "a mathematician", "a statistician", "an economist", "a sociologist",
            "a philosopher", "a theologian", "a historian", "a linguist", "a translator",
            "a diplomat", "a politician", "a civil servant", "a judge", "a prosecutor"
        ];

        const intros = [
            "I am writing to formally report a channel that is systematically violating Telegram's Terms of Service and international privacy laws.",
            "This is an urgent report regarding a channel that is actively engaged in doxing and spreading harmful content.",
            "I have documented serious violations by a channel that is causing real harm to individuals worldwide.",
            "The following channel is being used as a tool for harassment, privacy invasion, and the spread of harmful content.",
            "I am reporting a channel that is violating multiple Telegram policies, including doxing and spam.",
            "This channel is a direct threat to user safety and privacy, operating in clear violation of Telegram's community guidelines.",
            "I have evidence of systematic violations including sharing personal information and spreading misinformation.",
            "The content on this channel is illegal under international law and violates Telegram's own terms of service.",
            "I am submitting this report to protect innocent people from harm caused by this channel's activities.",
            "This channel poses a significant risk to public safety and must be investigated immediately.",
            "I have identified multiple violations that require your urgent attention and action.",
            "This channel is actively harming individuals by sharing their private information without consent.",
            "The network of channels associated with this account is engaged in coordinated illegal activities.",
            "I am a user who has witnessed dangerous behavior on this channel and feel compelled to report it.",
            "This report documents clear violations of Telegram's rules and international standards.",
            "I am writing to bring to your attention a channel that is engaging in illegal activities.",
            "This is a formal complaint about a channel that is violating Telegram's rules.",
            "I have discovered a channel that is being used for malicious purposes.",
            "The following channel is a clear violation of Telegram's policies.",
            "I am reporting a channel that is causing harm to individuals and communities."
        ];

        const bodies = [
            "The channel shares personal information of individuals without consent, which is a clear violation of Telegram's privacy policy.",
            "The channel encourages harassment and intimidation of specific individuals by sharing their personal information.",
            "The channel spreads misinformation and fake news that can cause panic and confusion among communities.",
            "The channel is being used to coordinate harassment campaigns against innocent individuals.",
            "They are posting personal data that can be used to identify and harm vulnerable people.",
            "The channel has been active for months and has caused numerous privacy violations.",
            "They are using Telegram to organize campaigns of intimidation and harassment.",
            "The content on this channel is designed to incite fear and silence political opposition.",
            "This channel is violating international human rights laws and Telegram's own policies.",
            "The material shared on this channel is illegal in many countries and must be removed.",
            "They are encouraging violence and causing real physical harm to people.",
            "The channel has become a platform for illegal activities and harassment.",
            "They are enabling criminals to identify and attack innocent people.",
            "The channel shares private information of individuals without their knowledge or consent.",
            "This channel is a hub for spreading dangerous misinformation and propaganda.",
            "The content on this channel is designed to deceive and manipulate users.",
            "The channel violates Telegram's policies against sharing personal information.",
            "The channel contains material that incites hatred and discrimination.",
            "The channel is a platform for spreading harmful misinformation and propaganda.",
            "The channel engages in activities that violate Telegram's safety guidelines."
        ];

        const rules = [
            "Telegram's Terms of Service strictly prohibit sharing personal information without consent (Section 5.1).",
            "Spreading misinformation that causes harm is a violation of Telegram's community guidelines.",
            "Harassment and intimidation are prohibited under Telegram's safety policies.",
            "Privacy violations are a direct breach of Telegram's core values and terms.",
            "Spam and scam content is prohibited under Telegram's anti-spam policies.",
            "Hate speech and incitement to violence violate Telegram's rules.",
            "Illegal content distribution is strictly forbidden on Telegram.",
            "All users have the right to privacy and safety as per Telegram's policy.",
            "Telegram's Terms of Service prohibit harassment and doxing.",
            "Users have the right to a safe and secure environment on Telegram."
        ];

        const closings = [
            "I urge you to investigate this channel and take immediate action to block it.",
            "Please take swift action to remove this channel and protect Telegram users.",
            "This channel must be shut down to prevent further harm to individuals.",
            "I request that you review this channel and take appropriate action.",
            "Please investigate this matter and enforce Telegram's rules.",
            "This is a serious violation that requires your immediate attention.",
            "I hope you will act swiftly to remove this dangerous channel.",
            "Please protect Telegram users by blocking this channel.",
            "This channel is a threat to safety and must be removed.",
            "I trust you will take the necessary action to stop this harmful activity.",
            "Your swift action will help protect innocent people from harm.",
            "Please take this report seriously and take appropriate action.",
            "I expect Telegram to uphold its own policies and remove this channel.",
            "This channel is causing real harm to real people right now.",
            "Please prioritize this report and take action as soon as possible.",
            "I am counting on Telegram to take action against this channel.",
            "Please do not ignore this serious violation.",
            "This channel must be removed to protect user safety.",
            "I look forward to your response and action on this matter.",
            "Thank you for your attention to this important matter."
        ];

        for (let i = 0; i < 200; i++) {
            const identity = identities[i % identities.length];
            const intro = intros[i % intros.length];
            const body = bodies[i % bodies.length];
            const rule = rules[i % rules.length];
            const closing = closings[i % closings.length];
            const num = i + 1;

            const subject =
                `🚨 Violation Report: ${CHANNEL_NAME} (Report #${num} - Doxing/Spam)`;

            // Select 10 random links for each email
            const shuffled = [...VIOLATION_LINKS].sort(() => Math.random() - 0.5);
            const selectedLinks = shuffled.slice(0, 10);

            const emailBody =
                `Dear Telegram Trust & Safety Team,

${intro}

The channel is called "${CHANNEL_NAME}" (Username: ${CHANNEL_USERNAME}) and has been active for a long time.

📋 VIOLATION TYPE: Doxing & Spam

🔍 DETAILED VIOLATION:
${body}

📜 APPLICABLE TELEGRAM RULE:
${rule}

🔗 EVIDENCE LINKS (${selectedLinks.length} sample violations):
${selectedLinks.join('\n')}

${closing}

Thank you for your attention to this serious matter.

Sincerely,
${identity.charAt(0).toUpperCase() + identity.slice(1)}

---
Report ID: H-${String(num).padStart(3, '0')}-${Date.now().toString(36)}
Channel: ${CHANNEL_NAME}
Username: ${CHANNEL_USERNAME}
Violation Type: Doxing & Spam
Evidence: ${selectedLinks.join(', ')}
`;

            templates.push({ subject, body: emailBody });
        }

        // ============================================================
        // RENDER
        // ============================================================
        let currentPage = 1;
        const perPage = 20;
