<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Dokumen Pengiriman</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f0f2f5;
            color: #333;
            padding: 20px;
        }
        .document-wrapper {
            background-color: white;
            width: 21cm; /* Ukuran kertas A4 portrait */
            min-height: 29.7cm;
            margin: 20px auto;
            padding: 1.5cm;
            box-shadow: 0 0 10px rgba(0,0,0,0.15);
            box-sizing: border-box;
        }
        .header {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            border-bottom: 3px solid #333;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        .header .company-info {
            font-size: 0.9em;
        }
        .header .company-info h1 {
            margin: 0;
            font-size: 1.8em;
            color: #2c3e50;
        }
        .document-title {
            text-align: right;
        }
        .document-title h2 {
            margin: 0;
            font-size: 2em;
            color: #3498db;
        }
        .info-section {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
            font-size: 0.9em;
        }
        .info-section div {
            width: 48%;
        }
        .info-section table {
            width: 100%;
        }
        .info-section td {
            padding: 2px 0;
        }
        .item-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
            font-size: 0.9em;
        }
        .item-table th, .item-table td {
            border: 1px solid #ccc;
            padding: 8px;
            text-align: left;
        }
        .item-table th {
            background-color: #f2f2f2;
        }
        .item-table .text-center { text-align: center; }
        .item-table .text-right { text-align: right; }
        .footer {
            margin-top: 40px;
            font-size: 0.9em;
        }
        .signature-section {
            display: flex;
            justify-content: space-around;
            text-align: center;
            margin-top: 60px;
        }
        .signature-box {
            width: 30%;
        }
        .signature-box .name {
            margin-top: 60px;
            border-top: 1px solid #333;
            padding-top: 5px;
        }
    </style>
