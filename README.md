<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY CỔ PHẦN NỒI HƠI VÀ THIẾT BỊ ÁP LỰC MIỀN TRUNG - noihoimientrung.com</title>
    <meta name="description" content="Công Ty Cổ Phần Nồi Hơi Và Thiết Bị Áp Lực Miền Trung - Chuyên thiết kế, chế tạo, lắp đặt, sửa chữa, bảo trì nồi hơi, lò hơi công nghiệp và thiết bị áp lực uy tín tại Đà Nẵng & toàn quốc. Hotline: 0974.669.288">
    
    <!-- Thumbnail là ảnh Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://noihoimientrung.com/">
    <meta property="og:title" content="CÔNG TY CỔ PHẦN NỒI HƠI VÀ THIẾT BỊ ÁP LỰC MIỀN TRUNG - noihoimientrung.com">
    <meta property="og:description" content="Chuyên thiết kế, chế tạo, lắp đặt, vận hành, bảo trì các loại lò hơi, nồi hơi, thiết bị áp lực tại 74 Trường Sơn, Phường Cẩm Lệ, TP. Đà Nẵng. ĐT: 0974.669.288">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1Kh5sj_k-4sMKuj3abwhCQaOYxoQDbVsG">
    <meta property="og:image:secure_url" content="https://drive.google.com/thumbnail?id=1Kh5sj_k-4sMKuj3abwhCQaOYxoQDbVsG&sz=w1200">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY CỔ PHẦN NỒI HƠI VÀ THIẾT BỊ ÁP LỰC MIỀN TRUNG">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1Kh5sj_k-4sMKuj3abwhCQaOYxoQDbVsG">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1Kh5sj_k-4sMKuj3abwhCQaOYxoQDbVsG">

    <!-- Tailwind CSS & Font Awesome & Google Font Inter -->
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
                        brandBlue: '#0b4f8a',
                        brandDark: '#07355e',
                        brandLight: '#eef6fc',
                        brandRed: '#d9251d',
                        brandOrange: '#ea580c'
                    },
                    maxWidth: {
                        'flatsome': '1500px'
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
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn Flatsome 1500px trên máy tính */
        .container-flatsome {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .container-flatsome {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Danh mục không xuống dòng bên trong tên danh mục */
        .cat-nowrap {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ, không tràn khung */
        .product-title-full {
            white-space: normal;
            word-break: break-word;
            overflow-wrap: break-word;
            line-height: 1.4;
        }

        /* Badge giảm giá chuẩn Flatsome góc trên bên trái */
        .flatsome-sale-badge {
            position: absolute;
            top: 10px;
            left: 10px;
            z-index: 10;
            background-color: #d9251d;
            color: #ffffff;
            font-weight: 700;
            font-size: 12px;
            width: 42px;
            height: 42px;
            border-radius: 9999px;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(217, 37, 29, 0.35);
            pointer-events: none;
        }
        @media (max-width: 640px) {
            .flatsome-sale-badge {
                width: 36px;
                height: 36px;
                font-size: 11px;
                top: 6px;
                left: 6px;
            }
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title) */
        .section-title-container {
            margin-bottom: 1.25rem;
        }
        .section-title-normal {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 8px;
            flex-wrap: wrap;
            gap: 8px;
        }
        .section-title-main {
            font-size: 1.15rem;
            font-weight: 800;
            color: #0b4f8a;
            text-transform: uppercase;
            position: relative;
        }
        @media (min-width: 768px) {
            .section-title-main {
                font-size: 1.35rem;
            }
        }
        .section-title-main::after {
            content: "";
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: #d9251d;
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 37, 29, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 37, 29, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 37, 29, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <!-- ==================== HEADER FLATSOME WRAPPER ==================== -->
    <header id="header" class="w-full bg-white shadow-sm sticky top-0 z-40">
        
        <!-- 1. TOP BAR -->
        <div class="bg-brandDark text-white text-xs py-1.5 border-b border-sky-900">
            <div class="container-flatsome flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 truncate">
                    <i class="fa-solid fa-building text-amber-400 shrink-0"></i>
                    <span class="font-medium truncate">CÔNG TY CỔ PHẦN NỒI HƠI VÀ THIẾT BỊ ÁP LỰC MIỀN TRUNG - <strong>noihoimientrung.com</strong></span>
                </div>
                <div class="hidden md:flex items-center gap-5 text-slate-200 shrink-0">
                    <span><i class="fa-solid fa-location-dot text-red-400 mr-1"></i>74 Trường Sơn, Phường Cẩm Lệ, Tp.Đà Nẵng</span>
                    <span><i class="fa-solid fa-phone-volume text-amber-400 mr-1"></i>Hotline: <strong class="text-white">0974.669.288</strong></span>
                </div>
            </div>
        </div>

        <!-- 2. HEADER MAIN (Logo nhỏ gọn, Không để nút gọi ngay trên header tránh tràn viền) -->
        <div class="bg-white py-2.5 border-b border-slate-100">
            <div class="container-flatsome flex items-center justify-between gap-3">
                
                <!-- Nút mở menu trên điện thoại -->
                <button id="mobileMenuBtn" onclick="toggleMobileMenu()" class="lg:hidden p-2 rounded-lg text-brandBlue hover:bg-slate-100 focus:outline-none shrink-0" aria-label="Menu">
                    <i class="fa-solid fa-bars text-xl"></i>
                </button>

                <!-- Logo chỉnh gọn nhỏ lại + Tên công ty -->
                <a href="#top" class="flex items-center gap-2.5 min-w-0">
                    <div class="w-11 h-11 md:w-12 md:h-12 rounded-lg border border-slate-200 bg-white p-1 flex items-center justify-center shrink-0 overflow-hidden shadow-sm">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1Kh5sj_k-4sMKuj3abwhCQaOYxoQDbVsG" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1Kh5sj_k-4sMKuj3abwhCQaOYxoQDbVsG&sz=w400';"
                            alt="Logo Nồi Hơi Miền Trung" 
                            class="max-h-full max-w-full object-contain"
                        >
                    </div>
                    <div class="min-w-0">
                        <div class="text-xs sm:text-sm md:text-base font-extrabold text-brandBlue leading-tight truncate">
                            NỒI HƠI & TB ÁP LỰC MIỀN TRUNG
                        </div>
                        <div class="text-[11px] text-slate-500 font-medium truncate">
                            MST: 0401481452 | ĐC: 74 Trường Sơn, Cẩm Lệ, Đà Nẵng
                        </div>
                    </div>
                </a>

                <!-- Ô tìm kiếm sản phẩm (giống mẫu noihoinamphat.com, gọn gàng không tràn viền) -->
                <div class="hidden md:flex items-center flex-1 max-w-md mx-4">
                    <div class="relative w-full">
                        <input 
                            type="text" 
                            id="searchInput"
                            onkeyup="searchProducts()"
                            placeholder="Tìm kiếm nồi hơi, lò hơi tầng sôi, bình góp hơi..." 
                            class="w-full pl-3.5 pr-10 py-2 text-xs border border-slate-300 rounded-lg focus:outline-none focus:border-brandBlue bg-slate-50"
                        >
                        <button onclick="searchProducts()" class="absolute right-1 top-1 bottom-1 px-3 bg-brandBlue text-white rounded-md text-xs hover:bg-brandDark">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </div>
                </div>

                <!-- Thông tin địa chỉ & giờ làm việc nhẹ nhàng trên máy tính (Không dùng nút gọi ngay) -->
                <div class="hidden xl:flex items-center gap-5 text-xs text-slate-600 shrink-0">
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-certificate text-brandBlue text-base"></i>
                        <div>
                            <div class="font-bold text-slate-800">An Toàn Chuẩn Quốc Gia</div>
                            <div class="text-[11px] text-slate-500">Kiểm định chất lượng 100%</div>
                        </div>
                    </div>
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-map-location-dot text-brandRed text-base"></i>
                        <div>
                            <div class="font-bold text-slate-800">74 Trường Sơn, Cẩm Lệ</div>
                            <div class="text-[11px] text-slate-500">TP. Đà Nẵng - Toàn Quốc</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- 3. HEADER BOTTOM - DANH MỤC TRÊN MÁY TÍNH (Viết liền trên 1 hàng chữ nhỏ gọn hoặc xuống hàng 2 nguyên cụm, không bao giờ gãy dòng tên danh mục) -->
        <nav class="hidden lg:block bg-brandBlue text-white">
            <div class="container-flatsome py-1.5">
                <ul class="flex flex-wrap items-center gap-x-1.5 gap-y-1 text-[12px] font-semibold">
                    <li>
                        <a href="#top" class="cat-nowrap px-2.5 py-1.5 rounded bg-brandRed text-white hover:bg-red-700 transition">
                            <i class="fa-solid fa-house mr-1.5 text-[11px]"></i>TRANG CHỦ
                        </a>
                    </li>
                    <li>
                        <a href="#gioi-thieu" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/15 transition">
                            GIỚI THIỆU
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham" onclick="filterCategory('all')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/15 transition">
                            NỒI HƠI ĐIỆN
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham" onclick="filterCategory('dau-gas')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/15 transition">
                            NỒI HƠI ĐỐT DẦU / ĐỐT GA
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham" onclick="filterCategory('tang-soi')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/15 transition">
                            LÒ HƠI TẦNG SÔI & BÁN TẦNG SÔI
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham" onclick="filterCategory('buong-dot-phu')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/15 transition">
                            LÒ ĐỐT CỦI BUỒNG ĐỐT PHỤ
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham" onclick="filterCategory('dot-bung')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/15 transition">
                            NỒI HƠI ĐỐT BỤNG & ỐNG LÒ
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham" onclick="filterCategory('lo-hoi-dung')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/15 transition">
                            LÒ HƠI ĐỨNG
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham" onclick="filterCategory('ap-luc')" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/15 transition">
                            BÌNH GÓP HƠI & THIẾT BỊ ÁP LỰC
                        </a>
                    </li>
                    <li>
                        <a href="#dich-vu" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/15 transition">
                            DỊCH VỤ LÒ HƠI
                        </a>
                    </li>
                    <li>
                        <a href="#doi-tac" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/15 transition">
                            ĐỐI TÁC
                        </a>
                    </li>
                    <li>
                        <a href="#bai-viet" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/15 transition">
                            TIN TỨC
                        </a>
                    </li>
                    <li>
                        <a href="#bao-gia" class="cat-nowrap px-2.5 py-1.5 rounded hover:bg-white/15 transition">
                            BÁO GIÁ & LIÊN HỆ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- MENU TRÊN ĐIỆN THOẠI (Drawer gọn đẹp) -->
        <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-b border-slate-200 shadow-lg">
            <div class="p-3 space-y-2">
                <div class="relative">
                    <input 
                        type="text" 
                        id="mobileSearchInput"
                        onkeyup="searchProductsMobile()"
                        placeholder="Tìm kiếm sản phẩm nồi hơi..." 
                        class="w-full pl-3 pr-9 py-2 text-xs border border-slate-300 rounded-lg"
                    >
                    <i class="fa-solid fa-magnifying-glass absolute right-3 top-2.5 text-slate-400 text-xs"></i>
                </div>
                <div class="grid grid-cols-2 gap-1.5 pt-1 text-xs font-semibold">
                    <a href="#top" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-brandLight text-brandBlue">Trang chủ</a>
                    <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700">Giới thiệu</a>
                    <a href="#san-pham" onclick="filterCategory('dien'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700">Nồi hơi điện</a>
                    <a href="#san-pham" onclick="filterCategory('dau-gas'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700">Nồi hơi đốt dầu/ga</a>
                    <a href="#san-pham" onclick="filterCategory('tang-soi'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700">Lò hơi tầng sôi</a>
                    <a href="#san-pham" onclick="filterCategory('buong-dot-phu'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700">Lò củi buồng đốt phụ</a>
                    <a href="#san-pham" onclick="filterCategory('dot-bung'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700">Nồi hơi đốt bụng</a>
                    <a href="#san-pham" onclick="filterCategory('ap-luc'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700">Bình góp hơi</a>
                    <a href="#dich-vu" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700">Dịch vụ sửa chữa</a>
                    <a href="#bao-gia" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-brandRed text-white text-center">Nhận báo giá</a>
                </div>
            </div>
        </div>
    </header>

    <!-- ==================== BANNER SLIDER TỰ TRƯỢT (2 SLIDE KÍCH THƯỚC BẰNG NHAU) ==================== -->
    <!-- Thiết kế riêng ảnh banner Máy Tính và ảnh banner Điện Thoại để chữ nằm gọn 100% bên trong ảnh, không tràn viền -->
    <section id="top" class="w-full py-3 bg-white border-b border-slate-200">
        <div class="container-flatsome">
            <div class="relative w-full overflow-hidden rounded-xl shadow-md border border-slate-200">

                <!-- ========== SLIDE 1 ========== -->
                <div class="banner-slide block transition-opacity duration-500" data-slide="0">
                    
                    <!-- BANNER 1: PHIÊN BẢN MÁY TÍNH (Chiều cao cố định 380px bằng nhau) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center w-full h-[380px] bg-gradient-to-r from-[#062c4d] via-[#0b4f8a] to-[#0f3d68] text-white px-10 lg:px-14 relative overflow-hidden">
                        <div class="col-span-7 space-y-3 z-10 pr-4">
                            <div class="inline-block bg-amber-500 text-slate-950 font-extrabold text-xs px-3 py-1 rounded uppercase tracking-wider">
                                CÔNG TY CỔ PHẦN NỒI HƠI VÀ THIẾT BỊ ÁP LỰC MIỀN TRUNG
                            </div>
                            <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-white">
                                CHẾ TẠO, LẮP ĐẶT NỒI HƠI CÔNG NGHIỆP & THIẾT BỊ ÁP LỰC UY TÍN HÀNG ĐẦU
                            </h1>
                            <p class="text-xs lg:text-sm text-sky-100 leading-relaxed max-w-2xl">
                                Chuyên cung cấp: Lò hơi tầng sôi, nồi hơi đốt dầu/gas, nồi hơi điện, lò đốt củi buồng đốt phụ, bình góp hơi, bồn chứa áp lực đạt chuẩn kiểm định an toàn quốc gia.
                            </p>
                            <div class="grid grid-cols-2 gap-2 pt-1 text-xs text-amber-300 font-semibold max-w-xl">
                                <div><i class="fa-solid fa-Location-dot mr-1.5"></i>ĐC: 74 Trường Sơn, P. Cẩm Lệ, TP. Đà Nẵng</div>
                                <div><i class="fa-solid fa-phone mr-1.5"></i>Hotline tư vấn: 0974.669.288</div>
                                <div><i class="fa-solid fa-globe mr-1.5"></i>Website: noihoimientrung.com</div>
                                <div><i class="fa-solid fa-shield-halved mr-1.5"></i>Đặt an toàn trên lợi nhuận</div>
                            </div>
                            <div class="pt-2 flex items-center gap-3">
                                <a href="#bao-gia" class="px-4 py-2 bg-brandRed hover:bg-red-700 text-white font-bold text-xs rounded-lg shadow transition">
                                    YÊU CẦU BÁO GIÁ NGAY
                                </a>
                                <a href="#san-pham" class="px-4 py-2 bg-white/15 hover:bg-white/25 text-white font-semibold text-xs rounded-lg border border-white/30 transition">
                                    XEM DANH MỤC SẢN PHẨM
                                </a>
                            </div>
                        </div>
                        <div class="col-span-5 flex items-center justify-center z-10 h-full py-5">
                            <div class="w-full h-[300px] rounded-xl overflow-hidden border-2 border-white/30 shadow-xl bg-slate-900/40 flex items-center justify-center p-2">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1oUNgeOeIAYZ790zpUl8sFmVj6z-PsG0A" 
                                    onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1oUNgeOeIAYZ790zpUl8sFmVj6z-PsG0A&sz=w1000';"
                                    alt="Hệ thống nồi hơi công nghiệp Miền Trung" 
                                    class="w-full h-full object-cover rounded-lg"
                                >
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 1: PHIÊN BẢN ĐIỆN THOẠI RIÊNG BIỆT (Chữ nhỏ gọn nằm hết trong khung 270px, không tràn viền) -->
                    <div class="flex md:hidden flex-col justify-between w-full h-[270px] bg-gradient-to-b from-[#062c4d] to-[#0b4f8a] text-white p-4 relative overflow-hidden">
                        <div class="flex items-center gap-2.5">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1oUNgeOeIAYZ790zpUl8sFmVj6z-PsG0A" 
                                onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1oUNgeOeIAYZ790zpUl8sFmVj6z-PsG0A&sz=w600';"
                                alt="Nồi hơi Miền Trung" 
                                class="w-20 h-20 rounded-lg object-cover border border-white/30 shrink-0"
                            >
                            <div class="min-w-0">
                                <span class="inline-block bg-amber-400 text-slate-900 font-bold text-[10px] px-2 py-0.5 rounded mb-1">
                                    noihoimientrung.com
                                </span>
                                <h2 class="text-xs font-extrabold leading-snug text-white">
                                    CTY CP NỒI HƠI & THIẾT BỊ ÁP LỰC MIỀN TRUNG
                                </h2>
                                <p class="text-[11px] text-amber-300 font-semibold mt-0.5">
                                    Hotline: 0974.669.288
                                </p>
                            </div>
                        </div>
                        <div class="bg-white/10 rounded-lg p-2.5 text-[11px] text-sky-100 leading-relaxed">
                            Chế tạo & lắp đặt Lò hơi tầng sôi, Nồi hơi đốt dầu/gas, Nồi hơi điện, Bình góp hơi chuẩn an toàn.
                            <div class="text-white font-medium mt-1">
                                <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>74 Trường Sơn, P. Cẩm Lệ, TP. Đà Nẵng
                            </div>
                        </div>
                        <div class="flex items-center justify-between gap-2">
                            <a href="#bao-gia" class="flex-1 text-center py-1.5 bg-brandRed text-white font-bold text-[11px] rounded-md">
                                NHẬN BÁO GIÁ
                            </a>
                            <a href="#san-pham" class="flex-1 text-center py-1.5 bg-white/20 text-white font-semibold text-[11px] rounded-md">
                                XEM SẢN PHẨM
                            </a>
                        </div>
                    </div>
                </div>

                <!-- ========== SLIDE 2 (KÍCH THƯỚC BẰNG HỆT SLIDE 1) ========== -->
                <div class="banner-slide hidden transition-opacity duration-500" data-slide="1">
                    
                    <!-- BANNER 2: PHIÊN BẢN MÁY TÍNH (Chiều cao cố định 380px bằng nhau) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center w-full h-[380px] bg-gradient-to-r from-[#0f2942] via-[#104e78] to-[#072c47] text-white px-10 lg:px-14 relative overflow-hidden">
                        <div class="col-span-7 space-y-3 z-10 pr-4">
                            <div class="inline-block bg-brandRed text-white font-extrabold text-xs px-3 py-1 rounded uppercase tracking-wider">
                                DỊCH VỤ KỸ THUẬT LÒ HƠI & ÁP LỰC TOÀN DIỆN
                            </div>
                            <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-white">
                                BẢO TRÌ, SỬA CHỮA, CẢI TẠO & CUNG CẤP HƠI CÔNG NGHIỆP TIẾT KIỆM NHIÊN LIỆU
                            </h2>
                            <p class="text-xs lg:text-sm text-sky-100 leading-relaxed max-w-2xl">
                                Đội ngũ kỹ sư giàu kinh nghiệm thực hiện lắp đặt trọn gói, tẩy rửa cáu cặn, nâng cấp buồng đốt phụ, xử lý khí thải đạt chuẩn môi trường và cung cấp chất đốt sinh khối.
                            </p>
                            <div class="grid grid-cols-2 gap-2 pt-1 text-xs text-amber-300 font-semibold max-w-xl">
                                <div><i class="fa-solid fa-check-circle mr-1.5"></i>Tiết kiệm 20% - 35% chi phí đốt</div>
                                <div><i class="fa-solid fa-check-circle mr-1.5"></i>Hỗ trợ kỹ thuật 24/7 tại nhà máy</div>
                                <div><i class="fa-solid fa-check-circle mr-1.5"></i>ĐC: 74 Trường Sơn, Cẩm Lệ, Đà Nẵng</div>
                                <div><i class="fa-solid fa-check-circle mr-1.5"></i>Liên hệ: 0974.669.288</div>
                            </div>
                            <div class="pt-2 flex items-center gap-3">
                                <a href="#dich-vu" class="px-4 py-2 bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs rounded-lg shadow transition">
                                    DỊCH VỤ BẢO TRÌ & SỬA CHỮA
                                </a>
                                <a href="#ket-noi" class="px-4 py-2 bg-white/15 hover:bg-white/25 text-white font-semibold text-xs rounded-lg border border-white/30 transition">
                                    XEM BẢN ĐỒ & FANPAGE
                                </a>
                            </div>
                        </div>
                        <div class="col-span-5 flex items-center justify-center z-10 h-full py-5">
                            <div class="w-full h-[300px] rounded-xl overflow-hidden border-2 border-white/30 shadow-xl bg-slate-900/40 flex items-center justify-center p-2">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1ti8mvI6RxhlS6W-8Hrtu-2ez7jyuBHd1" 
                                    onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1ti8mvI6RxhlS6W-8Hrtu-2ez7jyuBHd1&sz=w1000';"
                                    alt="Chế tạo lắp đặt lò hơi thực tế" 
                                    class="w-full h-full object-cover rounded-lg"
                                >
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2: PHIÊN BẢN ĐIỆN THOẠI RIÊNG BIỆT (Chữ nhỏ gọn nằm hết trong khung 270px, không tràn viền) -->
                    <div class="flex md:hidden flex-col justify-between w-full h-[270px] bg-gradient-to-b from-[#0f2942] to-[#104e78] text-white p-4 relative overflow-hidden">
                        <div class="flex items-center gap-2.5">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1ti8mvI6RxhlS6W-8Hrtu-2ez7jyuBHd1" 
                                onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1ti8mvI6RxhlS6W-8Hrtu-2ez7jyuBHd1&sz=w600';"
                                alt="Bảo trì sửa chữa nồi hơi" 
                                class="w-20 h-20 rounded-lg object-cover border border-white/30 shrink-0"
                            >
                            <div class="min-w-0">
                                <span class="inline-block bg-brandRed text-white font-bold text-[10px] px-2 py-0.5 rounded mb-1">
                                    DỊCH VỤ CHUYÊN NGHIỆP
                                </span>
                                <h2 class="text-xs font-extrabold leading-snug text-white">
                                    SỬA CHỮA, BẢO TRÌ & CẢI TẠO HỆ THỐNG LÒ HƠI
                                </h2>
                                <p class="text-[11px] text-amber-300 font-semibold mt-0.5">
                                    Tư vấn 24/7: 0974.669.288
                                </p>
                            </div>
                        </div>
                        <div class="bg-white/10 rounded-lg p-2.5 text-[11px] text-sky-100 leading-relaxed">
                            Tối ưu hiệu suất đốt, tiết kiệm chi phí nhiên liệu, tẩy rửa và kiểm định nồi hơi công nghiệp toàn quốc.
                            <div class="text-white font-medium mt-1">
                                <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>74 Trường Sơn, P. Cẩm Lệ, TP. Đà Nẵng
                            </div>
                        </div>
                        <div class="flex items-center justify-between gap-2">
                            <a href="#dich-vu" class="flex-1 text-center py-1.5 bg-amber-400 text-slate-900 font-bold text-[11px] rounded-md">
                                XEM DỊCH VỤ
                            </a>
                            <a href="#bao-gia" class="flex-1 text-center py-1.5 bg-white/20 text-white font-semibold text-[11px] rounded-md">
                                ĐẶT LỊCH KHẢO SÁT
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng qua lại & Chấm tròn chỉ báo Slide -->
                <button onclick="changeSlide(-1)" class="absolute left-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/40 hover:bg-black/65 text-white flex items-center justify-center z-20" aria-label="Slide trước">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="changeSlide(1)" class="absolute right-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/40 hover:bg-black/65 text-white flex items-center justify-center z-20" aria-label="Slide tiếp">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button onclick="goToSlide(0)" class="slide-dot w-2.5 h-2.5 rounded-full bg-amber-400 transition-all"></button>
                    <button onclick="goToSlide(1)" class="slide-dot w-2.5 h-2.5 rounded-full bg-white/50 transition-all"></button>
                </div>

            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC SẢN PHẨM TRANG CHỦ (TỐI ƯU ĐẸP TRÊN MÁY TÍNH & ĐIỆN THOẠI) ==================== -->
    <!-- Lấy đúng danh mục sản phẩm từ web mẫu noihoinamphat.com, chữ nhỏ gọn, viết liền trên 1 hàng không bị xuống dòng bên trong tên danh mục -->
    <section class="py-5 bg-white border-b border-slate-200">
        <div class="container-flatsome">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">DANH MỤC SẢN PHẨM</h2>
                    <span class="text-xs text-slate-500">Chọn danh mục để lọc nhanh thiết bị</span>
                </div>
            </div>

            <!-- Danh mục hiển thị gọn gàng: trên máy tính tự dàn 1-2 hàng ngang chữ nhỏ gọn không gãy dòng; trên điện thoại chia 2 cột cân đối -->
            <div class="grid grid-cols-2 sm:grid-cols-3 md:flex md:flex-wrap items-center gap-2">
                <button onclick="filterCategory('all')" data-cat-btn="all" class="cat-filter-btn active-cat bg-brandBlue text-white px-3 py-2 rounded-lg text-[12px] font-semibold border border-brandBlue transition flex items-center justify-center md:justify-start gap-1.5">
                    <i class="fa-solid fa-border-all text-[11px] shrink-0"></i>
                    <span class="cat-nowrap">Tất cả sản phẩm</span>
                </button>
                <button onclick="filterCategory('dien')" data-cat-btn="dien" class="cat-filter-btn bg-slate-50 hover:bg-brandLight text-slate-700 hover:text-brandBlue px-3 py-2 rounded-lg text-[12px] font-semibold border border-slate-200 transition flex items-center justify-center md:justify-start gap-1.5">
                    <i class="fa-solid fa-bolt text-amber-500 text-[11px] shrink-0"></i>
                    <span class="cat-nowrap">Nồi hơi điện</span>
                </button>
                <button onclick="filterCategory('dau-gas')" data-cat-btn="dau-gas" class="cat-filter-btn bg-slate-50 hover:bg-brandLight text-slate-700 hover:text-brandBlue px-3 py-2 rounded-lg text-[12px] font-semibold border border-slate-200 transition flex items-center justify-center md:justify-start gap-1.5">
                    <i class="fa-solid fa-fire-flame-simple text-brandRed text-[11px] shrink-0"></i>
                    <span class="cat-nowrap">Nồi hơi đốt dầu/ đốt ga</span>
                </button>
                <button onclick="filterCategory('lo-dot-dau')" data-cat-btn="lo-dot-dau" class="cat-filter-btn bg-slate-50 hover:bg-brandLight text-slate-700 hover:text-brandBlue px-3 py-2 rounded-lg text-[12px] font-semibold border border-slate-200 transition flex items-center justify-center md:justify-start gap-1.5">
                    <i class="fa-solid fa-oil-can text-sky-600 text-[11px] shrink-0"></i>
                    <span class="cat-nowrap">Lò hơi đốt dầu</span>
                </button>
                <button onclick="filterCategory('tang-soi')" data-cat-btn="tang-soi" class="cat-filter-btn bg-slate-50 hover:bg-brandLight text-slate-700 hover:text-brandBlue px-3 py-2 rounded-lg text-[12px] font-semibold border border-slate-200 transition flex items-center justify-center md:justify-start gap-1.5">
                    <i class="fa-solid fa-industry text-brandBlue text-[11px] shrink-0"></i>
                    <span class="cat-nowrap">Lò hơi tầng sôi</span>
                </button>
                <button onclick="filterCategory('ban-tang-soi')" data-cat-btn="ban-tang-soi" class="cat-filter-btn bg-slate-50 hover:bg-brandLight text-slate-700 hover:text-brandBlue px-3 py-2 rounded-lg text-[12px] font-semibold border border-slate-200 transition flex items-center justify-center md:justify-start gap-1.5">
                    <i class="fa-solid fa-gears text-emerald-600 text-[11px] shrink-0"></i>
                    <span class="cat-nowrap">Lò bán tầng sôi</span>
                </button>
                <button onclick="filterCategory('buong-dot-phu')" data-cat-btn="buong-dot-phu" class="cat-filter-btn bg-slate-50 hover:bg-brandLight text-slate-700 hover:text-brandBlue px-3 py-2 rounded-lg text-[12px] font-semibold border border-slate-200 transition flex items-center justify-center md:justify-start gap-1.5">
                    <i class="fa-solid fa-fire text-orange-500 text-[11px] shrink-0"></i>
                    <span class="cat-nowrap">Lò hơi buồng đốt phụ</span>
                </button>
                <button onclick="filterCategory('cui-buong-phu')" data-cat-btn="cui-buong-phu" class="cat-filter-btn bg-slate-50 hover:bg-brandLight text-slate-700 hover:text-brandBlue px-3 py-2 rounded-lg text-[12px] font-semibold border border-slate-200 transition flex items-center justify-center md:justify-start gap-1.5">
                    <i class="fa-solid fa-tree text-green-700 text-[11px] shrink-0"></i>
                    <span class="cat-nowrap">Lò đốt củi buồng đốt phụ</span>
                </button>
                <button onclick="filterCategory('dot-bung')" data-cat-btn="dot-bung" class="cat-filter-btn bg-slate-50 hover:bg-brandLight text-slate-700 hover:text-brandBlue px-3 py-2 rounded-lg text-[12px] font-semibold border border-slate-200 transition flex items-center justify-center md:justify-start gap-1.5">
                    <i class="fa-solid fa-temperature-high text-red-600 text-[11px] shrink-0"></i>
                    <span class="cat-nowrap">Nồi hơi đốt bụng</span>
                </button>
                <button onclick="filterCategory('ong-lo')" data-cat-btn="ong-lo" class="cat-filter-btn bg-slate-50 hover:bg-brandLight text-slate-700 hover:text-brandBlue px-3 py-2 rounded-lg text-[12px] font-semibold border border-slate-200 transition flex items-center justify-center md:justify-start gap-1.5">
                    <i class="fa-solid fa-circle-dot text-indigo-600 text-[11px] shrink-0"></i>
                    <span class="cat-nowrap">Lò đốt ống lò</span>
                </button>
                <button onclick="filterCategory('lo-hoi-dung')" data-cat-btn="lo-hoi-dung" class="cat-filter-btn bg-slate-50 hover:bg-brandLight text-slate-700 hover:text-brandBlue px-3 py-2 rounded-lg text-[12px] font-semibold border border-slate-200 transition flex items-center justify-center md:justify-start gap-1.5">
                    <i class="fa-solid fa-arrows-up-down text-teal-600 text-[11px] shrink-0"></i>
                    <span class="cat-nowrap">Lò hơi đứng</span>
                </button>
                <button onclick="filterCategory('ap-luc')" data-cat-btn="ap-luc" class="cat-filter-btn bg-slate-50 hover:bg-brandLight text-slate-700 hover:text-brandBlue px-3 py-2 rounded-lg text-[12px] font-semibold border border-slate-200 transition flex items-center justify-center md:justify-start gap-1.5">
                    <i class="fa-solid fa-gauge-high text-brandBlue text-[11px] shrink-0"></i>
                    <span class="cat-nowrap">Bình góp hơi</span>
                </button>
            </div>
        </div>
    </section>

    <!-- ==================== SẢN PHẨM NỔI BẬT (8 ẢNH THỰC TẾ DRIVE + DANH MỤC WEB MẪU + % GIẢM GIÁ GÓC TRÊN TRÁI) ==================== -->
    <!-- Trên điện thoại chia đúng 2 cột (grid-cols-2), tên sản phẩm hiển thị đầy đủ không mất chữ, không để các nhãn dán dư thừa -->
    <section id="san-pham" class="py-7">
        <div class="container-flatsome">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">SẢN PHẨM NỒI HƠI & THIẾT BỊ ÁP LỰC</h2>
                    <a href="#bao-gia" class="text-xs font-bold text-brandBlue hover:text-brandRed">
                        Nhận bảng giá kỹ thuật chi tiết <i class="fa-solid fa-arrow-right ml-1"></i>
                    </a>
                </div>
            </div>

            <!-- Grid sản phẩm: 2 cột trên điện thoại, 3 cột tablet, 4 cột máy tính -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 md:gap-5">

                <!-- SẢN PHẨM 1 (Ảnh Drive 1: 1oUNgeOeIAYZ790zpUl8sFmVj6z-PsG0A) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="tang-soi">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <div class="flatsome-sale-badge">-15%</div>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1oUNgeOeIAYZ790zpUl8sFmVj6z-PsG0A" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1oUNgeOeIAYZ790zpUl8sFmVj6z-PsG0A&sz=w800';"
                            alt="Lò hơi tầng sôi, cấp liệu băng tải" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Lò hơi tầng sôi</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue mb-2">
                                Lò hơi tầng sôi, cấp liệu băng tải công nghiệp
                            </h3>
                        </div>
                        <div>
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-slate-400">450.000.000₫</del>
                                <span class="text-xs sm:text-sm font-extrabold text-brandRed">382.500.000₫</span>
                            </div>
                            <button onclick="selectProductForQuote('Lò hơi tầng sôi, cấp liệu băng tải công nghiệp')" class="w-full py-2 px-2 bg-brandBlue hover:bg-brandDark text-white font-semibold text-xs rounded-lg transition">
                                Liên hệ báo giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 2 (Ảnh Drive 2: 1ti8mvI6RxhlS6W-8Hrtu-2ez7jyuBHd1) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="dau-gas">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <div class="flatsome-sale-badge">-12%</div>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1ti8mvI6RxhlS6W-8Hrtu-2ez7jyuBHd1" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1ti8mvI6RxhlS6W-8Hrtu-2ez7jyuBHd1&sz=w800';"
                            alt="Nồi hơi đốt dầu/ đốt ga" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Nồi hơi đốt dầu / đốt ga</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue mb-2">
                                Nồi hơi đốt dầu / đốt ga nằm ngang tự động
                            </h3>
                        </div>
                        <div>
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-slate-400">250.000.000₫</del>
                                <span class="text-xs sm:text-sm font-extrabold text-brandRed">220.000.000₫</span>
                            </div>
                            <button onclick="selectProductForQuote('Nồi hơi đốt dầu / đốt ga nằm ngang tự động')" class="w-full py-2 px-2 bg-brandBlue hover:bg-brandDark text-white font-semibold text-xs rounded-lg transition">
                                Liên hệ báo giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 3 (Ảnh Drive 3: 1y7pGXbp6oQi-N_As1LLcSDVZO1wB-4Hh) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="buong-dot-phu">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <div class="flatsome-sale-badge">-15%</div>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1y7pGXbp6oQi-N_As1LLcSDVZO1wB-4Hh" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1y7pGXbp6oQi-N_As1LLcSDVZO1wB-4Hh&sz=w800';"
                            alt="Lò hơi buồng đốt phụ" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Lò hơi buồng đốt phụ</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue mb-2">
                                Lò hơi buồng đốt phụ đa nhiên liệu công suất cao
                            </h3>
                        </div>
                        <div>
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-slate-400">320.000.000₫</del>
                                <span class="text-xs sm:text-sm font-extrabold text-brandRed">272.000.000₫</span>
                            </div>
                            <button onclick="selectProductForQuote('Lò hơi buồng đốt phụ đa nhiên liệu công suất cao')" class="w-full py-2 px-2 bg-brandBlue hover:bg-brandDark text-white font-semibold text-xs rounded-lg transition">
                                Liên hệ báo giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 4 (Ảnh Drive 4: 1fn4LDHwqc3BSLhvf1fBa8-XvgXqOlg-M) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="ap-luc">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <div class="flatsome-sale-badge">-18%</div>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1fn4LDHwqc3BSLhvf1fBa8-XvgXqOlg-M" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1fn4LDHwqc3BSLhvf1fBa8-XvgXqOlg-M&sz=w800';"
                            alt="Bình góp hơi - Thiết bị áp lực" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Bình góp hơi & Thiết bị áp lực</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue mb-2">
                                Bình góp hơi phân phối áp suất & Bồn chịu áp lực
                            </h3>
                        </div>
                        <div>
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-slate-400">45.000.000₫</del>
                                <span class="text-xs sm:text-sm font-extrabold text-brandRed">36.900.000₫</span>
                            </div>
                            <button onclick="selectProductForQuote('Bình góp hơi phân phối áp suất & Bồn chịu áp lực')" class="w-full py-2 px-2 bg-brandBlue hover:bg-brandDark text-white font-semibold text-xs rounded-lg transition">
                                Liên hệ báo giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 5 (Ảnh Drive 5: 1jTG8-DNo2A2d6GjuryTi7Y3QjfFa0F24) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="dien">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <div class="flatsome-sale-badge">-10%</div>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1jTG8-DNo2A2d6GjuryTi7Y3QjfFa0F24" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1jTG8-DNo2A2d6GjuryTi7Y3QjfFa0F24&sz=w800';"
                            alt="Nồi hơi điện công nghiệp" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Nồi hơi điện</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue mb-2">
                                Nồi hơi điện tự động hoàn toàn an toàn sạch sẽ
                            </h3>
                        </div>
                        <div>
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-slate-400">95.000.000₫</del>
                                <span class="text-xs sm:text-sm font-extrabold text-brandRed">85.500.000₫</span>
                            </div>
                            <button onclick="selectProductForQuote('Nồi hơi điện tự động hoàn toàn an toàn sạch sẽ')" class="w-full py-2 px-2 bg-brandBlue hover:bg-brandDark text-white font-semibold text-xs rounded-lg transition">
                                Liên hệ báo giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 6 (Ảnh Drive 6: 15vCN9cndPwtqej2HVN2KTXmz0HzakWx4) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="dot-bung">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <div class="flatsome-sale-badge">-14%</div>
                        <img 
                            src="https://lh3.googleusercontent.com/d/15vCN9cndPwtqej2HVN2KTXmz0HzakWx4" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=15vCN9cndPwtqej2HVN2KTXmz0HzakWx4&sz=w800';"
                            alt="Nồi hơi đốt bụng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Nồi hơi đốt bụng</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue mb-2">
                                Nồi hơi đốt bụng đốt củi, than đá, viên nén mùn cưa
                            </h3>
                        </div>
                        <div>
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-slate-400">210.000.000₫</del>
                                <span class="text-xs sm:text-sm font-extrabold text-brandRed">180.600.000₫</span>
                            </div>
                            <button onclick="selectProductForQuote('Nồi hơi đốt bụng đốt củi, than đá, viên nén mùn cưa')" class="w-full py-2 px-2 bg-brandBlue hover:bg-brandDark text-white font-semibold text-xs rounded-lg transition">
                                Liên hệ báo giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 7 (Ảnh Drive 7: 1JhU6B4E-XrCOKA_jb-kuQlaP7NS-yfeB) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="cui-buong-phu">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <div class="flatsome-sale-badge">-16%</div>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1JhU6B4E-XrCOKA_jb-kuQlaP7NS-yfeB" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1JhU6B4E-XrCOKA_jb-kuQlaP7NS-yfeB&sz=w800';"
                            alt="Lò đốt củi buồng đốt phụ" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Lò đốt củi buồng đốt phụ</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue mb-2">
                                Lò đốt củi buồng đốt phụ hiệu suất nhiệt cao
                            </h3>
                        </div>
                        <div>
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-slate-400">290.000.000₫</del>
                                <span class="text-xs sm:text-sm font-extrabold text-brandRed">243.600.000₫</span>
                            </div>
                            <button onclick="selectProductForQuote('Lò đốt củi buồng đốt phụ hiệu suất nhiệt cao')" class="w-full py-2 px-2 bg-brandBlue hover:bg-brandDark text-white font-semibold text-xs rounded-lg transition">
                                Liên hệ báo giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 8 (Ảnh Drive 8: 1hzKJVpJktoJTtU2AGeUm47MqnqSxwFmL) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="ban-tang-soi">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <div class="flatsome-sale-badge">-15%</div>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1hzKJVpJktoJTtU2AGeUm47MqnqSxwFmL" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1hzKJVpJktoJTtU2AGeUm47MqnqSxwFmL&sz=w800';"
                            alt="Lò bán tầng sôi" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Lò bán tầng sôi</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue mb-2">
                                Lò bán tầng sôi đốt sinh khối Biomass, trấu, mùn cưa
                            </h3>
                        </div>
                        <div>
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-slate-400">360.000.000₫</del>
                                <span class="text-xs sm:text-sm font-extrabold text-brandRed">306.000.000₫</span>
                            </div>
                            <button onclick="selectProductForQuote('Lò bán tầng sôi đốt sinh khối Biomass, trấu, mùn cưa')" class="w-full py-2 px-2 bg-brandBlue hover:bg-brandDark text-white font-semibold text-xs rounded-lg transition">
                                Liên hệ báo giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 9 (Danh mục Lò hơi đốt dầu - web mẫu) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="lo-dot-dau">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <div class="flatsome-sale-badge">-12%</div>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1ti8mvI6RxhlS6W-8Hrtu-2ez7jyuBHd1" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1ti8mvI6RxhlS6W-8Hrtu-2ez7jyuBHd1&sz=w800';"
                            alt="Lò hơi đốt dầu DO/FO" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Lò hơi đốt dầu</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue mb-2">
                                Lò hơi đốt dầu DO / FO tiết kiệm nhiên liệu
                            </h3>
                        </div>
                        <div>
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-slate-400">240.000.000₫</del>
                                <span class="text-xs sm:text-sm font-extrabold text-brandRed">211.200.000₫</span>
                            </div>
                            <button onclick="selectProductForQuote('Lò hơi đốt dầu DO / FO tiết kiệm nhiên liệu')" class="w-full py-2 px-2 bg-brandBlue hover:bg-brandDark text-white font-semibold text-xs rounded-lg transition">
                                Liên hệ báo giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 10 (Danh mục Lò đốt ống lò - web mẫu) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="ong-lo">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <div class="flatsome-sale-badge">-15%</div>
                        <img 
                            src="https://lh3.googleusercontent.com/d/15vCN9cndPwtqej2HVN2KTXmz0HzakWx4" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=15vCN9cndPwtqej2HVN2KTXmz0HzakWx4&sz=w800';"
                            alt="Lò đốt ống lò" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Lò đốt ống lò</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue mb-2">
                                Lò đốt ống lò ống lửa công nghiệp 1000kg/h - 5000kg/h
                            </h3>
                        </div>
                        <div>
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-slate-400">260.000.000₫</del>
                                <span class="text-xs sm:text-sm font-extrabold text-brandRed">221.000.000₫</span>
                            </div>
                            <button onclick="selectProductForQuote('Lò đốt ống lò ống lửa công nghiệp 1000kg/h - 5000kg/h')" class="w-full py-2 px-2 bg-brandBlue hover:bg-brandDark text-white font-semibold text-xs rounded-lg transition">
                                Liên hệ báo giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 11 (Danh mục Lò hơi đứng - web mẫu) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="lo-hoi-dung">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <div class="flatsome-sale-badge">-10%</div>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1jTG8-DNo2A2d6GjuryTi7Y3QjfFa0F24" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1jTG8-DNo2A2d6GjuryTi7Y3QjfFa0F24&sz=w800';"
                            alt="Lò hơi đứng công nghiệp" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Lò hơi đứng</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue mb-2">
                                Lò hơi đứng nhỏ gọn tiết kiệm diện tích nhà xưởng
                            </h3>
                        </div>
                        <div>
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-slate-400">135.000.000₫</del>
                                <span class="text-xs sm:text-sm font-extrabold text-brandRed">121.500.000₫</span>
                            </div>
                            <button onclick="selectProductForQuote('Lò hơi đứng nhỏ gọn tiết kiệm diện tích nhà xưởng')" class="w-full py-2 px-2 bg-brandBlue hover:bg-brandDark text-white font-semibold text-xs rounded-lg transition">
                                Liên hệ báo giá
                            </button>
                        </div>
                    </div>
                </div>

                <!-- SẢN PHẨM 12 (Danh mục Lò đốt bụng - web mẫu) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="dot-bung">
                    <div class="relative aspect-[4/3] bg-slate-100 overflow-hidden">
                        <div class="flatsome-sale-badge">-15%</div>
                        <img 
                            src="https://lh3.googleusercontent.com/d/1oUNgeOeIAYZ790zpUl8sFmVj6z-PsG0A" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1oUNgeOeIAYZ790zpUl8sFmVj6z-PsG0A&sz=w800';"
                            alt="Lò đốt bụng công nghiệp" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 md:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Lò đốt bụng</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-brandBlue mb-2">
                                Lò đốt bụng ngang truyền nhiệt nhanh độ bền cao
                            </h3>
                        </div>
                        <div>
                            <div class="flex flex-wrap items-baseline gap-1.5 mb-2.5">
                                <del class="text-[11px] text-slate-400">195.000.000₫</del>
                                <span class="text-xs sm:text-sm font-extrabold text-brandRed">165.750.000₫</span>
                            </div>
                            <button onclick="selectProductForQuote('Lò đốt bụng ngang truyền nhiệt nhanh độ bền cao')" class="w-full py-2 px-2 bg-brandBlue hover:bg-brandDark text-white font-semibold text-xs rounded-lg transition">
                                Liên hệ báo giá
                            </button>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==================== GIỚI THIỆU & NĂNG LỰC (THEO MẪU NOIHOINAMPHAT.COM) ==================== -->
    <section id="gioi-thieu" class="py-8 bg-white border-y border-slate-200">
        <div class="container-flatsome">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                <div class="lg:col-span-7 space-y-3">
                    <div class="text-xs font-bold text-brandRed uppercase tracking-wider">
                        ĐẶT AN TOÀN TRÊN LỢI NHUẬN - UY TÍN HÀNG ĐẦU
                    </div>
                    <h2 class="text-lg md:text-2xl font-extrabold text-brandBlue leading-snug">
                        CÔNG TY CỔ PHẦN NỒI HƠI VÀ THIẾT BỊ ÁP LỰC MIỀN TRUNG
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        <strong>Công Ty Cổ Phần Nồi Hơi Và Thiết Bị Áp Lực Miền Trung</strong> (MST: 0401481452 - Website: <strong>noihoimientrung.com</strong>) có trụ sở tại <strong>74 Trường Sơn, Phường Cẩm Lệ, TP. Đà Nẵng</strong> chuyên thiết kế, chế tạo, lắp đặt, vận hành, sửa chữa và bảo trì các loại lò hơi, nồi hơi công nghiệp, bình chịu áp lực, hệ thống sấy và thiết bị nhiệt chất lượng cao.
                    </p>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Với đội ngũ kỹ sư và kỹ thuật viên lành nghề, chúng tôi thực hiện kiểm định an toàn nghiêm ngặt, bảo trì định kỳ, cải tạo buồng đốt giúp doanh nghiệp tối ưu hiệu suất sinh hơi, tiết kiệm nhiên liệu và kéo dài tuổi thọ thiết bị.
                    </p>

                    <!-- 4 Thông số giống web mẫu noihoinamphat.com -->
                    <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 pt-3">
                        <div class="bg-brandLight border border-sky-200 rounded-xl p-3 text-center">
                            <div class="text-xl md:text-2xl font-extrabold text-brandBlue">14+</div>
                            <div class="text-xs text-slate-600 font-medium">Năm kinh nghiệm</div>
                        </div>
                        <div class="bg-brandLight border border-sky-200 rounded-xl p-3 text-center">
                            <div class="text-xl md:text-2xl font-extrabold text-brandBlue">34+</div>
                            <div class="text-xs text-slate-600 font-medium">Tỉnh thành phục vụ</div>
                        </div>
                        <div class="bg-brandLight border border-sky-200 rounded-xl p-3 text-center">
                            <div class="text-xl md:text-2xl font-extrabold text-brandBlue">13000+</div>
                            <div class="text-xs text-slate-600 font-medium">Diện tích xưởng (m²)</div>
                        </div>
                        <div class="bg-brandLight border border-sky-200 rounded-xl p-3 text-center">
                            <div class="text-xl md:text-2xl font-extrabold text-brandBlue">1000+</div>
                            <div class="text-xs text-slate-600 font-medium">Số công trình</div>
                        </div>
                    </div>
                </div>

                <!-- Hình ảnh thực tế nhà xưởng / thiết bị -->
                <div class="lg:col-span-5 grid grid-cols-2 gap-3">
                    <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm aspect-[4/3]">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1y7pGXbp6oQi-N_As1LLcSDVZO1wB-4Hh" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1y7pGXbp6oQi-N_As1LLcSDVZO1wB-4Hh&sz=w600';"
                            alt="Chế tạo nồi hơi tại xưởng" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm aspect-[4/3]">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1fn4LDHwqc3BSLhvf1fBa8-XvgXqOlg-M" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1fn4LDHwqc3BSLhvf1fBa8-XvgXqOlg-M&sz=w600';"
                            alt="Thiết bị áp lực Miền Trung" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm aspect-[4/3]">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1JhU6B4E-XrCOKA_jb-kuQlaP7NS-yfeB" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1JhU6B4E-XrCOKA_jb-kuQlaP7NS-yfeB&sz=w600';"
                            alt="Lắp đặt hệ thống lò hơi" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm aspect-[4/3]">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1hzKJVpJktoJTtU2AGeUm47MqnqSxwFmL" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1hzKJVpJktoJTtU2AGeUm47MqnqSxwFmL&sz=w600';"
                            alt="Vận hành kiểm định nồi hơi" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DỊCH VỤ CỦA CHÚNG TÔI & VÌ SAO CHỌN CHÚNG TÔI ==================== -->
    <section id="dich-vu" class="py-7">
        <div class="container-flatsome">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">DỊCH VỤ NỒI HƠI & THIẾT BỊ ÁP LỰC</h2>
                    <span class="text-xs text-slate-500">Giải pháp nhiệt tối ưu – Hiệu suất vượt trội</span>
                </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mb-6">
                <div class="bg-white p-4 rounded-xl border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 rounded-lg bg-brandLight text-brandBlue flex items-center justify-center mb-3">
                            <i class="fa-solid fa-screwdriver-wrench text-lg"></i>
                        </div>
                        <h3 class="text-sm font-bold text-slate-800 mb-1.5">Dịch vụ sửa chữa, cải tạo nồi hơi công nghiệp</h3>
                        <p class="text-xs text-slate-600 leading-relaxed">
                            Khắc phục sự cố xì ống lửa, thay thế ghi lò, nâng cấp buồng đốt phụ, cải tạo lò đốt than/dầu sang đốt sinh khối biomass tiết kiệm chi phí.
                        </p>
                    </div>
                    <a href="#bao-gia" class="text-xs font-bold text-brandBlue hover:text-brandRed mt-3 inline-block">
                        Yêu cầu khảo sát <i class="fa-solid fa-angle-right ml-1"></i>
                    </a>
                </div>

                <div class="bg-white p-4 rounded-xl border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 rounded-lg bg-brandLight text-brandBlue flex items-center justify-center mb-3">
                            <i class="fa-solid fa-shield-heart text-lg"></i>
                        </div>
                        <h3 class="text-sm font-bold text-slate-800 mb-1.5">Dịch vụ bảo trì, bảo dưỡng & tẩy rửa cáu cặn lò hơi</h3>
                        <p class="text-xs text-slate-600 leading-relaxed">
                            Tẩy rửa cáu cặn hóa chất chuyên dụng, kiểm tra van an toàn, bơm cấp nước, tủ điện điều khiển và chuẩn bị hồ sơ kiểm định định kỳ.
                        </p>
                    </div>
                    <a href="#bao-gia" class="text-xs font-bold text-brandBlue hover:text-brandRed mt-3 inline-block">
                        Đăng ký lịch bảo trì <i class="fa-solid fa-angle-right ml-1"></i>
                    </a>
                </div>

                <div class="bg-white p-4 rounded-xl border border-slate-200 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 rounded-lg bg-brandLight text-brandBlue flex items-center justify-center mb-3">
                            <i class="fa-solid fa-leaf text-lg"></i>
                        </div>
                        <h3 class="text-sm font-bold text-slate-800 mb-1.5">Cung cấp hơi bão hòa & Nhiên liệu đốt Biomass</h3>
                        <p class="text-xs text-slate-600 leading-relaxed">
                            Cung cấp củi trấu ép, viên nén mùn cưa, dăm bào, bã mía và lắp đặt hệ thống bếp ăn công nghiệp, tủ cơm, thiết bị trao đổi nhiệt.
                        </p>
                    </div>
                    <a href="#bao-gia" class="text-xs font-bold text-brandBlue hover:text-brandRed mt-3 inline-block">
                        Nhận báo giá chất đốt <i class="fa-solid fa-angle-right ml-1"></i>
                    </a>
                </div>
            </div>

            <!-- 5 Cam kết Vì sao chọn chúng tôi (từ web mẫu noihoinamphat.com) -->
            <div class="grid grid-cols-2 sm:grid-cols-5 gap-3 bg-brandBlue text-white p-4 rounded-xl">
                <div class="flex items-center gap-2.5">
                    <i class="fa-solid fa-circle-check text-amber-400 text-lg shrink-0"></i>
                    <span class="text-xs font-semibold">An toàn kiểm định 100%</span>
                </div>
                <div class="flex items-center gap-2.5">
                    <i class="fa-solid fa-compass-drafting text-amber-400 text-lg shrink-0"></i>
                    <span class="text-xs font-semibold">Tư vấn đúng công suất</span>
                </div>
                <div class="flex items-center gap-2.5">
                    <i class="fa-solid fa-piggy-bank text-amber-400 text-lg shrink-0"></i>
                    <span class="text-xs font-semibold">Cải tiến, tiết kiệm đốt</span>
                </div>
                <div class="flex items-center gap-2.5">
                    <i class="fa-solid fa-award text-amber-400 text-lg shrink-0"></i>
                    <span class="text-xs font-semibold">Sản phẩm bền bỉ giá trị</span>
                </div>
                <div class="col-span-2 sm:col-span-1 flex items-center gap-2.5">
                    <i class="fa-solid fa-medal text-amber-400 text-lg shrink-0"></i>
                    <span class="text-xs font-semibold">Thương hiệu từ năm 2012</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ ==================== -->
    <section id="bao-gia" class="py-8 bg-white border-y border-slate-200">
        <div class="container-flatsome">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">FORM YÊU CẦU TƯ VẤN & BÁO GIÁ NHANH</h2>
                    <span class="text-xs text-slate-500">Phản hồi báo giá kỹ thuật trong vòng 15 phút</span>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Cột thông tin hỗ trợ kỹ thuật -->
                <div class="lg:col-span-5 bg-gradient-to-br from-brandDark to-brandBlue text-white rounded-xl p-5 flex flex-col justify-between">
                    <div class="space-y-3">
                        <h3 class="text-base md:text-lg font-extrabold text-amber-400">
                            CÔNG TY CỔ PHẦN NỒI HƠI VÀ THIẾT BỊ ÁP LỰC MIỀN TRUNG
                        </h3>
                        <p class="text-xs text-sky-100 leading-relaxed">
                            Quý khách cần tư vấn lựa chọn công suất nồi hơi (từ 100 kg/h đến 20.000 kg/h), thiết kế bồn áp lực hoặc khảo sát sửa chữa tại nhà máy, vui lòng điền thông tin bên cạnh hoặc liên hệ trực tiếp:
                        </p>
                        <div class="space-y-2.5 pt-2 text-xs">
                            <div class="flex items-start gap-2.5">
                                <i class="fa-solid fa-location-dot text-amber-400 mt-1 shrink-0"></i>
                                <span><strong>Địa chỉ trụ sở:</strong> 74 Trường Sơn, Phường Cẩm Lệ, Tp.Đà Nẵng</span>
                            </div>
                            <div class="flex items-start gap-2.5">
                                <i class="fa-solid fa-industry text-amber-400 mt-1 shrink-0"></i>
                                <span><strong>Nhà máy chế tạo:</strong> Thôn Thạch Nhơn Tây, Xã Hòa Nhơn, Huyện Hòa Vang, TP. Đà Nẵng</span>
                            </div>
                            <div class="flex items-start gap-2.5">
                                <i class="fa-solid fa-phone-volume text-amber-400 mt-1 shrink-0"></i>
                                <span><strong>Hotline / Zalo:</strong> 0974.669.288 – ĐT: (0236) 3672072</span>
                            </div>
                            <div class="flex items-start gap-2.5">
                                <i class="fa-solid fa-globe text-amber-400 mt-1 shrink-0"></i>
                                <span><strong>Website:</strong> noihoimientrung.com</span>
                            </div>
                        </div>
                    </div>

                    <div class="mt-5 pt-4 border-t border-white/15 grid grid-cols-2 gap-2 text-xs">
                        <a href="tel:0974669288" class="py-2 px-3 rounded-lg bg-brandRed hover:bg-red-700 text-white font-bold text-center">
                            <i class="fa-solid fa-phone mr-1"></i>0974.669.288
                        </a>
                        <a href="https://zalo.me/0974669288" target="_blank" rel="noopener noreferrer" class="py-2 px-3 rounded-lg bg-sky-500 hover:bg-sky-600 text-white font-bold text-center">
                            <i class="fa-solid fa-comment-dots mr-1"></i>Chat Zalo Ngay
                        </a>
                    </div>
                </div>

                <!-- Cột Form Yêu Cầu Báo Giá -->
                <div class="lg:col-span-7 bg-slate-50 rounded-xl p-5 border border-slate-200">
                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3.5">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên / Tên doanh nghiệp *</label>
                                <input type="text" id="custName" required placeholder="Nhập họ tên hoặc tên công ty..." class="w-full px-3 py-2 text-xs bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-brandBlue">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại liên hệ *</label>
                                <input type="tel" id="custPhone" required placeholder="Ví dụ: 0974669288" class="w-full px-3 py-2 text-xs bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-brandBlue">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Sản phẩm / Dịch vụ quan tâm *</label>
                                <select id="custProduct" class="w-full px-3 py-2 text-xs bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-brandBlue">
                                    <option value="Lò hơi tầng sôi, cấp liệu băng tải">Lò hơi tầng sôi, cấp liệu băng tải</option>
                                    <option value="Lò bán tầng sôi đốt Biomass">Lò bán tầng sôi đốt Biomass</option>
                                    <option value="Nồi hơi đốt dầu / đốt ga">Nồi hơi đốt dầu / đốt ga</option>
                                    <option value="Lò hơi đốt dầu">Lò hơi đốt dầu</option>
                                    <option value="Lò hơi buồng đốt phụ">Lò hơi buồng đốt phụ</option>
                                    <option value="Lò đốt củi buồng đốt phụ">Lò đốt củi buồng đốt phụ</option>
                                    <option value="Nồi hơi điện công nghiệp">Nồi hơi điện công nghiệp</option>
                                    <option value="Nồi hơi đốt bụng / Lò đốt ống lò">Nồi hơi đốt bụng / Lò đốt ống lò</option>
                                    <option value="Lò hơi đứng">Lò hơi đứng</option>
                                    <option value="Bình góp hơi & Thiết bị áp lực">Bình góp hơi & Thiết bị áp lực</option>
                                    <option value="Dịch vụ sửa chữa, bảo trì, cải tạo nồi hơi">Dịch vụ sửa chữa, bảo trì, cải tạo nồi hơi</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Công suất yêu cầu & Tỉnh/Thành lắp đặt</label>
                                <input type="text" id="custCapacity" placeholder="VD: 2000 kg/h tại Đà Nẵng, Quảng Nam..." class="w-full px-3 py-2 text-xs bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-brandBlue">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Nội dung yêu cầu chi tiết</label>
                            <textarea id="custNote" rows="3" placeholder="Nhập yêu cầu kỹ thuật, áp suất làm việc, nhiên liệu đốt hoặc nhu cầu khảo sát thực tế..." class="w-full px-3 py-2 text-xs bg-white border border-slate-300 rounded-lg focus:outline-none focus:border-brandBlue"></textarea>
                        </div>

                        <button type="submit" class="w-full py-2.5 px-4 bg-brandRed hover:bg-red-700 text-white font-extrabold text-xs sm:text-sm rounded-lg shadow transition uppercase">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU NHẬN BÁO GIÁ NGAY
                        </button>

                        <!-- Thông báo gửi thành công (Thay cho alert) -->
                        <div id="quoteSuccessBox" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-medium"></div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC BÀI VIẾT TRANG CHỦ ==================== -->
    <section id="bai-viet" class="py-7">
        <div class="container-flatsome">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">DANH MỤC BÀI VIẾT & TIN TỨC KỸ THUẬT</h2>
                    <!-- Các tab danh mục bài viết -->
                    <div class="flex flex-wrap items-center gap-1.5">
                        <button onclick="filterPosts('all')" data-post-btn="all" class="post-cat-btn bg-brandBlue text-white px-2.5 py-1 rounded text-[11px] font-semibold cat-nowrap">
                            Tất cả bài viết
                        </button>
                        <button onclick="filterPosts('du-an')" data-post-btn="du-an" class="post-cat-btn bg-white text-slate-700 border border-slate-200 px-2.5 py-1 rounded text-[11px] font-semibold cat-nowrap">
                            Dự án bàn giao
                        </button>
                        <button onclick="filterPosts('ky-thuat')" data-post-btn="ky-thuat" class="post-cat-btn bg-white text-slate-700 border border-slate-200 px-2.5 py-1 rounded text-[11px] font-semibold cat-nowrap">
                            Kỹ thuật lò hơi
                        </button>
                        <button onclick="filterPosts('bao-tri')" data-post-btn="bao-tri" class="post-cat-btn bg-white text-slate-700 border border-slate-200 px-2.5 py-1 rounded text-[11px] font-semibold cat-nowrap">
                            Bảo trì & An toàn
                        </button>
                    </div>
                </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                <!-- Bài viết 1 -->
                <article class="post-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col" data-post-cat="du-an">
                    <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1oUNgeOeIAYZ790zpUl8sFmVj6z-PsG0A" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1oUNgeOeIAYZ790zpUl8sFmVj6z-PsG0A&sz=w600';"
                            alt="Bàn giao hệ thống lò hơi công nghiệp" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] font-bold text-brandBlue">Dự án bàn giao</span>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 mt-1 mb-1.5 leading-snug">
                                Bàn giao hệ thống lò hơi tầng sôi 3.500 kg/h tại KCN Miền Trung
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Hoàn thành chế tạo, lắp đặt và kiểm định an toàn hệ thống lò hơi tầng sôi đốt biomass tiết kiệm nhiên liệu cho nhà máy chế biến.
                            </p>
                        </div>
                        <a href="#bao-gia" class="text-xs font-bold text-brandRed mt-3 inline-block">Xem chi tiết &rarr;</a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="post-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col" data-post-cat="ky-thuat">
                    <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1ti8mvI6RxhlS6W-8Hrtu-2ez7jyuBHd1" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1ti8mvI6RxhlS6W-8Hrtu-2ez7jyuBHd1&sz=w600';"
                            alt="Đơn vị cung cấp lò hơi đốt dầu" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] font-bold text-brandBlue">Kỹ thuật lò hơi</span>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 mt-1 mb-1.5 leading-snug">
                                Giải pháp tiết kiệm 30% chi phí nhiên liệu với lò hơi buồng đốt phụ
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Phân tích ưu điểm của công nghệ buồng đốt phụ và lò bán tầng sôi khi chuyển đổi từ nhiên liệu hóa thạch sang củi trấu, dăm gỗ.
                            </p>
                        </div>
                        <a href="#bao-gia" class="text-xs font-bold text-brandRed mt-3 inline-block">Xem chi tiết &rarr;</a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="post-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col" data-post-cat="bao-tri">
                    <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1fn4LDHwqc3BSLhvf1fBa8-XvgXqOlg-M" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1fn4LDHwqc3BSLhvf1fBa8-XvgXqOlg-M&sz=w600';"
                            alt="Quy trình bảo dưỡng nồi hơi" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] font-bold text-brandBlue">Bảo trì & An toàn</span>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 mt-1 mb-1.5 leading-snug">
                                Quy trình kiểm định an toàn bình góp hơi và bảo dưỡng nồi hơi định kỳ
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Hướng dẫn kiểm tra van an toàn, áp kế, xử lý nước cấp lò hơi chống đóng cáu cặn và đảm bảo vận hành bền bỉ 24/7.
                            </p>
                        </div>
                        <a href="#bao-gia" class="text-xs font-bold text-brandRed mt-3 inline-block">Xem chi tiết &rarr;</a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="post-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col" data-post-cat="du-an">
                    <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1JhU6B4E-XrCOKA_jb-kuQlaP7NS-yfeB" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1JhU6B4E-XrCOKA_jb-kuQlaP7NS-yfeB&sz=w600';"
                            alt="Lắp đặt nồi hơi tại Đà Nẵng" 
                            class="w-full h-full object-cover"
                        >
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] font-bold text-brandBlue">Dự án bàn giao</span>
                            <h3 class="text-xs sm:text-sm font-bold text-slate-800 mt-1 mb-1.5 leading-snug">
                                Đơn vị chế tạo & sửa chữa nồi hơi công nghiệp uy tín tại Đà Nẵng
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Năng lực chế tạo trực tiếp tại xưởng Hòa Nhơn & văn phòng 74 Trường Sơn, Phường Cẩm Lệ, TP. Đà Nẵng phục vụ nhanh toàn khu vực.
                            </p>
                        </div>
                        <a href="#bao-gia" class="text-xs font-bold text-brandRed mt-3 inline-block">Xem chi tiết &rarr;</a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC ĐỐI TÁC TRANG CHỦ ==================== -->
    <section id="doi-tac" class="py-7 bg-white border-t border-slate-200">
        <div class="container-flatsome">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">DANH MỤC CÁC ĐỐI TÁC & KHÁCH HÀNG TIÊU BIỂU</h2>
                    <span class="text-xs text-slate-500">Đồng hành cùng các khu công nghiệp tại Đà Nẵng, Miền Trung & Toàn Quốc</span>
                </div>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <div class="p-3.5 rounded-xl border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-building-shield text-2xl text-brandBlue mb-1.5"></i>
                    <div class="text-xs font-bold text-slate-800">KCN Hòa Cầm & Hòa Khánh</div>
                    <div class="text-[11px] text-slate-500">Đối tác tại TP. Đà Nẵng</div>
                </div>
                <div class="p-3.5 rounded-xl border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-shirt text-2xl text-brandBlue mb-1.5"></i>
                    <div class="text-xs font-bold text-slate-800">Tập Đoàn Dệt May & Giặt Là</div>
                    <div class="text-[11px] text-slate-500">Hệ thống hơi bão hòa</div>
                </div>
                <div class="p-3.5 rounded-xl border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-fish-fins text-2xl text-brandBlue mb-1.5"></i>
                    <div class="text-xs font-bold text-slate-800">Nhà Máy Chế Biến Thủy Sản</div>
                    <div class="text-[11px] text-slate-500">Nồi hơi tiệt trùng & sấy</div>
                </div>
                <div class="p-3.5 rounded-xl border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-tree-city text-2xl text-brandBlue mb-1.5"></i>
                    <div class="text-xs font-bold text-slate-800">Nhà Máy Chế Biến Gỗ & Giấy</div>
                    <div class="text-[11px] text-slate-500">Lò sấy gỗ & Lò tầng sôi</div>
                </div>
                <div class="p-3.5 rounded-xl border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-wheat-awn text-2xl text-brandBlue mb-1.5"></i>
                    <div class="text-xs font-bold text-slate-800">Nhà Máy Thực Phẩm & Đồ Uống</div>
                    <div class="text-[11px] text-slate-500">Nồi hơi đốt dầu / điện</div>
                </div>
                <div class="p-3.5 rounded-xl border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-Industry text-2xl text-brandBlue mb-1.5"></i>
                    <div class="text-xs font-bold text-slate-800">KCN Chu Lai & VSIP</div>
                    <div class="text-[11px] text-slate-500">Thiết bị áp lực & Bảo trì</div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== ĐƯA FANPAGE FACEBOOK & ẢNH GOOGLE MAP RA NGOÀI TRANG CHỦ ==================== -->
    <section id="ket-noi" class="py-8 bg-slate-100 border-t border-slate-200">
        <div class="container-flatsome">
            <div class="section-title-container">
                <div class="section-title-normal">
                    <h2 class="section-title-main">KẾT NỐI FANPAGE FACEBOOK & BẢN ĐỒ GOOGLE MAP</h2>
                    <span class="text-xs text-slate-500">74 Trường Sơn, Phường Cẩm Lệ, Tp.Đà Nẵng</span>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
                
                <!-- 1. FANPAGE FACEBOOK NGOÀI TRANG CHỦ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 p-4 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between border-b border-slate-100 pb-3 mb-3">
                            <div class="flex items-center gap-2">
                                <i class="fa-brands fa-facebook text-blue-600 text-xl"></i>
                                <span class="text-xs sm:text-sm font-extrabold text-slate-800">FANPAGE FACEBOOK CHÍNH THỨC</span>
                            </div>
                            <a href="https://www.facebook.com/profile.php?id=100057648931640" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-blue-600 hover:underline">
                                Mở Facebook <i class="fa-solid fa-up-right-from-square ml-1 text-[10px]"></i>
                            </a>
                        </div>

                        <!-- Khung hiển thị trực quan Fanpage + Iframe Plugin Facebook -->
                        <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 mb-3">
                            <div class="bg-gradient-to-r from-brandDark to-brandBlue p-3.5 text-white flex items-center gap-3">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1Kh5sj_k-4sMKuj3abwhCQaOYxoQDbVsG" 
                                    onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1Kh5sj_k-4sMKuj3abwhCQaOYxoQDbVsG&sz=w300';"
                                    alt="Logo Fanpage" 
                                    class="w-12 h-12 rounded-lg bg-white p-1 object-contain shrink-0"
                                >
                                <div class="min-w-0">
                                    <div class="text-xs sm:text-sm font-bold leading-snug">
                                        Công Ty Cổ Phần Nồi Hơi Và Thiết Bị Áp Lực Miền Trung
                                    </div>
                                    <div class="text-[11px] text-sky-200 mt-0.5">
                                        Chế tạo, lắp đặt & bảo trì nồi hơi công nghiệp – 0974.669.288
                                    </div>
                                </div>
                            </div>
                            <div class="p-3 space-y-2 text-xs text-slate-600">
                                <div class="grid grid-cols-3 gap-2">
                                    <img src="https://lh3.googleusercontent.com/d/1oUNgeOeIAYZ790zpUl8sFmVj6z-PsG0A" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1oUNgeOeIAYZ790zpUl8sFmVj6z-PsG0A&sz=w400';" alt="Ảnh thực tế 1" class="w-full h-16 object-cover rounded border border-slate-200">
                                    <img src="https://lh3.googleusercontent.com/d/1ti8mvI6RxhlS6W-8Hrtu-2ez7jyuBHd1" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1ti8mvI6RxhlS6W-8Hrtu-2ez7jyuBHd1&sz=w400';" alt="Ảnh thực tế 2" class="w-full h-16 object-cover rounded border border-slate-200">
                                    <img src="https://lh3.googleusercontent.com/d/1y7pGXbp6oQi-N_As1LLcSDVZO1wB-4Hh" onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1y7pGXbp6oQi-N_As1LLcSDVZO1wB-4Hh&sz=w400';" alt="Ảnh thực tế 3" class="w-full h-16 object-cover rounded border border-slate-200">
                                </div>
                                <p class="text-[11px] text-slate-600">
                                    Cập nhật hình ảnh chế tạo nồi hơi, bình góp hơi và bàn giao công trình thực tế trên Fanpage chính thức của công ty.
                                </p>
                            </div>
                        </div>
                    </div>

                    <div class="flex flex-wrap gap-2">
                        <a href="https://www.facebook.com/profile.php?id=100057648931640" target="_blank" rel="noopener noreferrer" class="flex-1 py-2.5 px-3 bg-blue-600 hover:bg-blue-700 text-white font-bold text-xs rounded-lg text-center transition">
                            <i class="fa-brands fa-facebook-f mr-1.5"></i>THEO DÕI TRANG FANPAGE
                        </a>
                        <a href="https://www.facebook.com/profile.php?id=100057648931640" target="_blank" rel="noopener noreferrer" class="py-2.5 px-3 bg-slate-100 hover:bg-slate-200 text-slate-700 font-semibold text-xs rounded-lg text-center transition">
                            <i class="fa-brands fa-facebook-messenger text-blue-600 mr-1"></i>Nhắn tin
                        </a>
                    </div>
                </div>

                <!-- 2. ẢNH & BẢN ĐỒ GOOGLE MAP NGOÀI TRANG CHỦ -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 p-4 shadow-sm flex flex-col justify-between">
                    <div class="flex flex-wrap items-center justify-between gap-2 border-b border-slate-100 pb-3 mb-3">
                        <div class="flex items-center gap-2">
                            <i class="fa-solid fa-map-location-dot text-brandRed text-lg"></i>
                            <span class="text-xs sm:text-sm font-extrabold text-slate-800">BẢN ĐỒ ĐỊA CHỈ: 74 TRƯỜNG SƠN, PHƯỜNG CẨM LỆ, TP. ĐÀ NẴNG</span>
                        </div>
                        <a href="https://share.google/BisrkELRj7XyOftwd" target="_blank" rel="noopener noreferrer" class="px-3 py-1 bg-brandRed text-white rounded-md text-xs font-bold hover:bg-red-700 transition">
                            <i class="fa-solid fa-diamond-turn-right mr-1"></i>Mở Google Map chỉ đường
                        </a>
                    </div>

                    <!-- Bản đồ Google Map nhúng trực tiếp ngoài trang chủ -->
                    <div class="w-full h-[260px] sm:h-[290px] rounded-xl overflow-hidden border border-slate-200 relative bg-slate-100">
                        <iframe 
                            title="Bản đồ Công Ty Cổ Phần Nồi Hơi Và Thiết Bị Áp Lực Miền Trung - 74 Trường Sơn, Cẩm Lệ, Đà Nẵng"
                            src="https://maps.google.com/maps?q=74%20Tr%C6%B0%E1%BB%9Dng%20S%C6%A1n,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed" 
                            class="w-full h-full border-0" 
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>

                    <div class="mt-3 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-600">
                        <div>
                            <i class="fa-solid fa-location-dot text-brandRed mr-1"></i>
                            <strong>Địa chỉ:</strong> 74 Trường Sơn, Phường Cẩm Lệ, Tp.Đà Nẵng | <strong>ĐT:</strong> 0974.669.288
                        </div>
                        <a href="https://share.google/BisrkELRj7XyOftwd" target="_blank" rel="noopener noreferrer" class="text-brandBlue font-bold hover:underline">
                            Link Map: https://share.google/BisrkELRj7XyOftwd
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==================== FOOTER CHUẨN FLATSOME ==================== -->
    <footer class="bg-brandDark text-slate-200 pt-8 pb-20 md:pb-8 border-t-4 border-brandRed">
        <div class="container-flatsome">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-sky-900">
                
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5 space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1Kh5sj_k-4sMKuj3abwhCQaOYxoQDbVsG" 
                            onerror="this.onerror=null; this.src='https://drive.google.com/thumbnail?id=1Kh5sj_k-4sMKuj3abwhCQaOYxoQDbVsG&sz=w300';"
                            alt="Logo" 
                            class="w-10 h-10 rounded bg-white p-1 object-contain shrink-0"
                        >
                        <h3 class="text-xs sm:text-sm font-extrabold text-white leading-snug">
                            CÔNG TY CỔ PHẦN NỒI HƠI VÀ THIẾT BỊ ÁP LỰC MIỀN TRUNG
                        </h3>
                    </div>
                    <p class="text-xs text-slate-300 leading-relaxed">
                        Chuyên thiết kế, chế tạo, lắp đặt, vận hành, sửa chữa, bảo trì các loại lò hơi, nồi hơi công nghiệp, bình góp hơi, thiết bị trao đổi nhiệt, hệ thống sấy, lò hơi đốt biomass.
                    </p>
                    <ul class="text-xs space-y-1.5 text-slate-200">
                        <li><i class="fa-solid fa-location-dot text-amber-400 mr-2"></i><strong>Địa chỉ:</strong> 74 Trường Sơn, Phường Cẩm Lệ, Tp.Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-amber-400 mr-2"></i><strong>Điện thoại / Hotline:</strong> 0974.669.288 – (0236) 3672072</li>
                        <li><i class="fa-solid fa-id-card text-amber-400 mr-2"></i><strong>Mã số thuế:</strong> 0401481452</li>
                        <li><i class="fa-solid fa-globe text-amber-400 mr-2"></i><strong>Website:</strong> noihoimientrung.com</li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div class="lg:col-span-4 space-y-2">
                    <h4 class="text-xs sm:text-sm font-extrabold text-amber-400 uppercase">DANH MỤC SẢN PHẨM CHÍNH</h4>
                    <div class="grid grid-cols-2 gap-1.5 text-xs text-slate-300">
                        <a href="#san-pham" onclick="filterCategory('dien')" class="hover:text-white">&bull; Nồi hơi điện</a>
                        <a href="#san-pham" onclick="filterCategory('dau-gas')" class="hover:text-white">&bull; Nồi hơi đốt dầu/ đốt ga</a>
                        <a href="#san-pham" onclick="filterCategory('lo-dot-dau')" class="hover:text-white">&bull; Lò hơi đốt dầu</a>
                        <a href="#san-pham" onclick="filterCategory('tang-soi')" class="hover:text-white">&bull; Lò hơi tầng sôi</a>
                        <a href="#san-pham" onclick="filterCategory('ban-tang-soi')" class="hover:text-white">&bull; Lò bán tầng sôi</a>
                        <a href="#san-pham" onclick="filterCategory('buong-dot-phu')" class="hover:text-white">&bull; Lò hơi buồng đốt phụ</a>
                        <a href="#san-pham" onclick="filterCategory('cui-buong-phu')" class="hover:text-white">&bull; Lò đốt củi buồng phụ</a>
                        <a href="#san-pham" onclick="filterCategory('dot-bung')" class="hover:text-white">&bull; Nồi hơi đốt bụng</a>
                        <a href="#san-pham" onclick="filterCategory('ong-lo')" class="hover:text-white">&bull; Lò đốt ống lò</a>
                        <a href="#san-pham" onclick="filterCategory('ap-luc')" class="hover:text-white">&bull; Bình góp hơi</a>
                    </div>
                </div>

                <!-- Cột 3: Liên kết nhanh -->
                <div class="lg:col-span-3 space-y-2">
                    <h4 class="text-xs sm:text-sm font-extrabold text-amber-400 uppercase">LIÊN KẾT NHANH</h4>
                    <ul class="space-y-1.5 text-xs text-slate-300">
                        <li><a href="#gioi-thieu" class="hover:text-white">Giới thiệu năng lực công ty</a></li>
                        <li><a href="#dich-vu" class="hover:text-white">Dịch vụ sửa chữa & bảo trì lò hơi</a></li>
                        <li><a href="#bao-gia" class="hover:text-white">Yêu cầu báo giá nồi hơi</a></li>
                        <li><a href="https://www.facebook.com/profile.php?id=100057648931640" target="_blank" rel="noopener noreferrer" class="hover:text-white">Fanpage Facebook chính thức</a></li>
                        <li><a href="https://share.google/BisrkELRj7XyOftwd" target="_blank" rel="noopener noreferrer" class="hover:text-white">Bản đồ chỉ đường Google Map</a></li>
                    </ul>
                </div>

            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-xs text-slate-400 gap-2">
                <div>Bản quyền © CÔNG TY CỔ PHẦN NỒI HƠI VÀ THIẾT BỊ ÁP LỰC MIỀN TRUNG - <strong>noihoimientrung.com</strong></div>
                <div>Địa chỉ: 74 Trường Sơn, Phường Cẩm Lệ, Tp.Đà Nẵng | SĐT: 0974.669.288</div>
            </div>
        </div>
    </footer>

    <!-- ==================== NÚT LIÊN HỆ NỔI BẬT ZALO, FACEBOOK, HOTLINE (TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI) ==================== -->
    <div class="fixed left-3 bottom-4 z-50 flex flex-col gap-2.5">
        <!-- Nút Zalo -->
        <a href="https://zalo.me/0974669288" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 bg-sky-600 hover:bg-sky-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-sky-600 font-extrabold text-xs flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Chat Zalo: 0974.669.288</span>
        </a>

        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/profile.php?id=100057648931640" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 bg-blue-700 hover:bg-blue-800 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-blue-700 flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Fanpage Facebook</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0974669288" class="pulse-btn flex items-center gap-2 bg-brandRed hover:bg-red-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-brandRed flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">0974.669.288</span>
        </a>
    </div>

    <!-- ==================== JAVASCRIPT XỬ LÝ SLIDER, LỌC DANH MỤC & FORM BÁO GIÁ ==================== -->
    <script>
        // 1. Tự động trượt 2 Banner (5 giây/lần)
        let currentSlideIndex = 0;
        const slides = document.querySelectorAll('.banner-slide');
        const dots = document.querySelectorAll('.slide-dot');

        function showSlide(index) {
            if (index >= slides.length) currentSlideIndex = 0;
            else if (index < 0) currentSlideIndex = slides.length - 1;
            else currentSlideIndex = index;

            slides.forEach((slide, i) => {
                if (i === currentSlideIndex) {
                    slide.classList.remove('hidden');
                    slide.classList.add('block');
                } else {
                    slide.classList.remove('block');
                    slide.classList.add('hidden');
                }
            });

            dots.forEach((dot, i) => {
                if (i === currentSlideIndex) {
                    dot.classList.remove('bg-white/50');
                    dot.classList.add('bg-amber-400');
                } else {
                    dot.classList.remove('bg-amber-400');
                    dot.classList.add('bg-white/50');
                }
            });
        }

        function changeSlide(step) {
            showSlide(currentSlideIndex + step);
        }

        function goToSlide(index) {
            showSlide(index);
        }

        // Khởi chạy slider khi tải trang
        window.onload = function () {
            setInterval(() => {
                changeSlide(1);
            }, 5000);
        };

        // 2. Bật/tắt Menu trên điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            drawer.classList.toggle('hidden');
        }

        // 3. Lọc danh mục sản phẩm trang chủ
        function filterCategory(cat) {
            const cards = document.querySelectorAll('.product-card');
            const buttons = document.querySelectorAll('.cat-filter-btn');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-cat-btn') === cat) {
                    btn.className = 'cat-filter-btn bg-brandBlue text-white px-3 py-2 rounded-lg text-[12px] font-semibold border border-brandBlue transition flex items-center justify-center md:justify-start gap-1.5';
                } else {
                    btn.className = 'cat-filter-btn bg-slate-50 hover:bg-brandLight text-slate-700 hover:text-brandBlue px-3 py-2 rounded-lg text-[12px] font-semibold border border-slate-200 transition flex items-center justify-center md:justify-start gap-1.5';
                }
            });

            cards.forEach(card => {
                const itemCat = card.getAttribute('data-category');
                if (cat === 'all' || itemCat === cat) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // 4. Tìm kiếm sản phẩm
        function searchProducts() {
            const query = document.getElementById('searchInput').value.toLowerCase().trim();
            filterByKeyword(query);
        }

        function searchProductsMobile() {
            const query = document.getElementById('mobileSearchInput').value.toLowerCase().trim();
            filterByKeyword(query);
        }

        function filterByKeyword(query) {
            const cards = document.querySelectorAll('.product-card');
            cards.forEach(card => {
                const text = card.innerText.toLowerCase();
                if (text.includes(query)) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // 5. Lọc danh mục bài viết trang chủ
        function filterPosts(cat) {
            const posts = document.querySelectorAll('.post-card');
            const buttons = document.querySelectorAll('.post-cat-btn');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-post-btn') === cat) {
                    btn.className = 'post-cat-btn bg-brandBlue text-white px-2.5 py-1 rounded text-[11px] font-semibold cat-nowrap';
                } else {
                    btn.className = 'post-cat-btn bg-white text-slate-700 border border-slate-200 px-2.5 py-1 rounded text-[11px] font-semibold cat-nowrap';
                }
            });

            posts.forEach(post => {
                const postCat = post.getAttribute('data-post-cat');
                if (cat === 'all' || postCat === cat) {
                    post.classList.remove('hidden');
                } else {
                    post.classList.add('hidden');
                }
            });
        }

        // 6. Chọn sản phẩm và cuộn xuống Form Báo Giá
        function selectProductForQuote(productName) {
            const selectEl = document.getElementById('custProduct');
            const noteEl = document.getElementById('custNote');
            noteEl.value = 'Tôi cần tư vấn và nhận báo giá thiết bị: ' + productName;
            document.getElementById('bao-gia').scrollIntoView({ behavior: 'smooth' });
            document.getElementById('custName').focus();
        }

        // 7. Xử lý gửi Form Báo Giá
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('custName').value.trim();
            const phone = document.getElementById('custPhone').value.trim();
            const product = document.getElementById('custProduct').value;
            const capacity = document.getElementById('custCapacity').value.trim();
            const box = document.getElementById('quoteSuccessBox');

            box.innerHTML = `<i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá <strong>${product}</strong> ${capacity ? '(' + capacity + ')' : ''} đã được ghi nhận. Bộ phận kỹ thuật Công Ty CP Nồi Hơi & TB Áp Lực Miền Trung (0974.669.288) sẽ liên hệ ngay!`;
            box.classList.remove('hidden');
            document.getElementById('quoteForm').reset();
        }
    </script>
</body>
</html>
