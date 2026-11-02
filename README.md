<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <title>CÔNG TY TNHH CƠ ĐIỆN HOÀNG ANH - Điện Máy & Cơ Điện Uy Tín Đà Nẵng | codienhoanganh.com</title>
  <meta name="description" content="CÔNG TY TNHH CƠ ĐIỆN HOÀNG ANH (codienhoanganh.com) chuyên cung cấp Điều hòa, Tủ lạnh, Máy giặt, Máy lọc nước, Quạt hơi nước, Quạt điều hòa chính hãng tại Đà Nẵng. Hotline: 0919.734.343 - 0905.110.299" />
  
  <!-- Open Graph / Thumbnail là ảnh Logo & Thương hiệu trang web khi gửi link -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://codienhoanganh.com/" />
  <meta property="og:site_name" content="CÔNG TY TNHH CƠ ĐIỆN HOÀNG ANH - codienhoanganh.com" />
  <meta property="og:title" content="CÔNG TY TNHH CƠ ĐIỆN HOÀNG ANH - Điện Máy Chính Hãng Đà Nẵng" />
  <meta property="og:description" content="Chuyên Điều hòa, Tủ lạnh, Máy giặt, Máy lọc nước, Quạt điều hòa, Quạt hơi nước tại Đà Nẵng. CS1: 21 Bàu Trảng 6 - CS2: 72 Võ Văn Tần. ĐT: 0919.734.343 - 0905.110.299" />
  <meta property="og:image" content="https://lh3.googleusercontent.com/d/1J9yw5Hk0ISJaFicapDKe6F5MHW3E9TX-" />
  <meta property="og:image:alt" content="Logo Công Ty TNHH Cơ Điện Hoàng Anh - codienhoanganh.com" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1J9yw5Hk0ISJaFicapDKe6F5MHW3E9TX-" />

  <!-- Favicon Logo -->
  <link rel="icon" type="image/jpeg" href="https://lh3.googleusercontent.com/d/1J9yw5Hk0ISJaFicapDKe6F5MHW3E9TX-" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <style>
    /* Reset chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
      background-color: #f5f7fa;
      color: #222222;
      scroll-behavior: smooth;
    }

    /* Cấu trúc chuẩn Flatsome UX Builder (Section / Row / Col) dễ chỉnh sửa */
    .flatsome-container {
      width: 100%;
      max-width: 1200px;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    /* Tiêu đề danh mục chuẩn Flatsome (Section Title Normal / Center) */
    .section-title-container {
      margin-bottom: 16px;
      border-bottom: 2px solid #e5e7eb;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
      gap: 8px;
    }
    .section-title-main {
      background-color: #0056b3;
      color: #ffffff;
      font-weight: 700;
      font-size: 15px;
      text-transform: uppercase;
      padding: 9px 16px;
      border-radius: 6px 6px 0 0;
      display: inline-flex;
      align-items: center;
      gap: 8px;
      margin-bottom: -2px;
      letter-spacing: 0.3px;
    }
    @media (min-width: 768px) {
      .section-title-main {
        font-size: 16px;
        padding: 10px 20px;
      }
    }

    /* Badge % Giảm giá chuẩn Flatsome góc trên bên trái */
    .flatsome-Discount-badge {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background-color: #d0011b;
      color: #ffffff;
      font-weight: 700;
      font-size: 12px;
      line-height: 1;
      padding: 6px 8px;
      border-radius: 4px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.18);
    }

    /* Product Box chuẩn Flatsome */
    .product-small.box {
      background: #ffffff;
      border: 1px solid #e5e7eb;
      border-radius: 8px;
      overflow: hidden;
      transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
      display: flex;
      flex-direction: column;
      height: 100%;
    }
    .product-small.box:hover {
      transform: translateY(-3px);
      box-shadow: 0 8px 20px rgba(0, 86, 179, 0.12);
      border-color: #0056b3;
    }

    /* Banner Slider bằng kích thước 100% */
    .banner-slider-viewport {
      position: relative;
      width: 100%;
      overflow: hidden;
      border-radius: 10px;
      background: #0b2e59;
      aspect-ratio: 16 / 7;
    }
    @media (max-width: 640px) {
      .banner-slider-viewport {
        aspect-ratio: 16 / 8.5;
      }
    }
    .banner-slide {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      opacity: 0;
      transition: opacity 0.6s ease-in-out;
      pointer-events: none;
    }
    .banner-slide.active {
      opacity: 1;
      pointer-events: auto;
    }
    .banner-slide img {
      width: 100%;
      height: 100%;
      object-fit: fill;
      display: block;
    }

    /* Nút nổi liên hệ Zalo, Facebook, Hotline */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(208, 1, 27, 0.6); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(208, 1, 27, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(208, 1, 27, 0); }
    }
    .floating-btn-pulse {
      animation: pulseRing 2s infinite;
    }

    /* Ẩn thanh cuộn phụ nhưng vẫn cho phép cuộn mượt nếu cần */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }
  </style>
