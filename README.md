
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>خانم دکتر زهره پناهی - کمک جراح حرفه‌ای</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Vazirmatn:wght@100;200;300;400;500;600;700;800;900&display=swap');
        
        body {
            font-family: 'Vazirmatn', sans-serif;
            background-color: #f8f9fa;
        }
        
        .hero-gradient {
            background: linear-gradient(135deg, #f3e7e9 0%, #e3eeff 100%);
        }
        
        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        
        .testimonial-card {
            transition: all 0.3s ease;
        }
        
        .testimonial-card:hover {
            transform: scale(1.03);
        }
        
        .nav-link {
            position: relative;
        }
        
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -2px;
            right: 0;
            background-color: #3b82f6;
            transition: width 0.3s ease;
        }
        
        .nav-link:hover::after {
            width: 100%;
        }
        
        .animate-pulse-slow {
            animation: pulse 3s infinite;
        }
        
        @keyframes pulse {
            0%, 100% {
                opacity: 1;
            }
            50% {
                opacity: 0.7;
            }
        }
        
        .surgical-icon {
            color: #3b82f6;
            background-color: #e0f2fe;
            border-radius: 50%;
            padding: 15px;
            font-size: 1.5rem;
        }
    </style>
</head>
<body class="text-gray-800">
    <!-- Navigation -->
    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <i class="fas fa-syringe surgical-icon"></i>
                <a href="#" class="text-xl font-bold text-blue-600">خانم دکتر زهره پناهی</a>
            </div>
            
            <div class="hidden md:flex space-x-8">
                <a href="#home" class="nav-link text-gray-700 hover:text-blue-600">خانه</a>
                <a href="#about" class="nav-link text-gray-700 hover:text-blue-600">درباره من</a>
                <a href="#services" class="nav-link text-gray-700 hover:text-blue-600">خدمات</a>
                <a href="#experience" class="nav-link text-gray-700 hover:text-blue-600">تجربیات</a>
                <a href="#contact" class="nav-link text-gray-700 hover:text-blue-600">تماس</a>
            </div>
            
            <button class="md:hidden text-gray-700" id="mobile-menu-button">
                <i class="fas fa-bars text-2xl"></i>
            </button>
        </div>
        
        <!-- Mobile menu -->
        <div class="md:hidden hidden bg-white py-2 px-4 shadow-lg" id="mobile-menu">
            <a href="#home" class="block py-2 text-gray-700 hover:text-blue-600">خانه</a>
            <a href="#about" class="block py-2 text-gray-700 hover:text-blue-600">درباره من</a>
            <a href="#services" class="block py-2 text-gray-700 hover:text-blue-600">خدمات</a>
            <a href="#experience" class="block py-2 text-gray-700 hover:text-blue-600">تجربیات</a>
            <a href="#contact" class="block py-2 text-gray-700 hover:text-blue-600">تماس</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-gradient py-20">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0">
                <h1 class="text-4xl md:text-5xl font-bold text-gray-800 mb-4">خانم دکتر زهره پناهی</h1>
                <h2 class="text-2xl md:text-3xl font-semibold text-blue-600 mb-6">کمک جراح حرفه‌ای با 2 سال سابقه</h2>
                <p class="text-lg text-gray-700 mb-8 leading-relaxed">
                    با دانش و تخصص در زمینه کمک‌های جراحی، همراه شما در مسیر سلامت و بهبودی هستم. دقت و مراقبت از بیماران اولویت اصلی من است.
                </p>
                <div class="flex space-x-4">
                    <a href="#contact" class="bg-blue-600 text-white px-6 py-3 rounded-lg font-medium hover:bg-blue-700 transition duration-300">
                        تماس با من
                    </a>
                    <a href="#services" class="border-2 border-blue-600 text-blue-600 px-6 py-3 rounded-lg font-medium hover:bg-blue-50 transition duration-300">
                        خدمات من
                    </a>
                </div>
            </div>
            
            <div class="md:w-1/2 flex justify-center">
                <div class="relative">
                    <img src="/IMG_6638.jpeg" 
                         alt="دکتر زهره پناهی - کمک جراح" 
                         class="rounded-lg shadow-2xl w-full max-w-md border-4 border-white">
                    <div class="absolute -bottom-5 -left-5 bg-blue-500 text-white px-4 py-2 rounded-lg shadow-lg">
                        <i class="fas fa-award mr-2"></i> کمک جراح نمونه ۱۴۰۳
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">درباره من</h2>
                <div class="w-20 h-1 bg-blue-500 mx-auto"></div>
            </div>
            
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/3 mb-10 md:mb-0 flex justify-center">
                    <img src="/IMG_6637.jpeg" 
                         alt="خانم دکتر زهره پناهی" 
                         class="rounded-full w-64 h-64 object-cover border-4 border-blue-100 shadow-lg">
                </div>
                
                <div class="md:w-2/3 md:pr-10">
                    <h3 class="text-2xl font-semibold text-gray-800 mb-4">سلام، من دکتر زهره پناهی هستم</h3>
                    <p class="text-gray-600 mb-6 leading-relaxed">
                        کمک جراح متخصص با 2 سال سابقه کار در یکی از بهترین شفاخانه های کابل. فارغ‌التحصیل رشته پزشکی از بهترین انستیتسوت افغانستان با رتبه عالی. عاشق کمک به بیماران و مشارکت در جراحی‌های موفق هستم.
                    </p>
                    
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-8">
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-scalpel text-blue-600"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold text-gray-800">تخصص</h4>
                                <p class="text-gray-600">کمک جراحی عمومی و تخصصی</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-graduation-cap text-blue-600"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold text-gray-800">تحصیلات</h4>
                                <p class="text-gray-600">دارای مدرک 14 ساله - انستیتوت ...</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-language text-blue-600"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold text-gray-800">زبان‌ها</h4>
                                <p class="text-gray-600">دری (زبان مادری)، انگلیسی (پیشرفته)</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-heart text-blue-600"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold text-gray-800">علاقه‌مندی‌ها</h4>
                                <p class="text-gray-600">تحقیقات پزشکی، آموزش به دانشجویان، پیاده‌روی</p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="flex space-x-4">
                        <a href="#contact" class="inline-block bg-blue-600 text-white px-6 py-3 rounded-lg font-medium hover:bg-blue-700 transition duration-300">
                            بیشتر درباره من
                        </a>
                        <a href="#" class="inline-block border border-blue-600 text-blue-600 px-6 py-3 rounded-lg font-medium hover:bg-blue-50 transition duration-300">
                            دانلود رزومه
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">خدمات من</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">خدمات تخصصی کمک جراحی با بالاترین کیفیت و استانداردهای پزشکی</p>
                <div class="w-20 h-1 bg-blue-500 mx-auto mt-4"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden service-card transition duration-300">
                    <div class="h-48 bg-blue-100 flex items-center justify-center">
                        <i class="fas fa-procedures text-blue-600 text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">کمک در جراحی‌های عمومی</h3>
                        <p class="text-gray-600 mb-4">
                            مشارکت در جراحی‌های عمومی با دقت و مهارت بالا، آماده‌سازی بیمار قبل از عمل و مراقبت‌های پس از عمل
                        </p>
                        <ul class="text-gray-600 space-y-2">
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-blue-500 mr-2"></i>
                                آماده‌سازی تجهیزات جراحی
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-blue-500 mr-2"></i>
                                کمک به جراح اصلی
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-blue-500 mr-2"></i>
                                کنترل علائم حیاتی بیمار
                            </li>
                        </ul>
                    </div>
                </div>
                
                <!-- Service 2 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden service-card transition duration-300">
                    <div class="h-48 bg-blue-100 flex items-center justify-center">
                        <i class="fas fa-heartbeat text-blue-600 text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">کمک در جراحی‌های تخصصی</h3>
                        <p class="text-gray-600 mb-4">
                            مشارکت در جراحی‌های تخصصی مختلف با همکاری جراحان متخصص در زمینه‌های مختلف
                        </p>
                        <ul class="text-gray-600 space-y-2">
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-blue-500 mr-2"></i>
                                جراحی‌های ارتوپدی
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-blue-500 mr-2"></i>
                                جراحی‌های زنان
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-blue-500 mr-2"></i>
                                جراحی‌های زیبایی
                            </li>
                        </ul>
                    </div>
                </div>
                
                <!-- Service 3 -->
                <div class="bg-white rounded-lg shadow-md overflow-hidden service-card transition duration-300">
                    <div class="h-48 bg-blue-100 flex items-center justify-center">
                        <i class="fas fa-clipboard-check text-blue-600 text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-3">مشاوره قبل از عمل</h3>
                        <p class="text-gray-600 mb-4">
                            ارائه مشاوره تخصصی به بیماران قبل از عمل جراحی و پاسخگویی به سوالات و نگرانی‌های آن‌ها
                        </p>
                        <ul class="text-gray-600 space-y-2">
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-blue-500 mr-2"></i>
                                توضیح مراحل عمل
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-blue-500 mr-2"></i>
                                راهنمایی‌های قبل از عمل
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check-circle text-blue-500 mr-2"></i>
                                پاسخ به سوالات پزشکی
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#contact" class="inline-block bg-blue-600 text-white px-8 py-3 rounded-lg font-medium hover:bg-blue-700 transition duration-300">
                    درخواست مشاوره
                </a>
            </div>
        </div>
    </section>

    <!-- Experience Section -->
    <section id="experience" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">تجربیات و مدارک</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">سوابق کاری و تحصیلی من در زمینه کمک جراحی</p>
                <div class="w-20 h-1 bg-blue-500 mx-auto mt-4"></div>
            </div>
            
            <div class="flex flex-col md:flex-row">
                <!-- Work Experience -->
                <div class="md:w-1/2 md:pr-8 mb-10 md:mb-0">
                    <h3 class="text-2xl font-semibold text-gray-800 mb-6 flex items-center">
                        <i class="fas fa-briefcase text-blue-500 mr-3"></i> سوابق کاری
                    </h3>
                    
                    <div class="space-y-8">
                        <!-- Experience 1 -->
                        <div class="flex">
                            <div class="flex flex-col items-center mr-6">
                                <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center">
                                    <i class="fas fa-hospital text-blue-600"></i>
                                </div>
                                <div class="w-px h-full bg-gray-300 mt-2"></div>
                            </div>
                            <div>
                                <h4 class="text-xl font-semibold text-gray-800">کمک جراح بخش عمومی</h4>
                                <p class="text-blue-600 mb-2">شفاخانه امیری غرب </p>
                                <p class="text-gray-500 mb-2">۱۴۰۱ تا کنون</p>
                                <p class="text-gray-600">
                                    مسئولیت کمک به جراحان در انجام عمل‌های مختلف، آماده‌سازی بیماران قبل از عمل و نظارت بر روند بهبودی پس از عمل
                                </p>
                            </div>
                        </div>
                        
                        <!-- Experience 2 -->
                        <div class="flex">
                            <div class="flex flex-col items-center mr-6">
                                <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center">
                                    <i class="fas fa-clinic-medical text-blue-600"></i>
                                </div>
                                <div class="w-px h-full bg-gray-300 mt-2"></div>
                            </div>
                            <div>
                                <h4 class="text-xl font-semibold text-gray-800">کمک جراح بخش ارتوپدی</h4>
                                <p class="text-blue-600 mb-2">شفاخانه امیری غرب </p>
                                <p class="text-gray-500 mb-2">۱۴۰۱ - اکنون</p>
                                <p class="text-gray-600">
                                    کمک به جراحان ارتوپد در انجام عمل‌های مختلف، مدیریت تجهیزات جراحی و آموزش به بیماران پس از عمل
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Education -->
                <div class="md:w-1/2 md:pl-8">
                    <h3 class="text-2xl font-semibold text-gray-800 mb-6 flex items-center">
                        <i class="fas fa-graduation-cap text-blue-500 mr-3"></i> تحصیلات
                    </h3>
                    
                    <div class="space-y-8">
                        <!-- Education 1 -->
                        <div class="flex">
                            <div class="flex flex-col items-center mr-6">
                                <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center">
                                    <i class="fas fa-university text-blue-600"></i>
                                </div>
                                <div class="w-px h-full bg-gray-300 mt-2"></div>
                            </div>
                            <div>
                                <h4 class="text-xl font-semibold text-gray-800">دوره کمک جراحی پیشرفته</h4>
                                <p class="text-blue-600 mb-2">انستیتوت ...</p>
                                <p class="text-gray-500 mb-2">۱۴۰۱ - ۱۴۰۲</p>
                                <p class="text-gray-600">
                                    گذراندن دوره تخصصی کمک جراحی با تمرکز بر تکنیک‌های مدرن و استانداردهای بین‌المللی
                                </p>
                            </div>
                        </div>
                        
                        <!-- Education 2 -->
                        <div class="flex">
                            <div class="flex flex-col items-center mr-6">
                                <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center">
                                    <i class="fas fa-user-graduate text-blue-600"></i>
                                </div>
                                <div class="w-px h-full bg-gray-300 mt-2"></div>
                            </div>
                            <div>
                                <h4 class="text-xl font-semibold text-gray-800">تحصیل ۲ ساله </h4>
                                <p class="text-blue-600 mb-2">انستیتیوت ...</p>
                                <p class="text-gray-500 mb-2">۱۴۰۱ - ۱۴۰۲</p>
                                <p class="text-gray-600">
                                    فارغ‌التحصیل با رتبه ممتاز و کسب عنوان محصل نمونه در سال آخر تحصیل
                                </p>
                            </div>
                        </div>
                        
                        <!-- Education 3 -->
                        <div class="flex">
                            <div class="flex flex-col items-center mr-6">
                                <div class="w-12 h-12 bg-blue-100 rounded-full flex items-center justify-center">
                                    <i class="fas fa-certificate text-blue-600"></i>
                                </div>
                            </div>
                            <div>
                                <h4 class="text-xl font-semibold text-gray-800">دوره‌های تخصصی</h4>
                                <p class="text-blue-600 mb-2">موسسات معتبر آموزشی</p>
                                <p class="text-gray-500 mb-2">۱۴۰۱ تا کنون</p>
                                <p class="text-gray-600">
                                    شامل دوره‌های احیای قلبی ریوی پیشرفته (ACLS)، کنترل عفونت در اتاق عمل، اصول استریلیزاسیون و دوره‌های روانشناسی بیمار
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">نظرات همکاران و بیماران</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">تجربیات همکاران و بیماران از همکاری با من</p>
                <div class="w-20 h-1 bg-blue-500 mx-auto mt-4"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-white p-6 rounded-lg shadow-md testimonial-card">
                    <div class="flex items-center mb-4">
                        <img src="/IMG_6639.jpeg" alt="دکتر محمد هادی نهضت" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-semibold text-gray-800">دکتر محمد هادی نهضت </h4>
                            <p class="text-blue-500 text-sm">جراح عمومی </p>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">
                        "خانم دکتر پناهی یکی از بهترین کمک جراحانی است که با ایشان همکاری داشته‌ام. دقت و سرعت عمل ایشان در اتاق عمل واقعاً قابل تقدیر است و همیشه با آرامش و تسلط کامل به جراح اصلی کمک می‌کنند."
                    </p>
                    <div class="mt-4 flex text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="bg-white p-6 rounded-lg shadow-md testimonial-card">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/women/32.jpg" alt="مریم محمدی" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-semibold text-gray-800">مریم محمدی</h4>
                            <p class="text-blue-500 text-sm">بیمار</p>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">
                        "قبل از عمل جراحی بسیار مضطرب بودم، اما توضیحات و راهنمایی‌های دکتر پناهی به من آرامش داد. در طول عمل نیز با دقت و مهربانی مرا راهنمایی کردند و پس از عمل نیز پیگیر وضعیت من بودند. واقعاً سپاسگزارم."
                    </p>
                    <div class="mt-4 flex text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="bg-white p-6 rounded-lg shadow-md testimonial-card">
                    <div class="flex items-center mb-4">
                        <img src="https://randomuser.me/api/portraits/women/65.jpg" alt="نازنین کریمی" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-semibold text-gray-800">نازنین کریمی</h4>
                            <p class="text-blue-500 text-sm">پرستار اتاق عمل</p>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">
                        "همکاری با دکتر پناهی در اتاق عمل همیشه لذت‌بخش است. ایشان نه تنها در کار خود بسیار حرفه‌ای هستند، بلکه با تمام تیم با احترام و مهربانی رفتار می‌کنند و فضای مثبتی در اتاق عمل ایجاد می‌کنند."
                    </p>
                    <div class="mt-4 flex text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">تماس با من</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">برای دریافت مشاوره یا همکاری می‌توانید با من در تماس باشید</p>
                <div class="w-20 h-1 bg-blue-500 mx-auto mt-4"></div>
            </div>
            
            <div class="flex flex-col md:flex-row">
                <div class="md:w-1/2 mb-10 md:mb-0 md:pr-8">
                    <h3 class="text-2xl font-semibold text-gray-800 mb-6">اطلاعات تماس</h3>
                    
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-map-marker-alt text-blue-600"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold text-gray-800">آدرس</h4>
                                <p class="text-gray-600">افغانستان، کابل، دشت برچی</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-phone text-blue-600"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold text-gray-800">تلفن</h4>
                                <p class="text-gray-600">۰۷۰۰۰۰۰۰۰۰</p>
                                <p class="text-gray-600">۰۷۰۰۰۰۰۰۰۰</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-envelope text-blue-600"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold text-gray-800">ایمیل</h4>
                                <p class="text-gray-600">dr.zohrapanahi@example.com</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-blue-100 p-3 rounded-full mr-4">
                                <i class="fas fa-clock text-blue-600"></i>
                            </div>
                            <div>
                                <h4 class="font-semibold text-gray-800">ساعات کاری</h4>
                                <p class="text-gray-600">شنبه تا چهارشنبه: ۸ صبح تا ۴ بعدازظهر</p>
                                <p class="text-gray-600">پنجشنبه: ۸ صبح تا ۱۲ ظهر</p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="mt-8">
                        <h4 class="font-semibold text-gray-800 mb-4">من را در شبکه‌های اجتماعی دنبال کنید</h4>
                        <div class="flex space-x-4">
                            <a href="#" class="bg-blue-100 w-10 h-10 rounded-full flex items-center justify-center text-blue-600 hover:bg-blue-200">
                                <i class="fab fa-instagram"></i>
                            </a>
                            <a href="#" class="bg-blue-100 w-10 h-10 rounded-full flex items-center justify-center text-blue-600 hover:bg-blue-200">
                                <i class="fab fa-telegram"></i>
                            </a>
                            <a href="#" class="bg-blue-100 w-10 h-10 rounded-full flex items-center justify-center text-blue-600 hover:bg-blue-200">
                                <i class="fab fa-linkedin"></i>
                            </a>
                            <a href="#" class="bg-blue-100 w-10 h-10 rounded-full flex items-center justify-center text-blue-600 hover:bg-blue-200">
                                <i class="fab fa-twitter"></i>
                            </a>
                        </div>
                    </div>
                </div>
                
                <div class="md:w-1/2">
                    <form class="bg-gray-50 p-6 rounded-lg shadow-md">
                        <h3 class="text-2xl font-semibold text-gray-800 mb-6">فرم تماس</h3>
                        
                        <div class="mb-4">
                            <label for="name" class="block text-gray-700 mb-2">نام کامل</label>
                            <input type="text" id="name" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                        </div>
                        
                        <div class="mb-4">
                            <label for="email" class="block text-gray-700 mb-2">ایمیل</label>
                            <input type="email" id="email" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                        </div>
                        
                        <div class="mb-4">
                            <label for="phone" class="block text-gray-700 mb-2">تلفن</label>
                            <input type="tel" id="phone" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                        </div>
                        
                        <div class="mb-4">
                            <label for="subject" class="block text-gray-700 mb-2">موضوع</label>
                            <select id="subject" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                                <option value="">-- انتخاب کنید --</option>
                                <option value="consultation">مشاوره قبل از عمل</option>
                                <option value="collaboration">درخواست همکاری</option>
                                <option value="question">سوال پزشکی</option>
                                <option value="other">سایر</option>
                            </select>
                        </div>
                        
                        <div class="mb-4">
                            <label for="message" class="block text-gray-700 mb-2">پیام شما</label>
                            <textarea id="message" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500"></textarea>
                        </div>
                        
                        <button type="submit" class="w-full bg-blue-600 text-white px-6 py-3 rounded-lg font-medium hover:bg-blue-700 transition duration-300">
                            ارسال پیام
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between">
                <div class="mb-8 md:mb-0">
                    <div class="flex items-center mb-4">
                        <i class="fas fa-syringe surgical-icon"></i>
                        <span class="text-xl font-bold mr-2">خانم دکتر زهره پناهی
                    </div>
                    <p class="text-gray-400 max-w-xs">
                        کمک جراح متخصص با 2 سال سابقه در ارائه خدمات حرفه‌ای در زمینه کمک جراحی
                    </p>
                </div>
                
                <div class="mb-8 md:mb-0">
                    <h4 class="text-lg font-semibold mb-4">لینک‌های سریع</h4>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-400 hover:text-white transition">خانه</a></li>
                        <li><a href="#about" class="text-gray-400 hover:text-white transition">درباره من</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-white transition">خدمات</a></li>
                        <li><a href="#experience" class="text-gray-400 hover:text-white transition">تجربیات</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white transition">تماس</a></li>
                    </ul>
                </div>
                
                <div class="mb-8 md:mb-0">
                    <h4 class="text-lg font-semibold mb-4">خدمات</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition">کمک در جراحی‌های عمومی</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">کمک در جراحی‌های تخصصی</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">مشاوره قبل از عمل</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">خبرنامه</h4>
                    <p class="text-gray-400 mb-4 max-w-xs">
                        برای دریافت آخرین مقالات پزشکی و نکات مراقبتی ایمیل خود را وارد کنید
                    </p>
                    <div class="flex">
                        <input type="email" placeholder="ایمیل شما" class="px-4 py-2 rounded-r-lg focus:outline-none text-gray-800">
                        <button class="bg-blue-600 px-4 py-2 rounded-l-lg hover:bg-blue-700 transition">
                            <i class="fas fa-paper-plane"></i>
                        </button>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-700 mt-12 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 mb-4 md:mb-0">
                    © ۱۴۰۴ - تمامی حقوق برای دکتر زهره پناهی محفوظ است
                </p>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover:text-white transition">
                        <i class="fab fa-instagram"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition">
                        <i class="fab fa-telegram"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition">
                        <i class="fab fa-linkedin"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-white transition">
                        <i class="fab fa-twitter"></i>
                    </a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Back to top button -->
    <button id="back-to-top" class="fixed bottom-8 right-8 bg-blue-600 text-white w-12 h-12 rounded-full shadow-lg flex items-center justify-center hidden">
        <i class="fas fa-arrow-up"></i>
    </button>

    <script>
        // Mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        
        // Back to top button
        const backToTopButton = document.getElementById('back-to-top');
        
        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 300) {
                backToTopButton.classList.remove('hidden');
            } else {
                backToTopButton.classList.add('hidden');
            }
        });
        
        backToTopButton.addEventListener('click', () => {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        });
        
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                    
                    // Close mobile menu if open
                    mobileMenu.classList.add('hidden');
                }
            });
        });
        
        // Form submission
        const contactForm = document.querySelector('form');
        if (contactForm) {
            contactForm.addEventListener('submit', function(e) {
                e.preventDefault();
                
                // Get form values
                const name = document.getElementById('name').value;
                const email = document.getElementById('email').value;
                const phone = document.getElementById('phone').value;
                const subject = document.getElementById('subject').value;
                const message = document.getElementById('message').value;
                
                // Here you would typically send the data to a server
                // For now, we'll just show an alert
                alert(`پیام شما با موفقیت ارسال شد!\n\nنام: ${name}\nایمیل: ${email}\nتلفن: ${phone}\nموضوع: ${subject}\nپیام: ${message}`);
                
                // Reset form
                contactForm.reset();
            });
        }
    </script>
</body>
</html>