</head>
<body>

    <div class="document-wrapper">
        <div class="header">
            <div class="company-info">
                <h1>PT. BRIKET SEJAHTERA</h1>
                Jl. Industri Raya No. 123, Makassar, Indonesia<br>
                Telepon: (0411) 123-4567<br>
                Email: contact@briketsejahtera.com
            </div>
            <div class="document-title">
                <h2>SURAT JALAN</h2>
                <h4><em>DELIVERY NOTE</em></h4>
            </div>
        </div>

        <div class="info-section">
            <div class="recipient-info">
                <strong>DIKIRIM KEPADA (CONSIGNEE):</strong><br>
                PT. Mitra Jaya Abadi<br>
                Jl. Pelabuhan Baru No. 88, Jakarta Utara<br>
                DKI Jakarta, Indonesia<br>
                Attn: Bapak Rudi
            </div>
            <div class="shipping-info">
                <table>
                    <tr><td><strong>No. Surat Jalan:</strong></td><td>SJ-2025-06-015</td></tr>
                    <tr><td><strong>Tanggal Kirim:</strong></td><td>18 Juni 2025</td></tr>
                    <tr><td><strong>No. Order Penjualan:</strong></td><td>SO-2025-06-088</td></tr>
                </table>
            </div>
        </div>

        <div class="info-section">
             <div>
                <strong>INFORMASI PENGANGKUTAN:</strong><br>
                Ekspedisi: Truk Internal Perusahaan<br>
                Kendaraan: Truk Fuso<br>
                Nomor Polisi: DD 1234 XY
             </div>
        </div>

        <table class="item-table">
            <thead>
                <tr>
                    <th class="text-center">No.</th>
                    <th>Kode Barang</th>
                    <th>Nama Barang</th>
                    <th class="text-center">Jumlah</th>
                    <th class="text-center">Satuan</th>
                    <th>Keterangan</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td class="text-center">1</td>
                    <td>BK001</td>
                    <td>Briket Arang Hexagonal Super</td>
                    <td class="text-center">1000</td>
                    <td class="text-center">Kg</td>
                    <td>Dikemas dalam 100 karung</td>
                </tr>
                <tr>
                    <td class="text-center">2</td>
                    <td>BK002</td>
                    <td>Briket Arang Kubus Grade A</td>
                    <td class="text-center">500</td>
                    <td class="text-center">Kg</td>
                    <td>Dikemas dalam 20 dus</td>
                </tr>
            </tbody>
        </table>

        <div class="footer">
            <p>Barang-barang yang disebutkan di atas telah diterima dalam kondisi baik dan jumlah yang cukup.</p>
            <div class="signature-section">
                <div class="signature-box">
                    Disiapkan Oleh,
                    <div class="name">( Staf Gudang )</div>
                </div>
                <div class="signature-box">
                    Dibawa Oleh,
                    <div class="name">( Sopir )</div>
                </div>
                <div class="signature-box">
                    Diterima Oleh,
                    <div class="name">( Penerima / Cap Perusahaan )</div>
                </div>
            </div>
        </div>
    </div>

    <div class="document-wrapper">
        <div class="header">
            <div class="company-info">
                <h1>PT. BRIKET SEJAHTERA</h1>
                Jl. Industri Raya No. 123, Makassar, Indonesia
            </div>
            <div class="document-title">
                <h2>PACKING LIST</h2>
                <h4><em>DAFTAR PENGEPAKAN</em></h4>
            </div>
        </div>

        <div class="info-section">
            <div>
                <strong>PENERIMA:</strong><br>
                PT. Mitra Jaya Abadi, Jakarta
            </div>
            <div>
                 <table>
                    <tr><td><strong>Mereferensikan Surat Jalan No:</strong></td><td>SJ-2025-06-015</td></tr>
                    <tr><td><strong>Tanggal Kirim:</strong></td><td>18 Juni 2025</td></tr>
                </table>
            </div>
        </div>
         <div class="info-section">
             <div>
                <strong>RINGKASAN PENGIRIMAN:</strong><br>
                Total Kemasan: 2 Palet<br>
                Total Berat Kotor (Gross Weight): 1550 Kg<br>
                Total Berat Bersih (Net Weight): 1500 Kg
             </div>
        </div>

        <table class="item-table">
            <thead>
                <tr>
                    <th class="text-center">No.</th>
                    <th>Deskripsi Barang (termasuk No. Batch)</th>
                    <th class="text-center">Jumlah</th>
                    <th class="text-center">Satuan</th>
                    <th class="text-right">Berat Bersih (Kg)</th>
                    <th class="text-right">Berat Kotor (Kg)</th>
                </tr>
            </thead>
            <tbody>
                <tr><td colspan="6" style="background-color:#e9ecef; font-weight:bold;">PALLET 1 dari 2</td></tr>
                <tr>
                    <td class="text-center">1</td>
                    <td>[BK001] Briket Arang Hexagonal Super<br><em>Batch: BHEXA001</em></td>
                    <td class="text-center">1000</td>
                    <td class="text-center">Kg</td>
                    <td class="text-right">1000.00</td>
                    <td class="text-right">1020.00</td>
                </tr>
                <tr><td colspan="6" style="background-color:#e9ecef; font-weight:bold;">PALLET 2 dari 2</td></tr>
                <tr>
                    <td class="text-center">2</td>
                    <td>[BK002] Briket Arang Kubus Grade A<br><em>Batch: BKUBA008</em></td>
                    <td class="text-center">500</td>
                    <td class="text-center">Kg</td>
                    <td class="text-right">500.00</td>
                    <td class="text-right">530.00</td>
                </tr>
            </tbody>
            <tfoot>
                <tr style="background-color:#e9ecef; font-weight:bold;">
                    <td colspan="4" class="text-right">TOTAL</td>
                    <td class="text-right">1500.00 Kg</td>
                    <td class="text-right">1550.00 Kg</td>
                </tr>
            </tfoot>
        </table>

         <div class="footer">
            <p>Catatan: Berat Kotor termasuk berat palet dan kemasan.</p>
            <div class="signature-section">
                <div class="signature-box">
                    Diperiksa & Dikemas Oleh,
                    <div class="name">( Staf Pengepakan )</div>
                </div>
            </div>
        </div>
    </div>

</body>
</html>
