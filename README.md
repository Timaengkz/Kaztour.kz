<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KazTour Adventures - Explore Kazakhstan</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body class="font-poppins bg-gray-50">
    <custom-navbar></custom-navbar>
    
    <main>
        <!-- Hero Section -->
        <section class="relative h-screen flex items-center justify-center bg-gradient-to-r from-blue-900 to-blue-700 overflow-hidden">
            <div class="absolute inset-0 bg-black opacity-40"></div>
            <video autoplay muted loop class="absolute w-full h-full object-cover">
                <source src="https://assets.mixkit.co/videos/preview/mixkit-woman-walking-on-a-mountain-while-admiring-the-view-39800-large.mp4" type="video/mp4">
            </video>
            <div class="relative z-10 text-center px-4 max-w-4xl mx-auto">
                <h1 class="text-4xl md:text-6xl font-bold text-white font-playfair mb-6">Discover Kazakhstan's Hidden Gems</h1>
                <p class="text-xl text-white mb-8">Explore breathtaking landscapes, rich culture, and unforgettable adventures with our curated tours</p>
                <a href="/tours.html" class="bg-amber-500 hover:bg-amber-600 text-white font-bold py-3 px-8 rounded-full text-lg transition duration-300 inline-flex items-center">
                    Explore Tours <i data-feather="arrow-right" class="ml-2"></i>
                </a>
            </div>
        </section>

        <!-- Featured Tours -->
        <section class="py-16 px-4 max-w-7xl mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 font-playfair mb-4">Featured Tours</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Our most popular adventures handpicked for you</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Tour Card 1 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transition-transform duration-300 hover:scale-105">
                    <div class="relative h-64">
                        <img src="http://static.photos/nature/640x360/1" alt="Almaty Mountains" class="w-full h-full object-cover">
                        <div class="absolute top-4 right-4 bg-amber-500 text-white px-3 py-1 rounded-full text-sm font-bold">Popular</div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="text-xl font-bold text-gray-800">Almaty Mountain Escape</h3>
                            <span class="text-amber-500 font-bold">$599</span>
                        </div>
                        <p class="text-gray-600 mb-4">5-day adventure in the Tien Shan mountains</p>
                        <div class="flex items-center text-gray-500 mb-4">
                            <i data-feather="map-pin" class="mr-2"></i>
                            <span>Almaty Region</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <div class="flex items-center">
                                <i data-feather="star" class="text-amber-400 mr-1"></i>
                                <span class="font-bold">4.8</span>
                                <span class="text-gray-500 ml-1">(124)</span>
                            </div>
                            <a href="/tour-detail.html" class="text-blue-600 hover:text-blue-800 font-medium">View Details</a>
                        </div>
                    </div>
                </div>

                <!-- Tour Card 2 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transition-transform duration-300 hover:scale-105">
                    <div class="relative h-64">
                        <img src="http://static.photos/travel/640x360/2" alt="Charyn Canyon" class="w-full h-full object-cover">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="text-xl font-bold text-gray-800">Charyn Canyon Expedition</h3>
                            <span class="text-amber-500 font-bold">$349</span>
                        </div>
                        <p class="text-gray-600 mb-4">3-day exploration of Kazakhstan's Grand Canyon</p>
                        <div class="flex items-center text-gray-500 mb-4">
                            <i data-feather="map-pin" class="mr-2"></i>
                            <span>Almaty Region</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <div class="flex items-center">
                                <i data-feather="star" class="text-amber-400 mr-1"></i>
                                <span class="font-bold">4.9</span>
                                <span class="text-gray-500 ml-1">(87)</span>
                            </div>
                            <a href="/tour-detail.html" class="text-blue-600 hover:text-blue-800 font-medium">View Details</a>
                        </div>
                    </div>
                </div>

                <!-- Tour Card 3 -->
                <div class="bg-white rounded-xl shadow-lg overflow-hidden transition-transform duration-300 hover:scale-105">
                    <div class="relative h-64">
                        <img src="http://static.photos/cityscape/640x360/3" alt="Astana City" class="w-full h-full object-cover">
                        <div class="absolute top-4 right-4 bg-blue-500 text-white px-3 py-1 rounded-full text-sm font-bold">New</div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-start mb-2">
                            <h3 class="text-xl font-bold text-gray-800">Astana Modern Marvels</h3>
                            <span class="text-amber-500 font-bold">$279</span>
                        </div>
                        <p class="text-gray-600 mb-4">2-day cultural tour of Kazakhstan's capital</p>
                        <div class="flex items-center text-gray-500 mb-4">
                            <i data-feather="map-pin" class="mr-2"></i>
                            <span>Astana</span>
                        </div>
                        <div class="flex justify-between items-center">
                            <div class="flex items-center">
                                <i data-feather="star" class="text-amber-400 mr-1"></i>
                                <span class="font-bold">4.7</span>
                                <span class="text-gray-500 ml-1">(56)</span>
                            </div>
                            <a href="/tour-detail.html" class="text-blue-600 hover:text-blue-800 font-medium">View Details</a>
                        </div>
                    </div>
                </div>
            </div>

            <div class="text-center mt-12">
                <a href="/tours.html" class="inline-flex items-center text-blue-600 hover:text-blue-800 font-medium text-lg">
                    View All Tours <i data-feather="arrow-right" class="ml-2"></i>
                </a>
            </div>
        </section>

        <!-- Why Choose Us -->
        <section class="py-16 bg-gray-100">
            <div class="max-w-7xl mx-auto px-4">
                <div class="text-center mb-12">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-800 font-playfair mb-4">Why Choose KazTour</h2>
                    <p class="text-gray-600 max-w-2xl mx-auto">We're committed to providing unforgettable experiences</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="bg-white p-8 rounded-xl shadow-md text-center">
                        <div class="bg-blue-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i data-feather="award" class="text-blue-600 w-8 h-8"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Local Experts</h3>
                        <p class="text-gray-600">Our guides are born and raised in Kazakhstan with deep knowledge of local culture and history.</p>
                    </div>

                    <div class="bg-white p-8 rounded-xl shadow-md text-center">
                        <div class="bg-amber-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i data-feather="heart" class="text-amber-600 w-8 h-8"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Sustainable Tourism</h3>
                        <p class="text-gray-600">We prioritize eco-friendly practices and support local communities.</p>
                    </div>

                    <div class="bg-white p-8 rounded-xl shadow-md text-center">
                        <div class="bg-green-100 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                            <i data-feather="shield" class="text-green-600 w-8 h-8"></i>
                        </div>
                        <h3 class="text-xl font-bold mb-3">Safety First</h3>
                        <p class="text-gray-600">All our tours meet the highest safety standards with certified equipment and procedures.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Testimonials -->
        <section class="py-16 px-4 max-w-7xl mx-auto">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-800 font-playfair mb-4">Traveler Stories</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">What our adventurers say about their experiences</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-white p-8 rounded-xl shadow-md">
                    <div class="flex items-center mb-4">
                        <img src="http://static.photos/people/200x200/1" alt="Sarah Johnson" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="
</body>
</html> 