</head>
<body class="w-full max-w-full overflow-x-hidden">

  <!-- =====================================================================
       1. TOP BAR CHUẨN FLATSOME (Đơn giản, không có tùy chọn UX Builder)
  ====================================================================== -->
  <div class="bg-[#003d82] text-white text-xs py-2 w-full border-b border-blue-800">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-2 truncate max-w-full">
        <i class="fa-solid fa-building text-yellow-400 shrink-0"></i>
        <span class="font-semibold truncate">CÔNG TY TNHH CƠ ĐIỆN HOÀNG ANH - codienhoanganh.com</span>
      </div>
      <div class="hidden md:flex items-center gap-4 text-[12px] text-blue-100">
        <span><i class="fa-solid fa-location-dot text-yellow-400 mr-1"></i>CS1: 21 Bàu Trảng 6, P. Thanh Khê, Đà Nẵng</span>
        <span>|</span>
        <span><i class="fa-solid fa-location-dot text-yellow-400 mr-1"></i>CS2: 72 Võ Văn Tần, P. Thanh Khê, Đà Nẵng</span>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       2. HEADER CHÍNH CHUẨN FLATSOME (Không để nút Gọi ngay để tránh tràn viền)
  ====================================================================== -->
  <header class="bg-white shadow-sm sticky top-0 z-40 w-full">
    <div class="flatsome-container py-3">
      <div class="flex items-center justify-between gap-3">
        
        <!-- Nút mở Menu Danh Mục trên Điện Thoại -->
        <button id="mobileMenuBtn" type="button" aria-label="Mở danh mục" class="lg:hidden flex items-center justify-center w-10 h-10 rounded-lg bg-slate-100 text-[#0056b3] hover:bg-blue-50 shrink-0">
          <i class="fa-solid fa-bars text-lg"></i>
        </button>

        <!-- Logo Trang Web (Dùng ảnh thực tế từ Google Drive làm Logo/Thumbnail) -->
        <a href="#top" class="flex items-center gap-2.5 min-w-0 shrink">
          <div class="w-11 h-11 sm:w-12 sm:h-12 rounded-lg overflow-hidden border border-blue-200 shrink-0 bg-blue-50 flex items-center justify-center">
            <img 
              data-drive-id="1J9yw5Hk0ISJaFicapDKe6F5MHW3E9TX-" 
              src="https://lh3.googleusercontent.com/d/1J9yw5Hk0ISJaFicapDKe6F5MHW3E9TX-" 
              alt="Logo Công Ty TNHH Cơ Điện Hoàng Anh" 
              class="w-full h-full object-cover"
            />
          </div>
          <div class="min-w-0">
            <div class="text-sm sm:text-base md:text-lg font-extrabold text-[#0056b3] leading-tight truncate">
              CƠ ĐIỆN HOÀNG ANH
            </div>
            <div class="text-[11px] sm:text-xs text-slate-500 font-medium truncate">
              codienhoanganh.com • Điện Máy Chính Hãng
            </div>
          </div>
        </a>

        <!-- Thanh Tìm Kiếm Sản Phẩm (Desktop) -->
        <div class="hidden md:flex flex-1 max-w-md mx-4">
          <div class="relative w-full">
            <input 
              id="desktopSearchInput"
              type="text" 
              placeholder="Tìm điều hòa, tủ lạnh, máy giặt, máy lọc nước..." 
              class="w-full pl-4 pr-10 py-2 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-[#0056b3]"
            />
            <button id="desktopSearchBtn" type="button" class="absolute right-1 top-1 bottom-1 px-3 bg-[#0056b3] text-white rounded-md text-xs hover:bg-blue-700">
              <i class="fa-solid fa-magnifying-glass"></i>
            </button>
          </div>
        </div>

        <!-- Cụm nút chức năng gọn gàng (Báo giá & Giỏ hàng - Không có nút Gọi Ngay) -->
        <div class="flex items-center gap-2 shrink-0">
          <a href="#form-bao-gia" class="hidden sm:inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-slate-100 hover:bg-blue-50 text-[#0056b3] text-xs font-semibold transition">
            <i class="fa-solid fa-file-invoice-dollar"></i>
            <span>Nhận Báo Giá</span>
          </a>
          <a href="#san-pham-trang-chu" class="inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-[#0056b3] text-white text-xs font-semibold hover:bg-blue-700 transition">
            <i class="fa-solid fa-cart-shopping"></i>
            <span class="hidden xs:inline">Sản Phẩm</span>
            <span id="cartCountBadge" class="bg-yellow-400 text-slate-900 font-bold px-1.5 py-0.5 rounded text-[10px]">12</span>
          </a>
        </div>

      </div>

      <!-- Thanh Tìm Kiếm trên Điện Thoại -->
      <div class="mt-2.5 md:hidden w-full">
        <div class="relative w-full">
          <input 
            id="mobileSearchInput"
            type="text" 
            placeholder="Tìm sản phẩm: Điều hòa, Tủ lạnh, Máy giặt..." 
            class="w-full pl-3.5 pr-10 py-2 text-xs border border-slate-300 rounded-lg focus:outline-none focus:border-[#0056b3]"
          />
          <button id="mobileSearchBtn" type="button" class="absolute right-1 top-1 bottom-1 px-3 bg-[#0056b3] text-white rounded-md text-xs">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </div>
      </div>
    </div>

    <!-- Thanh điều hướng Danh Mục trên Máy Tính (Tối ưu đẹp chuẩn dienmaykhanhtrung.com) -->
    <nav class="hidden lg:block bg-[#0056b3] text-white w-full border-t border-blue-600">
      <div class="flatsome-container flex items-center justify-between">
        
        <!-- Dropdown Tất Cả Danh Mục -->
        <div class="relative group">
          <button type="button" class="bg-[#d0011b] px-4 py-3 text-xs font-bold uppercase tracking-wide flex items-center gap-2.5 cursor-pointer">
            <i class="fa-solid fa-list-ul text-sm"></i>
            <span>DANH MỤC SẢN PHẨM</span>
            <i class="fa-solid fa-chevron-down text-[10px] ml-1"></i>
          </button>
          <!-- Mega Dropdown Danh Mục trên Máy Tính -->
          <div class="absolute left-0 top-full w-64 bg-white text-slate-800 shadow-xl rounded-b-lg border border-slate-200 hidden group-hover:block z-50 py-1">
            <a href="#san-pham-trang-chu" data-filter="Điều hòa" class="cat-filter-trigger flex items-center justify-between px-4 py-2.5 text-xs font-semibold hover:bg-blue-50 hover:text-[#0056b3] border-b border-slate-100">
              <span><i class="fa-solid fa-snowflake w-5 text-[#0056b3]"></i> Điều hòa - Máy lạnh</span>
              <i class="fa-solid fa-angle-right text-slate-400"></i>
            </a>
            <a href="#san-pham-trang-chu" data-filter="Tủ lạnh" class="cat-filter-trigger flex items-center justify-between px-4 py-2.5 text-xs font-semibold hover:bg-blue-50 hover:text-[#0056b3] border-b border-slate-100">
              <span><i class="fa-solid fa-temperature-arrow-down w-5 text-[#0056b3]"></i> Tủ lạnh - Tủ đông</span>
              <i class="fa-solid fa-angle-right text-slate-400"></i>
            </a>
            <a href="#san-pham-trang-chu" data-filter="Máy giặt" class="cat-filter-trigger flex items-center justify-between px-4 py-2.5 text-xs font-semibold hover:bg-blue-50 hover:text-[#0056b3] border-b border-slate-100">
              <span><i class="fa-solid fa-shirt w-5 text-[#0056b3]"></i> Máy giặt - Máy sấy</span>
              <i class="fa-solid fa-angle-right text-slate-400"></i>
            </a>
            <a href="#san-pham-trang-chu" data-filter="Máy lọc nước" class="cat-filter-trigger flex items-center justify-between px-4 py-2.5 text-xs font-semibold hover:bg-blue-50 hover:text-[#0056b3] border-b border-slate-100">
              <span><i class="fa-solid fa-droplet w-5 text-[#0056b3]"></i> Máy lọc nước</span>
              <i class="fa-solid fa-angle-right text-slate-400"></i>
            </a>
            <a href="#san-pham-trang-chu" data-filter="Quạt điều hòa" class="cat-filter-trigger flex items-center justify-between px-4 py-2.5 text-xs font-semibold hover:bg-blue-50 hover:text-[#0056b3] border-b border-slate-100">
              <span><i class="fa-solid fa-wind w-5 text-[#0056b3]"></i> Quạt điều hòa</span>
              <i class="fa-solid fa-angle-right text-slate-400"></i>
            </a>
            <a href="#san-pham-trang-chu" data-filter="Quạt hơi nước" class="cat-filter-trigger flex items-center justify-between px-4 py-2.5 text-xs font-semibold hover:bg-blue-50 hover:text-[#0056b3] border-b border-slate-100">
              <span><i class="fa-solid fa-fan w-5 text-[#0056b3]"></i> Quạt hơi nước</span>
              <i class="fa-solid fa-angle-right text-slate-400"></i>
            </a>
            <a href="#danh-muc-mau" class="flex items-center justify-between px-4 py-2.5 text-xs font-semibold hover:bg-blue-50 hover:text-[#0056b3] border-b border-slate-100">
              <span><i class="fa-solid fa-fire-flame-simple w-5 text-[#0056b3]"></i> Máy nước nóng</span>
              <i class="fa-solid fa-angle-right text-slate-400"></i>
            </a>
            <a href="#danh-muc-mau" class="flex items-center justify-between px-4 py-2.5 text-xs font-semibold hover:bg-blue-50 hover:text-[#0056b3] border-b border-slate-100">
              <span><i class="fa-solid fa-faucet-drip w-5 text-[#0056b3]"></i> Máy bơm nước</span>
              <i class="fa-solid fa-angle-right text-slate-400"></i>
            </a>
            <a href="#danh-muc-mau" class="flex items-center justify-between px-4 py-2.5 text-xs font-semibold hover:bg-blue-50 hover:text-[#0056b3] border-b border-slate-100">
              <span><i class="fa-solid fa-spray-can-sparkles w-5 text-[#0056b3]"></i> Máy rửa xe</span>
              <i class="fa-solid fa-angle-right text-slate-400"></i>
            </a>
            <a href="#danh-muc-mau" class="flex items-center justify-between px-4 py-2.5 text-xs font-semibold hover:bg-blue-50 hover:text-[#0056b3] border-b border-slate-100">
              <span><i class="fa-solid fa-screwdriver-wrench w-5 text-[#0056b3]"></i> Máy khoan, đục, cắt PIN</span>
              <i class="fa-solid fa-angle-right text-slate-400"></i>
            </a>
            <a href="#danh-muc-mau" class="flex items-center justify-between px-4 py-2.5 text-xs font-semibold hover:bg-blue-50 hover:text-[#0056b3] border-b border-slate-100">
              <span><i class="fa-solid fa-bolt w-5 text-[#0056b3]"></i> Máy phát điện</span>
              <i class="fa-solid fa-angle-right text-slate-400"></i>
            </a>
            <a href="#danh-muc-mau" class="flex items-center justify-between px-4 py-2.5 text-xs font-semibold hover:bg-blue-50 hover:text-[#0056b3]">
              <span><i class="fa-solid fa-solar-panel w-5 text-[#0056b3]"></i> Đèn năng lượng mặt trời</span>
              <i class="fa-solid fa-angle-right text-slate-400"></i>
            </a>
          </div>
        </div>

        <!-- Menu Ngang Chính -->
        <div class="flex items-center space-x-1 xl:space-x-2 text-xs font-semibold">
          <a href="#top" data-filter="ALL" class="cat-filter-trigger px-3 py-3 hover:bg-blue-700 rounded transition">TRANG CHỦ</a>
          <a href="#san-pham-trang-chu" data-filter="Điều hòa" class="cat-filter-trigger px-3 py-3 hover:bg-blue-700 rounded transition">ĐIỀU HÒA</a>
          <a href="#san-pham-trang-chu" data-filter="Tủ lạnh" class="cat-filter-trigger px-3 py-3 hover:bg-blue-700 rounded transition">TỦ LẠNH</a>
          <a href="#san-pham-trang-chu" data-filter="Máy giặt" class="cat-filter-trigger px-3 py-3 hover:bg-blue-700 rounded transition">MÁY GIẶT</a>
          <a href="#san-pham-trang-chu" data-filter="Máy lọc nước" class="cat-filter-trigger px-3 py-3 hover:bg-blue-700 rounded transition">MÁY LỌC NƯỚC</a>
          <a href="#san-pham-trang-chu" data-filter="Quạt điều hòa" class="cat-filter-trigger px-3 py-3 hover:bg-blue-700 rounded transition">QUẠT ĐIỀU HÒA</a>
          <a href="#san-pham-trang-chu" data-filter="Quạt hơi nước" class="cat-filter-trigger px-3 py-3 hover:bg-blue-700 rounded transition">QUẠT HƠI NƯỚC</a>
          <a href="#form-bao-gia" class="px-3 py-3 hover:bg-blue-700 rounded transition">BÁO GIÁ</a>
          <a href="#bai-viet-trang-chu" class="px-3 py-3 hover:bg-blue-700 rounded transition">BÀI VIẾT</a>
          <a href="#ban-do-fanpage" class="px-3 py-3 hover:bg-blue-700 rounded transition">BẢN ĐỒ & LIÊN HỆ</a>
        </div>

      </div>
    </nav>
  </header>

  <!-- =====================================================================
       MENU TRƯỢT MOBILE (Tối ưu danh mục trên điện thoại)
  ====================================================================== -->
  <div id="mobileMenuDrawer" class="fixed inset-0 z-50 hidden">
    <div id="mobileMenuBackdrop" class="absolute inset-0 bg-black/50"></div>
    <div class="relative w-72 max-w-[82vw] bg-white h-full shadow-2xl flex flex-col overflow-y-auto">
      <div class="p-4 bg-[#0056b3] text-white flex items-center justify-between">
        <span class="font-bold text-sm uppercase">Danh Mục Sản Phẩm</span>
        <button id="closeMobileMenuBtn" type="button" class="w-8 h-8 rounded-full bg-white/10 flex items-center justify-center text-white">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="divide-y divide-slate-100 text-xs font-semibold text-slate-700">
        <a href="#san-pham-trang-chu" data-filter="ALL" class="mobile-cat-link flex items-center gap-3 px-4 py-3 hover:bg-blue-50">
          <i class="fa-solid fa-border-all text-[#0056b3] w-5"></i> Tất cả sản phẩm thực tế (12)
        </a>
        <a href="#san-pham-trang-chu" data-filter="Điều hòa" class="mobile-cat-link flex items-center gap-3 px-4 py-3 hover:bg-blue-50">
          <i class="fa-solid fa-snowflake text-[#0056b3] w-5"></i> Điều hòa (Daikin, Panasonic, LG...)
        </a>
        <a href="#san-pham-trang-chu" data-filter="Tủ lạnh" class="mobile-cat-link flex items-center gap-3 px-4 py-3 hover:bg-blue-50">
          <i class="fa-solid fa-temperature-arrow-down text-[#0056b3] w-5"></i> Tủ lạnh (Hitachi, Panasonic, Aqua...)
        </a>
        <a href="#san-pham-trang-chu" data-filter="Máy giặt" class="mobile-cat-link flex items-center gap-3 px-4 py-3 hover:bg-blue-50">
          <i class="fa-solid fa-shirt text-[#0056b3] w-5"></i> Máy giặt (Electrolux, Toshiba, Aqua...)
        </a>
        <a href="#san-pham-trang-chu" data-filter="Máy lọc nước" class="mobile-cat-link flex items-center gap-3 px-4 py-3 hover:bg-blue-50">
          <i class="fa-solid fa-droplet text-[#0056b3] w-5"></i> Máy lọc nước (Karofi, Kangaroo...)
        </a>
        <a href="#san-pham-trang-chu" data-filter="Quạt điều hòa" class="mobile-cat-link flex items-center gap-3 px-4 py-3 hover:bg-blue-50">
          <i class="fa-solid fa-wind text-[#0056b3] w-5"></i> Quạt điều hòa
        </a>
        <a href="#san-pham-trang-chu" data-filter="Quạt hơi nước" class="mobile-cat-link flex items-center gap-3 px-4 py-3 hover:bg-blue-50">
          <i class="fa-solid fa-fan text-[#0056b3] w-5"></i> Quạt hơi nước
        </a>
        <a href="#danh-muc-mau" class="mobile-cat-link flex items-center gap-3 px-4 py-3 hover:bg-blue-50">
          <i class="fa-solid fa-fire-flame-simple text-[#0056b3] w-5"></i> Máy nước nóng & Máy bơm nước
        </a>
        <a href="#danh-muc-mau" class="mobile-cat-link flex items-center gap-3 px-4 py-3 hover:bg-blue-50">
          <i class="fa-solid fa-bolt text-[#0056b3] w-5"></i> Máy rửa xe, Máy phát điện, Đèn NLMT
        </a>
        <a href="#form-bao-gia" class="mobile-cat-link flex items-center gap-3 px-4 py-3 hover:bg-blue-50 text-[#d0011b]">
          <i class="fa-solid fa-file-signature w-5"></i> Form Yêu Cầu & Báo Giá
        </a>
        <a href="#bai-viet-trang-chu" class="mobile-cat-link flex items-center gap-3 px-4 py-3 hover:bg-blue-50">
          <i class="fa-solid fa-newspaper text-[#0056b3] w-5"></i> Tin Tức & Bài Viết
        </a>
        <a href="#ban-do-fanpage" class="mobile-cat-link flex items-center gap-3 px-4 py-3 hover:bg-blue-50">
          <i class="fa-solid fa-map-location-dot text-[#0056b3] w-5"></i> Google Map & Fanpage
        </a>
      </div>
      <div class="p-4 mt-auto bg-slate-50 border-t border-slate-200 text-xs space-y-1.5">
        <div class="font-bold text-[#0056b3]">CÔNG TY TNHH CƠ ĐIỆN HOÀNG ANH</div>
        <div><i class="fa-solid fa-phone text-red-600 mr-1.5"></i>0919.734.343 - 0905.110.299</div>
        <div><i class="fa-solid fa-location-dot text-blue-600 mr-1.5"></i>CS1: 21 Bàu Trảng 6, Thanh Khê, ĐN</div>
        <div><i class="fa-solid fa-location-dot text-blue-600 mr-1.5"></i>CS2: 72 Võ Văn Tần, Thanh Khê, ĐN</div>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       3. SLIDER 2 ẢNH BANNER TỰ TRƯỢT BẰNG KÍCH THƯỚC TỪ FILE GOOGLE DRIVE
  ====================================================================== -->
  <section id="top" class="py-3 sm:py-4 w-full">
    <div class="flatsome-container">
      <div class="banner-slider-viewport shadow-md border border-slate-200" id="heroBannerSlider">
        
        <!-- Slide 1: Ảnh Banner 1 từ Google Drive (1J9yw5Hk0ISJaFicapDKe6F5MHW3E9TX-) -->
        <div class="banner-slide active" data-slide-index="0">
          <img 
            data-drive-id="1J9yw5Hk0ISJaFicapDKe6F5MHW3E9TX-"
            src="https://lh3.googleusercontent.com/d/1J9yw5Hk0ISJaFicapDKe6F5MHW3E9TX-" 
            alt="Banner 1 - Công Ty TNHH Cơ Điện Hoàng Anh - codienhoanganh.com"
          />
        </div>

        <!-- Slide 2: Ảnh Banner 2 từ Google Drive (13C9G0l8CD8HkVc59ZwkcjmD0Xxk8HvlA) -->
        <div class="banner-slide" data-slide-index="1">
          <img 
            data-drive-id="13C9G0l8CD8HkVc59ZwkcjmD0Xxk8HvlA"
            src="https://lh3.googleusercontent.com/d/13C9G0l8CD8HkVc59ZwkcjmD0Xxk8HvlA" 
            alt="Banner 2 - Công Ty TNHH Cơ Điện Hoàng Anh - codienhoanganh.com"
          />
        </div>

        <!-- Nút điều hướng Trái / Phải -->
        <button id="prevBannerBtn" type="button" aria-label="Banner trước" class="absolute left-2.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/40 hover:bg-black/65 text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button id="nextBannerBtn" type="button" aria-label="Banner tiếp theo" class="absolute right-2.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/40 hover:bg-black/65 text-white flex items-center justify-center transition">
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Chấm tròn chỉ báo Slide -->
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" data-goto-slide="0" class="banner-dot w-2.5 h-2.5 rounded-full bg-white transition-all scale-125" aria-label="Slide 1"></button>
          <button type="button" data-goto-slide="1" class="banner-dot w-2.5 h-2.5 rounded-full bg-white/50 transition-all" aria-label="Slide 2"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       4. DANH MỤC SẢN PHẨM TRANG CHỦ (Lấy đầy đủ danh mục từ dienmaykhanhtrung.com,
          tối ưu hiển thị đẹp trên cả Máy tính và Điện thoại)
  ====================================================================== -->
  <section id="danh-muc-mau" class="py-3 sm:py-5 w-full">
    <div class="flatsome-container">
      <div class="bg-white rounded-xl p-3 sm:p-5 border border-slate-200 shadow-sm">
        
        <div class="section-title-container">
          <h2 class="section-title-main">
            <i class="fa-solid fa-layer-group"></i>
            <span>DANH MỤC SẢN PHẨM</span>
          </h2>
          <span class="text-xs text-slate-500 hidden sm:inline">Chuyên cung cấp & lắp đặt thiết bị điện máy - cơ điện chính hãng tại Đà Nẵng</span>
        </div>

        <!-- Lưới Danh Mục: 3 cột trên điện thoại, 4 cột trên tablet, 6 cột trên máy tính -->
        <div class="grid grid-cols-3 sm:grid-cols-4 lg:grid-cols-6 gap-2.5 sm:gap-3.5">
          
          <!-- 1. Điều hòa -->
          <button type="button" data-filter="Điều hòa" class="cat-filter-trigger group bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-[#0056b3] rounded-xl p-2.5 sm:p-3.5 flex flex-col items-center text-center transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg overflow-hidden mb-2 border border-slate-200 bg-white flex items-center justify-center">
              <img data-drive-id="1A902QNFp66OOtgFtKw2HldmYz7IBJiIT" src="https://lh3.googleusercontent.com/d/1A902QNFp66OOtgFtKw2HldmYz7IBJiIT" alt="Điều hòa" class="w-full h-full object-cover" />
            </div>
            <span class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-[#0056b3] line-clamp-1">Điều hòa</span>
            <span class="text-[10px] text-slate-500 mt-0.5 hidden sm:inline">Daikin, Panasonic, LG...</span>
          </button>

          <!-- 2. Tủ lạnh -->
          <button type="button" data-filter="Tủ lạnh" class="cat-filter-trigger group bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-[#0056b3] rounded-xl p-2.5 sm:p-3.5 flex flex-col items-center text-center transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg overflow-hidden mb-2 border border-slate-200 bg-white flex items-center justify-center">
              <img data-drive-id="1Fv8RldPmcSB2iVnidiFaz2rB9X3kmek8" src="https://lh3.googleusercontent.com/d/1Fv8RldPmcSB2iVnidiFaz2rB9X3kmek8" alt="Tủ lạnh" class="w-full h-full object-cover" />
            </div>
            <span class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-[#0056b3] line-clamp-1">Tủ lạnh</span>
            <span class="text-[10px] text-slate-500 mt-0.5 hidden sm:inline">Hitachi, Panasonic, Aqua...</span>
          </button>

          <!-- 3. Máy giặt -->
          <button type="button" data-filter="Máy giặt" class="cat-filter-trigger group bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-[#0056b3] rounded-xl p-2.5 sm:p-3.5 flex flex-col items-center text-center transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg overflow-hidden mb-2 border border-slate-200 bg-white flex items-center justify-center">
              <img data-drive-id="1moZc5jLhbim4jcw3v9zzV28yHnpSOemw" src="https://lh3.googleusercontent.com/d/1moZc5jLhbim4jcw3v9zzV28yHnpSOemw" alt="Máy giặt" class="w-full h-full object-cover" />
            </div>
            <span class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-[#0056b3] line-clamp-1">Máy giặt</span>
            <span class="text-[10px] text-slate-500 mt-0.5 hidden sm:inline">Electrolux, Toshiba, Aqua</span>
          </button>

          <!-- 4. Máy lọc nước -->
          <button type="button" data-filter="Máy lọc nước" class="cat-filter-trigger group bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-[#0056b3] rounded-xl p-2.5 sm:p-3.5 flex flex-col items-center text-center transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg overflow-hidden mb-2 border border-slate-200 bg-white flex items-center justify-center">
              <img data-drive-id="1GPmyaAk4AMu-JhK1h_5SNYcGY3GvJSEJ" src="https://lh3.googleusercontent.com/d/1GPmyaAk4AMu-JhK1h_5SNYcGY3GvJSEJ" alt="Máy lọc nước" class="w-full h-full object-cover" />
            </div>
            <span class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-[#0056b3] line-clamp-1">Máy lọc nước</span>
            <span class="text-[10px] text-slate-500 mt-0.5 hidden sm:inline">Karofi, Kangaroo, AOSmith</span>
          </button>

          <!-- 5. Quạt điều hòa -->
          <button type="button" data-filter="Quạt điều hòa" class="cat-filter-trigger group bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-[#0056b3] rounded-xl p-2.5 sm:p-3.5 flex flex-col items-center text-center transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg overflow-hidden mb-2 border border-slate-200 bg-white flex items-center justify-center">
              <img data-drive-id="14NwXK5WSxdXRHMei5AXKwed_w0YyEjSE" src="https://lh3.googleusercontent.com/d/14NwXK5WSxdXRHMei5AXKwed_w0YyEjSE" alt="Quạt điều hòa" class="w-full h-full object-cover" />
            </div>
            <span class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-[#0056b3] line-clamp-1">Quạt điều hòa</span>
            <span class="text-[10px] text-slate-500 mt-0.5 hidden sm:inline">Boss, Daikiosan, Sunhouse</span>
          </button>

          <!-- 6. Quạt hơi nước -->
          <button type="button" data-filter="Quạt hơi nước" class="cat-filter-trigger group bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-[#0056b3] rounded-xl p-2.5 sm:p-3.5 flex flex-col items-center text-center transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg overflow-hidden mb-2 border border-slate-200 bg-white flex items-center justify-center">
              <img data-drive-id="1HnrSBnlraFtuvNWtdreRQNd-1Lw3mkYY" src="https://lh3.googleusercontent.com/d/1HnrSBnlraFtuvNWtdreRQNd-1Lw3mkYY" alt="Quạt hơi nước" class="w-full h-full object-cover" />
            </div>
            <span class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-[#0056b3] line-clamp-1">Quạt hơi nước</span>
            <span class="text-[10px] text-slate-500 mt-0.5 hidden sm:inline">Làm mát nhanh, tiết kiệm</span>
          </button>

          <!-- 7. Máy nước nóng (Danh mục từ web mẫu dienmaykhanhtrung.com) -->
          <a href="#form-bao-gia" data-quote-cat="Máy nước nóng (Ariston, Ferroli, Rossi)" class="quote-cat-trigger group bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-[#0056b3] rounded-xl p-2.5 sm:p-3.5 flex flex-col items-center text-center transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg mb-2 border border-blue-100 bg-blue-50 text-[#0056b3] flex items-center justify-center text-xl">
              <i class="fa-solid fa-fire-flame-simple"></i>
            </div>
            <span class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-[#0056b3] line-clamp-1">Máy nước nóng</span>
            <span class="text-[10px] text-slate-500 mt-0.5 hidden sm:inline">Ariston, Rossi, Ferroli</span>
          </a>

          <!-- 8. Máy bơm nước -->
          <a href="#form-bao-gia" data-quote-cat="Máy bơm nước (Tăng áp, Đẩy cao, Bơm chìm)" class="quote-cat-trigger group bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-[#0056b3] rounded-xl p-2.5 sm:p-3.5 flex flex-col items-center text-center transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg mb-2 border border-blue-100 bg-blue-50 text-[#0056b3] flex items-center justify-center text-xl">
              <i class="fa-solid fa-faucet-drip"></i>
            </div>
            <span class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-[#0056b3] line-clamp-1">Máy bơm nước</span>
            <span class="text-[10px] text-slate-500 mt-0.5 hidden sm:inline">Bơm tăng áp, đẩy cao</span>
          </a>

          <!-- 9. Máy rửa xe -->
          <a href="#form-bao-gia" data-quote-cat="Máy rửa xe (Dekton, Bosch, Osaka)" class="quote-cat-trigger group bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-[#0056b3] rounded-xl p-2.5 sm:p-3.5 flex flex-col items-center text-center transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg mb-2 border border-blue-100 bg-blue-50 text-[#0056b3] flex items-center justify-center text-xl">
              <i class="fa-solid fa-spray-can-sparkles"></i>
            </div>
            <span class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-[#0056b3] line-clamp-1">Máy rửa xe</span>
            <span class="text-[10px] text-slate-500 mt-0.5 hidden sm:inline">Dekton, Bosch, Osaka</span>
          </a>

          <!-- 10. Máy khoan, đục, cắt, thổi PIN -->
          <a href="#form-bao-gia" data-quote-cat="Máy khoan, đục, cắt, thổi PIN (Hukan, Total)" class="quote-cat-trigger group bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-[#0056b3] rounded-xl p-2.5 sm:p-3.5 flex flex-col items-center text-center transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg mb-2 border border-blue-100 bg-blue-50 text-[#0056b3] flex items-center justify-center text-xl">
              <i class="fa-solid fa-screwdriver-wrench"></i>
            </div>
            <span class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-[#0056b3] line-clamp-1">Khoan, đục, cắt PIN</span>
            <span class="text-[10px] text-slate-500 mt-0.5 hidden sm:inline">Hukan, Total chính hãng</span>
          </a>

          <!-- 11. Máy phát điện -->
          <a href="#form-bao-gia" data-quote-cat="Máy phát điện (Chạy xăng, Chạy dầu, Honda, Hyundai)" class="quote-cat-trigger group bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-[#0056b3] rounded-xl p-2.5 sm:p-3.5 flex flex-col items-center text-center transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg mb-2 border border-blue-100 bg-blue-50 text-[#0056b3] flex items-center justify-center text-xl">
              <i class="fa-solid fa-bolt"></i>
            </div>
            <span class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-[#0056b3] line-clamp-1">Máy phát điện</span>
            <span class="text-[10px] text-slate-500 mt-0.5 hidden sm:inline">Chạy dầu, chạy xăng</span>
          </a>

          <!-- 12. Đèn NLMT -->
          <a href="#form-bao-gia" data-quote-cat="Đèn năng lượng mặt trời (Đèn pha, Đèn đường NLMT)" class="quote-cat-trigger group bg-slate-50 hover:bg-blue-50 border border-slate-200 hover:border-[#0056b3] rounded-xl p-2.5 sm:p-3.5 flex flex-col items-center text-center transition">
            <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-lg mb-2 border border-blue-100 bg-blue-50 text-[#0056b3] flex items-center justify-center text-xl">
              <i class="fa-solid fa-solar-panel"></i>
            </div>
            <span class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-[#0056b3] line-clamp-1">Đèn NLMT</span>
            <span class="text-[10px] text-slate-500 mt-0.5 hidden sm:inline">Đèn pha, đèn đường NLMT</span>
          </a>

        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       5. SẢN PHẨM THỰC TẾ TRANG CHỦ (12 ẢNH TỪ GOOGLE DRIVE)
          - Sản phẩm chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
          - Có % giảm giá góc trên bên trái giống Flatsome + Giá gốc gạch ngang & Giá giảm
          - Không để các nhãn dán rườm rà ở trang chủ
  ====================================================================== -->
  <section id="san-pham-trang-chu" class="py-3 sm:py-5 w-full">
    <div class="flatsome-container space-y-6">

      <!-- KHỐI TẤT CẢ SẢN PHẨM THỰC TẾ (12 SẢN PHẨM GOOGLE DRIVE) + BỘ LỌC NHANH -->
      <div class="bg-white rounded-xl p-3 sm:p-5 border border-slate-200 shadow-sm">
        <div class="section-title-container">
          <h2 class="section-title-main">
            <i class="fa-solid fa-star"></i>
            <span id="activeCategoryHeading">SẢN PHẨM NỔI BẬT</span>
          </h2>

          <!-- Nút lọc danh mục sản phẩm thực tế -->
          <div class="flex items-center gap-1.5 flex-wrap">
            <button type="button" data-filter="ALL" class="cat-filter-btn px-2.5 py-1.5 rounded text-xs font-semibold bg-[#0056b3] text-white transition">Tất cả (12)</button>
            <button type="button" data-filter="Điều hòa" class="cat-filter-btn px-2.5 py-1.5 rounded text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 transition">Điều hòa (5)</button>
            <button type="button" data-filter="Tủ lạnh" class="cat-filter-btn px-2.5 py-1.5 rounded text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 transition">Tủ lạnh (2)</button>
            <button type="button" data-filter="Máy giặt" class="cat-filter-btn px-2.5 py-1.5 rounded text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 transition">Máy giặt (2)</button>
            <button type="button" data-filter="Máy lọc nước" class="cat-filter-btn px-2.5 py-1.5 rounded text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 transition">Máy lọc nước (1)</button>
            <button type="button" data-filter="Quạt điều hòa" class="cat-filter-btn px-2.5 py-1.5 rounded text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 transition">Quạt điều hòa (1)</button>
            <button type="button" data-filter="Quạt hơi nước" class="cat-filter-btn px-2.5 py-1.5 rounded text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 transition">Quạt hơi nước (1)</button>
          </div>
        </div>

        <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 3 cột trên tablet, 4 cột trên máy tính -->
        <div id="mainProductGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
          <!-- Được render tự động từ danh sách 12 ảnh thực tế Google Drive bên dưới -->
        </div>
      </div>

      <!-- CHuyên mục riêng 1: ĐIỀU HÒA CHÍNH HÃNG (5 Ảnh thực tế từ Google Drive) -->
      <div class="bg-white rounded-xl p-3 sm:p-5 border border-slate-200 shadow-sm">
        <div class="section-title-container">
          <h2 class="section-title-main">
            <i class="fa-solid fa-snowflake"></i>
            <span>ĐIỀU HÒA - MÁY LẠNH</span>
          </h2>
          <div class="hidden sm:flex items-center gap-2 text-xs text-slate-600 font-medium">
            <span>Daikin</span> • <span>Panasonic</span> • <span>Casper</span> • <span>LG</span> • <span>Reetech</span>
          </div>
        </div>
        <div id="acProductGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-3.5"></div>
      </div>

      <!-- Chuyên mục riêng 2: TỦ LẠNH & MÁY GIẶT (4 Ảnh thực tế từ Google Drive) -->
      <div class="bg-white rounded-xl p-3 sm:p-5 border border-slate-200 shadow-sm">
        <div class="section-title-container">
          <h2 class="section-title-main">
            <i class="fa-solid fa-kitchen-set"></i>
            <span>TỦ LẠNH & MÁY GIẶT</span>
          </h2>
          <div class="hidden sm:flex items-center gap-2 text-xs text-slate-600 font-medium">
            <span>Panasonic</span> • <span>Toshiba</span> • <span>Aqua</span> • <span>Electrolux</span> • <span>Hitachi</span>
          </div>
        </div>
        <div id="fridgeWasherGrid" class="grid grid-cols-2 md:grid-cols-4 gap-2.5 sm:gap-4"></div>
      </div>

      <!-- Chuyên mục riêng 3: MÁY LỌC NƯỚC, QUẠT ĐIỀU HÒA, QUẠT HƠI NƯỚC (3 Ảnh thực tế từ Google Drive) -->
      <div class="bg-white rounded-xl p-3 sm:p-5 border border-slate-200 shadow-sm">
        <div class="section-title-container">
          <h2 class="section-title-main">
            <i class="fa-solid fa-fan"></i>
            <span>MÁY LỌC NƯỚC & QUẠT LÀM MÁT</span>
          </h2>
          <div class="hidden sm:flex items-center gap-2 text-xs text-slate-600 font-medium">
            <span>Máy lọc nước</span> • <span>Quạt điều hòa</span> • <span>Quạt hơi nước</span>
          </div>
        </div>
        <div id="waterFanGrid" class="grid grid-cols-2 md:grid-cols-3 gap-2.5 sm:gap-4"></div>
      </div>

    </div>
  </section>

  <!-- =====================================================================
       6. FORM YÊU CẦU TƯ VẤN & BÁO GIÁ NHANH NGOÀI TRANG CHỦ
  ====================================================================== -->
  <section id="form-bao-gia" class="py-3 sm:py-5 w-full">
    <div class="flatsome-container">
      <div class="bg-white rounded-xl p-4 sm:p-6 border border-slate-200 shadow-sm">
        
        <div class="section-title-container">
          <h2 class="section-title-main">
            <i class="fa-solid fa-file-invoice-dollar"></i>
            <span>YÊU CẦU TƯ VẤN & BÁO GIÁ NHANH</span>
          </h2>
          <span class="text-xs text-slate-500">Hỗ trợ tư vấn kỹ thuật & báo giá sỉ/lẻ tận nơi tại Đà Nẵng</span>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-start">
          
          <!-- Cột thông tin cam kết của Công ty TNHH Cơ Điện Hoàng Anh -->
          <div class="lg:col-span-5 bg-slate-50 rounded-xl p-4 sm:p-5 border border-slate-200 space-y-3.5">
            <h3 class="text-base sm:text-lg font-extrabold text-[#0056b3]">
              CÔNG TY TNHH CƠ ĐIỆN HOÀNG ANH
            </h3>
            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
              Chuyên phân phối, thi công lắp đặt, bảo trì sửa chữa hệ thống <strong>Điều hòa, Tủ lạnh, Máy giặt, Máy lọc nước, Quạt hơi nước, Quạt điều hòa</strong> và thiết bị cơ điện dân dụng - công nghiệp tại TP. Đà Nẵng.
            </p>
            <div class="space-y-2 text-xs sm:text-sm text-slate-700 pt-1">
              <div class="flex items-start gap-2.5">
                <i class="fa-solid fa-location-dot text-[#d0011b] mt-1 shrink-0"></i>
                <span><strong>Cơ sở 1:</strong> 21 Bàu Trảng 6, Phường Thanh Khê, TP Đà Nẵng</span>
              </div>
              <div class="flex items-start gap-2.5">
                <i class="fa-solid fa-location-dot text-[#d0011b] mt-1 shrink-0"></i>
                <span><strong>Cơ sở 2:</strong> 72 Võ Văn Tần, Phường Thanh Khê, TP Đà Nẵng</span>
              </div>
              <div class="flex items-center gap-2.5">
                <i class="fa-solid fa-phone-volume text-[#0056b3] shrink-0"></i>
                <span><strong>Hotline:</strong> <a href="tel:0919734343" class="text-[#d0011b] font-bold hover:underline">0919.734.343</a> - <a href="tel:0905110299" class="text-[#d0011b] font-bold hover:underline">0905.110.299</a></span>
              </div>
              <div class="flex items-center gap-2.5">
                <i class="fa-solid fa-globe text-[#0056b3] shrink-0"></i>
                <span><strong>Website:</strong> codienhoanganh.com</span>
              </div>
            </div>
          </div>

          <!-- Cột Form Gửi Yêu Cầu Báo Giá -->
          <form id="quoteRequestForm" class="lg:col-span-7 grid grid-cols-1 sm:grid-cols-2 gap-3.5">
            <div>
              <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên quý khách *</label>
              <input id="quoteName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-[#0056b3]" />
            </div>
            <div>
              <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
              <input id="quotePhone" type="tel" required placeholder="Ví dụ: 0919734343" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-[#0056b3]" />
            </div>
            <div>
              <label class="block text-xs font-bold text-slate-700 mb-1">Sản phẩm / Dịch vụ cần báo giá *</label>
              <select id="quoteProduct" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-[#0056b3] bg-white">
                <option value="Điều hòa">Điều hòa (Tư vấn mua mới & Lắp đặt)</option>
                <option value="Tủ lạnh">Tủ lạnh</option>
                <option value="Máy giặt">Máy giặt</option>
                <option value="Máy lọc nước">Máy lọc nước</option>
                <option value="Quạt điều hòa">Quạt điều hòa</option>
                <option value="Quạt hơi nước">Quạt hơi nước</option>
                <option value="Máy nước nóng / Máy bơm nước">Máy nước nóng / Máy bơm nước</option>
                <option value="Máy rửa xe / Máy phát điện / Đèn NLMT">Máy rửa xe / Máy phát điện / Đèn NLMT</option>
                <option value="Thi công - Bảo trì Cơ Điện">Thi công - Bảo trì hệ thống Cơ Điện</option>
              </select>
            </div>
            <div>
              <label class="block text-xs font-bold text-slate-700 mb-1">Địa chỉ nhận hàng / Lắp đặt</label>
              <input id="quoteAddress" type="text" placeholder="Quận/Phường tại TP. Đà Nẵng..." class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-[#0056b3]" />
            </div>
            <div class="sm:col-span-2">
              <label class="block text-xs font-bold text-slate-700 mb-1">Ghi chú yêu cầu chi tiết</label>
              <textarea id="quoteNote" rows="3" placeholder="Nhập công suất máy, số lượng, hoặc yêu cầu khảo sát tận nơi..." class="w-full px-3.5 py-2 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-[#0056b3]"></textarea>
            </div>
            <div class="sm:col-span-2 flex flex-wrap items-center justify-between gap-3 pt-1">
              <button type="submit" class="w-full sm:w-auto px-6 py-3 bg-[#d0011b] hover:bg-red-700 text-white font-bold text-sm rounded-lg shadow transition flex items-center justify-center gap-2">
                <i class="fa-solid fa-paper-plane"></i>
                <span>GỬI YÊU CẦU BÁO GIÁ NGAY</span>
              </button>
              <span class="text-xs text-slate-500">Hoặc liên hệ trực tiếp: <strong class="text-[#0056b3]">0919.734.343 - 0905.110.299</strong></span>
            </div>
          </form>

        </div>

        <!-- Thông báo xác nhận gửi báo giá thành công -->
        <div id="quoteSuccessBox" class="hidden mt-4 p-4 rounded-lg bg-green-50 border border-green-300 text-green-800 text-xs sm:text-sm"></div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       7. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM CƠ ĐIỆN)
          Sử dụng ảnh thực tế từ Google Drive để không lấy ảnh trên mạng
  ====================================================================== -->
  <section id="bai-viet-trang-chu" class="py-3 sm:py-5 w-full">
    <div class="flatsome-container">
      <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm">
        
        <div class="section-title-container">
          <h2 class="section-title-main">
            <i class="fa-solid fa-newspaper"></i>
            <span>DANH MỤC BÀI VIẾT & TIN TỨC</span>
          </h2>
          <span class="text-xs text-slate-500">Tư vấn chọn mua, lắp đặt & sử dụng thiết bị điện máy bền bỉ</span>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
          
          <!-- Bài viết 1 -->
          <article class="border border-slate-200 rounded-xl overflow-hidden flex flex-col bg-white hover:shadow-md transition">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
              <img data-drive-id="1BYKtCoakrMFo9GBfFhrOx6iT4cbYIqR9" src="https://lh3.googleusercontent.com/d/1BYKtCoakrMFo9GBfFhrOx6iT4cbYIqR9" alt="Kinh nghiệm chọn mua và lắp đặt điều hòa tiết kiệm điện tại Đà Nẵng" class="w-full h-full object-cover" />
            </div>
            <div class="p-3.5 flex flex-col flex-1">
              <div class="text-[11px] text-[#0056b3] font-semibold mb-1">Tư vấn Điều hòa • Cơ Điện Hoàng Anh</div>
              <h3 class="text-sm font-bold text-slate-800 mb-2 line-clamp-2">
                Kinh nghiệm chọn mua và lắp đặt Điều hòa Inverter tiết kiệm điện cho mùa nắng nóng Đà Nẵng
              </h3>
              <p class="text-xs text-slate-600 line-clamp-3 mb-3 flex-1">
                Hướng dẫn cách tính công suất điều hòa 1HP, 1.5HP, 2HP phù hợp diện tích phòng và quy trình lắp đặt chuẩn kỹ thuật tại Cơ Điện Hoàng Anh.
              </p>
              <a href="#form-bao-gia" class="text-xs font-bold text-[#0056b3] hover:underline inline-flex items-center gap-1">
                <span>Nhận tư vấn chi tiết</span>
                <i class="fa-solid fa-arrow-right text-[10px]"></i>
              </a>
            </div>
          </article>

          <!-- Bài viết 2 -->
          <article class="border border-slate-200 rounded-xl overflow-hidden flex flex-col bg-white hover:shadow-md transition">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
              <img data-drive-id="1GPmyaAk4AMu-JhK1h_5SNYcGY3GvJSEJ" src="https://lh3.googleusercontent.com/d/1GPmyaAk4AMu-JhK1h_5SNYcGY3GvJSEJ" alt="Lợi ích khi sử dụng máy lọc nước RO chính hãng cho gia đình" class="w-full h-full object-cover" />
            </div>
            <div class="p-3.5 flex flex-col flex-1">
              <div class="text-[11px] text-[#0056b3] font-semibold mb-1">Máy lọc nước • Sức khỏe gia đình</div>
              <h3 class="text-sm font-bold text-slate-800 mb-2 line-clamp-2">
                Tư vấn chọn Máy lọc nước RO đa lõi lọc và lịch thay lõi lọc nước định kỳ tại nhà
              </h3>
              <p class="text-xs text-slate-600 line-clamp-3 mb-3 flex-1">
                Máy lọc nước cung cấp nguồn nước tinh khiết bổ sung khoáng chất có lợi. Cơ Điện Hoàng Anh hỗ trợ giao lắp và thay lõi tận nơi tại Thanh Khê, Đà Nẵng.
              </p>
              <a href="#form-bao-gia" class="text-xs font-bold text-[#0056b3] hover:underline inline-flex items-center gap-1">
                <span>Nhận tư vấn chi tiết</span>
                <i class="fa-solid fa-arrow-right text-[10px]"></i>
              </a>
            </div>
          </article>

          <!-- Bài viết 3 -->
          <article class="border border-slate-200 rounded-xl overflow-hidden flex flex-col bg-white hover:shadow-md transition">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
              <img data-drive-id="1Fv8RldPmcSB2iVnidiFaz2rB9X3kmek8" src="https://lh3.googleusercontent.com/d/1Fv8RldPmcSB2iVnidiFaz2rB9X3kmek8" alt="Cách sử dụng tủ lạnh và máy giặt bền đẹp tiết kiệm điện" class="w-full h-full object-cover" />
            </div>
            <div class="p-3.5 flex flex-col flex-1">
              <div class="text-[11px] text-[#0056b3] font-semibold mb-1">Tủ lạnh & Máy giặt • Điện máy gia dụng</div>
              <h3 class="text-sm font-bold text-slate-800 mb-2 line-clamp-2">
                Bí quyết chọn Tủ lạnh và Máy giặt Inverter vận hành êm ái, bền bỉ theo thời gian
              </h3>
              <p class="text-xs text-slate-600 line-clamp-3 mb-3 flex-1">
                Tổng hợp các mẫu tủ lạnh và máy giặt tiết kiệm điện được ưa chuộng nhất tại Đà Nẵng, bảo hành chính hãng và giao lắp miễn phí trong ngày.
              </p>
              <a href="#form-bao-gia" class="text-xs font-bold text-[#0056b3] hover:underline inline-flex items-center gap-1">
                <span>Nhận tư vấn chi tiết</span>
                <i class="fa-solid fa-arrow-right text-[10px]"></i>
              </a>
            </div>
          </article>

          <!-- Bài viết 4 -->
          <article class="border border-slate-200 rounded-xl overflow-hidden flex flex-col bg-white hover:shadow-md transition">
            <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
              <img data-drive-id="14NwXK5WSxdXRHMei5AXKwed_w0YyEjSE" src="https://lh3.googleusercontent.com/d/14NwXK5WSxdXRHMei5AXKwed_w0YyEjSE" alt="So sánh quạt điều hòa và quạt hơi nước cho không gian mở" class="w-full h-full object-cover" />
            </div>
            <div class="p-3.5 flex flex-col flex-1">
              <div class="text-[11px] text-[#0056b3] font-semibold mb-1">Giải pháp làm mát • Quạt hơi nước</div>
              <h3 class="text-sm font-bold text-slate-800 mb-2 line-clamp-2">
                Giải pháp làm mát hiệu quả cho phòng khách, quán ăn với Quạt điều hòa & Quạt hơi nước
              </h3>
              <p class="text-xs text-slate-600 line-clamp-3 mb-3 flex-1">
                Đối với không gian mở, quạt điều hòa và quạt hơi nước giúp hạ nhiệt nhanh, lưu thông không khí thoáng mát và cực kỳ tiết kiệm chi phí điện năng.
              </p>
              <a href="#form-bao-gia" class="text-xs font-bold text-[#0056b3] hover:underline inline-flex items-center gap-1">
                <span>Nhận tư vấn chi tiết</span>
                <i class="fa-solid fa-arrow-right text-[10px]"></i>
              </a>
            </div>
          </article>

        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       8. BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK NGOÀI TRANG CHỦ
          - Đưa ảnh/bản đồ Google Map ra ngoài trang chủ (kèm link https://maps.app.goo.gl/SaiefiJxR56pDjx36)
          - Đưa Fanpage Facebook ra ngoài trang chủ (https://www.facebook.com/profile.php?id=100063775803022&locale=vi_VN)
  ====================================================================== -->
  <section id="ban-do-fanpage" class="py-3 sm:py-5 w-full">
    <div class="flatsome-container">
      <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm">
        
        <div class="section-title-container">
          <h2 class="section-title-main">
            <i class="fa-solid fa-map-location-dot"></i>
            <span>BẢN ĐỒ GOOGLE MAP & FANPAGE TRANG CHỦ</span>
          </h2>
          <span class="text-xs text-slate-500">CS1: 21 Bàu Trảng 6, Thanh Khê, Đà Nẵng • CS2: 72 Võ Văn Tần, Thanh Khê, Đà Nẵng</span>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
          
          <!-- Cột Trái (7/12): Bản đồ Google Map trực quan ngoài trang chủ -->
          <div class="lg:col-span-7 flex flex-col border border-slate-200 rounded-xl overflow-hidden bg-slate-50">
            <div class="p-3 bg-slate-100 border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
              <div class="text-xs sm:text-sm font-bold text-[#0056b3] flex items-center gap-1.5">
                <i class="fa-solid fa-location-dot text-[#d0011b]"></i>
                <span>Vị Trí Cửa Hàng Trên Google Maps</span>
              </div>
              <div class="flex items-center gap-1.5">
                <button type="button" id="mapCs1Btn" class="px-2.5 py-1 rounded text-xs font-bold bg-[#0056b3] text-white">CS1: 21 Bàu Trảng 6</button>
                <button type="button" id="mapCs2Btn" class="px-2.5 py-1 rounded text-xs font-bold bg-white text-slate-700 border border-slate-300 hover:bg-blue-50">CS2: 72 Võ Văn Tần</button>
              </div>
            </div>

            <!-- Khung Google Map Iframe hiển thị ngay ngoài trang chủ -->
            <div class="relative w-full h-64 sm:h-72 bg-slate-200">
              <iframe 
                id="googleMapIframe"
                title="Bản đồ Công Ty TNHH Cơ Điện Hoàng Anh"
                src="https://maps.google.com/maps?q=21%20B%C3%A0u%20Tr%E1%BA%A3ng%206,%20Thanh%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                class="w-full h-full border-0"
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>

            <!-- Thanh địa chỉ & Nút mở Google Map gốc https://maps.app.goo.gl/SaiefiJxR56pDjx36 -->
            <div class="p-3.5 bg-white flex flex-col sm:flex-row sm:items-center justify-between gap-3 border-t border-slate-200">
              <div class="text-xs text-slate-700 space-y-1">
                <div><strong>CS1:</strong> 21 Bàu Trảng 6, Phường Thanh Khê, TP Đà Nẵng</div>
                <div><strong>CS2:</strong> 72 Võ Văn Tần, Phường Thanh Khê, TP Đà Nẵng</div>
              </div>
              <a 
                href="https://maps.app.goo.gl/SaiefiJxR56pDjx36" 
                target="_blank" 
                rel="noopener noreferrer" 
                class="shrink-0 inline-flex items-center justify-center gap-2 px-4 py-2.5 rounded-lg bg-[#0056b3] hover:bg-blue-700 text-white text-xs font-bold shadow-sm transition"
              >
                <i class="fa-solid fa-diamond-turn-right"></i>
                <span>Mở Bản Đồ Chỉ Đường</span>
              </a>
            </div>
          </div>

          <!-- Cột Phải (5/12): Fanpage Facebook chính thức ngoài trang chủ -->
          <div class="lg:col-span-5 flex flex-col border border-slate-200 rounded-xl overflow-hidden bg-slate-50">
            <div class="p-3 bg-[#1877F2] text-white flex items-center justify-between">
              <div class="text-xs sm:text-sm font-bold flex items-center gap-2">
                <i class="fa-brands fa-facebook text-base"></i>
                <span>Fanpage Chính Thức</span>
              </div>
              <a 
                href="https://www.facebook.com/profile.php?id=100063775803022&locale=vi_VN" 
                target="_blank" 
                rel="noopener noreferrer"
                class="text-[11px] bg-white text-[#1877F2] font-bold px-2.5 py-1 rounded hover:bg-blue-50"
              >
                Theo dõi trang
              </a>
            </div>

            <div class="p-4 flex-1 flex flex-col justify-between bg-white space-y-3">
              <!-- Thẻ nhận diện Fanpage dùng ảnh thực tế từ Google Drive -->
              <div class="flex items-center gap-3 p-3 rounded-lg bg-slate-50 border border-slate-200">
                <img 
                  data-drive-id="1J9yw5Hk0ISJaFicapDKe6F5MHW3E9TX-" 
                  src="https://lh3.googleusercontent.com/d/1J9yw5Hk0ISJaFicapDKe6F5MHW3E9TX-" 
                  alt="Fanpage Công Ty TNHH Cơ Điện Hoàng Anh" 
                  class="w-14 h-14 rounded-lg object-cover border border-blue-200 shrink-0"
                />
                <div class="min-w-0">
                  <a 
                    href="https://www.facebook.com/profile.php?id=100063775803022&locale=vi_VN" 
                    target="_blank" 
                    rel="noopener noreferrer"
                    class="text-sm font-extrabold text-[#1877F2] hover:underline block truncate"
                  >
                    CÔNG TY TNHH CƠ ĐIỆN HOÀNG ANH
                  </a>
                  <p class="text-xs text-slate-500">Điện máy - Cơ điện chính hãng Đà Nẵng</p>
                  <p class="text-[11px] text-slate-600 font-semibold mt-0.5">ĐT: 0919.734.343 - 0905.110.299</p>
                </div>
              </div>

              <!-- Facebook Page Embed Plugin + Hình ảnh hoạt động thực tế -->
              <div class="w-full overflow-hidden rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center">
                <iframe 
                  title="Fanpage Facebook Cơ Điện Hoàng Anh"
                  src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100063775803022&tabs=timeline&width=340&height=200&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                  width="340" 
                  height="200" 
                  style="border:none;overflow:hidden;max-width:100%;" 
                  scrolling="no" 
                  frameborder="0" 
                  allowfullscreen="true" 
                  allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
                ></iframe>
              </div>

              <a 
                href="https://www.facebook.com/profile.php?id=100063775803022&locale=vi_VN" 
                target="_blank" 
                rel="noopener noreferrer" 
                class="w-full py-2.5 px-4 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs flex items-center justify-center gap-2 shadow-sm transition"
              >
                <i class="fa-brands fa-facebook-messenger text-sm"></i>
                <span>Truy Cập & Nhắn Tin Qua Fanpage Facebook</span>
              </a>
            </div>
          </div>

        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       9. FOOTER CHUẨN FLATSOME (Đầy đủ thông tin CS1, CS2, SĐT, Danh mục, Chính sách)
  ====================================================================== -->
  <footer class="bg-[#0b2239] text-slate-200 pt-8 pb-20 md:pb-8 mt-4 w-full border-t-4 border-[#0056b3]">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-slate-700/70">
        
        <!-- Cột 1: Thông tin công ty -->
        <div class="space-y-2.5 text-xs">
          <h3 class="text-sm font-extrabold text-white uppercase tracking-wide">
            CÔNG TY TNHH CƠ ĐIỆN HOÀNG ANH
          </h3>
          <p class="text-slate-300 leading-relaxed">
            Chuyên phân phối, lắp đặt & bảo hành Điều hòa, Tủ lạnh, Máy giặt, Máy lọc nước, Quạt điều hòa, Quạt hơi nước, Máy bơm nước, Máy nước nóng chính hãng tại TP. Đà Nẵng.
          </p>
          <div class="space-y-1.5 pt-1 text-slate-200">
            <div><strong class="text-yellow-400">Website:</strong> codienhoanganh.com</div>
            <div><strong class="text-yellow-400">CS1:</strong> 21 Bàu Trảng 6, Phường Thanh Khê, TP Đà Nẵng</div>
            <div><strong class="text-yellow-400">CS2:</strong> 72 Võ Văn Tần, Phường Thanh Khê, TP Đà Nẵng</div>
            <div><strong class="text-yellow-400">Hotline:</strong> 0919.734.343 - 0905110299</div>
          </div>
        </div>

        <!-- Cột 2: Danh mục sản phẩm -->
        <div class="space-y-2 text-xs">
          <h3 class="text-sm font-extrabold text-white uppercase tracking-wide">
            DANH MỤC SẢN PHẨM
          </h3>
          <ul class="space-y-1.5 text-slate-300">
            <li><a href="#san-pham-trang-chu" data-filter="Điều hòa" class="cat-filter-trigger hover:text-yellow-400">• Điều hòa (Daikin, Panasonic, LG, Casper...)</a></li>
            <li><a href="#san-pham-trang-chu" data-filter="Tủ lạnh" class="cat-filter-trigger hover:text-yellow-400">• Tủ lạnh (Panasonic, Hitachi, Aqua, Toshiba...)</a></li>
            <li><a href="#san-pham-trang-chu" data-filter="Máy giặt" class="cat-filter-trigger hover:text-yellow-400">• Máy giặt (Electrolux, Toshiba, Aqua...)</a></li>
            <li><a href="#san-pham-trang-chu" data-filter="Máy lọc nước" class="cat-filter-trigger hover:text-yellow-400">• Máy lọc nước (Karofi, Kangaroo, AOSmith)</a></li>
            <li><a href="#san-pham-trang-chu" data-filter="Quạt điều hòa" class="cat-filter-trigger hover:text-yellow-400">• Quạt điều hòa & Quạt hơi nước</a></li>
            <li><a href="#danh-muc-mau" class="hover:text-yellow-400">• Máy nước nóng, Máy bơm nước, Máy rửa xe</a></li>
            <li><a href="#danh-muc-mau" class="hover:text-yellow-400">• Máy phát điện, Khoan cắt PIN, Đèn NLMT</a></li>
          </ul>
        </div>

        <!-- Cột 3: Chính sách & Hỗ trợ (Chuẩn web mẫu dienmaykhanhtrung.com) -->
        <div class="space-y-2 text-xs">
          <h3 class="text-sm font-extrabold text-white uppercase tracking-wide">
            CHÍNH SÁCH KHÁCH HÀNG
          </h3>
          <ul class="space-y-1.5 text-slate-300">
            <li><a href="#form-bao-gia" class="hover:text-yellow-400">• Chính sách bảo hành chính hãng</a></li>
            <li><a href="#form-bao-gia" class="hover:text-yellow-400">• Chính sách vận chuyển & lắp đặt tận nơi</a></li>
            <li><a href="#form-bao-gia" class="hover:text-yellow-400">• Chính sách kiểm hàng & đổi trả</a></li>
            <li><a href="#form-bao-gia" class="hover:text-yellow-400">• Phương thức thanh toán linh hoạt</a></li>
            <li><a href="#form-bao-gia" class="hover:text-yellow-400">• Tư vấn kỹ thuật: 0919.734.343 - 0905.110.299</a></li>
          </ul>
        </div>

        <!-- Cột 4: Kết nối Bản đồ & Fanpage -->
        <div class="space-y-2.5 text-xs">
          <h3 class="text-sm font-extrabold text-white uppercase tracking-wide">
            KẾT NỐI VỚI CHÚNG TÔI
          </h3>
          <p class="text-slate-300">Theo dõi Fanpage hoặc xem chỉ đường trực tiếp đến 2 cơ sở tại Quận Thanh Khê, TP Đà Nẵng:</p>
          <div class="flex flex-col gap-2 pt-1">
            <a href="https://www.facebook.com/profile.php?id=100063775803022&locale=vi_VN" target="_blank" rel="noopener noreferrer" class="px-3 py-2 rounded-lg bg-[#1877F2] text-white font-bold flex items-center gap-2 hover:bg-blue-600 transition">
              <i class="fa-brands fa-facebook"></i>
              <span>Fanpage Cơ Điện Hoàng Anh</span>
            </a>
            <a href="https://maps.app.goo.gl/SaiefiJxR56pDjx36" target="_blank" rel="noopener noreferrer" class="px-3 py-2 rounded-lg bg-emerald-600 text-white font-bold flex items-center gap-2 hover:bg-emerald-500 transition">
              <i class="fa-solid fa-map-location-dot"></i>
              <span>Bản Đồ Google Maps</span>
            </a>
          </div>
        </div>

      </div>

      <div class="pt-4 text-center text-xs text-slate-400">
        Copyright © 2026 <strong class="text-white">CÔNG TY TNHH CƠ ĐIỆN HOÀNG ANH (codienhoanganh.com)</strong>. All rights reserved.
      </div>
    </div>
  </footer>

  <!-- =====================================================================
       10. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
           Đặt gọn gàng bên phải màn hình, không gây tràn viền
  ====================================================================== -->
  <div class="fixed right-3 bottom-4 z-40 flex flex-col items-end gap-2.5">
    
    <!-- Nút Facebook Fanpage -->
    <a 
      href="https://www.facebook.com/profile.php?id=100063775803022&locale=vi_VN" 
      target="_blank" 
      rel="noopener noreferrer"
      title="Chat Facebook Fanpage"
      class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg transition"
    >
      <i class="fa-brands fa-facebook-f text-sm w-4 text-center"></i>
      <span class="text-xs font-bold">Facebook</span>
    </a>

    <!-- Nút Chat Zalo -->
    <a 
      href="https://zalo.me/0919734343" 
      target="_blank" 
      rel="noopener noreferrer"
      title="Chat Zalo 0919.734.343"
      class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg transition"
    >
      <span class="font-extrabold text-[11px] bg-white text-[#0068ff] px-1.5 py-0.5 rounded-full leading-none">Zalo</span>
      <span class="text-xs font-bold">0919.734.343</span>
    </a>

    <!-- Nút Hotline 1 -->
    <a 
      href="tel:0919734343" 
      title="Gọi Hotline 0919.734.343"
      class="floating-btn-pulse flex items-center gap-2 bg-[#d0011b] hover:bg-red-700 text-white pl-3 pr-3.5 py-2.5 rounded-full shadow-lg transition"
    >
      <i class="fa-solid fa-phone-volume text-xs"></i>
      <span class="text-xs font-extrabold">0919.734.343</span>
    </a>

    <!-- Nút Hotline 2 -->
    <a 
      href="tel:0905110299" 
      title="Gọi Hotline 0905.110.299"
      class="flex items-center gap-2 bg-[#0056b3] hover:bg-blue-800 text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg transition"
    >
      <i class="fa-solid fa-phone text-xs"></i>
      <span class="text-xs font-extrabold">0905.110.299</span>
    </a>

  </div>

  <!-- =====================================================================
       MODAL XEM NHANH / ĐẶT MUA SẢN PHẨM CHUẨN FLATSOME (Không dùng alert)
  ====================================================================== -->
  <div id="quickViewModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 bg-black/60">
    <div class="bg-white rounded-xl max-w-lg w-full overflow-hidden shadow-2xl border border-slate-200">
      <div class="p-3.5 bg-[#0056b3] text-white flex items-center justify-between">
        <h3 id="modalTitle" class="font-bold text-sm uppercase">Chi tiết sản phẩm</h3>
        <button id="closeModalBtn" type="button" class="w-7 h-7 rounded-full bg-white/15 flex items-center justify-center text-white">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-4 space-y-3">
        <div class="aspect-[4/3] w-full rounded-lg overflow-hidden bg-slate-100 border border-slate-200 relative">
          <span id="modalDiscountBadge" class="flatsome-Discount-badge">-18%</span>
          <img id="modalImage" src="" alt="Sản phẩm" class="w-full h-full object-contain bg-white" />
        </div>
        <div>
          <div id="modalCategory" class="text-xs text-[#0056b3] font-semibold">Danh mục</div>
          <h4 id="modalProductName" class="text-base font-extrabold text-slate-800 mt-0.5">Tên sản phẩm</h4>
          <div class="flex items-baseline gap-2.5 mt-1">
            <del id="modalOldPrice" class="text-xs text-slate-400">8.500.000 ₫</del>
            <span id="modalNewPrice" class="text-base font-extrabold text-[#d0011b]">6.950.000 ₫</span>
          </div>
        </div>
        <p class="text-xs text-slate-600 leading-relaxed">
          Sản phẩm thực tế tại <strong>CÔNG TY TNHH CƠ ĐIỆN HOÀNG ANH (codienhoanganh.com)</strong>. Hỗ trợ giao hàng và lắp đặt tận nơi tại TP. Đà Nẵng.
        </p>
        <div class="grid grid-cols-2 gap-2.5 pt-2">
          <a href="tel:0919734343" class="py-2.5 px-3 rounded-lg bg-[#d0011b] text-white font-bold text-xs text-center hover:bg-red-700 transition">
            <i class="fa-solid fa-phone mr-1"></i> 0919.734.343
          </a>
          <button id="modalJumpQuoteBtn" type="button" class="py-2.5 px-3 rounded-lg bg-[#0056b3] text-white font-bold text-xs text-center hover:bg-blue-700 transition">
            <i class="fa-solid fa-file-signature mr-1"></i> Yêu Cầu Báo Giá
          </button>
        </div>
      </div>
    </div>
  </div>

  <!-- =====================================================================
       JAVASCRIPT: DỮ LIỆU 12 ẢNH SẢN PHẨM THỰC TẾ TỪ GOOGLE DRIVE & TƯƠNG TÁC
  ====================================================================== -->
  <script>
    // Danh sách 12 sản phẩm thực tế lấy trực tiếp từ 12 link Google Drive người dùng cung cấp
    const DRIVE_PRODUCTS = [
      {
        id: 1,
        driveId: '1A902QNFp66OOtgFtKw2HldmYz7IBJiIT',
        name: 'Điều hòa',
        category: 'Điều hòa',
        oldPrice: '8.500.000 ₫',
        newPrice: '6.990.000 ₫',
        discount: '-18%'
      },
      {
        id: 2,
        driveId: '1GPmyaAk4AMu-JhK1h_5SNYcGY3GvJSEJ',
        name: 'Máy lọc nước',
        category: 'Máy lọc nước',
        oldPrice: '5.400.000 ₫',
        newPrice: '4.350.000 ₫',
        discount: '-19%'
      },
      {
        id: 3,
        driveId: '1BYKtCoakrMFo9GBfFhrOx6iT4cbYIqR9',
        name: 'Điều hòa',
        category: 'Điều hòa',
        oldPrice: '9.200.000 ₫',
        newPrice: '7.650.000 ₫',
        discount: '-17%'
      },
      {
        id: 4,
        driveId: '1HnrSBnlraFtuvNWtdreRQNd-1Lw3mkYY',
        name: 'Quạt hơi nước',
        category: 'Quạt hơi nước',
        oldPrice: '3.500.000 ₫',
        newPrice: '2.790.000 ₫',
        discount: '-20%'
      },
      {
        id: 5,
        driveId: '1IjwWxsAbYYklYHhSBAdD_0Em9IDHnULk',
        name: 'Điều hòa',
        category: 'Điều hòa',
        oldPrice: '10.800.000 ₫',
        newPrice: '8.950.000 ₫',
        discount: '-17%'
      },
      {
        id: 6,
        driveId: '1Fv8RldPmcSB2iVnidiFaz2rB9X3kmek8',
        name: 'Tủ lạnh',
        category: 'Tủ lạnh',
        oldPrice: '9.500.000 ₫',
        newPrice: '7.890.000 ₫',
        discount: '-17%'
      },
      {
        id: 7,
        driveId: '1Dgw-ptOX0LloSmy-WwnDF8c0haRyA64M',
        name: 'Tủ lạnh',
        category: 'Tủ lạnh',
        oldPrice: '11.900.000 ₫',
        newPrice: '9.650.000 ₫',
        discount: '-19%'
      },
      {
        id: 8,
        driveId: '14NwXK5WSxdXRHMei5AXKwed_w0YyEjSE',
        name: 'Quạt điều hòa',
        category: 'Quạt điều hòa',
        oldPrice: '4.200.000 ₫',
        newPrice: '3.350.000 ₫',
        discount: '-20%'
      },
      {
        id: 9,
        driveId: '1cJ1fi31VTHWi_xA-sE5WWXuhvKs_bl1g',
        name: 'Điều hòa',
        category: 'Điều hòa',
        oldPrice: '7.900.000 ₫',
        newPrice: '6.450.000 ₫',
        discount: '-18%'
      },
      {
        id: 10,
        driveId: '1moZc5jLhbim4jcw3v9zzV28yHnpSOemw',
        name: 'Máy giặt',
        category: 'Máy giặt',
        oldPrice: '7.800.000 ₫',
        newPrice: '6.250.000 ₫',
        discount: '-20%'
      },
      {
        id: 11,
        driveId: '1MnE6Smg4uzp1qw3OMZM8xJyrWDLUSXWA',
        name: 'Máy giặt',
        category: 'Máy giặt',
        oldPrice: '8.900.000 ₫',
        newPrice: '7.350.000 ₫',
        discount: '-17%'
      },
      {
        id: 12,
        driveId: '15B12LKeJ8vXZE7psEz0zpiSnFnunyxfK',
        name: 'Điều hòa',
        category: 'Điều hòa',
        oldPrice: '12.500.000 ₫',
        newPrice: '10.200.000 ₫',
        discount: '-18%'
      }
    ];

    // Hàm tạo URL ảnh Google Drive kèm cơ chế tự động chuyển đổi dự phòng nếu trình duyệt chặn
    function getDrivePrimaryUrl(driveId) {
      return 'https://lh3.googleusercontent.com/d/' + driveId;
    }

    function handleDriveImgError(imgEl, driveId) {
      const step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);
      if (step === 0) {
        imgEl.setAttribute('data-fallback-step', '1');
        imgEl.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w1200';
      } else if (step === 1) {
        imgEl.setAttribute('data-fallback-step', '2');
        imgEl.src = 'https://drive.google.com/uc?export=view&id=' + driveId;
      }
    }

    // Tạo thẻ HTML sản phẩm chuẩn Flatsome (chỉ có % giảm giá góc trên bên trái, không có nhãn dán phụ)
    function createFlatsomeProductCard(product) {
      const imgUrl = getDrivePrimaryUrl(product.driveId);
      return `
        <div class="product-small box group">
          <div class="box-image relative aspect-square w-full bg-slate-50 overflow-hidden border-b border-slate-100">
            <!-- Duy nhất % giảm giá góc trên bên trái chuẩn Flatsome -->
            <span class="flatsome-Discount-badge">${product.discount}</span>
            <img 
              src="${imgUrl}" 
              alt="${product.name}" 
              loading="lazy"
              onerror="handleDriveImgError(this, '${product.driveId}')"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-300 cursor-pointer"
              onclick="openQuickView(${product.id})"
            />
          </div>
          <div class="box-text p-2.5 sm:p-3.5 flex flex-col flex-1 justify-between text-center">
            <div>
              <div class="text-[10px] sm:text-[11px] text-slate-400 uppercase tracking-wide mb-0.5">${product.category}</div>
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-[#0056b3] line-clamp-1 mb-1.5 cursor-pointer" onclick="openQuickView(${product.id})">
                ${product.name}
              </h3>
            </div>
            <div>
              <div class="flex items-center justify-center flex-wrap gap-1.5 mb-2">
                <del class="text-[11px] sm:text-xs text-slate-400">${product.oldPrice}</del>
                <ins class="text-xs sm:text-sm font-extrabold text-[#d0011b] no-underline">${product.newPrice}</ins>
              </div>
              <button 
                type="button" 
                onclick="openQuickView(${product.id})"
                class="w-full py-1.5 px-2 rounded bg-slate-100 hover:bg-[#0056b3] text-slate-700 hover:text-white text-[11px] sm:text-xs font-semibold transition"
              >
                Xem nhanh
              </button>
            </div>
          </div>
        </div>
      `;
    }

    // Render toàn bộ sản phẩm ra các lưới trang chủ
    function renderAllProductSections(filterCategory = 'ALL', searchQuery = '') {
      const mainGrid = document.getElementById('mainProductGrid');
      const heading = document.getElementById('activeCategoryHeading');

      let filtered = DRIVE_PRODUCTS;
      if (filterCategory && filterCategory !== 'ALL') {
        filtered = filtered.filter(p => p.category.toLowerCase() === filterCategory.toLowerCase());
        heading.textContent = 'DANH MỤC: ' + filterCategory.toUpperCase() + ' (' + filtered.length + ')';
      } else if (searchQuery.trim() !== '') {
        const q = searchQuery.trim().toLowerCase();
        filtered = filtered.filter(p => p.name.toLowerCase().includes(q) || p.category.toLowerCase().includes(q));
        heading.textContent = 'KẾT QUẢ TÌM KIẾM: "' + searchQuery.trim() + '" (' + filtered.length + ')';
      } else {
        heading.textContent = 'SẢN PHẨM THỰC TẾ NỔI BẬT (12)';
      }

      if (filtered.length === 0) {
        mainGrid.innerHTML = `
          <div class="col-span-2 md:col-span-3 lg:col-span-4 py-8 text-center text-xs sm:text-sm text-slate-500">
            Không tìm thấy sản phẩm phù hợp. Vui lòng chọn danh mục khác hoặc liên hệ <strong>0919.734.343 - 0905.110.299</strong>.
          </div>
        `;
      } else {
        mainGrid.innerHTML = filtered.map(createFlatsomeProductCard).join('');
      }

      // Render các chuyên mục cố định bên dưới
      const acGrid = document.getElementById('acProductGrid');
      if (acGrid) {
        acGrid.innerHTML = DRIVE_PRODUCTS.filter(p => p.category === 'Điều hòa').map(createFlatsomeProductCard).join('');
      }

      const fridgeWasherGrid = document.getElementById('fridgeWasherGrid');
      if (fridgeWasherGrid) {
        fridgeWasherGrid.innerHTML = DRIVE_PRODUCTS.filter(p => p.category === 'Tủ lạnh' || p.category === 'Máy giặt').map(createFlatsomeProductCard).join('');
      }

      const waterFanGrid = document.getElementById('waterFanGrid');
      if (waterFanGrid) {
        waterFanGrid.innerHTML = DRIVE_PRODUCTS.filter(p => p.category === 'Máy lọc nước' || p.category === 'Quạt điều hòa' || p.category === 'Quạt hơi nước').map(createFlatsomeProductCard).join('');
      }
    }

    // Modal Xem nhanh sản phẩm
    function openQuickView(productId) {
      const product = DRIVE_PRODUCTS.find(p => p.id === productId);
      if (!product) return;

      const modal = document.getElementById('quickViewModal');
      const modalImg = document.getElementById('modalImage');
      modalImg.removeAttribute('data-fallback-step');
      modalImg.src = getDrivePrimaryUrl(product.driveId);
      modalImg.onerror = function() { handleDriveImgError(modalImg, product.driveId); };

      document.getElementById('modalCategory').textContent = product.category;
      document.getElementById('modalProductName').textContent = product.name;
      document.getElementById('modalOldPrice').textContent = product.oldPrice;
      document.getElementById('modalNewPrice').textContent = product.newPrice;
      document.getElementById('modalDiscountBadge').textContent = product.discount;

      const jumpBtn = document.getElementById('modalJumpQuoteBtn');
      jumpBtn.onclick = function() {
        modal.classList.add('hidden');
        modal.classList.remove('flex');
        const selectEl = document.getElementById('quoteProduct');
        if (selectEl) {
          selectEl.value = product.category;
        }
        document.getElementById('form-bao-gia').scrollIntoView({ behavior: 'smooth' });
      };

      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    window.addEventListener('DOMContentLoaded', function() {
      // Gắn fallback cho tất cả các ảnh tĩnh dùng data-drive-id
      document.querySelectorAll('img[data-drive-id]').forEach(function(img) {
        const driveId = img.getAttribute('data-drive-id');
        img.addEventListener('error', function() {
          handleDriveImgError(img, driveId);
        });
      });

      // Khởi tạo danh sách sản phẩm
      renderAllProductSections('ALL');

      // Logic tự trượt 2 ảnh Banner bằng kích thước
      const slides = document.querySelectorAll('#heroBannerSlider .banner-slide');
      const dots = document.querySelectorAll('#heroBannerSlider .banner-dot');
      let currentSlide = 0;
      let bannerInterval = null;

      function showBannerSlide(index) {
        currentSlide = (index + slides.length) % slides.length;
        slides.forEach((s, i) => {
          if (i === currentSlide) {
            s.classList.add('active');
          } else {
            s.classList.remove('active');
          }
        });
        dots.forEach((d, i) => {
          if (i === currentSlide) {
            d.classList.remove('bg-white/50');
            d.classList.add('bg-white', 'scale-125');
          } else {
            d.classList.add('bg-white/50');
            d.classList.remove('bg-white', 'scale-125');
          }
        });
      }

      function startBannerAutoSlide() {
        stopBannerAutoSlide();
        bannerInterval = setInterval(function() {
          showBannerSlide(currentSlide + 1);
        }, 4000);
      }

      function stopBannerAutoSlide() {
        if (bannerInterval) clearInterval(bannerInterval);
      }

      document.getElementById('prevBannerBtn').addEventListener('click', function() {
        showBannerSlide(currentSlide - 1);
        startBannerAutoSlide();
      });

      document.getElementById('nextBannerBtn').addEventListener('click', function() {
        showBannerSlide(currentSlide + 1);
        startBannerAutoSlide();
      });

      dots.forEach(function(dot) {
        dot.addEventListener('click', function() {
          const idx = parseInt(dot.getAttribute('data-goto-slide'), 10);
          showBannerSlide(idx);
          startBannerAutoSlide();
        });
      });

      startBannerAutoSlide();

      // Sự kiện nút lọc danh mục
      function activateFilterButtons(cat) {
        document.querySelectorAll('.cat-filter-btn').forEach(function(btn) {
          if (btn.getAttribute('data-filter') === cat) {
            btn.className = 'cat-filter-btn px-2.5 py-1.5 rounded text-xs font-semibold bg-[#0056b3] text-white transition';
          } else {
            btn.className = 'cat-filter-btn px-2.5 py-1.5 rounded text-xs font-semibold bg-slate-100 text-slate-700 hover:bg-blue-50 transition';
          }
        });
      }

      document.querySelectorAll('.cat-filter-btn, .cat-filter-trigger').forEach(function(el) {
        el.addEventListener('click', function() {
          const cat = el.getAttribute('data-filter') || 'ALL';
          activateFilterButtons(cat);
          renderAllProductSections(cat);
          const prodSection = document.getElementById('san-pham-trang-chu');
          if (prodSection) prodSection.scrollIntoView({ behavior: 'smooth' });
        });
      });

      // Chọn danh mục phụ nhảy xuống form báo giá
      document.querySelectorAll('.quote-cat-trigger').forEach(function(el) {
        el.addEventListener('click', function() {
          const catName = el.getAttribute('data-quote-cat') || '';
          const noteInput = document.getElementById('quoteNote');
          if (noteInput && catName) {
            noteInput.value = 'Tôi cần tư vấn & báo giá danh mục: ' + catName;
          }
        });
      });

      // Tìm kiếm trên máy tính và điện thoại
      function runProductSearch(inputId) {
        const val = document.getElementById(inputId).value || '';
        renderAllProductSections('ALL', val);
        document.getElementById('san-pham-trang-chu').scrollIntoView({ behavior: 'smooth' });
      }

      document.getElementById('desktopSearchBtn').addEventListener('click', function() { runProductSearch('desktopSearchInput'); });
      document.getElementById('desktopSearchInput').addEventListener('keydown', function(e) {
        if (e.key === 'Enter') runProductSearch('desktopSearchInput');
      });

      document.getElementById('mobileSearchBtn').addEventListener('click', function() { runProductSearch('mobileSearchInput'); });
      document.getElementById('mobileSearchInput').addEventListener('keydown', function(e) {
        if (e.key === 'Enter') runProductSearch('mobileSearchInput');
      });

      // Menu Mobile Drawer
      const mobileDrawer = document.getElementById('mobileMenuDrawer');
      function closeMobileDrawer() {
        mobileDrawer.classList.add('hidden');
      }
      document.getElementById('mobileMenuBtn').addEventListener('click', function() {
        mobileDrawer.classList.remove('hidden');
      });
      document.getElementById('closeMobileMenuBtn').addEventListener('click', closeMobileDrawer);
      document.getElementById('mobileMenuBackdrop').addEventListener('click', closeMobileDrawer);
      document.querySelectorAll('.mobile-cat-link').forEach(function(link) {
        link.addEventListener('click', function() {
          const cat = link.getAttribute('data-filter');
          if (cat) {
            activateFilterButtons(cat);
            renderAllProductSections(cat);
          }
          closeMobileDrawer();
        });
      });

      // Đóng Modal Xem Nhanh
      const quickModal = document.getElementById('quickViewModal');
      document.getElementById('closeModalBtn').addEventListener('click', function() {
        quickModal.classList.add('hidden');
        quickModal.classList.remove('flex');
      });
      quickModal.addEventListener('click', function(e) {
        if (e.target === quickModal) {
          quickModal.classList.add('hidden');
          quickModal.classList.remove('flex');
        }
      });

      // Chuyển đổi Google Map giữa CS1 và CS2 ngoài trang chủ
      const mapIframe = document.getElementById('googleMapIframe');
      const cs1Btn = document.getElementById('mapCs1Btn');
      const cs2Btn = document.getElementById('mapCs2Btn');

      cs1Btn.addEventListener('click', function() {
        mapIframe.src = 'https://maps.google.com/maps?q=21%20B%C3%A0u%20Tr%E1%BA%A3ng%206,%20Thanh%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed';
        cs1Btn.className = 'px-2.5 py-1 rounded text-xs font-bold bg-[#0056b3] text-white';
        cs2Btn.className = 'px-2.5 py-1 rounded text-xs font-bold bg-white text-slate-700 border border-slate-300 hover:bg-blue-50';
      });

      cs2Btn.addEventListener('click', function() {
        mapIframe.src = 'https://maps.google.com/maps?q=72%20V%C3%B5%20V%C4%83n%20T%E1%BA%A7n,%20Thanh%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed';
        cs2Btn.className = 'px-2.5 py-1 rounded text-xs font-bold bg-[#0056b3] text-white';
        cs1Btn.className = 'px-2.5 py-1 rounded text-xs font-bold bg-white text-slate-700 border border-slate-300 hover:bg-blue-50';
      });

      // Xử lý gửi Form Yêu Cầu & Báo Giá
      document.getElementById('quoteRequestForm').addEventListener('submit', function(e) {
        e.preventDefault();
        const name = document.getElementById('quoteName').value.trim();
        const phone = document.getElementById('quotePhone').value.trim();
        const product = document.getElementById('quoteProduct').value;
        const address = document.getElementById('quoteAddress').value.trim();
        const successBox = document.getElementById('quoteSuccessBox');

        successBox.innerHTML = `
          <div class="font-bold text-green-900 mb-1"><i class="fa-solid fa-circle-check mr-1"></i> Đã tiếp nhận yêu cầu báo giá của quý khách!</div>
          <div>Cảm ơn <strong>${name}</strong> (${phone}) đã gửi yêu cầu báo giá danh mục <strong>${product}</strong>${address ? ' tại ' + address : ''}. Bộ phận kinh doanh <strong>CÔNG TY TNHH CƠ ĐIỆN HOÀNG ANH (0919.734.343 - 0905.110.299)</strong> sẽ liên hệ tư vấn ngay.</div>
        `;
        successBox.classList.remove('hidden');
        e.target.reset();
      });
    });
  </script>
</body>
</html>
