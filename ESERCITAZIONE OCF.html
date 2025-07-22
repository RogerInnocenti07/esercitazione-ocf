<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ESERCITAZIONE OCF</title>
    
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Sora:wght@400;600;700;900&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --dark-bg: #000000; 
            --primary-card-bg: rgba(16, 20, 24, 0.95); 
            --secondary-card-bg: rgba(26, 29, 33, 0.9);
            --primary-text: #e8e8e8; 
            --secondary-text: #b3b3b3; 
            --accent-primary: #3b82f6;
            --accent-secondary: #1d4ed8; 
            --border-color: #2c2c2c; 
            --success-color: #28a745; 
            --error-color: #dc3545;
            --success-bg: rgba(40, 167, 69, 0.1); 
            --error-bg: rgba(220, 53, 69, 0.1);
            --font-family: 'Sora', sans-serif;
            --valentino-yellow: #FFDE00;
            --hypnotic-purple: #9400D3;
        }

        * { 
            margin: 0; 
            padding: 0; 
            box-sizing: border-box; 
        }

        ::-webkit-scrollbar { 
            width: 8px; 
        } 
        ::-webkit-scrollbar-track { 
            background: #111; 
        } 
        ::-webkit-scrollbar-thumb { 
            background-color: var(--accent-primary); 
            border-radius: 10px; 
        }

        body {
            font-family: var(--font-family); 
            color: var(--primary-text); 
            min-height: 100vh;
            background-color: var(--dark-bg);
            background-size: cover;
            background-position: center center;
            background-attachment: fixed;
            transition: background-image 0.5s ease-in-out;
        }

        .container { 
            max-width: 1400px; 
            margin: 0 auto; 
            padding: 20px; 
        }

        .header {
            display: flex;
            justify-content: space-between; 
            align-items: center;
            padding: 15px;
            margin-bottom: 25px;
            flex-wrap: wrap; 
            gap: 20px;
        }

        .header .header-buttons-left {
            display: flex;
            gap: 10px; 
            align-items: center;
            flex-wrap: wrap;
        }

        .header .title-wrapper {
            text-align: center;
            flex-grow: 1; 
        }

        .header h1 {
            font-size: 2.2em;
            font-weight: 700;
            margin: 0;
            color: var(--valentino-yellow);
            text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
        }

        .hypnotic-subtitle {
            font-size: 1.2em;
            font-weight: 700;
            margin-top: 10px;
            cursor: pointer;
            letter-spacing: 1px;
            color: rgba(255, 255, 255, 0.9);
            background: -webkit-radial-gradient(center, ellipse cover, var(--accent-primary) 0%, var(--hypnotic-purple) 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 8px rgba(255,255,255,0.3);
            transition: all 0.5s ease-in-out;
        }

        .hypnotic-subtitle.hypno-active {
            animation: hypno-pulse-strong 2s ease-in-out infinite alternate;
        }

        @keyframes hypno-pulse-strong {
            from { text-shadow: 0 0 10px #fff,0 0 20px #00FFFF,0 0 30px #00FFFF,0 0 40px var(--hypnotic-purple),0 0 50px var(--hypnotic-purple); }
            to { text-shadow: 0 0 20px #fff,0 0 30px #00FFFF,0 0 40px #00FFFF,0 0 50px var(--hypnotic-purple),0 0 60px var(--hypnotic-purple),0 0 70px var(--hypnotic-purple); }
        }

        .header-time-info {
            display: flex;
            flex-direction: column;
            align-items: flex-end;
            min-width: 220px; 
            font-family: 'Sora', sans-serif;
        }

        .time-display {
            font-weight: 600; 
            font-size: 1em; 
            color: var(--accent-secondary); 
            line-height: 1.5;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.5);
        }

        .time-display span {
            color: var(--secondary-text); 
            font-size: 0.8em; 
            margin-right: 8px;
        }

        .btn.btn-black-blue {
            background-color: rgba(0,0,0,0.7);
            color: var(--accent-primary);
            border: 1px solid var(--accent-primary);
        }

        .btn.btn-black-blue:hover {
            background-color: var(--secondary-card-bg);
        }

        .main-content { 
            display: grid; 
            grid-template-columns: 1fr 340px; 
            gap: 25px; 
        }

        .quiz-section, .stats-section { 
            background: var(--primary-card-bg); 
            border-radius: 20px; 
            padding: 30px; 
            border: 1px solid var(--border-color); 
        }

        .btn { 
            padding: 12px 25px; 
            border: none; 
            border-radius: 8px; 
            font-size: 0.9em; 
            cursor: pointer; 
            transition: all 0.3s ease; 
            font-weight: 600; 
            display: inline-flex; 
            align-items: center; 
            justify-content: center; 
            gap: 8px; 
            text-decoration: none;
        }

        .btn-primary { 
            background: linear-gradient(45deg, var(--accent-primary), var(--accent-secondary)); 
            color: white; 
            box-shadow: 0 4px 15px rgba(59, 130, 246, 0.2); 
        }

        .btn-primary:hover:not(:disabled) { 
            transform: translateY(-3px); 
            box-shadow: 0 6px 20px rgba(59, 130, 246, 0.4); 
        }

        .btn-secondary { 
            background: rgba(51,51,51,0.8); 
            color: var(--primary-text); 
            border: 1px solid #444;
        }

        .btn-secondary:hover { 
            background: #444; 
            border-color: #555; 
        }

        .btn:disabled { 
            opacity: 0.5; 
            cursor: not-allowed; 
            transform: none; 
            box-shadow: none; 
        }

        h2 { 
            font-weight: 600; 
            margin-bottom: 1.5rem; 
            border-bottom: 1px solid var(--border-color); 
            padding-bottom: 1rem; 
            color:#fff; 
            text-shadow: 1px 1px 2px rgba(0,0,0,0.3);
        }

        #subjectsDashboard { 
            display: grid; 
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); 
            gap: 20px; 
        }

        .subject-card { 
            background: var(--secondary-card-bg); 
            border-radius: 15px; 
            padding: 25px; 
            display: flex; 
            flex-direction: column; 
            justify-content: space-between; 
            border: 1px solid var(--border-color); 
            transition: transform 0.2s, box-shadow 0.2s; 
        }

        .subject-card:hover { 
            transform: translateY(-5px); 
            box-shadow: 0 10px 20px rgba(0,0,0,0.2); 
        }

        .subject-card h3 {
            font-size: 1.1em; 
            margin-bottom: 10px; 
            color: #fff;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.3);
        }

        .subject-card h3 .matter-prefix {
            display: block;
            font-size: 0.8em;
            color: var(--secondary-text);
            margin-bottom: 5px;
            text-transform: uppercase;
        }

        .subject-card .status { 
            font-size: 0.9em; 
            color: var(--secondary-text); 
            min-height: 20px; 
            margin-bottom: 20px; 
        }

        .subject-card .controls { 
            display: flex; 
            gap: 10px; 
            margin-top: auto; 
        }

        .timer-container { 
            display: flex; 
            align-items: center; 
            justify-content: center; 
            gap: 15px; 
            margin-bottom: 20px;
        }

        #pauseBtn { 
            width: 44px; 
            height: 44px; 
            border-radius: 50%; 
            padding: 0; 
            font-size: 1.2em; 
            background: rgba(26, 29, 33, 0.8); 
            border: 1px solid var(--border-color);
        }

        .quiz-frozen .answer-option, .quiz-frozen .controls button { 
            pointer-events: none; 
            opacity: 0.5; 
        }

        #pauseBtn { 
            opacity: 1 !important; 
            pointer-events: all !important;
        }

        .question {
            font-size: 1.15em;
            margin-bottom: 25px;
            line-height: 1.6;
            color: #fff;
            font-weight: 600;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.7);
            text-align: justify;
        }

        .answers { 
            display: flex; 
            flex-direction: column; 
            gap: 15px; 
        }

        .answer-option { 
            padding: 18px 25px; 
            background: var(--secondary-card-bg); 
            border: 2px solid var(--border-color); 
            border-radius: 10px; 
            cursor: pointer; 
            transition: all 0.2s ease-in-out; 
        }

        .answer-option:hover, .answer-option.selected { 
            border-color: var(--accent-primary); 
            background: #2f2f2f; 
            transform: scale(1.02); 
        }

        .answer-option.correct {
            background: var(--accent-primary);
            border-color: var(--accent-primary);
            color: white;
            transform: scale(1.02);
        }

        .answer-option.incorrect {
            background: var(--error-color);
            border-color: var(--error-color);
            color: white;
            transform: scale(1.02);
        }

        .stats-card { 
            margin-bottom: 2rem; 
        }

        .stat-item { 
            display: flex; 
            justify-content: space-between; 
            margin-bottom: 12px; 
            font-size: 0.95em; 
        }

        .stat-value { 
            font-weight: 600; 
            color: var(--accent-primary); 
        }

        .modal { 
            display: none; 
            position: fixed; 
            top: 0; 
            left: 0; 
            width: 100%; 
            height: 100%; 
            background: rgba(0, 0, 0, 0.8); 
            backdrop-filter: blur(8px); 
            z-index: 1000; 
            align-items: flex-start; 
            justify-content: center; 
            overflow-y: auto; 
            padding: 5vh 15px;
        }

        .modal-content { 
            background: rgba(21, 21, 21, 0.95); 
            border-radius: 20px; 
            padding: 30px; 
            width: 100%; 
            max-width: 600px;
            animation: slideIn 0.3s; 
            border: 1px solid var(--border-color); 
        }

        @keyframes slideIn { 
            from { transform: translateY(-50px); opacity: 0; } 
            to { transform: translateY(0); opacity: 1; } 
        }

        .modal-content.review-modal { 
            max-width: 950px; 
            text-align: left;
        }

        #reviewContainer, #historyContainer, #errorsReviewContainer, #analysisResultsContainer { 
            margin-top: 30px; 
            display: flex; 
            flex-direction: column; 
            gap: 20px; 
            max-height: 70vh; 
            overflow-y:auto; 
            padding-right:10px;
        }
        
        #analysisResultsContainer {
             text-align: left;
        }

        .review-question, .history-entry { 
            background: rgba(28, 28, 28, 0.9); 
            padding: 20px; 
            border-radius: 10px; 
            border-left: 4px solid var(--border-color);
        }

        .review-answer { 
            display: flex; 
            align-items: center; 
            gap: 10px; 
            padding: 12px; 
            border-radius: 5px; 
            opacity: 0.8; 
            border:1px solid transparent;
        }

        .review-answer.correct { 
            opacity: 1; 
            border-color: var(--success-color); 
            background: rgba(40,167,69, 0.08);
        }

        .review-answer.user-incorrect { 
            opacity: 1; 
            border-color: var(--error-color); 
            background: rgba(220,53,69, 0.08);
        }

        .history-entry { 
            display: grid; 
            grid-template-columns: 1fr auto; 
            align-items: center; 
            gap: 20px; 
        }

        .history-entry-chart { 
            width: 100px; 
            height: 100px; 
        }

        .question-indicator-container {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-top: 25px;
            justify-content: center;
            padding: 10px;
            background: var(--secondary-card-bg);
            border-radius: 10px;
            border: 1px solid var(--border-color);
            max-height: 150px;
            overflow-y: auto;
        }

        .question-indicator {
            width: 35px;
            height: 35px;
            border-radius: 8px;
            background-color: var(--border-color);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.9em;
            font-weight: 700;
            cursor: pointer;
            transition: background-color 0.2s, transform 0.2s, border-color 0.2s;
            color: var(--primary-text);
            border: 2px solid transparent;
        }

        .question-indicator:hover {
            transform: translateY(-2px);
            border-color: var(--accent-primary);
        }

        .question-indicator.answered-correct {
            background-color: var(--accent-secondary);
            color: white;
            border-color: var(--accent-secondary);
        }

        .question-indicator.answered-incorrect {
            background-color: var(--error-color);
            color: white;
            border-color: var(--error-color);
        }

        .question-indicator.skipped {
            background-color: var(--hypnotic-purple);
            color: white;
        }

        .question-indicator.current {
            border: 3px solid var(--valentino-yellow);
            transform: scale(1.1);
            box-shadow: 0 0 10px rgba(255, 222, 0, 0.5);
        }
        
        .keyword-tag {
            display: inline-block;
            background-color: var(--accent-secondary);
            color: white;
            padding: 4px 10px;
            border-radius: 12px;
            font-size: 0.85em;
            margin: 3px;
        }
        
        #keywordHelperContent {
            display: flex;
            flex-wrap: wrap;
            gap: 5px;
            padding-top: 10px;
        }


        @media (max-width: 900px) { 
            .main-content { 
                grid-template-columns: 1fr; 
            } 
            .stats-section { 
                order: -1; 
            } 
            .header {
                flex-direction: column;
            }
            .header .header-buttons-left, .header .header-time-info {
                width: 100%;
                justify-content: center;
                flex-direction: row;
                align-items: center;
            }
            .header .header-time-info {
                align-items: center;
            }
        }

        @media (max-width: 480px) {
            .header h1 {
                font-size: 1.8em;
            }
            .hypnotic-subtitle {
                font-size: 1em;
            }
            .quiz-section, .stats-section {
                padding: 20px;
            }
            .btn {
                padding: 10px 15px;
                font-size: 0.8em;
            }
            .question {
                font-size: 1em;
            }
            .answer-option {
                padding: 15px 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header class="header">
            <div class="header-buttons-left">
                <a href="https://www.organismocf.it/portal/web/portale-ocf/accedi?p_p_id=com_liferay_login_web_portlet_LoginPortlet&p_p_lifecycle=0&_com_liferay_login_web_portlet_LoginPortlet_redirect=%2Fportal%2Fgroup%2Farea-riservata%2Fworkspace" target="_blank" class="btn btn-black-blue">WORKSPACE OCF</a>
                <button class="btn btn-black-blue" id="resetAppBtn">🔄 Azzera</button>
                <button class="btn btn-black-blue" id="openMixedQuizModalBtn">Quiz Misto</button> </div>
            <div class="title-wrapper">
                <h1>ESERCITAZIONE ESAME OCF</h1>
                <p id="hypnoSubtitle" class="hypnotic-subtitle">Roger Innocenti - CONSULENTE FINANZIARIO MEDIOLANUM</p>
            </div>
             <div class="header-time-info">
                <div class="time-display" id="dateDisplay">--/--/----</div>
                <div class="time-display" id="realTimeClock">--:--:--</div>
                <div class="time-display"><span>Sessione:</span><span id="sessionTimer">00:00:00</span></div>
            </div>
        </header>

        <div class="main-content">
            <section class="quiz-section" id="mainSection"></section>
            <aside class="stats-section">
                <h2>Statistiche</h2>
                <div class="stats-card"><h3>Sessione Corrente</h3><div class="stat-item"><span>Risposte:</span><span class="stat-value" id="sessionAnswered">0</span></div><div class="stat-item"><span>Corrette:</span><span class="stat-value" id="sessionCorrect">0</span></div><div class="stat-item"><span>Percentuale:</span><span class="stat-value" id="sessionPercentage">0%</span></div></div>
                <div class="stats-card"><h3>Performance di Oggi</h3><div class="stat-item"><span>Corrette:</span><span class="stat-value" id="todayCorrect">-</span></div><div class="stat-item"><span>Errate:</span><span class="stat-value" id="todayIncorrect">-</span></div><div class="stat-item"><span>Percentuale:</span><span class="stat-value" id="todayPercentage">-</span></div></div>
                
                <div class="stats-card" id="keywordHelperCard" style="display: none;">
                    <h3>Suggeritore Parole Chiave</h3>
                    <div id="keywordHelperContent">
                        <p style="color: var(--secondary-text); font-size: 0.9em;">Le parole chiave della domanda corrente appariranno qui.</p>
                    </div>
                </div>
                <div class="stats-card" id="weeklyDashboardCard">
                    <h3>Dashboard Settimanale</h3><canvas id="performanceChart" height="140"></canvas><button class="btn btn-secondary" id="showHistoryBtn" style="width:100%;margin-top:15px;">Visualizza Storico</button>
                </div>


                <div class="stats-card"><h3>Gestione Dati</h3>
                    <div class="stat-item"><span>Errori da Ripassare:</span><span class="stat-value" id="errorQuestionsCount">0</span></div>
                    <button class="btn btn-secondary" id="reviewErrorsBtn" style="width:100%;margin-top:10px; margin-bottom: 1.5rem;" disabled>Ripassa Errori</button>
                    <div class="backup-controls" style="display:flex; flex-direction: column; gap:10px; justify-content:center;margin:1rem 0;">
                        <label class="btn btn-secondary"><input type="file" id="bgUpload" accept="image/*" style="display:none;">Carica Sfondo</label>
                        <label class="btn btn-primary"><input type="file" id="multiFileUpload" accept=".txt,.json" multiple style="display:none;">Carica File Materie</label> <button class="btn btn-secondary" id="saveBackupBtn">Salva</button>
                        <label class="btn btn-secondary"><input type="file" id="loadBackupInput" accept=".json" style="display:none;">Carica</label>
                    </div>
                    <button class="btn btn-secondary" id="analyzeTextBtn" style="width:100%; margin-top:10px;">Analizza File TXT</button>
                    <button class="btn btn-secondary" id="resetStatsBtn" style="width:100%;background-color:#501b1b;border-color:var(--error-color); margin-top: 10px;">Resetta Statistiche</button>
                </div>
            </aside>
        </div>
    </div>

    <div class="modal" id="resultsModal"><div class="modal-content" style="max-width:600px;text-align:center;"><h2>🎉 Quiz Completato!</h2><div class="results-summary" style="display:flex;justify-content:space-around;text-align:center;margin:20px 0;"></div><div class="controls" style="margin-top:30px;display:flex;justify-content:center;gap:15px;"><button class="btn btn-secondary" id="reviewQuizBtn">Rivedi Risposte</button><button class="btn btn-primary" id="backToDashboardBtn">Torna alla Dashboard</button></div></div></div>
    <div class="modal" id="reviewModal"><div class="modal-content review-modal"><h2>Riepilogo Sessione</h2><div id="reviewContainer"></div><div class="controls" style="text-align:center;margin-top:20px;"><button class="btn btn-secondary" id="closeReviewBtn">Chiudi</button></div></div></div>
    <div class="modal" id="historyModal"><div class="modal-content review-modal"><h2>Storico Performance</h2><div id="historyContainer"></div><div class="controls" style="text-align:center;margin-top:20px;"><button class="btn btn-secondary" id="closeHistoryBtn">Chiudi</button></div></div></div>
    <div class="modal" id="errorsModal"><div class="modal-content review-modal"><h2>Riepilogo Errori Complessivi</h2><div id="errorsReviewContainer"></div><div class="controls" style="text-align:center;margin-top:20px;"><button class="btn btn-secondary" id="closeErrorsBtn">Chiudi</button></div></div></div>
    <div class="modal" id="mixedQuizModal">
        <div class="modal-content" style="max-width:700px;">
            <h2>Crea Quiz Misto (60 Domande)</h2>
            <p style="margin-bottom:20px;">Seleziona le materie da cui vuoi estrarre le domande per un quiz misto.</p>
            <div id="mixedQuizSubjectsContainer" style="display:grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; margin-bottom: 25px;">
            </div>
            <button class="btn btn-primary" id="startMixedQuizBtn" disabled>Inizia Quiz Misto (60 Domande)</button>
            <button class="btn btn-secondary" id="closeMixedQuizModalBtn" style="margin-top: 15px;">Annulla</button>
        </div>
    </div>

    <div class="modal" id="textAnalyzerModal">
        <div class="modal-content" style="max-width: 800px;">
            <h2>Analizzatore di File di Testo</h2>
            <p style="margin-bottom:20px; color: var(--secondary-text);">Carica un file .txt per analizzarne il contenuto.</p>
            <label class="btn btn-primary">
                Carica File TXT
                <input type="file" id="txtAnalysisUpload" accept=".txt,text/plain" style="display:none;">
            </label>
            <div id="analysisResultsContainer" style="margin-top: 25px; text-align: left;">
            </div>
            <div class="controls" style="text-align:center;margin-top:20px;">
                <button class="btn btn-secondary" id="closeTextAnalyzerBtn">Chiudi</button>
            </div>
        </div>
    </div>
    
    <!-- MODAL DI CONFERMA PERSONALIZZATA -->
    <div class="modal" id="confirmModal">
        <div class="modal-content" style="max-width: 450px; text-align: center;">
            <h2 id="confirmModalTitle">Sei sicuro?</h2>
            <p id="confirmModalText" style="margin: 20px 0; color: var(--secondary-text);"></p>
            <div class="controls" style="display:flex;justify-content:center;gap:15px;">
                <button class="btn btn-secondary" id="confirmModalCancelBtn">Annulla</button>
                <button class="btn btn-primary" id="confirmModalConfirmBtn" style="background-color: var(--error-color);">Conferma</button>
            </div>
        </div>
    </div>

    <script>
        const MATERIE={diritto_mercato:"PRIMA MATERIA Diritto del mercato finanziario e degli intermediari",matematica_fin:"SECONDA MATERIA Matematica finanziaria, mercati e strumenti, pianificazione, finanza comportamentale e investimenti ESG",diritto_tributario:"TERZA MATERIA Nozioni di diritto tributario riguardanti il mercato finanziario",diritto_previdenziale:"QUARTA MATERIA Nozioni di diritto previdenziale e assicurativo",diritto_privato:"QUINTA MATERIA Nozioni di diritto privato e di diritto commerciale",domande_miste_ocf:"DOMANDE MISTE OCF"};
        let quizzesBySubject={};
        let allQuestions = []; 
        let filteredQuestions=[];
        let currentQuestionIndex=0;
        let selectedAnswer=null;
        let timerInterval=null;
        let performanceChartInstance=null;
        let dailyChartInstances=[];
        let stats={session:{},global:{errorQuestions:[],history:[]}};
        const ICONS={correct:`<svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="var(--success-color)" stroke-width="2"><path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"/><path d="m22 4-10 10.01L9 11.01"/></svg>`,incorrect:`<svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="var(--error-color)" stroke-width="2"><circle cx="12" cy="12" r="10"/><path d="m15 9-6 6"/><path d="m9 9 6 6"/></svg>`};
        let UI={};
        let confirmCallback = null;

        let questionStates = new Map();

        const QUESTION_STATUS = {
            UNANSWERED: 'unanswered',
            ANSWERED_CORRECT: 'answered-correct',
            ANSWERED_INCORRECT: 'answered-incorrect',
            SKIPPED: 'skipped'
        };

        const KEYWORD_SETS = {
            diritto_mercato: [
                'agenti in attività finanziaria', 'imprese di assicurazione', 'revisori contabili', 'consulente finanziario autonomo', 'consulente finanziario abilitato all\'offerta fuori sede', 'consulente finanziario', 'società di consulenza finanziaria', 'sgr', 'sim', 'sicav', 'sicaf', 'banca', 'consob', 'ivass', 'banca d\'italia', 'uif', 'cicr', 'cliente', 'intermediari', 'soggetti obbligati', 'controparti centrali', 'depositario centrale', 'organismo di vigilanza', 'emittenti', 'azionisti', 'personale', 'esponenti aziendali', 'organo di amministrazione', 'organo di controllo', 'collegio sindacale', 'società di revisione', 'cliente al dettaglio', 'cliente professionale', 'controparte qualificata', 'iscritti nell\'elenco', 'operano nei rami', 'applicano l\'art', 'svolgere attività', 'presta consulenza', 'promuove e colloca', 'vigila su', 'autorizza', 'è compatibile con', 'è incompatibile con', 'è tenuto a', 'deve comunicare', 'può essere sospeso', 'si applica la sanzione', 'conservazione dei dati', 'ricezione e trasmissione di ordini', 'esecuzione di ordini', 'gestione di portafogli', 'offerta fuori sede', 'comunicazione a distanza', 'cessazione di violazioni', 'sospendere il diritto di voto', 'revocabile', 'approva il documento', 'adeguata verifica', 'valutare l\'adeguatezza', 'valutare l\'appropriatezza', 'presumere l\'appropriatezza', 'operazioni sospette', 'sana e prudente gestione', 'prodotti finanziari', 'strumenti finanziari', 'mercato regolamentato', 'sistemi multilaterali di negoziazione', 'trasparenza delle condizioni contrattuali', 'abusi di mercato', 'informazioni privilegiate', 'prospetto informativo', 'documento d\'offerta', 'albo unico dei consulenti finanziari', 'attribuiscono una quota dei diritti di voto'
            ],
            matematica_fin: [
                'tasso di interesse', 'capitalizzazione composta', 'capitalizzazione semplice', 'valore attuale netto', 'van', 'tasso interno di rendimento', 'tir', 'duration', 'ammortamento', 'opzioni', 'futures', 'swap', 'certificati di credito del tesoro', 'cct', 'tasso variabile', 'tasso fisso', 'zero coupon', 'con cedola', 'senza cedola', 'rendimento', 'montante', 'valore attuale', 'valore nominale', 'prezzo tel quel', 'prezzo secco', 'struttura a termine', 'curva dei rendimenti', 'buoni ordinari del tesoro', 'bot', 'btp', 'ctz', 'coupon bond', 'floating rate note', 'tasso annuo nominale', 'tan', 'tasso effettivo globale', 'taeg', 'scadenza', 'flussi di cassa'
            ],
            diritto_tributario: [
                'irpef', 'ires', 'iva', 'imposta di bollo', 'capital gain', 'base imponibile', 'ritenuta a titolo d\'imposta', 'dichiarazione dei redditi', 'crediti d\'imposta', 'tassazione rendite finanziarie', 'imposta sostitutiva', 'dividendi', 'plusvalenze', 'minusvalenze', 'principio di cassa', 'principio di competenza', 'cedolare secca', 'sostituto d\'imposta', 'contribuente', 'imposta sulle successioni', 'imposta sulle donazioni', 'imposta di registro', 'imposta ipotecaria', 'imposta catastale'
            ],
            diritto_previdenziale: [
                'polizze vita', 'fondi pensione', 'previdenza complementare', 'ivass', 'covip', 'rischio demografico', 'prestazioni pensionistiche', 'contributi', 'montante contributivo', 'ramo vita', 'ramo danni', 'tfr', 'pip', 'fondi aperti', 'fondi chiusi', 'riscatto', 'anticipazione', 'rendita vitalizia', 'capitale', 'assicurazione sulla vita', 'assicurazione contro i danni', 'premio assicurativo', 'indennizzo'
            ],
            diritto_privato: [
                'contratto', 'obbligazioni', 'società di persone', 'società di capitali', 's.p.a.', 's.r.l.', 'fallimento', 'liquidazione', 'nullità del contratto', 'annullabilità', 'rappresentanza', 'diritto di recesso', 'patrimonio', 'persona giuridica', 'proprietà', 'possesso', 'diritti reali', 'successione', 'testamento', 'donazione', 'responsabilità contrattuale', 'responsabilità extracontrattuale', 'buona fede', 'diligenza del buon padre di famiglia', 'vizi del consenso', 'errore', 'violenza', 'dolo', 'capacità di agire', 'interdizione', 'inabilitazione'
            ]
        };

        document.addEventListener('DOMContentLoaded',()=>{
            const e=[
                'mainSection','reviewQuizBtn','closeReviewBtn','saveBackupBtn','loadBackupInput',
                'showHistoryBtn','closeHistoryBtn','resetStatsBtn','backToDashboardBtn',
                'resetAppBtn','reviewErrorsBtn','closeErrorsBtn','bgUpload',
                'multiFileUpload', 'mixedQuizModal', 'startMixedQuizBtn', 'closeMixedQuizModalBtn',
                'mixedQuizSubjectsContainer', 'openMixedQuizModalBtn',
                'analyzeTextBtn', 'textAnalyzerModal', 'closeTextAnalyzerBtn', 'txtAnalysisUpload', 'analysisResultsContainer',
                'keywordHelperCard', 'keywordHelperContent', 'weeklyDashboardCard',
                'confirmModal', 'confirmModalTitle', 'confirmModalText', 'confirmModalCancelBtn', 'confirmModalConfirmBtn'
            ];
            e.forEach(e=>UI[e]=document.getElementById(e));
            setupEventListeners();
            startRealTimeAndSessionClocks();
            loadAllData();
            switchView('dashboard')
        });

        function showConfirmModal(title, text, onConfirm) {
            UI.confirmModalTitle.textContent = title;
            UI.confirmModalText.textContent = text;
            confirmCallback = onConfirm;
            UI.confirmModal.style.display = 'flex';
        }

        function startRealTimeAndSessionClocks(){
            const e=document.getElementById('realTimeClock'),t=document.getElementById('sessionTimer'),n=document.getElementById('dateDisplay'),r=Date.now();
            setInterval(()=>{
                const o=new Date;
                e.textContent=o.toLocaleTimeString('it-IT',{timeZone:'Europe/Rome'});
                n.textContent=new Intl.DateTimeFormat('it-IT',{weekday:'long',day:'2-digit',month:'2-digit',year:'numeric'}).format(o).replace(",","");
                const a=Date.now()-r,i=Math.floor(a/36e5),s=Math.floor(a%36e5/6e4),l=Math.floor(a%6e4/1e3);
                t.textContent=`${i.toString().padStart(2,'0')}:${s.toString().padStart(2,'0')}:${l.toString().padStart(2,'0')}`
            },1e3)
        }

        function setupEventListeners(){
            UI.reviewQuizBtn.addEventListener('click',showReviewModal);
            UI.closeReviewBtn.addEventListener('click',()=>document.getElementById('reviewModal').style.display='none');
            UI.saveBackupBtn.addEventListener('click',saveBackup);
            UI.loadBackupInput.addEventListener('change',handleBackupUpload);
            UI.showHistoryBtn.addEventListener('click',showHistoryModal);
            UI.closeHistoryBtn.addEventListener('click',()=>document.getElementById('historyModal').style.display='none');
            UI.resetStatsBtn.addEventListener('click',resetGlobalStats);
            UI.backToDashboardBtn.addEventListener('click',()=>switchView('dashboard'));
            UI.resetAppBtn.addEventListener('click',resetAllQuizzes);
            UI.reviewErrorsBtn.addEventListener('click',showErrorsModal);
            UI.closeErrorsBtn.addEventListener('click',()=>document.getElementById('errorsModal').style.display='none');
            UI.bgUpload&&UI.bgUpload.addEventListener('change',handleBgUpload);
            const e=document.getElementById('hypnoSubtitle');
            e&&e.addEventListener('click',()=>e.classList.toggle('hypno-active'));
            const t=localStorage.getItem('custom-bg');
            t&&(document.body.style.backgroundImage=`url(${t}`);
            
            UI.multiFileUpload && UI.multiFileUpload.addEventListener('change', handleMultiFileUpload);
            UI.startMixedQuizBtn && UI.startMixedQuizBtn.addEventListener('click', startMixedQuiz);
            UI.closeMixedQuizModalBtn && UI.closeMixedQuizModalBtn.addEventListener('click', () => UI.mixedQuizModal.style.display = 'none');
            UI.openMixedQuizModalBtn && UI.openMixedQuizModalBtn.addEventListener('click', openMixedQuizModal);

            UI.analyzeTextBtn.addEventListener('click', () => {
                UI.analysisResultsContainer.innerHTML = '<p style="color: var(--secondary-text);">In attesa di un file...</p>';
                UI.textAnalyzerModal.style.display = 'flex';
            });
            UI.closeTextAnalyzerBtn.addEventListener('click', () => UI.textAnalyzerModal.style.display = 'none');
            UI.txtAnalysisUpload.addEventListener('change', handleTextFileAnalysis);

            // Listeners per la modal di conferma
            UI.confirmModalCancelBtn.addEventListener('click', () => {
                UI.confirmModal.style.display = 'none';
                confirmCallback = null;
            });
            UI.confirmModalConfirmBtn.addEventListener('click', () => {
                if (confirmCallback) {
                    confirmCallback();
                }
                UI.confirmModal.style.display = 'none';
                confirmCallback = null;
            });
        }

        function handleTextFileAnalysis(event) {
            const file = event.target.files[0];
            if (!file) return;
            if (file.type !== 'text/plain') {
                alert('Per favore, carica un file in formato .txt');
                return;
            }
            const reader = new FileReader();
            reader.onload = (e) => {
                try {
                    const text = e.target.result;
                    const analysisResults = analyzeText(text);
                    displayAnalysisResults(analysisResults, file.name);
                } catch (error) {
                    UI.analysisResultsContainer.innerHTML = `<p style="color: var(--error-color);">Errore durante l'analisi del file: ${error.message}</p>`;
                }
            };
            reader.onerror = () => {
                UI.analysisResultsContainer.innerHTML = `<p style="color: var(--error-color);">Impossibile leggere il file.</p>`;
            };
            reader.readAsText(file, 'UTF-8');
            event.target.value = null; 
        }

        function analyzeText(text) {
            const charCount = text.length;
            const charCountNoSpaces = text.replace(/\s/g, '').length;
            const words = text.trim().split(/\s+/).filter(word => word.length > 0);
            const wordCount = words.length;
            const lineCount = text.split('\n').length;
            const wordFrequencies = new Map();
            words.forEach(word => {
                const cleanWord = word.toLowerCase().replace(/[.,\/#!$%\^&\*;:{}=\-_`~()]/g,"");
                if (cleanWord) {
                    wordFrequencies.set(cleanWord, (wordFrequencies.get(cleanWord) || 0) + 1);
                }
            });
            const sortedFrequencies = Array.from(wordFrequencies.entries()).sort((a, b) => b[1] - a[1]).slice(0, 10);
            return { charCount, charCountNoSpaces, wordCount, lineCount, topWords: sortedFrequencies };
        }

        function displayAnalysisResults(results, fileName) {
            let frequencyTable = `
                <h4 style="margin-top: 20px; margin-bottom: 10px; color: var(--primary-text);">Top 10 Parole più Frequenti:</h4>
                <table style="width: 100%; border-collapse: collapse;">
                    <thead><tr style="border-bottom: 1px solid var(--border-color);"><th style="padding: 8px; text-align: left;">Parola</th><th style="padding: 8px; text-align: right;">Frequenza</th></tr></thead>
                    <tbody>`;
            if (results.topWords.length > 0) {
                 results.topWords.forEach(([word, count]) => {
                    frequencyTable += `<tr style="border-bottom: 1px solid var(--border-color);"><td style="padding: 8px;">${word}</td><td style="padding: 8px; text-align: right;">${count}</td></tr>`;
                });
            } else {
                 frequencyTable += `<tr><td colspan="2" style="padding: 8px; text-align: center; color: var(--secondary-text);">Nessuna parola trovata.</td></tr>`;
            }
            frequencyTable += `</tbody></table>`;
            UI.analysisResultsContainer.innerHTML = `
                <h3 style="color: var(--valentino-yellow); margin-bottom: 15px;">Risultati per: ${fileName}</h3>
                <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-bottom: 20px;">
                    <div style="background: var(--secondary-card-bg); padding: 15px; border-radius: 8px;"><div style="font-size: 1.5em; font-weight: bold; color: var(--accent-primary);">${results.wordCount.toLocaleString('it-IT')}</div><div style="font-size: 0.9em; color: var(--secondary-text);">Parole</div></div>
                    <div style="background: var(--secondary-card-bg); padding: 15px; border-radius: 8px;"><div style="font-size: 1.5em; font-weight: bold; color: var(--accent-primary);">${results.lineCount.toLocaleString('it-IT')}</div><div style="font-size: 0.9em; color: var(--secondary-text);">Righe</div></div>
                    <div style="background: var(--secondary-card-bg); padding: 15px; border-radius: 8px;"><div style="font-size: 1.5em; font-weight: bold; color: var(--accent-primary);">${results.charCount.toLocaleString('it-IT')}</div><div style="font-size: 0.9em; color: var(--secondary-text);">Caratteri (con spazi)</div></div>
                    <div style="background: var(--secondary-card-bg); padding: 15px; border-radius: 8px;"><div style="font-size: 1.5em; font-weight: bold; color: var(--accent-primary);">${results.charCountNoSpaces.toLocaleString('it-IT')}</div><div style="font-size: 0.9em; color: var(--secondary-text);">Caratteri (senza spazi)</div></div>
                </div>
                ${frequencyTable}`;
        }

        function handleBgUpload(e){
            const t=e.target.files[0];
            if(t&&t.type.startsWith('image/')){
                const n=new FileReader;
                n.onload=e=>{const t=e.target.result;document.body.style.backgroundImage=`url(${t})`,localStorage.setItem('custom-bg',t)},n.readAsDataURL(t)
            }
        }

        function switchView(e,t=null){
            document.querySelectorAll('.modal').forEach(e=>e.style.display='none');
            if (e === 'dashboard') {
                UI.keywordHelperCard.style.display = 'none';
                UI.weeklyDashboardCard.style.display = 'block';
                renderDashboard();
            } else if (e === 'quiz' && t) {
                UI.keywordHelperCard.style.display = 'block';
                UI.weeklyDashboardCard.style.display = 'none';
                renderQuizView(t);
            }
        }

        function renderDashboard(){
            UI.mainSection.innerHTML=`<h2>Seleziona una materia per esercitarti</h2><div id="subjectsDashboard"></div>`;
            const e=document.getElementById('subjectsDashboard');
            e.innerHTML=Object.entries(MATERIE).map(([t,n])=>{
                const r=quizzesBySubject[t],o=n.split(" "),a=o.shift(),i=o.join(" ");
                return`<div class="subject-card"><div><h3><span class="matter-prefix">${a}</span>${i}</h3><p class="status">${r?`${r.length} domande caricate`:"Nessun quiz caricato"}</p></div><div class="controls"><label class="btn btn-secondary">Carica File<input type="file" class="file-input" data-subject-key="${t}" accept=".txt,.json" style="display:none;"></label><button class="btn btn-primary start-quiz-btn" data-subject-key="${t}" ${r?"":"disabled"}>Inizia Quiz</button></div></div>`
            }).join("");
            e.querySelectorAll(".file-input").forEach(e=>e.addEventListener("change",handleFileUpload));
            e.querySelectorAll(".start-quiz-btn").forEach(e=>e.addEventListener("click",startQuiz));
        }

        function renderQuizView(subjectKey){
            UI.mainSection.innerHTML=`
                <div id="quizView">
                    <div class="timer-container">
                        <div id="timer" style="font-size:1.2em;color:var(--accent-primary);">Tempo: <span id="timeDisplay">00:00</span></div>
                        <button id="pauseBtn" class="btn">⏸️</button>
                    </div>
                    <div id="quizContainer" class="question-container">
                        <div class="question-info" style="display:flex;justify-content:space-between;margin-bottom:15px;font-size:0.9em;color:var(--secondary-text);">
                            <span>Domanda <span id="currentQuestion"></span>/<span id="totalQuestions"></span></span>
                            <span>Materia: ${MATERIE[subjectKey]}</span>
                        </div>
                        <div class="question" id="questionText"></div>
                        <div class="answers" id="answersContainer"></div>
                        <div class="controls" style="display:flex;justify-content:space-around;gap:15px;margin-top:30px;">
                            <button id="prevQuestionBtn" class="btn btn-primary">Indietro</button>
                            <button id="confirmAnswerBtn" class="btn btn-primary">Conferma</button>
                            <button id="skipQuestionBtn" class="btn btn-secondary">Salta</button>
                            <button id="exitQuizBtn" class="btn btn-secondary" style="background-color: #991b1b; border-color: var(--error-color);">Esci dal Quiz</button>
                        </div>
                        <div class="question-indicator-container" id="questionIndicatorContainer">
                        </div>
                    </div>
                </div>
            `;
            Object.assign(UI,{
                confirmAnswerBtn:document.getElementById('confirmAnswerBtn'),
                skipQuestionBtn:document.getElementById('skipQuestionBtn'),
                prevQuestionBtn:document.getElementById('prevQuestionBtn'),
                pauseBtn:document.getElementById('pauseBtn'),
                questionIndicatorContainer: document.getElementById('questionIndicatorContainer'),
                exitQuizBtn: document.getElementById('exitQuizBtn')
            });
            UI.confirmAnswerBtn.addEventListener('click',confirmAnswer);
            UI.skipQuestionBtn.addEventListener('click',skipQuestion);
            UI.prevQuestionBtn.addEventListener('click',prevQuestion);
            UI.pauseBtn.addEventListener('click',togglePause);
            UI.exitQuizBtn.addEventListener('click', () => {
                showConfirmModal(
                    "Uscire dal Quiz?",
                    "I progressi di questa sessione non verranno salvati nelle statistiche generali. Sei sicuro di voler tornare alla dashboard?",
                    () => {
                        stopTimer();
                        stats.session = {}; 
                        switchView('dashboard');
                    }
                );
            });
            showQuestion();
            renderQuestionIndicators();
        }

        function showQuestion(){
            const question=filteredQuestions[currentQuestionIndex];
            selectedAnswer=null;
            document.getElementById('currentQuestion').textContent=currentQuestionIndex+1;
            document.getElementById('totalQuestions').textContent=filteredQuestions.length;
            document.getElementById('questionText').textContent=question.text;

            const answersContainer=document.getElementById('answersContainer');
            answersContainer.innerHTML='';
            Object.entries(question.answers).sort((a,b)=>a[0].localeCompare(b[0])).forEach(([letter,answerData])=>{
                const option=document.createElement('div');
                option.className='answer-option';
                option.dataset.letter=letter;
                const answerText = typeof answerData === 'string' ? answerData : answerData.text;
                option.innerHTML=`<label style="pointer-events:none"><strong>${letter}:</strong> ${answerText}</label>`;
                option.addEventListener('click',()=>selectAnswer(letter,option));
                answersContainer.appendChild(option);
            });

            UI.prevQuestionBtn.disabled = currentQuestionIndex === 0;
            const status = questionStates.get(question.number);
            const isAnswered = status === QUESTION_STATUS.ANSWERED_CORRECT || status === QUESTION_STATUS.ANSWERED_INCORRECT;

            UI.confirmAnswerBtn.disabled = true;
            UI.skipQuestionBtn.disabled = isAnswered;
            
            Array.from(answersContainer.children).forEach(option => {
                option.style.pointerEvents = isAnswered ? 'none' : 'auto';
                if (isAnswered) {
                    if (option.dataset.letter === question.correct) {
                        option.classList.add('correct');
                    } else if (question.userAnswer && option.dataset.letter === question.userAnswer) {
                        option.classList.add('incorrect');
                    }
                }
            });
            
            displayKeywords(question);
            renderQuestionIndicators();
        }
        
        function displayKeywords(question) {
            let keywordsToShow;
            if (question.keywords && question.keywords.length > 0) { 
                const allKeywords = new Set(question.keywords);
                Object.values(question.answers).forEach(answerData => {
                    if (answerData.keywords) {
                        answerData.keywords.forEach(kw => allKeywords.add(kw));
                    }
                });
                keywordsToShow = allKeywords;
            } else { 
                keywordsToShow = extractKeywordsFromText(question, stats.session.subjectKey);
            }

            const uniqueKeywords = [...keywordsToShow];
            if (uniqueKeywords.length > 0) {
                UI.keywordHelperContent.innerHTML = uniqueKeywords.map(word => `<span class="keyword-tag">${word}</span>`).join('');
            } else {
                UI.keywordHelperContent.innerHTML = `<p style="color: var(--secondary-text); font-size: 0.9em;">Nessuna parola chiave rilevante trovata.</p>`;
            }
        }

        function extractKeywordsFromText(question, subjectKey) {
            let fullText = question.text;
            // Aggiungi solo il testo della risposta corretta per l'analisi
            const correctAnswerLetter = question.correct;
            const correctAnswerData = question.answers[correctAnswerLetter];
            if (correctAnswerData) {
                fullText += ' ' + (typeof correctAnswerData === 'string' ? correctAnswerData : correctAnswerData.text);
            }

            const textLower = fullText.toLowerCase();
            const foundKeywords = new Set();

            // Scegli il set di parole chiave corretto in base alla materia
            const keyPhrases = KEYWORD_SETS[subjectKey] || [].concat(...Object.values(KEYWORD_SETS));

            // 1. TEMA CENTRALE
            const topicMatchers = [
                /in materia di ([\w\s]+)/i,
                /relativo a ([\w\s]+)/i,
                /riguardanti ([\w\s]+)/i,
                /disciplina de[gli|i|l] ([\w\s]+)/i,
                /alla tenuta de[l] ([\w\s]+)/i
            ];
            topicMatchers.forEach(regex => {
                const match = question.text.toLowerCase().match(regex);
                if (match && match[1]) {
                    let topic = match[1].replace(/(,)?\s*provvede.*$/, '').trim();
                    foundKeywords.add(topic);
                }
            });

            // 2. FRASI CHIAVE (Soggetti, Azioni, Oggetti)
            keyPhrases.forEach(phrase => {
                if (textLower.includes(phrase)) {
                    foundKeywords.add(phrase);
                }
            });

            // 3. RIFERIMENTI NORMATIVI
            const oggettiRegex = /(d\.\s?lgs\.?\s?n\.?\s?\d{1,4}\/\d{2,4}|art\.\s?\d{1,4}-?[a-z,]*|tuf|tub|cap|regolamento\s*\(ue\)\s*\d{4}\/\d{4})/gi;
            const lawMatches = textLower.match(oggettiRegex);
            if (lawMatches) {
                lawMatches.forEach(match => foundKeywords.add(match.replace(/[,.]$/, '').trim()));
            }
            
            return foundKeywords;
        }


        function selectAnswer(e,t){ 
            selectedAnswer=e; 
            document.querySelectorAll('.answer-option').forEach(e=>e.classList.remove('selected')); 
            t.classList.add('selected'); 
            UI.confirmAnswerBtn.disabled = false; 
        } 

        function parseTxtQuestions(text) { 
            const questions = []; 
            const cleanedText = text.replace(/\r\n/g, '\n').replace(/\[cite[^\]]*\]/g, ''); 
            const questionBlocks = cleanedText.split(/(?=^\s*(?:\*\*Domanda numero:|Domanda numero:|Domanda:)\s*\d+)/im); 

            for (const block of questionBlocks) { 
                if (block.trim() === '') continue; 

                const questionNumberMatch = block.match(/(?:Domanda\s*numero:|Domanda:)\s*(\d+)/i); 
                if (!questionNumberMatch) continue; 
                const questionNumber = parseInt(questionNumberMatch[1], 10); 

                const correctAnswerMatch = block.match(/Risposta\s*(?:corretta|esatta):\s*([A-D])/im); 
                if (!correctAnswerMatch) continue; 
                const correctAnswer = correctAnswerMatch[1].toUpperCase(); 

                const answers = {}; 
                const answerLines = block.match(/^[A-D]:\s*.+/gm); 
                if (answerLines) { 
                    answerLines.forEach(line => { 
                        const letter = line.charAt(0); 
                        const answerText = line.substring(2).trim(); 
                        answers[letter] = answerText; 
                    }); 
                } 
                
                if (Object.keys(answers).length === 0) { 
                     const alternativeBlockMatch = block.match(/Alternative\s*risposta:([\s\S]*?)(?=Risposta\s*corretta|Risposta\s*esatta)/i); 
                     if(alternativeBlockMatch) { 
                         const answerLinesFromAlt = alternativeBlockMatch[1].match(/^[A-D]:\s*.+/gm); 
                         if(answerLinesFromAlt) { 
                             answerLinesFromAlt.forEach(line => { 
                                const letter = line.charAt(0); 
                                const answerText = line.substring(2).trim(); 
                                answers[letter] = answerText; 
                            }); 
                         } 
                     } 
                } 

                if (Object.keys(answers).length < 2) continue; 

                let questionText = block; 
                questionText = questionText.replace(/^\s*(?:\*\*Domanda\s*numero:|Domanda\s*numero:|Domanda:)\s*\d+.*?\n/im, ''); 
                questionText = questionText.replace(/Alternative\s*risposta:[\s\S]*/i, ''); 
                Object.values(answers).forEach(ans => { 
                    const escapedAns = ans.replace(/[.*+?^${}()|[\]\\]/g, '\\$&'); 
                    const ansRegex = new RegExp(`^[A-D]:\\s*${escapedAns}\\s*`, 'gm'); 
                    questionText = questionText.replace(ansRegex, ''); 
                }); 
                questionText = questionText.replace(/Risposta\s*(?:corretta|esatta):\s*[A-D].*/i, ''); 
                questionText = questionText.replace(/Domanda:/g, '').replace(/\*\*/g, '').replace(/\n/g, ' ').trim(); 

                if (questionText) { 
                    questions.push({ 
                        number: questionNumber, 
                        text: questionText, 
                        answers: answers, 
                        correct: correctAnswer, 
                        level: 1  
                    }); 
                } 
            } 
            return questions; 
        } 
        
        function parseJsonQuestions(jsonString) { 
            try { 
                const data = JSON.parse(jsonString); 
                if (!Array.isArray(data)) { 
                    console.error("Il file JSON non contiene un array di domande."); 
                    return []; 
                } 

                return data.map((q, index) => { 
                    const answers = {}; 
                    for (const key in q.opzioni) { 
                        answers[key] = { 
                            text: q.opzioni[key].testo, 
                            keywords: q.opzioni[key].keywords || [] 
                        }; 
                    } 

                    return { 
                        number: q.domanda.numero || index + 1, 
                        text: q.domanda.testo, 
                        keywords: q.domanda.keywords || [], 
                        answers: answers, 
                        correct: q.risposta_esatta, 
                        level: 1 
                    }; 
                }); 
            } catch (error) { 
                console.error("Errore nel parsing del file JSON:", error); 
                alert("Errore: il file JSON non è formattato correttamente."); 
                return []; 
            } 
        } 

        function handleFileUpload(e){ 
            const t=e.target.files[0],n=e.target.dataset.subjectKey; 
            if(t&&n){ 
                const r=new FileReader; 
                r.onload=e=>processFileContent(e.target.result, n, t.name); 
                r.onerror=()=>alert('Errore lettura file.'); 
                r.readAsText(t,'UTF-8') 
            } 
            e.target.value=null; 
        } 

        function handleMultiFileUpload(event) { 
            const files = event.target.files; 
            if (files.length === 0) return; 
            let loadedFilesCount = 0; 
            const totalFiles = files.length; 
            for (let i = 0; i < files.length; i++) { 
                const file = files[i]; 
                const reader = new FileReader(); 
                reader.onload = (e) => { 
                    const subjectKey = file.name.replace(/\.(txt|json)$/i, '').toLowerCase().replace(/ /g, '_'); 
                    if (!MATERIE[subjectKey]) { 
                        MATERIE[subjectKey] = file.name.replace(/\.(txt|json)$/i, '').toUpperCase(); 
                    } 
                    processFileContent(e.target.result, subjectKey, file.name, true); 
                    loadedFilesCount++; 
                    if (loadedFilesCount === totalFiles) { 
                        // Non mostrare alert per ogni file, ma uno solo alla fine 
                    } 
                }; 
                reader.onerror = () => { 
                    // Gestisci l'errore 
                    loadedFilesCount++; 
                }; 
                reader.readAsText(file, 'UTF-8'); 
            } 
        } 

        function processFileContent(content, subjectKey, fileName, isMultiUpload = false) { 
            let questions = []; 
            if (fileName.toLowerCase().endsWith('.json')) { 
                questions = parseJsonQuestions(content); 
            } else { 
                questions = parseTxtQuestions(content); 
            } 

            if(0===questions.length) { 
                if (!isMultiUpload) showConfirmModal("Errore di Caricamento", `Nessuna domanda valida trovata nel file "${fileName}". Controlla il formato del file.`, ()=>{}); 
                return; 
            } 
            quizzesBySubject[subjectKey]=questions; 
            saveAllData(); 
            if (!isMultiUpload) { 
                showConfirmModal("Caricamento Riuscito", `${questions.length} domande caricate per "${MATERIE[subjectKey]}".`, ()=>{}); 
                renderDashboard(); 
            } 
            allQuestions = Object.values(quizzesBySubject).flat(); 
        } 

        function startQuiz(e){ 
            const t=e.target.dataset.subjectKey,n=quizzesBySubject[t]; 
            if(!n||0===n.length)return void alert('Nessuna domanda disponibile.'); 
            
            filteredQuestions=[...n].sort(()=>.5-Math.random()); 
            questionStates.clear(); 
            filteredQuestions.forEach(q => { 
                q.userAnswer = null; 
                questionStates.set(q.number, QUESTION_STATUS.UNANSWERED) 
            }); 

            stats.session={subjectKey:t,questions:filteredQuestions,answered:0,correct:0,isPaused:!1,startTime:Date.now(),accumulatedTime:0}; 
            currentQuestionIndex=0; 
            switchView('quiz',t); 
            startTimer(); 
        } 

        function openMixedQuizModal() { 
            UI.mixedQuizSubjectsContainer.innerHTML = ''; 
            let hasSelectableSubjects = false; 
            for (const key in MATERIE) { 
                if (quizzesBySubject[key] && quizzesBySubject[key].length > 0) { 
                    hasSelectableSubjects = true; 
                    const subjectDiv = document.createElement('div'); 
                    subjectDiv.style.cssText = 'display:flex; align-items:center; gap:10px; background:var(--secondary-card-bg); padding:10px; border-radius:8px; border:1px solid var(--border-color);'; 
                    subjectDiv.innerHTML = ` 
                        <input type="checkbox" id="subject-${key}" data-subject-key="${key}" style="width:20px; height:20px;"> 
                        <label for="subject-${key}" style="flex-grow:1; cursor:pointer;">${MATERIE[key]}</label> 
                    `; 
                    UI.mixedQuizSubjectsContainer.appendChild(subjectDiv); 
                } 
            } 

            if (!hasSelectableSubjects) { 
                UI.mixedQuizSubjectsContainer.innerHTML = '<p style="text-align:center; color:var(--secondary-text);">Nessuna materia con domande caricate. Carica prima i file.</p>'; 
                UI.startMixedQuizBtn.disabled = true; 
            } else { 
                UI.mixedQuizSubjectsContainer.querySelectorAll('input[type="checkbox"]').forEach(checkbox => { 
                    checkbox.addEventListener('change', () => { 
                        const selectedCount = UI.mixedQuizSubjectsContainer.querySelectorAll('input[type="checkbox"]:checked').length; 
                        UI.startMixedQuizBtn.disabled = selectedCount === 0; 
                    }); 
                }); 
                UI.startMixedQuizBtn.disabled = true; 
            } 
            UI.mixedQuizModal.style.display = 'flex'; 
        } 

        function startMixedQuiz() { 
            const selectedSubjects = Array.from(UI.mixedQuizSubjectsContainer.querySelectorAll('input[type="checkbox"]:checked')) 
                .map(checkbox => checkbox.dataset.subjectKey); 

            if (selectedSubjects.length === 0) { 
                return; 
            } 

            let questionsFromSelectedSubjects = []; 
            selectedSubjects.forEach(subjectKey => { 
                if (quizzesBySubject[subjectKey]) { 
                    questionsFromSelectedSubjects = questionsFromSelectedSubjects.concat(quizzesBySubject[subjectKey]); 
                } 
            }); 

            if (questionsFromSelectedSubjects.length === 0) { 
                return; 
            } 
            
            filteredQuestions = shuffleArray(questionsFromSelectedSubjects).slice(0, 60); 

            if (filteredQuestions.length === 0) { 
                return; 
            } 

            questionStates.clear(); 
            filteredQuestions.forEach(q => { 
                    q.userAnswer = null; 
                    questionStates.set(q.number, QUESTION_STATUS.UNANSWERED) 
            }); 

            stats.session = { 
                subjectKey: 'domande_miste_ocf', 
                questions: filteredQuestions, 
                answered: 0, 
                correct: 0, 
                isPaused: false, 
                startTime: Date.now(), 
                accumulatedTime: 0 
            }; 
            currentQuestionIndex = 0; 
            switchView('quiz', 'domande_miste_ocf'); 
            startTimer(); 
            UI.mixedQuizModal.style.display = 'none'; 
        } 

        function shuffleArray(array) { 
            for (let i = array.length - 1; i > 0; i--) { 
                const j = Math.floor(Math.random() * (i + 1)); 
                [array[i], array[j]] = [array[j], array[i]]; 
            } 
            return array; 
        } 

        function startTimer(){stopTimer();const e=document.getElementById('timeDisplay');timerInterval=setInterval(()=>{if(!stats.session.isPaused&&e){const t=stats.session.accumulatedTime+(Date.now()-stats.session.startTime);e.textContent=`${Math.floor(t/6e4).toString().padStart(2,'0')}:${Math.floor(t/1e3%60).toString().padStart(2,'0')}`}},1e3)} 
        function stopTimer(){clearInterval(timerInterval);timerInterval=null} 
        function togglePause(){stats.session.isPaused=!stats.session.isPaused;const e=document.getElementById('quizContainer'),t=document.getElementById('pauseBtn');stats.session.isPaused?(stats.session.accumulatedTime+=Date.now()-stats.session.startTime,t&&(t.innerHTML='▶️'),e&&e.classList.add('quiz-frozen')):(stats.session.startTime=Date.now(),t&&(t.innerHTML='⏸️'),e&&e.classList.remove('quiz-frozen'))} 

        function confirmAnswer(){ 
            if(!selectedAnswer){return;} 
            
            const question=filteredQuestions[currentQuestionIndex]; 
            const isCorrect=selectedAnswer===question.correct; 
            
            stats.session.answered++; 
            question.userAnswer = selectedAnswer; 
            stats.session.questions[currentQuestionIndex].userAnswer = selectedAnswer; 

            if(isCorrect){ 
                stats.session.correct++; 
                questionStates.set(question.number, QUESTION_STATUS.ANSWERED_CORRECT); 
            } else { 
                questionStates.set(question.number, QUESTION_STATUS.ANSWERED_INCORRECT); 
            } 
            
            recordAnswerInHistory(question.number,isCorrect,selectedAnswer); 
            updateStatsDisplay(); 

            Array.from(document.getElementById('answersContainer').children).forEach(n=>{ 
                n.style.pointerEvents='none'; 
                if(n.dataset.letter===question.correct){ 
                    n.classList.add('correct'); 
                } else if(n.dataset.letter===selectedAnswer){ 
                    n.classList.add('incorrect'); 
                } 
            }); 

            UI.confirmAnswerBtn.disabled=true; 
            UI.skipQuestionBtn.disabled=true; 
            renderQuestionIndicators(); 

            setTimeout(() => { 
                nextQuestion(); 
            }, 1500); 
        } 

        function skipQuestion(){ 
            const question=filteredQuestions[currentQuestionIndex]; 
            questionStates.set(question.number, QUESTION_STATUS.SKIPPED); 
            stats.session.questions[currentQuestionIndex].userAnswer='skipped'; 
            
            nextQuestion(); 
        } 

        function prevQuestion() { 
            if (currentQuestionIndex > 0) { 
                currentQuestionIndex--; 
                showQuestion(); 
            } 
        } 

        function nextQuestion() { 
            if (currentQuestionIndex < filteredQuestions.length - 1) { 
                currentQuestionIndex++; 
                showQuestion(); 
            } else { 
                endQuiz(); 
            } 
        } 

        function endQuiz(){ 
            stats.session.isPaused||(stats.session.accumulatedTime+=Date.now()-stats.session.startTime); 
            stopTimer(); 
            saveAllData(); 
            updateStatsDisplay(); 
            const e=document.querySelector('#resultsModal .results-summary'),t=stats.session.accumulatedTime,n=`${Math.floor(t/6e4).toString().padStart(2,'0')}:${Math.floor(t/1e3%60).toString().padStart(2,'0')}`; 
            const r=filteredQuestions.length>0?Math.round(stats.session.correct/filteredQuestions.length*100):0; 
            e.innerHTML=`<div class="result-stat"><strong>${r}%</strong><span>Punteggio</span></div><div class="result-stat"><strong>${stats.session.correct}/${filteredQuestions.length}</strong><span>Corrette</span></div><div class="result-stat"><strong>${n}</strong><span>Tempo</span></div>`,document.getElementById('resultsModal').style.display='flex' 
            UI.keywordHelperCard.style.display = 'none'; 
            UI.weeklyDashboardCard.style.display = 'block'; 
        } 

        function showReviewModal(){ 
            document.getElementById('reviewContainer').innerHTML=stats.session.questions.map(e=>{ 
                let t=Object.entries(e.answers).sort((e,t)=>e[0].localeCompare(t[0])).map(([t,n])=>{ 
                    let r='review-answer',o=''; 
                    const answerText = typeof n === 'string' ? n : n.text; 
                    return t===e.correct?(r+=' correct',o=ICONS.correct):t===e.userAnswer&&(r+=' user-incorrect',o=ICONS.incorrect),`<div class="${r}">${o}<strong>${t}:</strong> ${answerText}</div>` 
                }).join(''); 
                return`<div class="review-question"><p><strong>Domanda ${e.number}:</strong> ${e.text}</p><div class="review-answers-list">${t}</div></div>` 
            }).join(''); 
            document.getElementById('resultsModal').style.display='none'; 
            document.getElementById('reviewModal').style.display='flex'; 
        } 

        function showHistoryModal(){ 
            dailyChartInstances.forEach(e=>e.destroy()),dailyChartInstances=[]; 
            const e=document.getElementById('historyContainer'),t=stats.global.history.reduce((e,t)=>{const n=new Date(t.timestamp).toISOString().split('T')[0];return e[n]||(e[n]=[]),e[n].push(t),e},{}),n=Object.keys(t).sort((e,n)=>new Date(n)-new Date(e)); 
            e.innerHTML=n.length>0?n.map(e=>{const n=t[e],r=n.filter(e=>e.isCorrect).length,o=n.length,a=o>0?Math.round(r/o*100):0,i=new Intl.DateTimeFormat('it-IT',{weekday:'short',day:'2-digit',month:'2-digit',year:'numeric'}).format(new Date(e));return`<div class="history-entry"><div class="history-entry-stats"><div class="history-entry-date">${i.replace(",","")}</div><div class="stat-item"><span>Corrette:</span><span style="color:var(--success-color)">${r}</span></div><div class="stat-item"><span>Errate:</span><span style="color:var(--error-color)">${o-r}</span></div><div class="stat-item"><span>Percentuale:</span><span>${a}%</span></div></div><div class="history-entry-chart"><canvas id="chart-${e}"></canvas></div></div>`}).join(''):'<p>Nessuno storico disponibile.</p>'; 
            n.forEach(e=>{ 
                const n=t[e],r=n.filter(e=>e.isCorrect).length,o=n.length; 
                if(o>0){ 
                    const a=new Chart(document.getElementById(`chart-${e}`),{type:'doughnut',data:{labels:['Corrette','Errate'],datasets:[{data:[r,o-r],backgroundColor:['rgba(40,167,69,0.8)','rgba(220,53,69,0.8)'],borderColor:['#151515'],borderWidth:2}]},options:{responsive:!0,maintainAspectRatio:!1,plugins:{legend:{display:!1},tooltip:{enabled:!1}}}}); 
                    dailyChartInstances.push(a) 
                } 
            }); 
            document.getElementById('historyModal').style.display='flex' 
        } 

        function showErrorsModal(){ 
            const e=document.getElementById('errorsReviewContainer'),t=new Set(stats.global.errorQuestions); 
            if(0===t.size)return e.innerHTML='<p style="text-align:center; color: var(--secondary-text);">Nessun errore da ripassare. Ottimo lavoro!</p>',void(document.getElementById('errorsModal').style.display='flex'); 
            const n=new Map; 
            Object.values(quizzesBySubject).flat().forEach(e=>n.set(e.number,e)),e.innerHTML=Array.from(t).map(e=>{ 
                const t=n.get(e); 
                if(!t)return''; 
                const r=[...stats.global.history].reverse().find(t=>t.number===e&&!t.isCorrect),o=r?r.userAnswer:null; 
                let a=Object.entries(t.answers).sort((e,t)=>e[0].localeCompare(t[0])).map(([n,r])=>{ 
                    let a='review-answer',i=''; 
                    const answerText = typeof r === 'string' ? r : r.text; 
                    return n===t.correct?(a+=' correct',i=ICONS.correct):n===o&&(a+=' user-incorrect',i=ICONS.incorrect),`<div class="${a}">${i}<strong>${n}:</strong> ${answerText}</div>` 
                }).join(''); 
                return`<div class="review-question"><p><strong>Domanda ${t.number}:</strong> ${t.text}</p><div class="review-answers-list">${a}</div></div>` 
            }).join(''); 
            document.getElementById('errorsModal').style.display='flex' 
        } 

        function renderQuestionIndicators() { 
            const container = UI.questionIndicatorContainer; 
            if (!container) return; 
            container.innerHTML = ''; 

            filteredQuestions.forEach((question, index) => { 
                const indicator = document.createElement('div'); 
                indicator.className = 'question-indicator'; 
                indicator.textContent = index + 1; 

                const status = questionStates.get(question.number); 
                if (status) { 
                    indicator.classList.add(status); 
                } 

                if (index === currentQuestionIndex) { 
                    indicator.classList.add('current'); 
                } 

                indicator.addEventListener('click', () => { 
                    currentQuestionIndex = index; 
                    showQuestion(); 
                }); 
                container.appendChild(indicator); 
            }); 
        } 

        function loadAllData(){ 
            const e=localStorage.getItem("quizOCFData_v1"); 
            if(e)try{ 
                const t=JSON.parse(e); 
                quizzesBySubject=t.quizzes||{}; 
                stats.global=t.global||{errorQuestions:[],history:[]}; 
                allQuestions = Object.values(quizzesBySubject).flat(); 
            }catch(t){ 
                quizzesBySubject={}; 
                stats.global={errorQuestions:[],history:[]}; 
                allQuestions = []; 
            } 
            updateStatsDisplay(); 
        } 

        function saveAllData(){localStorage.setItem("quizOCFData_v1",JSON.stringify({quizzes:quizzesBySubject,global:stats.global}))} 
        
        function resetAllQuizzes(){ 
            showConfirmModal( 
                "Azzera Tutti i Quiz?", 
                "Questa azione cancellerà permanentemente tutte le domande caricate da tutti i file. Sei sicuro di voler procedere?", 
                () => { 
                    quizzesBySubject={}; 
                    allQuestions=[]; 
                    saveAllData(); 
                    switchView('dashboard'); 
                } 
            ); 
        } 

        function resetGlobalStats(){ 
             showConfirmModal( 
                "Resettare le Statistiche?", 
                "ATTENZIONE! Questa azione cancellerà TUTTE le statistiche di performance, inclusi lo storico e gli errori salvati. Sei sicuro?", 
                () => { 
                    stats.global={errorQuestions:[],history:[]}; 
                    stats.session={}; 
                    saveAllData(); 
                    updateStatsDisplay(); 
                    renderDashboard(); 
                } 
            ); 
        } 

        function saveBackup(){const e=new Blob([JSON.stringify({quizzes:quizzesBySubject,global:stats.global},null,2)],{type:'application/json'}),t=document.createElement('a');t.href=URL.createObjectURL(e),t.download=`OCF_Backup_${(new Date).toISOString().split('T')[0]}.json`,document.body.appendChild(t),t.click(),document.body.removeChild(t),URL.revokeObjectURL(t.href)} 
        function handleBackupUpload(e){const t=e.target.files[0];if(!t)return;const n=new FileReader;n.onload=e=>{try{const t=JSON.parse(e.target.result);t.global&&t.quizzes?(stats.global=t.global,quizzesBySubject=t.quizzes,allQuestions = Object.values(quizzesBySubject).flat(),saveAllData(),updateStatsDisplay(),renderDashboard(),alert('Backup caricato.')):alert('File non valido.')}catch(t){alert('Errore parsing backup.')}},n.readAsText(t),e.target.value=null} 
        function recordAnswerInHistory(e,t,n){stats.global.history.push({number:e,userAnswer:n,isCorrect:t,timestamp:Date.now()});const r=new Set(stats.global.errorQuestions);t?r.delete(e):r.add(e),stats.global.errorQuestions=Array.from(r)} 
        function updateStatsDisplay(){const{answered:e=0,correct:t=0}=stats.session;document.getElementById('sessionAnswered').textContent=e,document.getElementById('sessionCorrect').textContent=t; 
        const sessionPercentage = stats.session.answered > 0 ? Math.round(stats.session.correct/stats.session.answered*100) : 0; 
        document.getElementById('sessionPercentage').textContent=`${sessionPercentage}%`; 
        const n=new Date;n.setHours(0,0,0,0);const r=stats.global.history.filter(e=>e.timestamp>=n.getTime()),o=r.filter(e=>e.isCorrect).length,a=r.length;document.getElementById('todayCorrect').textContent=o,document.getElementById('todayIncorrect').textContent=a-o,document.getElementById('todayPercentage').textContent=a>0?`${Math.round(o/a*100)}%`:'-';const i=stats.global.errorQuestions.length;document.getElementById('errorQuestionsCount').textContent=i,UI.reviewErrorsBtn&&(UI.reviewErrorsBtn.disabled=0===i),renderPerformanceChart()} 
        function calculatePerformanceInDateRange(e,t){const n=stats.global.history.filter(n=>n.timestamp>=e&&n.timestamp<=t);return 0===n.length?0:Math.round(n.filter(e=>e.isCorrect).length/n.length*100)} 
        
        function renderPerformanceChart() { 
            if (performanceChartInstance) performanceChartInstance.destroy(); 

            const today = new Date(); 
            const dayOfWeek = today.getDay();  
            const monday = new Date(); 
            const diff = monday.getDate() - dayOfWeek + (dayOfWeek === 0 ? -6 : 1); 
            monday.setDate(diff); 
            monday.setHours(0, 0, 0, 0); 

            const labels = []; 
            const data = []; 
            const backgroundColors = []; 

            for (let i = 0; i < 7; i++) { 
                const currentDay = new Date(monday); 
                currentDay.setDate(monday.getDate() + i); 
                
                labels.push(currentDay.toLocaleDateString('it-IT', { weekday: 'short' })); 

                if (currentDay <= today) { 
                    const startOfDay = new Date(currentDay); 
                    startOfDay.setHours(0, 0, 0, 0); 
                    const endOfDay = new Date(currentDay); 
                    endOfDay.setHours(23, 59, 59, 999); 
                    data.push(calculatePerformanceInDateRange(startOfDay.getTime(), endOfDay.getTime())); 
                } else { 
                    data.push(null);  
                } 

                if (currentDay.toDateString() === today.toDateString()) { 
                    backgroundColors.push('var(--valentino-yellow)'); 
                } else { 
                    backgroundColors.push('rgba(59, 130, 246, 0.4)'); 
                } 
            } 

            performanceChartInstance = new Chart('performanceChart', { 
                type: 'bar', 
                data: { 
                    labels: labels, 
                    datasets: [{ 
                        data: data, 
                        backgroundColor: backgroundColors, 
                        borderColor: 'rgba(59,130,246,1)', 
                        borderWidth: 1, 
                        borderRadius: 5 
                    }] 
                }, 
                options: { 
                    responsive: true, 
                    scales: { 
                        y: { beginAtZero: true, max: 100, ticks: { color: 'rgba(255,255,255,0.7)', callback: e => e + '%' } }, 
                        x: { ticks: { color: 'rgba(255,255,255,0.7)' }, grid: { display: false } } 
                    }, 
                    plugins: { legend: { display: false } } 
                } 
            }); 
        } 
     </script> 
 </body> 
 </html>
