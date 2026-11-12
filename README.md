<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Huy Toàn Pet Clinic - Phòng Khám Thú Y Hòa Tiến Đà Nẵng | huytoanpetclinic.com</title>
    <meta name="description" content="Phòng Khám Thú Y Hòa Tiến - Huy Toàn Pet Clinic (huytoanpetclinic.com) tại T605 Dương Sơn, Hòa Tiến, TP Đà Nẵng. Chuyên khám chữa bệnh thú cưng, siêu âm, X-quang, xét nghiệm máu, tiêm phòng vaccine, phẫu thuật, triệt sản, cấp cứu 24/24 và dược phẩm thú y chính hãng. Hotline: 0396.912692 - 0974.554922.">
    
    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://huytoanpetclinic.com/">
    <meta property="og:title" content="Huy Toàn Pet Clinic - Phòng Khám Thú Y Hòa Tiến Đà Nẵng">
    <meta property="og:description" content="Chăm sóc sức khỏe thú cưng toàn diện tại T605 Dương Sơn, Hòa Tiến, TP Đà Nẵng. Khám điều trị, siêu âm, X-quang, xét nghiệm, phẫu thuật, dược phẩm thú y. ĐT: 0396.912692 - 0974.554922">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1JYqsUuRVqTlQL9zErdSpxcQgNJ2PddbE&sz=w1200">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Huy Toàn Pet Clinic - Phòng Khám Thú Y Hòa Tiến">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1JYqsUuRVqTlQL9zErdSpxcQgNJ2PddbE&sz=w1200">
    <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1JYqsUuRVqTlQL9zErdSpxcQgNJ2PddbE&sz=w200">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Font Awesome 6 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        petPrimary: '#0284c7',   /* Xanh dương y tế chủ đạo theo logo & web mẫu GoVet */
                        petDark: '#0c4a6e',      /* Xanh đậm chuyên nghiệp */
                        petTeal: '#0d9488',      /* Xanh ngọc y khoa */
                        petLight: '#f0f9ff',     /* Nền xanh nhạt dịu mắt */
                        petAccent: '#f97316',    /* Cam điểm nhấn CTA */
                    }
                }
            }
        }
    </script>

    <style>
        /* Reset chống tràn viền & chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn Flatsome: Chiều ngang trên máy tính bằng 95% màn hình, căn giữa cân đối */
        .flatsome-container {
            width: 96%;
            max-width: 96%;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                margin-left: auto;
                margin-right: auto;
            }
        }

        /* Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không bao giờ tự ngắt dòng giữa chừng */
        .cat-nav-item {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            line-height: 1.2;
            transition: all 0.2s ease;
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder */
        .section-title-container {
            margin-bottom: 1.25rem;
        }
        .section-title-main {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 0.75rem;
            text-align: center;
        }
        .section-title-main::before,
        .section-title-main::after {
            content: "";
            flex: 1;
            height: 2px;
            background-color: #e2e8f0;
            max-width: 180px;
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị cắt mất chữ, không tràn khung */
        .product-title-full {
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            line-height: 1.35;
        }

        /* Ẩn thanh cuộn ngang cho danh mục trên mobile */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
        @keyframes phoneRing {
            0%, 100% { transform: rotate(0deg) scale(1); }
            15% { transform: rotate(-12deg) scale(1.06); }
            30% { transform: rotate(12deg) scale(1.06); }
            45% { transform: rotate(-8deg) scale(1.04); }
            60% { transform: rotate(8deg) scale(1.04); }
            75% { transform: rotate(0deg) scale(1); }
        }
        .animate-ring {
            animation: phoneRing 2.4s infinite ease-in-out;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased">

    <!-- ==========================================
         TOP BAR: Thông tin phòng khám (Không có thanh công cụ UX Builder)
    =========================================== -->
    <div class="bg-petDark text-white text-[11px] sm:text-xs py-2 border-b border-sky-800">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-globe text-sky-300"></i>
                    <strong class="tracking-wide">huytoanpetclinic.com</strong>
                </span>
                <span class="hidden sm:inline-block text-sky-500">|</span>
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-sky-300"></i>
                    <span>Đ/C: T605 DƯƠNG SƠN, HÒA TIẾN, TP ĐÀ NẴNG</span>
                </span>
            </div>
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-regular fa-clock text-sky-300"></i>
                    <span>Giờ phục vụ: 07:30 - 20:00 (Cấp cứu 24/24h)</span>
                </span>
                <span class="hidden md:inline-block text-sky-500">|</span>
                <span class="hidden md:inline-flex items-center gap-1.5 text-sky-200 font-medium">
                    <i class="fa-solid fa-phone-volume"></i>
                    <span>SĐT: 0396.912692 - 0974.554922</span>
                </span>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH (Logo gọn nhỏ, Menu 1 hàng không xuống dòng, KHÔNG để nút Gọi ngay tránh tràn viền)
    =========================================== -->
    <header class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200">
        <div class="flatsome-container py-2.5 flex items-center justify-between gap-3">
            <!-- Logo chỉnh gọn nhỏ lại & Tên thương hiệu -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group">
                <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-full overflow-hidden border border-sky-200 bg-white flex items-center justify-center p-0.5 shrink-0 shadow-sm">
                    <img 
                        src="https://drive.google.com/thumbnail?id=1JYqsUuRVqTlQL9zErdSpxcQgNJ2PddbE&sz=w400" 
                        alt="Logo Huy Toàn Pet Clinic" 
                        class="w-full h-full object-contain rounded-full"
                        onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1JYqsUuRVqTlQL9zErdSpxcQgNJ2PddbE=w400';"
                    >
                </div>
                <div class="leading-tight">
                    <div class="text-xs sm:text-sm md:text-base font-extrabold text-petDark tracking-tight group-hover:text-petPrimary transition-colors">
                        HUY TOÀN PET CLINIC
                    </div>
                    <div class="text-[10px] sm:text-[11px] font-medium text-petTeal">
                        Phòng Khám Thú Y Hòa Tiến • Đà Nẵng
                    </div>
                </div>
            </a>

            <!-- Menu điều hướng chính trên Máy tính (Chữ nhỏ gọn, viết liền 1 hàng, không xuống dòng) -->
            <nav class="hidden lg:flex items-center justify-center flex-wrap gap-1 xl:gap-1.5">
                <a href="#trang-chu" class="cat-nav-item px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold text-petPrimary bg-sky-50 rounded-md">
                    Trang chủ
                </a>
                <a href="#gioi-thieu" class="cat-nav-item px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold text-slate-700 hover:text-petPrimary hover:bg-sky-50 rounded-md">
                    Giới thiệu
                </a>
                <a href="#dich-vu" class="cat-nav-item px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold text-slate-700 hover:text-petPrimary hover:bg-sky-50 rounded-md">
                    Dịch vụ thú y
                </a>
                <a href="#san-pham" class="cat-nav-item px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold text-slate-700 hover:text-petPrimary hover:bg-sky-50 rounded-md">
                    Dược phẩm & Sản phẩm
                </a>
                <a href="#trang-thiet-bi" class="cat-nav-item px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold text-slate-700 hover:text-petPrimary hover:bg-sky-50 rounded-md">
                    Trang thiết bị
                </a>
                <a href="#bao-gia" class="cat-nav-item px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold text-slate-700 hover:text-petPrimary hover:bg-sky-50 rounded-md">
                    Yêu cầu & Báo giá
                </a>
                <a href="#bai-viet" class="cat-nav-item px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold text-slate-700 hover:text-petPrimary hover:bg-sky-50 rounded-md">
                    Bài viết
                </a>
                <a href="#doi-tac" class="cat-nav-item px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold text-slate-700 hover:text-petPrimary hover:bg-sky-50 rounded-md">
                    Đối tác
                </a>
                <a href="#ban-do-fanpage" class="cat-nav-item px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold text-slate-700 hover:text-petPrimary hover:bg-sky-50 rounded-md">
                    Bản đồ & Fanpage
                </a>
            </nav>

            <!-- Ô tìm kiếm gọn & nút mở Menu Mobile (Không đặt nút Gọi ngay trên Header) -->
            <div class="flex items-center gap-2 shrink-0">
                <div class="hidden sm:flex items-center bg-slate-100 border border-slate-200 rounded-md px-2.5 py-1">
                    <input 
                        type="text" 
                        id="headerSearchInput"
                        placeholder="Tìm thuốc, dịch vụ..." 
                        class="bg-transparent text-xs text-slate-700 focus:outline-none w-32 xl:w-40"
                        oninput="filterProductsBySearch(this.value)"
                    >
                    <button type="button" onclick="document.getElementById('san-pham').scrollIntoView({behavior:'smooth'})" class="text-slate-500 hover:text-petPrimary text-xs">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>

                <!-- Nút mở menu trên điện thoại -->
                <button 
                    type="button" 
                    onclick="toggleMobileMenu()" 
                    class="lg:hidden inline-flex items-center justify-center w-9 h-9 rounded-md border border-slate-200 text-slate-700 hover:bg-slate-100"
                    aria-label="Mở danh mục"
                >
                    <i id="mobileMenuIcon" class="fa-solid fa-bars text-base"></i>
                </button>
            </div>
        </div>

        <!-- THANH DANH MỤC SẢN PHẨM & DỊCH VỤ (Chuẩn web mẫu GoVet - Chữ nhỏ gọn, nằm trên 1 hàng hoặc xuống hàng 2 nguyên cụm, không bao giờ đứt chữ) -->
        <div class="bg-sky-50/90 border-t border-sky-100">
            <div class="flatsome-container py-1.5">
                <!-- Máy tính: Flex-wrap gọn gàng trên 1 hàng (hoặc hàng 2 nguyên mục), tuyệt đối không xuống dòng trong tên danh mục -->
                <div class="hidden md:flex items-center justify-center flex-wrap gap-x-1.5 gap-y-1">
                    <button type="button" onclick="selectCategoryAndScroll('all')" class="cat-nav-item px-2.5 py-1 rounded text-[11.5px] font-semibold bg-petPrimary text-white shadow-xs">
                        <i class="fa-solid fa-layer-group mr-1 text-[10px]"></i>Tất cả danh mục
                    </button>
                    <button type="button" onclick="selectCategoryAndScroll('duoc-pham')" class="cat-nav-item px-2.5 py-1 rounded text-[11.5px] font-medium text-petDark bg-white hover:bg-petPrimary hover:text-white border border-sky-200/80">
                        Dược phẩm thú y
                    </button>
                    <button type="button" onclick="selectCategoryAndScroll('khang-sinh')" class="cat-nav-item px-2.5 py-1 rounded text-[11.5px] font-medium text-petDark bg-white hover:bg-petPrimary hover:text-white border border-sky-200/80">
                        Kháng sinh & Đặc trị
                    </button>
                    <button type="button" onclick="selectCategoryAndScroll('ky-sinh-trung')" class="cat-nav-item px-2.5 py-1 rounded text-[11.5px] font-medium text-petDark bg-white hover:bg-petPrimary hover:text-white border border-sky-200/80">
                        Trị ve rận & Ký sinh trùng
                    </button>
                    <button type="button" onclick="selectCategoryAndScroll('dinh-duong')" class="cat-nav-item px-2.5 py-1 rounded text-[11.5px] font-medium text-petDark bg-white hover:bg-petPrimary hover:text-white border border-sky-200/80">
                        Vitamin & Dinh dưỡng
                    </button>
                    <button type="button" onclick=" scrollToServiceSection('Cấp cứu 24/24')" class="cat-nav-item px-2.5 py-1 rounded text-[11.5px] font-medium text-petDark bg-white hover:bg-petPrimary hover:text-white border border-sky-200/80">
                        Cấp cứu 24/24
                    </button>
                    <button type="button" onclick="scrollToServiceSection('Siêu âm – Chụp X quang')" class="cat-nav-item px-2.5 py-1 rounded text-[11.5px] font-medium text-petDark bg-white hover:bg-petPrimary hover:text-white border border-sky-200/80">
                        Siêu âm & X-Quang
                    </button>
                    <button type="button" onclick="scrollToServiceSection('Xét nghiệm máu')" class="cat-nav-item px-2.5 py-1 rounded text-[11.5px] font-medium text-petDark bg-white hover:bg-petPrimary hover:text-white border border-sky-200/80">
                        Xét nghiệm máu
                    </button>
                    <button type="button" onclick="scrollToServiceSection('Tiêm vaccine chó & mèo')" class="cat-nav-item px-2.5 py-1 rounded text-[11.5px] font-medium text-petDark bg-white hover:bg-petPrimary hover:text-white border border-sky-200/80">
                        Tiêm vaccine chó mèo
                    </button>
                    <button type="button" onclick="scrollToServiceSection('Triệt sản chó & mèo')" class="cat-nav-item px-2.5 py-1 rounded text-[11.5px] font-medium text-petDark bg-white hover:bg-petPrimary hover:text-white border border-sky-200/80">
                        Phẫu thuật & Triệt sản
                    </button>
                    <button type="button" onclick="scrollToServiceSection('Spa & Grooming')" class="cat-nav-item px-2.5 py-1 rounded text-[11.5px] font-medium text-petDark bg-white hover:bg-petPrimary hover:text-white border border-sky-200/80">
                        Spa & Grooming
                    </button>
                </div>

                <!-- Điện thoại: Danh mục chia lưới/cuộn mượt nhỏ gọn, đẹp mắt, không tràn viền -->
                <div class="flex md:hidden items-center gap-1.5 overflow-x-auto no-scrollbar py-0.5">
                    <button type="button" onclick="selectCategoryAndScroll('all')" class="cat-nav-item px-2.5 py-1 rounded text-[11px] font-semibold bg-petPrimary text-white shrink-0">
                        Tất cả
                    </button>
                    <button type="button" onclick="selectCategoryAndScroll('duoc-pham')" class="cat-nav-item px-2.5 py-1 rounded text-[11px] font-medium bg-white text-petDark border border-sky-200 shrink-0">
                        Dược phẩm thú y
                    </button>
                    <button type="button" onclick="selectCategoryAndScroll('khang-sinh')" class="cat-nav-item px-2.5 py-1 rounded text-[11px] font-medium bg-white text-petDark border border-sky-200 shrink-0">
                        Kháng sinh đặc trị
                    </button>
                    <button type="button" onclick="selectCategoryAndScroll('ky-sinh-trung')" class="cat-nav-item px-2.5 py-1 rounded text-[11px] font-medium bg-white text-petDark border border-sky-200 shrink-0">
                        Trị ve rận
                    </button>
                    <button type="button" onclick="selectCategoryAndScroll('dinh-duong')" class="cat-nav-item px-2.5 py-1 rounded text-[11px] font-medium bg-white text-petDark border border-sky-200 shrink-0">
                        Vitamin & Thuốc bổ
                    </button>
                    <button type="button" onclick="scrollToServiceSection('Siêu âm – Chụp X quang')" class="cat-nav-item px-2.5 py-1 rounded text-[11px] font-medium bg-white text-petDark border border-sky-200 shrink-0">
                        Siêu âm - Xquang
                    </button>
                    <button type="button" onclick="scrollToServiceSection('Tiêm vaccine chó & mèo')" class="cat-nav-item px-2.5 py-1 rounded text-[11px] font-medium bg-white text-petDark border border-sky-200 shrink-0">
                        Tiêm Vaccine
                    </button>
                    <button type="button" onclick="scrollToServiceSection('Triệt sản chó & mèo')" class="cat-nav-item px-2.5 py-1 rounded text-[11px] font-medium bg-white text-petDark border border-sky-200 shrink-0">
                        Triệt sản - Phẫu thuật
                    </button>
                </div>
            </div>
        </div>

        <!-- Menu xổ xuống trên Điện thoại -->
        <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="flatsome-container py-3 space-y-2">
                <div class="flex items-center bg-slate-100 border border-slate-200 rounded-md px-3 py-1.5">
                    <input 
                        type="text" 
                        placeholder="Tìm tên sản phẩm, thuốc thú y..." 
                        class="bg-transparent text-xs text-slate-700 focus:outline-none w-full"
                        oninput="filterProductsBySearch(this.value)"
                    >
                    <i class="fa-solid fa-magnifying-glass text-slate-400 text-xs"></i>
                </div>
                <div class="grid grid-cols-2 gap-1.5 pt-1">
                    <a href="#trang-chu" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-sky-50 text-petPrimary font-semibold text-xs flex items-center gap-2">
                        <i class="fa-solid fa-house text-[11px]"></i> Trang chủ
                    </a>
                    <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700 font-medium text-xs flex items-center gap-2">
                        <i class="fa-solid fa-hospital text-[11px] text-petPrimary"></i> Giới thiệu
                    </a>
                    <a href="#dich-vu" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700 font-medium text-xs flex items-center gap-2">
                        <i class="fa-solid fa-stethoscope text-[11px] text-petPrimary"></i> Dịch vụ thú y
                    </a>
                    <a href="#san-pham" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700 font-medium text-xs flex items-center gap-2">
                        <i class="fa-solid fa-capsules text-[11px] text-petPrimary"></i> Sản phẩm & Thuốc
                    </a>
                    <a href="#trang-thiet-bi" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700 font-medium text-xs flex items-center gap-2">
                        <i class="fa-solid fa-microscope text-[11px] text-petPrimary"></i> Trang thiết bị
                    </a>
                    <a href="#bao-gia" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700 font-medium text-xs flex items-center gap-2">
                        <i class="fa-solid fa-file-invoice-dollar text-[11px] text-petPrimary"></i> Yêu cầu & Báo giá
                    </a>
                    <a href="#bai-viet" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700 font-medium text-xs flex items-center gap-2">
                        <i class="fa-solid fa-newspaper text-[11px] text-petPrimary"></i> Bài viết tư vấn
                    </a>
                    <a href="#ban-do-fanpage" onclick="toggleMobileMenu()" class="px-3 py-2 rounded bg-slate-50 text-slate-700 font-medium text-xs flex items-center gap-2">
                        <i class="fa-solid fa-map-location-dot text-[11px] text-petPrimary"></i> Bản đồ & Fanpage
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- ==========================================
         HERO BANNER SLIDER: 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
         Thiết kế riêng Banner Máy Tính (hidden md:block) và Banner Điện Thoại (block md:hidden)
         để tối ưu chữ nhỏ gọn nằm trọn bên trong ảnh, không tràn viền
    =========================================== -->
    <section id="trang-chu" class="py-3 md:py-4">
        <div class="flatsome-container">
            <div class="relative rounded-xl overflow-hidden shadow-md border border-sky-100 bg-petDark">

                <!-- ==================== SLIDE 1 ==================== -->
                <div id="bannerSlide0" class="banner-slide block transition-opacity duration-500">
                    
                    <!-- BANNER 1 TRÊN MÁY TÍNH (Chiều cao cố định 370px bằng Slide 2, chữ nhỏ gọn nằm gọn trong khung) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[370px] bg-gradient-to-r from-[#082f49] via-[#0369a1] to-[#0f766e] px-10 lg:px-14 py-6 relative overflow-hidden">
                        <div class="col-span-7 text-white z-10 pr-4 space-y-2.5">
                            <div class="inline-flex items-center gap-2 bg-white/15 border border-white/25 px-3 py-1 rounded-full text-xs font-semibold text-sky-100">
                                <i class="fa-solid fa-shield-dog text-amber-300"></i>
                                <span>PHÒNG KHÁM THÚ Y HÒA TIẾN - HUY TOÀN PET CLINIC</span>
                            </div>
                            <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-white">
                                ĐỊA CHỈ KHÁM & ĐIỀU TRỊ THÚ CƯNG UY TÍN TẠI ĐÀ NẴNG
                            </h1>
                            <p class="text-xs lg:text-sm text-sky-100 leading-relaxed max-w-xl">
                                Chuyên khám chữa bệnh chó mèo, siêu âm, chụp X-quang, xét nghiệm máu, tiêm phòng vaccine, phẫu thuật ngoại khoa - triệt sản và cung cấp dược phẩm thú y chính hãng.
                            </p>
                            <div class="grid grid-cols-2 gap-2 pt-1 max-w-lg text-xs text-sky-50">
                                <div class="flex items-center gap-1.5 bg-black/20 px-2.5 py-1.5 rounded">
                                    <i class="fa-solid fa-phone-volume text-amber-300"></i>
                                    <span>Hotline: <strong>0396.912692 - 0974.554922</strong></span>
                                </div>
                                <div class="flex items-center gap-1.5 bg-black/20 px-2.5 py-1.5 rounded">
                                    <i class="fa-solid fa-location-dot text-amber-300"></i>
                                    <span>T605 Dương Sơn, Hòa Tiến, Đà Nẵng</span>
                                </div>
                            </div>
                            <div class="flex items-center gap-3 pt-1">
                                <a href="#bao-gia" class="px-4 py-2 rounded-lg bg-amber-500 hover:bg-amber-600 text-white font-bold text-xs shadow transition">
                                    <i class="fa-regular fa-calendar-check mr-1"></i> Đặt Lịch Khám & Báo Giá
                                </a>
                                <a href="#dich-vu" class="px-4 py-2 rounded-lg bg-white/15 hover:bg-white/25 text-white font-semibold text-xs border border-white/30 transition">
                                    Xem Dịch Vụ Thú Y
                                </a>
                            </div>
                        </div>
                        <div class="col-span-5 h-full flex items-center justify-center z-10">
                            <div class="w-full h-[290px] rounded-xl overflow-hidden border-2 border-white/30 shadow-lg bg-slate-900/40 flex items-center justify-center">
                                <img 
                                    src="https://drive.google.com/thumbnail?id=1RW9Z6yOLprRrBbjCDEX2JW2Jp1LKOGcl&sz=w1000" 
                                    alt="Phòng Khám Thú Y Hòa Tiến - Huy Toàn Pet Clinic" 
                                    class="w-full h-full object-cover"
                                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1RW9Z6yOLprRrBbjCDEX2JW2Jp1LKOGcl=w1000';"
                                >
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 1 THIẾT KẾ MỚI DÀNH RIÊNG CHO ĐIỆN THOẠI (Chiều cao cố định 270px bằng Slide 2, chữ nhỏ nằm trọn trong ảnh) -->
                    <div class="block md:hidden h-[270px] bg-gradient-to-br from-[#082f49] via-[#0369a1] to-[#0d9488] p-3.5 flex flex-col justify-between relative overflow-hidden">
                        <div class="flex items-center gap-2.5">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1JYqsUuRVqTlQL9zErdSpxcQgNJ2PddbE&sz=w200" 
                                alt="Logo" 
                                class="w-9 h-9 rounded-full bg-white p-0.5 object-contain shrink-0 border border-sky-200"
                            >
                            <div class="min-w-0">
                                <div class="text-[10px] font-bold uppercase tracking-wider text-amber-300">huytoanpetclinic.com</div>
                                <h2 class="text-[13px] font-extrabold text-white leading-tight">HUY TOÀN PET CLINIC - HÒA TIẾN</h2>
                            </div>
                        </div>

                        <div class="grid grid-cols-12 gap-2.5 items-center my-auto py-1">
                            <div class="col-span-7 space-y-1 text-white">
                                <div class="text-[12px] font-bold text-sky-100 leading-snug">
                                    Khám Chữa Bệnh, Siêu Âm, X-Quang & Cấp Cứu 24/24
                                </div>
                                <p class="text-[10.5px] text-sky-100/90 leading-normal">
                                    Tiêm vaccine, xét nghiệm máu, phẫu thuật ngoại khoa, triệt sản & thuốc thú y chính hãng.
                                </p>
                            </div>
                            <div class="col-span-5">
                                <div class="h-[105px] w-full rounded-lg overflow-hidden border border-white/30 bg-slate-800">
                                    <img 
                                        src="https://drive.google.com/thumbnail?id=1RW9Z6yOLprRrBbjCDEX2JW2Jp1LKOGcl&sz=w600" 
                                        alt="Huy Toàn Pet Clinic" 
                                        class="w-full h-full object-cover"
                                    >
                                </div>
                            </div>
                        </div>

                        <div class="bg-black/25 rounded-lg px-2.5 py-1.5 flex items-center justify-between gap-2 text-[10px] text-white">
                            <div class="truncate">
                                <i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>T605 Dương Sơn, Hòa Tiến, Đà Nẵng
                            </div>
                            <a href="tel:0396912692" class="bg-amber-500 text-white font-bold px-2 py-0.5 rounded shrink-0">
                                0396.912692
                            </a>
                        </div>
                    </div>
                </div>

                <!-- ==================== SLIDE 2 ==================== -->
                <div id="bannerSlide1" class="banner-slide hidden transition-opacity duration-500">
                    
                    <!-- BANNER 2 TRÊN MÁY TÍNH (Chiều cao cố định 370px bằng Slide 1, chữ nhỏ gọn nằm trọn trong ảnh) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[370px] bg-gradient-to-r from-[#064e3b] via-[#0f766e] to-[#0284c7] px-10 lg:px-14 py-6 relative overflow-hidden">
                        <div class="col-span-7 text-white z-10 pr-4 space-y-2.5">
                            <div class="inline-flex items-center gap-2 bg-white/15 border border-white/25 px-3 py-1 rounded-full text-xs font-semibold text-emerald-100">
                                <i class="fa-solid fa-kit-medical text-amber-300"></i>
                                <span>TRANG THIẾT BỊ HIỆN ĐẠI & NHÀ THUỐC THÚ Y ĐẠT CHUẨN</span>
                            </div>
                            <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-white">
                                CHẨN ĐOÁN HÌNH ẢNH CHÍNH XÁC • DƯỢC PHẨM THÚ Y CHÍNH HÃNG
                            </h2>
                            <p class="text-xs lg:text-sm text-emerald-50 leading-relaxed max-w-xl">
                                Trang bị hệ thống máy siêu âm, máy X-quang, máy xét nghiệm máu nhanh cùng đầy đủ các dòng kháng sinh, vitamin, thuốc trị ký sinh trùng và dinh dưỡng cho thú cưng.
                            </p>
                            <div class="grid grid-cols-2 gap-2 pt-1 max-w-lg text-xs text-emerald-50">
                                <div class="flex items-center gap-1.5 bg-black/20 px-2.5 py-1.5 rounded">
                                    <i class="fa-solid fa-check-circle text-amber-300"></i>
                                    <span>Khám điều trị tại phòng khám & tại nhà</span>
                                </div>
                                <div class="flex items-center gap-1.5 bg-black/20 px-2.5 py-1.5 rounded">
                                    <i class="fa-solid fa-phone-volume text-amber-300"></i>
                                    <span>Tư vấn 24/7: <strong>0974.554922</strong></span>
                                </div>
                            </div>
                            <div class="flex items-center gap-3 pt-1">
                                <a href="#san-pham" class="px-4 py-2 rounded-lg bg-amber-500 hover:bg-amber-600 text-white font-bold text-xs shadow transition">
                                    <i class="fa-solid fa-pills mr-1"></i> Xem Dược Phẩm & Sản Phẩm
                                </a>
                                <a href="#ban-do-fanpage" class="px-4 py-2 rounded-lg bg-white/15 hover:bg-white/25 text-white font-semibold text-xs border border-white/30 transition">
                                    Xem Bản Đồ Chỉ Đường
                                </a>
                            </div>
                        </div>
                        <div class="col-span-5 h-full flex items-center justify-center z-10">
                            <div class="w-full h-[290px] rounded-xl overflow-hidden border-2 border-white/30 shadow-lg bg-slate-900/40 flex items-center justify-center">
                                <img 
                                    src="https://drive.google.com/thumbnail?id=1psu878DHC-9uc6A-5Cc-U5qAj21jyV2i&sz=w1000" 
                                    alt="Trang thiết bị & Dược phẩm Huy Toàn Pet Clinic" 
                                    class="w-full h-full object-cover"
                                    onerror="this.onerror=null; this.src='https://lh3.googleusercontent.com/d/1psu878DHC-9uc6A-5Cc-U5qAj21jyV2i=w1000';"
                                >
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2 THIẾT KẾ MỚI DÀNH RIÊNG CHO ĐIỆN THOẠI (Chiều cao cố định 270px bằng Slide 1, chữ nhỏ nằm trọn trong ảnh) -->
                    <div class="block md:hidden h-[270px] bg-gradient-to-br from-[#064e3b] via-[#0f766e] to-[#0284c7] p-3.5 flex flex-col justify-between relative overflow-hidden">
                        <div class="flex items-center gap-2.5">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1JYqsUuRVqTlQL9zErdSpxcQgNJ2PddbE&sz=w200" 
                                alt="Logo" 
                                class="w-9 h-9 rounded-full bg-white p-0.5 object-contain shrink-0 border border-emerald-200"
                            >
                            <div class="min-w-0">
                                <div class="text-[10px] font-bold uppercase tracking-wider text-amber-300">Nhà Thuốc & Thiết Bị Thú Y</div>
                                <h2 class="text-[13px] font-extrabold text-white leading-tight">DƯỢC PHẨM & CHẨN ĐOÁN HIỆN ĐẠI</h2>
                            </div>
                        </div>

                        <div class="grid grid-cols-12 gap-2.5 items-center my-auto py-1">
                            <div class="col-span-7 space-y-1 text-white">
                                <div class="text-[12px] font-bold text-emerald-100 leading-snug">
                                    Máy Siêu Âm, X-Quang, Xét Nghiệm & Thuốc Đặc Trị
                                </div>
                                <p class="text-[10.5px] text-emerald-50/90 leading-normal">
                                    Đầy đủ thuốc kháng sinh, trị ve rận, bổ trợ gan thận, vitamin và thức ăn dinh dưỡng.
                                </p>
                            </div>
                            <div class="col-span-5">
                                <div class="h-[105px] w-full rounded-lg overflow-hidden border border-white/30 bg-slate-800">
                                    <img 
                                        src="https://drive.google.com/thumbnail?id=1psu878DHC-9uc6A-5Cc-U5qAj21jyV2i&sz=w600" 
                                        alt="Dược phẩm thú y Huy Toàn" 
                                        class="w-full h-full object-cover"
                                    >
                                </div>
                            </div>
                        </div>

                        <div class="bg-black/25 rounded-lg px-2.5 py-1.5 flex items-center justify-between gap-2 text-[10px] text-white">
                            <div class="truncate">
                                <i class="fa-solid fa-phone text-amber-300 mr-1"></i>SĐT: 0396.912692 - 0974.554922
                            </div>
                            <a href="#san-pham" class="bg-amber-500 text-white font-bold px-2 py-0.5 rounded shrink-0">
                                Xem sản phẩm
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Slide Trái / Phải & Chấm tròn -->
                <button 
                    type="button" 
                    onclick="changeBannerSlide(-1)" 
                    class="hidden sm:flex absolute left-2.5 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/30 hover:bg-black/50 text-white items-center justify-center z-20 transition"
                    aria-label="Slide trước"
                >
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button 
                    type="button" 
                    onclick="changeBannerSlide(1)" 
                    class="hidden sm:flex absolute right-2.5 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/30 hover:bg-black/50 text-white items-center justify-center z-20 transition"
                    aria-label="Slide tiếp theo"
                >
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button type="button" id="bannerDot0" onclick="goToBannerSlide(0)" class="w-5 h-1.5 rounded-full bg-amber-400 transition-all" aria-label="Banner 1"></button>
                    <button type="button" id="bannerDot1" onclick="goToBannerSlide(1)" class="w-2 h-1.5 rounded-full bg-white/60 transition-all" aria-label="Banner 2"></button>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         4 CAM KẾT DỊCH VỤ (Chuẩn bố cục 4 cột Flatsome giống web mẫu GoVet)
    =========================================== -->
    <section class="py-3">
        <div class="flatsome-container">
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 md:gap-4">
                <div class="bg-white rounded-lg p-3 md:p-4 border border-slate-200 shadow-xs flex items-center gap-3">
                    <div class="w-10 h-10 rounded-full bg-sky-100 text-petPrimary flex items-center justify-center shrink-0">
                        <i class="fa-regular fa-calendar-check text-lg"></i>
                    </div>
                    <div class="min-w-0">
                        <div class="text-xs md:text-sm font-bold text-petDark">Đặt Lịch Khám 24/7</div>
                        <div class="text-[11px] text-slate-500">Hỗ trợ tư vấn nhanh chóng</div>
                    </div>
                </div>
                <div class="bg-white rounded-lg p-3 md:p-4 border border-slate-200 shadow-xs flex items-center gap-3">
                    <div class="w-10 h-10 rounded-full bg-teal-100 text-petTeal flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-truck-medical text-lg"></i>
                    </div>
                    <div class="min-w-0">
                        <div class="text-xs md:text-sm font-bold text-petDark">Cấp Cứu 24/7</div>
                        <div class="text-[11px] text-slate-500">Trực cấp cứu nội & ngoại khoa</div>
                    </div>
                </div>
                <div class="bg-white rounded-lg p-3 md:p-4 border border-slate-200 shadow-xs flex items-center gap-3">
                    <div class="w-10 h-10 rounded-full bg-sky-100 text-petPrimary flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-microscope text-lg"></i>
                    </div>
                    <div class="min-w-0">
                        <div class="text-xs md:text-sm font-bold text-petDark">Thiết Bị Hiện Đại</div>
                        <div class="text-[11px] text-slate-500">Siêu âm, X-quang, xét nghiệm</div>
                    </div>
                </div>
                <div class="bg-white rounded-lg p-3 md:p-4 border border-slate-200 shadow-xs flex items-center gap-3">
                    <div class="w-10 h-10 rounded-full bg-amber-100 text-amber-600 flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-user-doctor text-lg"></i>
                    </div>
                    <div class="min-w-0">
                        <div class="text-xs md:text-sm font-bold text-petDark">Bác Sĩ Tận Tâm</div>
                        <div class="text-[11px] text-slate-500">Chuyên môn cao, giàu kinh nghiệm</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         GIỚI THIỆU PHÒNG KHÁM THÚ Y HÒA TIẾN - HUY TOÀN PET CLINIC
         (Bố cục 2 cột chuẩn Flatsome giống web mẫu GoVet + hình ảnh thực tế từ Google Drive)
    =========================================== -->
    <section id="gioi-thieu" class="py-6 md:py-8">
        <div class="flatsome-container">
            <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-6 md:p-8 shadow-xs">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                    <div class="lg:col-span-7 space-y-3">
                        <div class="text-xs font-bold uppercase tracking-wider text-petTeal">
                            PHÒNG KHÁM THÚ Y HÒA TIẾN • HUYTOANPETCLINIC.COM
                        </div>
                        <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-petDark leading-snug">
                            Địa Chỉ Chăm Sóc & Điều Trị Thú Cưng Đáng Tin Cậy Tại Hòa Tiến, TP. Đà Nẵng
                        </h2>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            <strong>Phòng Khám Thú Y Hòa Tiến – Huy Toàn Pet Clinic</strong> tọa lạc tại <strong>T605 Dương Sơn, Hòa Tiến, TP Đà Nẵng</strong> tự hào là cơ sở thú y uy tín đồng hành cùng các gia đình nuôi thú cưng. Với đội ngũ bác sĩ thú y giàu kinh nghiệm, tận tâm và yêu thương động vật, chúng tôi luôn đặt sự an toàn và sức khỏe của các bé cún, bé mèo lên hàng đầu.
                        </p>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            Song song với yếu tố chuyên môn, <strong>Huy Toàn Pet Clinic</strong> đầu tư đồng bộ trang thiết bị chẩn đoán hiện đại gồm: <strong>máy siêu âm kiểm tra nội tạng, máy chụp X-quang chấn thương xương khớp, hệ thống xét nghiệm máu sinh lý - sinh hóa nhanh</strong> cùng nhà thuốc thú y đầy đủ các dòng dược phẩm đặc trị chính hãng.
                        </p>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 pt-1 text-xs text-slate-700">
                            <div class="flex items-center gap-2 bg-sky-50 px-3 py-2 rounded-lg border border-sky-100">
                                <i class="fa-solid fa-circle-check text-petPrimary"></i>
                                <span>Khám, chẩn đoán & điều trị nội trú - ngoại trú</span>
                            </div>
                            <div class="flex items-center gap-2 bg-sky-50 px-3 py-2 rounded-lg border border-sky-100">
                                <i class="fa-solid fa-circle-check text-petPrimary"></i>
                                <span>Siêu âm thai, nội tạng & Chụp X-quang kỹ thuật số</span>
                            </div>
                            <div class="flex items-center gap-2 bg-sky-50 px-3 py-2 rounded-lg border border-sky-100">
                                <i class="fa-solid fa-circle-check text-petPrimary"></i>
                                <span>Tiêm phòng vaccine, tẩy giun & phòng ký sinh trùng</span>
                            </div>
                            <div class="flex items-center gap-2 bg-sky-50 px-3 py-2 rounded-lg border border-sky-100">
                                <i class="fa-solid fa-circle-check text-petPrimary"></i>
                                <span>Phẫu thuật mổ đẻ, triệt sản, ngoại khoa & cấp cứu 24/24</span>
                            </div>
                        </div>
                        <div class="pt-2 flex flex-wrap items-center gap-3">
                            <a href="#bao-gia" class="px-4 py-2 rounded-lg bg-petPrimary hover:bg-petDark text-white font-semibold text-xs transition">
                                Nhận Tư Vấn & Báo Giá Ngay >
                            </a>
                            <a href="https://www.facebook.com/phongkhamthuyhoatienhuytoanpetclinnic" target="_blank" rel="noopener noreferrer" class="px-4 py-2 rounded-lg bg-slate-100 hover:bg-slate-200 text-petDark font-semibold text-xs transition">
                                <i class="fa-brands fa-facebook text-blue-600 mr-1"></i> Xem Fanpage Phòng Khám
                            </a>
                        </div>
                    </div>

                    <!-- Khung ảnh thực tế từ Google Drive -->
                    <div class="lg:col-span-5 grid grid-cols-2 gap-2.5">
                        <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-100 aspect-4/3">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1RW9Z6yOLprRrBbjCDEX2JW2Jp1LKOGcl&sz=w800" 
                                alt="Hình ảnh thực tế Huy Toàn Pet Clinic 1" 
                                class="w-full h-full object-cover"
                            >
                        </div>
                        <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-100 aspect-4/3">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1AHSK-b7ml7um_Dk7Ugv0IEbfA2CVE4GJ&sz=w800" 
                                alt="Hình ảnh thực tế Huy Toàn Pet Clinic 2" 
                                class="w-full h-full object-cover"
                            >
                        </div>
                        <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-100 aspect-4/3">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1Wy3WlUgVRRo_1fn-1UbJEB0PsSKsm9TN&sz=w800" 
                                alt="Hình ảnh thực tế Huy Toàn Pet Clinic 3" 
                                class="w-full h-full object-cover"
                            >
                        </div>
                        <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-100 aspect-4/3">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1JXIOBXu2_2i8gllcPg15XuP8XpvbCCU2&sz=w800" 
                                alt="Hình ảnh thực tế Huy Toàn Pet Clinic 4" 
                                class="w-full h-full object-cover"
                            >
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         MỘT SỐ DỊCH VỤ CỦA CHÚNG TÔI
         (Lấy đầy đủ 12 danh mục dịch vụ từ web mẫu GoVet + Huy Toàn Pet Clinic,
         chia 2 cột trên điện thoại, 4 cột trên máy tính, KHÔNG để nhãn dán ở trang chủ)
    =========================================== -->
    <section id="dich-vu" class="py-6 md:py-8">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-main text-base sm:text-lg md:text-xl font-extrabold text-petDark uppercase tracking-wide">
                    MỘT SỐ DỊCH VỤ CỦA CHÚNG TÔI
                </h2>
                <p class="text-center text-xs text-slate-500 mt-1">
                    Cung cấp đầy đủ các hạng mục khám, chẩn đoán, phẫu thuật và chăm sóc thú cưng tại T605 Dương Sơn, Hòa Tiến
                </p>
            </div>

            <!-- Lưới dịch vụ: 2 cột trên điện thoại, 4 cột trên máy tính, tuyệt đối KHÔNG có nhãn dán (badge/sticker) -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 md:gap-4">
                
                <!-- Dịch vụ 1 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="aspect-16/10 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1RW9Z6yOLprRrBbjCDEX2JW2Jp1LKOGcl&sz=w700" alt="Siêu âm – Chụp X quang" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark">Siêu âm – Chụp X quang</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Kiểm tra thai kỳ, bệnh lý nội tạng, chẩn đoán chấn thương xương khớp chính xác.</p>
                        </div>
                        <button type="button" onclick="prefillQuoteForm('Siêu âm – Chụp X quang')" class="mt-2.5 w-full py-1.5 rounded bg-sky-50 hover:bg-petPrimary text-petPrimary hover:text-white text-[11px] font-semibold transition">
                            Đặt lịch & Báo giá
                        </button>
                    </div>
                </div>

                <!-- Dịch vụ 2 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="aspect-16/10 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1psu878DHC-9uc6A-5Cc-U5qAj21jyV2i&sz=w700" alt="Khám sức khỏe và điều trị bệnh" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark">Khám sức khỏe và điều trị bệnh</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Khám lâm sàng, điều trị các bệnh truyền nhiễm, tiêu hóa, hô hấp, da liễu ở chó mèo.</p>
                        </div>
                        <button type="button" onclick="prefillQuoteForm('Khám sức khỏe và điều trị bệnh')" class="mt-2.5 w-full py-1.5 rounded bg-sky-50 hover:bg-petPrimary text-petPrimary hover:text-white text-[11px] font-semibold transition">
                            Đặt lịch & Báo giá
                        </button>
                    </div>
                </div>

                <!-- Dịch vụ 3 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="aspect-16/10 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1AHSK-b7ml7um_Dk7Ugv0IEbfA2CVE4GJ&sz=w700" alt="Xét nghiệm máu" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark">Xét nghiệm máu</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Xét nghiệm sinh lý, sinh hóa máu, test nhanh virus Parvo, Care, giảm bạch cầu, ký sinh trùng máu.</p>
                        </div>
                        <button type="button" onclick="prefillQuoteForm('Xét nghiệm máu')" class="mt-2.5 w-full py-1.5 rounded bg-sky-50 hover:bg-petPrimary text-petPrimary hover:text-white text-[11px] font-semibold transition">
                            Đặt lịch & Báo giá
                        </button>
                    </div>
                </div>

                <!-- Dịch vụ 4 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="aspect-16/10 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1Wy3WlUgVRRo_1fn-1UbJEB0PsSKsm9TN&sz=w700" alt="Cấp cứu 24/24" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark">Cấp cứu 24/24</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Tiếp nhận xử lý cấp cứu ngộ độc, tai nạn, khó đẻ, sốc nhiệt, suy hô hấp ngày và đêm.</p>
                        </div>
                        <button type="button" onclick="prefillQuoteForm('Cấp cứu 24/24')" class="mt-2.5 w-full py-1.5 rounded bg-sky-50 hover:bg-petPrimary text-petPrimary hover:text-white text-[11px] font-semibold transition">
                            Đặt lịch & Báo giá
                        </button>
                    </div>
                </div>

                <!-- Dịch vụ 5 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="aspect-16/10 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1JXIOBXu2_2i8gllcPg15XuP8XpvbCCU2&sz=w700" alt="Khám điều trị tại nhà" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark">Khám điều trị tại nhà</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Bác sĩ thú y hỗ trợ thăm khám, tiêm phòng và điều trị tận nhà tại Hòa Tiến và khu vực Đà Nẵng.</p>
                        </div>
                        <button type="button" onclick="prefillQuoteForm('Khám điều trị tại nhà')" class="mt-2.5 w-full py-1.5 rounded bg-sky-50 hover:bg-petPrimary text-petPrimary hover:text-white text-[11px] font-semibold transition">
                            Đặt lịch & Báo giá
                        </button>
                    </div>
                </div>

                <!-- Dịch vụ 6 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="aspect-16/10 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=17P4YRmfqeBVjSxO16yp8bzNQnt1IoUG8&sz=w700" alt="Phẫu thuật mổ đẻ" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark">Phẫu thuật mổ đẻ</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Đỡ đẻ và phẫu thuật mổ đẻ an toàn cho chó mèo mẹ, hồi sức sơ sinh chuyên nghiệp.</p>
                        </div>
                        <button type="button" onclick="prefillQuoteForm('Phẫu thuật mổ đẻ')" class="mt-2.5 w-full py-1.5 rounded bg-sky-50 hover:bg-petPrimary text-petPrimary hover:text-white text-[11px] font-semibold transition">
                            Đặt lịch & Báo giá
                        </button>
                    </div>
                </div>

                <!-- Dịch vụ 7 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="aspect-16/10 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1Edz-jFCaTepa3xGRjQv51SWZWFg7HfB0&sz=w700" alt="Phẫu thuật phức tạp" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark">Phẫu thuật phức tạp</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Phẫu thuật sỏi bàng quang, cắt khối u, viêm tử cung蓄 mủ, thoát vị và xử lý ngoại khoa.</p>
                        </div>
                        <button type="button" onclick="prefillQuoteForm('Phẫu thuật phức tạp')" class="mt-2.5 w-full py-1.5 rounded bg-sky-50 hover:bg-petPrimary text-petPrimary hover:text-white text-[11px] font-semibold transition">
                            Đặt lịch & Báo giá
                        </button>
                    </div>
                </div>

                <!-- Dịch vụ 8 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="aspect-16/10 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1RW9Z6yOLprRrBbjCDEX2JW2Jp1LKOGcl&sz=w700" alt="Phẫu thuật xương" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark">Phẫu thuật xương</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Kết hợp xương, bó bột, điều trị trật khớp và phục hồi vận động cho chó mèo sau chấn thương.</p>
                        </div>
                        <button type="button" onclick="prefillQuoteForm('Phẫu thuật xương')" class="mt-2.5 w-full py-1.5 rounded bg-sky-50 hover:bg-petPrimary text-petPrimary hover:text-white text-[11px] font-semibold transition">
                            Đặt lịch & Báo giá
                        </button>
                    </div>
                </div>

                <!-- Dịch vụ 9 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="aspect-16/10 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1psu878DHC-9uc6A-5Cc-U5qAj21jyV2i&sz=w700" alt="Spa & Grooming" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark">Spa & Grooming</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Tắm khử mùi, cắt tỉa lông thẩm mỹ, vệ sinh tai, cắt mài móng, vắt tuyến hôi an toàn.</p>
                        </div>
                        <button type="button" onclick="prefillQuoteForm('Spa & Grooming')" class="mt-2.5 w-full py-1.5 rounded bg-sky-50 hover:bg-petPrimary text-petPrimary hover:text-white text-[11px] font-semibold transition">
                            Đặt lịch & Báo giá
                        </button>
                    </div>
                </div>

                <!-- Dịch vụ 10 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="aspect-16/10 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1AHSK-b7ml7um_Dk7Ugv0IEbfA2CVE4GJ&sz=w700" alt="Tiêm vaccine chó & mèo" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark">Tiêm vaccine chó & mèo</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Tiêm phòng vaccine 5 bệnh, 7 bệnh cho cún, 4 bệnh cho mèo và vaccine phòng dại định kỳ.</p>
                        </div>
                        <button type="button" onclick="prefillQuoteForm('Tiêm vaccine chó & mèo')" class="mt-2.5 w-full py-1.5 rounded bg-sky-50 hover:bg-petPrimary text-petPrimary hover:text-white text-[11px] font-semibold transition">
                            Đặt lịch & Báo giá
                        </button>
                    </div>
                </div>

                <!-- Dịch vụ 11 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="aspect-16/10 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1Wy3WlUgVRRo_1fn-1UbJEB0PsSKsm9TN&sz=w700" alt="Triệt sản chó & mèo" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark">Triệt sản chó & mèo</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Thiến và triệt sản chó mèo đực/cái bằng phương pháp thẩm mỹ ít xâm lấn, mau lành.</p>
                        </div>
                        <button type="button" onclick="prefillQuoteForm('Triệt sản chó & mèo')" class="mt-2.5 w-full py-1.5 rounded bg-sky-50 hover:bg-petPrimary text-petPrimary hover:text-white text-[11px] font-semibold transition">
                            Đặt lịch & Báo giá
                        </button>
                    </div>
                </div>

                <!-- Dịch vụ 12 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="aspect-16/10 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1JXIOBXu2_2i8gllcPg15XuP8XpvbCCU2&sz=w700" alt="Lưu chuồng và điều trị" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark">Lưu chuồng và điều trị</h3>
                            <p class="text-[11px] text-slate-500 mt-1">Phòng lưu chuồng sạch sẽ, khử khuẩn tách biệt, theo dõi truyền dịch & chăm sóc hậu phẫu.</p>
                        </div>
                        <button type="button" onclick="prefillQuoteForm('Lưu chuồng và điều trị')" class="mt-2.5 w-full py-1.5 rounded bg-sky-50 hover:bg-petPrimary text-petPrimary hover:text-white text-[11px] font-semibold transition">
                            Đặt lịch & Báo giá
                        </button>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         SẢN PHẨM NỔI BẬT & DƯỢC PHẨM THÚ Y
         - Lấy danh mục và sản phẩm từ web mẫu GoVet + 7 ảnh thực tế từ Google Drive
         - Chia thành 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
         - Tên sản phẩm hiển thị đầy đủ, không bị tràn ra ngoài hoặc thiếu chữ
         - Không để các nhãn dán (stickers/badges) ở trang chủ
    =========================================== -->
    <section id="san-pham" class="py-6 md:py-8 bg-white border-y border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-main text-base sm:text-lg md:text-xl font-extrabold text-petDark uppercase tracking-wide">
                    SẢN PHẨM NỔI BẬT CỦA CHÚNG TÔI
                </h2>
                <p class="text-center text-xs text-slate-500 mt-1">
                    Danh mục Dược phẩm thú y, Kháng sinh đặc trị, Thuốc diệt ký sinh trùng & Vitamin hồi phục chính hãng
                </p>
            </div>

            <!-- Thanh lọc Danh mục sản phẩm ở trang chủ: Chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng giữa chữ -->
            <div class="flex items-center justify-start sm:justify-center gap-1.5 overflow-x-auto no-scrollbar pb-3 mb-3">
                <button type="button" data-cat="all" onclick="filterProducts('all')" class="prod-cat-btn cat-nav-item px-3 py-1.5 rounded-md text-xs font-semibold bg-petPrimary text-white border border-petPrimary">
                    Tất cả sản phẩm (11)
                </button>
                <button type="button" data-cat="duoc-pham" onclick="filterProducts('duoc-pham')" class="prod-cat-btn cat-nav-item px-3 py-1.5 rounded-md text-xs font-medium bg-slate-100 text-slate-700 hover:bg-sky-50 hover:text-petPrimary border border-slate-200">
                    Dược phẩm thú y
                </button>
                <button type="button" data-cat="khang-sinh" onclick="filterProducts('khang-sinh')" class="prod-cat-btn cat-nav-item px-3 py-1.5 rounded-md text-xs font-medium bg-slate-100 text-slate-700 hover:bg-sky-50 hover:text-petPrimary border border-slate-200">
                    Kháng sinh & Đặc trị
                </button>
                <button type="button" data-cat="ky-sinh-trung" onclick="filterProducts('ky-sinh-trung')" class="prod-cat-btn cat-nav-item px-3 py-1.5 rounded-md text-xs font-medium bg-slate-100 text-slate-700 hover:bg-sky-50 hover:text-petPrimary border border-slate-200">
                    Trị ve rận & Ký sinh trùng
                </button>
                <button type="button" data-cat="dinh-duong" onclick="filterProducts('dinh-duong')" class="prod-cat-btn cat-nav-item px-3 py-1.5 rounded-md text-xs font-medium bg-slate-100 text-slate-700 hover:bg-sky-50 hover:text-petPrimary border border-slate-200">
                    Vitamin & Bổ trợ sức khỏe
                </button>
            </div>

            <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4), KHÔNG nhãn dán -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 md:gap-4">
                <!-- Được render tự động bằng JS bên dưới để đảm bảo lọc mượt và hiển thị đầy đủ 11 sản phẩm thực tế + web mẫu -->
            </div>
        </div>
    </section>

    <!-- ==========================================
         TRANG THIẾT BỊ TỐI TÂN & TIÊU CHUẨN PHÒNG KHÁM (Theo đúng bố cục web mẫu GoVet)
    =========================================== -->
    <section id="trang-thiet-bi" class="py-6 md:py-8">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-main text-base sm:text-lg md:text-xl font-extrabold text-petDark uppercase tracking-wide">
                    TRANG THIẾT BỊ TỐI TÂN & TIÊU CHUẨN CHUYÊN MÔN
                </h2>
                <p class="text-center text-xs text-slate-500 mt-1 max-w-3xl mx-auto">
                    Luôn cập nhật và trang bị những thiết bị máy móc hiện đại: máy X-quang, máy siêu âm, hệ thống xét nghiệm sinh lý - sinh hóa, thiết bị hỗ trợ phẫu thuật để điều trị cho các bé tốt nhất.
                </p>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5 md:gap-4">
                <div class="bg-white rounded-xl p-4 border border-slate-200 shadow-xs space-y-2">
                    <div class="w-11 h-11 rounded-lg bg-sky-100 text-petPrimary flex items-center justify-center text-xl">
                        <i class="fa-solid fa-certificate"></i>
                    </div>
                    <h3 class="text-sm font-bold text-petDark">Phòng khám đạt chuẩn Thú Y</h3>
                    <p class="text-xs text-slate-600 leading-relaxed">
                        Huy Toàn Pet Clinic được cấp phép hoạt động đầy đủ về dịch vụ khám chữa bệnh, lưu chuồng chăm sóc, thiết bị y khoa và nhà thuốc dược phẩm thú y chính hãng tại Đà Nẵng.
                    </p>
                </div>

                <div class="bg-white rounded-xl p-4 border border-slate-200 shadow-xs space-y-2">
                    <div class="w-11 h-11 rounded-lg bg-teal-100 text-petTeal flex items-center justify-center text-xl">
                        <i class="fa-solid fa-user-graduate"></i>
                    </div>
                    <h3 class="text-sm font-bold text-petDark">Trình độ chuyên môn Bác sĩ thú y</h3>
                    <p class="text-xs text-slate-600 leading-relaxed">
                        Đội ngũ bác sĩ thú y được đào tạo bài bản từ các trường đại học ngành thú y hàng đầu, có nhiều năm kinh nghiệm thực chiến trong khám nội khoa và phẫu thuật ngoại khoa.
                    </p>
                </div>

                <div class="bg-white rounded-xl p-4 border border-slate-200 shadow-xs space-y-2">
                    <div class="w-11 h-11 rounded-lg bg-sky-100 text-petPrimary flex items-center justify-center text-xl">
                        <i class="fa-solid fa-hospital-user"></i>
                    </div>
                    <h3 class="text-sm font-bold text-petDark">Không gian phòng bệnh sạch thoáng</h3>
                    <p class="text-xs text-slate-600 leading-relaxed">
                        Không gian phòng khám rộng rãi, sạch sẽ, thoáng mát. Khu vực lưu chuồng nội trú và phòng điều trị truyền nhiễm được tách biệt và khử trùng định kỳ đảm bảo an toàn.
                    </p>
                </div>

                <div class="bg-white rounded-xl p-4 border border-slate-200 shadow-xs space-y-2">
                    <div class="w-11 h-11 rounded-lg bg-amber-100 text-amber-600 flex items-center justify-center text-xl">
                        <i class="fa-solid fa-laptop-medical"></i>
                    </div>
                    <h3 class="text-sm font-bold text-petDark">Máy móc y khoa hiện đại</h3>
                    <p class="text-xs text-slate-600 leading-relaxed">
                        Trang bị máy siêu âm kiểm tra nội tạng, hệ thống xét nghiệm máu phát hiện bệnh sớm và máy X-quang hỗ trợ chẩn đoán chính xác các ca chấn thương xương khớp.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FORM YÊU CẦU TƯ VẤN, ĐẶT LỊCH KHÁM & BÁO GIÁ TRANG CHỦ
    =========================================== -->
    <section id="bao-gia" class="py-6 md:py-8 bg-sky-50/70 border-y border-sky-100">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-main text-base sm:text-lg md:text-xl font-extrabold text-petDark uppercase tracking-wide">
                    ĐĂNG KÝ YÊU CẦU TƯ VẤN, ĐẶT LỊCH KHÁM & NHẬN BÁO GIÁ
                </h2>
                <p class="text-center text-xs text-slate-600 mt-1">
                    Điền thông tin bên dưới để Bác sĩ Thú y Huy Toàn tư vấn phác đồ và gửi báo giá chi tiết ngay lập tức
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-start">
                <!-- Cột Form Yêu Cầu & Báo Giá -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 p-4 sm:p-6 shadow-xs">
                    <h3 class="text-sm sm:text-base font-bold text-petDark mb-3 flex items-center gap-2">
                        <i class="fa-solid fa-file-signature text-petPrimary"></i>
                        <span>Form Gửi Yêu Cầu Đặt Lịch & Báo Giá Nhanh</span>
                    </h3>

                    <form id="quoteRequestForm" onsubmit="handleQuoteSubmit(event)" class="space-y-3">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên chủ nuôi *</label>
                                <input 
                                    type="text" 
                                    id="custName" 
                                    required 
                                    placeholder="Nhập họ và tên của bạn" 
                                    class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs focus:outline-none focus:border-petPrimary"
                                >
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input 
                                    type="tel" 
                                    id="custPhone" 
                                    required 
                                    placeholder="Ví dụ: 0396912692" 
                                    class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs focus:outline-none focus:border-petPrimary"
                                >
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Loại thú cưng & Cân nặng</label>
                                <input 
                                    type="text" 
                                    id="petType" 
                                    placeholder="VD: Chó Poodle 5kg / Mèo Anh 3.5kg" 
                                    class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs focus:outline-none focus:border-petPrimary"
                                >
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Dịch vụ / Sản phẩm cần báo giá *</label>
                                <select 
                                    id="serviceSelect" 
                                    required 
                                    class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs bg-white focus:outline-none focus:border-petPrimary"
                                >
                                    <option value="Khám sức khỏe và điều trị bệnh">Khám sức khỏe và điều trị bệnh</option>
                                    <option value="Siêu âm – Chụp X quang">Siêu âm – Chụp X quang</option>
                                    <option value="Xét nghiệm máu">Xét nghiệm máu sinh lý - sinh hóa</option>
                                    <option value="Tiêm vaccine chó & mèo">Tiêm vaccine phòng bệnh chó & mèo</option>
                                    <option value="Triệt sản chó & mèo">Phẫu thuật Thiến / Triệt sản chó & mèo</option>
                                    <option value="Phẫu thuật mổ đẻ / Ngoại khoa">Phẫu thuật mổ đẻ / Phẫu thuật xương / Ngoại khoa</option>
                                    <option value="Spa & Grooming">Spa & Grooming làm đẹp thú cưng</option>
                                    <option value="Cấp cứu 24/24 / Khám tại nhà">Cấp cứu 24/24 / Khám điều trị tại nhà</option>
                                    <option value="Mua Dược phẩm & Thuốc thú y">Mua Dược phẩm & Thuốc thú y (Sỉ / Lẻ)</option>
                                </select>
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Triệu chứng của bé hoặc tên thuốc cần báo giá</label>
                            <textarea 
                                id="custNote" 
                                rows="3" 
                                placeholder="Mô tả triệu chứng của thú cưng, ngày giờ muốn đặt lịch hoặc tên sản phẩm cần báo giá..." 
                                class="w-full rounded-lg border border-slate-300 px-3 py-2 text-xs focus:outline-none focus:border-petPrimary"
                            ></textarea>
                        </div>

                        <div class="flex flex-wrap items-center justify-between gap-2 pt-1">
                            <div class="text-[11px] text-slate-500">
                                <i class="fa-solid fa-headset text-petPrimary mr-1"></i>
                                Hotline trực tiếp: <strong>0396.912692 - 0974.554922</strong>
                            </div>
                            <button 
                                type="submit" 
                                class="px-5 py-2.5 rounded-lg bg-petPrimary hover:bg-petDark text-white font-bold text-xs shadow-sm transition cursor-pointer"
                            >
                                <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU & NHẬN BÁO GIÁ
                            </button>
                        </div>
                    </form>

                    <!-- Hộp thông báo kết quả gửi form -->
                    <div id="quoteSuccessBox" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs"></div>
                </div>

                <!-- Cột Bảng Giá Tham Khảo Nhanh -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 p-4 sm:p-6 shadow-xs space-y-3">
                    <h3 class="text-sm sm:text-base font-bold text-petDark flex items-center gap-2">
                        <i class="fa-solid fa-tags text-petTeal"></i>
                        <span>Bảng Giá Dịch Vụ Thú Y Tham Khảo</span>
                    </h3>
                    <p class="text-xs text-slate-500">
                        Chi phí minh bạch, hợp lý, bác sĩ luôn tư vấn rõ phương án và báo giá trước khi thực hiện:
                    </p>
                    <div class="overflow-x-auto">
                        <table class="w-full text-left border-collapse text-xs">
                            <thead>
                                <tr class="bg-sky-50 text-petDark border-b border-sky-100">
                                    <th class="py-2 px-2.5 font-bold">Hạng mục Dịch vụ / Sản phẩm</th>
                                    <th class="py-2 px-2.5 font-bold text-right">Đơn giá tham khảo</th>
                                </tr>
                            </thead>
                            <tbody class="divide-y divide-slate-100 text-slate-700">
                                <tr>
                                    <td class="py-2 px-2.5">Khám lâm sàng & Tư vấn phác đồ</td>
                                    <td class="py-2 px-2.5 text-right font-semibold text-petPrimary">Miễn phí tư vấn</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-2.5">Tiêm Vaccine 5 bệnh / 7 bệnh cho cún</td>
                                    <td class="py-2 px-2.5 text-right font-semibold">160.000đ - 180.000đ</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-2.5">Tiêm Vaccine 4 bệnh cho mèo</td>
                                    <td class="py-2 px-2.5 text-right font-semibold">260.000đ - 280.000đ</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-2.5">Tiêm Vaccine phòng Dại chó mèo</td>
                                    <td class="py-2 px-2.5 text-right font-semibold">80.000đ / mũi</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-2.5">Thiến mèo đực / Triệt sản mèo cái</td>
                                    <td class="py-2 px-2.5 text-right font-semibold">250.000đ - 500.000đ</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-2.5">Thiến chó đực / Triệt sản chó cái</td>
                                    <td class="py-2 px-2.5 text-right font-semibold">Theo cân nặng</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-2.5">Siêu âm ổ bụng / Siêu âm thai</td>
                                    <td class="py-2 px-2.5 text-right font-semibold">100.000đ - 150.000đ</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-2.5">Chụp X-Quang kỹ thuật số</td>
                                    <td class="py-2 px-2.5 text-right font-semibold">150.000đ - 250.000đ</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-2.5">Xét nghiệm máu sinh lý / sinh hóa</td>
                                    <td class="py-2 px-2.5 text-right font-semibold">150.000đ - 350.000đ</td>
                                </tr>
                                <tr>
                                    <td class="py-2 px-2.5">Tắm Spa, vệ sinh tai, cắt tỉa lông</td>
                                    <td class="py-2 px-2.5 text-right font-semibold">100.000đ - 300.000đ</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                    <div class="p-3 rounded-lg bg-sky-50 border border-sky-100 text-[11px] text-slate-600 leading-relaxed">
                        <strong class="text-petDark">Lưu ý:</strong> Đối với các ca phẫu thuật ngoại khoa, mổ đẻ hoặc mua thuốc thú y số lượng lớn, quý khách vui lòng điền form bên cạnh hoặc liên hệ <strong>0396.912692 - 0974.554922</strong> để nhận báo giá chi tiết.
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Cẩm nang & Tin tức thú y chuẩn Flatsome)
    =========================================== -->
    <section id="bai-viet" class="py-6 md:py-8 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-main text-base sm:text-lg md:text-xl font-extrabold text-petDark uppercase tracking-wide">
                    DANH MỤC BÀI VIẾT & KIẾN THỨC CHĂM SÓC THÚ CƯNG
                </h2>
                <p class="text-center text-xs text-slate-500 mt-1">
                    Chia sẻ kinh nghiệm nuôi dưỡng, lịch tiêm phòng vaccine và cách nhận biết sớm các bệnh lý ở chó mèo
                </p>
            </div>

            <!-- Thanh danh mục bài viết nhỏ gọn trên 1 hàng -->
            <div class="flex items-center justify-start sm:justify-center gap-1.5 overflow-x-auto no-scrollbar pb-3 mb-3">
                <button type="button" onclick="filterPosts('all')" class="post-cat-btn cat-nav-item px-3 py-1 rounded text-xs font-semibold bg-petPrimary text-white">
                    Tất cả bài viết
                </button>
                <button type="button" onclick="filterPosts('lich-tiem')" class="post-cat-btn cat-nav-item px-3 py-1 rounded text-xs font-medium bg-slate-100 text-slate-700 hover:bg-sky-50 hover:text-petPrimary">
                    Lịch tiêm phòng & Tẩy giun
                </button>
                <button type="button" onclick="filterPosts('benh-ly')" class="post-cat-btn cat-nav-item px-3 py-1 rounded text-xs font-medium bg-slate-100 text-slate-700 hover:bg-sky-50 hover:text-petPrimary">
                    Bệnh học & Cấp cứu thú y
                </button>
                <button type="button" onclick="filterPosts('dinh-duong')" class="post-cat-btn cat-nav-item px-3 py-1 rounded text-xs font-medium bg-slate-100 text-slate-700 hover:bg-sky-50 hover:text-petPrimary">
                    Dinh dưỡng & Chăm sóc hậu phẫu
                </button>
            </div>

            <!-- Danh sách 4 bài viết trang chủ (2 cột trên điện thoại, 4 cột trên máy tính, không dán nhãn) -->
            <div id="blogGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                
                <article data-post-cat="lich-tiem" class="blog-card bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col hover:shadow-md transition">
                    <div class="aspect-16/10 bg-slate-200 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1RW9Z6yOLprRrBbjCDEX2JW2Jp1LKOGcl&sz=w600" alt="Lịch tiêm phòng vaccine cho chó mèo" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark hover:text-petPrimary">
                                Lịch tiêm phòng Vaccine 5 bệnh, 7 bệnh cho chó và 4 bệnh cho mèo đầy đủ nhất
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5">
                                Hướng dẫn thời điểm tiêm mũi 1, mũi 2, mũi 3 và tiêm nhắc lại hàng năm giúp bảo vệ bé khỏi Parvo, Care, Giảm bạch cầu.
                            </p>
                        </div>
                        <button type="button" onclick="openArticleModal(0)" class="mt-2.5 text-left text-[11px] font-semibold text-petPrimary hover:underline">
                            Đọc chi tiết bài viết →
                        </button>
                    </div>
                </article>

                <article data-post-cat="benh-ly" class="blog-card bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col hover:shadow-md transition">
                    <div class="aspect-16/10 bg-slate-200 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1psu878DHC-9uc6A-5Cc-U5qAj21jyV2i&sz=w600" alt="Dấu hiệu bệnh Parvo và Care" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark hover:text-petPrimary">
                                Dấu hiệu nhận biết sớm chó mèo bị nôn mửa, bỏ ăn, tiêu chảy cấp và cách xử lý
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5">
                                Khi thấy thú cưng mệt mỏi, nôn ra dịch vàng hoặc tiêu chảy ra máu, chủ nuôi cần lưu ý những gì trước khi đưa đến phòng khám?
                            </p>
                        </div>
                        <button type="button" onclick="openArticleModal(1)" class="mt-2.5 text-left text-[11px] font-semibold text-petPrimary hover:underline">
                            Đọc chi tiết bài viết →
                        </button>
                    </div>
                </article>

                <article data-post-cat="dinh-duong" class="blog-card bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col hover:shadow-md transition">
                    <div class="aspect-16/10 bg-slate-200 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1Wy3WlUgVRRo_1fn-1UbJEB0PsSKsm9TN&sz=w600" alt="Chăm sóc chó mèo sau triệt sản" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark hover:text-petPrimary">
                                Hướng dẫn chăm sóc chó mèo trước và sau khi phẫu thuật triệt sản, mổ đẻ
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5">
                                Quy trình nhịn ăn trước khi gây mê, vệ sinh vết mổ tại nhà và chế độ dinh dưỡng giúp thú cưng hồi phục nhanh chóng.
                            </p>
                        </div>
                        <button type="button" onclick="openArticleModal(2)" class="mt-2.5 text-left text-[11px] font-semibold text-petPrimary hover:underline">
                            Đọc chi tiết bài viết →
                        </button>
                    </div>
                </article>

                <article data-post-cat="lich-tiem" class="blog-card bg-slate-50 rounded-lg border border-slate-200 overflow-hidden flex flex-col hover:shadow-md transition">
                    <div class="aspect-16/10 bg-slate-200 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1JXIOBXu2_2i8gllcPg15XuP8XpvbCCU2&sz=w600" alt="Phòng trị ve rận ghẻ nấm" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-petDark hover:text-petPrimary">
                                Phác đồ phòng và điều trị dứt điểm ve rận, bọ chét, ghẻ Demodex và nấm da
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5">
                                Kết hợp viên nhai diệt ký sinh trùng, thuốc nhỏ gáy và kháng sinh - vitamin hỗ trợ phục hồi da lông hiệu quả tại nhà.
                            </p>
                        </div>
                        <button type="button" onclick="openArticleModal(3)" class="mt-2.5 text-left text-[11px] font-semibold text-petPrimary hover:underline">
                            Đọc chi tiết bài viết →
                        </button>
                    </div>
                </article>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC ĐỐI TÁC DƯỢC PHẨM & THÚ Y CHÍNH HÃNG
    =========================================== -->
    <section id="doi-tac" class="py-6 md:py-8">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-main text-base sm:text-lg md:text-xl font-extrabold text-petDark uppercase tracking-wide">
                    ĐỐI TÁC DƯỢC PHẨM & THƯƠNG HIỆU ĐỒNG HÀNH
                </h2>
                <p class="text-center text-xs text-slate-500 mt-1">
                    Huy Toàn Pet Clinic sử dụng vaccine, thuốc thú y và dinh dưỡng chính hãng từ các tập đoàn uy tín trong và ngoài nước
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 md:gap-3">
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center shadow-xs hover:border-petPrimary transition">
                    <div class="text-xs font-extrabold text-petDark tracking-wide">ZOETIS</div>
                    <div class="text-[10px] text-slate-500 mt-0.5">Hoa Kỳ • Vaccine & Thuốc</div>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center shadow-xs hover:border-petPrimary transition">
                    <div class="text-xs font-extrabold text-petDark tracking-wide">VIRBAC</div>
                    <div class="text-[10px] text-slate-500 mt-0.5">Pháp • Dược phẩm thú y</div>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center shadow-xs hover:border-petPrimary transition">
                    <div class="text-xs font-extrabold text-petDark tracking-wide">BOEHRINGER</div>
                    <div class="text-[10px] text-slate-500 mt-0.5">Đức • NexGard & Vaccine</div>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center shadow-xs hover:border-petPrimary transition">
                    <div class="text-xs font-extrabold text-petDark tracking-wide">MSD ANIMAL</div>
                    <div class="text-[10px] text-slate-500 mt-0.5">Nobivac & Bravecto</div>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center shadow-xs hover:border-petPrimary transition">
                    <div class="text-xs font-extrabold text-petDark tracking-wide">BAYER / ELANCO</div>
                    <div class="text-[10px] text-slate-500 mt-0.5">Drontal & Ký sinh trùng</div>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center shadow-xs hover:border-petPrimary transition">
                    <div class="text-xs font-extrabold text-petDark tracking-wide">ROYAL CANIN</div>
                    <div class="text-[10px] text-slate-500 mt-0.5">Dinh dưỡng y khoa</div>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center shadow-xs hover:border-petPrimary transition">
                    <div class="text-xs font-extrabold text-petDark tracking-wide">VEMEDIM</div>
                    <div class="text-[10px] text-slate-500 mt-0.5">Thuốc thú y đạt chuẩn</div>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-3 flex flex-col items-center justify-center text-center shadow-xs hover:border-petPrimary transition">
                    <div class="text-xs font-extrabold text-petDark tracking-wide">BIO PHARMA</div>
                    <div class="text-[10px] text-slate-500 mt-0.5">Kháng sinh & Vitamin</div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK NGOÀI TRANG CHỦ
         - Đưa Google Map địa chỉ T605 Dương Sơn, Hòa Tiến, TP Đà Nẵng ra ngoài trang chủ
         - Đưa Fanpage Phòng Khám Thú Y Hòa Tiến - Huy Toàn Pet Clinic ra ngoài trang chủ
    =========================================== -->
    <section id="ban-do-fanpage" class="py-6 md:py-8 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <h2 class="section-title-main text-base sm:text-lg md:text-xl font-extrabold text-petDark uppercase tracking-wide">
                    BẢN ĐỒ CHỈ ĐƯỜNG & FANPAGE PHÒNG KHÁM
                </h2>
                <p class="text-center text-xs text-slate-500 mt-1">
                    Địa chỉ: T605 Dương Sơn, Hòa Tiến, TP Đà Nẵng • Điện thoại: 0396.912692 - 0974.554922
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
                <!-- Cột Google Map ngoài trang chủ (7 cột) -->
                <div class="lg:col-span-7 bg-slate-50 rounded-xl border border-slate-200 p-3 sm:p-4 flex flex-col justify-between">
                    <div class="flex flex-wrap items-center justify-between gap-2 mb-2.5">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-petDark flex items-center gap-1.5">
                                <i class="fa-solid fa-map-location-dot text-petPrimary"></i>
                                <span>Bản Đồ Google Maps: T605 Dương Sơn, Hòa Tiến, TP Đà Nẵng</span>
                            </h3>
                            <p class="text-[11px] text-slate-500">Thuận tiện di chuyển cho khách hàng khu vực Hòa Tiến, Hòa Vang, Cẩm Lệ và TP Đà Nẵng</p>
                        </div>
                        <a 
                            href="https://www.google.com/maps/search/?api=1&query=D%C6%B0%C6%A1ng+S%C6%A1n+H%C3%B2a+Ti%E1%BA%BFn+%C4%90%C3%A0+N%E1%BA%B5ng" 
                            target="_blank" 
                            rel="noopener noreferrer" 
                            class="px-3 py-1.5 rounded bg-petPrimary hover:bg-petDark text-white text-[11px] font-semibold transition shrink-0"
                        >
                            <i class="fa-solid fa-diamond-turn-right mr-1"></i> Mở Google Maps Chỉ Đường
                        </a>
                    </div>

                    <div class="w-full h-[280px] sm:h-[330px] rounded-lg overflow-hidden border border-slate-300 bg-slate-200">
                        <iframe 
                            title="Bản đồ Phòng Khám Thú Y Hòa Tiến - Huy Toàn Pet Clinic"
                            src="https://www.google.com/maps?q=D%C6%B0%C6%A1ng+S%C6%A1n,+H%C3%B2a+Ti%E1%BA%BFn,+H%C3%B2a+Vang,+%C4%90%C3%A0+N%E1%BA%B5ng&output=embed" 
                            class="w-full h-full border-0" 
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <!-- Cột Fanpage Facebook ngoài trang chủ (5 cột) -->
                <div class="lg:col-span-5 bg-slate-50 rounded-xl border border-slate-200 p-3 sm:p-4 flex flex-col justify-between">
                    <div class="mb-2.5">
                        <h3 class="text-xs sm:text-sm font-bold text-petDark flex items-center gap-1.5">
                            <i class="fa-brands fa-facebook text-blue-600"></i>
                            <span>Fanpage: Phòng Khám Thú Y Hòa Tiến - Huy Toàn Pet Clinic</span>
                        </h3>
                        <p class="text-[11px] text-slate-500">Cập nhật hoạt động khám chữa bệnh và tư vấn trực tuyến hàng ngày</p>
                    </div>

                    <!-- Khung thông tin Fanpage trực quan + Plugin Facebook -->
                    <div class="bg-white rounded-lg border border-slate-200 p-3 space-y-3 flex-1 flex flex-col justify-between">
                        <div class="flex items-center gap-3 pb-2.5 border-b border-slate-100">
                            <img 
                                src="https://drive.google.com/thumbnail?id=1JYqsUuRVqTlQL9zErdSpxcQgNJ2PddbE&sz=w200" 
                                alt="Logo Fanpage Huy Toàn Pet Clinic" 
                                class="w-12 h-12 rounded-full border border-sky-200 object-contain p-0.5 shrink-0"
                            >
                            <div class="min-w-0">
                                <a href="https://www.facebook.com/phongkhamthuyhoatienhuytoanpetclinnic" target="_blank" rel="noopener noreferrer" class="text-xs sm:text-sm font-bold text-petDark hover:text-blue-600 block">
                                    Phòng Khám Thú Y Hòa Tiến - Huy Toàn Pet Clinic
                                </a>
                                <div class="text-[11px] text-slate-500">Phòng khám thú y • T605 Dương Sơn, Hòa Tiến, Đà Nẵng</div>
                                <div class="text-[11px] text-emerald-600 font-semibold mt-0.5">
                                    <i class="fa-solid fa-circle-check mr-1"></i>Đang hoạt động • SĐT: 0396.912692 - 0974.554922
                                </div>
                            </div>
                        </div>

                        <!-- Nhúng Facebook Page Plugin kết hợp ảnh hoạt động phòng khám -->
                        <div class="w-full overflow-hidden rounded border border-slate-200 bg-slate-100 flex flex-col items-center">
                            <iframe 
                                title="Fanpage Facebook Huy Toàn Pet Clinic"
                                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fphongkhamthuyhoatienhuytoanpetclinnic&tabs=timeline&width=340&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                width="340" 
                                height="180" 
                                style="border:none;overflow:hidden;max-width:100%;" 
                                scrolling="no" 
                                frameborder="0" 
                                allowfullscreen="true" 
                                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                            </iframe>
                        </div>

                        <div class="grid grid-cols-2 gap-2 pt-1">
                            <a 
                                href="https://www.facebook.com/phongkhamthuyhoatienhuytoanpetclinnic" 
                                target="_blank" 
                                rel="noopener noreferrer" 
                                class="py-2 px-3 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-semibold text-xs text-center transition"
                            >
                                <i class="fa-brands fa-facebook-f mr-1"></i> Truy cập Fanpage
                            </a>
                            <a 
                                href="https://m.me/phongkhamthuyhoatienhuytoanpetclinnic" 
                                target="_blank" 
                                rel="noopener noreferrer" 
                                class="py-2 px-3 rounded-lg bg-sky-100 hover:bg-sky-200 text-petDark font-semibold text-xs text-center transition"
                            >
                                <i class="fa-brands fa-facebook-messenger text-blue-600 mr-1"></i> Nhắn Messenger
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME (Đầy đủ thông tin liên hệ, dịch vụ, danh mục)
    =========================================== -->
    <footer class="bg-petDark text-sky-100 pt-8 pb-20 md:pb-8 border-t-4 border-petPrimary">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-sky-800/80">
                <!-- Cột 1: Thông tin Phòng Khám (4 cột) -->
                <div class="lg:col-span-4 space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1JYqsUuRVqTlQL9zErdSpxcQgNJ2PddbE&sz=w200" 
                            alt="Logo Huy Toàn Pet Clinic" 
                            class="w-10 h-10 rounded-full bg-white p-0.5 object-contain shrink-0"
                        >
                        <div>
                            <div class="text-sm font-extrabold text-white">HUY TOÀN PET CLINIC</div>
                            <div class="text-[11px] text-sky-300">Phòng Khám Thú Y Hòa Tiến - Đà Nẵng</div>
                        </div>
                    </div>
                    <p class="text-xs text-sky-100/90 leading-relaxed">
                        Chuyên khám và điều trị bệnh chó mèo, siêu âm, chụp X-quang, xét nghiệm máu, tiêm phòng vaccine, phẫu thuật ngoại khoa - triệt sản, cấp cứu 24/24 và phân phối dược phẩm thú y chính hãng.
                    </p>
                    <ul class="space-y-1.5 text-xs text-sky-100">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-amber-400 mt-0.5"></i>
                            <span><strong>Địa chỉ:</strong> T605 Dương Sơn, Hòa Tiến, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone-volume text-amber-400"></i>
                            <span><strong>Hotline / Zalo:</strong> 0396.912692 - 0974.554922</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-amber-400"></i>
                            <span><strong>Website:</strong> huytoanpetclinic.com</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Dịch vụ thú y (3 cột) -->
                <div class="lg:col-span-3 space-y-2">
                    <h4 class="text-xs font-extrabold uppercase tracking-wider text-white border-b border-sky-700 pb-1.5">
                        DỊCH VỤ THÚ Y CHUYÊN KHOA
                    </h4>
                    <ul class="space-y-1.5 text-xs text-sky-100/90">
                        <li><a href="#dich-vu" class="hover:text-amber-300">• Khám sức khỏe và điều trị bệnh</a></li>
                        <li><a href="#dich-vu" class="hover:text-amber-300">• Siêu âm ổ bụng – Chụp X-quang</a></li>
                        <li><a href="#dich-vu" class="hover:text-amber-300">• Xét nghiệm máu sinh lý - sinh hóa</a></li>
                        <li><a href="#dich-vu" class="hover:text-amber-300">• Tiêm phòng vaccine chó & mèo</a></li>
                        <li><a href="#dich-vu" class="hover:text-amber-300">• Phẫu thuật mổ đẻ, xương & triệt sản</a></li>
                        <li><a href="#dich-vu" class="hover:text-amber-300">• Cấp cứu 24/24 & Khám tại nhà</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục sản phẩm (3 cột) -->
                <div class="lg:col-span-3 space-y-2">
                    <h4 class="text-xs font-extrabold uppercase tracking-wider text-white border-b border-sky-700 pb-1.5">
                        DANH MỤC DƯỢC PHẨM & SẢN PHẨM
                    </h4>
                    <ul class="space-y-1.5 text-xs text-sky-100/90">
                        <li><a href="#san-pham" onclick="filterProducts('duoc-pham')" class="hover:text-amber-300">• Dược phẩm thú y chính hãng</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('khang-sinh')" class="hover:text-amber-300">• Thuốc kháng sinh & Đặc trị</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('ky-sinh-trung')" class="hover:text-amber-300">• Thuốc trị ve rận, ghẻ nấm, ký sinh trùng</a></li>
                        <li><a href="#san-pham" onclick="filterProducts('dinh-duong')" class="hover:text-amber-300">• Vitamin, Bổ máu, Giải độc gan thận</a></li>
                        <li><a href="#bao-gia" class="hover:text-amber-300">• Đăng ký nhận báo giá thuốc & dịch vụ</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Giờ làm việc & Kết nối (2 cột) -->
                <div class="lg:col-span-2 space-y-2">
                    <h4 class="text-xs font-extrabold uppercase tracking-wider text-white border-b border-sky-700 pb-1.5">
                        GIỜ LÀM VIỆC
                    </h4>
                    <p class="text-xs text-sky-100/90 leading-relaxed">
                        <strong>Thứ 2 - Chủ Nhật:</strong><br>
                        07:30 sáng – 20:00 tối<br>
                        <span class="text-amber-300 font-semibold">Trực cấp cứu thú y 24/24h</span>
                    </p>
                    <div class="pt-1 flex items-center gap-2">
                        <a href="https://www.facebook.com/phongkhamthuyhoatienhuytoanpetclinnic" target="_blank" rel="noopener noreferrer" class="w-8 h-8 rounded-full bg-blue-600 hover:bg-blue-500 text-white flex items-center justify-center text-xs" aria-label="Facebook">
                            <i class="fa-brands fa-facebook-f"></i>
                        </a>
                        <a href="https://zalo.me/0396912692" target="_blank" rel="noopener noreferrer" class="w-8 h-8 rounded-full bg-sky-500 hover:bg-sky-400 text-white flex items-center justify-center text-[10px] font-bold" aria-label="Zalo">
                            Zalo
                        </a>
                        <a href="tel:0396912692" class="w-8 h-8 rounded-full bg-emerald-600 hover:bg-emerald-500 text-white flex items-center justify-center text-xs" aria-label="Gọi điện">
                            <i class="fa-solid fa-phone"></i>
                        </a>
                    </div>
                </div>
            </div>

            <div class="pt-4 flex flex-wrap items-center justify-between gap-2 text-[11px] text-sky-300">
                <div>© Bản quyền thuộc về <strong>Huy Toàn Pet Clinic (huytoanpetclinic.com)</strong> - T605 Dương Sơn, Hòa Tiến, TP Đà Nẵng.</div>
                <div>Giao diện chuẩn Flatsome UX Builder • Tối ưu máy tính & điện thoại</div>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         Tương thích mượt trên cả máy tính và điện thoại, không làm tràn màn hình
    =========================================== -->
    <div class="fixed right-3 bottom-4 z-50 flex flex-col items-end gap-2">
        <!-- Nút Facebook Fanpage -->
        <a 
            href="https://www.facebook.com/phongkhamthuyhoatienhuytoanpetclinnic" 
            target="_blank" 
            rel="noopener noreferrer"
            class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white rounded-full shadow-lg px-3 py-2 transition"
            title="Chat Facebook Fanpage"
        >
            <i class="fa-brands fa-facebook-messenger text-base"></i>
            <span class="hidden sm:inline text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a 
            href="https://zalo.me/0396912692" 
            target="_blank" 
            rel="noopener noreferrer"
            class="flex items-center gap-2 bg-sky-500 hover:bg-sky-600 text-white rounded-full shadow-lg px-3 py-2 transition"
            title="Chat Zalo: 0396.912692"
        >
            <span class="w-5 h-5 rounded-full bg-white text-sky-600 font-extrabold text-[10px] flex items-center justify-center">Z</span>
            <span class="text-xs font-bold">Zalo Tư Vấn</span>
        </a>

        <!-- Nút Hotline 1 -->
        <a 
            href="tel:0396912692" 
            class="flex items-center gap-2 bg-rose-600 hover:bg-rose-700 text-white rounded-full shadow-lg px-3.5 py-2 transition"
            title="Gọi Hotline 1: 0396.912692"
        >
            <i class="fa-solid fa-phone-volume text-sm animate-ring"></i>
            <span class="text-xs font-extrabold">0396.912692</span>
        </a>

        <!-- Nút Hotline 2 -->
        <a 
            href="tel:0974554922" 
            class="flex items-center gap-2 bg-petTeal hover:bg-teal-700 text-white rounded-full shadow-lg px-3.5 py-1.5 transition"
            title="Gọi Hotline 2: 0974.554922"
        >
            <i class="fa-solid fa-phone text-xs"></i>
            <span class="text-[11px] font-bold">0974.554922</span>
        </a>
    </div>

    <!-- ==========================================
         MODAL XEM CHI TIẾT SẢN PHẨM / BÀI VIẾT (Thay thế hoàn toàn alert)
    =========================================== -->
    <div id="infoModal" class="fixed inset-0 bg-slate-900/60 z-50 hidden items-center justify-center p-3">
        <div class="bg-white rounded-xl max-w-lg w-full border border-slate-200 shadow-xl overflow-hidden">
            <div class="bg-petDark text-white px-4 py-3 flex items-center justify-between">
                <h3 id="modalTitle" class="text-xs sm:text-sm font-bold">Thông tin chi tiết</h3>
                <button type="button" onclick="closeInfoModal()" class="text-sky-200 hover:text-white text-sm">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="modalBody" class="p-4 text-xs text-slate-700 space-y-3 max-h-[75vh] overflow-y-auto"></div>
            <div class="px-4 py-3 bg-slate-50 border-t border-slate-200 flex items-center justify-end gap-2">
                <button type="button" onclick="closeInfoModal()" class="px-3 py-1.5 rounded bg-slate-200 hover:bg-slate-300 text-slate-700 text-xs font-semibold">
                    Đóng
                </button>
                <a href="tel:0396912692" class="px-3.5 py-1.5 rounded bg-petPrimary hover:bg-petDark text-white text-xs font-semibold">
                    <i class="fa-solid fa-phone mr-1"></i> Gọi tư vấn: 0396.912692
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ DỮ LIỆU SẢN PHẨM THỰC TẾ, SLIDER BANNER, LỌC DANH MỤC & FORM
    =========================================== -->
    <script>
        /* Danh sách 11 sản phẩm lấy từ 7 ảnh thực tế Google Drive của phòng khám + sản phẩm chuẩn web mẫu GoVet */
        const clinicProducts = [
            {
                id: 1,
                name: "Dung dịch tiêm kháng sinh đặc trị nhiễm khuẩn hô hấp & tiêu hóa cho chó mèo (Lọ 100ml)",
                category: "khang-sinh",
                categoryName: "Kháng sinh & Đặc trị",
                price: "Liên hệ báo giá",
                image: "https://drive.google.com/thumbnail?id=1RW9Z6yOLprRrBbjCDEX2JW2Jp1LKOGcl&sz=w700",
                desc: "Kháng sinh phổ rộng chuyên dùng trong phác đồ điều trị viêm phổi, viêm ruột, tiêu chảy cấp, nhiễm trùng vết thương và hậu phẫu cho thú cưng."
            },
            {
                id: 2,
                name: "Thuốc bổ trợ gan thận, giải độc cấp & phục hồi thể trạng cho thú cưng",
                category: "dinh-duong",
                categoryName: "Vitamin & Bổ trợ sức khỏe",
                price: "Liên hệ báo giá",
                image: "https://drive.google.com/thumbnail?id=1psu878DHC-9uc6A-5Cc-U5qAj21jyV2i&sz=w700",
                desc: "Hỗ trợ tăng cường chức năng gan thận, giải độc sau điều trị kháng sinh dài ngày, kích thích thèm ăn và phục hồi nhanh cho chó mèo suy nhược."
            },
            {
                id: 3,
                name: "Thuốc đặc trị ký sinh trùng máu, nội ngoại ký sinh trùng, ghẻ Demodex & ve rận",
                category: "ky-sinh-trung",
                categoryName: "Trị ve rận & Ký sinh trùng",
                price: "Liên hệ báo giá",
                image: "https://drive.google.com/thumbnail?id=1AHSK-b7ml7um_Dk7Ugv0IEbfA2CVE4GJ&sz=w700",
                desc: "Phác đồ đặc trị và phòng ngừa hiệu quả ve chó, bọ chét, rận tai, cái ghẻ Demodex, Sarcoptes và giun sán nội ngoại ký sinh."
            },
            {
                id: 4,
                name: "Phức hợp Vitamin B-Complex, Acid Amin & Khoáng chất tiêm/uống hồi sức thú cưng",
                category: "dinh-duong",
                categoryName: "Vitamin & Bổ trợ sức khỏe",
                price: "Liên hệ báo giá",
                image: "https://drive.google.com/thumbnail?id=1Wy3WlUgVRRo_1fn-1UbJEB0PsSKsm9TN&sz=w700",
                desc: "Bổ sung vitamin thiết yếu và khoáng chất giúp tăng sức đề kháng, bồi bổ máu, hỗ trợ chó mèo mang thai, nuôi con hoặc sau phẫu thuật."
            },
            {
                id: 5,
                name: "Thuốc kháng viêm, hạ sốt, giảm đau an toàn chuyên dụng trong thú y",
                category: "duoc-pham",
                categoryName: "Dược phẩm thú y",
                price: "Liên hệ báo giá",
                image: "https://drive.google.com/thumbnail?id=1JXIOBXu2_2i8gllcPg15XuP8XpvbCCU2&sz=w700",
                desc: "Kiểm soát nhanh triệu chứng sốt cao, viêm khớp, sưng đau mô mềm và hỗ trợ giảm đau hiệu quả sau phẫu thuật ngoại khoa, triệt sản."
            },
            {
                id: 6,
                name: "Thuốc đặc trị viêm đường tiêu hóa, nôn mửa, tiêu chảy phân máu ở chó mèo",
                category: "khang-sinh",
                categoryName: "Kháng sinh & Đặc trị",
                price: "Liên hệ báo giá",
                image: "https://drive.google.com/thumbnail?id=17P4YRmfqeBVjSxO16yp8bzNQnt1IoUG8&sz=w700",
                desc: "Đặc trị nhiễm trùng đường ruột, tiêu chảy cấp tính, viêm dạ dày - ruột và bảo vệ niêm mạc tiêu hóa cho cún và mèo."
            },
            {
                id: 7,
                name: "Chế phẩm tăng cường miễn dịch, điện giải & men tiêu hóa sống cho chó mèo",
                category: "dinh-duong",
                categoryName: "Vitamin & Bổ trợ sức khỏe",
                price: "Liên hệ báo giá",
                image: "https://drive.google.com/thumbnail?id=1Edz-jFCaTepa3xGRjQv51SWZWFg7HfB0&sz=w700",
                desc: "Cân bằng hệ vi sinh đường ruột, bù nước và điện giải, tăng cường kháng thể tự nhiên cho thú cưng ở giai đoạn tách mẹ hoặc đang điều trị bệnh."
            },
            {
                id: 8,
                name: "Thuốc nhỏ mắt, nhỏ mũi & vệ sinh tai đặc trị viêm tai giữa, rận tai (Lọ 10ml)",
                category: "duoc-pham",
                categoryName: "Dược phẩm thú y",
                price: "Liên hệ báo giá",
                image: "https://drive.google.com/thumbnail?id=1RW9Z6yOLprRrBbjCDEX2JW2Jp1LKOGcl&sz=w700",
                desc: "Dược phẩm thú y chuyên điều trị chảy nước mắt, ghèn mắt, viêm kết mạc, viêm tai có mủ và mùi hôi ở chó mèo."
            },
            {
                id: 9,
                name: "Viên nhai & Nhỏ gáy diệt ve rận, bọ chét, ghẻ nấm tác dụng kéo dài cho chó mèo",
                category: "ky-sinh-trung",
                categoryName: "Trị ve rận & Ký sinh trùng",
                price: "Liên hệ báo giá",
                image: "https://drive.google.com/thumbnail?id=1AHSK-b7ml7um_Dk7Ugv0IEbfA2CVE4GJ&sz=w700",
                desc: "Bảo vệ toàn diện thú cưng khỏi ve rận, bọ chét, ghẻ Demodex, ghẻ Sarcoptes và phòng ngừa giun tim định kỳ."
            },
            {
                id: 10,
                name: "Gel dinh dưỡng năng lượng cao & Sữa bột y khoa cho chó mèo con, chó mèo bệnh",
                category: "dinh-duong",
                categoryName: "Vitamin & Bổ trợ sức khỏe",
                price: "Liên hệ báo giá",
                image: "https://drive.google.com/thumbnail?id=1psu878DHC-9uc6A-5Cc-U5qAj21jyV2i&sz=w700",
                desc: "Cung cấp nguồn năng lượng dễ hấp thu, giàu vitamin và khoáng chất cho chó mèo biếng ăn, mới ốm dậy hoặc sau sinh."
            },
            {
                id: 11,
                name: "Dung dịch xịt sát khuẩn vết thương, trị nấm da, viêm da có mủ chuyên dụng thú y",
                category: "duoc-pham",
                categoryName: "Dược phẩm thú y",
                price: "Liên hệ báo giá",
                image: "https://drive.google.com/thumbnail?id=1Wy3WlUgVRRo_1fn-1UbJEB0PsSKsm9TN&sz=w700",
                desc: "Làm sạch và sát trùng vết thương hở, vết khâu phẫu thuật, điều trị nấm đồng xu, viêm da tiết bã và ngứa rụng lông."
            }
        ];

        let activeProductCategory = 'all';
        let currentSearchKeyword = '';

        /* Hàm hiển thị danh sách sản phẩm (Chia 2 cột trên điện thoại, 4 cột trên máy tính, tên hiển thị đầy đủ không cắt chữ, không nhãn dán) */
        function renderProducts() {
            const grid = document.getElementById('productGrid');
            if (!grid) return;

            const filtered = clinicProducts.filter(item => {
                const matchCat = (activeProductCategory === 'all') || (item.category === activeProductCategory);
                const matchKeyword = !currentSearchKeyword ||
                    item.name.toLowerCase().includes(currentSearchKeyword.toLowerCase()) ||
                    item.categoryName.toLowerCase().includes(currentSearchKeyword.toLowerCase());
                return matchCat && matchKeyword;
            });

            if (filtered.length === 0) {
                grid.innerHTML = `
                    <div class="col-span-2 lg:col-span-4 bg-slate-50 rounded-lg p-6 text-center border border-slate-200">
                        <p class="text-xs text-slate-600 font-medium">Không tìm thấy sản phẩm phù hợp với từ khóa. Quý khách vui lòng liên hệ Hotline <strong>0396.912692</strong> để bác sĩ tư vấn trực tiếp.</p>
                    </div>
                `;
                return;
            }

            grid.innerHTML = filtered.map(prod => `
                <div class="bg-slate-50 rounded-lg border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="aspect-square sm:aspect-4/3 bg-white overflow-hidden border-b border-slate-100">
                        <img 
                            src="${prod.image}" 
                            alt="${prod.name}" 
                            class="w-full h-full object-cover"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] font-semibold text-petTeal mb-1">${prod.categoryName}</div>
                            <h3 class="product-title-full text-xs sm:text-[13px] font-bold text-petDark">
                                ${prod.name}
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1 leading-relaxed">
                                ${prod.desc}
                            </p>
                        </div>
                        <div class="pt-2.5 mt-2 border-t border-slate-200/80 flex flex-col sm:flex-row sm:items-center justify-between gap-1.5">
                            <span class="text-xs font-extrabold text-petPrimary">${prod.price}</span>
                            <div class="flex items-center gap-1.5">
                                <button 
                                    type="button" 
                                    onclick="openProductModal(${prod.id})" 
                                    class="flex-1 sm:flex-initial px-2.5 py-1.5 rounded bg-white hover:bg-slate-100 text-slate-700 border border-slate-300 text-[11px] font-semibold transition"
                                >
                                    Chi tiết
                                </button>
                                <button 
                                    type="button" 
                                    onclick="prefillQuoteForm('${prod.name.replace(/'/g, "\\'")}')" 
                                    class="flex-1 sm:flex-initial px-2.5 py-1.5 rounded bg-petPrimary hover:bg-petDark text-white text-[11px] font-semibold transition"
                                >
                                    Báo giá
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        function filterProducts(cat) {
            activeProductCategory = cat;
            document.querySelectorAll('.prod-cat-btn').forEach(btn => {
                if (btn.getAttribute('data-cat') === cat) {
                    btn.className = "prod-cat-btn cat-nav-item px-3 py-1.5 rounded-md text-xs font-semibold bg-petPrimary text-white border border-petPrimary";
                } else {
                    btn.className = "prod-cat-btn cat-nav-item px-3 py-1.5 rounded-md text-xs font-medium bg-slate-100 text-slate-700 hover:bg-sky-50 hover:text-petPrimary border border-slate-200";
                }
            });
            renderProducts();
        }

        function selectCategoryAndScroll(cat) {
            filterProducts(cat);
            const section = document.getElementById('san-pham');
            if (section) section.scrollIntoView({ behavior: 'smooth' });
        }

        function scrollToServiceSection(serviceName) {
            const section = document.getElementById('dich-vu');
            if (section) section.scrollIntoView({ behavior: 'smooth' });
        }

        function filterProductsBySearch(keyword) {
            currentSearchKeyword = keyword || '';
            renderProducts();
        }

        /* Tự động trượt 2 Banner kích thước bằng nhau */
        let currentBannerIndex = 0;
        let bannerTimer = null;

        function showBannerSlide(index) {
            const slides = [document.getElementById('bannerSlide0'), document.getElementById('bannerSlide1')];
            const dots = [document.getElementById('bannerDot0'), document.getElementById('bannerDot1')];
            if (!slides[0] || !slides[1]) return;

            currentBannerIndex = (index + slides.length) % slides.length;
            slides.forEach((sl, idx) => {
                if (idx === currentBannerIndex) {
                    sl.classList.remove('hidden');
                    sl.classList.add('block');
                } else {
                    sl.classList.remove('block');
                    sl.classList.add('hidden');
                }
            });
            dots.forEach((dot, idx) => {
                if (!dot) return;
                if (idx === currentBannerIndex) {
                    dot.className = "w-5 h-1.5 rounded-full bg-amber-400 transition-all";
                } else {
                    dot.className = "w-2 h-1.5 rounded-full bg-white/60 transition-all";
                }
            });
        }

        function changeBannerSlide(step) {
            showBannerSlide(currentBannerIndex + step);
            resetBannerTimer();
        }

        function goToBannerSlide(index) {
            showBannerSlide(index);
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerTimer) clearInterval(bannerTimer);
            bannerTimer = setInterval(() => {
                showBannerSlide(currentBannerIndex + 1);
            }, 5000);
        }

        /* Đóng/mở menu trên điện thoại */
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            const icon = document.getElementById('mobileMenuIcon');
            if (!drawer) return;
            drawer.classList.toggle('hidden');
            if (icon) {
                icon.className = drawer.classList.contains('hidden')
                    ? 'fa-solid fa-bars text-base'
                    : 'fa-solid fa-xmark text-base';
            }
        }

        /* Điền nhanh dịch vụ/sản phẩm vào Form Yêu Cầu & Báo Giá */
        function prefillQuoteForm(itemName) {
            const noteEl = document.getElementById('custNote');
            const formSec = document.getElementById('bao-gia');
            if (noteEl) {
                noteEl.value = "Tôi cần tư vấn và nhận báo giá cho: " + itemName;
            }
            if (formSec) {
                formSec.scrollIntoView({ behavior: 'smooth' });
            }
        }

        /* Xử lý gửi Form Báo Giá */
        function handleQuoteSubmit(event) {
            event.preventDefault();
            const name = document.getElementById('custName').value.trim();
            const phone = document.getElementById('custPhone').value.trim();
            const pet = document.getElementById('petType').value.trim();
            const service = document.getElementById('serviceSelect').value;
            const note = document.getElementById('custNote').value.trim();

            const box = document.getElementById('quoteSuccessBox');
            if (box) {
                box.classList.remove('hidden');
                box.innerHTML = `
                    <div class="font-bold text-emerald-900 mb-1">
                        <i class="fa-solid fa-circle-check mr-1"></i> Đã tiếp nhận yêu cầu báo giá của ${name} (${phone})!
                    </div>
                    <div>
                        Hạng mục: <strong>${service}</strong> ${pet ? `• Thú cưng: <strong>${pet}</strong>` : ''}<br>
                        ${note ? `Nội dung: <em>${note}</em><br>` : ''}
                        Bác sĩ Phòng Khám Thú Y Hòa Tiến - Huy Toàn Pet Clinic sẽ liên hệ lại ngay qua SĐT/Zalo của bạn. Hoặc bạn có thể bấm gọi nhanh <strong>0396.912692 - 0974.554922</strong>.
                    </div>
                `;
            }
        }

        /* Lọc bài viết theo danh mục */
        function filterPosts(cat) {
            document.querySelectorAll('. blog-card, .blog-card').forEach(card => {
                const c = card.getAttribute('data-post-cat');
                if (cat === 'all' || c === cat) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        /* Xem chi tiết sản phẩm hoặc bài viết trong Modal */
        function openProductModal(id) {
            const prod = clinicProducts.find(p => p.id === id);
            if (!prod) return;
            const modal = document.getElementById('infoModal');
            document.getElementById('modalTitle').textContent = prod.categoryName;
            document.getElementById('modalBody').innerHTML = `
                <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-100 aspect-16/10">
                    <img src="${prod.image}" alt="${prod.name}" class="w-full h-full object-cover">
                </div>
                <h4 class="text-sm font-bold text-petDark">${prod.name}</h4>
                <p class="text-xs text-slate-600 leading-relaxed">${prod.desc}</p>
                <div class="p-2.5 rounded bg-sky-50 border border-sky-100 text-xs text-petDark">
                    <strong>Phân phối & Tư vấn liều dùng tại:</strong> Phòng Khám Thú Y Hòa Tiến - Huy Toàn Pet Clinic (T605 Dương Sơn, Hòa Tiến, TP Đà Nẵng).<br>
                    <strong>SĐT / Zalo bác sĩ:</strong> 0396.912692 - 0974.554922
                </div>
            `;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        const articleDetails = [
            {
                title: "Lịch tiêm phòng Vaccine 5 bệnh, 7 bệnh cho chó và 4 bệnh cho mèo đầy đủ nhất",
                content: "Để bảo vệ thú cưng khỏi các bệnh truyền nhiễm nguy hiểm (Parvovirus, Care, Ho cũi chó, Giảm bạch cầu mèo...), chó mèo con từ 6-8 tuần tuổi cần được tiêm mũi vaccine đầu tiên, sau đó tiêm nhắc lại mũi 2 và mũi 3 cách nhau 3-4 tuần, kèm mũi phòng Dại khi đủ 3 tháng tuổi. Trước khi tiêm, bác sĩ tại Huy Toàn Pet Clinic sẽ khám lâm sàng và đo thân nhiệt kỹ lưỡng."
            },
            {
                title: "Dấu hiệu nhận biết sớm chó mèo bị nôn mửa, bỏ ăn, tiêu chảy cấp và cách xử lý",
                content: "Khi chó mèo có biểu hiện ủ rũ, bỏ ăn, nôn ra bọt trắng hoặc dịch vàng, tiêu chảy phân tanh hoặc lẫn máu, chủ nuôi tuyệt đối không tự ý cho uống thuốc giảm đau của người. Hãy ngừng cho ăn thức ăn dầu mỡ và đưa bé đến ngay T605 Dương Sơn, Hòa Tiến hoặc gọi cấp cứu 0396.912692 để xét nghiệm test nhanh và truyền dịch kịp thời."
            },
            {
                title: "Hướng dẫn chăm sóc chó mèo trước và sau khi phẫu thuật triệt sản, mổ đẻ",
                content: "Trước khi phẫu thuật triệt sản, thú cưng cần nhịn ăn từ 6-8 tiếng để đảm bảo an toàn gây mê. Sau phẫu thuật tại Huy Toàn Pet Clinic, bé được tiêm kháng sinh, kháng viêm giảm đau và hướng dẫn đeo loa chống liếm, vệ sinh vết khâu hàng ngày giúp vết mổ khô nhanh và lành hẳn sau 7-10 ngày."
            },
            {
                title: "Phác đồ phòng và điều trị dứt điểm ve rận, bọ chét, ghẻ Demodex và nấm da",
                content: "Khí hậu nóng ẩm khiến chó mèo dễ nhiễm ve rận, ký sinh trùng máu và nấm da. Phòng khám cung cấp đầy đủ các dòng viên nhai, thuốc nhỏ gáy, thuốc tiêm đặc trị ngoại ký sinh kết hợp thuốc bổ gan thận và vitamin dưỡng lông giúp bé sạch ve rận và mọc lông mới khỏe mạnh."
            }
        ];

        function openArticleModal(idx) {
            const art = articleDetails[idx];
            if (!art) return;
            const modal = document.getElementById('infoModal');
            document.getElementById('modalTitle').textContent = "Cẩm nang chăm sóc thú cưng";
            document.getElementById('modalBody').innerHTML = `
                <h4 class="text-sm font-bold text-petDark">${art.title}</h4>
                <p class="text-xs text-slate-600 leading-relaxed">${art.content}</p>
                <div class="p-2.5 rounded bg-sky-50 border border-sky-100 text-xs text-petDark">
                    Cần bác sĩ tư vấn trực tiếp? Gọi ngay <strong>0396.912692 - 0974.554922</strong> hoặc ghé <strong>T605 Dương Sơn, Hòa Tiến, TP Đà Nẵng</strong>.
                </div>
            `;
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeInfoModal() {
            const modal = document.getElementById('infoModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        window.addEventListener('DOMContentLoaded', () => {
            renderProducts();
            resetBannerTimer();
        });
    </script>
</body>
</html>
