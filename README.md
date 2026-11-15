<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ TRUNG MỪNG - trungmung.com | Vật Liệu Xây Dựng Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ TRUNG MỪNG (trungmung.com) chuyên cung cấp Gạch men, Sơn nước, Sen vòi thiết bị vệ sinh, Cát sạn xi măng, San lấp mặt bằng tại 381 Nguyễn Phước Nguyên - 373 Nguyễn Đình Tựu, Thanh Khê, Đà Nẵng. Hotline: 0905182455 - 0905432455.">
    
    <!-- Open Graph Thumbnail là Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://trungmung.com/">
    <meta property="og:title" content="CÔNG TY TNHH TM & DV TRUNG MỪNG - Vật Liệu Xây Dựng Đà Nẵng | trungmung.com">
    <meta property="og:description" content="Chuyên cung cấp: Gạch men, Sơn nước, Sen vòi thiết bị vệ sinh, Cát sạn xi măng, San lấp mặt bằng uy tín tại Đà Nẵng. Đ/c: 381 Nguyễn Phước Nguyên - 373 Nguyễn Đình Tựu, Thanh Khê, Đà Nẵng.">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61&sz=w1200">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61&sz=w1200">

    <!-- Favicon đồng bộ màu Logo -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='18' fill='%230c4a6e'/%3E%3Cpath d='M20 75 L50 22 L80 75 Z' fill='%23ea580c'/%3E%3Cpath d='M35 75 L50 45 L65 75 Z' fill='%23ffffff'/%3E%3C/svg%3E">

    <!-- Tailwind CSS & Font Awesome & Google Fonts -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            blue: '#0c4a6e',      /* Màu xanh đậm chủ đạo theo logo VLXD */
                            blueLight: '#0284c7', /* Màu xanh sáng điểm nhấn */
                            orange: '#ea580c',    /* Màu cam gạch/xây dựng theo logo */
                            orangeHover: '#c2410c',
                            bg: '#f8fafc'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f4f6f8;
            color: #1e293b;
            -webkit-text-size-adjust: 100%;
        }

        /* Khung giao diện chuẩn 95% chiều ngang màn hình máy tính, trên điện thoại gọn gàng 100% */
        .flatsome-container {
            width: 100%;
            padding-left: 10px;
            padding-right: 10px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không bao giờ tự gãy dòng tên danh mục */
        .nav-cat-item {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
            flex-shrink: 0;
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title Normal / Center) */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            margin-bottom: 16px;
            position: relative;
        }
        .flatsome-section-title-main {
            background-color: #0c4a6e;
            color: #ffffff;
            padding: 8px 16px;
            font-weight: 700;
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 0.3px;
            border-top-left-radius: 6px;
            border-top-right-radius: 6px;
            position: relative;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }
        @media (min-width: 768px) {
            .flatsome-section-title-main {
                font-size: 15px;
                padding: 9px 20px;
            }
        }

        /* Nhãn giảm giá % chuẩn Flatsome ở góc trên bên trái khung ảnh sản phẩm */
        .flatsome-sale-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background-color: #ea580c;
            color: #ffffff;
            font-weight: 700;
            font-size: 11px;
            line-height: 1;
            padding: 5px 7px;
            border-radius: 50px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.18);
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị tràn ra ngoài hoặc mất chữ */
        .product-title-flatsome {
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            line-height: 1.38;
            min-height: 2.76em;
            display: block;
        }

        /* Nút liên hệ nổi bật có hiệu ứng nhịp đập */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(234, 88, 12, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(234, 88, 12, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(234, 88, 12, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="flex flex-col min-h-screen">

    <!-- ================= TOP BAR ĐƠN GIẢN CHUẨN FLATSOME (KHÔNG CÓ THANH UX BUILDER) ================= -->
    <div class="bg-brand-blue text-white text-xs py-1.5 border-b border-sky-800">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 truncate">
                <span class="inline-flex items-center gap-1.5 font-medium">
                    <i class="fa-solid fa-building text-amber-400"></i>
                    <span>CÔNG TY TNHH TM & DV TRUNG MỪNG - <strong>trungmung.com</strong></span>
                </span>
                <span class="hidden md:inline-block text-sky-300">|</span>
                <span class="hidden md:inline-flex items-center gap-1 text-sky-100">
                    <i class="fa-solid fa-location-dot text-amber-400"></i>
                    381 Nguyễn Phước Nguyên - 373 Nguyễn Đình Tựu, Thanh Khê, Đà Nẵng
                </span>
            </div>
            <div class="hidden sm:flex items-center gap-4 text-sky-100 shrink-0">
                <span><i class="fa-regular fa-clock text-amber-400 mr-1"></i>Mở cửa: 06:30 - 18:30 (T2 - CN)</span>
                <span><i class="fa-solid fa-phone-volume text-amber-400 mr-1"></i>0905.182.455 - 0905.432.455</span>
            </div>
        </div>
    </div>

    <!-- ================= HEADER CHÍNH (LOGO NHỎ GỌN, KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ================= -->
    <header class="bg-white shadow-sm sticky top-0 z-40">
        <div class="flatsome-container py-2.5">
            <div class="flex items-center justify-between gap-3">
                
                <!-- Nút Menu Danh Mục trên Mobile -->
                <button id="mobileMenuBtn" onclick="toggleMobileMenu()" class="lg:hidden p-2 rounded-md border border-slate-200 text-brand-blue hover:bg-slate-50 shrink-0" aria-label="Mở danh mục">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>

                <!-- Logo Vật Liệu Xây Dựng Chuyên Nghiệp - Chỉnh Gọn Nhỏ Lại -->
                <a href="#" class="flex items-center gap-2.5 shrink-0 group">
                    <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg bg-brand-blue flex items-center justify-center shadow-sm border border-sky-800 shrink-0 relative overflow-hidden">
                        <!-- Biểu tượng SVG Vật liệu xây dựng + Ngôi nhà + Gạch men & Sơn -->
                        <svg class="w-7 h-7" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M8 30L32 10L56 30V54H8V30Z" fill="#0284c7" fill-opacity="0.25"/>
                            <path d="M6 31L32 9L58 31" stroke="#ea580c" stroke-width="5" stroke-linecap="round" stroke-linejoin="round"/>
                            <rect x="16" y="31" width="14" height="10" rx="1.5" fill="#ffffff"/>
                            <rect x="34" y="31" width="14" height="10" rx="1.5" fill="#ea580c"/>
                            <rect x="16" y="44" width="14" height="10" rx="1.5" fill="#ea580c"/>
                            <rect x="34" y="44" width="14" height="10" rx="1.5" fill="#ffffff"/>
                        </svg>
                    </div>
                    <div class="leading-tight">
                        <div class="text-xs sm:text-sm md:text-base font-extrabold text-brand-blue tracking-tight">
                            TRUNG MỪNG <span class="text-brand-orange">VLXD</span>
                        </div>
                        <div class="text-[10px] sm:text-[11px] font-semibold text-slate-500">
                            trungmung.com • Đà Nẵng
                        </div>
                    </div>
                </a>

                <!-- Thanh tìm kiếm sản phẩm (Giống Flatsome) -->
                <div class="hidden md:flex flex-1 max-w-xl mx-4">
                    <div class="relative flex w-full">
                        <select id="searchCategorySelect" onchange="filterProductsByCategory(this.value)" class="bg-slate-100 border border-r-0 border-slate-300 text-slate-700 text-xs font-medium px-3 py-2 rounded-l-md focus:outline-none">
                            <option value="all">Tất cả danh mục</option>
                            <option value="gach-men">Gạch men ốp lát</option>
                            <option value="son-nuoc">Sơn nước & Chống thấm</option>
                            <option value="sen-voi">Sen vòi & Thiết bị vệ sinh</option>
                            <option value="cat-san-xi-mang">Cát sạn - Đá - Xi măng</option>
                            <option value="san-lap">San lấp mặt bằng & Vật tư phụ</option>
                        </select>
                        <input id="searchInputDesktop" type="text" oninput="searchProducts(this.value)" placeholder="Tìm gạch men, sơn Jotun, Dulux, sen vòi, xi măng, cát đá..." class="w-full border border-slate-300 px-3 py-2 text-xs sm:text-sm focus:outline-none focus:border-brand-blue">
                        <button onclick="searchProducts(document.getElementById('searchInputDesktop').value)" class="bg-brand-orange hover:bg-brand-orangeHover text-white px-4 py-2 rounded-r-md text-sm font-semibold transition">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </div>
                </div>

                <!-- Liên kết điều hướng nhanh gọn (Không để nút gọi ngay để tránh tràn viền) -->
                <div class="flex items-center gap-2 sm:gap-3 shrink-0">
                    <a href="#form-bao-gia" class="inline-flex items-center gap-1.5 bg-slate-100 hover:bg-brand-blue hover:text-white text-brand-blue text-xs font-semibold px-2.5 py-2 rounded-md transition border border-slate-200">
                        <i class="fa-solid fa-file-invoice-dollar text-brand-orange"></i>
                        <span>Nhận Báo Giá</span>
                    </a>
                    <a href="#ban-do-cua-hang" class="hidden sm:inline-flex items-center gap-1.5 bg-slate-100 hover:bg-brand-blue hover:text-white text-slate-700 text-xs font-semibold px-2.5 py-2 rounded-md transition border border-slate-200">
                        <i class="fa-solid fa-map-location-dot text-brand-blue"></i>
                        <span>Chỉ Đường</span>
                    </a>
                </div>
            </div>

            <!-- Thanh tìm kiếm trên điện thoại -->
            <div class="mt-2 md:hidden">
                <div class="flex w-full">
                    <input id="searchInputMobile" type="text" oninput="searchProducts(this.value)" placeholder="Tìm gạch men, sơn nước, sen vòi, cát xi măng..." class="w-full border border-slate-300 rounded-l-md px-3 py-1.5 text-xs focus:outline-none focus:border-brand-blue">
                    <button onclick="searchProducts(document.getElementById('searchInputMobile').value)" class="bg-brand-orange text-white px-3.5 py-1.5 rounded-r-md text-xs">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- ================= THANH DANH MỤC TRÊN MÁY TÍNH (CHỮ NHỎ GỌN, VIẾT LIỀN TRÊN 1 HÀNG HOẶC XUỐNG HÀNG 2, KHÔNG GÃY DÒNG TÊN DANH MỤC) ================= -->
        <nav class="bg-brand-blue text-white border-t border-sky-800 hidden lg:block">
            <div class="flatsome-container">
                <ul class="flex flex-wrap items-center gap-x-1 gap-y-1 py-1 text-[12px] font-semibold">
                    <li>
                        <a href="#tat-ca-san-pham" onclick="filterProductsByCategory('all')" class="nav-cat-item bg-brand-orange text-white px-3 py-1.5 rounded hover:bg-brand-orangeHover transition">
                            <i class="fa-solid fa-bars-staggered mr-1.5"></i>DANH MỤC SẢN PHẨM
                        </a>
                    </li>
                    <li>
                        <a href="#" onclick="filterProductsByCategory('all')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-sky-800 transition">
                            TRANG CHỦ
                        </a>
                    </li>
                    <li>
                        <a href="#sec-gach-men" onclick="filterProductsByCategory('gach-men')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-sky-800 transition">
                            GẠCH MEN ỐP LÁT
                        </a>
                    </li>
                    <li>
                        <a href="#sec-son-nuoc" onclick="filterProductsByCategory('son-nuoc')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-sky-800 transition">
                            SƠN JOTUN
                        </a>
                    </li>
                    <li>
                        <a href="#sec-son-nuoc" onclick="filterProductsByCategory('son-nuoc')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-sky-800 transition">
                            SƠN DULUX
                        </a>
                    </li>
                    <li>
                        <a href="#sec-son-nuoc" onclick="filterProductsByCategory('son-nuoc')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-sky-800 transition">
                            SƠN MAXILITE
                        </a>
                    </li>
                    <li>
                        <a href="#sec-son-nuoc" onclick="filterProductsByCategory('son-nuoc')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-sky-800 transition">
                            SƠN CHỐNG THẤM
                        </a>
                    </li>
                    <li>
                        <a href="#sec-sen-voi" onclick="filterProductsByCategory('sen-voi')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-sky-800 transition">
                            SEN VÒI & THIẾT BỊ VỆ SINH
                        </a>
                    </li>
                    <li>
                        <a href="#sec-cat-xi-mang" onclick="filterProductsByCategory('cat-san-xi-mang')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-sky-800 transition">
                            CÁT - ĐÁ - XI MĂNG
                        </a>
                    </li>
                    <li>
                        <a href="#sec-san-lap" onclick="filterProductsByCategory('san-lap')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-sky-800 transition">
                            SAN LẤP MẶT BẰNG
                        </a>
                    </li>
                    <li>
                        <a href="#sec-san-lap" onclick="filterProductsByCategory('san-lap')" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-sky-800 transition">
                            VẬT TƯ PHỤ
                        </a>
                    </li>
                    <li>
                        <a href="#tin-tuc-xay-dung" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-sky-800 transition">
                            TIN TỨC
                        </a>
                    </li>
                    <li>
                        <a href="#ban-do-cua-hang" class="nav-cat-item px-2.5 py-1.5 rounded hover:bg-sky-800 transition">
                            LIÊN HỆ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Menu Danh Mục Mở Rộng Trên Điện Thoại -->
        <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="flatsome-container py-3">
                <div class="text-xs font-bold uppercase text-brand-blue mb-2 px-1">Danh mục sản phẩm (trungmung.com)</div>
                <div class="grid grid-cols-2 gap-1.5 text-xs font-medium">
                    <a href="#sec-gach-men" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-sky-50 text-slate-800 flex items-center gap-2">
                        <i class="fa-solid fa-border-all text-brand-orange"></i><span>Gạch Men Ốp Lát</span>
                    </a>
                    <a href="#sec-son-nuoc" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-sky-50 text-slate-800 flex items-center gap-2">
                        <i class="fa-solid fa-fill-drip text-brand-blue"></i><span>Sơn Nước Jotun/Dulux</span>
                    </a>
                    <a href="#sec-son-nuoc" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-sky-50 text-slate-800 flex items-center gap-2">
                        <i class="fa-solid fa-shield-halved text-brand-orange"></i><span>Sơn Chống Thấm</span>
                    </a>
                    <a href="#sec-sen-voi" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-sky-50 text-slate-800 flex items-center gap-2">
                        <i class="fa-solid fa-shower text-brand-blue"></i><span>Sen Vòi & TB Vệ Sinh</span>
                    </a>
                    <a href="#sec-cat-xi-mang" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-sky-50 text-slate-800 flex items-center gap-2">
                        <i class="fa-solid fa-cubes text-brand-orange"></i><span>Cát - Đá - Xi Măng</span>
                    </a>
                    <a href="#sec-san-lap" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-sky-50 text-slate-800 flex items-center gap-2">
                        <i class="fa-solid fa-truck-monster text-brand-blue"></i><span>San Lấp Mặt Bằng</span>
                    </a>
                    <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-sky-50 text-slate-800 flex items-center gap-2">
                        <i class="fa-solid fa-file-signature text-brand-orange"></i><span>Yêu Cầu Báo Giá</span>
                    </a>
                    <a href="#ban-do-cua-hang" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-sky-50 text-slate-800 flex items-center gap-2">
                        <i class="fa-solid fa-map-pin text-brand-blue"></i><span>Bản Đồ & Liên Hệ</span>
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- ================= MAIN CONTENT ================= -->
    <main class="flex-1 py-4 space-y-6">

        <!-- 1. HAI ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU (CHỮ NẰM TRONG HẾT BANNER, CÁCH XA VIỀN, KHÔNG BỊ THIẾU CHỮ TRÊN ĐIỆN THOẠI & MÁY TÍNH) -->
        <section class="flatsome-container">
            <div class="relative w-full h-[250px] sm:h-[310px] md:h-[370px] rounded-xl overflow-hidden shadow-md bg-brand-blue">
                
                <!-- Slide 1 -->
                <div id="bannerSlide0" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                    <!-- Nền gradient + Ảnh cửa hàng thực tế làm nền mờ sang trọng -->
                    <div class="absolute inset-0 bg-gradient-to-r from-[#082f49] via-[#0c4a6e]/95 to-[#0c4a6e]/80 z-10"></div>
                    <img src="https://drive.google.com/thumbnail?id=1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61&sz=w1200" 
                         onerror="handleDriveImageError(this, '1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61')"
                         alt="Cửa hàng VLXD Trung Mừng" 
                         class="absolute inset-0 w-full h-full object-cover opacity-35">
                    
                    <!-- Nội dung chữ & ảnh nằm gọn hoàn toàn bên trong, cách xa viền banner (px-8 sm:px-14 md:px-20) -->
                    <div class="relative z-20 w-full h-full flex items-center justify-between px-8 py-5 sm:px-14 sm:py-8 md:px-20 md:py-10">
                        <div class="w-full md:w-7/12 text-white space-y-2 sm:space-y-3">
                            <div class="inline-block bg-brand-orange text-white text-[10px] sm:text-xs font-bold px-2.5 py-1 rounded uppercase tracking-wider">
                                CÔNG TY TNHH TM & DV TRUNG MỪNG • TRUNGMUNG.COM
                            </div>
                            <h1 class="text-sm sm:text-xl md:text-2xl lg:text-3xl font-extrabold leading-snug text-white">
                                TỔNG KHO GẠCH MEN - SƠN NƯỚC - SEN VÒI & THIẾT BỊ VỆ SINH ĐÀ NẴNG
                            </h1>
                            <p class="text-[11px] sm:text-xs md:text-sm text-sky-100 leading-relaxed">
                                Phân phối chính hãng Gạch men cao cấp, Sơn Jotun - Dulux - Maxilite, Sen vòi Inax - Viglacera. Giao hàng tận công trình nhanh chóng, chiết khấu cao.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-2 text-[11px] sm:text-xs font-semibold text-amber-300">
                                <span><i class="fa-solid fa-location-dot mr-1"></i>381 Nguyễn Phước Nguyên - 373 Nguyễn Đình Tựu, Thanh Khê</span>
                                <span class="hidden sm:inline">•</span>
                                <span><i class="fa-solid fa-phone mr-1"></i>0905.182.455 - 0905.432.455</span>
                            </div>
                        </div>

                        <!-- Khung ảnh sản phẩm thực tế nằm gọn bên trong phải của Banner trên máy tính -->
                        <div class="hidden md:grid grid-cols-2 gap-2.5 w-4/12 max-w-[300px] p-2 bg-white/10 backdrop-blur-sm rounded-lg border border-white/20">
                            <img src="https://drive.google.com/thumbnail?id=1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY&sz=w400" 
                                 onerror="handleDriveImageError(this, '1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY')"
                                 alt="Gạch men Trung Mừng" class="w-full h-24 object-cover rounded">
                            <img src="https://drive.google.com/thumbnail?id=11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP&sz=w400" 
                                 onerror="handleDriveImageError(this, '11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP')"
                                 alt="Sơn nước Trung Mừng" class="w-full h-24 object-cover rounded">
                            <img src="https://drive.google.com/thumbnail?id=1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr&sz=w400" 
                                 onerror="handleDriveImageError(this, '1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr')"
                                 alt="Sen vòi TBVS Trung Mừng" class="w-full h-24 object-cover rounded">
                            <img src="https://drive.google.com/thumbnail?id=1X31hmhpLVVORV-tmMSZYzBO-qtpyusry&sz=w400" 
                                 onerror="handleDriveImageError(this, '1X31hmhpLVVORV-tmMSZYzBO-qtpyusry')"
                                 alt="Vật liệu xây dựng Trung Mừng" class="w-full h-24 object-cover rounded">
                        </div>
                    </div>
                </div>

                <!-- Slide 2 (Kích thước bằng nhau tuyệt đối với Slide 1) -->
                <div id="bannerSlide1" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                    <div class="absolute inset-0 bg-gradient-to-r from-[#1e293b] via-[#0c4a6e]/95 to-[#9a3412]/90 z-10"></div>
                    <img src="https://drive.google.com/thumbnail?id=171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O&sz=w1200" 
                         onerror="handleDriveImageError(this, '171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O')"
                         alt="Cát sạn xi măng và San lấp mặt bằng" 
                         class="absolute inset-0 w-full h-full object-cover opacity-30">
                    
                    <!-- Nội dung chữ & ảnh nằm gọn hoàn toàn bên trong, cách xa viền banner (px-8 sm:px-14 md:px-20) -->
                    <div class="relative z-20 w-full h-full flex items-center justify-between px-8 py-5 sm:px-14 sm:py-8 md:px-20 md:py-10">
                        <div class="w-full md:w-7/12 text-white space-y-2 sm:space-y-3">
                            <div class="inline-block bg-amber-500 text-slate-950 text-[10px] sm:text-xs font-extrabold px-2.5 py-1 rounded uppercase tracking-wider">
                                CUNG ỨNG VLXD & CƠ GIỚI CHUYÊN NGHIỆP • TRUNGMUNG.COM
                            </div>
                            <h2 class="text-sm sm:text-xl md:text-2xl lg:text-3xl font-extrabold leading-snug text-white">
                                CUNG CẤP CÁT SẠN XI MĂNG & DỊCH VỤ SAN LẤP MẶT BẰNG TRỌN GÓI
                            </h2>
                            <p class="text-[11px] sm:text-xs md:text-sm text-slate-100 leading-relaxed">
                                Chuyên Cát xây tô, Đá 1x2 - 2x4 - 4x6, Xi măng Đồng Lâm - Kim Đỉnh - Sông Gianh, San lấp mặt bằng, vận chuyển xà bần uy tín đúng tiến độ tại Đà Nẵng.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-2 text-[11px] sm:text-xs font-semibold text-amber-300">
                                <span><i class="fa-solid fa-truck-fast mr-1"></i>Đội xe ben & cơ giới hùng hậu</span>
                                <span class="hidden sm:inline">•</span>
                                <span><i class="fa-solid fa-phone-volume mr-1"></i>Hotline: 0905.182.455 - 0905.432.455</span>
                            </div>
                        </div>

                        <!-- Khung ảnh thực tế bên phải Slide 2 -->
                        <div class="hidden md:grid grid-cols-2 gap-2.5 w-4/12 max-w-[300px] p-2 bg-white/10 backdrop-blur-sm rounded-lg border border-white/20">
                            <img src="https://drive.google.com/thumbnail?id=1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg&sz=w400" 
                                 onerror="handleDriveImageError(this, '1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg')"
                                 alt="Xi măng cát sạn" class="w-full h-24 object-cover rounded">
                            <img src="https://drive.google.com/thumbnail?id=1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4&sz=w400" 
                                 onerror="handleDriveImageError(this, '1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4')"
                                 alt="Vật liệu xây dựng" class="w-full h-24 object-cover rounded">
                            <img src="https://drive.google.com/thumbnail?id=1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54&sz=w400" 
                                 onerror="handleDriveImageError(this, '1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54')"
                                 alt="San lấp mặt bằng" class="w-full h-24 object-cover rounded">
                            <img src="https://drive.google.com/thumbnail?id=1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61&sz=w400" 
                                 onerror="handleDriveImageError(this, '1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61')"
                                 alt="Kho bãi Trung Mừng" class="w-full h-24 object-cover rounded">
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Trái / Phải nằm gọn trong mép banner -->
                <button onclick="prevBanner()" class="absolute left-2 top-1/2 -translate-y-1/2 z-30 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-orange text-white flex items-center justify-center transition" aria-label="Slide trước">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button onclick="nextBanner()" class="absolute right-2 top-1/2 -translate-y-1/2 z-30 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-orange text-white flex items-center justify-center transition" aria-label="Slide tiếp">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Chấm tròn chuyển slide -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-30 flex items-center gap-2">
                    <button id="bannerDot0" onclick="goToBanner(0)" class="w-6 h-2 rounded-full bg-brand-orange transition-all" aria-label="Banner 1"></button>
                    <button id="bannerDot1" onclick="goToBanner(1)" class="w-2.5 h-2 rounded-full bg-white/60 transition-all" aria-label="Banner 2"></button>
                </div>
            </div>
        </section>

        <!-- 2. DANH MỤC SẢN PHẨM TRANG CHỦ (CHỮ DANH MỤC NHỎ GỌN, TỐI ƯU TRÊN ĐIỆN THOẠI & MÁY TÍNH) -->
        <section id="tat-ca-san-pham" class="flatsome-container">
            <div class="bg-white rounded-xl p-3 sm:p-4 shadow-sm border border-slate-200">
                <div class="flex items-center justify-between mb-3 border-b border-slate-100 pb-2">
                    <h2 class="text-xs sm:text-sm font-extrabold uppercase text-brand-blue flex items-center gap-2">
                        <i class="fa-solid fa-layer-group text-brand-orange"></i>
                        <span>DANH MỤC SẢN PHẨM CHÍNH</span>
                    </h2>
                    <button onclick="filterProductsByCategory('all')" class="text-[11px] sm:text-xs font-semibold text-brand-orange hover:underline">
                        Hiển thị tất cả (24)
                    </button>
                </div>

                <!-- Grid Danh mục chữ nhỏ gọn, không gãy dòng tên danh mục -->
                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 lg:grid-cols-9 gap-2">
                    <button onclick="filterProductsByCategory('gach-men')" class="group p-2 rounded-lg border border-slate-200 hover:border-brand-orange bg-slate-50 hover:bg-orange-50/40 transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-brand-blue/10 text-brand-blue group-hover:bg-brand-orange group-hover:text-white flex items-center justify-center mb-1.5 transition">
                            <i class="fa-solid fa-border-all text-sm"></i>
                        </div>
                        <span class="text-[11px] font-bold text-slate-800 whitespace-nowrap overflow-hidden text-ellipsis w-full">Gạch Men</span>
                    </button>

                    <button onclick="filterProductsByCategory('son-nuoc')" class="group p-2 rounded-lg border border-slate-200 hover:border-brand-orange bg-slate-50 hover:bg-orange-50/40 transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-brand-blue/10 text-brand-blue group-hover:bg-brand-orange group-hover:text-white flex items-center justify-center mb-1.5 transition">
                            <i class="fa-solid fa-fill-drip text-sm"></i>
                        </div>
                        <span class="text-[11px] font-bold text-slate-800 whitespace-nowrap overflow-hidden text-ellipsis w-full">Sơn Jotun</span>
                    </button>

                    <button onclick="filterProductsByCategory('son-nuoc')" class="group p-2 rounded-lg border border-slate-200 hover:border-brand-orange bg-slate-50 hover:bg-orange-50/40 transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-brand-blue/10 text-brand-blue group-hover:bg-brand-orange group-hover:text-white flex items-center justify-center mb-1.5 transition">
                            <i class="fa-solid fa-paint-roller text-sm"></i>
                        </div>
                        <span class="text-[11px] font-bold text-slate-800 whitespace-nowrap overflow-hidden text-ellipsis w-full">Sơn Dulux</span>
                    </button>

                    <button onclick="filterProductsByCategory('son-nuoc')" class="group p-2 rounded-lg border border-slate-200 hover:border-brand-orange bg-slate-50 hover:bg-orange-50/40 transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-brand-blue/10 text-brand-blue group-hover:bg-brand-orange group-hover:text-white flex items-center justify-center mb-1.5 transition">
                            <i class="fa-solid fa-brush text-sm"></i>
                        </div>
                        <span class="text-[11px] font-bold text-slate-800 whitespace-nowrap overflow-hidden text-ellipsis w-full">Sơn Maxilite</span>
                    </button>

                    <button onclick="filterProductsByCategory('son-nuoc')" class="group p-2 rounded-lg border border-slate-200 hover:border-brand-orange bg-slate-50 hover:bg-orange-50/40 transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-brand-blue/10 text-brand-blue group-hover:bg-brand-orange group-hover:text-white flex items-center justify-center mb-1.5 transition">
                            <i class="fa-solid fa-shield-halved text-sm"></i>
                        </div>
                        <span class="text-[11px] font-bold text-slate-800 whitespace-nowrap overflow-hidden text-ellipsis w-full">Chống Thấm</span>
                    </button>

                    <button onclick="filterProductsByCategory('sen-voi')" class="group p-2 rounded-lg border border-slate-200 hover:border-brand-orange bg-slate-50 hover:bg-orange-50/40 transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-brand-blue/10 text-brand-blue group-hover:bg-brand-orange group-hover:text-white flex items-center justify-center mb-1.5 transition">
                            <i class="fa-solid fa-shower text-sm"></i>
                        </div>
                        <span class="text-[11px] font-bold text-slate-800 whitespace-nowrap overflow-hidden text-ellipsis w-full">Sen Vòi & TBVS</span>
                    </button>

                    <button onclick="filterProductsByCategory('cat-san-xi-mang')" class="group p-2 rounded-lg border border-slate-200 hover:border-brand-orange bg-slate-50 hover:bg-orange-50/40 transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-brand-blue/10 text-brand-blue group-hover:bg-brand-orange group-hover:text-white flex items-center justify-center mb-1.5 transition">
                            <i class="fa-solid fa-cubes text-sm"></i>
                        </div>
                        <span class="text-[11px] font-bold text-slate-800 whitespace-nowrap overflow-hidden text-ellipsis w-full">Cát Đá Xi Măng</span>
                    </button>

                    <button onclick="filterProductsByCategory('san-lap')" class="group p-2 rounded-lg border border-slate-200 hover:border-brand-orange bg-slate-50 hover:bg-orange-50/40 transition flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-brand-blue/10 text-brand-blue group-hover:bg-brand-orange group-hover:text-white flex items-center justify-center mb-1.5 transition">
                            <i class="fa-solid fa-truck-monster text-sm"></i>
                        </div>
                        <span class="text-[11px] font-bold text-slate-800 whitespace-nowrap overflow-hidden text-ellipsis w-full">San Lấp Mặt Bằng</span>
                    </button>

                    <button onclick="filterProductsByCategory('san-lap')" class="group p-2 rounded-lg border border-slate-200 hover:border-brand-orange bg-slate-50 hover:bg-orange-50/40 transition col-span-2 sm:col-span-1 flex flex-col items-center text-center">
                        <div class="w-9 h-9 rounded-full bg-brand-blue/10 text-brand-blue group-hover:bg-brand-orange group-hover:text-white flex items-center justify-center mb-1.5 transition">
                            <i class="fa-solid fa-screwdriver-wrench text-sm"></i>
                        </div>
                        <span class="text-[11px] font-bold text-slate-800 whitespace-nowrap overflow-hidden text-ellipsis w-full">Vật Tư Phụ</span>
                    </button>
                </div>
            </div>
        </section>

        <!-- ================= CÁC DANH MỤC SẢN PHẨM TRANG CHỦ CHUẨN FLATSOME (CHIA 2 CỘT TRÊN ĐIỆN THOẠI, CÓ % GIẢM GIÁ GÓC TRÊN BÊN TRÁI, KHÔNG NHÃN DÁN RỜM RÀ) ================= -->

        <!-- DANH MỤC 1: GẠCH MEN ỐP LÁT & GẠCH XÂY DỰNG -->
        <section id="sec-gach-men" class="flatsome-container product-section-block" data-cat="gach-men">
            <div class="flatsome-section-title">
                <div class="flatsome-section-title-main">
                    <i class="fa-solid fa-border-all"></i>
                    <span>GẠCH MEN ỐP LÁT & GẠCH XÂY DỰNG</span>
                </div>
                <a href="#form-bao-gia" class="text-xs font-bold text-brand-blue hover:text-brand-orange whitespace-nowrap">
                    Xem thêm <i class="fa-solid fa-angle-right ml-0.5"></i>
                </a>
            </div>
            <!-- Grid 2 cột trên điện thoại (grid-cols-2), 4-5 cột trên máy tính -->
            <div id="grid-gach-men" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5"></div>
        </section>

        <!-- DANH MỤC 2: SƠN NƯỚC (JOTUN - DULUX - MAXILITE) & SƠN CHỐNG THẤM -->
        <section id="sec-son-nuoc" class="flatsome-container product-section-block" data-cat="son-nuoc">
            <div class="flatsome-section-title">
                <div class="flatsome-section-title-main">
                    <i class="fa-solid fa-fill-drip"></i>
                    <span>SƠN NƯỚC (JOTUN • DULUX • MAXILITE) & CHỐNG THẤM</span>
                </div>
                <a href="#form-bao-gia" class="text-xs font-bold text-brand-blue hover:text-brand-orange whitespace-nowrap">
                    Xem thêm <i class="fa-solid fa-angle-right ml-0.5"></i>
                </a>
            </div>
            <div id="grid-son-nuoc" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5"></div>
        </section>

        <!-- DANH MỤC 3: SEN VÒI & THIẾT BỊ VỆ SINH PHÒNG TẮM -->
        <section id="sec-sen-voi" class="flatsome-container product-section-block" data-cat="sen-voi">
            <div class="flatsome-section-title">
                <div class="flatsome-section-title-main">
                    <i class="fa-solid fa-shower"></i>
                    <span>SEN VÒI & THIẾT BỊ VỆ SINH CAO CẤP</span>
                </div>
                <a href="#form-bao-gia" class="text-xs font-bold text-brand-blue hover:text-brand-orange whitespace-nowrap">
                    Xem thêm <i class="fa-solid fa-angle-right ml-0.5"></i>
                </a>
            </div>
            <div id="grid-sen-voi" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5"></div>
        </section>

        <!-- DANH MỤC 4: CÁT SẠN - ĐÁ XÂY DỰNG - XI MĂNG - SẮT THÉP -->
        <section id="sec-cat-xi-mang" class="flatsome-container product-section-block" data-cat="cat-san-xi-mang">
            <div class="flatsome-section-title">
                <div class="flatsome-section-title-main">
                    <i class="fa-solid fa-cubes"></i>
                    <span>CÁT SẠN • ĐÁ XÂY DỰNG • XI MĂNG • THÉP</span>
                </div>
                <a href="#form-bao-gia" class="text-xs font-bold text-brand-blue hover:text-brand-orange whitespace-nowrap">
                    Xem thêm <i class="fa-solid fa-angle-right ml-0.5"></i>
                </a>
            </div>
            <div id="grid-cat-san-xi-mang" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5"></div>
        </section>

        <!-- DANH MỤC 5: DỊCH VỤ SAN LẤP MẶT BẰNG & VẬT TƯ PHỤ -->
        <section id="sec-san-lap" class="flatsome-container product-section-block" data-cat="san-lap">
            <div class="flatsome-section-title">
                <div class="flatsome-section-title-main">
                    <i class="fa-solid fa-truck-monster"></i>
                    <span>SAN LẤP MẶT BẰNG & VẬT TƯ PHỤ XÂY DỰNG</span>
                </div>
                <a href="#form-bao-gia" class="text-xs font-bold text-brand-blue hover:text-brand-orange whitespace-nowrap">
                    Xem thêm <i class="fa-solid fa-angle-right ml-0.5"></i>
                </a>
            </div>
            <div id="grid-san-lap" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5"></div>
        </section>

        <!-- 3. GIỚI THIỆU CỬA HÀNG THỰC TẾ & FORM YÊU CẦU BÁO GIÁ TRANG CHỦ -->
        <section id="form-bao-gia" class="flatsome-container">
            <div class="bg-white rounded-xl shadow-sm border border-slate-200 p-4 sm:p-6">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
                    
                    <!-- Cột Hình ảnh thực tế Cửa hàng Trung Mừng (5/12) -->
                    <div class="lg:col-span-5 space-y-3">
                        <div class="flatsome-section-title mb-2">
                            <div class="flatsome-section-title-main">
                                <i class="fa-solid fa-store"></i>
                                <span>HÌNH ẢNH CỬA HÀNG TRUNG MỪNG</span>
                            </div>
                        </div>
                        <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-100">
                            <img src="https://drive.google.com/thumbnail?id=1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61&sz=w1000" 
                                 onerror="handleDriveImageError(this, '1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61')"
                                 alt="Cửa hàng Vật Liệu Xây Dựng Trung Mừng Đà Nẵng" 
                                 class="w-full h-56 sm:h-64 object-cover">
                        </div>
                        <div class="bg-slate-50 p-3.5 rounded-lg border border-slate-200 text-xs sm:text-sm space-y-1.5">
                            <h3 class="font-extrabold text-brand-blue text-sm sm:text-base">
                                CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ TRUNG MỪNG
                            </h3>
                            <p class="text-slate-600"><i class="fa-solid fa-globe text-brand-orange mr-1.5"></i>Website: <strong>trungmung.com</strong></p>
                            <p class="text-slate-600"><i class="fa-solid fa-location-dot text-brand-orange mr-1.5"></i>Địa chỉ: <strong>381 Nguyễn Phước Nguyên - 373 Nguyễn Đình Tựu, Q. Thanh Khê, TP. Đà Nẵng</strong></p>
                            <p class="text-slate-600"><i class="fa-solid fa-phone-volume text-brand-orange mr-1.5"></i>SĐT / Zalo: <a href="tel:0905182455" class="font-bold text-brand-blue hover:underline">0905.182.455</a> - <a href="tel:0905432455" class="font-bold text-brand-blue hover:underline">0905.432.455</a></p>
                            <p class="text-slate-600"><i class="fa-solid fa-circle-check text-emerald-600 mr-1.5"></i>Chuyên: Gạch men, Sơn nước, Sen vòi TBVS, Cát sạn xi măng, San lấp mặt bằng.</p>
                        </div>
                    </div>

                    <!-- Cột Form Yêu Cầu & Báo Giá Trang Chủ (7/12) -->
                    <div class="lg:col-span-7">
                        <div class="flatsome-section-title mb-3">
                            <div class="flatsome-section-title-main">
                                <i class="fa-solid fa-file-invoice-dollar"></i>
                                <span>ĐĂNG KÝ YÊU CẦU TƯ VẤN & BÁO GIÁ VẬT LIỆU</span>
                            </div>
                        </div>
                        <p class="text-xs sm:text-sm text-slate-600 mb-4">
                            Quý khách hàng, nhà thầu cần báo giá sỉ & lẻ <strong>Gạch men, Sơn nước, Sen vòi TBVS, Cát sạn xi măng hoặc San lấp mặt bằng</strong> vui lòng điền thông tin bên dưới. Trung Mừng sẽ liên hệ báo giá tốt nhất trong 5 phút!
                        </p>

                        <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên khách hàng *</label>
                                    <input type="text" id="qName" required placeholder="Nhập họ và tên..." class="w-full border border-slate-300 rounded-md px-3 py-2 text-xs sm:text-sm focus:outline-none focus:border-brand-blue">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input type="tel" id="qPhone" required placeholder="Ví dụ: 0905182455" class="w-full border border-slate-300 rounded-md px-3 py-2 text-xs sm:text-sm focus:outline-none focus:border-brand-blue">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Hạng mục cần báo giá *</label>
                                    <select id="qCategory" class="w-full border border-slate-300 rounded-md px-3 py-2 text-xs sm:text-sm focus:outline-none focus:border-brand-blue bg-white">
                                        <option value="Trọn gói VLXD">Trọn gói Vật Liệu Xây Dựng</option>
                                        <option value="Gạch men ốp lát">Gạch men lát nền, ốp tường</option>
                                        <option value="Sơn nước & Chống thấm">Sơn nước (Jotun, Dulux, Maxilite) & Chống thấm</option>
                                        <option value="Sen vòi & Thiết bị vệ sinh">Sen vòi, Bồn cầu, Thiết bị vệ sinh</option>
                                        <option value="Cát sạn - Đá - Xi măng">Cát sạn, Đá xây dựng, Xi măng</option>
                                        <option value="San lấp mặt bằng">Dịch vụ San lấp mặt bằng, vận chuyển xà bần</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Địa chỉ công trình giao hàng</label>
                                    <input type="text" id="qAddress" placeholder="Quận Thanh Khê, Đà Nẵng..." class="w-full border border-slate-300 rounded-md px-3 py-2 text-xs sm:text-sm focus:outline-none focus:border-brand-blue">
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Nội dung chi tiết (Số lượng, mã sản phẩm cần báo giá)</label>
                                <textarea id="qNote" rows="3" placeholder="Nhập chi tiết loại gạch men, mã sơn, khối lượng cát đá xi măng hoặc diện tích cần san lấp..." class="w-full border border-slate-300 rounded-md px-3 py-2 text-xs sm:text-sm focus:outline-none focus:border-brand-blue"></textarea>
                            </div>

                            <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                                <button type="submit" class="bg-brand-orange hover:bg-brand-orangeHover text-white font-bold text-xs sm:text-sm px-6 py-2.5 rounded-md shadow transition flex items-center gap-2">
                                    <i class="fa-solid fa-paper-plane"></i>
                                    <span>GỬI YÊU CẦU BÁO GIÁ NGAY</span>
                                </button>
                                <span class="text-xs text-slate-500">
                                    Hoặc gọi trực tiếp: <strong class="text-brand-blue">0905.182.455 - 0905.432.455</strong>
                                </span>
                            </div>

                            <!-- Thông báo gửi form thành công -->
                            <div id="quoteSuccessBox" class="hidden p-3 rounded-md bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs sm:text-sm font-medium"></div>
                        </form>
                    </div>

                </div>
            </div>
        </section>

        <!-- 4. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM VLXD CHUẨN FLATSOME) -->
        <section id="tin-tuc-xay-dung" class="flatsome-container">
            <div class="flatsome-section-title">
                <div class="flatsome-section-title-main">
                    <i class="fa-solid fa-newspaper"></i>
                    <span>DANH MỤC BÀI VIẾT & KINH NGHIỆM XÂY DỰNG</span>
                </div>
                <a href="#form-bao-gia" class="text-xs font-bold text-brand-blue hover:text-brand-orange whitespace-nowrap">
                    Tất cả bài viết <i class="fa-solid fa-angle-right ml-0.5"></i>
                </a>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="h-40 overflow-hidden bg-slate-100 relative">
                        <img src="https://drive.google.com/thumbnail?id=19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r&sz=w600" 
                             onerror="handleDriveImageError(this, '19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r')"
                             alt="Kinh nghiệm chọn gạch men lát nền" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between space-y-2">
                        <div>
                            <span class="text-[10px] font-bold uppercase text-brand-orange">Tư vấn Gạch Men</span>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 mt-1 leading-snug hover:text-brand-blue">
                                Kinh nghiệm chọn gạch men lát nền & ốp tường bền đẹp cho nhà phố Đà Nẵng
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 line-clamp-2">
                                Hướng dẫn cách chọn gạch bóng kiếng 60x60, 80x80 chống trầy xước, chống thấm ẩm phù hợp khí hậu miền Trung...
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="text-xs font-semibold text-brand-blue hover:text-brand-orange inline-flex items-center gap-1 pt-1">
                            Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="h-40 overflow-hidden bg-slate-100 relative">
                        <img src="https://drive.google.com/thumbnail?id=1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h&sz=w600" 
                             onerror="handleDriveImageError(this, '1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h')"
                             alt="Giải pháp sơn nước và chống thấm" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between space-y-2">
                        <div>
                            <span class="text-[10px] font-bold uppercase text-brand-orange">Kỹ thuật Sơn & Chống thấm</span>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 mt-1 leading-snug hover:text-brand-blue">
                                Quy trình thi công sơn Jotun, Dulux và chống thấm tường ngoài trời bền màu 10 năm
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 line-clamp-2">
                                Giải pháp kết hợp sơn lót kháng kiềm và chất chống thấm Sika, CT11A bảo vệ tối ưu cho công trình tại Đà Nẵng...
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="text-xs font-semibold text-brand-blue hover:text-brand-orange inline-flex items-center gap-1 pt-1">
                            Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="h-40 overflow-hidden bg-slate-100 relative">
                        <img src="https://drive.google.com/thumbnail?id=1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN&sz=w600" 
                             onerror="handleDriveImageError(this, '1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN')"
                             alt="Chọn sen vòi thiết bị vệ sinh" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between space-y-2">
                        <div>
                            <span class="text-[10px] font-bold uppercase text-brand-orange">Thiết Bị Vệ Sinh</span>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 mt-1 leading-snug hover:text-brand-blue">
                                Trọn bộ sen vòi tắm đứng Inox 304 và bồn cầu liền khối tiết kiệm nước tại Trung Mừng
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 line-clamp-2">
                                Tổng hợp các mẫu sen cây tắm nóng lạnh, lavabo bàn đá và phụ kiện phòng tắm chính hãng bảo hành dài hạn...
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="text-xs font-semibold text-brand-blue hover:text-brand-orange inline-flex items-center gap-1 pt-1">
                            Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="h-40 overflow-hidden bg-slate-100 relative">
                        <img src="https://drive.google.com/thumbnail?id=1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c&sz=w600" 
                             onerror="handleDriveImageError(this, '1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c')"
                             alt="Báo giá cát đá xi măng và san lấp mặt bằng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between space-y-2">
                        <div>
                            <span class="text-[10px] font-bold uppercase text-brand-orange">Báo Giá VLXD & San Lấp</span>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 mt-1 leading-snug hover:text-brand-blue">
                                Bảng báo giá Cát sạn, Đá 1x2, Xi măng & Dịch vụ san lấp mặt bằng tại Thanh Khê, Đà Nẵng
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 line-clamp-2">
                                Cam kết giao đủ khối lượng cát xây tô, đá bê tông, xi măng Đồng Lâm, Kim Đỉnh và san lấp mặt bằng nhanh gọn...
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="text-xs font-semibold text-brand-blue hover:text-brand-orange inline-flex items-center gap-1 pt-1">
                            Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>
            </div>
        </section>

        <!-- 5. DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI -->
        <section class="flatsome-container">
            <div class="bg-white rounded-xl p-4 shadow-sm border border-slate-200">
                <div class="flatsome-section-title mb-3">
                    <div class="flatsome-section-title-main">
                        <i class="fa-solid fa-handshake"></i>
                        <span>ĐỐI TÁC & THƯƠNG HIỆU ĐỒNG HÀNH</span>
                    </div>
                </div>
                <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 text-center">
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-sm text-brand-blue">JOTUN</span>
                        <span class="text-[10px] text-slate-500">Sơn Nước Cao Cấp</span>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-sm text-sky-700">DULUX</span>
                        <span class="text-[10px] text-slate-500">Sơn Nội Ngoại Thất</span>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-sm text-brand-orange">MAXILITE</span>
                        <span class="text-[10px] text-slate-500">Sơn Kinh Tế Bền Đẹp</span>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-sm text-red-600">SIKA</span>
                        <span class="text-[10px] text-slate-500">Phụ Gia Chống Thấm</span>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-sm text-brand-blue">VIGLACERA</span>
                        <span class="text-[10px] text-slate-500">Gạch Men & TBVS</span>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-sm text-sky-800">INAX • TOTO</span>
                        <span class="text-[10px] text-slate-500">Sen Vòi & Phòng Tắm</span>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-sm text-emerald-700">ĐỒNG LÂM</span>
                        <span class="text-[10px] text-slate-500">Xi Măng PCB40</span>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
                        <span class="font-extrabold text-sm text-amber-700">KIM ĐỈNH</span>
                        <span class="text-[10px] text-slate-500">Xi Măng Xây Dựng</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- 6. ĐƯA BẢN ĐỒ GOOGLE MAP & FANPAGE RA NGOÀI TRANG CHỦ -->
        <section id="ban-do-cua-hang" class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
                
                <!-- Bản đồ Google Map ngoài trang chủ (7/12) -->
                <div class="lg:col-span-7 bg-white rounded-xl p-4 shadow-sm border border-slate-200 flex flex-col">
                    <div class="flatsome-section-title mb-3">
                        <div class="flatsome-section-title-main">
                            <i class="fa-solid fa-map-location-dot"></i>
                            <span>BẢN ĐỒ GOOGLE MAP: 381 NGUYỄN PHƯỚC NGUYÊN - 373 NGUYỄN ĐÌNH TỰU</span>
                        </div>
                    </div>
                    <div class="w-full h-64 sm:h-72 rounded-lg overflow-hidden border border-slate-200 relative bg-slate-100">
                        <iframe 
                            title="Bản đồ Công Ty TNHH TM & DV Trung Mừng - 381 Nguyễn Phước Nguyên, Thanh Khê, Đà Nẵng"
                            src="https://www.google.com/maps?q=381+Nguy%E1%BB%85n+Ph%C6%B0%E1%BB%9Bc+Nguy%C3%AAn,+Thanh+Kh%C3%AA,+%C4%90%C3%A0+N%E1%BA%B5ng&output=embed"
                            width="100%" 
                            height="100%" 
                            style="border:0;" 
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                    <div class="mt-3 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-700">
                        <div>
                            <i class="fa-solid fa-location-dot text-brand-orange mr-1"></i>
                            <strong>Địa chỉ:</strong> 381 Nguyễn Phước Nguyên - 373 Nguyễn Đình Tựu, Quận Thanh Khê, TP. Đà Nẵng
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=381+Nguyen+Phuoc+Nguyen+Thanh+Khe+Da+Nang" target="_blank" rel="noopener noreferrer" class="bg-brand-blue hover:bg-sky-800 text-white font-semibold px-3 py-1.5 rounded inline-flex items-center gap-1.5 transition">
                            <i class="fa-solid fa-diamond-turn-right"></i> Mở Google Maps lớn
                        </a>
                    </div>
                </div>

                <!-- Fanpage Facebook ngoài trang chủ (5/12) -->
                <div class="lg:col-span-5 bg-white rounded-xl p-4 shadow-sm border border-slate-200 flex flex-col justify-between">
                    <div>
                        <div class="flatsome-section-title mb-3">
                            <div class="flatsome-section-title-main">
                                <i class="fa-brands fa-facebook"></i>
                                <span>FANPAGE CHÍNH THỨC TRUNG MỪNG</span>
                            </div>
                        </div>

                        <!-- Khung hiển thị Fanpage trực quan ngoài trang chủ -->
                        <div class="border border-slate-200 rounded-lg overflow-hidden bg-slate-50">
                            <div class="relative h-36 bg-brand-blue overflow-hidden">
                                <img src="https://drive.google.com/thumbnail?id=1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61&sz=w800" 
                                     onerror="handleDriveImageError(this, '1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61')"
                                     alt="Fanpage VLXD Trung Mừng" class="w-full h-full object-cover opacity-55">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3 text-white">
                                    <div class="w-12 h-12 rounded-lg bg-white p-1 shadow flex items-center justify-center shrink-0">
                                        <i class="fa-solid fa-building-shield text-brand-blue text-2xl"></i>
                                    </div>
                                    <div class="min-w-0">
                                        <h4 class="font-bold text-sm truncate">VLXD Trung Mừng - Đà Nẵng</h4>
                                        <p class="text-[11px] text-sky-200 truncate">trungmung.com • 5.2K người theo dõi</p>
                                    </div>
                                </div>
                            </div>

                            <div class="p-3.5 space-y-2.5 text-xs text-slate-700">
                                <p class="font-medium text-slate-800">
                                    <i class="fa-solid fa-circle-check text-blue-600 mr-1"></i>
                                    Cập nhật mẫu Gạch men mới, bảng màu Sơn Jotun/Dulux, Sen vòi TBVS & giá Cát đá xi măng mỗi ngày.
                                </p>
                                <div class="grid grid-cols-2 gap-2 pt-1">
                                    <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer" class="bg-[#1877F2] hover:bg-blue-700 text-white font-bold py-2 px-3 rounded text-center inline-flex items-center justify-center gap-1.5 transition">
                                        <i class="fa-brands fa-facebook-f"></i> Theo dõi Fanpage
                                    </a>
                                    <a href="https://zalo.me/0905182455" target="_blank" rel="noopener noreferrer" class="bg-[#0068FF] hover:bg-blue-600 text-white font-bold py-2 px-3 rounded text-center inline-flex items-center justify-center gap-1.5 transition">
                                        <i class="fa-solid fa-comment-dots"></i> Nhắn Zalo Ngay
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-3 pt-3 border-t border-slate-200 flex items-center justify-between text-xs text-slate-600">
                        <span><i class="fa-solid fa-headset text-brand-orange mr-1"></i>Hỗ trợ trực tuyến 24/7:</span>
                        <span class="font-bold text-brand-blue">0905.182.455 - 0905.432.455</span>
                    </div>
                </div>

            </div>
        </section>

    </main>

    <!-- ================= FOOTER CHUẨN FLATSOME ================= -->
    <footer class="bg-[#082f49] text-slate-200 pt-8 pb-20 md:pb-8 border-t-4 border-brand-orange mt-6">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-sky-900">
                
                <!-- Cột 1: Thông tin công ty -->
                <div class="space-y-2.5 text-xs">
                    <h3 class="text-sm font-extrabold text-white uppercase tracking-wide">
                        CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ TRUNG MỪNG
                    </h3>
                    <p class="text-sky-200 leading-relaxed">
                        Đơn vị uy tín hàng đầu tại Đà Nẵng chuyên cung cấp Gạch men, Sơn nước, Sen vòi thiết bị vệ sinh, Cát sạn xi măng và Dịch vụ san lấp mặt bằng.
                    </p>
                    <ul class="space-y-1.5 pt-1">
                        <li><i class="fa-solid fa-location-dot text-brand-orange mr-2"></i><strong>Địa chỉ:</strong> 381 Nguyễn Phước Nguyên - 373 Nguyễn Đình Tựu, Quận Thanh Khê, TP. Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-brand-orange mr-2"></i><strong>Hotline:</strong> 0905.182.455 - 0905.432.455</li>
                        <li><i class="fa-solid fa-globe text-brand-orange mr-2"></i><strong>Website:</strong> trungmung.com</li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div class="space-y-2 text-xs">
                    <h3 class="text-sm font-extrabold text-white uppercase tracking-wide">DANH MỤC SẢN PHẨM</h3>
                    <ul class="space-y-1.5 text-sky-100">
                        <li><a href="#sec-gach-men" class="hover:text-brand-orange transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand-orange"></i>Gạch men lát nền & ốp tường</a></li>
                        <li><a href="#sec-son-nuoc" class="hover:text-brand-orange transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand-orange"></i>Sơn nước Jotun, Dulux, Maxilite</a></li>
                        <li><a href="#sec-son-nuoc" class="hover:text-brand-orange transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand-orange"></i>Sơn chống thấm Sika, CT11A</a></li>
                        <li><a href="#sec-sen-voi" class="hover:text-brand-orange transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand-orange"></i>Sen vòi & Thiết bị vệ sinh</a></li>
                        <li><a href="#sec-cat-xi-mang" class="hover:text-brand-orange transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand-orange"></i>Cát xây tô, Đá 1x2, Xi măng</a></li>
                        <li><a href="#sec-san-lap" class="hover:text-brand-orange transition"><i class="fa-solid fa-angle-right mr-1.5 text-brand-orange"></i>Dịch vụ San lấp mặt bằng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách khách hàng -->
                <div class="space-y-2 text-xs">
                    <h3 class="text-sm font-extrabold text-white uppercase tracking-wide">CAM KẾT DỊCH VỤ</h3>
                    <ul class="space-y-1.5 text-sky-100">
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Hàng chính hãng 100% từ nhà máy</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Giao vật liệu tận chân công trình Đà Nẵng</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Đúng khối lượng cát, đá, xi măng cam kết</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Chiết khấu cao cho nhà thầu & công trình</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>San lấp mặt bằng cơ giới nhanh gọn</li>
                    </ul>
                </div>

                <!-- Cột 4: Liên hệ nhanh -->
                <div class="space-y-2.5 text-xs">
                    <h3 class="text-sm font-extrabold text-white uppercase tracking-wide">TƯ VẤN & ĐẶT HÀNG</h3>
                    <div class="bg-sky-950/80 p-3 rounded-lg border border-sky-800 space-y-2">
                        <div class="text-amber-400 font-bold">HOTLINE PHòng KINH DOANH:</div>
                        <a href="tel:0905182455" class="block text-base font-extrabold text-white hover:text-brand-orange">
                            <i class="fa-solid fa-phone-volume mr-1.5 text-brand-orange"></i>0905.182.455
                        </a>
                        <a href="tel:0905432455" class="block text-base font-extrabold text-white hover:text-brand-orange">
                            <i class="fa-solid fa-phone-volume mr-1.5 text-brand-orange"></i>0905.432.455
                        </a>
                    </div>
                </div>
            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-xs text-sky-300 gap-2">
                <div>© 2026 Bản quyền thuộc về <strong>CÔNG TY TNHH THƯƠNG MẠI VÀ DỊCH VỤ TRUNG MỪNG</strong> (trungmung.com).</div>
                <div>Đ/c: 381 Nguyễn Phước Nguyên - 373 Nguyễn Đình Tựu, Thanh Khê, Đà Nẵng</div>
            </div>
        </div>
    </footer>

    <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH TRÊN MÁY TÍNH VÀ ĐIỆN THOẠI ================= -->
    <div class="fixed bottom-4 right-3 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer" 
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
           title="Chat Facebook Fanpage">
            <i class="fa-brands fa-facebook-messenger text-base sm:text-lg"></i>
            <span class="text-[11px] sm:text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a href="https://zalo.me/0905182455" target="_blank" rel="noopener noreferrer" 
           class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
           title="Nhắn tin Zalo 0905182455">
            <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center">Zalo</span>
            <span class="text-[11px] sm:text-xs font-bold">Chat Zalo</span>
        </a>

        <!-- Nút Gọi Hotline 1 -->
        <a href="tel:0905182455" 
           class="pulse-btn flex items-center gap-2 bg-brand-orange hover:bg-brand-orangeHover text-white px-3.5 py-2 rounded-full shadow-lg transition"
           title="Gọi 0905.182.455">
            <i class="fa-solid fa-phone-volume text-sm sm:text-base"></i>
            <span class="text-[11px] sm:text-xs font-extrabold">0905.182.455</span>
        </a>

        <!-- Nút Gọi Hotline 2 -->
        <a href="tel:0905432455" 
           class="flex items-center gap-2 bg-brand-blue hover:bg-sky-800 text-white px-3.5 py-2 rounded-full shadow-lg border border-sky-400/30 transition"
           title="Gọi 0905.432.455">
            <i class="fa-solid fa-phone text-sm sm:text-base text-amber-400"></i>
            <span class="text-[11px] sm:text-xs font-extrabold">0905.432.455</span>
        </a>
    </div>

    <!-- ================= MODAL XEM CHI TIẾT SẢN PHẨM & BÁO GIÁ NHANH ================= -->
    <div id="productModal" class="fixed inset-0 bg-black/60 z-50 hidden items-center justify-center p-3">
        <div class="bg-white rounded-xl max-w-lg w-full overflow-hidden shadow-2xl border border-slate-200 relative">
            <button onclick="closeProductModal()" class="absolute top-3 right-3 w-8 h-8 rounded-full bg-slate-100 hover:bg-red-500 hover:text-white text-slate-700 flex items-center justify-center transition z-10">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div class="p-4 sm:p-5">
                <div class="w-full h-56 sm:h-64 bg-slate-100 rounded-lg overflow-hidden mb-3 relative">
                    <span id="modalSaleBadge" class="flatsome-sale-badge"></span>
                    <img id="modalProductImg" src="" alt="" class="w-full h-full object-contain">
                </div>
                <div id="modalProductCat" class="text-[11px] font-bold uppercase text-brand-orange"></div>
                <h3 id="modalProductName" class="text-base sm:text-lg font-extrabold text-slate-800 mt-1"></h3>
                <div class="mt-2 flex items-baseline gap-2">
                    <span id="modalOldPrice" class="text-xs text-slate-400 line-through"></span>
                    <span id="modalNewPrice" class="text-base font-extrabold text-brand-orange"></span>
                </div>
                <p class="text-xs text-slate-600 mt-2 leading-relaxed">
                    Sản phẩm phân phối chính hãng tại <strong>CÔNG TY TNHH TM & DV TRUNG MỪNG (trungmung.com)</strong> - Đ/c: 381 Nguyễn Phước Nguyên - 373 Nguyễn Đình Tựu, Thanh Khê, Đà Nẵng.
                </p>
                <div class="mt-4 grid grid-cols-2 gap-2.5">
                    <a href="tel:0905182455" class="bg-brand-orange hover:bg-brand-orangeHover text-white font-bold text-xs py-2.5 px-3 rounded-lg text-center flex items-center justify-center gap-1.5">
                        <i class="fa-solid fa-phone-volume"></i> Gọi 0905.182.455
                    </a>
                    <a href="https://zalo.me/0905182455" target="_blank" rel="noopener noreferrer" class="bg-[#0068FF] hover:bg-blue-700 text-white font-bold text-xs py-2.5 px-3 rounded-lg text-center flex items-center justify-center gap-1.5">
                        <i class="fa-solid fa-comment-dots"></i> Báo Giá Qua Zalo
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- ================= JAVASCRIPT XỬ LÝ DỮ LIỆU 19 ẢNH THỰC TẾ GOOGLE DRIVE, SLIDER & BỘ LỌC ================= -->
    <script>
        /* Hàm tự động chuyển đổi link dự phòng khi tải ảnh từ Google Drive để đảm bảo hiển thị 100% */
        function handleDriveImageError(imgElement, fileId) {
            const step = parseInt(imgElement.getAttribute('data-fallback-step') || '0', 10);
            if (step === 0) {
                imgElement.setAttribute('data-fallback-step', '1');
                imgElement.src = 'https://lh3.googleusercontent.com/d/' + fileId + '=w800';
            } else if (step === 1) {
                imgElement.setAttribute('data-fallback-step', '2');
                imgElement.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
            } else {
                imgElement.onerror = null;
                imgElement.src = 'https://placehold.co/600x600/0c4a6e/ffffff?text=VLXD+Trung+Mung';
            }
        }

        /* Danh sách toàn bộ 19 sản phẩm lấy trực tiếp từ 19 file Google Drive thực tế của khách hàng + các sản phẩm mẫu vatlieuxaydungdanang.com */
        const productsData = [
            // --- DANH MỤC 1: GẠCH MEN ỐP LÁT & GẠCH XÂY DỰNG (5 sản phẩm) ---
            {
                id: 1,
                category: 'gach-men',
                categoryLabel: 'Gạch Men Ốp Lát',
                name: 'Gạch Men Lát Nền Bóng Kiếng Vân Đá 60x60 Cao Cấp',
                driveId: '1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY',
                discount: '-25%',
                oldPrice: '220.000 ₫/m²',
                newPrice: '165.000 ₫/m²'
            },
            {
                id: 2,
                category: 'gach-men',
                categoryLabel: 'Gạch Men Ốp Lát',
                name: 'Gạch Men Ốp Tường Phòng Khách & Phòng Tắm 30x60',
                driveId: '11z7ir7cmqEcdrYuAThZvpOhgUVFsLUnP',
                discount: '-20%',
                oldPrice: '195.000 ₫/m²',
                newPrice: '156.000 ₫/m²'
            },
            {
                id: 3,
                category: 'gach-men',
                categoryLabel: 'Gạch Men Ốp Lát',
                name: 'Gạch Porcelain Vân Đá Marble 80x80 Chống Trầy',
                driveId: '1KTDzdSGqiXWuLZDkPoDD7oZZVL-5F3Rr',
                discount: '-30%',
                oldPrice: '310.000 ₫/m²',
                newPrice: '217.000 ₫/m²'
            },
            {
                id: 4,
                category: 'gach-men',
                categoryLabel: 'Gạch Men Ốp Lát',
                name: 'Gạch Lát Sân Vườn Chống Trơn & Gạch Trang Trí Mặt Tiền',
                driveId: '1X31hmhpLVVORV-tmMSZYzBO-qtpyusry',
                discount: '-18%',
                oldPrice: '175.000 ₫/m²',
                newPrice: '143.000 ₫/m²'
            },
            {
                id: 5,
                category: 'gach-men',
                categoryLabel: 'Gạch Xây Dựng',
                name: 'Gạch 6 Lỗ & Gạch Thẻ Xây Tường Đại Hưng - Điện Ngọc',
                driveId: '171kMlCqYFeFpvYcgH1wQbaIMszY0Ns3O',
                discount: '-15%',
                oldPrice: '1.650 ₫/viên',
                newPrice: 'Liên hệ: 0905.182.455'
            },

            // --- DANH MỤC 2: SƠN NƯỚC (JOTUN - DULUX - MAXILITE) & CHỐNG THẤM (5 sản phẩm) ---
            {
                id: 6,
                category: 'son-nuoc',
                categoryLabel: 'Sơn Jotun',
                name: 'Sơn Nội Thất Jotun Majestic Đẹp Hoàn Hảo Bóng',
                driveId: '1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg',
                discount: '-55%',
                oldPrice: '2.223.000 ₫',
                newPrice: '995.000 ₫'
            },
            {
                id: 7,
                category: 'son-nuoc',
                categoryLabel: 'Sơn Jotun',
                name: 'Sơn Ngoại Thất Jotun Jotashield Bền Màu Toàn Diện',
                driveId: '1uqL6ACCB5ne0G1BYkXCurdnrsf1m2lr4',
                discount: '-50%',
                oldPrice: '3.546.000 ₫',
                newPrice: '1.773.000 ₫'
            },
            {
                id: 8,
                category: 'son-nuoc',
                categoryLabel: 'Sơn Dulux',
                name: 'Sơn Ngoại Thất Dulux Weathershield Chống Kiềm BJ8',
                driveId: '1NwR4v0eypEtIwPi6NJVJCKoNCFFQ8G54',
                discount: '-45%',
                oldPrice: '3.150.000 ₫',
                newPrice: '1.730.000 ₫'
            },
            {
                id: 9,
                category: 'son-nuoc',
                categoryLabel: 'Sơn Maxilite',
                name: 'Sơn Phủ Nội Ngoại Thất Maxilite Tough 28C & Total',
                driveId: '19jauCH_X7lcc0KNlu2OJ75CRiw3ArT7r',
                discount: '-35%',
                oldPrice: '1.380.000 ₫',
                newPrice: '897.000 ₫'
            },
            {
                id: 10,
                category: 'son-nuoc',
                categoryLabel: 'Sơn Chống Thấm',
                name: 'Sơn Chống Thấm SikaTop Seal 107 & Kova CT-11A Đa Năng',
                driveId: '1_HXfxWiPLtWiayxMPjgFCsl1WS1wGb7h',
                discount: '-30%',
                oldPrice: '980.000 ₫',
                newPrice: '686.000 ₫'
            },

            // --- DANH MỤC 3: SEN VÒI & THIẾT BỊ VỆ SINH (5 sản phẩm) ---
            {
                id: 11,
                category: 'sen-voi',
                categoryLabel: 'Sen Vòi & TBVS',
                name: 'Bộ Sen Cây Tắm Đứng Nóng Lạnh Inox 304 Cao Cấp',
                driveId: '1ciwHcFfmGbsIyjTsi9KlyIsx6EXBNJTN',
                discount: '-35%',
                oldPrice: '2.850.000 ₫',
                newPrice: '1.850.000 ₫'
            },
            {
                id: 12,
                category: 'sen-voi',
                categoryLabel: 'Sen Vòi & TBVS',
                name: 'Bồn Cầu Một Khối Men Tuyết Nano Kháng Khuẩn',
                driveId: '1vHG-pgeryaSItJoQ5ciiCGSWA7SJSU8c',
                discount: '-30%',
                oldPrice: '4.200.000 ₫',
                newPrice: '2.940.000 ₫'
            },
            {
                id: 13,
                category: 'sen-voi',
                categoryLabel: 'Sen Vòi & TBVS',
                name: 'Chậu Rửa Mặt Lavabo Bàn Đá Kèm Vòi Nóng Lạnh',
                driveId: '1X-ECML9CKN4ycBfVFu4pC0wnqzTS12CP',
                discount: '-25%',
                oldPrice: '1.950.000 ₫',
                newPrice: '1.460.000 ₫'
            },
            {
                id: 14,
                category: 'sen-voi',
                categoryLabel: 'Sen Vòi & TBVS',
                name: 'Vòi Rửa Chén Bát Cần Rút Nóng Lạnh & Chậu Inox 304',
                driveId: '1CGBZ4cuB7DMWadnoktlMoji6MB3dioC-',
                discount: '-28%',
                oldPrice: '1.600.000 ₫',
                newPrice: '1.150.000 ₫'
            },
            {
                id: 15,
                category: 'sen-voi',
                categoryLabel: 'Sen Vòi & TBVS',
                name: 'Trọn Bộ Phụ Kiện Phòng Tắm Gương Soi & Vắt Khăn Inox',
                driveId: '17YrxXteZmzhvVRYgfaklNGC2hKjN09N8',
                discount: '-20%',
                oldPrice: '1.250.000 ₫',
                newPrice: '990.000 ₫'
            },

            // --- DANH MỤC 4: CÁT SẠN - ĐÁ - XI MĂNG - SẮT THÉP (5 sản phẩm) ---
            {
                id: 16,
                category: 'cat-san-xi-mang',
                categoryLabel: 'Xi Măng Xây Dựng',
                name: 'Xi Măng Đồng Lâm PCB40 & Kim Đỉnh PCB40 Chính Hãng',
                driveId: '19k5uWHn_xeas2_BMP_JgBDwwu-IysSRP',
                discount: '-12%',
                oldPrice: '98.000 ₫/bao',
                newPrice: '86.000 ₫/bao'
            },
            {
                id: 17,
                category: 'cat-san-xi-mang',
                categoryLabel: 'Cát Sạn Xây Dựng',
                name: 'Cát Xây, Cát Tô, Cát Đúc Bê Tông Sạch Đủ Khối Lượng',
                driveId: '1oah4j6YAPIsJacMYQFJ0JGVemrMwqCgf',
                discount: '-15%',
                oldPrice: '380.000 ₫/m³',
                newPrice: '320.000 ₫/m³'
            },
            {
                id: 18,
                category: 'cat-san-xi-mang',
                categoryLabel: 'Đá Xây Dựng',
                name: 'Đá Xây Dựng 1x2, Đá 2x4, Đá 4x6 Đổ Bê Tông Móng',
                driveId: '15IWAPhzVLsyUO5TDRoWXxvncrHoFcH1_',
                discount: '-15%',
                oldPrice: '420.000 ₫/m³',
                newPrice: '355.000 ₫/m³'
            },
            {
                id: 19,
                category: 'cat-san-xi-mang',
                categoryLabel: 'Xi Măng & Bột Trét',
                name: 'Xi Măng Sông Gianh, Nghi Sơn PCB40 & Bột Trét Jotun',
                driveId: '1WLKyUBxRc63xFN9GBUhFcqE0xPo0sQKh',
                discount: '-30%',
                oldPrice: '515.000 ₫',
                newPrice: '361.000 ₫'
            },
            {
                id: 20,
                category: 'cat-san-xi-mang',
                categoryLabel: 'Thép Xây Dựng',
                name: 'Thép Cuộn D6, D8 & Thép Cây Hòa Phát - Việt Mỹ',
                driveId: '1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61',
                discount: '-10%',
                oldPrice: 'Liên hệ giá sỉ',
                newPrice: 'Liên hệ: 0905.182.455'
            },

            // --- DANH MỤC 5: SAN LẤP MẶT BẰNG & VẬT TƯ PHỤ (4 sản phẩm) ---
            {
                id: 21,
                category: 'san-lap',
                categoryLabel: 'San Lấp Mặt Bằng',
                name: 'Dịch Vụ San Lấp Mặt Bằng Công Trình & Nhà Phố Đà Nẵng',
                driveId: '1qbPrqEKf9TFKy6PCYacRgI7M5FAD1X61',
                discount: '-20%',
                oldPrice: 'Báo giá khảo sát',
                newPrice: 'Liên hệ: 0905.182.455'
            },
            {
                id: 22,
                category: 'san-lap',
                categoryLabel: 'San Lấp Mặt Bằng',
                name: 'Cung Cấp Cát Nền San Lấp & Xe Cơ Giới Đào Móng, Xà Bần',
                driveId: '1oah4j6YAPIsJacMYQFJ0JGVemrMwqCgf',
                discount: '-15%',
                oldPrice: '290.000 ₫/m³',
                newPrice: '245.000 ₫/m³'
            },
            {
                id: 23,
                category: 'san-lap',
                categoryLabel: 'Vật Tư Phụ',
                name: 'Cọ Lăn Sơn Đông Nam Á, Bay Thép, Dao Trét & Giấy Nhám',
                driveId: '1t8U7WQsmDbGWzmSelkxzjVv8M0BvIxAg',
                discount: '-25%',
                oldPrice: '25.000 ₫',
                newPrice: '18.000 ₫'
            },
            {
                id: 24,
                category: 'san-lap',
                categoryLabel: 'Vật Tư Phụ',
                name: 'Keo Dán Gạch, Keo Chà Ron Chống Thấm & Lưới Thủy Tinh',
                driveId: '1P2fePSvPXm6YIcNDixVa0YwFWshcHFDY',
                discount: '-20%',
                oldPrice: '185.000 ₫/bao',
                newPrice: '148.000 ₫/bao'
            }
        ];

        /* Tạo thẻ HTML sản phẩm chuẩn Flatsome (Chỉ giữ duy nhất % giảm giá góc trên bên trái, không dán nhãn phụ) */
        function createProductCardHTML(item) {
            const thumbUrl = 'https://drive.google.com/thumbnail?id=' + item.driveId + '&sz=w600';
            return `
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between group">
                    <div>
                        <div class="relative w-full aspect-square bg-slate-100 overflow-hidden cursor-pointer" onclick="openProductModal(${item.id})">
                            <span class="flatsome-sale-badge">${item.discount}</span>
                            <img src="${thumbUrl}" 
                                 onerror="handleDriveImageError(this, '${item.driveId}')"
                                 alt="${item.name}" 
                                 loading="lazy"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <div class="text-[10px] font-semibold text-slate-400 uppercase truncate">${item.categoryLabel}</div>
                            <h3 onclick="openProductModal(${item.id})" class="product-title-flatsome text-xs sm:text-[13px] font-bold text-slate-800 hover:text-brand-blue cursor-pointer mt-0.5">
                                ${item.name}
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 pt-1 border-t border-slate-100">
                        <div class="flex flex-wrap items-baseline gap-x-1.5 gap-y-0.5">
                            <del class="text-[10px] sm:text-[11px] text-slate-400">${item.oldPrice}</del>
                            <ins class="text-xs sm:text-[13px] font-extrabold text-brand-orange no-underline">${item.newPrice}</ins>
                        </div>
                        <div class="mt-2 flex items-center gap-1.5">
                            <a href="tel:0905182455" class="flex-1 bg-brand-blue hover:bg-brand-orange text-white text-[11px] font-semibold py-1.5 px-2 rounded text-center transition">
                                Liên hệ: 0905.182.455
                            </a>
                        </div>
                    </div>
                </div>
            `;
        }

        /* Render toàn bộ sản phẩm ra các khung danh mục trên trang chủ */
        function renderAllProducts(filterText = '') {
            const categories = ['gach-men', 'son-nuoc', 'sen-voi', 'cat-san-xi-mang', 'san-lap'];
            const keyword = filterText.trim().toLowerCase();

            categories.forEach(cat => {
                const container = document.getElementById('grid-' + cat);
                if (!container) return;
                const filtered = productsData.filter(p => {
                    const matchCat = p.category === cat;
                    const matchKeyword = !keyword || p.name.toLowerCase().includes(keyword) || p.categoryLabel.toLowerCase().includes(keyword);
                    return matchCat && matchKeyword;
                });
                container.innerHTML = filtered.map(createProductCardHTML).join('');
            });
        }

        /* Lọc theo danh mục khi người dùng bấm chọn */
        function filterProductsByCategory(cat) {
            const sections = document.querySelectorAll('.product-section-block');
            sections.forEach(sec => {
                if (cat === 'all' || sec.getAttribute('data-cat') === cat) {
                    sec.classList.remove('hidden');
                } else {
                    sec.classList.add('hidden');
                }
            });
        }

        /* Tìm kiếm sản phẩm trực tiếp */
        function searchProducts(query) {
            filterProductsByCategory('all');
            renderAllProducts(query);
        }

        /* Mở Modal chi tiết sản phẩm */
        function openProductModal(id) {
            const item = productsData.find(p => p.id === id);
            if (!item) return;
            const imgEl = document.getElementById('modalProductImg');
            imgEl.removeAttribute('data-fallback-step');
            imgEl.onerror = function() { handleDriveImageError(imgEl, item.driveId); };
            imgEl.src = 'https://drive.google.com/thumbnail?id=' + item.driveId + '&sz=w800';
            document.getElementById('modalSaleBadge').textContent = item.discount;
            document.getElementById('modalProductCat').textContent = item.categoryLabel;
            document.getElementById('modalProductName').textContent = item.name;
            document.getElementById('modalOldPrice').textContent = item.oldPrice;
            document.getElementById('modalNewPrice').textContent = item.newPrice;

            const modal = document.getElementById('productModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeProductModal() {
            const modal = document.getElementById('productModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        /* Đóng mở Menu trên điện thoại */
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            drawer.classList.toggle('hidden');
        }

        /* Xử lý gửi Form Yêu cầu & Báo giá trang chủ */
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value;
            const phone = document.getElementById('qPhone').value;
            const cat = document.getElementById('qCategory').value;
            const box = document.getElementById('quoteSuccessBox');
            box.innerHTML = `<i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá hạng mục <strong>${cat}</strong> đã được ghi nhận. Bộ phận kinh doanh <strong>Trung Mừng (0905.182.455 - 0905.432.455)</strong> sẽ liên hệ ngay!`;
            box.classList.remove('hidden');
            document.getElementById('quoteRequestForm').reset();
        }

        /* Điều khiển 2 Banner tự trượt chuyên nghiệp */
        let currentBannerIndex = 0;
        let bannerInterval = null;

        function showBanner(index) {
            currentBannerIndex = index;
            const s0 = document.getElementById('bannerSlide0');
            const s1 = document.getElementById('bannerSlide1');
            const d0 = document.getElementById('bannerDot0');
            const d1 = document.getElementById('bannerDot1');

            if (index === 0) {
                s0.classList.replace('opacity-0', 'opacity-100');
                s0.classList.replace('z-0', 'z-10');
                s1.classList.replace('opacity-100', 'opacity-0');
                s1.classList.replace('z-10', 'z-0');
                d0.className = 'w-6 h-2 rounded-full bg-brand-orange transition-all';
                d1.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
            } else {
                s1.classList.replace('opacity-0', 'opacity-100');
                s1.classList.replace('z-0', 'z-10');
                s0.classList.replace('opacity-100', 'opacity-0');
                s0.classList.replace('z-10', 'z-0');
                d1.className = 'w-6 h-2 rounded-full bg-brand-orange transition-all';
                d0.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
            }
        }

        function nextBanner() {
            showBanner(currentBannerIndex === 0 ? 1 : 0);
            resetBannerTimer();
        }

        function prevBanner() {
            showBanner(currentBannerIndex === 0 ? 1 : 0);
            resetBannerTimer();
        }

        function goToBanner(idx) {
            showBanner(idx);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                showBanner(currentBannerIndex === 0 ? 1 : 0);
            }, 5000);
        }

        window.onload = function() {
            renderAllProducts();
            resetBannerTimer();
        };
    </script>
</body>
</html>
