<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Kalkulator Nilai Ujian</title>
    <style>
        :root {
            --primary-color: #16a34a;
            --primary-dark: #166534;
            --primary-soft: #dcfce7;
            --bg-color: #f3f7f5;
            --bg-accent: #e0f2fe;
            --card-color: rgba(255, 255, 255, 0.92);
            --text-color: #1f2937;
            --muted-color: #526074;
            --border-color: rgba(22, 163, 74, 0.14);
            --success-bg: #ecfdf5;
            --success-border: #bbf7d0;
            --success-dark: #166534;
            --shadow-soft: 0 18px 38px rgba(15, 23, 42, 0.12);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background:
                radial-gradient(circle at top left, rgba(34, 197, 94, 0.22), transparent 28%),
                radial-gradient(circle at bottom right, rgba(14, 165, 233, 0.20), transparent 32%),
                linear-gradient(180deg, #eafaf1 0%, #edf4ff 100%);
            color: var(--text-color);
            margin: 0;
            padding: 18px 12px 30px;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            min-height: 100vh;
        }

        .container {
            background: linear-gradient(180deg, rgba(255,255,255,0.96), rgba(247,250,252,0.9));
            padding: 12px 14px 18px;
            border-radius: 32px;
            box-shadow: 0 24px 40px rgba(15, 23, 42, 0.12);
            width: min(100%, 420px);
            border: 1px solid rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(10px);
        }

        .status-bar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 2px 6px 10px;
            font-size: 12px;
            font-weight: 700;
            color: #334155;
        }

        .status-icons {
            display: flex;
            align-items: center;
            gap: 6px;
            font-size: 12px;
        }

        .app-header {
            display: flex;
            align-items: center;
            gap: 14px;
            margin-bottom: 18px;
            padding: 10px 8px 16px;
            border-bottom: 1px solid rgba(148, 163, 184, 0.2);
        }

        .brand-badge {
            width: 52px;
            height: 52px;
            border-radius: 16px;
            display: grid;
            place-items: center;
            background: linear-gradient(135deg, var(--primary-color), #22c55e);
            box-shadow: 0 12px 22px rgba(22, 163, 74, 0.25);
            font-size: 26px;
        }

        .eyebrow {
            font-size: 11px;
            letter-spacing: 0.12em;
            text-transform: uppercase;
            color: var(--muted-color);
            margin-bottom: 4px;
            font-weight: 700;
        }

        h1 {
            text-align: left;
            color: var(--primary-dark);
            font-size: clamp(1.6rem, 3vw, 2.2rem);
            line-height: 1.2;
        }

        .section {
            margin-bottom: 18px;
            padding: 18px 16px 14px;
            border: 1px solid var(--border-color);
            border-radius: 18px;
            background: linear-gradient(180deg, rgba(255,255,255,0.75), rgba(248,250,252,0.86));
            box-shadow: inset 0 1px 0 rgba(255,255,255,0.9);
        }

        .section-title {
            display: flex;
            align-items: center;
            gap: 8px;
            font-weight: 800;
            margin-bottom: 15px;
            color: var(--primary-dark);
            background: var(--primary-soft);
            border-radius: 10px;
            padding: 8px 10px;
            font-size: 13px;
            letter-spacing: 0.02em;
        }

        .section-title::before {
            content: "✓";
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 20px;
            height: 20px;
            background: var(--primary-color);
            color: white;
            border-radius: 50%;
            font-size: 12px;
            font-weight: 700;
        }

        .form-group {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 12px;
            gap: 12px;
        }

        .form-group label {
            flex: 1;
            font-size: 14px;
            color: var(--muted-color);
            font-weight: 600;
        }

        .form-group input {
            flex: 0.62;
            padding: 11px 12px;
            border: 1.5px solid rgba(148, 163, 184, 0.45);
            border-radius: 12px;
            text-align: center;
            font-size: 14px;
            color: var(--text-color);
            background: rgba(255, 255, 255, 0.9);
            transition: border-color 0.2s ease, box-shadow 0.2s ease, transform 0.2s ease;
        }

        .form-group input:focus {
            outline: none;
            border-color: var(--primary-color);
            box-shadow: 0 0 0 4px rgba(34, 197, 94, 0.15);
            transform: translateY(-1px);
        }

        .form-hint {
            display: block;
            font-size: 12px;
            color: #64748b;
            margin: 8px 0 12px;
            font-style: italic;
        }

        .button-container {
            display: flex;
            gap: 12px;
            margin-top: 22px;
        }

        button {
            flex: 1;
            padding: 14px 16px;
            border: none;
            border-radius: 14px;
            font-size: 15px;
            font-weight: 800;
            cursor: pointer;
            transition: transform 0.2s ease, box-shadow 0.2s ease, filter 0.2s ease;
        }

        .btn-hitung {
            background: linear-gradient(135deg, var(--primary-color), #22c55e);
            color: white;
            box-shadow: 0 12px 24px rgba(22, 163, 74, 0.22);
        }

        .btn-hitung:hover {
            filter: brightness(1.05);
            transform: translateY(-1px);
        }

        .btn-hitung:active {
            transform: translateY(0) scale(0.99);
        }

        .btn-reset {
            background: linear-gradient(135deg, #64748b, #475569);
            color: white;
            box-shadow: 0 12px 24px rgba(71, 85, 105, 0.18);
        }

        .btn-reset:hover {
            filter: brightness(1.04);
            transform: translateY(-1px);
        }

        .error-message {
            display: none;
            color: #b91c1c;
            font-size: 13px;
            margin-top: 14px;
            font-weight: 700;
            background: #fef2f2;
            border: 1px solid #fecaca;
            border-radius: 12px;
            padding: 10px 12px;
        }

        .error-message.show {
            display: block;
        }

        .result-box {
            margin-top: 22px;
            text-align: center;
            padding: 20px 18px;
            background: linear-gradient(180deg, var(--success-bg), #f0fdf4);
            border: 1.5px solid var(--success-border);
            border-radius: 18px;
            display: none;
            animation: slideIn 0.25s ease-out;
            box-shadow: inset 0 1px 0 rgba(255,255,255,0.7);
        }

        .result-box.show {
            display: block;
        }

        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateY(-10px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .result-box h3 {
            margin: 0 0 12px 0;
            color: var(--success-dark);
            font-size: 15px;
            letter-spacing: 0.08em;
            text-transform: uppercase;
        }

        .final-score {
            font-size: clamp(2.2rem, 7vw, 3.2rem);
            font-weight: 800;
            color: var(--success-dark);
            margin: 10px 0;
            line-height: 1;
        }

        .details {
            font-size: 13px;
            color: #475569;
            margin-top: 12px;
            line-height: 1.7;
        }

        .score-breakdown {
            margin-top: 10px;
            padding-top: 10px;
            border-top: 1px solid rgba(22, 163, 74, 0.2);
            font-size: 12px;
            color: #334155;
        }

        @media (max-width: 480px) {
            .container {
                padding: 22px 18px 18px;
                border-radius: 20px;
            }

            .app-header {
                align-items: flex-start;
            }

            .form-group {
                flex-direction: column;
                align-items: flex-start;
            }

            .form-group input {
                width: 100%;
                flex: 1;
            }

            .button-container {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>

<div class="container">
    <div class="status-bar">
        <span>9:41</span>
        <div class="status-icons">◔◍◌</div>
    </div>

    <div class="app-header">
        <div class="brand-badge">📘</div>
        <div>
            <p class="eyebrow">Aplikasi Penilaian</p>
            <h1>Kalkulator Nilai Ujian</h1>
        </div>
    </div>

    <div class="section">
        <label class="section-title">1. Pilihan Ganda (PG)</label>
        <div class="form-group">
            <label for="pg-soal">Jumlah Soal PG:</label>
            <input type="number" id="pg-soal" value="28" min="0" step="1">
        </div>
        <div class="form-group">
            <label for="pg-benar">Jawaban Benar:</label>
            <input type="number" id="pg-benar" value="0" min="0" step="1">
        </div>
        <div class="form-group">
            <label for="pg-bobot">Bobot per Soal:</label>
            <input type="number" id="pg-bobot" value="1" min="0.1" step="0.1">
        </div>
    </div>

    <div class="section">
        <label class="section-title">2. Isian Singkat</label>
        <div class="form-group">
            <label for="isian-soal">Jumlah Soal Isian:</label>
            <input type="number" id="isian-soal" value="6" min="0" step="1">
        </div>
        <div class="form-group">
            <label for="isian-benar">Jawaban Benar:</label>
            <input type="number" id="isian-benar" value="0" min="0" step="1">
        </div>
        <div class="form-group">
            <label for="isian-bobot">Bobot per Soal:</label>
            <input type="number" id="isian-bobot" value="2" min="0.1" step="0.1">
        </div>
    </div>

    <div class="section">
        <label class="section-title">3. Essay / Uraian</label>
        <span class="form-hint">*Masukkan total skor akhir essay secara keseluruhan.</span>
        <div class="form-group">
            <label for="essay-max">Skor Maksimal Essay:</label>
            <input type="number" id="essay-max" value="18" min="0" step="0.1">
        </div>
        <div class="form-group">
            <label for="essay-perolehan">Skor Perolehan Siswa:</label>
            <input type="number" id="essay-perolehan" value="0" min="0" step="0.1">
        </div>
    </div>

    <div class="button-container">
        <button class="btn-hitung" onclick="hitungNilai()">Hitung Nilai Akhir</button>
        <button class="btn-reset" type="button" onclick="resetForm()">Reset</button>
    </div>

    <div class="error-message" id="error-message"></div>

    <div class="result-box" id="result-box">
        <h3>Nilai Akhir</h3>
        <p class="final-score" id="final-score">0</p>
        <div class="details">
            <div id="score-summary">Total Skor: 0 dari 0</div>
            <div class="score-breakdown" id="score-breakdown"></div>
        </div>
    </div>
</div>

<script>
    function showError(message) {
        const errorEl = document.getElementById('error-message');
        errorEl.textContent = message;
        errorEl.classList.add('show');
    }

    function hideError() {
        const errorEl = document.getElementById('error-message');
        errorEl.textContent = '';
        errorEl.classList.remove('show');
    }

    function validateInputs(pgSoal, pgBenar, isianSoal, isianBenar, essayMax, essayPerolehan) {
        if (
            pgSoal < 0 || pgBenar < 0 ||
            isianSoal < 0 || isianBenar < 0 ||
            essayMax < 0 || essayPerolehan < 0
        ) {
            showError('Semua nilai harus bernilai positif atau nol.');
            return false;
        }

        if (pgBenar > pgSoal) {
            showError('Jawaban benar PG tidak boleh lebih dari jumlah soal PG.');
            return false;
        }

        if (isianBenar > isianSoal) {
            showError('Jawaban benar isian tidak boleh lebih dari jumlah soal isian.');
            return false;
        }

        if (essayPerolehan > essayMax) {
            showError('Skor essay perolehan tidak boleh lebih dari skor maksimal essay.');
            return false;
        }

        if (pgSoal === 0 && isianSoal === 0 && essayMax === 0) {
            showError('Minimal ada satu kategori soal dengan nilai lebih dari 0.');
            return false;
        }

        hideError();
        return true;
    }

    function formatAngka(value) {
        if (Number.isInteger(value)) {
            return value.toString();
        }
        return value.toFixed(2).replace(/\.00$/, '').replace(/(\.\d)0$/, '$1');
    }

    function hitungNilai() {
        const pgSoal = parseFloat(document.getElementById('pg-soal').value) || 0;
        const pgBenar = parseFloat(document.getElementById('pg-benar').value) || 0;
        const pgBobot = parseFloat(document.getElementById('pg-bobot').value) || 0;

        const isianSoal = parseFloat(document.getElementById('isian-soal').value) || 0;
        const isianBenar = parseFloat(document.getElementById('isian-benar').value) || 0;
        const isianBobot = parseFloat(document.getElementById('isian-bobot').value) || 0;

        const essayMax = parseFloat(document.getElementById('essay-max').value) || 0;
        const essayPerolehan = parseFloat(document.getElementById('essay-perolehan').value) || 0;

        if (!validateInputs(pgSoal, pgBenar, isianSoal, isianBenar, essayMax, essayPerolehan)) {
            document.getElementById('result-box').classList.remove('show');
            return;
        }

        const skorMaxPG = pgSoal * pgBobot;
        const skorPerolehanPG = pgBenar * pgBobot;

        const skorMaxIsian = isianSoal * isianBobot;
        const skorPerolehanIsian = isianBenar * isianBobot;

        const totalSkorMaksimal = skorMaxPG + skorMaxIsian + essayMax;
        const totalSkorPerolehan = skorPerolehanPG + skorPerolehanIsian + essayPerolehan;

        let nilaiAkhir = 0;
        if (totalSkorMaksimal > 0) {
            nilaiAkhir = (totalSkorPerolehan / totalSkorMaksimal) * 100;
        }

        nilaiAkhir = Math.round(nilaiAkhir * 100) / 100;

        document.getElementById('final-score').textContent = formatAngka(nilaiAkhir);

        document.getElementById('score-summary').textContent =
            `Total Skor: ${formatAngka(totalSkorPerolehan)} dari ${formatAngka(totalSkorMaksimal)}`;

        let breakdown = '<strong>Rincian:</strong><br>';
        if (pgSoal > 0) {
            breakdown += `PG: ${formatAngka(skorPerolehanPG)} dari ${formatAngka(skorMaxPG)}<br>`;
        }
        if (isianSoal > 0) {
            breakdown += `Isian: ${formatAngka(skorPerolehanIsian)} dari ${formatAngka(skorMaxIsian)}<br>`;
        }
        if (essayMax > 0) {
            breakdown += `Essay: ${formatAngka(essayPerolehan)} dari ${formatAngka(essayMax)}`;
        }

        document.getElementById('score-breakdown').innerHTML = breakdown;
        document.getElementById('result-box').classList.add('show');
    }

    function resetForm() {
        document.getElementById('pg-soal').value = 28;
        document.getElementById('pg-benar').value = 0;
        document.getElementById('pg-bobot').value = 1;

        document.getElementById('isian-soal').value = 6;
        document.getElementById('isian-benar').value = 0;
        document.getElementById('isian-bobot').value = 2;

        document.getElementById('essay-max').value = 18;
        document.getElementById('essay-perolehan').value = 0;

        document.getElementById('result-box').classList.remove('show');
        hideError();
    }

    document.addEventListener('keydown', function(event) {
        if (event.key === 'Enter') {
            hitungNilai();
        }
    });
</script>

</body>
</html>
