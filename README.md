# peta-jalur-belanda-indonesia
Website interaktif yang menampilkan peta dan jalur masuknya bangsa Belanda ke Indonesia.

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Peta Jalur Pelayaran Bangsa Belanda ke Indonesia</title>

    <!-- Leaflet CSS -->
    <link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #111827;
            color: #f3f4f6;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            background: linear-gradient(135deg, #1e293b, #0f172a);
            text-align: center;
            padding: 20px;
            border-bottom: 2px solid #f97316;
        }

        header h1 {
            font-size: 1.8rem;
            color: #f97316;
            margin-bottom: 5px;
        }
