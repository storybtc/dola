<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>LAPORAN PEMBAYARAN WIFI</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            /* GANTI FONT supaya bisa bedain besar/kecil */
            font-family: 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            font-weight: bold;
            white-space: nowrap;
            text-transform: uppercase; /* SEMUA HURUF BESAR SECARA OTOMATIS */
        }

        body {
            background-color: #ffffff;
            padding: 8px;
            overflow-x: hidden;
        }

        .container {
            max-width: 1080px;
            margin: 0 auto;
        }

        /* HEADER UTAMA - ANIMASI TERBANG */
        .header-bar {
            background: linear-gradient(90deg, #2563eb 0%, #9333ea 100%);
            color: white;
            text-align: center;
            padding: 12px 0;
            border-radius: 10px;
            font-weight: 900;
            font-size: clamp(14px, 3.2vw, 22px);
            letter-spacing: 0.5px;
            margin-bottom: 8px;
            
            /* ANIMASI TERBANG / MELAYANG */
            animation: terbang 2s ease-in-out infinite alternate;
            text-shadow: 0 2px 4px rgba(0,0,0,0.3);
        }

        @keyframes terbang {
            0% { transform: translateY(0px); }
            100% { transform: translateY(-4px); }
        }

        /* KOTAK SALDO UTAMA */
        .saldo-card {
            background: linear-gradient(90deg, #3b82f6 0%, #a855f7 100%);
            border-radius: 10px;
            padding: 15px 8px;
            text-align: center;
            color: white;
            margin-bottom: 8px;
        }

        .system-online {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 6px;
            font-size: clamp(11px, 2.8vw, 16px);
            margin-bottom: 4px;
            position: relative;
            width: 100%;
        }

        .system-online span {
            color: #39FF14;
            text-shadow: 0 0 8px rgba(57, 255, 20, 0.8);
            line-height: 1;
            display: flex;
            align-items: center;
            height: 24px;
        }

        .radar-wrapper {
            position: relative;
            width: 24px;
            height: 24px;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
        }

        .radar-dot {
            width: 6px;
            height: 6px;
            background-color: #00FF00;
            border-radius: 50%;
            position: relative;
            z-index: 2;
            box-shadow: 0 0 6px #00FF00;
        }

        .radar-wave {
            position: absolute;
            border: 1px solid rgba(0, 255, 0, 0.8);
            border-radius: 50%;
            animation: radarKedip 2s infinite ease-out;
            z-index: 1;
        }

        .radar-wave:nth-child(2) { animation-delay: 0s; }
        .radar-wave:nth-child(3) { animation-delay: 0.6s; }
        .radar-wave:nth-child(4) { animation-delay: 1.2s; }

        @keyframes radarKedip {
            0% { width: 0px; height: 0px; opacity: 1; border-width: 2px; box-shadow: 0 0 8px rgba(255,255,255,0.6); }
            100% { width: 30px; height: 30px; opacity: 0; border-width: 1px; box-shadow: 0 0 2px rgba(255,255,255,0.2); }
        }

        .saldo-label {
            font-size: clamp(10px, 2.5vw, 15px);
            opacity: 0.9;
            margin-bottom: 3px;
        }

        /* NOMINAL SALDO - BAYANGAN REMANG-REMANG, EFEK TERBANG */
        .saldo-value {
            font-size: clamp(32px, 10vw, 60px);
            font-weight: 900;
            color: #ffffff;
            /* BAYANGAN LEMBUT / REMANG-REMANG */
            text-shadow: 0 4px 6px rgba(0, 0, 0, 0.15), 
                         0 1px 3px rgba(0, 0, 0, 0.08);
            transform: translateY(-3px); /* EFEK TERBANG TERANGKAT */
            position: relative;
            z-index: 2;
            /* KHUSUS BAGIAN INI: HILANGKAN UPPERCASE supaya Rp tetap Rp */
            text-transform: none;
        }

        /* TOTAL BAYAR & TAGIHAN */
        .total-row {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 6px;
            margin-bottom: 8px;
        }

        .total-box {
            background-color: #ffffff;
            border-radius: 10px;
            padding: 12px 4px 6px 4px; /* Spasi bawah dikurangi untuk garis putih */
            text-align: center;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
            position: relative;
            overflow: hidden;
        }

        .total-label {
            font-size: clamp(9px, 2.2vw, 14px);
            color: #6b7280;
            margin-bottom: 3px;
        }

        .total-bayar {
            /* UKURAN DIPERKECIL SESUAI PERMINTAAN */
            font-size: clamp(16px, 4vw, 24px);
            font-weight: 900;
            color: #16a34a;
            padding-bottom: 4px; /* Spasi sebelum garis hijau */
            /* GARIS HIJAU DI PALING BAWAH */
            border-bottom: 3px solid #16a34a;
            border-radius: 0 0 6px 6px;
            /* GARIS PUTIH DI BAWAH GARIS HIJAU */
            box-shadow: 0 2px 0 0 #ffffff;
            /* KHUSUS BAGIAN INI: HILANGKAN UPPERCASE supaya Rp tetap Rp */
            text-transform: none;
        }

        .total-tagihan {
            /* UKURAN DIPERKECIL SESUAI PERMINTAAN */
            font-size: clamp(16px, 4vw, 24px);
            font-weight: 900;
            color: #dc2626;
            padding-bottom: 4px; /* Spasi sebelum garis merah */
            /* GARIS MERAH DI PALING BAWAH */
            border-bottom: 3px solid #dc2626;
            border-radius: 0 0 6px 6px;
            /* GARIS PUTIH DI BAWAH GARIS MERAH */
            box-shadow: 0 2px 0 0 #ffffff;
            /* KHUSUS BAGIAN INI: HILANGKAN UPPERCASE supaya Rp tetap Rp */
            text-transform: none;
        }

        /* TOMBOL INPUT */
        .input-bar {
            background: linear-gradient(90deg, #2563eb 0%, #9333ea 100%);
            color: white;
            text-align: center;
            padding: 8px 0;
            border-radius: 10px;
            font-size: clamp(12px, 3vw, 16px);
            margin-bottom: 8px;
            cursor: pointer;
            transition: opacity 0.2s;
        }

        .input-bar:hover { opacity: 0.9; }

        /* TABEL UTAMA */
        .table-container {
            border: 1px solid #e2e8f0;
            border-radius: 10px;
            overflow: hidden;
            width: 100%;
            margin-bottom: 4px;
        }

        .table-header, .table-row, .table-total {
            display: grid;
            grid-template-columns: 2.2fr 1.3fr 1.3fr 1.3fr 0.8fr 1.6fr;
            width: 100%;
            gap: 0; /* Hilangkan jarak antar kolom */
        }

        .table-header {
            background-color: #eff6ff;
            padding: 4px 0; /* Spasi header */
        }

        .table-row {
            background-color: #ffffff;
            padding: 1px 0; /* SPASI VERTIKAL 2px TOTAL (atas 1 + bawah 1) */
            border-bottom: 1px solid #f3f4f6;
        }

        .table-cell {
            text-align: center;
            padding: 1px 2px; /* SPASI VERTIKAL DI DALAM SEL 2px */
            font-size: clamp(9px, 2.2vw, 13px);
            display: flex;
            align-items: center;
            justify-content: center;
            line-height: 1.1; /* Rapatkan tinggi baris */
        }

        .nama-bulan {
            color: #2563eb;
            justify-content: flex-start;
            padding-left: 8px;
            font-size: clamp(11px, 2.5vw, 15px);
            padding-top: 3px;
            padding-bottom: 3px;
            background-color: #dbeafe;
            font-weight: 900;
        }

        .nilai-bayar { 
            color: #16a34a; 
            /* KHUSUS BAGIAN INI: HILANGKAN UPPERCASE supaya Rp tetap Rp jika ada */
            text-transform: none;
        }
        .nilai-tagih { 
            color: #dc2626; 
            /* KHUSUS BAGIAN INI: HILANGKAN UPPERCASE supaya Rp tetap Rp jika ada */
            text-transform: none;
        }
        .nilai-saldo { 
            color: #16a34a; 
            /* KHUSUS BAGIAN INI: HILANGKAN UPPERCASE supaya Rp tetap Rp jika ada */
            text-transform: none;
        }
        .nilai-akm { 
            color: #2563eb; 
            /* KHUSUS BAGIAN INI: HILANGKAN UPPERCASE supaya Rp tetap Rp jika ada */
            text-transform: none;
        }

        /* BARIS TOTAL PER BULAN - FONT LEBIH BESAR & MENONJOL */
        .table-total {
            background: linear-gradient(90deg, #2563eb 0%, #9333ea 100%);
            color: white;
            padding: 2px 0; /* SPASI VERTIKAL 2px */
            font-weight: 900;
        }
        /* Khusus tulisan TOTAL di kolom pertama */
        .table-total .table-cell:first-child {
            font-size: clamp(12px, 3vw, 18px); /* LEBIH BESAR */
            font-weight: 900;
            letter-spacing: 0.5px;
        }
        /* Nilai angka di baris total juga diperbesar sedikit */
        .table-total .table-cell {
            font-size: clamp(10px, 2.5vw, 15px);
            font-weight: bold;
        }

        /* IKON SAMPAH - SANGAT KECIL & WARNA MERAH NYALA */
        .icon-hapus {
            font-size: 7px; /* SANGAT KECIL SEKALI */
            cursor: pointer;
            color: #ff0000; /* MERAH MURNI */
            transition: 0.2s;
            text-shadow: 0 0 2px rgba(255, 0, 0, 0.6);
        }
        .icon-hapus:hover { transform: scale(1.5); }

        /* ========================================== */
        /* BAGIAN PIN - WARNA SUDAH DISESUAIKAN DGN HEADER */
        /* ========================================== */
        .modal-pin {
            display: none;
            position: fixed;
            top: 0; left: 0;
            width: 100%; height: 100%;
            background-color: rgba(0,0,0,0.6);
            z-index: 999;
            align-items: center;
            justify-content: center;
            padding: 8px;
            overflow-y: auto;
        }

        .modal-content {
            background-color: #ffffff;
            border-radius: 16px;
            padding: 20px;
            width: 100%; 
            max-width: 340px;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0,0,0,0.15);
        }

        .icon-kunci {
            width: 50px;
            height: 50px;
            background: linear-gradient(90deg, #2563eb 0%, #9333ea 100%);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 12px auto;
            color: #ffffff;
            font-size: 24px;
        }

        .modal-content h3 {
            margin-bottom: 6px;
            color: #2563eb;
            font-size: clamp(16px, 4vw, 20px);
            font-weight: bold;
        }

        .modal-subtitle {
            font-size: clamp(12px, 3vw, 14px);
            color: #6b7280;
            margin-bottom: 20px;
            text-transform: none;
        }

        .pin-display {
            font-size: clamp(18px, 6vw, 24px);
            letter-spacing: 4px;
            padding: 12px 10px;
            border: 1px solid #cbd5e1;
            border-radius: 8px;
            margin-bottom: 20px;
            background-color: #ffffff;
            color: #1e293b;
            min-height: 48px;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }
        .pin-display span {
            width: 8px;
            height: 8px;
            background: linear-gradient(90deg, #2563eb 0%, #9333ea 100%);
            border-radius: 50%;
            margin: 0 4px;
        }

        .tombol-aksi {
            display: flex;
            gap: 10px;
            margin-bottom: 20px;
        }
        .btn-batal {
            flex: 1;
            padding: 10px 0;
            border: none;
            border-radius: 8px;
            background-color: #e2e8f0;
            color: #334155;
            font-weight: bold;
            font-size: clamp(13px, 3vw, 16px);
            cursor: pointer;
        }
        .btn-verifikasi {
            flex: 1;
            padding: 10px 0;
            border: none;
            border-radius: 8px;
            background: linear-gradient(90deg, #2563eb 0%, #9333ea 100%);
            color: white;
            font-weight: bold;
            font-size: clamp(13px, 3vw, 16px);
            cursor: pointer;
        }

        .keypad {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
            background: linear-gradient(90deg, #2563eb 0%, #9333ea 100%);
            padding: 12px;
            border-radius: 12px;
        }

        .key {
            padding: 14px 5px;
            font-size: clamp(16px, 4vw, 20px);
            border: none;
            border-radius: 8px;
            background-color: #ffffff;
            color: #1e293b;
            cursor: pointer;
            transition: 0.2s;
            font-weight: bold;
        }
        .key:hover { background-color: #f1f5f9; }

        .key-hapus {
            background-color: #ffffff;
            color: #dc2626;
            font-size: 18px;
        }
        .key-ok {
            background-color: #1d4ed8;
            color: white;
            font-size: 18px;
        }
        /* ========================================== */


        /* MODAL SIMPAN */
        .modal-simpan {
            display: none;
            position: fixed;
            top: 0; left: 0;
            width: 100%; height: 100%;
            background-color: rgba(0,0,0,0.6);
            z-index: 1000;
            align-items: center;
            justify-content: center;
            padding: 8px;
            overflow-y: auto;
        }

        .form-group {
            display: flex;
            flex-direction: column;
            gap: 4px;
            margin-bottom: 10px;
            text-align: left;
        }
        .form-group label {
            font-size: clamp(11px, 2.8vw, 14px);
            color: #334155;
        }
        .form-group input, .form-group select {
            padding: 8px 10px;
            border: 1px solid #cbd5e1;
            border-radius: 8px;
            font-size: clamp(11px, 2.8vw, 14px);
            outline: none;
            font-weight: bold;
            width: 100%;
            text-transform: none; /* Supaya input angka tidak ikut besar kecil */
        }

        .btn-simpan-data {
            background: linear-gradient(90deg, #2563eb 0%, #9333ea 100%);
            color: white;
            border: none;
            padding: 10px 0;
            border-radius: 8px;
            font-size: clamp(12px, 3vw, 15px);
            cursor: pointer;
            width: 100%;
        }
        .btn-simpan-data:hover { opacity: 0.9; }

        .footer-text {
            text-align: center;
            font-size: clamp(9px, 2vw, 13px);
            color: #94a3b8;
            margin-top: 10px;
            letter-spacing: 0.5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- HEADER DENGAN ANIMASI TERBANG -->
        <div class="header-bar">
            LAPORAN PEMBAYARAN WIFI
        </div>

        <!-- SALDO UTAMA -->
        <div class="saldo-card">
            <div class="system-online">
                <div class="radar-wrapper">
                    <div class="radar-wave"></div>
                    <div class="radar-wave"></div>
                    <div class="radar-wave"></div>
                    <div class="radar-dot"></div>
                </div>
                <span>SYSTEM ONLINE</span>
            </div>
            <div class="saldo-label">SALDO AKUMULASI SAAT INI</div>
            <div class="saldo-value" id="saldoAkumulasi">Rp 0</div>
        </div>

        <!-- TOTAL BAYAR & TAGIHAN -->
        <div class="total-row">
            <div class="total-box">
                <div class="total-label">TOTAL BAYAR</div>
                <div class="total-bayar" id="totalBayar">Rp 0</div>
            </div>
            <div class="total-box">
                <div class="total-label">TOTAL TAGIHAN</div>
                <div class="total-tagihan" id="totalTagihan">Rp 0</div>
            </div>
        </div>

        <!-- TOMBOL INPUT -->
        <div class="input-bar" id="btnBukaPin">
            INPUT DATA BARU
        </div>

        <!-- TABEL -->
        <div class="table-container">
            <div class="table-header">
                <div class="table-cell">BULAN</div>
                <div class="table-cell">PEMBAYARAN</div>
                <div class="table-cell">TAGIHAN</div>
                <div class="table-cell">SALDO</div>
                <div class="table-cell">OPSI</div>
                <div class="table-cell">AKM. SALDO</div>
            </div>
            <div id="isiTabel"></div>
        </div>

        <!-- FOOTER -->
        <div class="footer-text">
            POWERED BY: MBS ID
        </div>
    </div>


    <!-- MODAL PIN -->
    <div class="modal-pin" id="modalPin">
        <div class="modal-content">
            <div class="icon-kunci">🔒</div>
            <h3>PIN OTORISASI SISTEM</h3>
            <div class="modal-subtitle">MASUKKAN PIN KEAMANAN SISTEM</div>
            
            <div class="pin-display" id="pinDisplay">
                <span></span><span></span><span></span><span></span><span></span><span></span>
            </div>

            <div class="tombol-aksi">
                <button class="btn-batal" onclick="tutupModal()">BATAL</button>
                <button class="btn-verifikasi" onclick="cekPin()">VERIFIKASI</button>
            </div>

            <div class="keypad">
                <button class="key" onclick="tekanAngka(1)">1</button>
                <button class="key" onclick="tekanAngka(2)">2</button>
                <button class="key" onclick="tekanAngka(3)">3</button>
                <button class="key" onclick="tekanAngka(4)">4</button>
                <button class="key" onclick="tekanAngka(5)">5</button>
                <button class="key" onclick="tekanAngka(6)">6</button>
                <button class="key" onclick="tekanAngka(7)">7</button>
                <button class="key" onclick="tekanAngka(8)">8</button>
                <button class="key" onclick="tekanAngka(9)">9</button>
                <button class="key key-hapus" onclick="hapusAngka()">⌫</button>
                <button class="key" onclick="tekanAngka(0)">0</button>
                <button class="key key-ok" onclick="cekPin()">➔</button>
            </div>
        </div>
    </div>


    <!-- MODAL SIMPAN -->
    <div class="modal-simpan" id="modalSimpan">
        <div class="modal-content">
            <h3>SIMPAN DATA</h3>
            <div class="form-group">
                <label for="bulan">BULAN & TAHUN</label>
                <div style="display:flex; gap:6px;">
                    <select id="bulan" name="bulan" style="flex:1;">
                        <option value="01">Januari</option>
                        <option value="02">Februari</option>
                        <option value="03">Maret</option>
                        <option value="04">April</option>
                        <option value="05">Mei</option>
                        <option value="06">Juni</option>
                        <option value="07">Juli</option>
                        <option value="08">Agustus</option>
                        <option value="09">September</option>
                        <option value="10">Oktober</option>
                        <option value="11">November</option>
                        <option value="12">Desember</option>
                    </select>
                    <select id="tahun" name="tahun" style="flex:1;">
                        <option value="2024">2024</option>
                        <option value="2025">2025</option>
                        <option value="2026" selected>2026</option>
                        <option value="2027">2027</option>
                        <option value="2028">2028</option>
                    </select>
                </div>
            </div>
            <div class="form-group">
                <label for="pembayaran">PEMBAYARAN (Rp)</label>
                <input type="number" id="pembayaran" name="pembayaran" value="55000">
            </div>
            <div class="form-group">
                <label for="tagihan">TAGIHAN (Rp)</label>
                <input type="number" id="tagihan" name="tagihan" value="52447">
            </div>
            <button class="btn-simpan-data" onclick="simpanData()">SIMPAN</button>
        </div>
    </div>


    <script>
        const modalPin = document.getElementById('modalPin');
        const modalSimpan = document.getElementById('modalSimpan');
        const pinDisplay = document.getElementById('pinDisplay');
        let inputPin = '';
        let barisAkanDihapus = null;

        // Simpan bulan & tahun terakhir diinput agar tidak kembali ke Mei
        let bulanTerakhir = '05'; // default awal
        let tahunTerakhir = '2026'; // default awal
        
        let totalBayar = 0;
        let totalTagihan = 0;
        let saldoAkumulasiAkhir = 78860; // ✅ SALDO AWAL SEBELUM JANUARI = 78.860
        let dataPerBulan = {}; // Simpan data per bulan untuk hitung total

        // Urutan bulan untuk pengurutan
        const urutanBulan = {
            'JANUARI 2026': 1, 'FEBRUARI 2026': 2, 'MARET 2026': 3, 'APRIL 2026': 4, 'MEI 2026': 5, 'JUNI 2026': 6,
            'JULI 2026': 7, 'AGUSTUS 2026': 8, 'SEPTEMBER 2026': 9, 'OKTOBER 2026': 10, 'NOVEMBER 2026': 11, 'DESEMBER 2026': 12,
            'JANUARI 2025': 13, 'FEBRUARI 2025': 14, 'MARET 2025': 15, 'APRIL 2025': 16, 'MEI 2025': 17, 'JUNI 2025': 18,
            'JULI 2025': 19, 'AGUSTUS 2025': 20, 'SEPTEMBER 2025': 21, 'OKTOBER 2025': 22, 'NOVEMBER 2025': 23, 'DESEMBER 2025': 24,
            'JANUARI 2024': 25, 'FEBRUARI 2024': 26, 'MARET 2024': 27, 'APRIL 2024': 28, 'MEI 2024': 29, 'JUNI 2024': 30,
            'JULI 2024': 31, 'AGUSTUS 2024': 32, 'SEPTEMBER 2024': 33, 'OKTOBER 2024': 34, 'NOVEMBER 2024': 35, 'DESEMBER 2024': 36
        };

        // Saat buka modal, gunakan bulan terakhir diinput
        function setTanggalTerakhir() {
            document.getElementById('bulan').value = bulanTerakhir;
            document.getElementById('tahun').value = tahunTerakhir;
            // Isi otomatis nilai paten
            document.getElementById('pembayaran').value = 55000;
            document.getElementById('tagihan').value = 52447;
        }

        // Buka PIN
        document.getElementById('btnBukaPin').addEventListener('click', function() {
            modalPin.style.display = 'flex';
            modalSimpan.style.display = 'none';
            inputPin = '';
            perbaruiTampilanPin();
            barisAkanDihapus = null;
        });

        // Hapus baris
        function hapusBaris(elemenBaris) {
            barisAkanDihapus = elemenBaris;
            modalPin.style.display = 'flex';
            modalSimpan.style.display = 'none';
            inputPin = '';
            perbaruiTampilanPin();
        }

        // Tutup modal
        function tutupModal() {
            modalPin.style.display = 'none'; 
            hapusAngka(); 
            barisAkanDihapus=null;
        }

        // Ketik PIN: max 6 digit
        function tekanAngka(angka) {
            if (inputPin.length < 6) {
                inputPin += angka;
                perbaruiTampilanPin();
            }
        }

        function hapusAngka() {
            inputPin = '';
            perbaruiTampilanPin();
        }

        // Perbarui tampilan titik PIN
        function perbaruiTampilanPin() {
            const titik = pinDisplay.querySelectorAll('span');
            titik.forEach((el, idx) => {
                el.style.opacity = (idx < inputPin.length) ? '1' : '0.3';
            });
        }

        // Cek PIN: harus PAS 999
        function cekPin() {
            if (inputPin === '999') {
                modalPin.style.display = 'none';
                
                if(barisAkanDihapus !== null) {
                    // ✅ PERBAIKAN: HAPUS HANYA 1 BARIS SAJA
                    const b = parseInt(barisAkanDihapus.dataset.bayar);
                    const t = parseInt(barisAkanDihapus.dataset.tagih);
                    const akmHapus = parseInt(barisAkanDihapus.dataset.akm);
                    const bulan = barisAkanDihapus.dataset.bulan;
                    const selisih = b - t;

                    // Kurangi total keseluruhan
                    totalBayar -= b;
                    totalTagihan -= t;

                    // ✅ HAPUS HANYA DATA BARIS TERSEBUT DALAM DAFTAR, BUKAN SEMUA DATA BULAN
                    if(dataPerBulan[bulan]) {
                        // Cari indeks data yang akan dihapus
                        const indexHapus = dataPerBulan[bulan].rincian.findIndex(item => 
                            item.bayar === b && item.tagih === t && item.akumulasi === akmHapus
                        );
                        
                        if(indexHapus > -1) {
                            // Hapus hanya 1 data itu saja
                            dataPerBulan[bulan].rincian.splice(indexHapus, 1);
                            // Kurangi hitungan total bulan
                            dataPerBulan[bulan].bayar -= b;
                            dataPerBulan[bulan].tagih -= t;
                            dataPerBulan[bulan].saldo -= selisih;
                            dataPerBulan[bulan].jumlahData -= 1;
                        }

                        // Jika setelah dihapus bulan itu kosong, baru hapus nama bulannya
                        if(dataPerBulan[bulan].jumlahData <= 0) {
                            delete dataPerBulan[bulan];
                            const namaBulanEl = document.querySelector(`.nama-bulan[data-bulan="${bulan}"]`);
                            if(namaBulanEl) namaBulanEl.parentElement.remove();
                            const totalBulanEl = document.querySelector(`.table-total[data-bulan="${bulan}"]`);
                            if(totalBulanEl) totalBulanEl.remove();
                        }
                    }

                    // Hapus baris dari tampilan
                    barisAkanDihapus.remove();

                    // ✅ HITUNG ULANG SEMUA AKUMULASI DARI AWAL
                    hitungUlangSemuaAkumulasi();
                    tampilkanUlangSemuaData();
                    perbaruiTampilanTotal();
                    barisAkanDihapus = null;
                } else {
                    modalSimpan.style.display = 'flex';
                    setTanggalTerakhir(); // Panggil tanggal terakhir
                }
            } else {
                alert('❌ PIN SALAH!');
                hapusAngka();
            }
        }

        // Simpan Data
        function simpanData() {
            const bulanPilih = document.getElementById('bulan').value;
            const tahunPilih = document.getElementById('tahun').value;
            const bayar = parseInt(document.getElementById('pembayaran').value) || 0;
            const tagih = parseInt(document.getElementById('tagihan').value) || 0;

            if (!bulanPilih || !tahunPilih) { alert('⚠️ BULAN & TAHUN WAJIB DIPILIH!'); return; }

            // SIMPAN BULAN & TAHUN TERAKHIR YANG DIPILIH
            bulanTerakhir = bulanPilih;
            tahunTerakhir = tahunPilih;

            const tglBuatan = `${tahunPilih}-${bulanPilih}-01`;
            const selisih = bayar - tagih;
            totalBayar += bayar;
            totalTagihan += tagih;

            const namaBulan = new Date(tglBuatan).toLocaleDateString('id-ID', { month: 'long', year: 'numeric' }).toUpperCase();

            if(!dataPerBulan[namaBulan]) {
                dataPerBulan[namaBulan] = { bayar:0, tagih:0, saldo:0, jumlahData:0, rincian:[] };
            }
            
            // ✅ Simpan sementara, akumulasi dihitung ulang nanti
            dataPerBulan[namaBulan].rincian.push({bayar, tagih, selisih, waktu: new Date().getTime()});
            dataPerBulan[namaBulan].bayar += bayar;
            dataPerBulan[namaBulan].tagih += tagih;
            dataPerBulan[namaBulan].saldo += selisih;
            dataPerBulan[namaBulan].jumlahData += 1;

            // ✅ HITUNG ULANG SEMUA AKUMULASI DARI AWAL (PERSIS GAMBAR)
            hitungUlangSemuaAkumulasi();
            tampilkanUlangSemuaData();
            perbaruiTampilanTotal();

            // Reset nilai input saja, tanggal tetap tersimpan
            document.getElementById('pembayaran').value = 55000;
            document.getElementById('tagihan').value = 52447;
            modalSimpan.style.display = 'none';
        }


        // ✅ ALGORITMA PERHITUNGAN PERSIS GAMBAR: AKUMULASI = NILAI SEBELUMNYA + SELISIH BARIS INI
        function hitungUlangSemuaAkumulasi() {
            let akumulasiSekarang = 78860; // ✅ MULAI DARI 78.860
            const urutanKunci = Object.keys(dataPerBulan).sort((a, b) => (urutanBulan[a] || 999) - (urutanBulan[b] || 999));

            urutanKunci.forEach(kunciBulan => {
                // Urutkan rincian sesuai waktu input
                const rincianUrut = dataPerBulan[kunciBulan].rincian.sort((a,b) => a.waktu - b.waktu);
                
                rincianUrut.forEach(item => {
                    akumulasiSekarang = akumulasiSekarang + item.selisih;
                    item.akumulasi = akumulasiSekarang;
                });
            });

            saldoAkumulasiAkhir = akumulasiSekarang;
        }


        // Tampilkan ulang SEMUA data urut sesuai bulan
        function tampilkanUlangSemuaData() {
            document.getElementById('isiTabel').innerHTML = '';
            const urutanKunci = Object.keys(dataPerBulan).sort((a, b) => (urutanBulan[a] || 999) - (urutanBulan[b] || 999));

            urutanKunci.forEach(kunciBulan => {
                // ✅ NAMA BULAN MUNCUL KEMBALI
                const barisNama = document.createElement('div');
                barisNama.className = 'table-row';
                barisNama.innerHTML = `<div class="table-cell nama-bulan" data-bulan="${kunciBulan}" colspan="6">${kunciBulan}</div>`;
                document.getElementById('isiTabel').appendChild(barisNama);

                let akhiranBulan = 0;
                // Urutkan rincian agar urutan input benar
                const rincianUrut = dataPerBulan[kunciBulan].rincian.sort((a,b) => a.waktu - b.waktu);

                rincianUrut.forEach((item, idx) => {
                    akhiranBulan = item.akumulasi;

                    const barisData = document.createElement('div');
                    barisData.className = 'table-row';
                    barisData.dataset.bulan = kunciBulan;
                    barisData.dataset.bayar = item.bayar;
                    barisData.dataset.tagih = item.tagih;
                    barisData.dataset.akm = item.akumulasi;
                    barisData.innerHTML = `
                        <div class="table-cell"></div>
                        <div class="table-cell nilai-bayar">${item.bayar.toLocaleString('id-ID')}</div>
                        <div class="table-cell nilai-tagih">${item.tagih.toLocaleString('id-ID')}</div>
                        <div class="table-cell nilai-saldo">${item.selisih.toLocaleString('id-ID')}</div>
                        <div class="table-cell"><span class="icon-hapus" onclick="hapusBaris(this.parentElement.parentElement)">🗑</span></div>
                        <div class="table-cell nilai-akm">${item.akumulasi.toLocaleString('id-ID')}</div>
                    `;
                    document.getElementById('isiTabel').appendChild(barisData);
                });

                buatUlangTotalBulan(kunciBulan, akhiranBulan);
            });
        }


        // Buat baris TOTAL di akhir setiap bulan
        function buatUlangTotalBulan(namaBulan, akhiranBulan) {
            const semuaBaris = document.querySelectorAll('.table-total');
            semuaBaris.forEach(el => { if(el.dataset.bulan === namaBulan) el.remove(); });

            const total = dataPerBulan[namaBulan];
            const barisTotal = document.createElement('div');
            barisTotal.className = 'table-total';
            barisTotal.dataset.bulan = namaBulan;
            // ✅ PERSIS GAMBAR: AKM SALDO di TOTAL = angka terakhir bulan itu
            barisTotal.innerHTML = `
                <div class="table-cell">TOTAL</div>
                <div class="table-cell">${total.bayar.toLocaleString('id-ID')}</div>
                <div class="table-cell">${total.tagih.toLocaleString('id-ID')}</div>
                <div class="table-cell">${total.saldo.toLocaleString('id-ID')}</div>
                <div class="table-cell"></div>
                <div class="table-cell">${akhiranBulan.toLocaleString('id-ID')}</div>
            `;
            document.getElementById('isiTabel').appendChild(barisTotal);
        }

        // Update tampilan angka besar
        function perbaruiTampilanTotal() {
            document.getElementById('totalBayar').textContent = `Rp ${totalBayar.toLocaleString('id-ID')}`;
            document.getElementById('totalTagihan').textContent = `Rp ${totalTagihan.toLocaleString('id-ID')}`;
            document.getElementById('saldoAkumulasi').textContent = `Rp ${saldoAkumulasiAkhir.toLocaleString('id-ID')}`;
        }

        // Tutup modal
        window.onclick = function(event) {
            if (event.target === modalPin) tutupModal();
            if (event.target === modalSimpan) modalSimpan.style.display = 'none';
        }
    </script>
</body>
</html>
