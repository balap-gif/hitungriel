<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes" />
<title>Converter USD ⇄ RIEL | Live Rate & Clock</title>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', 'Poppins', sans-serif;
    }

    body {
        background: radial-gradient(circle at 10% 30%, #0B1120, #030712);
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
        padding: 20px;
        position: relative;
        overflow-x: hidden;
    }

    body::before {
        content: "";
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-image: radial-gradient(rgba(255,255,255,0.05) 1px, transparent 1px);
        background-size: 35px 35px;
        pointer-events: none;
        z-index: 0;
    }

    .container {
        width: 100%;
        max-width: 550px;
        background: rgba(18, 25, 45, 0.75);
        backdrop-filter: blur(12px);
        border-radius: 48px;
        padding: 28px 24px 36px;
        box-shadow: 0 25px 50px -12px rgba(0,0,0,0.5), 0 0 0 1px rgba(255,255,255,0.08);
        transition: all 0.25s ease;
        z-index: 2;
        border: 1px solid rgba(255,255,255,0.12);
    }

    /* Header dengan jam */
    .header-top {
        display: flex;
        justify-content: space-between;
        align-items: baseline;
        flex-wrap: wrap;
        margin-bottom: 8px;
    }

    h1 {
        font-size: 28px;
        font-weight: 700;
        background: linear-gradient(135deg, #FFFFFF 30%, #94A3F8 80%);
        background-clip: text;
        -webkit-background-clip: text;
        color: transparent;
        display: flex;
        align-items: center;
        gap: 10px;
    }

    .datetime-box {
        background: #0F172A;
        padding: 6px 14px;
        border-radius: 40px;
        border: 1px solid #334155;
        text-align: center;
        font-size: 13px;
        font-weight: 500;
    }

    .date {
        color: #94a3b8;
        letter-spacing: 0.3px;
    }

    .time {
        color: #22c55e;
        font-size: 16px;
        font-weight: 700;
        font-family: monospace;
        letter-spacing: 1px;
    }

    .sub {
        text-align: center;
        font-size: 12px;
        color: #94a3b8;
        margin-bottom: 24px;
        border-bottom: 1px dashed rgba(255,255,255,0.2);
        display: inline-block;
        width: auto;
        margin-left: auto;
        margin-right: auto;
        padding-bottom: 6px;
    }

    /* rate card */
    .rate-card {
        background: linear-gradient(145deg, #0F172A, #0B1120);
        border-radius: 32px;
        padding: 4px 20px 20px 20px;
        margin-bottom: 28px;
        border: 1px solid rgba(34, 197, 94, 0.25);
        box-shadow: 0 8px 20px -10px rgba(0,0,0,0.3);
    }

    .rate-header {
        display: flex;
        justify-content: space-between;
        align-items: baseline;
        flex-wrap: wrap;
        margin-bottom: 12px;
    }

    .rate-header label {
        font-weight: 600;
        font-size: 14px;
        color: #cbd5e6;
        background: #1E293B;
        padding: 5px 12px;
        border-radius: 40px;
    }

    .live-badge {
        font-size: 11px;
        background: #22c55e20;
        color: #86efac;
        padding: 4px 12px;
        border-radius: 30px;
        display: inline-flex;
        align-items: center;
        gap: 6px;
    }

    .live-badge::before {
        content: "";
        width: 8px;
        height: 8px;
        background: #22c55e;
        border-radius: 50%;
        display: inline-block;
        box-shadow: 0 0 5px #22c55e;
        animation: pulse 1.5s infinite;
    }

    @keyframes pulse {
        0% { opacity: 0.4; transform: scale(0.8);}
        100% { opacity: 1; transform: scale(1.2);}
    }

    .rate-input-group {
        display: flex;
        gap: 12px;
        align-items: center;
        flex-wrap: wrap;
    }

    .rate-input-group input {
        flex: 2;
        padding: 14px 18px;
        border: none;
        border-radius: 28px;
        font-size: 16px;
        font-weight: 500;
        background: #0F172A;
        color: #F1F5F9;
        border: 1px solid #334155;
        outline: none;
    }

    .rate-input-group input:focus {
        border-color: #22c55e;
        box-shadow: 0 0 0 3px #22c55e30;
    }

    .fetch-rate-btn {
        flex: 1;
        padding: 12px 16px;
        border: none;
        border-radius: 40px;
        background: #3B82F6;
        color: white;
        font-weight: 600;
        font-size: 13px;
        cursor: pointer;
        transition: 0.2s;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 6px;
    }

    .fetch-rate-btn:hover {
        background: #2563EB;
        transform: scale(1.02);
    }

    .fetch-rate-btn:disabled {
        background: #475569;
        cursor: not-allowed;
        opacity: 0.6;
    }

    input, select {
        width: 100%;
        padding: 14px 18px;
        border: none;
        border-radius: 28px;
        font-size: 16px;
        font-weight: 500;
        background: #0F172A;
        color: #F1F5F9;
        border: 1px solid #334155;
        outline: none;
    }

    .input-group {
        margin-bottom: 18px;
    }

    .input-group label {
        display: block;
        margin-bottom: 8px;
        font-size: 13px;
        font-weight: 500;
        color: #9ca3af;
        margin-left: 8px;
    }

    button {
        width: 100%;
        padding: 16px;
        border: none;
        border-radius: 60px;
        background: linear-gradient(105deg, #22c55e, #15803d);
        color: white;
        font-size: 18px;
        font-weight: 700;
        cursor: pointer;
        transition: all 0.25s;
        box-shadow: 0 8px 20px -8px #15803d70;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 10px;
        margin-top: 8px;
    }

    button:hover {
        transform: scale(1.02);
        background: linear-gradient(105deg, #2ecc71, #16a34a);
    }

    .hasil-wrapper {
        margin-top: 28px;
        background: rgba(15, 23, 42, 0.7);
        border-radius: 36px;
        padding: 6px;
        backdrop-filter: blur(5px);
        border: 1px solid rgba(34,197,94,0.3);
    }

    .hasil {
        background: #0B1120;
        padding: 24px 16px;
        border-radius: 32px;
        text-align: center;
        font-size: 24px;
        font-weight: 800;
        word-break: break-word;
        color: #e2e8f0;
        transition: 0.15s;
    }

    .info-modern {
        margin-top: 28px;
        background: #0A0F1C;
        border-radius: 28px;
        padding: 16px;
        border: 1px solid #2d3a4e;
    }

    .info-title {
        font-size: 12px;
        text-transform: uppercase;
        font-weight: 600;
        letter-spacing: 1px;
        color: #7c8ba0;
        margin-bottom: 12px;
    }

    .week-grid {
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        gap: 10px;
        text-align: center;
    }

    .day-item {
        background: #111827;
        border-radius: 20px;
        padding: 8px 4px;
    }

    .day-name {
        font-size: 12px;
        font-weight: 500;
        color: #9aa9c1;
    }

    .day-rate {
        font-size: 14px;
        font-weight: 700;
        color: #facc15;
    }

    .footer-note {
        text-align: center;
        font-size: 11px;
        color: #5e6f8d;
        margin-top: 20px;
    }

    select {
        cursor: pointer;
        appearance: none;
        background-image: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='18' height='18' viewBox='0 0 24 24' fill='none' stroke='%2394a3b8' stroke-width='2'><polyline points='6 9 12 15 18 9'></polyline></svg>");
        background-repeat: no-repeat;
        background-position: right 18px center;
    }

    @keyframes fadeSlideUp {
        from { opacity: 0; transform: translateY(20px);}
        to { opacity: 1; transform: translateY(0);}
    }

    .container {
        animation: fadeSlideUp 0.5s ease-out;
    }

    .loading-spinner {
        display: inline-block;
        width: 14px;
        height: 14px;
        border: 2px solid rgba(255,255,255,0.3);
        border-radius: 50%;
        border-top-color: white;
        animation: spin 0.6s linear infinite;
    }

    @keyframes spin {
        to { transform: rotate(360deg);}
    }

    @media (max-width: 500px) {
        .container { padding: 20px 18px;}
        .hasil { font-size: 18px;}
        .rate-input-group { flex-direction: column;}
        .fetch-rate-btn { width: 100%;}
        .header-top { flex-direction: column; gap: 10px; align-items: stretch;}
        .datetime-box { text-align: center;}
    }
</style>
</head>
<body>

<div class="container">
    <div class="header-top">
        <h1>
            <span>💵</span> USD ⇄ RIEL <span>🇰🇭</span>
        </h1>
        <div class="datetime-box">
            <div class="date" id="dateDisplay">--/--/----</div>
            <div class="time" id="timeDisplay">--:--:--</div>
        </div>
    </div>
    <div style="text-align: center; margin-bottom: 18px;">
        <div class="sub">live converter • kurs realtime</div>
    </div>

    <div class="rate-card">
        <div class="rate-header">
            <label>⚡ Kurs referensi (1 USD → KHR)</label>
            <div class="live-badge">Update hari ini</div>
        </div>
        <div class="rate-input-group">
            <input type="number" id="rate" value="4100" step="5" placeholder="Rate harian KHR">
            <button class="fetch-rate-btn" id="fetchRateBtn" onclick="fetchLiveRate()">
                🔄 Ambil Rate Hari Ini
            </button>
        </div>
        <div style="font-size:11px; color:#6f7c91; margin-top: 10px; text-align:right;">
            📌 Klik tombol untuk ambil kurs resmi dari National Bank of Cambodia
        </div>
    </div>

    <div class="input-group">
        <label>📌 Pilih arah konversi</label>
        <select id="jenis">
            <option value="usdToRiel">🇺🇸 USD → 🇰🇭 RIEL (KHR)</option>
            <option value="rielToUsd">🇰🇭 RIEL → 🇺🇸 USD</option>
        </select>
    </div>

    <div class="input-group">
        <label>💸 Masukkan nominal</label>
        <input type="number" id="nominal" placeholder="0" step="any" autocomplete="off">
    </div>

    <button onclick="hitung()" id="convertBtn">
        <span>KONVERSI SEKARANG <span>➡️</span>
    </button>

    <div class="hasil-wrapper">
        <div class="hasil" id="hasil">
            💰 Hasil konversi
        </div>
    </div>

    <div class="info-modern">
        <div class="info-title">
            📅 Contoh kurs mingguan (KHR / 1 USD)
        </div>
        <div class="week-grid">
            <div class="day-item"><div class="day-name">Senin</div><div class="day-rate">4,050 ៛</div></div>
            <div class="day-item"><div class="day-name">Selasa</div><div class="day-rate">4,100 ៛</div></div>
            <div class="day-item"><div class="day-name">Rabu</div><div class="day-rate">4,080 ៛</div></div>
            <div class="day-item"><div class="day-name">Kamis</div><div class="day-rate">4,120 ៛</div></div>
        </div>
        <div class="footer-note">
            💡 Rate dapat diubah manual atau klik tombol biru untuk ambil kurs resmi hari ini dari Bank Nasional Kamboja
        </div>
    </div>
</div>

<script>
    // ==================== FUNGSI TANGGAL & JAM ====================
    function updateDateTime() {
        const now = new Date();
        
        // Format tanggal: Senin, 17 Mei 2026
        const days = ['Minggu', 'Senin', 'Selasa', 'Rabu', 'Kamis', 'Jumat', 'Sabtu'];
        const months = ['Januari', 'Februari', 'Maret', 'April', 'Mei', 'Juni', 'Juli', 'Agustus', 'September', 'Oktober', 'November', 'Desember'];
        
        const dayName = days[now.getDay()];
        const date = now.getDate();
        const month = months[now.getMonth()];
        const year = now.getFullYear();
        
        document.getElementById('dateDisplay').innerHTML = `${dayName}, ${date} ${month} ${year}`;
        
        // Format jam: HH:MM:SS
        const hours = String(now.getHours()).padStart(2, '0');
        const minutes = String(now.getMinutes()).padStart(2, '0');
        const seconds = String(now.getSeconds()).padStart(2, '0');
        
        document.getElementById('timeDisplay').innerHTML = `${hours}:${minutes}:${seconds}`;
    }
    
    updateDateTime();
    setInterval(updateDateTime, 1000);
    
    // ==================== FORMAT ANGKA ====================
    function formatAngka(angka) {
        return angka.toLocaleString('id-ID');
    }
    
    function formatUSD(angka) {
        return angka.toLocaleString('id-ID', { minimumFractionDigits: 2, maximumFractionDigits: 2 });
    }
    
    // ==================== FUNGSI AMBIL RATE DARI API ====================
    async function fetchLiveRate() {
        const fetchBtn = document.getElementById('fetchRateBtn');
        const originalText = fetchBtn.innerHTML;
        const rateInput = document.getElementById('rate');
        
        // Tampilkan loading
        fetchBtn.innerHTML = '<span class="loading-spinner"></span> Mengambil...';
        fetchBtn.disabled = true;
        
        try {
            // Menggunakan API National Bank of Cambodia (sumber resmi)
            // API endpoint: https://api.nbc.gov.kh/api/real_time_api/khmer_riel_exchange_rate?format=json
            // Referensi: data.mef.gov.kh [citation:5]
            const response = await fetch('https://api.nbc.gov.kh/api/real_time_api/khmer_riel_exchange_rate?format=json');
            
            if (!response.ok) {
                throw new Error('Gagal mengambil data');
            }
            
            const data = await response.json();
            
            // Cari rate untuk USD
            let usdRate = null;
            
            // Struktur response dari API NBC
            if (data && data.data && Array.isArray(data.data)) {
                const usdEntry = data.data.find(item => item.currency_id === 'USD');
                if (usdEntry && usdEntry.data && usdEntry.data.selling_rate) {
                    usdRate = parseFloat(usdEntry.data.selling_rate);
                }
            }
            
            // Fallback: cek properti lain
            if (!usdRate && data && data.rates && data.rates.USD) {
                usdRate = parseFloat(data.rates.USD);
            }
            
            if (usdRate && !isNaN(usdRate) && usdRate > 0) {
                rateInput.value = Math.round(usdRate);
                // Tampilkan notifikasi sukses di hasil
                const hasilDiv = document.getElementById('hasil');
                const oldContent = hasilDiv.innerHTML;
                hasilDiv.innerHTML = '✅ Rate berhasil diperbarui! ' + oldContent;
                setTimeout(() => {
                    if (document.getElementById('hasil').innerHTML.includes('✅')) {
                        hasilDiv.innerHTML = oldContent;
                    }
                }, 2000);
                
                // Jika sudah ada nominal, hitung ulang
                const nominal = parseFloat(document.getElementById('nominal').value);
                if (!isNaN(nominal) && nominal > 0) {
                    hitung();
                }
            } else {
                throw new Error('Rate USD tidak ditemukan dalam response');
            }
            
        } catch (error) {
            console.error('Error fetching rate:', error);
            // Fallback: gunakan rate default dan beri tahu user
            const hasilDiv = document.getElementById('hasil');
            hasilDiv.innerHTML = '⚠️ Gagal mengambil rate online. Gunakan rate manual. ⚠️';
            setTimeout(() => {
                if (document.getElementById('hasil').innerHTML.includes('⚠️')) {
                    const nominal = parseFloat(document.getElementById('nominal').value);
                    if (!isNaN(nominal) && nominal > 0) {
                        hitung();
                    } else {
                        hasilDiv.innerHTML = '💰 Hasil konversi';
                    }
                }
            }, 2500);
        } finally {
            fetchBtn.innerHTML = originalText;
            fetchBtn.disabled = false;
        }
    }
    
    // ==================== FUNGSI HITUNG KONVERSI ====================
    function hitung() {
        let rateInput = document.getElementById("rate").value;
        let nominalInput = document.getElementById("nominal").value;
        let jenis = document.getElementById("jenis").value;
        
        let rate = parseFloat(rateInput);
        let nominal = parseFloat(nominalInput);
        
        if (isNaN(rate) || rate <= 0) {
            document.getElementById("hasil").innerHTML = "⚠️ Masukkan rate yang valid (>0)";
            shakeEffect();
            return;
        }
        
        if (isNaN(nominal) || nominal <= 0) {
            document.getElementById("hasil").innerHTML = "⚠️ Masukkan nominal > 0";
            shakeEffect();
            return;
        }
        
        let hasilValue = 0;
        let resultText = "";
        
        if (jenis === "usdToRiel") {
            hasilValue = nominal * rate;
            let rielFormatted = formatAngka(Math.round(hasilValue));
            let usdFormatted = formatUSD(nominal);
            resultText = `💵 $${usdFormatted} USD  →  ៛ ${rielFormatted} KHR`;
        } else {
            hasilValue = nominal / rate;
            let usdFormatted = formatUSD(hasilValue);
            let rielFormatted = formatAngka(Math.round(nominal));
            resultText = `៛ ${rielFormatted} KHR  →  💵 $${usdFormatted} USD`;
        }
        
        const hasilDiv = document.getElementById("hasil");
        hasilDiv.style.transform = "scale(0.98)";
        hasilDiv.style.opacity = "0.7";
        setTimeout(() => {
            hasilDiv.innerHTML = resultText;
            setTimeout(() => {
                hasilDiv.style.transform = "scale(1)";
                hasilDiv.style.opacity = "1";
            }, 50);
        }, 80);
        
        addRipple();
    }
    
    function shakeEffect() {
        const container = document.querySelector('.container');
        container.style.transform = 'translateX(4px)';
        setTimeout(() => { container.style.transform = 'translateX(-4px)'; }, 60);
        setTimeout(() => { container.style.transform = 'translateX(2px)'; }, 120);
        setTimeout(() => { container.style.transform = 'translateX(0)'; }, 180);
    }
    
    function addRipple() {
        const btn = document.querySelector('button');
        btn.style.transform = "scale(0.99)";
        setTimeout(() => { btn.style.transform = "scale(1)"; }, 120);
    }
    
    // Auto convert ketika ada perubahan
    function autoConvertIfReady() {
        let nominal = document.getElementById("nominal").value;
        let rate = document.getElementById("rate").value;
        if (nominal && rate && parseFloat(nominal) > 0 && parseFloat(rate) > 0) {
            hitung();
        }
    }
    
    // Event listeners
    document.getElementById("rate").addEventListener("input", autoConvertIfReady);
    document.getElementById("nominal").addEventListener("input", autoConvertIfReady);
    document.getElementById("jenis").addEventListener("change", autoConvertIfReady);
    
    document.getElementById("nominal").addEventListener("keypress", function(event) {
        if (event.key === "Enter") hitung();
    });
    document.getElementById("rate").addEventListener("keypress", function(event) {
        if (event.key === "Enter") hitung();
    });
    
    // Inisialisasi
    window.addEventListener("load", () => {
        document.getElementById("rate").value = "4100";
        document.getElementById("nominal").placeholder = "cth: 100, 250.5";
        document.getElementById("hasil").innerHTML = "💰 siap konversi";
    });
</script>
</body>
</html>
