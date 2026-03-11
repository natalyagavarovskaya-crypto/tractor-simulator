<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MTZ BELARUS - Реалистичная сборка трактора</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background: linear-gradient(135deg, #0f1419 0%, #1a1f2e 100%);
            color: #fff;
            overflow: hidden;
            height: 100vh;
        }

        /* Header */
        .header {
            background: linear-gradient(135deg, #C41E3A 0%, #8B0000 100%);
            padding: 12px 25px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 4px 20px rgba(0,0,0,0.4);
            z-index: 100;
            position: relative;
        }

        .logo {
            font-size: 1.4em;
            font-weight: bold;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .timer-section {
            display: flex;
            align-items: center;
            gap: 20px;
        }

        .timer {
            font-size: 1.5em;
            font-weight: bold;
            font-family: 'Courier New', monospace;
            background: rgba(0,0,0,0.3);
            padding: 8px 18px;
            border-radius: 8px;
            border: 2px solid rgba(255,255,255,0.2);
        }

        .timer.warning { color: #ffaa00; animation: pulse 1s infinite; }
        .timer.danger { color: #ff4444; animation: pulse 0.5s infinite; }

        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.6; }
        }

        .progress-info {
            text-align: right;
        }

        .progress-label {
            font-size: 0.75em;
            opacity: 0.8;
        }

        .progress-value {
            font-size: 1.2em;
            font-weight: bold;
            color: #00ff88;
        }

        /* Main */
        .main {
            display: flex;
            height: calc(100vh - 65px);
        }

        /* Left Panel - Parts */
        .parts-panel {
            width: 240px;
            background: rgba(15, 20, 30, 0.98);
            padding: 15px;
            overflow-y: auto;
            border-right: 1px solid rgba(0, 255, 136, 0.2);
        }

        .panel-title {
            font-size: 1em;
            color: #00ff88;
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 2px solid rgba(0, 255, 136, 0.3);
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .part-item {
            background: linear-gradient(135deg, rgba(30, 40, 55, 0.9) 0%, rgba(20, 30, 45, 0.9) 100%);
            border: 2px solid rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            padding: 12px;
            margin-bottom: 10px;
            cursor: grab;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .part-item:hover {
            border-color: rgba(0, 255, 136, 0.5);
            transform: translateX(5px);
            box-shadow: 0 5px 15px rgba(0, 255, 136, 0.2);
        }

        .part-item:active {
            cursor: grabbing;
        }

        .part-item.installed {
            opacity: 0.3;
            cursor: not-allowed;
            border-color: rgba(0, 255, 136, 0.2);
        }

        .part-icon {
            width: 42px;
            height: 42px;
            background: linear-gradient(135deg, rgba(0, 255, 136, 0.2) 0%, rgba(0, 204, 106, 0.1) 100%);
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.4em;
            border: 1px solid rgba(0, 255, 136, 0.3);
            flex-shrink: 0;
        }

        .part-info {
            flex: 1;
            min-width: 0;
        }

        .part-name {
            font-size: 0.85em;
            font-weight: bold;
            margin-bottom: 3px;
        }

        .part-desc {
            font-size: 0.65em;
            color: rgba(255, 255, 255, 0.6);
        }

        /* Center - Assembly Area with Realistic Tractor */
        .assembly-area {
            flex: 1;
            position: relative;
            background: 
                radial-gradient(circle at 50% 60%, rgba(196, 30, 58, 0.08) 0%, transparent 50%),
                radial-gradient(circle at 30% 40%, rgba(0, 255, 136, 0.05) 0%, transparent 50%);
            overflow: hidden;
        }

        .assembly-title {
            position: absolute;
            top: 15px;
            left: 50%;
            transform: translateX(-50%);
            font-size: 1.1em;
            color: rgba(255, 255, 255, 0.7);
            text-transform: uppercase;
            letter-spacing: 2px;
            z-index: 10;
        }

        /* Realistic Tractor Container */
        .tractor-container {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 650px;
            height: 400px;
        }

        /* Realistic Tractor SVG Base */
        .tractor-base-svg {
            width: 100%;
            height: 100%;
            filter: drop-shadow(0 10px 30px rgba(0,0,0,0.5));
        }

        /* Overlay Parts (appear when installed) */
        .overlay-part {
            position: absolute;
            transition: all 0.8s cubic-bezier(0.4, 0, 0.2, 1);
            opacity: 0;
            transform: scale(0.8);
            filter: brightness(0.3);
            cursor: pointer;
        }

        .overlay-part.installed {
            opacity: 1;
            transform: scale(1);
            filter: brightness(1);
        }

        /* Engine Overlay */
        .overlay-engine {
            bottom: 140px;
            left: 50%;
            transform: translateX(-50%) scale(0.8);
            width: 140px;
            height: 80px;
        }

        .overlay-engine.installed {
            transform: translateX(-50%) scale(1);
        }

        /* Cabin Overlay */
        .overlay-cabin {
            bottom: 220px;
            left: 50%;
            transform: translateX(-50%) scale(0.8);
            width: 150px;
            height: 95px;
        }

        .overlay-cabin.installed {
            transform: translateX(-50%) scale(1);
        }

        /* Hood Overlay */
        .overlay-hood {
            bottom: 150px;
            left: 55%;
            transform: scale(0.8);
            width: 120px;
            height: 65px;
        }

        .overlay-hood.installed {
            transform: scale(1);
        }

        /* Exhaust Overlay */
        .overlay-exhaust {
            bottom: 215px;
            left: 58%;
            transform: scale(0.8);
            width: 25px;
            height: 70px;
        }

        .overlay-exhaust.installed {
            transform: scale(1);
        }

        /* Wheel Overlays */
        .overlay-wheel {
            border-radius: 50%;
        }

        .overlay-wheel-fl {
            bottom: 55px;
            left: 18%;
            width: 85px;
            height: 85px;
            transform: scale(0.8);
        }

        .overlay-wheel-fr {
            bottom: 55px;
            right: 18%;
            width: 85px;
            height: 85px;
            transform: scale(0.8);
        }

        .overlay-wheel-rl {
            bottom: 60px;
            left: 28%;
            width: 120px;
            height: 120px;
            transform: scale(0.8);
        }

        .overlay-wheel-rr {
            bottom: 60px;
            right: 28%;
            width: 120px;
            height: 120px;
            transform: scale(0.8);
        }

        .overlay-wheel.installed {
            transform: scale(1);
        }

        /* Hitch Overlay */
        .overlay-hitch {
            bottom: 100px;
            right: 12%;
            transform: scale(0.8);
            width: 80px;
            height: 55px;
        }

        .overlay-hitch.installed {
            transform: scale(1);
        }

        /* Drop Zones (invisible until drag) */
        .drop-zone {
            position: absolute;
            border: 2px dashed rgba(0, 255, 136, 0);
            border-radius: 10px;
            background: rgba(0, 255, 136, 0);
            transition: all 0.3s ease;
            cursor: pointer;
        }

        .drop-zone.drag-over {
            border-color: rgba(0, 255, 136, 0.8);
            background: rgba(0, 255, 136, 0.15);
            transform: scale(1.05);
        }

        .drop-zone.correct {
            border-color: rgba(0, 255, 136, 0.8);
            background: rgba(0, 255, 136, 0.25);
            animation: successGlow 0.6s ease;
        }

        .drop-zone.wrong {
            border-color: rgba(255, 68, 68, 0.8);
            background: rgba(255, 68, 68, 0.2);
            animation: shake 0.5s ease;
        }

        @keyframes successGlow {
            0%, 100% { box-shadow: 0 0 20px rgba(0, 255, 136, 0.4); }
            50% { box-shadow: 0 0 50px rgba(0, 255, 136, 0.8); }
        }

        @keyframes shake {
            0%, 100% { transform: translateX(0); }
            25% { transform: translateX(-8px); }
            75% { transform: translateX(8px); }
        }

        /* Drop Zone Positions */
        #drop-engine { bottom: 140px; left: 50%; transform: translateX(-50%); width: 150px; height: 90px; }
        #drop-cabin { bottom: 220px; left: 50%; transform: translateX(-50%); width: 160px; height: 105px; }
        #drop-wheel-fl { bottom: 55px; left: 18%; width: 95px; height: 95px; border-radius: 50%; }
        #drop-wheel-fr { bottom: 55px; right: 18%; width: 95px; height: 95px; border-radius: 50%; }
        #drop-wheel-rl { bottom: 60px; left: 28%; width: 130px; height: 130px; border-radius: 50%; }
        #drop-wheel-rr { bottom: 60px; right: 28%; width: 130px; height: 130px; border-radius: 50%; }
        #drop-hitch { bottom: 100px; right: 12%; width: 90px; height: 65px; }

        /* Status Lights */
        .status-lights {
            position: absolute;
            top: 15px;
            right: 15px;
            display: flex;
            flex-direction: column;
            gap: 8px;
        }

        .status-light-item {
            display: flex;
            align-items: center;
            gap: 8px;
            padding: 6px 12px;
            background: rgba(0, 0, 0, 0.4);
            border-radius: 15px;
            font-size: 0.75em;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .status-dot {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            background: #2a2a2a;
            box-shadow: inset 0 1px 3px rgba(0,0,0,0.5);
            transition: all 0.3s ease;
        }

        .status-dot.on {
            background: #00ff88;
            box-shadow: 0 0 12px #00ff88, inset 0 1px 3px rgba(255,255,255,0.5);
            animation: blink 1.5s infinite;
        }

        @keyframes blink {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.6; }
        }

        /* Right Panel - Info */
        .info-panel {
            width: 300px;
            background: rgba(15, 20, 30, 0.98);
            padding: 15px;
            overflow-y: auto;
            border-left: 1px solid rgba(0, 170, 255, 0.2);
        }

        .info-card {
            background: linear-gradient(135deg, rgba(30, 40, 55, 0.95) 0%, rgba(20, 30, 45, 0.95) 100%);
            border: 2px solid rgba(0, 170, 255, 0.3);
            border-radius: 12px;
            padding: 15px;
            margin-bottom: 15px;
            display: none;
            animation: slideIn 0.5s ease;
        }

        .info-card.show {
            display: block;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateX(20px); }
            to { opacity: 1; transform: translateX(0); }
        }

        .info-header {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 12px;
            padding-bottom: 10px;
            border-bottom: 2px solid rgba(0, 170, 255, 0.2);
        }

        .info-icon {
            font-size: 1.8em;
        }

        .info-title {
            font-size: 0.95em;
            color: #00aaff;
            font-weight: bold;
        }

        .info-section {
            margin-bottom: 10px;
        }

        .info-section h3 {
            font-size: 0.7em;
            color: #00ff88;
            margin-bottom: 5px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .info-section p, .info-section li {
            font-size: 0.85em;
            line-height: 1.5;
            color: rgba(255, 255, 255, 0.85);
        }

        .info-section ul {
            list-style: none;
            padding-left: 0;
        }

        .info-section li {
            padding: 4px 0;
            padding-left: 18px;
            position: relative;
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
        }

        .info-section li:last-child {
            border-bottom: none;
        }

        .info-section li::before {
            content: '▸';
            position: absolute;
            left: 0;
            color: #00aaff;
        }

        .fact-box {
            background: rgba(255, 170, 0, 0.12);
            border-left: 3px solid #ffaa00;
            padding: 10px;
            border-radius: 6px;
            margin-top: 12px;
        }

        .fact-box strong {
            color: #ffaa00;
            display: block;
            margin-bottom: 5px;
            font-size: 0.75em;
            text-transform: uppercase;
        }

        .hint-box {
            background: rgba(255, 68, 68, 0.12);
            border-left: 3px solid #ff4444;
            padding: 10px;
            border-radius: 6px;
            margin-top: 12px;
            display: none;
        }

        .hint-box.show {
            display: block;
        }

        .hint-box strong {
            color: #ff4444;
            display: block;
            margin-bottom: 5px;
            font-size: 0.75em;
            text-transform: uppercase;
        }

        .info-default {
            display: block;
            text-align: center;
            padding: 40px 20px;
            color: rgba(255,255,255,0.5);
        }

        .info-default-icon {
            font-size: 3em;
            margin-bottom: 15px;
        }

        /* Start Screen */
        .start-screen {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(135deg, #0f1419 0%, #1a1f2e 50%, #0f1419 100%);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            z-index: 1000;
            gap: 25px;
        }

        .start-logo {
            font-size: 5em;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
        }

        .start-title {
            font-size: 2.2em;
            text-align: center;
            background: linear-gradient(135deg, #00ff88 0%, #00aaff 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .start-rules {
            background: rgba(255, 255, 255, 0.05);
            padding: 25px;
            border-radius: 12px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            max-width: 500px;
        }

        .start-rules h3 {
            color: #00ff88;
            margin-bottom: 12px;
            text-align: center;
        }

        .start-rules li {
            padding: 8px 0;
            padding-left: 28px;
            position: relative;
            list-style: none;
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
        }

        .start-rules li:last-child {
            border-bottom: none;
        }

        .start-rules li::before {
            content: '✓';
            position: absolute;
            left: 0;
            color: #00ff88;
        }

        .start-btn {
            background: linear-gradient(135deg, #00ff88 0%, #00cc6a 100%);
            color: #000;
            border: none;
            padding: 16px 45px;
            font-size: 1.1em;
            font-weight: bold;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 10px 35px rgba(0, 255, 136, 0.3);
        }

        .start-btn:hover {
            transform: translateY(-4px);
            box-shadow: 0 15px 45px rgba(0, 255, 136, 0.5);
        }

        .flag-belarus {
            margin: 15px 0;
        }

        .flag-belarus svg {
            height: 50px;
            border-radius: 6px;
        }

        /* Completion Screen */
        .completion-screen {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(0, 0, 0, 0.95);
            display: none;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            z-index: 1000;
            gap: 25px;
        }

        .completion-screen.show {
            display: flex;
        }

        .completion-icon {
            font-size: 5em;
            animation: bounce 1s infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
        }

        .completion-title {
            font-size: 2.2em;
            color: #00ff88;
        }

        .stat-box {
            background: rgba(255, 255, 255, 0.05);
            padding: 18px;
            border-radius: 10px;
            text-align: center;
            border: 1px solid rgba(0, 255, 136, 0.3);
        }

        .stat-value {
            font-size: 1.7em;
            font-weight: bold;
            color: #00ff88;
        }

        .stat-label {
            font-size: 0.8em;
            color: rgba(255, 255, 255, 0.6);
        }

        .tooltip {
            position: fixed;
            background: rgba(0, 0, 0, 0.95);
            padding: 10px 15px;
            border-radius: 8px;
            font-size: 0.85em;
            pointer-events: none;
            z-index: 1000;
            border: 1px solid rgba(0, 255, 136, 0.3);
            display: none;
        }

        .tooltip.show {
            display: block;
        }

        .confetti {
            position: fixed;
            width: 8px;
            height: 8px;
            background: #00ff88;
            animation: confetti-fall 3s linear infinite;
            z-index: 999;
        }

        @keyframes confetti-fall {
            to { transform: translateY(100vh) rotate(720deg); }
        }

        .ground {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            height: 70px;
            background: linear-gradient(180deg, rgba(30, 40, 55, 0.8) 0%, rgba(15, 20, 30, 0.95) 100%);
        }
    </style>
</head>
<body>
    <!-- Start Screen -->
    <div class="start-screen" id="startScreen">
        <div class="start-logo">🚜</div>
        <h1 class="start-title">MTZ BELARUS<br>Реалистичная сборка</h1>
        <div class="flag-belarus">
            <svg viewBox="0 0 900 600" width="130" height="87">
                <rect fill="#D22730" width="900" height="600"/>
                <rect fill="#0F943E" y="400" width="900" height="200"/>
            </svg>
        </div>
        <div class="start-rules">
            <h3>📋 Инструкция</h3>
            <li>Перетащите детали на реалистичный трактор</li>
            <li>7 компонентов за 4 минуты</li>
            <li>Зелёная лампочка = правильно</li>
            <li>Подсказки только в панели информации</li>
            <li>Все факты проверены (МТЗ, ММЗ)</li>
        </div>
        <button class="start-btn" onclick="startGame()">▶️ Начать сборку</button>
    </div>

    <!-- Completion Screen -->
    <div class="completion-screen" id="completionScreen">
        <div class="completion-icon">🏆</div>
        <h1 class="completion-title">Трактор BELARUS-82 собран!</h1>
        <div style="display: flex; gap: 15px;">
            <div class="stat-box">
                <div class="stat-value" id="finalTime">00:00</div>
                <div class="stat-label">Время</div>
            </div>
            <div class="stat-box">
                <div class="stat-value">7</div>
                <div class="stat-label">Деталей</div>
            </div>
        </div>
        <button class="start-btn" onclick="location.reload()">🔄 Заново</button>
    </div>

    <!-- Header -->
    <div class="header">
        <div class="logo">🏭 MTZ ASSEMBLY</div>
        <div class="timer-section">
            <div class="timer" id="timer">04:00</div>
            <div class="progress-info">
                <div class="progress-label">Установлено</div>
                <div class="progress-value"><span id="installedCount">0</span>/7</div>
            </div>
        </div>
    </div>

    <!-- Main -->
    <div class="main">
        <!-- Parts Panel -->
        <div class="parts-panel">
            <div class="panel-title">🔧 Компоненты</div>
            
            <div class="part-item" draggable="true" data-id="engine">
                <div class="part-icon">⚙️</div>
                <div class="part-info">
                    <div class="part-name">Двигатель Д-243</div>
                    <div class="part-desc">81 л.с., дизель</div>
                </div>
            </div>

            <div class="part-item" draggable="true" data-id="cabin">
                <div class="part-icon">🏠</div>
                <div class="part-info">
                    <div class="part-name">Кабина</div>
                    <div class="part-desc">ROPS/FOPS</div>
                </div>
            </div>

            <div class="part-item" draggable="true" data-id="wheel-fl">
                <div class="part-icon">🎯</div>
                <div class="part-info">
                    <div class="part-name">Колесо переднее Л</div>
                    <div class="part-desc">11.2-20"</div>
                </div>
            </div>

            <div class="part-item" draggable="true" data-id="wheel-fr">
                <div class="part-icon">🎯</div>
                <div class="part-info">
                    <div class="part-name">Колесо переднее П</div>
                    <div class="part-desc">11.2-20"</div>
                </div>
            </div>

            <div class="part-item" draggable="true" data-id="wheel-rl">
                <div class="part-icon">🎯</div>
                <div class="part-info">
                    <div class="part-name">Колесо заднее Л</div>
                    <div class="part-desc">18.4-34"</div>
                </div>
            </div>

            <div class="part-item" draggable="true" data-id="wheel-rr">
                <div class="part-icon">🎯</div>
                <div class="part-info">
                    <div class="part-name">Колесо заднее П</div>
                    <div class="part-desc">18.4-34"</div>
                </div>
            </div>

            <div class="part-item" draggable="true" data-id="hitch">
                <div class="part-icon">🔗</div>
                <div class="part-info">
                    <div class="part-name">Навеска</div>
                    <div class="part-desc">3-точечная</div>
                </div>
            </div>
        </div>

        <!-- Assembly Area -->
        <div class="assembly-area">
            <div class="assembly-title">📐 Реалистичная модель BELARUS-82</div>
            
            <div class="tractor-container">
                <!-- Realistic Tractor SVG Base -->
                <svg class="tractor-base-svg" viewBox="0 0 650 400">
                    <!-- Ground shadow -->
                    <ellipse cx="325" cy="365" rx="280" ry="25" fill="rgba(0,0,0,0.4)"/>
                    
                    <!-- Rear Wheel Left (base) -->
                    <ellipse cx="240" cy="340" rx="58" ry="58" fill="#1a1a1a" stroke="#2a2a2a" stroke-width="3"/>
                    <ellipse cx="240" cy="340" rx="25" ry="25" fill="#3a3a3a" stroke="#5a5a5a" stroke-width="2"/>
                    <circle cx="240" cy="340" r="10" fill="#2a2a2a"/>
                    
                    <!-- Rear Wheel Right (base) -->
                    <ellipse cx="410" cy="340" rx="58" ry="58" fill="#1a1a1a" stroke="#2a2a2a" stroke-width="3"/>
                    <ellipse cx="410" cy="340" rx="25" ry="25" fill="#3a3a3a" stroke="#5a5a5a" stroke-width="2"/>
                    <circle cx="410" cy="340" r="10" fill="#2a2a2a"/>
                    
                    <!-- Front Wheel Left (base) -->
                    <ellipse cx="165" cy="340" rx="40" ry="40" fill="#1a1a1a" stroke="#2a2a2a" stroke-width="3"/>
                    <ellipse cx="165" cy="340" rx="18" ry="18" fill="#3a3a3a" stroke="#5a5a5a" stroke-width="2"/>
                    <circle cx="165" cy="340" r="8" fill="#2a2a2a"/>
                    
                    <!-- Front Wheel Right (base) -->
                    <ellipse cx="485" cy="340" rx="40" ry="40" fill="#1a1a1a" stroke="#2a2a2a" stroke-width="3"/>
                    <ellipse cx="485" cy="340" rx="18" ry="18" fill="#3a3a3a" stroke="#5a5a5a" stroke-width="2"/>
                    <circle cx="485" cy="340" r="8" fill="#2a2a2a"/>
                    
                    <!-- Main Chassis -->
                    <path d="M 140 300 L 510 300 L 520 280 L 520 260 L 480 260 L 470 280 L 180 280 L 170 260 L 130 260 L 130 280 L 140 300" 
                          fill="url(#chassisGradient)" stroke="#3a3a4e" stroke-width="2"/>
                    
                    <!-- Engine block (base) -->
                    <rect x="280" y="260" width="120" height="50" rx="5" fill="url(#engineGradient)"/>
                    
                    <!-- Transmission -->
                    <rect x="200" y="270" width="90" height="40" rx="3" fill="#3a3a4e"/>
                    
                    <!-- Axle connection -->
                    <rect x="220" y="310" width="210" height="15" rx="3" fill="#4a4a5e"/>
                    
                    <!-- Hitch base -->
                    <rect x="520" y="285" width="50" height="25" rx="3" fill="#5a5a6e"/>
                    <rect x="540" y="310" width="10" height="20" fill="#5a5a6e"/>
                    
                    <!-- Gradients -->
                    <defs>
                        <linearGradient id="chassisGradient" x1="0%" y1="0%" x2="0%" y2="100%">
                            <stop offset="0%" style="stop-color:#3a3a4e"/>
                            <stop offset="50%" style="stop-color:#2a2a3e"/>
                            <stop offset="100%" style="stop-color:#1a1a2e"/>
                        </linearGradient>
                        <linearGradient id="engineGradient" x1="0%" y1="0%" x2="0%" y2="100%">
                            <stop offset="0%" style="stop-color:#5a5a6e"/>
                            <stop offset="100%" style="stop-color:#4a4a5e"/>
                        </linearGradient>
                    </defs>
                </svg>

                <!-- Overlay Parts (appear when installed) -->
                
                <!-- Engine Overlay -->
                <div class="overlay-part overlay-engine" id="visual-engine">
                    <svg viewBox="0 0 140 80" width="100%" height="100%">
                        <rect x="5" y="10" width="130" height="60" rx="8" fill="url(#engineOVGradient)" stroke="#6a6a7e" stroke-width="2"/>
                        <rect x="15" y="15" width="18" height="25" rx="3" fill="#6a6a7e" stroke="#7a7a8e"/>
                        <rect x="38" y="15" width="18" height="25" rx="3" fill="#6a6a7e" stroke="#7a7a8e"/>
                        <rect x="61" y="15" width="18" height="25" rx="3" fill="#6a6a7e" stroke="#7a7a8e"/>
                        <rect x="84" y="15" width="18" height="25" rx="3" fill="#6a6a7e" stroke="#7a7a8e"/>
                        <rect x="110" y="25" width="20" height="30" rx="3" fill="#5a5a6e"/>
                        <defs>
                            <linearGradient id="engineOVGradient" x1="0%" y1="0%" x2="0%" y2="100%">
                                <stop offset="0%" style="stop-color:#5a5a6e"/>
                                <stop offset="100%" style="stop-color:#4a4a5e"/>
                            </linearGradient>
                        </defs>
                    </svg>
                </div>

                <!-- Cabin Overlay -->
                <div class="overlay-part overlay-cabin" id="visual-cabin">
                    <svg viewBox="0 0 150 95" width="100%" height="100%">
                        <rect x="10" y="20" width="130" height="70" rx="8" fill="url(#cabinGradient)" stroke="#E43E5A" stroke-width="2"/>
                        <rect x="15" y="25" width="120" height="45" rx="5" fill="url(#windowGradient)" stroke="rgba(255,255,255,0.3)" stroke-width="2"/>
                        <rect x="5" y="5" width="140" height="18" rx="8" fill="#E43E5A"/>
                        <rect x="20" y="55" width="40" height="30" rx="3" fill="#2a2a3e" opacity="0.5"/>
                        <defs>
                            <linearGradient id="cabinGradient" x1="0%" y1="0%" x2="0%" y2="100%">
                                <stop offset="0%" style="stop-color:#D42E4A"/>
                                <stop offset="100%" style="stop-color:#8B0000"/>
                            </linearGradient>
                            <linearGradient id="windowGradient" x1="0%" y1="0%" x2="100%" y2="100%">
                                <stop offset="0%" style="stop-color:rgba(150,220,255,0.6)"/>
                                <stop offset="100%" style="stop-color:rgba(100,180,255,0.4)"/>
                            </linearGradient>
                        </defs>
                    </svg>
                </div>

                <!-- Hood Overlay -->
                <div class="overlay-part overlay-hood" id="visual-hood">
                    <svg viewBox="0 0 120 65" width="100%" height="100%">
                        <path d="M 5 10 L 115 10 L 115 55 L 5 55 Z" fill="url(#hoodGradient)" stroke="#E43E5A" stroke-width="2" rx="8"/>
                        <rect x="20" y="20" width="70" height="25" rx="5" fill="rgba(0,0,0,0.3)" stroke="rgba(255,255,255,0.2)" stroke-width="1"/>
                        <line x1="25" y1="28" x2="85" y2="28" stroke="rgba(255,255,255,0.15)" stroke-width="1"/>
                        <line x1="25" y1="36" x2="85" y2="36" stroke="rgba(255,255,255,0.15)" stroke-width="1"/>
                        <defs>
                            <linearGradient id="hoodGradient" x1="0%" y1="0%" x2="0%" y2="100%">
                                <stop offset="0%" style="stop-color:#D42E4A"/>
                                <stop offset="100%" style="stop-color:#8B0000"/>
                            </linearGradient>
                        </defs>
                    </svg>
                </div>

                <!-- Exhaust Overlay -->
                <div class="overlay-part overlay-exhaust" id="visual-exhaust">
                    <svg viewBox="0 0 25 70" width="100%" height="100%">
                        <rect x="5" y="10" width="15" height="60" rx="3" fill="url(#exhaustGradient)" stroke="#7a7a8e" stroke-width="2"/>
                        <ellipse cx="12.5" cy="8" rx="10" ry="6" fill="#5a5a6e" stroke="#6a6a7e" stroke-width="2"/>
                        <defs>
                            <linearGradient id="exhaustGradient" x1="0%" y1="0%" x2="0%" y2="100%">
                                <stop offset="0%" style="stop-color:#6a6a7e"/>
                                <stop offset="100%" style="stop-color:#4a4a5e"/>
                            </linearGradient>
                        </defs>
                    </svg>
                </div>

                <!-- Wheel Overlays -->
                <div class="overlay-part overlay-wheel overlay-wheel-fl" id="visual-wheel-fl">
                    <svg viewBox="0 0 85 85" width="100%" height="100%">
                        <circle cx="42.5" cy="42.5" r="40" fill="url(#tireGradient)" stroke="#3a3a3a" stroke-width="3"/>
                        <circle cx="42.5" cy="42.5" r="20" fill="url(#rimGradient)" stroke="#8a8a9e" stroke-width="2"/>
                        <circle cx="42.5" cy="42.5" r="8" fill="#4a4a5e" stroke="#5a5a6e" stroke-width="2"/>
                        <circle cx="42.5" cy="25" r="3" fill="#6a6a7e"/>
                        <circle cx="42.5" cy="60" r="3" fill="#6a6a7e"/>
                        <circle cx="25" cy="42.5" r="3" fill="#6a6a7e"/>
                        <circle cx="60" cy="42.5" r="3" fill="#6a6a7e"/>
                        <defs>
                            <radialGradient id="tireGradient">
                                <stop offset="0%" style="stop-color:#2a2a2a"/>
                                <stop offset="100%" style="stop-color:#0a0a0a"/>
                            </radialGradient>
                            <radialGradient id="rimGradient">
                                <stop offset="0%" style="stop-color:#7a7a8e"/>
                                <stop offset="100%" style="stop-color:#5a5a6e"/>
                            </radialGradient>
                        </defs>
                    </svg>
                </div>

                <div class="overlay-part overlay-wheel overlay-wheel-fr" id="visual-wheel-fr">
                    <svg viewBox="0 0 85 85" width="100%" height="100%">
                        <circle cx="42.5" cy="42.5" r="40" fill="url(#tireGradient2)" stroke="#3a3a3a" stroke-width="3"/>
                        <circle cx="42.5" cy="42.5" r="20" fill="url(#rimGradient2)" stroke="#8a8a9e" stroke-width="2"/>
                        <circle cx="42.5" cy="42.5" r="8" fill="#4a4a5e" stroke="#5a5a6e" stroke-width="2"/>
                        <circle cx="42.5" cy="25" r="3" fill="#6a6a7e"/>
                        <circle cx="42.5" cy="60" r="3" fill="#6a6a7e"/>
                        <circle cx="25" cy="42.5" r="3" fill="#6a6a7e"/>
                        <circle cx="60" cy="42.5" r="3" fill="#6a6a7e"/>
                        <defs>
                            <radialGradient id="tireGradient2">
                                <stop offset="0%" style="stop-color:#2a2a2a"/>
                                <stop offset="100%" style="stop-color:#0a0a0a"/>
                            </radialGradient>
                            <radialGradient id="rimGradient2">
                                <stop offset="0%" style="stop-color:#7a7a8e"/>
                                <stop offset="100%" style="stop-color:#5a5a6e"/>
                            </radialGradient>
                        </defs>
                    </svg>
                </div>

                <div class="overlay-part overlay-wheel overlay-wheel-rl" id="visual-wheel-rl">
                    <svg viewBox="0 0 120 120" width="100%" height="100%">
                        <circle cx="60" cy="60" r="58" fill="url(#tireGradient3)" stroke="#3a3a3a" stroke-width="4"/>
                        <circle cx="60" cy="60" r="28" fill="url(#rimGradient3)" stroke="#8a8a9e" stroke-width="3"/>
                        <circle cx="60" cy="60" r="10" fill="#4a4a5e" stroke="#5a5a6e" stroke-width="2"/>
                        <circle cx="60" cy="35" r="4" fill="#6a6a7e"/>
                        <circle cx="60" cy="85" r="4" fill="#6a6a7e"/>
                        <circle cx="35" cy="60" r="4" fill="#6a6a7e"/>
                        <circle cx="85" cy="60" r="4" fill="#6a6a7e"/>
                        <defs>
                            <radialGradient id="tireGradient3">
                                <stop offset="0%" style="stop-color:#2a2a2a"/>
                                <stop offset="100%" style="stop-color:#0a0a0a"/>
                            </radialGradient>
                            <radialGradient id="rimGradient3">
                                <stop offset="0%" style="stop-color:#7a7a8e"/>
                                <stop offset="100%" style="stop-color:#5a5a6e"/>
                            </radialGradient>
                        </defs>
                    </svg>
                </div>

                <div class="overlay-part overlay-wheel overlay-wheel-rr" id="visual-wheel-rr">
                    <svg viewBox="0 0 120 120" width="100%" height="100%">
                        <circle cx="60" cy="60" r="58" fill="url(#tireGradient4)" stroke="#3a3a3a" stroke-width="4"/>
                        <circle cx="60" cy="60" r="28" fill="url(#rimGradient4)" stroke="#8a8a9e" stroke-width="3"/>
                        <circle cx="60" cy="60" r="10" fill="#4a4a5e" stroke="#5a5a6e" stroke-width="2"/>
                        <circle cx="60" cy="35" r="4" fill="#6a6a7e"/>
                        <circle cx="60" cy="85" r="4" fill="#6a6a7e"/>
                        <circle cx="35" cy="60" r="4" fill="#6a6a7e"/>
                        <circle cx="85" cy="60" r="4" fill="#6a6a7e"/>
                        <defs>
                            <radialGradient id="tireGradient4">
                                <stop offset="0%" style="stop-color:#2a2a2a"/>
                                <stop offset="100%" style="stop-color:#0a0a0a"/>
                            </radialGradient>
                            <radialGradient id="rimGradient4">
                                <stop offset="0%" style="stop-color:#7a7a8e"/>
                                <stop offset="100%" style="stop-color:#5a5a6e"/>
                            </radialGradient>
                        </defs>
                    </svg>
                </div>

                <!-- Hitch Overlay -->
                <div class="overlay-part overlay-hitch" id="visual-hitch">
                    <svg viewBox="0 0 80 55" width="100%" height="100%">
                        <rect x="5" y="5" width="70" height="40" rx="5" fill="url(#hitchGradient)" stroke="#8a8a9e" stroke-width="2"/>
                        <rect x="35" y="45" width="10" height="10" fill="#6a6a7e"/>
                        <circle cx="40" cy="40" r="5" fill="#5a5a6e" stroke="#6a6a7e"/>
                        <defs>
                            <linearGradient id="hitchGradient" x1="0%" y1="0%" x2="0%" y2="100%">
                                <stop offset="0%" style="stop-color:#7a7a8e"/>
                                <stop offset="100%" style="stop-color:#5a5a6e"/>
                            </linearGradient>
                        </defs>
                    </svg>
                </div>

                <!-- Drop Zones -->
                <div class="drop-zone" id="drop-engine" data-accepts="engine"></div>
                <div class="drop-zone" id="drop-cabin" data-accepts="cabin"></div>
                <div class="drop-zone" id="drop-wheel-fl" data-accepts="wheel-fl"></div>
                <div class="drop-zone" id="drop-wheel-fr" data-accepts="wheel-fr"></div>
                <div class="drop-zone" id="drop-wheel-rl" data-accepts="wheel-rl"></div>
                <div class="drop-zone" id="drop-wheel-rr" data-accepts="wheel-rr"></div>
                <div class="drop-zone" id="drop-hitch" data-accepts="hitch"></div>
            </div>

            <!-- Status Lights -->
            <div class="status-lights">
                <div class="status-light-item">
                    <div class="status-dot" id="light-engine"></div>
                    <span>Двигатель</span>
                </div>
                <div class="status-light-item">
                    <div class="status-dot" id="light-cabin"></div>
                    <span>Кабина</span>
                </div>
                <div class="status-light-item">
                    <div class="status-dot" id="light-wheels"></div>
                    <span>Колёса</span>
                </div>
                <div class="status-light-item">
                    <div class="status-dot" id="light-hitch"></div>
                    <span>Навеска</span>
                </div>
            </div>

            <div class="ground"></div>
        </div>

        <!-- Info Panel -->
        <div class="info-panel">
            <div class="panel-title">📖 Информация</div>

            <div class="info-card" id="info-engine">
                <div class="info-header">
                    <div class="info-icon">⚙️</div>
                    <div class="info-title">Двигатель Д-243</div>
                </div>
                <div class="info-section">
                    <h3>🏭 Производство</h3>
                    <p>ОАО "Минский моторный завод" (ММЗ), Беларусь</p>
                </div>
                <div class="info-section">
                    <h3>📊 Характеристики</h3>
                    <ul>
                        <li>Мощность: 81 л.с. при 2200 об/мин</li>
                        <li>Объём: 4,75 литра</li>
                        <li>4 цилиндра, дизельный</li>
                        <li>Расход: 226 г/кВт·ч</li>
                    </ul>
                </div>
                <div class="fact-box">
                    <strong>💡 Факт</strong>
                    <p>Производится с 1975 года. Ресурс до капремонта: 10 000 моточасов. Экспорт в 60+ стран.</p>
                </div>
                <div class="hint-box" id="hint-engine">
                    <strong>⚠️ Подсказка</strong>
                    <p>В передней части трактора, под капотом</p>
                </div>
            </div>

            <div class="info-card" id="info-cabin">
                <div class="info-header">
                    <div class="info-icon">🏠</div>
                    <div class="info-title">Кабина оператора</div>
                </div>
                <div class="info-section">
                    <h3>🏭 Производство</h3>
                    <p>ОАО "МТЗ", г. Минск, Беларусь</p>
                </div>
                <div class="info-section">
                    <h3>📊 Характеристики</h3>
                    <ul>
                        <li>Защита: ROPS/FOPS (OECD)</li>
                        <li>Шум: ≤75 дБ</li>
                        <li>Обзор: 360°</li>
                    </ul>
                </div>
                <div class="fact-box">
                    <strong>💡 Факт</strong>
                    <p>Сертификация OECD Code 4. С 2000 года все BELARUS оснащаются кабинами ROPS/FOPS.</p>
                </div>
                <div class="hint-box" id="hint-cabin">
                    <strong>⚠️ Подсказка</strong>
                    <p>В центральной части, над трансмиссией</p>
                </div>
            </div>

            <div class="info-card" id="info-wheel">
                <div class="info-header">
                    <div class="info-icon">🎯</div>
                    <div class="info-title">Колёса</div>
                </div>
                <div class="info-section">
                    <h3>🏭 Производство</h3>
                    <p>ОАО "Белшина", г. Бобруйск</p>
                </div>
                <div class="info-section">
                    <h3>📊 Характеристики</h3>
                    <ul>
                        <li>Передние: 11.2-20"</li>
                        <li>Задние: 18.4-34"</li>
                        <li>Протектор: "ёлочка"</li>
                    </ul>
                </div>
                <div class="fact-box">
                    <strong>💡 Факт</strong>
                    <p>"Белшина" основано в 1965. Экспорт в 80+ стран. Задние колёса принимают 75% веса.</p>
                </div>
                <div class="hint-box" id="hint-wheel">
                    <strong>⚠️ Подсказка</strong>
                    <p>Задние больше передних. Передние — спереди, задние — сзади</p>
                </div>
            </div>

            <div class="info-card" id="info-hitch">
                <div class="info-header">
                    <div class="info-icon">🔗</div>
                    <div class="info-title">Навеска</div>
                </div>
                <div class="info-section">
                    <h3>🏭 Производство</h3>
                    <p>ОАО "МТЗ", г. Минск</p>
                </div>
                <div class="info-section">
                    <h3>📊 Характеристики</h3>
                    <ul>
                        <li>Тип: 3-точечная, кат. II</li>
                        <li>Стандарт: ISO 730</li>
                        <li>Груз: 2000 кг</li>
                    </ul>
                </div>
                <div class="fact-box">
                    <strong>💡 Факт</strong>
                    <p>Совместима с оборудованием 100+ производителей. Стандарт ISO 730 универсален.</p>
                </div>
                <div class="hint-box" id="hint-hitch">
                    <strong>⚠️ Подсказка</strong>
                    <p>В задней части трактора</p>
                </div>
            </div>

            <div class="info-default" id="info-default">
                <div class="info-default-icon">📋</div>
                <p>Перетащите деталь на трактор</p>
            </div>
        </div>
    </div>

    <div class="tooltip" id="tooltip"></div>

    <script>
        var gameTime = 240;
        var timerInterval;
        var installedParts = [];
        var draggedElement = null;
        var wheelsInstalled = 0;

        var components = {
            engine: { zone: 'drop-engine', light: 'light-engine', hint: 'hint-engine', visual: 'visual-engine', info: 'info-engine' },
            cabin: { zone: 'drop-cabin', light: 'light-cabin', hint: 'hint-cabin', visual: 'visual-cabin', info: 'info-cabin' },
            'wheel-fl': { zone: 'drop-wheel-fl', light: 'light-wheels', hint: 'hint-wheel', visual: 'visual-wheel-fl', info: 'info-wheel' },
            'wheel-fr': { zone: 'drop-wheel-fr', light: 'light-wheels', hint: 'hint-wheel', visual: 'visual-wheel-fr', info: 'info-wheel' },
            'wheel-rl': { zone: 'drop-wheel-rl', light: 'light-wheels', hint: 'hint-wheel', visual: 'visual-wheel-rl', info: 'info-wheel' },
            'wheel-rr': { zone: 'drop-wheel-rr', light: 'light-wheels', hint: 'hint-wheel', visual: 'visual-wheel-rr', info: 'info-wheel' },
            hitch: { zone: 'drop-hitch', light: 'light-hitch', hint: 'hint-hitch', visual: 'visual-hitch', info: 'info-hitch' }
        };

        function startGame() {
            document.getElementById('startScreen').style.display = 'none';
            startTimer();
            initDragAndDrop();
        }

        function startTimer() {
            timerInterval = setInterval(function() {
                gameTime--;
                var minutes = Math.floor(gameTime / 60);
                var seconds = gameTime % 60;
                var timerEl = document.getElementById('timer');
                timerEl.textContent = (minutes < 10 ? '0' : '') + minutes + ':' + (seconds < 10 ? '0' : '') + seconds;

                if (gameTime <= 60) { timerEl.classList.add('warning'); timerEl.classList.remove('danger'); }
                if (gameTime <= 30) { timerEl.classList.remove('warning'); timerEl.classList.add('danger'); }
                if (gameTime <= 0) { clearInterval(timerInterval); alert('Время вышло!'); location.reload(); }
            }, 1000);
        }

        function initDragAndDrop() {
            var items = document.querySelectorAll('.part-item');
            for (var i = 0; i < items.length; i++) {
                items[i].addEventListener('dragstart', handleDragStart);
                items[i].addEventListener('dragend', handleDragEnd);
            }
            var zones = document.querySelectorAll('.drop-zone');
            for (var j = 0; j < zones.length; j++) {
                zones[j].addEventListener('dragover', handleDragOver);
                zones[j].addEventListener('dragleave', handleDragLeave);
                zones[j].addEventListener('drop', handleDrop);
            }
        }

        function handleDragStart(e) {
            draggedElement = this;
            this.classList.add('dragging');
            e.dataTransfer.effectAllowed = 'move';
            e.dataTransfer.setData('text/plain', this.getAttribute('data-id'));
        }

        function handleDragEnd() { this.classList.remove('dragging'); draggedElement = null; }
        function handleDragOver(e) { e.preventDefault(); e.dataTransfer.dropEffect = 'move'; this.classList.add('drag-over'); return false; }
        function handleDragLeave() { this.classList.remove('drag-over'); }

        function handleDrop(e) {
            e.stopPropagation();
            this.classList.remove('drag-over');
            if (draggedElement) {
                var partId = draggedElement.getAttribute('data-id');
                var zoneId = this.id;
                var component = components[partId];
                if (component && component.zone === zoneId) { handleCorrectPlacement(partId, component); }
                else { handleWrongPlacement(partId, component); }
            }
            return false;
        }

        function handleCorrectPlacement(partId, component) {
            if (installedParts.indexOf(partId) === -1) {
                installedParts.push(partId);
                if (partId.indexOf('wheel') >= 0) {
                    wheelsInstalled++;
                    if (wheelsInstalled === 4) document.getElementById('installedCount').textContent = installedParts.length;
                } else { document.getElementById('installedCount').textContent = installedParts.length; }

                var zone = document.getElementById(component.zone);
                zone.classList.add('correct');
                setTimeout(function() { zone.classList.remove('correct'); }, 600);

                document.getElementById(component.light).classList.add('on');
                document.getElementById(component.visual).classList.add('installed');
                draggedElement.classList.add('installed');
                draggedElement.draggable = false;

                document.getElementById('info-default').style.display = 'none';
                var cards = document.querySelectorAll('.info-card');
                for (var i = 0; i < cards.length; i++) cards[i].classList.remove('show');
                document.getElementById(component.info).classList.add('show');

                var hint = document.getElementById(component.hint);
                if (hint) hint.classList.remove('show');

                if (installedParts.length === 7) setTimeout(showCompletion, 1500);
            }
        }

        function handleWrongPlacement(partId, component) {
            var zone = document.getElementById(component.zone);
            zone.classList.add('wrong');
            setTimeout(function() { zone.classList.remove('wrong'); }, 500);

            var hint = document.getElementById(component.hint);
            if (hint) {
                hint.classList.add('show');
                setTimeout(function() { hint.classList.remove('show'); }, 5000);
            }
            showTooltip('❌ Неверно! Смотрите подсказку справа.', event.clientX, event.clientY);
        }

        function showTooltip(text, x, y) {
            var tooltip = document.getElementById('tooltip');
            tooltip.textContent = text;
            tooltip.style.left = (x - 150) + 'px';
            tooltip.style.top = (y - 50) + 'px';
            tooltip.classList.add('show');
            setTimeout(function() { tooltip.classList.remove('show'); }, 2500);
        }

        function showCompletion() {
            clearInterval(timerInterval);
            createConfetti();
            var minutes = Math.floor((240 - gameTime) / 60);
            var seconds = (240 - gameTime) % 60;
            document.getElementById('finalTime').textContent = (minutes < 10 ? '0' : '') + minutes + ':' + (seconds < 10 ? '0' : '') + seconds;
            setTimeout(function() { document.getElementById('completionScreen').classList.add('show'); }, 1000);
        }

        function createConfetti() {
            var colors = ['#00ff88', '#00cc6a', '#ffaa00', '#00aaff', '#ffffff', '#C41E3A'];
            for (var i = 0; i < 120; i++) {
                var confetti = document.createElement('div');
                confetti.className = 'confetti';
                confetti.style.left = Math.random() * 100 + 'vw';
                confetti.style.background = colors[Math.floor(Math.random() * colors.length)];
                confetti.style.animationDelay = Math.random() * 2 + 's';
                confetti.style.animationDuration = (Math.random() * 2 + 3) + 's';
                document.body.appendChild(confetti);
                (function(c) { setTimeout(function() { if (c && c.parentNode) c.remove(); }, 6000); })(confetti);
            }
        }

        document.addEventListener('dragover', function(e) { e.preventDefault(); });
        document.addEventListener('drop', function(e) { e.preventDefault(); });
    </script>
</body>
</html>
