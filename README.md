<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Đặc sản Bến Tre</title>
    <style>
        body {

            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: #f9f9f9;
            color: #333; 
            background: linear-gradient(to bottom right, #b2fab4, #006400); /* Chuyển màu nền từ xanh nhạt đến xanh đậm */
            background-attachment: fixed; /* Cố định nền khi cuộn trang */
        }

        .header {
            position:relative; 
            background-image: url('https://imgcdn.tapchicongthuong.vn/tcct-media/24/5/6/xu-dua_663884786e5fe.jpg'); /* Thay bằng đường dẫn ảnh phù hợp */
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: left;
            color: yellow;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }

        .header h1 {
            font-size: 3em;
            margin: 0;
            align-items: center;
            text-align: center;
        }

        .header p {
            font-size: 1.5em;
            margin: 10px 0;
        }

        .content {
            max-width: 1000px;
            margin: 20px auto;
            padding: 20px;
            background: green;
            background: rgba(255, 255, 255, 0.8); /* Màu trắng trong suốt để làm nổi nội dung */
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            position: relative;
            z-index: 1;
        }

        .dish {
            display: flex;
            margin-bottom: 20px;
            gap: 20px;
            border-radius: 10px; /* Bo góc của khung */
            background-color: #f0f8ff; /* Màu nền khung */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Tạo bóng cho khung */
        }

        .dish img {
            width: 150px;
            height: 150px;
            border-radius: 10px;
            object-fit: cover;
        }
        
        .image-container {
            width: 200px;
            height: 150px; 
            position: relative;
        } 

        .image-container img {
            width: 95%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.3s ease; /* Hiệu ứng chuyển động */
    } 

        .image-container:hover img {
            transform: scale(1.25); /* Phóng to ảnh khi hover */
    } 
        .dish-info {
            flex: 1;
            padding: 10px;
            background-color: #ffffff; /* Màu nền cho văn bản */
            border-radius: 0 10px 10px 0; /* Bo góc phía bên phải */
            box-shadow: inset 0 0 10px rgba(0, 0, 0, 0.1); /* Hiệu ứng đổ bóng bên trong */
        }

        .dish-info h3 {
            margin: 0 0 10px;
            color: #006400;
        }

        .dish-info p { 
            margin: 0;
        }

        .footer {
            background-color: linear-gradient(to right, #006400, #b2fab4);
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }

        .group-label {
            position: absolute;
            top: 5px;
            left: 10px;
            font-size: 0.4em;
            font-weight: bold;
            color: white;
            border-radius: 8px;
            z-index: 1000; /* Đảm bảo hiện lên trên */
            line-height: 1.5;
            text-align: left;
        }

        .group-label p {
            margin: 0;
            font-weight: normal; 
        }

    </style>
</head>
<body>
    <div class="header">
        <div class="group-label">
            <p>Nhóm 8:</p>
            <p>Bùi Phúc Hậu</p>
            <p>Trần Minh Phi</p>
            <p>Đỗ Thúy Ngân</p>
            <p>La Thị Cẩm Tú</p>
        </div> 
        <h1><center>Đặc Sản Bến Tre - Quê hương Xứ Dừa</center></h1>
    </div> 
    <div class="content">
        <div class="dish">
            <div class="image-container">
                <img src="https://huongvietmart.vn/wp-content/uploads/2022/06/thuyet-minh-ve-keo-dua-ben-tre-2.jpg" alt="Kẹo ">
            </div>
            <div class="dish-info">
                <h3> 1. Kẹo dừa</h3>  
                <p>Đây là loại kẹo đặc sản và là một nghề thủ công truyền thống mang đậm văn hóa xứ sở.</p>
            </div>
        </div>

        <div class="dish">
            <div class="image-container">
                <img src="https://huongvique.vn/wp-content/uploads/2022/05/banh-trang-dua-my-long-me-den-2.jpg" alt="Bánh tráng Mỹ Lồng">
            </div>
            <div class="dish-info">
                <h3>2. Bánh tráng Mỹ Lồng</h3> 
                <p>Đặc sản nổi tiếng vừa béo vừa xốp, đặt lên lò than tỏa hương thơm. Có ba loại bánh tráng, đó là: bánh đặc biệt có sữa, trứng gà, dừa; bánh có dừa không sữa; bánh có sữa không dừa...</p>
            </div>
        </div>

        <div class="dish">
            <div class="image-container">
                <img src="https://mia.vn/media/uploads/blog-du-lich/banh-phong-son-doc-dac-san-danh-bat-hu-truyen-cua-tinh-ben-tre-1-1666020908.jpg" alt="Bánh phồng Sơn Đốc">
            </div>
            <div class="dish-info">
                <h3>3. Bánh phồng Sơn Đốc</h3> 
                <p>Đây là một loại bánh phồng, có xuất xứ từ xã Hưng Nhượng, huyện Giồng Trôm, tỉnh Bến Tre. Nghề làm bánh phồng Sơn Đốc đã được xếp hạng Di sản văn hóa phi vật thể quốc gia vào năm 2018.</p>
            </div>
        </div>

        <div class="dish">
            <div class="image-container">
                <img src="https://cuhudua.com/public/upload/images/goi-cu-hu-dua-tom-thit(1).jpg" alt="Gỏi củ hủ dừa tôm thịt">
            </div>
            <div class="dish-info">
                <h3>4. Gỏi củ hủ dừa tôm thịt</h3>
                <p>Món gỏi củ hủ dừa tôm thịt thường được dùng làm món khai vị với vị chua ngọt đậm đà và độ giòn ngon của món gỏi này.</p>
            </div>
        </div>

        <div class="dish">
            <div class="image-container">
                <img src="https://reviewvilla.vn/wp-content/uploads/2024/06/Banh-dua-ben-tre-12.jpg" alt="Bánh dừa Giồng Luông">
            </div>
            <div class="dish-info">
                <h3>5. Bánh dừa Giồng Luông</h3> 
                <p>Đây  món ăn đặc sản đã gắn liền với biết bao thế hệ người dân Bến Tre. Món này xuất phát từ huyện Đồng Khởi và đã được lưu truyền qua nhiều thế hệ. Món bánh dân dã làm rất đơn giản, từng chiếc bánh nhỏ chỉ bằng hai ngón tay người lớn nhưng lại mang phong vị riêng của mảnh đất Tây Nam Bộ.</p>
            </div>
        </div>

        <div class="dish">
            <div class="image-container">
                <img src="https://setechvn.com/wp-content/uploads/2024/12/5.png" alt="Mứt dừa">
            </div>
            <div class="dish-info">
                <h3>6. Mứt dừa</h3> 
                <p>Mứt dừa Bến Tre không chỉ là món ăn ngon miệng mà còn mang trong mình nhiều giá trị văn hóa của người dân nơi đây.</p>
            </div>
        </div>

        <div class="dish">
            <div class="image-container">
                <img src="https://mia.vn/media/uploads/blog-du-lich/thuong-thuc-com-dua-ben-tre-mon-an-dan-da-voi-huong-vi-ngon-me-ly-01-1664718874.jpeg" alt="Cơm dừa">
            </div>
            <div class="dish-info">
                <h3>7. Cơm dừa</h3>  
                <p>Cơm dừa từ lâu được biết đến là món đặc sản của xứ dừa Bến Tre không chỉ bởi hương vị thơm ngon mà còn là nét độc đáo của nó mang lại. Món ăn này tuy dân dã, bình dị, nhưng để nấu được món cơm dừa ngon đúng điệu thì đòi hỏi công đoạn chế biến phải rất tỉ mỉ.</p>
            </div>
        </div>

        <div class="dish">
            <div class="image-container">
                <img src="https://baodongnai.com.vn/file/e7837c02876411cd0187645a2551379f/dataimages/202201/original/images2426627_11e.jpg" alt="Bánh xèo ốc gạo">
            </div>
            <div class="dish-info">
                <h3>8. Bánh xèo ốc gạo</h3> 
                <p>Bánh xèo ốc gạo là món ăn dân dã ưa thích của người dân cồn Phú Đa (huyện Chợ Lách, tỉnh Bến Tre), đặc biệt là vào dịp tết Đoan Ngọ (tức ngày mùng 5 tháng 5 âm lịch). </p>
            </div>
        </div>

        <div class="dish">
            <div class="image-container">
                <img src="https://luhanhvietnam.com.vn/du-lich/vnt_upload/news/12_2022/soi-banh-canh-xat-ra_1.jpg" alt="Bánh canh bột xắt">
            </div>
            <div class="dish-info">
                <h3>9. Bánh canh bột xắt</h3> 
                <p>Bánh canh bột xắt Bến Tre chủ yếu làm bằng phương pháp thủ công đòi hỏi tay nghề khéo léo của người thợ nên sở hữu hương vị đặc biệt cuốn hút.</p>
            </div>
        </div>

        <div class="dish">
            <div class="image-container">
                <img src="https://ttol.vietnamnetjsc.vn/images/2020/09/08/07/01/ca-bong-kho-1.jpg" alt="Cá bống kho dừa">
            </div> 
            <div class="dish-info">
                <h3>10. Cá bống kho dừa</h3>  
                <p>Món cá bống dừa kho nước dừa với mùi vị thơm lừng, thịt cá săn chắc, màu đẹp, ăn lại ngon, không có mùi tanh của cá. Món ăn sẽ càng thêm ngon khi ăn kèm với các loại rau vườn như: kèo nèo, bông súng, đậu rồng… để chấm với nước cá, ngon, chân chất dân dã, đậm đà, khó quên.</p>
            </div>
        </div>
    </div>

    <div class="footer">
        <p>&copy; 12A1 - Nhóm 8</p>  
    </div>
</body>
</html>
