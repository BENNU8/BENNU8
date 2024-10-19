<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Status</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet" />
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }

        .container {
            max-width: 400px;
            margin: 20px auto;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }

        .header {
            display: flex;
            align-items: center;
            padding: 10px 0;
        }

        .header img {
            width: 50px;
            margin-right: 10px;
        }

        .header div {
            font-size: 12px;
            color: #333;
        }

        .header div span {
            display: block;
        }

        .status {
            text-align: center;
            margin: 20px 0;
        }

        .status img {
            width: 100px;
        }

        .status p {
            margin: 10px 0;
            font-size: 14px;
        }

        .status .active {
            color: green;
        }

        .info {
            font-size: 14px;
            color: #333;
        }

        .info p {
            margin: 5px 0;
        }

        .info .label {
            font-weight: bold;
        }

        .info .value {
            color: #555;
        }

        .info .highlight {
            color: #000;
        }

        .info .highlight-blue {
            color: #0000ff;
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="header">
            <img alt="Government Logo" height="100" src="https://gisa.dukcapil.kemendagri.go.id/widget/v1/login/images/logo-dirjen-dukcapil.jpg" width="100" />
            <div>
                <span>DIREKTORAT JENDERAL KEPENDUDUKAN DAN PENCATATAN SIPIL</span>
                <span>KEMENTERIAN DALAM NEGERI REPUBLIK INDONESIA</span>
            </div>
        </div>

        <div class="status">
            <img alt="Document Status Icon" height="100" src="https://storage.googleapis.com/a1aa/image/QZyfs5AFIfjUlE4y2DfOeVw9ZevnaSGDeZsXceLWHE6fCfiQnA.jpg" width="100" />
            <p class="label">Status dokumen</p>
            <p class="active">AKTIF</p>
        </div>

        <div class="info">
            <p>
                <span class="label">Nama Lengkap</span> <br />
                <span class="value">ROCHMAD</span>
            </p>
            <p>
                <span class="label">Tanggal Kematian</span> <br />
                <span class="value">14-01-2015</span>
            </p>
            <p>
                <span class="label">No. Akta</span> <br />
                <span class="highlight">3604-KM-26022020-0***</span>
            </p>
            <p class="highlight-blue">Info Penandatangan</p>
            <p>
                <span class="label">Daerah</span> <br />
                <span class="value">Pemerintah Kabupaten Serang</span>
            </p>
            <p>
                <span class="label">Lembaga</span> <br />
                <span class="value">DUKCAPIL</span>
            </p>
            <p>
                <span class="label">Penandatangan</span> <br />
                <span class="value">Abdullah</span>
            </p>
        </div>
    </div>
</body>

</html>
