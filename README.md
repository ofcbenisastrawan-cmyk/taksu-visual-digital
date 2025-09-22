<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taksu visual- Jasa Digital Terpercaya</title>
    <link rel="icon" type="image" href="tv.png2.png">
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'navy': '#1e3a8a',
                        'navy-dark': '#1e40af',
                        'navy-light': '#3b82f6'
                    }
                }
            }
        }
    </script>
    <style>
        .smooth-transition { transition: all 0.3s ease; }
        .fade-in { opacity: 0; animation: fadeIn 0.6s ease forwards; }
        @keyframes fadeIn { to { opacity: 1; } }
        .slide-up { transform: translateY(20px); opacity: 0; animation: slideUp 0.8s ease forwards; }
        @keyframes slideUp { to { transform: translateY(0); opacity: 1; } }
    </style>
</head>
<body class="bg-white text-gray-800">
    <nav class="bg-navy shadow-lg fixed w-full top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <div class="flex items-center space-x-3">
                    <div class="w-10 h-10 rounded-lg flex items-center justify-center">
                        <img src="tv.png" alt="logo" class="w-8 h-8">
                            <path d="M12 2L2 7v10c0 5.55 3.84 9.74 9 11 5.16-1.26 9-5.45 9-11V7l-10-5z"/>
                            <path d="M9 12l2 2 4-4" stroke="white" stroke-width="2" fill="none"/>
                        </svg>
                    </div>
                    <span class="text-white text-xl font-bold">Taksu visual</span>
                </div>
                

                <div class="hidden md:flex space-x-8">
                    <a href="#" onclick="showSection('beranda')" class="nav-link text-white hover:text-blue-200 smooth-transition font-medium">Beranda</a>
                    <a href="#" onclick="showSection('layanan')" class="nav-link text-white hover:text-blue-200 smooth-transition font-medium">Layanan</a>
                    <a href="#" onclick="showSection('portofolio')" class="nav-link text-white hover:text-blue-200 smooth-transition font-medium">Portofolio</a>
                    <a href="#" onclick="showSection('tentang')" class="nav-link text-white hover:text-blue-200 smooth-transition font-medium">Tentang Kami</a>
                    <a href="#" onclick="showSection('kontak')" class="nav-link text-white hover:text-blue-200 smooth-transition font-medium">Kontak</a>
                </div>

               
                <div class="md:hidden">
                    <button onclick="toggleMobileMenu()" class="text-white hover:text-blue-200">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                        </svg>
                    </button>
                </div>
            </div>
        </div>

     
        <div id="mobileMenu" class="md:hidden bg-navy-dark hidden">
            <div class="px-2 pt-2 pb-3 space-y-1">
                <a href="#" onclick="showSection('beranda'); toggleMobileMenu()" class="block px-3 py-2 text-white hover:bg-navy-light rounded-md">Beranda</a>
                <a href="#" onclick="showSection('layanan'); toggleMobileMenu()" class="block px-3 py-2 text-white hover:bg-navy-light rounded-md">Layanan</a>
                <a href="#" onclick="showSection('portofolio'); toggleMobileMenu()" class="block px-3 py-2 text-white hover:bg-navy-light rounded-md">Portofolio</a>
                <a href="#" onclick="showSection('tentang'); toggleMobileMenu()" class="block px-3 py-2 text-white hover:bg-navy-light rounded-md">Tentang Kami</a>
                <a href="#" onclick="showSection('kontak'); toggleMobileMenu()" class="block px-3 py-2 text-white hover:bg-navy-light rounded-md">Kontak</a>
            </div>
        </div>
    </nav>

    
    <main class="pt-16">
      
        <section id="beranda" class="section-content min-h-screen bg-gradient-to-br from-navy to-navy-light text-white">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20">
                <div class="text-center fade-in">
                    <h1 class="text-5xl md:text-6xl font-bold mb-6">Solusi Digital Terdepan</h1>
                    <p class="text-xl md:text-2xl mb-8 text-blue-100">Wujudkan visi digital Anda bersama tim profesional kami</p>
                    <div class="space-x-4">
                        <button onclick="showSection('layanan')" class="bg-white text-navy px-8 py-3 rounded-lg font-semibold hover:bg-blue-50 smooth-transition">
                            Lihat Layanan
                        </button>
                        <button onclick="showSection('portofolio')" class="border-2 border-white text-white px-8 py-3 rounded-lg font-semibold hover:bg-white hover:text-navy smooth-transition">
                            Portofolio Kami
                        </button>
                    </div>
                </div>
                
                
                <div class="grid md:grid-cols-3 gap-8 mt-20 slide-up">
                    <div class="bg-white/10 backdrop-blur-sm rounded-xl p-6 text-center hover:bg-white/20 smooth-transition">
                        <div class="w-16 h-16 bg-white/20 rounded-full flex items-center justify-center mx-auto mb-4">
                            <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Kualitas Terjamin</h3>
                        <p class="text-blue-100">Standar internasional dengan hasil yang memuaskan</p>
                    </div>
                    
                    <div class="bg-white/10 backdrop-blur-sm rounded-xl p-6 text-center hover:bg-white/20 smooth-transition">
                        <div class="w-16 h-16 bg-white/20 rounded-full flex items-center justify-center mx-auto mb-4">
                            <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Tepat Waktu</h3>
                        <p class="text-blue-100">Komitmen penuh terhadap deadline yang disepakati</p>
                    </div>
                    
                    <div class="bg-white/10 backdrop-blur-sm rounded-xl p-6 text-center hover:bg-white/20 smooth-transition">
                        <div class="w-16 h-16 bg-white/20 rounded-full flex items-center justify-center mx-auto mb-4">
                            <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z"/>
                            </svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Support 24/7</h3>
                        <p class="text-blue-100">Tim support siap membantu kapan saja Anda butuhkan</p>
                    </div>
                </div>
            </div>
        </section>

        
        <section id="layanan" class="section-content hidden min-h-screen bg-gray-50 py-20">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-16 fade-in">
                    <h2 class="text-4xl font-bold text-navy mb-4">Layanan Kami</h2>
                    <p class="text-xl text-gray-600">Solusi digital lengkap untuk kebutuhan bisnis Anda</p>
                </div>
                
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 slide-up">
                    <div class="bg-white rounded-xl shadow-lg p-8 hover:shadow-xl smooth-transition">
                        <div class="w-16 h-16 bg-navy rounded-lg flex items-center justify-center mb-6">
                            <img src="img.png" alt="button desain grafis" class="w-8 h-8 object-contain">

                        </div>
                        <h3 class="text-2xl font-semibold text-navy mb-4">Fotografi</h3>
                        <p class="text-gray-600 mb-6">Menghadirkan foto terbaik untuk anda</p>
                        <ul class="text-sm text-gray-500 space-y-2">
                            <li>•Foto produk</li>
                            <li>•Foto dokumenter</li>
                        </ul>
                    </div>
                    
                    <div class="bg-white rounded-xl shadow-lg p-8 hover:shadow-xl smooth-transition">
                        <div class="w-16 h-16 bg-navy rounded-lg flex items-center justify-center mb-6">
                            <img src="img.1.png" alt="button desain grafis" class="w-8 h-8 object-contain">
                        </div>
                        <h3 class="text-2xl font-semibold text-navy mb-4">Design Grafis</h3>
                        <p class="text-gray-600 mb-6">Menciptakan desain visual digital terbaik </p>
                        <ul class="text-sm text-gray-500 space-y-2">
                            <li>• Logo</li>
                            <li>• Poster </li>
                        </ul>
                    </div>
                    
                    <div class="bg-white rounded-xl shadow-lg p-8 hover:shadow-xl smooth-transition">
                        <div class="w-16 h-16 bg-navy rounded-lg flex items-center justify-center mb-6">
                            <img src="im.png" alt="button desain grafis" class="w-8 h-8 object-contain">

                        </div>
                        <h3 class="text-2xl font-semibold text-navy mb-4">Editing</h3>
                        <p class="text-gray-600 mb-6">Menyempurnakan karya digital anda dengan editing menarik</p>
                        <ul class="text-sm text-gray-500 space-y-2">
                            <li>• Editing foto </li>
                        
                        </ul>
                    </div>
                </div>
            </div>
        </section>

       
        <section id="portofolio" class="section-content hidden min-h-screen bg-white py-20">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-16 fade-in">
                    <h2 class="text-4xl font-bold text-navy mb-4">Portofolio Kami</h2>
                    <p class="text-xl text-gray-600">Beberapa project terbaik yang telah kami kerjakan</p>
                </div>
                
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 slide-up">
                    <div class="bg-gray-50 rounded-xl overflow-hidden shadow-lg hover:shadow-xl smooth-transition">
                        <!-- Tempat gambar project - Ganti dengan gambar project Anda -->
                        <div class="h-48 bg-gradient-to-br from-navy to-navy-light flex items-center justify-center">
                            <img src="poster.jpg" alt="Project 1" class="w-full h-48 object-cover">
                            <!-- Ganti dengan: <img src="project1.jpg" alt="Project 1" class="w-full h-48 object-cover"> -->
                        </div>
                        <div class="p-6">
                            <h3 class="text-xl font-semibold text-navy mb-2">Design </h3>
                            <p class="text-gray-600 mb-4">Design Poster</p>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-3 py-1 bg-navy text-white text-sm rounded-full">Adobe Photoshop</span>
                                <span class="px-3 py-1 bg-navy text-white text-sm rounded-full">Canva</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="bg-gray-50 rounded-xl overflow-hidden shadow-lg hover:shadow-xl smooth-transition">
                        <div class="h-48 bg-gradient-to-br from-navy-light to-navy flex items-center justify-center">
                            <img src="editing.jpg" alt="Project 2" class="w-full h-48 object-cover">
                        </div>
                        <div class="p-6">
                            <h3 class="text-xl font-semibold text-navy mb-2">Editing</h3>
                            <p class="text-gray-600 mb-4">Editing foto</p>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-3 py-1 bg-navy text-white text-sm rounded-full">Adobe Photoshop</span>
                               
                            </div>
                        </div>
                    </div>
                    
                    <div class="bg-gray-50 rounded-xl overflow-hidden shadow-lg hover:shadow-xl smooth-transition">
                        <div class="h-48 bg-gradient-to-br from-navy to-blue-600 flex items-center justify-center">
                            <img src="fot.jpg" alt="Project 3" class="w-full h-48 object-cover">
                        </div>
                        <div class="p-6">
                            <h3 class="text-xl font-semibold text-navy mb-2">Fotografi</h3>
                            <p class="text-gray-600 mb-4"> Dokumenter </p>
                            <div class="flex flex-wrap gap-2">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        
        <section id="tentang" class="section-content hidden min-h-screen bg-gray-50 py-20">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-16 fade-in">
                    <h2 class="text-4xl font-bold text-navy mb-4">Tentang Kami</h2>
                    <p class="text-xl text-gray-600">Tim profesional dengan pengalaman lebih dari 3 tahun</p>
                </div>
                
                <div class="grid lg:grid-cols-2 gap-12 items-center slide-up">
                    <div>
                        <h3 class="text-3xl font-semibold text-navy mb-6">Mengapa Memilih Kami?</h3>
                        <p class="text-gray-600 mb-6 text-lg leading-relaxed">
                            Taksu visual adalah perusahaan teknologi yang berfokus pada pengembangan solusi digital inovatif. 
                            Kami memiliki tim yang berpengalaman dan berkomitmen untuk memberikan hasil terbaik bagi setiap klien.
                        </p>
                        
                        <div class="space-y-4">
                            <div class="flex items-center space-x-4">
                                <div class="w-12 h-12 bg-navy rounded-full flex items-center justify-center">
                                    <svg class="w-6 h-6 text-white" fill="currentColor" viewBox="0 0 24 24">
                                        <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/>
                                    </svg>
                                </div>
                                <div>
                                    <h4 class="text-lg font-semibold text-navy">+ Project Selesai</h4>
                                    <p class="text-gray-600">Dengan tingkat kepuasan klien %</p>
                                </div>
                            </div>
                            
                            <div class="flex items-center space-x-4">
                                <div class="w-12 h-12 bg-navy rounded-full flex items-center justify-center">
                                    <svg class="w-6 h-6 text-white" fill="currentColor" viewBox="0 0 24 24">
                                        <path d="M16 1H4c-1.1 0-2 .9-2 2v14h2V3h12V1zm3 4H8c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h11c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2zm0 16H8V7h11v14z"/>
                                    </svg>
                                </div>
                                <div>
                                    <h4 class="text-lg font-semibold text-navy">Tim Berpengalaman</h4>
                                    <p class="text-gray-600"> dengan sertifikasi internasional</p>
                                </div>
                            </div>
                            
                            <div class="flex items-center space-x-4">
                                <div class="w-12 h-12 bg-navy rounded-full flex items-center justify-center">
                                    <svg class="w-6 h-6 text-white" fill="currentColor" viewBox="0 0 24 24">
                                        <path d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z"/>
                                    </svg>
                                </div>
                                <div>
                                    <h4 class="text-lg font-semibold text-navy">Teknologi Terdepan</h4>
                                    <p class="text-gray-600">Menggunakan software berkulitas</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="bg-white rounded-2xl shadow-xl p-8">
                        <h4 class="text-2xl font-semibold text-navy mb-6 text-center">Statistik Kami</h4>
                        <div class="grid grid-cols-2 gap-6">
                            <div class="text-center">
                                <div class="text-4xl font-bold text-navy mb-2">300+</div>
                                <div class="text-gray-600">Project Selesai</div>
                            </div>
                            <div class="text-center">
                                <div class="text-4xl font-bold text-navy mb-2">200+</div>
                                <div class="text-gray-600">Klien Puas</div>
                            </div>
                            <div class="text-center">
                                <div class="text-4xl font-bold text-navy mb-2">3+</div>
                                <div class="text-gray-600">Tahun Pengalaman</div>
                            </div>
                            <div class="text-center">
                                <div class="text-4xl font-bold text-navy mb-2">24/7</div>
                                <div class="text-gray-600">Support</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

       
        <section id="kontak" class="section-content hidden min-h-screen bg-white py-20">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-16 fade-in">
                    <h2 class="text-4xl font-bold text-navy mb-4">Hubungi Kami</h2>
                    <p class="text-xl text-gray-600">Siap membantu mewujudkan project digital Anda</p>
                </div>
                
                <div class="grid lg:grid-cols-2 gap-12 slide-up">
                    <div>
                        <h3 class="text-2xl font-semibold text-navy mb-6">Informasi Kontak</h3>
                        
                        <div class="space-y-6">
                            <div class="flex items-center space-x-4">
                                <div class="w-12 h-12 bg-navy rounded-full flex items-center justify-center">
                                    <svg class="w-6 h-6 text-white" fill="currentColor" viewBox="0 0 24 24">
                                        <path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/>
                                    </svg>
                                </div>
                                <div>
                                    <h4 class="text-lg font-semibold text-navy">Alamat</h4>
                                    <p class="text-gray-600">Jl.</p>
                                </div>
                            </div>
                            
                            <div class="flex items-center space-x-4">
                                <div class="w-12 h-12 bg-navy rounded-full flex items-center justify-center">
                                    <svg class="w-6 h-6 text-white" fill="currentColor" viewBox="0 0 24 24">
                                        <path d="M6.62 10.79c1.44 2.83 3.76 5.14 6.59 6.59l2.2-2.2c.27-.27.67-.36 1.02-.24 1.12.37 2.33.57 3.57.57.55 0 1 .45 1 1V20c0 .55-.45 1-1 1-9.39 0-17-7.61-17-17 0-.55.45-1 1-1h3.5c.55 0 1 .45 1 1 0 1.25.2 2.45.57 3.57.11.35.03.74-.25 1.02l-2.2 2.2z"/>
                                    </svg>
                                </div>
                                <div>
                                    <h4 class="text-lg font-semibold text-navy">Telepon</h4>
                                    <p class="text-gray-600">+62 81237751682</p>
                                </div>
                            </div>
                            
                            <div class="flex items-center space-x-4">
                                <div class="w-12 h-12 bg-navy rounded-full flex items-center justify-center">
                                    <svg class="w-6 h-6 text-white" fill="currentColor" viewBox="0 0 24 24">
                                        <path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/>
                                    </svg>
                                </div>
                                <div>
                                    <h4 class="text-lg font-semibold text-navy">Email</h4>
                                    <p class="text-gray-600">info@taksuvisual.com</p>
                                </div>
                            </div>
                        </div>
                        
                        <div class="mt-8">
                            <h4 class="text-lg font-semibold text-navy mb-4">Jam Operasional</h4>
                            <div class="space-y-2 text-gray-600">
                                <p> 09:00 - 18:00</p>
                            </div>
                        </div>
                    </div>
                    <div class="bg-gray-50 rounded-2xl p-8">
    <div class="flex justify-center">
        <img src="tv.png2.png" 
             alt="Fotopng" 
             >
    </div>
