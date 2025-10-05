<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🚀 Live Betting Analyzer</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        .header {
            background: white;
            border-radius: 20px;
            padding: 40px;
            margin-bottom: 30px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
            text-align: center;
        }
        h1 {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-size: 3em;
            margin-bottom: 10px;
            font-weight: 800;
        }
        .subtitle {
            color: #666;
            font-size: 1.2em;
            margin-bottom: 20px;
        }
        .btn {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            padding: 18px 50px;
            border-radius: 50px;
            font-size: 1.2em;
            cursor: pointer;
            transition: all 0.3s;
            font-weight: 600;
            box-shadow: 0 10px 30px rgba(102, 126, 234, 0.4);
        }
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(102, 126, 234, 0.6);
        }
        .btn:active {
            transform: translateY(-1px);
        }
        .btn:disabled {
            opacity: 0.6;
            cursor: not-allowed;
            transform: none;
        }
        .loading {
            background: white;
            border-radius: 20px;
            padding: 60px;
            text-align: center;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
        }
        .loading h2 {
            color: #667eea;
            font-size: 2em;
            margin-bottom: 20px;
        }
        .loading p {
            color: #666;
            font-size: 1.1em;
            line-height: 1.8;
        }
        .spinner {
            border: 4px solid #f3f3f3;
            border-top: 4px solid #667eea;
            border-radius: 50%;
            width: 60px;
            height: 60px;
            animation: spin 1s linear infinite;
            margin: 30px auto;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        .results {
            background: white;
            border-radius: 20px;
            padding: 40px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
        }
        .results h2 {
            color: #667eea;
            font-size: 2em;
            margin-bottom: 10px;
        }
        .results-info {
            color: #666;
            margin-bottom: 30px;
            font-size: 1.1em;
        }
        .match-card {
            border: 3px solid #f0f0f0;
            border-radius: 15px;
            padding: 25px;
            margin-bottom: 20px;
            transition: all 0.3s;
            background: linear-gradient(to right, #ffffff, #f9f9f9);
        }
        .match-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(0,0,0,0.15);
            border-color: #667eea;
        }
        .match-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 15px;
        }
        .league-badge {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 0.9em;
            font-weight: 600;
        }
        .score {
            font-size: 2.5em;
            font-weight: 800;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .teams {
            font-size: 1.5em;
            font-weight: 700;
            color: #333;
            margin-bottom: 10px;
        }
        .match-time {
            color: #999;
            font-size: 1em;
            display: flex;
            align-items: center;
            gap: 5px;
        }
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }
        .stat-box {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            padding: 15px;
            border-radius: 12px;
            text-align: center;
            transition: all 0.3s;
        }
        .stat-box:hover {
            transform: scale(1.05);
        }
        .stat-label {
            font-size: 0.85em;
            color: #666;
            margin-bottom: 8px;
            font-weight: 600;
        }
        .stat-value {
            font-size: 1.8em;
            font-weight: 800;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .signal {
            background: linear-gradient(135deg, #d4fc79 0%, #96e6a1 100%);
            border-left: 5px solid #4caf50;
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
            box-shadow: 0 5px 15px rgba(76, 175, 80, 0.2);
        }
        .signal-title {
            font-weight: 700;
            color: #2e7d32;
            margin-bottom: 8px;
            font-size: 1.1em;
        }
        .confidence-bar {
            height: 8px;
            background: rgba(46, 125, 50, 0.2);
            border-radius: 10px;
            overflow: hidden;
            margin: 10px 0;
        }
        .confidence-fill {
            height: 100%;
            background: linear-gradient(90deg, #4caf50, #2e7d32);
            transition: width 0.5s ease;
        }
        .confidence-text {
            color: #2e7d32;
            font-size: 0.9em;
            font-weight: 600;
        }
        .error {
            background: linear-gradient(135deg, #ff6b6b, #ee5a6f);
            color: white;
            border-radius: 15px;
            padding: 40px;
            text-align: center;
            box-shadow: 0 20px 60px rgba(238, 90, 111, 0.3);
        }
        .error h2 {
            font-size: 2em;
            margin-bottom: 15px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🚀 Live Betting Analyzer</h1>
            <p class="subtitle">Zaawansowana analiza meczów na żywo • Powered by AI</p>
            <button class="btn" onclick="analyzeMatches()" id="analyzeBtn">
                ⚽ Analizuj Mecze Live
            </button>
        </div>

        <div id="loading" class="loading" style="display:none;">
            <h2>⚽ Analizuję mecze live...</h2>
            <div class="spinner"></div>
            <p>Pobieram dane z API-Football...<br>Analizuję statystyki xG i momentum...<br>To może potrwać kilka sekund...</p>
        </div>

        <div id="results"></div>
    </div>

    <script>
        async function analyzeMatches() {
            const btn = document.getElementById('analyzeBtn');
            const loading = document.getElementById('loading');
            const results = document.getElementById('results');

            btn.disabled = true;
            loading.style.display = 'block';
            results.innerHTML = '';

            try {
                const response = await fetch('/api/analyze');
                const data = await response.json();

                loading.style.display = 'none';
                btn.disabled = false;

                if (data.success) {
                    displayResults(data);
                } else {
                    results.innerHTML = `
                        <div class="error">
                            <h2>❌ Błąd</h2>
                            <p>${data.error}</p>
                            <p style="margin-top: 15px; font-size: 0.9em;">Sprawdź logi w Vercel Dashboard lub spróbuj ponownie</p>
                        </div>
                    `;
                }
            } catch (error) {
                loading.style.display = 'none';
                btn.disabled = false;
                results.innerHTML = `
                    <div class="error">
                        <h2>❌ Błąd połączenia</h2>
                        <p>${error.message}</p>
                        <p style="margin-top: 15px;">Możliwe przyczyny:</p>
                        <ul style="text-align: left; max-width: 400px; margin: 15px auto;">
                            <li>Brak meczów live w tym momencie</li>
                            <li>Problem z API-Football</li>
                            <li>Przekroczony limit requestów</li>
                        </ul>
                    </div>
                `;
            }
        }

        function displayResults(data) {
            const results = document.getElementById('results');

            let html = `
                <div class="results">
                    <h2>📊 Wyniki Analizy Live</h2>
                    <p class="results-info">
                        🌍 Znalezionych meczów: <strong>${data.matches_found}</strong> | 
                        🔍 Przeanalizowanych: <strong>${data.matches_analyzed}</strong> |
                        🕐 ${new Date(data.timestamp).toLocaleString('pl-PL')}
                    </p>
            `;

            if (data.results.length === 0) {
                html += `
                    <div class="error">
                        <h2>⚠️ Brak meczów do analizy</h2>
                        <p>W tym momencie nie ma dostępnych meczów live lub wszystkie mecze są w przerwie.</p>
                        <p style="margin-top: 15px;">Spróbuj ponownie za kilka minut lub w godzinach wieczornych (18:00-22:00 CEST).</p>
                    </div>
                `;
            } else {
                data.results.forEach((match, index) => {
                    html += `
                        <div class="match-card">
                            <div class="match-header">
                                <div class="league-badge">
                                    ${match.country} • ${match.league}
                                </div>
                                <div class="score">
                                    ${match.home_goals} - ${match.away_goals}
                                </div>
                            </div>

                            <div class="teams">
                                ${match.home_team} <span style="color: #999;">vs</span> ${match.away_team}
                            </div>

                            <div class="match-time">
                                ⏱️ Minuta: <strong>${match.minute}'</strong>
                            </div>

                            ${match.home_xg ? `
                                <div class="stats">
                                    <div class="stat-box">
                                        <div class="stat-label">xG Gospodarze</div>
                                        <div class="stat-value">${match.home_xg}</div>
                                    </div>
                                    <div class="stat-box">
                                        <div class="stat-label">xG Goście</div>
                                        <div class="stat-value">${match.away_xg}</div>
                                    </div>
                                    <div class="stat-box">
                                        <div class="stat-label">Total xG</div>
                                        <div class="stat-value">${match.total_xg.toFixed(1)}</div>
                                    </div>
                                </div>
                            ` : '<p style="color: #999; margin-top: 15px;">Szczegółowe statystyki niedostępne</p>'}

                            ${match.signals.map(signal => `
                                <div class="signal">
                                    <div class="signal-title">🎯 ${signal.market}</div>
                                    <div class="confidence-bar">
                                        <div class="confidence-fill" style="width: ${signal.confidence}%"></div>
                                    </div>
                                    <div class="confidence-text">
                                        Confidence: ${signal.confidence}% • ${signal.reasoning}
                                    </div>
                                </div>
                            `).join('')}

                            ${match.signals.length === 0 ? '<p style="color: #999; margin-top: 15px; text-align: center;">Brak silnych sygnałów dla tego meczu</p>' : ''}
                        </div>
                    `;
                });
            }

            html += '</div>';
            results.innerHTML = html;
        }
    </script>
</body>
</html>
