<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>💖 Muh. Rifa & Nabila — 1 Tahun 💖</title>
    <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg1: #fff7f9;
            --bg2: #fffaf6;
            --accent: #ff7fbf;
            --accent-light: #ffb6d9;
            --accent-dark: #ff4fa7;
            --gold: #cfa04a;
            --gold-light: #e6c887;
            --text: #42303a;
            --text-light: #7c576c;
            --glass: rgba(255,255,255,0.85);
            --glass-dark: rgba(255,255,255,0.92);
        }
        
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        
        html, body {
            min-height: 100%;
            font-family: 'Poppins', sans-serif;
            color: var(--text);
            line-height: 1.6;
            overflow-x: hidden;
        }
        
        body {
            background: 
                linear-gradient(135deg, rgba(255,247,249,0.9) 0%, rgba(255,250,246,0.9) 100%),
                url('https://open-rose-yw8we31cr3.edgeone.app/photoboxx.jpg') center/cover fixed no-repeat;
            padding: 15px;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            position: relative;
        }
        
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                radial-gradient(circle at 20% 80%, rgba(255,182,217,0.15) 0%, transparent 50%),
                radial-gradient(circle at 80% 20%, rgba(255,127,191,0.1) 0%, transparent 50%),
                radial-gradient(circle at 40% 40%, rgba(255,247,249,0.2) 0%, transparent 50%),
                linear-gradient(45deg, rgba(255,247,249,0.3) 0%, rgba(255,250,246,0.3) 100%);
            z-index: -1;
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            background: linear-gradient(135deg, 
                rgba(255,255,255,0.95) 0%, 
                rgba(255,247,249,0.98) 50%, 
                rgba(255,255,255,0.95) 100%);
            border-radius: 25px;
            padding: clamp(20px, 5vw, 35px);
            box-shadow: 
                0 25px 80px rgba(255,127,191,0.2),
                0 15px 40px rgba(255,127,191,0.1),
                inset 0 1px 0 rgba(255,255,255,0.8);
            position: relative;
            overflow: hidden;
            margin: 20px 0;
            border: 1px solid rgba(255,255,255,0.6);
            backdrop-filter: blur(10px);
        }
        
        .container::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 4px;
            background: linear-gradient(90deg, 
                var(--accent-light), 
                var(--accent), 
                var(--gold), 
                var(--accent));
            border-radius: 25px 25px 0 0;
        }
        
        .stars {
            position: absolute;
            inset: 0;
            pointer-events: none;
            mix-blend-mode: screen;
            opacity: 0.4;
            background: 
                radial-gradient(circle at 15% 25%, rgba(255,255,255,0.9) 1px, transparent 2px),
                radial-gradient(circle at 65% 15%, rgba(255,255,255,0.7) 1px, transparent 2px),
                radial-gradient(circle at 25% 75%, rgba(255,255,255,0.8) 1px, transparent 2px),
                radial-gradient(circle at 85% 65%, rgba(255,255,255,0.6) 1px, transparent 2px),
                radial-gradient(circle at 45% 35%, rgba(255,255,255,0.5) 1px, transparent 2px);
            animation: twinkle 8s ease-in-out infinite;
        }
        
        @keyframes twinkle {
            0%, 100% { opacity: 0.3; }
            50% { opacity: 0.7; }
        }
        
        .floating-hearts {
            position: absolute;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }
        
        .floating-heart {
            position: absolute;
            color: rgba(255,127,191,0.3);
            font-size: 20px;
            animation: float 15s linear infinite;
        }
        
        @keyframes float {
            0% {
                transform: translateY(100vh) rotate(0deg);
                opacity: 0;
            }
            10% {
                opacity: 0.7;
            }
            90% {
                opacity: 0.7;
            }
            100% {
                transform: translateY(-100px) rotate(360deg);
                opacity: 0;
            }
        }
        
        header {
            display: flex;
            flex-direction: column;
            gap: 20px;
            margin-bottom: 30px;
            text-align: center;
            position: relative;
            z-index: 2;
        }
        
        @media (min-width: 768px) {
            header {
                flex-direction: row;
                justify-content: space-between;
                align-items: flex-start;
                text-align: left;
            }
            
            .header-right {
                text-align: right;
            }
        }
        
        h1 {
            font-family: 'Great Vibes', cursive;
            font-size: clamp(3rem, 10vw, 4.5rem);
            color: var(--accent);
            text-shadow: 
                0 4px 20px rgba(255,127,191,0.3),
                0 2px 8px rgba(255,255,255,0.8);
            margin-bottom: 8px;
            line-height: 1.1;
            background: linear-gradient(135deg, var(--accent-dark), var(--accent), var(--gold));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .sub {
            color: var(--text-light);
            font-weight: 600;
            font-size: clamp(16px, 4vw, 18px);
            margin-bottom: 5px;
        }
        
        .date {
            color: #a9859c;
            font-size: clamp(13px, 3vw, 15px);
            margin-bottom: 12px;
            font-weight: 500;
        }
        
        .controls {
            display: flex;
            gap: 12px;
            justify-content: center;
            flex-wrap: wrap;
        }
        
        @media (min-width: 768px) {
            .controls {
                justify-content: flex-end;
            }
        }
        
        .btn {
            background: linear-gradient(135deg, var(--accent), var(--accent-dark));
            color: white;
            border: none;
            padding: clamp(10px, 2vw, 12px) clamp(15px, 3vw, 20px);
            border-radius: 15px;
            cursor: pointer;
            font-weight: 700;
            font-size: clamp(13px, 3vw, 15px);
            box-shadow: 
                0 8px 25px rgba(255,127,191,0.3),
                inset 0 1px 0 rgba(255,255,255,0.3);
            transition: all 0.3s ease;
            flex: 1;
            min-width: 130px;
            max-width: 160px;
            position: relative;
            overflow: hidden;
        }
        
        .btn::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            transition: left 0.5s ease;
        }
        
        .btn:hover::before {
            left: 100%;
        }
        
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 
                0 15px 35px rgba(255,127,191,0.4),
                inset 0 1px 0 rgba(255,255,255,0.3);
        }
        
        .btn.gold {
            background: linear-gradient(135deg, var(--gold), var(--gold-light));
            color: #4a2f10;
            box-shadow: 
                0 8px 25px rgba(207,160,74,0.3),
                inset 0 1px 0 rgba(255,255,255,0.3);
        }
        
        main {
            display: flex;
            flex-direction: column;
            gap: 25px;
            position: relative;
            z-index: 2;
        }
        
        @media (min-width: 1024px) {
            main {
                display: grid;
                grid-template-columns: 1fr 380px;
                gap: 30px;
                align-items: start;
            }
        }
        
        .card {
            background: linear-gradient(135deg, var(--glass-dark), var(--glass));
            border-radius: 20px;
            padding: clamp(20px, 4vw, 25px);
            box-shadow: 
                0 15px 40px rgba(0,0,0,0.08),
                0 8px 20px rgba(255,127,191,0.1),
                inset 0 1px 0 rgba(255,255,255,0.8);
            margin-bottom: 25px;
            border: 1px solid rgba(255,255,255,0.6);
            position: relative;
            overflow: hidden;
        }
        
        .card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            background: linear-gradient(90deg, 
                transparent, 
                var(--accent-light), 
                var(--accent), 
                var(--accent-light), 
                transparent);
        }
        
        .time-header {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-bottom: 20px;
        }
        
        @media (min-width: 480px) {
            .time-header {
                flex-direction: row;
                justify-content: space-between;
                align-items: center;
            }
        }
        
        .time-title {
            font-weight: 700;
            font-size: clamp(18px, 4vw, 20px);
            color: #6d4454;
            background: linear-gradient(135deg, #6d4454, #8a5c72);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .time-subtitle {
            color: #9b6e84;
            font-size: clamp(13px, 3vw, 15px);
            font-weight: 500;
        }
        
        .anniversary-badge {
            text-align: center;
            background: linear-gradient(135deg, rgba(255,255,255,0.9), rgba(255,247,249,0.9));
            padding: 12px 20px;
            border-radius: 15px;
            box-shadow: 0 5px 20px rgba(255,127,191,0.15);
            border: 1px solid rgba(255,255,255,0.8);
        }
        
        @media (min-width: 480px) {
            .anniversary-badge {
                text-align: right;
            }
        }
        
        .anniversary-text {
            font-weight: 800;
            color: var(--gold);
            font-size: clamp(20px, 5vw, 22px);
            margin-bottom: 5px;
        }
        
        .anniversary-date {
            font-size: clamp(12px, 3vw, 14px);
            color: #9b6e84;
            font-weight: 500;
        }
        
        .timer {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
            margin: 25px 0;
        }
        
        @media (min-width: 480px) {
            .timer {
                display: flex;
                gap: 15px;
                flex-wrap: wrap;
                justify-content: center;
            }
        }
        
        .time-box {
            text-align: center;
            padding: clamp(12px, 3vw, 15px) clamp(10px, 2vw, 12px);
            border-radius: 15px;
            background: linear-gradient(135deg, #fff, #fff7fb);
            box-shadow: 
                0 8px 25px rgba(255,127,191,0.12),
                inset 0 1px 0 rgba(255,255,255,0.8);
            border: 1px solid rgba(255,127,191,0.15);
            min-width: 80px;
            position: relative;
            overflow: hidden;
        }
        
        @media (min-width: 480px) {
            .time-box {
                min-width: 100px;
            }
        }
        
        .time-box::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 2px;
            background: linear-gradient(90deg, var(--accent-light), var(--accent), var(--accent-light));
        }
        
        .time-box .num {
            font-weight: 800;
            color: var(--accent);
            font-size: clamp(18px, 4vw, 22px);
            text-shadow: 0 2px 4px rgba(255,127,191,0.2);
        }
        
        .time-box .lbl {
            font-size: clamp(11px, 2.5vw, 13px);
            color: #8a6b7f;
            margin-top: 6px;
            font-weight: 600;
        }
        
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
            gap: 12px;
            margin: 25px 0;
        }
        
        @media (min-width: 480px) {
            .gallery {
                grid-template-columns: repeat(3, 1fr);
                gap: 15px;
            }
        }
        
        .gallery img {
            width: 100%;
            height: clamp(120px, 30vw, 140px);
            object-fit: cover;
            border-radius: 15px;
            cursor: pointer;
            transition: all 0.4s ease;
            border: 2px solid transparent;
            box-shadow: 
                0 8px 25px rgba(0,0,0,0.1),
                0 4px 12px rgba(255,127,191,0.2);
            filter: brightness(0.95);
        }
        
        .gallery img:hover {
            transform: translateY(-5px) scale(1.03);
            box-shadow: 
                0 15px 40px rgba(0,0,0,0.15),
                0 8px 25px rgba(255,127,191,0.3);
            border-color: var(--accent);
            filter: brightness(1.05);
        }
        
        .message {
            padding: clamp(20px, 4vw, 25px);
            border-radius: 15px;
            background: linear-gradient(135deg, #fff, #fff7fb);
            box-shadow: 
                0 12px 35px rgba(255,127,191,0.12),
                inset 0 1px 0 rgba(255,255,255,0.8);
            line-height: 1.7;
            border: 1px solid rgba(255,255,255,0.6);
        }
        
        .message strong {
            display: block;
            margin-bottom: 15px;
            font-size: clamp(18px, 4vw, 20px);
            color: var(--accent);
            background: linear-gradient(135deg, var(--accent-dark), var(--accent));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .message p {
            margin: 15px 0;
            color: #4b2f3e;
            font-size: clamp(14px, 3.5vw, 16px);
            line-height: 1.8;
        }
        
        .card-aside {
            padding: clamp(20px, 4vw, 25px);
            border-radius: 20px;
            background: linear-gradient(135deg, var(--glass-dark), var(--glass));
            box-shadow: 
                0 15px 40px rgba(0,0,0,0.08),
                0 8px 20px rgba(255,127,191,0.1),
                inset 0 1px 0 rgba(255,255,255,0.8);
            border: 1px solid rgba(255,255,255,0.6);
            position: relative;
            overflow: hidden;
        }
        
        .card-aside::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            background: linear-gradient(90deg, 
                transparent, 
                var(--gold-light), 
                var(--gold), 
                var(--gold-light), 
                transparent);
        }
        
        .label {
            font-weight: 700;
            color: #7b4f66;
            margin-bottom: 15px;
            font-size: clamp(18px, 4vw, 20px);
            background: linear-gradient(135deg, #7b4f66, #9b6e84);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .surprise-btn {
            display: block;
            width: 100%;
            padding: clamp(15px, 3vw, 18px);
            border-radius: 15px;
            border: 2px solid var(--accent);
            background: transparent;
            color: var(--accent);
            font-weight: 700;
            cursor: pointer;
            transition: all 0.4s ease;
            font-size: clamp(15px, 3.5vw, 17px);
            margin-bottom: 20px;
            position: relative;
            overflow: hidden;
            box-shadow: 0 5px 20px rgba(255,127,191,0.2);
        }
        
        .surprise-btn::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,127,191,0.1), transparent);
            transition: left 0.6s ease;
        }
        
        .surprise-btn:hover::before {
            left: 100%;
        }
        
        .surprise-btn:hover {
            background: linear-gradient(135deg, var(--accent), var(--accent-dark));
            color: white;
            box-shadow: 
                0 10px 30px rgba(255,127,191,0.4),
                0 5px 15px rgba(255,127,191,0.3);
            transform: translateY(-2px);
        }
        
        .hidden-letter {
            padding: clamp(20px, 4vw, 25px);
            border-radius: 15px;
            background: linear-gradient(135deg, #fff, #fff7fb);
            box-shadow: 
                0 10px 30px rgba(255,127,191,0.15),
                inset 0 1px 0 rgba(255,255,255,0.8);
            font-style: italic;
            opacity: 0;
            transform: translateY(25px);
            transition: all 1s cubic-bezier(0.2,0.9,0.28,1);
            line-height: 1.8;
            color: #4b2f3e;
            margin-top: 20px;
            font-size: clamp(14px, 3.5vw, 16px);
            border: 1px solid rgba(255,255,255,0.6);
            position: relative;
            overflow: hidden;
        }
        
        .hidden-letter::before {
            content: '💌';
            position: absolute;
            top: 10px;
            right: 15px;
            font-size: 24px;
            opacity: 0.3;
        }
        
        .hidden-letter.show {
            opacity: 1;
            transform: translateY(0);
        }
        
        .instructions {
            font-size: clamp(13px, 3vw, 15px);
            color: #7a5a6c;
            line-height: 1.7;
        }
        
        footer {
            margin-top: 30px;
            text-align: center;
            color: #8a697b;
            font-size: clamp(13px, 3vw, 15px);
            padding-top: 20px;
            border-top: 1px solid rgba(255,127,191,0.2);
            position: relative;
            z-index: 2;
        }
        
        .audio-player {
            width: 100%;
            margin: 20px 0;
            padding: clamp(15px, 3vw, 20px);
            border-radius: 15px;
            background: linear-gradient(135deg, #fff, #fff7fb);
            box-shadow: 
                0 10px 30px rgba(0,0,0,0.1),
                0 5px 15px rgba(255,127,191,0.2),
                inset 0 1px 0 rgba(255,255,255,0.8);
            border: 1px solid rgba(255,255,255,0.6);
            position: relative;
        }
        
        .audio-player::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 2px;
            background: linear-gradient(90deg, var(--accent-light), var(--accent), var(--accent-light));
        }
        
        .audio-controls {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }
        
        @media (min-width: 480px) {
            .audio-controls {
                flex-direction: row;
                align-items: center;
                gap: 15px;
            }
        }
        
        .audio-btn {
            background: linear-gradient(135deg, var(--accent), var(--accent-dark));
            color: white;
            border: none;
            width: 45px;
            height: 45px;
            border-radius: 50%;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 18px;
            transition: all 0.3s ease;
            flex-shrink: 0;
            box-shadow: 0 5px 15px rgba(255,127,191,0.3);
        }
        
        .audio-btn:hover {
            transform: scale(1.1);
            box-shadow: 0 8px 20px rgba(255,127,191,0.4);
        }
        
        .song-info {
            flex: 1;
            text-align: center;
        }
        
        @media (min-width: 480px) {
            .song-info {
                text-align: left;
            }
        }
        
        .song-title {
            font-weight: 700;
            color: #7b4f66;
            font-size: clamp(14px, 3vw, 16px);
            margin-bottom: 3px;
        }
        
        .song-artist {
            color: #9b6e84;
            font-size: clamp(12px, 2.5vw, 14px);
            font-weight: 500;
        }
        
        .progress-container {
            width: 100%;
            height: 8px;
            background: #ffeef7;
            border-radius: 4px;
            overflow: hidden;
            cursor: pointer;
            margin: 12px 0;
            box-shadow: inset 0 1px 3px rgba(0,0,0,0.1);
        }
        
        .progress-bar {
            height: 100%;
            background: linear-gradient(90deg, var(--accent), var(--gold));
            border-radius: 4px;
            width: 0%;
            transition: width 0.1s ease;
            box-shadow: 0 0 10px rgba(255,127,191,0.3);
        }
        
        .time-display {
            display: flex;
            justify-content: space-between;
            font-size: clamp(11px, 2.5vw, 13px);
            color: #8a6b7f;
            margin-top: 8px;
            font-weight: 500;
        }
        
        .volume-control {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-top: 12px;
        }
        
        .volume-slider {
            flex: 1;
            height: 6px;
            background: #ffeef7;
            border-radius: 3px;
            outline: none;
            -webkit-appearance: none;
            box-shadow: inset 0 1px 3px rgba(0,0,0,0.1);
        }
        
        .volume-slider::-webkit-slider-thumb {
            -webkit-appearance: none;
            width: 16px;
            height: 16px;
            border-radius: 50%;
            background: var(--accent);
            cursor: pointer;
            box-shadow: 0 2px 8px rgba(255,127,191,0.4);
            border: 2px solid white;
        }
        
        .heart {
            position: fixed;
            color: rgba(255,127,191,0.8);
            font-size: clamp(16px, 4vw, 20px);
            pointer-events: none;
            opacity: 0.9;
            z-index: 50;
            transition: transform 6s linear, opacity 2s linear;
            text-shadow: 0 0 10px rgba(255,255,255,0.5);
        }
        
        .music-notification {
            position: fixed;
            bottom: 25px;
            left: 50%;
            transform: translateX(-50%);
            background: linear-gradient(135deg, rgba(255,255,255,0.95), rgba(255,247,249,0.95));
            padding: 12px 25px;
            border-radius: 25px;
            box-shadow: 
                0 8px 30px rgba(0,0,0,0.15),
                0 4px 15px rgba(255,127,191,0.2);
            z-index: 100;
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: clamp(14px, 3vw, 16px);
            color: var(--text);
            animation: fadeInOut 5s ease-in-out;
            backdrop-filter: blur(10px);
            max-width: 90%;
            text-align: center;
            border: 1px solid rgba(255,255,255,0.6);
        }
        
        @keyframes fadeInOut {
            0% { opacity: 0; transform: translateX(-50%) translateY(20px); }
            20% { opacity: 1; transform: translateX(-50%) translateY(0); }
            80% { opacity: 1; transform: translateX(-50%) translateY(0); }
            100% { opacity: 0; transform: translateX(-50%) translateY(-20px); }
        }
        
        .fullscreen-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.95);
            display: none;
            justify-content: center;
            align-items: center;
            z-index: 1000;
            padding: 20px;
        }
        
        .fullscreen-img {
            max-width: 100%;
            max-height: 100%;
            border-radius: 15px;
            box-shadow: 
                0 25px 80px rgba(0,0,0,0.5),
                0 15px 40px rgba(255,127,191,0.3);
            object-fit: contain;
        }
        
        .close-btn {
            position: absolute;
            top: 20px;
            right: 20px;
            background: linear-gradient(135deg, var(--accent), var(--accent-dark));
            color: white;
            border: none;
            width: 45px;
            height: 45px;
            border-radius: 50%;
            font-size: 20px;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            z-index: 1001;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
            transition: all 0.3s ease;
        }
        
        .close-btn:hover {
            transform: scale(1.1);
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            body {
                padding: 10px;
            }
            
            .container {
                padding: 20px;
                border-radius: 20px;
            }
            
            .btn {
                min-width: 120px;
                padding: 12px 15px;
            }
            
            .time-box {
                padding: 12px 10px;
            }
            
            .gallery img {
                height: 120px;
            }
            
            .audio-btn {
                width: 48px;
                height: 48px;
            }
        }
        
        @media (max-width: 480px) {
            .timer {
                grid-template-columns: repeat(2, 1fr);
            }
            
            .gallery {
                grid-template-columns: repeat(2, 1fr);
            }
            
            .gallery img:nth-child(3) {
                grid-column: 1 / -1;
                height: 140px;
            }
        }
        
        @media (max-width: 360px) {
            .timer {
                grid-template-columns: 1fr;
            }
            
            .gallery {
                grid-template-columns: 1fr;
            }
            
            .gallery img {
                height: 140px;
            }
            
            .controls {
                flex-direction: column;
            }
            
            .btn {
                max-width: none;
            }
        }
        
        @media (max-height: 500px) and (orientation: landscape) {
            body {
                align-items: flex-start;
                padding: 10px;
            }
            
            .container {
                margin: 10px 0;
            }
            
            .gallery img {
                height: 100px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="stars" aria-hidden="true"></div>
        <div class="floating-hearts" id="floatingHearts"></div>
        
        <header>
            <div class="header-left">
                <h1>Hari Jadi Kita</h1>
                <div class="sub">Muh. Rifa Abdil Manaf & Nabila Emly Mamesah</div>
                <div class="date">Sejak 30 Oktober 2024 — Selamat 1 Tahun</div>
            </div>
            
            <div class="header-right">
                <div style="font-weight:700;color:#7a4a66;margin-bottom:10px;font-size:clamp(14px,3vw,16px);">Selamat 1 Tahun 💖</div>
                <div class="controls">
                    <button class="btn gold" id="savePage">Save HTML</button>
                    <button class="btn" id="printBtn">Print</button>
                </div>
            </div>
        </header>
        
        <main>
            <section class="left">
                <div class="card">
                    <div class="time-header">
                        <div>
                            <div class="time-title">Sudah bersama selama</div>
                            <div class="time-subtitle">Setiap detik perjalanan kita berharga</div>
                        </div>
                        <div class="anniversary-badge">
                            <div class="anniversary-text">1 Tahun</div>
                            <div class="anniversary-date">30 Okt 2024 — sekarang</div>
                        </div>
                    </div>
                    
                    <div class="timer">
                        <div class="time-box">
                            <div class="num" id="years">0</div>
                            <div class="lbl">tahun</div>
                        </div>
                        <div class="time-box">
                            <div class="num" id="months">0</div>
                            <div class="lbl">bulan</div>
                        </div>
                        <div class="time-box">
                            <div class="num" id="days">0</div>
                            <div class="lbl">hari</div>
                        </div>
                        <div class="time-box">
                            <div class="num" id="hours">0</div>
                            <div class="lbl">jam</div>
                        </div>
                        <div class="time-box">
                            <div class="num" id="minutes">0</div>
                            <div class="lbl">menit</div>
                        </div>
                        <div class="time-box">
                            <div class="num" id="seconds">0</div>
                            <div class="lbl">detik</div>
                        </div>
                    </div>
                    
                    <div class="gallery" id="gallery">
                        <img src="https://spectacular-tomato-2oyqx6b3c1.edgeone.app/pth1%20(2).jpg" 
                             alt="Kenangan indah kita 1" 
                             onclick="openFullscreen(this.src)">
                        <img src="https://yearling-blue-kvcbjzs2xj.edgeone.app/pth1%20(3).jpg" 
                             alt="Kenangan indah kita 2" 
                             onclick="openFullscreen(this.src)">
                        <img src="https://minimum-green-vmf5d3wyqv.edgeone.app/WhatsApp%20Image%202025-10-26%20at%2020.56.31_a4d82a5d.jpg" 
                             alt="Kenangan indah kita 3" 
                             onclick="openFullscreen(this.src)">
                    </div>
                    
                    <div class="message">
                        <strong>Untuk Nabila tersayang 💐</strong>
                        <p>
                            Terima kasih untuk 1 tahun yang tidak mudah ini. Banyak hal yang kita berdua hadapi, banyak pertengkaran yang membuat kita ragu bahkan sampai saling benci. Tapi semua itu tidak akan ada habisnya karena kita saling menyayangi, saling mendukung, saling melengkapi. Aku ingin kamu tetap sama denganku meski aku banyak salahnya dan banyak kurangnya. Aku ingin kita selalu bersama biar banyak yang tidak suka dan banyak yang membuat kita ragu akan masing-masing.
                        </p>
                        <p><strong>Terima kasih sudah ada buat aku selalu — <em>Muh. Rifa Abdil Manaf 🤍🫂</em></strong></p>
                    </div>
                </div>
            </section>
            
            <aside>
                <div class="card-aside">
                    <div class="label">Lagu Anniversary Kita</div>
                    <div class="audio-player">
                        <div class="audio-controls">
                            <button class="audio-btn" id="playPauseBtn">⏸️</button>
                            <div class="song-info">
                                <div class="song-title">Cinta Luar Biasa</div>
                                <div class="song-artist">Andmesh Kamaleng</div>
                            </div>
                        </div>
                        <div class="progress-container" id="progressContainer">
                            <div class="progress-bar" id="progressBar"></div>
                        </div>
                        <div class="time-display">
                            <span id="currentTime">0:00</span>
                            <span id="duration">0:00</span>
                        </div>
                        <div class="volume-control">
                            <span>🔊</span>
                            <input type="range" class="volume-slider" id="volumeSlider" min="0" max="1" step="0.1" value="0.7">
                        </div>
                    </div>
                    
                    <div class="label">Buka Surat Cinta</div>
                    <button class="surprise-btn" id="openLetterBtn">💌 Buka Hatiku</button>
                    
                    <div class="hidden-letter" id="hiddenLetter">
                        Selamat ulang tahun yang pertama untuk kita, sayangku. Satu tahun sudah kita lalui bersama dengan segala suka dan duka. Aku bersyukur bisa melewati semuanya bersamamu. Kamu adalah bagian terindah dalam hidupku, dan aku berjanji akan selalu berusaha menjadi yang terbaik untukmu.
                        
                        <div style="margin-top:15px;font-weight:700">— Muh. Rifa Abdil Manaf 🤍🫂</div>
                    </div>
                    
                    <div style="margin-top:20px" class="label">Kenangan Indah Kita</div>
                    <div class="instructions">
                        • Klik pada foto untuk melihat dalam ukuran penuh<br>
                        • Foto-foto spesial dari perjalanan 1 tahun kita<br>
                        • Musik akan diputar otomatis<br>
                        • Kontrol volume dan progress tersedia
                    </div>
                </div>
            </aside>
        </main>
        
        <footer>
            © 2024 Muh. Rifa & Nabila — Selamat 1 Tahun ❤️
        </footer>
    </div>

    <!-- Fullscreen Image Overlay -->
    <div class="fullscreen-overlay" id="fullscreenOverlay">
        <button class="close-btn" onclick="closeFullscreen()">✕</button>
        <img class="fullscreen-img" id="fullscreenImg" src="" alt="Foto kenangan">
    </div>

    <!-- Audio Element -->
    <audio id="mainAudio" loop>
        <source src="https://native-maroon-vhropojjdw.edgeone.app/Andmesh%20Kamaleng%20-%20Cinta%20Luar%20Biasa%20(Official%20Music%20Video)%20-%20HITS%20Records.mp3" type="audio/mpeg">
    </audio>
    
    <script>
        // Timer
        const start = new Date("2024-10-30T00:00:00");
        
        function updateTimer() {
            const now = new Date();
            const diff = now - start;
            
            const years = Math.floor(diff / (1000 * 60 * 60 * 24 * 365));
            const months = Math.floor((diff % (1000 * 60 * 60 * 24 * 365)) / (1000 * 60 * 60 * 24 * 30));
            const days = Math.floor((diff % (1000 * 60 * 60 * 24 * 30)) / (1000 * 60 * 60 * 24));
            const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((diff % (1000 * 60)) / 1000);
            
            document.getElementById('years').textContent = years;
            document.getElementById('months').textContent = months;
            document.getElementById('days').textContent = days;
            document.getElementById('hours').textContent = hours;
            document.getElementById('minutes').textContent = minutes;
            document.getElementById('seconds').textContent = seconds;
        }
        
        setInterval(updateTimer, 1000);
        updateTimer();
        
        // Floating hearts background
        function createFloatingHearts() {
            const container = document.getElementById('floatingHearts');
            for (let i = 0; i < 15; i++) {
                const heart = document.createElement('div');
                heart.className = 'floating-heart';
                heart.innerHTML = '❤';
                heart.style.left = Math.random() * 100 + '%';
                heart.style.animationDelay = Math.random() * 15 + 's';
                heart.style.fontSize = (Math.random() * 10 + 15) + 'px';
                container.appendChild(heart);
            }
        }
        
        createFloatingHearts();
        
        // Fullscreen image functionality
        function openFullscreen(src) {
            const overlay = document.getElementById('fullscreenOverlay');
            const img = document.getElementById('fullscreenImg');
            img.src = src;
            overlay.style.display = 'flex';
            document.body.style.overflow = 'hidden';
        }
        
        function closeFullscreen() {
            const overlay = document.getElementById('fullscreenOverlay');
            overlay.style.display = 'none';
            document.body.style.overflow = 'auto';
        }
        
        // Close overlay when clicking outside image
        document.getElementById('fullscreenOverlay').addEventListener('click', function(e) {
            if (e.target === this) {
                closeFullscreen();
            }
        });
        
        // Audio Player Functionality
        const audio = document.getElementById('mainAudio');
        const playPauseBtn = document.getElementById('playPauseBtn');
        const progressBar = document.getElementById('progressBar');
        const progressContainer = document.getElementById('progressContainer');
        const currentTimeEl = document.getElementById('currentTime');
        const durationEl = document.getElementById('duration');
        const volumeSlider = document.getElementById('volumeSlider');
        
        // Format time function
        function formatTime(seconds) {
            const mins = Math.floor(seconds / 60);
            const secs = Math.floor(seconds % 60);
            return `${mins}:${secs < 10 ? '0' : ''}${secs}`;
        }
        
        // Update progress bar
        function updateProgress() {
            const { duration, currentTime } = audio;
            if (duration) {
                const progressPercent = (currentTime / duration) * 100;
                progressBar.style.width = `${progressPercent}%`;
                currentTimeEl.textContent = formatTime(currentTime);
                durationEl.textContent = formatTime(duration);
            }
        }
        
        // Set progress
        function setProgress(e) {
            const width = this.clientWidth;
            const clickX = e.offsetX;
            const duration = audio.duration;
            audio.currentTime = (clickX / width) * duration;
        }
        
        // Play/Pause functionality
        function togglePlayPause() {
            if (audio.paused) {
                audio.play();
                playPauseBtn.textContent = '⏸️';
            } else {
                audio.pause();
                playPauseBtn.textContent = '▶️';
            }
        }
        
        // Volume control
        function setVolume() {
            audio.volume = volumeSlider.value;
        }
        
        // Event listeners for audio
        audio.addEventListener('timeupdate', updateProgress);
        audio.addEventListener('loadedmetadata', () => {
            durationEl.textContent = formatTime(audio.duration);
        });
        progressContainer.addEventListener('click', setProgress);
        playPauseBtn.addEventListener('click', togglePlayPause);
        volumeSlider.addEventListener('input', setVolume);
        
        // Auto-play with user interaction
        function tryAutoplay() {
            audio.volume = 0.7;
            const playPromise = audio.play();
            
            if (playPromise !== undefined) {
                playPromise.then(() => {
                    playPauseBtn.textContent = '⏸️';
                    showMusicNotification();
                }).catch(error => {
                    console.log('Autoplay prevented:', error);
                    playPauseBtn.textContent = '▶️';
                    
                    const notification = document.createElement('div');
                    notification.className = 'music-notification';
                    notification.innerHTML = 'Klik tombol play untuk memutar musik';
                    document.body.appendChild(notification);
                    
                    setTimeout(() => {
                        notification.remove();
                    }, 5000);
                });
            }
        }
        
        // Wait for page to load then try autoplay
        window.addEventListener('load', tryAutoplay);
        
        // Allow user gesture to enable audio
        function enableAudioAfterUserGesture() {
            if (audio && audio.paused) {
                audio.play().then(() => {
                    playPauseBtn.textContent = '⏸️';
                }).catch(() => {
                    // Ignore
                });
            }
            document.body.removeEventListener('click', enableAudioAfterUserGesture);
        }
        document.body.addEventListener('click', enableAudioAfterUserGesture);
        
        // Show music notification
        function showMusicNotification() {
            const notification = document.createElement('div');
            notification.className = 'music-notification';
            notification.innerHTML = '🎵 Lagu anniversary diputar otomatis';
            document.body.appendChild(notification);
            
            setTimeout(() => {
                notification.remove();
            }, 5000);
        }
        
        // Surprise Letter
        const openBtn = document.getElementById('openLetterBtn');
        const letter = document.getElementById('hiddenLetter');
        
        openBtn.addEventListener('click', () => {
            letter.classList.add('show');
            letter.setAttribute('aria-hidden', 'false');
            
            openBtn.disabled = true;
            openBtn.textContent = '💌 Terbuka';
        });
        
        // Save HTML button
        document.getElementById('savePage').addEventListener('click', () => {
            const doctype = '<!DOCTYPE html>\n';
            const html = document.documentElement.outerHTML;
            const blob = new Blob([doctype + html], { type: 'text/html' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = 'hari-jadi-muh-rifa-nabila.html';
            document.body.appendChild(a);
            a.click();
            a.remove();
            URL.revokeObjectURL(url);
        });
        
        // Print button
        document.getElementById('printBtn').addEventListener('click', () => window.print());
        
        // Floating hearts animation
        function spawnHeart() {
            const h = document.createElement('div');
            h.className = 'heart';
            h.textContent = '❤';
            h.style.left = (8 + Math.random() * 84) + '%';
            h.style.bottom = '-30px';
            h.style.fontSize = (12 + Math.random() * 18) + 'px';
            document.body.appendChild(h);
            
            requestAnimationFrame(() => {
                h.style.transform = 'translateY(-110vh) rotate(' + (Math.random() * 80 - 40) + 'deg)';
                h.style.opacity = 0;
            });
            
            setTimeout(() => h.remove(), 7000);
        }
        
        setInterval(spawnHeart, 700);
        
        // Touch device improvements
        document.addEventListener('touchstart', function() {}, {passive: true});
        
        // Prevent zoom on double tap
        let lastTouchEnd = 0;
        document.addEventListener('touchend', function (event) {
            const now = (new Date()).getTime();
            if (now - lastTouchEnd <= 300) {
                event.preventDefault();
            }
            lastTouchEnd = now;
        }, false);
    </script>
</body>
</html>