</div>

                </div>
            </div>
        </section>
    </main>

   
    <footer class="bg-navy text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-4 gap-8">
                <div>
                    <div class="flex items-center space-x-3 mb-4">
                        <div class="w-8 h-8 bg-white rounded-lg flex items-center justify-center">
                            <svg class="w-6 h-6 text-navy" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 2L2 7v10c0 5.55 3.84 9.74 9 11 5.16-1.26 9-5.45 9-11V7l-10-5z"/>
                            </svg>
                        </div>
                        <span class="text-lg font-bold">Taksu visual</span>
                    </div>
                    <p class="text-blue-200">Solusi digital terpercaya untuk kemajuan bisnis Anda.</p>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Layanan</h4>
                    <ul class="space-y-2 text-blue-200">
                        <li><a href="#" onclick="showSection('layanan')" class="hover:text-white smooth-transition">Fotografi</a></li>
                        <li><a href="#" onclick="showSection('layanan')" class="hover:text-white smooth-transition">Design Grafis</a></li>
                        <li><a href="#" onclick="showSection('layanan')" class="hover:text-white smooth-transition">Editing</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Perusahaan</h4>
                    <ul class="space-y-2 text-blue-200">
                        <li><a href="#" onclick="showSection('tentang')" class="hover:text-white smooth-transition">Tentang Kami</a></li>
                        <li><a href="#" onclick="showSection('portofolio')" class="hover:text-white smooth-transition">Portofolio</a></li>
                        <li><a href="#" onclick="showSection('kontak')" class="hover:text-white smooth-transition">Kontak</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Ikuti Kami</h4>
                    <div class="flex space-x-4">
                        <a href="https://www.tiktok.com/@taksuvisualdigital?_t=ZS-8zsM6kY2As6&_r=1" class="w-10 h-10 bg-white/20 rounded-full flex items-center justify-center hover:bg-white/30 smooth-transition">
                           <img src="tiktok.png" alt="button desain grafis" class="w-8 h-8 object-contain">
                        </a>
                        <a href="https://www.instagram.com/taksuvisyal?igsh=MTZjNmk5ZXkzd2lkZw==" class="w-10 h-10 bg-white/20 rounded-full flex items-center justify-center hover:bg-white/30 smooth-transition">
                           <img src="ig.png" alt="button desain grafis" class="w-8 h-8 object-contain">
                        </a>
                        
                    </div>
                </div>
            </div>
            
            <div class="border-t border-blue-800 mt-8 pt-8 text-center text-blue-200">
                <p>&copy; 2024 Taksu visual. Semua hak dilindungi.</p>
            </div>
        </div>
    </footer>

    <script>
 
        function showSection(sectionName) {
          
            const sections = document.querySelectorAll('.section-content');
            sections.forEach(section => {
                section.classList.add('hidden');
            });
            
            // Show selected section
            const targetSection = document.getElementById(sectionName);
            if (targetSection) {
                targetSection.classList.remove('hidden');
                
            
                const fadeElements = targetSection.querySelectorAll('.fade-in');
                const slideElements = targetSection.querySelectorAll('.slide-up');
                
                fadeElements.forEach((el, index) => {
                    el.style.animationDelay = `${index * 0.1}s`;
                });
                
                slideElements.forEach((el, index) => {
                    el.style.animationDelay = `${index * 0.2}s`;
                });
            }
            
           
            const navLinks = document.querySelectorAll('.nav-link');
            navLinks.forEach(link => {
                link.classList.remove('text-blue-200');
                link.classList.add('text-white');
            });
            
         
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        
        function toggleMobileMenu() {
            const mobileMenu = document.getElementById('mobileMenu');
            mobileMenu.classList.toggle('hidden');
        }

        function handleFormSubmit(event) {
            event.preventDefault();
            
            alert('Terima kasih! Pesan Anda telah dikirim. Tim kami akan segera menghubungi Anda.');
            
            event.target.reset();
        }

        document.addEventListener('DOMContentLoaded', function() {
            showSection('beranda');
            
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    const target = document.querySelector(this.getAttribute('href'));
                    if (target) {
                        target.scrollIntoView({
                            behavior: 'smooth',
                            block: 'start'
                        });
                    }
                });
            });
        });

        window.addEventListener('scroll', function() {
            const navbar = document.querySelector('nav');
            if (window.scrollY > 50) {
                navbar.classList.add('shadow-xl');
            } else {
                navbar.classList.remove('shadow-xl');
            }
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'97fb3b10072ffd13',t:'MTc1Nzk3MTg4My4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
