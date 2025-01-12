<!DOCTYPE html>
<html>
<head>
    <title>Đơn Cam Kết</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: "Times New Roman", serif;
            font-size: 16px;
            line-height: 1.5;
            margin: 20px;
            background-color: #fff; /* Nên để nền trắng cho dễ đọc trên di động */
            color: #000;
        }

        .header {
            text-align: center;
            margin-bottom: 20px;
        }

        .header p {
            margin: 5px 0;
        }

        .indented {
            margin-left: 40px;
        }

        h1 {
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 20px;
        }

        .content {
            text-align: justify;
        }

        .content p {
            margin-bottom: 10px;
        }

        .commitment-list {
            list-style: none;
            padding: 0;
            margin-left: 20px; /* Giảm thụt lề trên di động */
            text-align: left;
        }

        .commitment-list li {
            margin-bottom: 5px;
        }

        .signature {
            text-align: right;
            margin-top: 30px;
        }

        .signature p {
            margin: 5px 0;
        }

        .signature i {
            display: block;
            text-align: center;
        }

        /* Media query cho màn hình nhỏ (điện thoại) */
        @media (max-width: 768px) {
            body {
                font-size: 14px; /* Giảm kích thước chữ trên di động */
                margin: 10px; /* Giảm margin trên di động */
            }

            .content {
                margin-left: 20px; /* Giảm lề trái */
                margin-right: 20px; /* Giảm lề phải */
            }

            .commitment-list {
                margin-left: 10px;
            }

            .signature {
                margin-right: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <p>CỘNG HÒA XÃ HỘI CHỦ NGHĨA VIỆT NAM</p>
        <p class="indented">Độc lập - Tự do - Hạnh phúc</p>
    </div>

    <h1>ĐƠN CAM KẾT</h1>

    <div class="content">
        <p><strong>Tôi:</strong> Hoàng Văn Giang</p>
        <p><strong>Ngày tháng năm sinh:</strong> 22/07/2006</p>
        <p><strong>Lí do:</strong> Ghi đơn này, tôi hứa sẽ mãi yêu bé: Phạm Tuyết Mai.</p>
        <p><strong>Ngày tháng năm:</strong> 12/04/2007</p>
        <ul class="commitment-list">
            <li>Tôi xin thề sẽ không làm em thất vọng.</li>
            <li>Yêu em nhất ❤️</li>
        </ul>
        <p><strong>Người viết đơn:</strong></p>
        <div class="signature">
                 <p>Giang</p>
            <p>Hoàng Văn Giang</p>
        </div>
    </div>
</body>
</html>
