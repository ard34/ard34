<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Data Produk</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        .action-buttons {
            display: flex;
            gap: 10px;
        }
        .edit-button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 5px 10px;
            cursor: pointer;
            border-radius: 3px;
        }
        .delete-button {
            background-color: #f44336;
            color: white;
            border: none;
            padding: 5px 10px;
            cursor: pointer;
            border-radius: 3px;
        }
    </style>
</head>
<body>
    <h1>Data Produk</h1>
    <table>
        <thead>
            <tr>
                <th>No</th>
                <th>Produk</th>
                <th>Deskripsi</th>
                <th>Harga Beli</th>
                <th>Harga Jual</th>
                <th>Action</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Qtela</td>
                <td>MAkanan Ringan</td>
                <td>Rp 1.700</td>
                <td>Rp 2.000</td>
                <td>
                    <div class="action-buttons">
                        <button class="edit-button">Edit</button>
                        <button class="delete-button">Hapus</button>
                    </div>
                </td>
            </tr>
            <tr>
                <td>2</td>
                <td>Indomie</td>
                <td>Mie instan</td>
                <td>Rp 2.300</td>
                <td>Rp 3.000</td>
                <td>
                    <div class="action-buttons">
                        <button class="edit-button">Edit</button>
                        <button class="delete-button">Hapus</button>
                    </div>
                </td>
            </tr>
            <td>2</td>
                <td>MIe Sedap</td>
                <td>Mie instan</td>
                <td>Rp 2.500</td>
                <td>Rp 3.000</td>
                <td>
                    <div class="action-buttons">
                        <button class="edit-button">Edit</button>
                        <button class="delete-button">Hapus</button>
                    </div>
                </td>
            </tr>
            <!-- Tambahkan baris produk lainnya sesuai kebutuhan -->
        </tbody>
    </table>
</body>
</html>


