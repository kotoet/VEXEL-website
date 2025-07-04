<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VEXEL Japan Guide - Discover Japan from a New Perspective.</title>
    <meta name="description" content="VEXEL Japan Guide offers personalized local guiding services by university students and experienced private guides. Discover Tokyo's hidden gems and create unforgettable travel experiences. We focus on guiding; accommodation and transportation are not arranged.">
    <!-- Tailwind CSS CDN for modern styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        /* Basic custom styles, primarily for font and scroll behavior, remaining largely Tailwind for responsive design */
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
        .scroll-to-section:hover {
            color: #A6D4EF; /* Light blue from logo */
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header Section -->
    <header class="bg-gradient-to-r from-[#423271] to-[#2B2149] text-white py-6 shadow-lg">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center justify-between">
            <div class="flex items-center mb-4 md:mb-0">
                <!-- VEXEL Japan Guide Logo (top of the page) -->
                <img src="https://content-fetcher.sandbox.google.com/item?id=uploaded:vexel%20logo.jpg-94e58b24-fd48-4220-b107-b5bb2bfe0278" alt="VEXEL Japan Guide Logo" class="h-16 md:h-20 mr-4">
                <div class="text-center md:text-left">
                    <h1 class="text-4xl font-bold tracking-tight text-white">VEXEL</h1>
                    <p class="text-lg mt-1 text-gray-300">Japan Guide</p>
                </div>
            </div>
            <nav>
                <ul class="flex flex-wrap justify-center md:justify-end space-x-4 md:space-x-6 text-lg">
                    <li><a href="#home" class="scroll-to-section text-white hover:text-[#A6D4EF] transition-colors duration-300">Home</a></li>
                    <li><a href="#about" class="scroll-to-section text-white hover:text-[#A6D4EF] transition-colors duration-300">Our Services</a></li>
                    <li><a href="#student-tours" class="scroll-to-section text-white hover:text-[#A6D4EF] transition-colors duration-300">Student Tours</a></li>
                    <li><a href="#private-tours" class="scroll-to-section text-white hover:text-[#A6D4EF] transition-colors duration-300">Private Tours</a></li>
                    <li><a href="#custom-tours" class="scroll-to-section text-white hover:text-[#A6D4EF] transition-colors duration-300">Custom Tours</a></li>
                    <li><a href="#faq" class="scroll-to-section text-white hover:text-[#A6D4EF] transition-colors duration-300">FAQ</a></li>
                    <li><a href="#contact" class="scroll-to-section text-white hover:text-[#A6D4EF] transition-colors duration-300">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="relative bg-gradient-to-br from-[#A6D4EF] to-[#F0B4C8] text-gray-900 py-20 md:py-32 flex items-center justify-center min-h-[50vh]">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-5xl md:text-6xl font-extrabold leading-tight mb-6">Your Journey, Our Expertise.</h2>
            <p class="text-xl md:text-2xl mb-8 max-w-3xl mx-auto">VEXEL Japan Guide offers personalized local guiding services for visitors eager to experience the depths of Japanese culture and daily life.</p>
            <a href="#contact" class="inline-block bg-white text-[#593E91] font-bold py-3 px-8 rounded-full shadow-lg hover:bg-gray-100 transition-colors duration-300 text-lg md:text-xl">Book Your Unforgettable Tour Now</a>
        </div>
    </section>

    <!-- Our Services Section -->
    <section id="about" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-gray-900 mb-10 text-center">Our Services</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
                <div class="bg-indigo-50 p-8 rounded-lg shadow-md hover:shadow-xl transition-shadow duration-300">
                    <h3 class="text-2xl font-semibold text-[#5D6BBA] mb-4">Personalized Guiding by University Volunteers</h3>
                    <p class="text-lg text-gray-700 mb-4">Experience real insights into Japanese daily life from a local perspective. Our university student guides offer fresh, passionate perspectives on Tokyo's hidden gems and vibrant youth culture.</p>
                    <p class="text-md text-gray-600 font-medium"><strong>Free-Pricing System:</strong> After the tour, you pay what you feel the experience was worth. This unique system encourages authentic interaction and ensures your satisfaction.</p>
                </div>
                <div class="bg-purple-50 p-8 rounded-lg shadow-md hover:shadow-xl transition-shadow duration-300">
                    <h3 class="text-2xl font-semibold text-[#8B5F9B] mb-4">High-Quality Private Tours by Dedicated Guides</h3>
                    <p class="text-lg text-gray-700 mb-4">For those seeking a deeper, more refined exploration. Our expert guides provide meticulous care, specialized knowledge, and an exclusive experience tailored just for your special time in Tokyo.</p>
                    <p class="text-md text-gray-600 font-medium"><strong>Pre-set Pricing:</strong> Enjoy peace of mind with clear, upfront pricing. Our dedicated guides ensure a premium, personalized journey into Japan's culture and heritage.</p>
                </div>
                <div class="bg-blue-50 p-8 rounded-lg shadow-md hover:shadow-xl transition-shadow duration-300">
                    <h3 class="text-2xl font-semibold text-[#593E91] mb-4">Custom-Made Tours: Your Japan, Your Way.</h3>
                    <p class="text-lg text-gray-700 mb-4">For the ultimate personalized journey, our Custom-Made Tours are designed from scratch around your unique interests, passions, and pace. Let us transform your unique ideas into an unforgettable Japanese adventure.</p>
                    <p class="text-md text-gray-600 font-medium"><strong>Tailored Experiences:</strong> Explore niche subcultures, delve into specific historical periods, or pursue unique hobbies. Your dream itinerary, crafted by our experts.</p>
                </div>
            </div>

            <div class="mt-16 text-center">
                <h3 class="text-3xl font-bold text-gray-900 mb-6">How Your VEXEL Japan Guide Journey Works</h3>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-left">
                    <div class="bg-gray-100 p-6 rounded-lg shadow-sm">
                        <div class="text-[#5D6BBA] text-4xl mb-3 font-bold">1.</div>
                        <h4 class="text-xl font-semibold text-gray-900 mb-2">Inquiry & Customization</h4>
                        <p class="text-gray-700">Tell us your interests and preferred tour type through our easy online form. For private tours, we'll design a bespoke itinerary tailored to your desires.</p>
                    </div>
                    <div class="bg-gray-100 p-6 rounded-lg shadow-sm">
                        <div class="text-[#5D6BBA] text-4xl mb-3 font-bold">2.</div>
                        <h4 class="text-xl font-semibold text-gray-900 mb-2">Guide Assignment & Confirmation</h4>
                        <p class="text-gray-700">We'll connect you with the perfect student or dedicated private guide. Once you're satisfied with the plan and guide, your booking is confirmed.</p>
                    </div>
                    <div class="bg-gray-100 p-6 rounded-lg shadow-sm">
                        <div class="text-[#5D6BBA] text-4xl mb-3 font-bold">3.</div>
                        <h4 class="text-xl font-semibold text-gray-900 mb-2">Experience & Discovery</h4>
                        <p class="text-gray-700">Meet your guide at the designated spot, and embark on your unique adventure. Explore hidden gems and authentic culture, guided by local expertise.</p>
                    </div>
                </div>
                <p class="mt-8 text-gray-700 text-lg font-semibold">Please note: VEXEL Japan Guide focuses solely on guiding services. We do not arrange accommodation, transportation, or pre-purchase entry tickets/food/drinks. These costs are paid by the customer directly on-site.</p>
            </div>
        </div>
    </section>

    <!-- Student Community Tours Section -->
    <section id="student-tours" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-gray-900 mb-10 text-center">Student Community Tours <span class="text-[#5D6BBA]">(Free-Pricing System)</span></h2>
            <p class="text-lg text-gray-700 mb-8 text-center max-w-3xl mx-auto">Our vibrant university student guides offer unique, local perspectives on Tokyo. Experience authentic culture, engage in real interactions, and at the end of your tour, you decide what you'd like to pay based on the value you received. All tours are approximately 3 hours.</p>

            <!-- Student Day Tours Sub-section -->
            <h3 class="text-3xl font-bold text-gray-800 mb-8 text-center">Student Day Tours</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mb-16">
                <!-- Student Tour Card 1 (Day) -->
                <div class="bg-white rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col">
                    <h3 class="text-2xl font-semibold text-[#5D6BBA] mb-3">Ura-Harajuku & Omotesando Street Culture Exploration</h3>
                    <p class="text-gray-700 mb-4 flex-grow">Discover Tokyo's youth culture hub. Our student guides will show you the latest fashion trends, unique shops, and hidden cafes, along with popular photo spots in Harajuku and Omotesando.</p>
                    <ul class="text-gray-600 text-sm list-disc list-inside mt-auto">
                        <li><strong>Duration:</strong> Approx. 3 hours</li>
                        <li><strong>Area:</strong> Harajuku, Omotesando</li>
                        <li><strong>Key Experiences:</strong> Takeshita Street, Cat Street, Ura-Harajuku select shops, trendy cafes (payment separate)</li>
                    </ul>
                    <div class="mt-4">
                        <button onclick="bookStudentTour('Ura-Harajuku & Omotesando Street Culture Exploration')" class="bg-[#5D6BBA] text-white text-center font-bold py-2 px-4 rounded-full hover:bg-[#4E5A9D] transition-colors duration-300 text-sm w-full">Book Now</button>
                    </div>
                </div>
                <!-- Student Tour Card 3 (Day) -->
                <div class="bg-white rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col">
                    <h3 class="text-2xl font-semibold text-[#5D6BBA] mb-3">Modern Tokyo: Shibuya Scramble Crossing to Latest Trends</h3>
                    <p class="text-gray-700 mb-4 flex-grow">Starting from the world-famous Shibuya Scramble Crossing, experience modern Tokyo where cutting-edge fashion, technology, and youth energy converge.</p>
                    <ul class="text-gray-600 text-sm list-disc list-inside mt-auto">
                        <li><strong>Duration:</strong> Approx. 3 hours</li>
                        <li><strong>Area:</strong> Shibuya</li>
                        <li><strong>Key Experiences:</strong> Shibuya Scramble Crossing experience, Shibuya Scramble Square observation deck (admission separate), Shibuya Center Gai, youth culture</li>
                    </ul>
                    <div class="mt-4">
                        <button onclick="bookStudentTour('Modern Tokyo: Shibuya Scramble Crossing to Latest Trends')" class="bg-[#5D6BBA] text-white text-center font-bold py-2 px-4 rounded-full hover:bg-[#4E5A9D] transition-colors duration-300 text-sm w-full">Book Now</button>
                    </div>
                </div>
            </div>

            <!-- Student Night Tours Sub-section -->
            <h3 class="text-3xl font-bold text-gray-800 mb-8 text-center">Student Night Tours</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Student Tour Card 4 (Night) -->
                <div class="bg-white rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col">
                    <h3 class="text-2xl font-semibold text-[#5D6BBA] mb-3">Shinjuku Golden Gai & Omoide Yokocho Retro Izakaya Experience </h3>
                    <p class="text-gray-700 mb-4 flex-grow">Experience the chaotic charm of Shinjuku's nightlife. Visit small izakayas in Omoide Yokocho and unique bars in Golden Gai. Your student guide will help you experience a deeper side of Tokyo's night.</p>
                    <ul class="text-gray-600 text-sm list-disc list-inside mt-auto">
                        <li><strong>Duration:</strong> Approx. 3 hours</li>
                        <li><strong>Area:</strong> Shinjuku</li>
                        <li><strong>Key Experiences:</strong> Omoide Yokocho & Golden Gai exploration, drinks & food at izakayas/bars (payment separate)</li>
                    </ul>
                    <div class="mt-4">
                        <button onclick="bookStudentTour('Shinjuku Golden Gai & Omoide Yokocho Retro Izakaya Experience (Night)')" class="bg-[#5D6BBA] text-white text-center font-bold py-2 px-4 rounded-full hover:bg-[#4E5A9D] transition-colors duration-300 text-sm w-full">Book Now</button>
                    </div>
                </div>
                <!-- Student Tour Card: Shimokitazawa (re-added) -->
                <div class="bg-white rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col">
                    <h3 class="text-2xl font-semibold text-[#5D6BBA] mb-3">Shimokitazawa Subculture & Unique Bar Hopping </h3>
                    <p class="text-gray-700 mb-4 flex-grow">Explore Shimokitazawa, a hub for youth culture and subcultures. Visit vintage shops, live houses, and unique bars, experiencing the area's artistic vibe.</p>
                    <ul class="text-gray-600 text-sm list-disc list-inside mt-auto">
                        <li><strong>Duration:</strong> Approx. 3 hours</li>
                        <li><strong>Area:</strong> Shimokitazawa</li>
                        <li><strong>Key Experiences:</strong> Subculture exploration, hidden bars, vintage shops, music & art spots (drinks & food separate)</li>
                    </ul>
                    <div class="mt-4">
                        <button onclick="bookStudentTour('Shimokitazawa Subculture & Unique Bar Hopping (Night)')" class="bg-[#5D6BBA] text-white text-center font-bold py-2 px-4 rounded-full hover:bg-[#4E5A9D] transition-colors duration-300 text-sm w-full">Book Now</button>
                    </div>
                </div>
                <!-- Student Tour Card 5 (Night) -->
                <div class="bg-white rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col">
                    <h3 class="text-2xl font-semibold text-[#5D6BBA] mb-3">Shibuya Youth Nightlife Spot Hopping</h3>
                    <p class="text-700 mb-4 flex-grow">From the bustling Shibuya Center Gai, the heart of youth culture, to the more relaxed "Oku-Shibuya," experience the diverse nightlife of modern Tokyo with a student guide.</p>
                    <ul class="text-gray-600 text-sm list-disc list-inside mt-auto">
                        <li><strong>Duration:</strong> Approx. 3 hours</li>
                        <li><strong>Area:</b> Shibuya</li>
                        <li><strong>Key Experiences:</b> Center Gai, Oku-Shibuya exploration, trendy spots, casual bars (drinks & food separate)</li>
                    </ul>
                    <div class="mt-4">
                        <button onclick="bookStudentTour('Shibuya Youth Nightlife Spot Hopping (Night)')" class="bg-[#5D6BBA] text-white text-center font-bold py-2 px-4 rounded-full hover:bg-[#4E5A9D] transition-colors duration-300 text-sm w-full">Book Now</button>
                    </div>
                </div>
                <!-- Kichijoji Night Tour Card -->
                <div class="bg-white rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col">
                    <h3 class="text-2xl font-semibold text-[#5D6BBA] mb-3">Kichijoji Night: Izakaya Alley & Local Hangouts </h3>
                    <p class="text-gray-700 mb-4 flex-grow">Discover Kichijoji's lively and eclectic nightlife, a popular hub for students and young adults. This tour focuses on popular izakayas, quirky bars, and the vibrant atmosphere around Kichijoji Station.</p>
                    <ul class="text-gray-600 text-sm list-disc list-inside mt-auto">
                        <li><strong>Duration:</strong> Approx. 3 hours</li>
                        <li><strong>Area:</strong> Kichijoji</li>
                        <li><strong>Key Experiences:</strong> Harmonica Yokocho, student-frequented izakayas, local bars, Kichijoji's unique blend of urban cool (drinks & food separate)</li>
                    </ul>
                    <div class="mt-4">
                        <button onclick="bookStudentTour('Kichijoji Night: Izakaya Alley & Local Hangouts (Night)')" class="bg-[#5D6BBA] text-white text-center font-bold py-2 px-4 rounded-full hover:bg-[#4E5A9D] transition-colors duration-300 text-sm w-full">Book Now</button>
                    </div>
                </div>
            </div>
            <div class="call-to-action mt-10 text-center">
                <a href="#contact" class="inline-block bg-[#5D6BBA] text-white font-bold py-3 px-8 rounded-full shadow-lg hover:bg-[#4E5A9D] transition-colors duration-300 text-lg">Inquire About Student Tours</a>
            </div>
        </section>

    <!-- Private Quality Tours Section -->
    <section id="private-tours" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-gray-900 mb-10 text-center">Private Quality Tours <span class="text-[#8B5F9B]">(Pre-set Pricing)</span></h2>
            <p class="text-lg text-gray-700 mb-8 text-center max-w-3xl mx-auto">Our experienced, dedicated guides provide a deeper, more refined exploration of Tokyo's charms, tailored exclusively for you. Enjoy a premium, personalized journey with clear, upfront pricing. All tours are approximately 3 hours.</p>

            <!-- Private Day Tours Sub-section -->
            <h3 class="text-3xl font-bold text-gray-800 mb-8 text-center">Private Day Tours</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mb-16">
                <!-- Private Tour Card 1 (Day) -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col">
                    <h4 class="text-2xl font-semibold text-[#8B5F9B] mb-3">Ginza Day Tour: "The Art of Elegance & Hidden Craftsmanship"</h4>
                    <p class="text-gray-700 mb-4 flex-grow">A sophisticated journey through Ginza's refined aesthetics, exploring its historical foundations, unique architecture, and exquisite traditional crafts that thrive in this modern district.</p>
                    <ul class="text-gray-600 text-sm list-disc list-inside mt-auto">
                        <li><strong>Price:</strong> ¥20,000</li>
                        <li><strong>Duration:</strong> Approx. 3 hours</li>
                        <li><strong>Area:</strong> Ginza</li>
                        <li><strong>Key Experiences:</strong> Wako Clock Tower, Ando Cloisonné, Ginza Kuroda Touen, Kagami Crystal, Kabuki-za (exterior)</li>
                    </ul>
                    <div class="mt-4 flex flex-col space-y-2">
                        <a href="YOUR_STRIPE_CHECKOUT_URL_GINZA_DAY" target="_blank" class="bg-[#8B5F9B] text-white text-center font-bold py-2 px-4 rounded-full hover:bg-[#724E82] transition-colors duration-300 text-sm">Book & Pay Now (Credit Card)</a>
                        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top" class="w-full">
                            <input type="hidden" name="cmd" value="_xclick">
                            <input type="hidden" name="business" value="YOUR_PAYPAL_BUSINESS_EMAIL@example.com">
                            <input type="hidden" name="item_name" value="Ginza Day Tour: Art & Craftsmanship">
                            <input type="hidden" name="amount" value="PRICE_GINZA_DAY"> <!-- Replace with actual price -->
                            <input type="hidden" name="currency_code" value="USD">
                            <input type="hidden" name="return" value="https://yourwebsite.com/payment-success.html">
                            <input type="hidden" name="cancel_return" value="https://yourwebsite.com/payment-cancel.html">
                            <input type="hidden" name="button_subtype" value="services">
                            <input type="hidden" name="no_shipping" value="1">
                            <input type="hidden" name="no_note" value="1">
                            <input type="hidden" name="lc" value="US">
                            <input type="hidden" name="bn" value="PP-BuyNowBF">
                            <button type="submit" class="bg-blue-600 text-white text-center font-bold py-2 px-4 rounded-full hover:bg-blue-700 transition-colors duration-300 text-sm w-full">Pay with PayPal</button>
                        </form>
                    </div>
                </div>
                <!-- Private Tour Card 3 (Day) -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col">
                    <h4 class="text-2xl font-semibold text-[#8B5F9B] mb-3">Asakusa Day Tour: "Echoes of Edo & Artisans' Spirit"</h4>
                    <p class="text-gray-700 mb-4 flex-grow">Go beyond the bustling Nakamise-dori to uncover the deeper layers of Asakusa's history, spiritual significance, and living traditions through serene areas and local craftsmanship.</p>
                    <ul class="text-gray-600 text-sm list-disc list-inside mt-auto">
                        <li><strong>Price:</strong> ¥18,000</li>
                        <li><strong>Duration:</strong> Approx. 3 hours</li>
                        <li><strong>Area:</strong> Asakusa</li>
                        <li><strong>Key Experiences:</strong> Asakusa Culture Tourist Info Center (view), Kaminarimon, Senso-ji Temple, Oku-Asakusa, traditional craft shops, Kappabashi (optional)</li>
                    </ul>
                    <div class="mt-4 flex flex-col space-y-2">
                        <a href="YOUR_STRIPE_CHECKOUT_URL_ASAKUSA_DAY" target="_blank" class="bg-[#8B5F9B] text-white text-center font-bold py-2 px-4 rounded-full hover:bg-[#724E82] transition-colors duration-300 text-sm">Book & Pay Now (Credit Card)</a>
                        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top" class="w-full">
                            <input type="hidden" name="cmd" value="_xclick">
                            <input type="hidden" name="business" value="YOUR_PAYPAL_BUSINESS_EMAIL@example.com">
                            <input type="hidden" name="item_name" value="Asakusa Day Tour: Edo & Artisans">
                            <input type="hidden" name="amount" value="PRICE_ASAKUSA_DAY"> <!-- Replace with actual price -->
                            <input type="hidden" name="currency_code" value="USD">
                            <input type="hidden" name="return" value="https://yourwebsite.com/payment-success.html">
                            <input type="hidden" name="cancel_return" value="https://yourwebsite.com/payment-cancel.html">
                            <input type="hidden" name="button_subtype" value="services">
                            <input type="hidden" name="no_shipping" value="1">
                            <input type="hidden" name="no_note" value="1">
                            <input type="hidden" name="lc" value="US">
                            <input type="hidden" name="bn" value="PP-BuyNowBF">
                            <button type="submit" class="bg-blue-600 text-white text-center font-bold py-2 px-4 rounded-full hover:bg-blue-700 transition-colors duration-300 text-sm w-full">Pay with PayPal</button>
                        </form>
                    </div>
                </div>
                <!-- Private Tour Card 4 (Day) -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col">
                    <h4 class="text-2xl font-semibold text-[#8B5F9B] mb-3">Imperial Palace Day Tour: "Guardians of History & Imperial Serenity"</h4>
                    <p class="text-gray-700 mb-4 flex-grow">Journey into the heart of Tokyo's imperial legacy, exploring the serene East Garden of the Imperial Palace and its surrounding historical sites, unraveling centuries of Japanese history.</p>
                    <ul class="text-gray-600 text-sm list-disc list-inside mt-auto">
                        <li><strong>Price:</strong> ¥15,000</li>
                        <li><strong>Duration:</strong> Approx. 3 hours</li>
                        <li><strong>Area:</strong> Imperial Palace East Garden & Outer Area</li>
                        <li><strong>Key Experiences:</strong> Otemon Gate, Edo Castle Keep, Ninmaru Garden, Nijubashi Bridge, Kitanomaru Park, Nippon Budokan (exterior)</li>
                    </ul>
                    <div class="mt-4 flex flex-col space-y-2">
                        <a href="YOUR_STRIPE_CHECKOUT_URL_IMPERIAL_PALACE_DAY" target="_blank" class="bg-[#8B5F9B] text-white text-center font-bold py-2 px-4 rounded-full hover:bg-[#724E82] transition-colors duration-300 text-sm">Book & Pay Now (Credit Card)</a>
                        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top" class="w-full">
                            <input type="hidden" name="cmd" value="_xclick">
                            <input type="hidden" name="business" value="YOUR_PAYPAL_BUSINESS_EMAIL@example.com">
                            <input type="hidden" name="item_name" value="Imperial Palace Day Tour">
                            <input type="hidden" name="amount" value="PRICE_IMPERIAL_PALACE_DAY"> <!-- Replace with actual price -->
                            <input type="hidden" name="currency_code" value="USD">
                            <input type="hidden" name="return" value="https://yourwebsite.com/payment-success.html">
                            <input type="hidden" name="cancel_return" value="https://yourwebsite.com/payment-cancel.html">
                            <input type="hidden" name="button_subtype" value="services">
                            <input type="hidden" name="no_shipping" value="1">
                            <input type="hidden" name="no_note" value="1">
                            <input type="hidden" name="lc" value="US">
                            <input type="hidden" name="bn" value="PP-BuyNowBF">
                            <button type="submit" class="bg-blue-600 text-white text-center font-bold py-2 px-4 rounded-full hover:bg-blue-700 transition-colors duration-300 text-sm w-full">Pay with PayPal</button>
                        </form>
                    </div>
                </div>
                <!-- Private Tour Card 7 (Day) -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col">
                    <h4 class="text-2xl font-semibold text-[#8B5F9B] mb-3">Kagurazaka Day Tour: "Whispers of Geisha & Elegant Enclaves"</h4>
                    <p class="text-gray-700 mb-4 flex-grow">Step back in time to explore Kagurazaka, Tokyo's charming "geisha district." Wander its stone-paved alleys, discover hidden temples, traditional shops, and delve into its rich history.</p>
                    <ul class="text-gray-600 text-sm list-disc list-inside mt-auto">
                        <li><strong>Price:</strong> ¥15,000</li>
                        <li><strong>Duration:</strong> Approx. 3 hours</li>
                        <li><strong>Area:</strong> Kagurazaka</li>
                        <li><strong>Key Experiences:</strong> Kagurazaka-dori, Hyogo Yokocho, Bishamonten Zenkoku-ji Temple, Akagi Shrine, traditional shops, ryotei exteriors (refreshment separate)</li>
                    </ul>
                    <div class="mt-4 flex flex-col space-y-2">
                        <a href="YOUR_STRIPE_CHECKOUT_URL_KAGURAZAKA_DAY" target="_blank" class="bg-[#8B5F9B] text-white text-center font-bold py-2 px-4 rounded-full hover:bg-[#724E82] transition-colors duration-300 text-sm">Book & Pay Now (Credit Card)</a>
                        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top" class="w-full">
                            <input type="hidden" name="cmd" value="_xclick">
                            <input type="hidden" name="business" value="YOUR_PAYPAL_BUSINESS_EMAIL@example.com">
                            <input type="hidden" name="item_name" value="Kagurazaka Day Tour">
                            <input type="hidden" name="amount" value="PRICE_KAGURAZAKA_DAY"> <!-- Replace with actual price -->
                            <input type="hidden" name="currency_code" value="USD">
                            <input type="hidden" name="return" value="https://yourwebsite.com/payment-success.html">
                            <input type="hidden" name="cancel_return" value="https://yourwebsite.com/payment-cancel.html">
                            <input type="hidden" name="button_subtype" value="services">
                            <input type="hidden" name="no_shipping" value="1">
                            <input type="hidden" name="no_note" value="1">
                            <input type="hidden" name="lc" value="US">
                            <input type="hidden" name="bn" value="PP-BuyNowBF">
                            <button type="submit" class="bg-blue-600 text-white text-center font-bold py-2 px-4 rounded-full hover:bg-blue-700 transition-colors duration-300 text-sm w-full">Pay with PayPal</button>
                        </form>
                    </div>
                </div>
            </div>

            <!-- Private Night Tours Sub-section -->
            <h3 class="text-3xl font-bold text-gray-800 mb-8 text-center">Private Night Tours</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Private Tour Card 2 (Night) -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col">
                    <h4 class="text-2xl font-semibold text-[#8B5F9B] mb-3">Ginza Night Tour: "Tokyo's Liquid Gold: Bespoke Bar Hopping"</h4>
                    <p class="text-gray-700 mb-4 flex-grow">Experience Ginza's sophisticated nocturnal allure. This tour focuses on its stunning illuminations, high-end bar culture, offering premium Japanese spirits and bespoke cocktails in intimate settings.</p>
                    <ul class="text-gray-600 text-sm list-disc list-inside mt-auto">
                        <li><strong>Price:</strong> ¥26,000</li>
                        <li><strong>Duration:</strong> Approx. 3 hours</li>
                        <li><strong>Area:</strong> Ginza</li>
                        <li><strong>Key Experiences:</strong> Keyakizaka-dori illuminations, curated cocktail bar, hidden gem bar, Japanese bar culture insights (drinks separate)</li>
                    </ul>
                    <div class="mt-4 flex flex-col space-y-2">
                        <a href="YOUR_STRIPE_CHECKOUT_URL_GINZA_NIGHT" target="_blank" class="bg-[#8B5F9B] text-white text-center font-bold py-2 px-4 rounded-full hover:bg-[#724E82] transition-colors duration-300 text-sm">Book & Pay Now (Credit Card)</a>
                        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top" class="w-full">
                            <input type="hidden" name="cmd" value="_xclick">
                            <input type="hidden" name="business" value="YOUR_PAYPAL_BUSINESS_EMAIL@example.com">
                            <input type="hidden" name="item_name" value="Ginza Night Tour: Bar Hopping">
                            <input type="hidden" name="amount" value="PRICE_GINZA_NIGHT"> <!-- Replace with actual price -->
                            <input type="hidden" name="currency_code" value="USD">
                            <input type="hidden" name="return" value="https://yourwebsite.com/payment-success.html">
                            <input type="hidden" name="cancel_return" value="https://yourwebsite.com/payment-cancel.html">
                            <input type="hidden" name="button_subtype" value="services">
                            <input type="hidden" name="no_shipping" value="1">
                            <input type="hidden" name="no_note" value="1">
                            <input type="hidden" name="lc" value="US">
                            <input type="hidden" name="bn" value="PP-BuyNowBF">
                            <button type="submit" class="bg-blue-600 text-white text-center font-bold py-2 px-4 rounded-full hover:bg-blue-700 transition-colors duration-300 text-sm w-full">Pay with PayPal</button>
                        </form>
                    </div>
                </div>
                <!-- Private Tour Card 5 (Night) -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col">
                    <h4 class="text-2xl font-semibold text-[#8B5F9B] mb-3">Naka-Meguro Night Tour: "Riverside Revelry & Hidden Culinary Gems"</h4>
                    <p class="text-gray-700 mb-4 flex-grow">Immerse yourself in the chic, understated elegance of Naka-Meguro's night scene. This tour blends a romantic stroll along the Meguro River with visits to carefully selected hidden bars and unique dining spots.</p>
                    <ul class="text-gray-600 text-sm list-disc list-inside mt-auto">
                        <li><strong>Price:</strong> ¥23,000</li>
                        <li><strong>Duration:</strong> Approx. 3 hours</li>
                        <li><strong>Area:</strong> Naka-Meguro</li>
                        <li><strong>Key Experiences:</strong> Meguro River stroll, sophisticated izakaya/dining bar, hidden alleyways, bespoke cocktail/specialty bar (food/drinks separate)</li>
                    </ul>
                    <div class="mt-4 flex flex-col space-y-2">
                        <a href="YOUR_STRIPE_CHECKOUT_URL_NAKA_MEGURO_NIGHT" target="_blank" class="bg-[#8B5F9B] text-white text-center font-bold py-2 px-4 rounded-full hover:bg-[#724E82] transition-colors duration-300 text-sm">Book & Pay Now (Credit Card)</a>
                        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top" class="w-full">
                            <input type="hidden" name="cmd" value="_xclick">
                            <input type="hidden" name="business" value="YOUR_PAYPAL_BUSINESS_EMAIL@example.com">
                            <input type="hidden" name="item_name" value="Naka-Meguro Night Tour">
                            <input type="hidden" name="amount" value="PRICE_NAKA_MEGURO_NIGHT"> <!-- Replace with actual price -->
                            <input type="hidden" name="currency_code" value="USD">
                            <input type="hidden" name="return" value="https://yourwebsite.com/payment-success.html">
                            <input type="hidden" name="cancel_return" value="https://yourwebsite.com/payment-cancel.html">
                            <input type="hidden" name="button_subtype" value="services">
                            <input type="hidden" name="no_shipping" value="1">
                            <input type="hidden" name="no_note" value="1">
                            <input type="hidden" name="lc" value="US">
                            <input type="hidden" name="bn" value="PP-BuyNowBF">
                            <button type="submit" class="bg-blue-600 text-white text-center font-bold py-2 px-4 rounded-full hover:bg-blue-700 transition-colors duration-300 text-sm w-full">Pay with PayPal</button>
                        </form>
                    </div>
                </div>
                <!-- Private Tour Card 6 (Night) -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col">
                    <h4 class="text-2xl font-semibold text-[#8B5F9B] mb-3">Roppongi Night Tour: "Tokyo's Liquid Gold: Bespoke Bar Hopping"</h4>
                    <p class="text-gray-700 mb-4 flex-grow">Dive into Roppongi's electrifying and diverse nightlife, exploring its sophisticated bar scene. Guide through hand-picked establishments, offering an exclusive taste of Tokyo's finest libations.</p>
                    <ul class="text-gray-600 text-sm list-disc list-inside mt-auto">
                        <li><strong>Price:</strong> ¥25,000</li>
                        <li><strong>Duration:</strong> Approx. 3 hours</li>
                        <li><strong>Area:</strong> Roppongi</li>
                        <li><strong>Key Experiences:</strong> Keyakizaka-dori, Mori Tower (exterior), sophisticated cocktail bar, niche spirit bar, Japanese bar culture (drinks separate)</li>
                    </ul>
                    <div class="mt-4 flex flex-col space-y-2">
                        <a href="YOUR_STRIPE_CHECKOUT_URL_ROPPONGI_NIGHT" target="_blank" class="bg-[#8B5F9B] text-white text-center font-bold py-2 px-4 rounded-full hover:bg-[#724E82] transition-colors duration-300 text-sm">Book & Pay Now (Credit Card)</a>
                        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top" class="w-full">
                            <input type="hidden" name="cmd" value="_xclick">
                            <input type="hidden" name="business" value="YOUR_PAYPAL_BUSINESS_EMAIL@example.com">
                            <input type="hidden" name="item_name" value="Roppongi Night Tour: Bar Hopping">
                            <input type="hidden" name="amount" value="PRICE_ROPPONGI_NIGHT"> <!-- Replace with actual price -->
                            <input type="hidden" name="currency_code" value="USD">
                            <input type="hidden" name="return" value="https://yourwebsite.com/payment-success.html">
                            <input type="hidden" name="cancel_return" value="https://yourwebsite.com/payment-cancel.html">
                            <input type="hidden" name="button_subtype" value="services">
                            <input type="hidden" name="no_shipping" value="1">
                            <input type="hidden" name="no_note" value="1">
                            <input type="hidden" name="lc" value="US">
                            <input type="hidden" name="bn" value="PP-BuyNowBF">
                            <button type="submit" class="bg-blue-600 text-white text-center font-bold py-2 px-4 rounded-full hover:bg-blue-700 transition-colors duration-300 text-sm w-full">Pay with PayPal</button>
                        </form>
                    </div>
                </div>
                <!-- NEW Private Tour Card (Night) -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col">
                    <h4 class="text-2xl font-semibold text-[#8B5F9B] mb-3">Nishi-Azabu Night: "Discreet Elegance & Tokyo's Hidden Haunts" <span class="text-gray-500">(Night)</span></h4>
                    <p class="text-gray-700 mb-4 flex-grow">Uncover Nishi-Azabu's exclusive and discreet nightlife, a haven for sophisticated Tokyoites. This tour leads guests through quiet streets to intimate, high-end bars and lounges, offering a taste of Tokyo's refined, secretive side.</p>
                    <ul class="text-gray-600 text-sm list-disc list-inside mt-auto">
                        <li><strong>Price:</strong> ¥26,000</li>
                        <li><strong>Duration:</strong> Approx. 3 hours</li>
                        <li><strong>Area:</strong> Nishi-Azabu</li>
                        <li><strong>Key Experiences:</strong> Sophisticated cocktail bars, bespoke mixology, hidden whisky lounges, quiet ambiance, exclusive local insights (drinks separate)</li>
                    </ul>
                    <div class="mt-4 flex flex-col space-y-2">
                        <a href="YOUR_STRIPE_CHECKOUT_URL_NISHI_AZABU_NIGHT" target="_blank" class="bg-[#8B5F9B] text-white text-center font-bold py-2 px-4 rounded-full hover:bg-[#724E82] transition-colors duration-300 text-sm">Book & Pay Now (Credit Card)</a>
                        <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top" class="w-full">
                            <input type="hidden" name="cmd" value="_xclick">
                            <input type="hidden" name="business" value="YOUR_PAYPAL_BUSINESS_EMAIL@example.com">
                            <input type="hidden" name="item_name" value="Nishi-Azabu Night Tour">
                            <input type="hidden" name="amount" value="PRICE_NISHI_AZABU_NIGHT"> <!-- Replace with actual price -->
                            <input type="hidden" name="currency_code" value="USD">
                            <input type="hidden" name="return" value="https://yourwebsite.com/payment-success.html">
                            <input type="hidden" name="cancel_return" value="https://yourwebsite.com/payment-cancel.html">
                            <input type="hidden" name="button_subtype" value="services">
                            <input type="hidden" name="no_shipping" value="1">
                            <input type="hidden" name="no_note" value="1">
                            <input type="hidden" name="lc" value="US">
                            <input type="hidden" name="bn" value="PP-BuyNowBF">
                            <button type="submit" class="bg-blue-600 text-white text-center font-bold py-2 px-4 rounded-full hover:bg-blue-700 transition-colors duration-300 text-sm w-full">Pay with PayPal</button>
                        </form>
                    </div>
                </div>
            </div>
            <div class="call-to-action mt-10 text-center">
                <a href="#contact" class="inline-block bg-[#8B5F9B] text-white font-bold py-3 px-8 rounded-full shadow-lg hover:bg-[#724E82] transition-colors duration-300 text-lg">Inquire About Private Tours</a>
            </div>
        </section>

    <!-- Custom-Made Tours Section -->
    <section id="custom-tours" class="py-16 bg-gradient-to-br from-blue-50 to-indigo-100">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-4xl font-bold text-gray-900 mb-10">Custom-Made Tours: Your Japan, Your Way.</h2>
            <p class="text-lg text-gray-700 mb-8 max-w-3xl mx-auto">For the ultimate personalized journey, our Custom-Made Tours are designed from scratch around your unique interests, passions, and pace. Whether you dream of exploring niche subcultures, delving into specific historical periods, pursuing unique hobbies, or experiencing Japan off the beaten path, we craft an itinerary that is truly yours.</p>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-left mt-12">
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-2xl font-semibold text-[#593E91] mb-4">Initial Consultation</h3>
                    <p class="text-gray-700">Share your vision, interests, desired dates, and group size via our easy inquiry form. No request is too unique!</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-2xl font-semibold text-[#593E91] mb-4">Personalized Proposal</h3>
                    <p class="text-gray-700">A dedicated consultant will connect with you to discuss details and propose a preliminary itinerary and estimated cost.</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md">
                    <h3 class="text-2xl font-semibold text-[#593E91] mb-4">Refinement & Quotation</h3>
                    <p class="text-gray-700">We'll work closely with you to refine every detail until it's perfect, then provide a detailed quotation for your approval.</p>
                </div>
            </div>
            <p class="mt-8 text-gray-700 text-lg font-semibold">Let us transform your unique ideas into an unforgettable Japanese adventure.</p>
            <div class="call-to-action mt-10">
                <a href="#contact" class="inline-block bg-[#593E91] text-white font-bold py-3 px-8 rounded-full shadow-lg hover:bg-[#46316D] transition-colors duration-300 text-lg">Create Your Custom Tour</a>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section id="faq" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-gray-900 mb-10 text-center">Frequently Asked Questions (FAQ)</h2>
            <div class="max-w-3xl mx-auto space-y-6">
                <div class="bg-white rounded-lg shadow-md p-6">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">Q: How is the pricing determined?</h3>
                    <p class="text-gray-700">A: For **Student Community Tours**, we operate on a free-pricing system. After the tour, you pay what you feel the experience was worth. For **Private Quality Tours**, a pre-set fee will be communicated to you in advance during the consultation phase.</p>
                </div>
                <div class="bg-white rounded-lg shadow-md p-6">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">Q: Does the tour fee include accommodation or transportation?</h3>
                    <p class="text-gray-700">A: No, VEXEL Japan Guide provides pure guiding services and does not arrange accommodation or transportation. All costs for public transport during the tour, facility admissions, and food/drinks are to be paid by the customer directly on site.</p>
                </div>
                <div class="bg-white rounded-lg shadow-md p-6">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">Q: What languages do your guides speak?</h3>
                    <p class="text-gray-700">A: Our guides primarily speak English. Some guides may also be proficient in other languages (e.g., Chinese, Korean, Spanish). Please inform us of your preferred language when making an inquiry.</p>
                </div>
                <div class="bg-white rounded-lg shadow-md p-6">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">Q: How far in advance should I book a tour?</h3>
                    <p class="text-gray-700">A: We recommend inquiring at least one week before your desired tour date, though this can vary depending on the tour and guide availability. Last-minute bookings may be possible, so please don't hesitate to ask.</p>
                </div>
                <div class="bg-white rounded-lg shadow-md p-6">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">Q: What about food and drinks during the tour?</h3>
                    <p class="text-gray-700">A: Food and drinks consumed during the tour are to be ordered and paid for by the customer directly. Your guide can recommend places and assist with ordering.</p>
                </div>
                <div class="bg-white rounded-lg shadow-md p-6">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">Q: Can minors participate in tours alone?</h3>
                    <p class="text-gray-700">A: Participants under 18 years old are not permitted to join tours without an accompanying guardian. Please note that Japanese law strictly prohibits underage drinking, especially on evening tours.</p>
            </div>
        </div>
    </section>

    <!-- Contact Us Section -->
    <section id="contact" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-bold text-gray-900 mb-10 text-center">Contact Us</h2>
            <p class="text-lg text-gray-700 mb-8 text-center max-w-3xl mx-auto">Ready to discover Japan from a new perspective? Fill out the form below to inquire about our tours or discuss a custom-made itinerary. We look forward to hearing from you!</p>

            <div class="max-w-lg mx-auto bg-gray-100 p-8 rounded-lg shadow-md">
                <form action="#" method="POST" class="space-y-6">
                    <div>
                        <label for="name" class="block text-gray-700 text-sm font-bold mb-2">Your Name:</label>
                        <input type="text" id="name" name="name" required class="shadow appearance-none border rounded w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-indigo-500">
                    </div>
                    <div>
                        <label for="email" class="block text-gray-700 text-sm font-bold mb-2">Email Address:</label>
                        <input type="email" id="email" name="email" required class="shadow appearance-none border rounded w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-indigo-500">
                    </div>
                    <div>
                        <label for="tour-type" class="block text-gray-700 text-sm font-bold mb-2">Preferred Tour Type:</label>
                        <select id="tour-type" name="tour-type" class="shadow border rounded w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-indigo-500">
                            <option value="student-community">Student Community Tour</option>
                            <option value="private-quality">Private Quality Tour</option>
                            <option value="custom">Custom Tour Consultation</option>
                        </select>
                    </div>
                    <div>
                        <label for="message" class="block text-gray-700 text-sm font-bold mb-2">Your Message:</label>
                        <textarea id="message" name="message" rows="6" required class="shadow appearance-none border rounded w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-indigo-500 resize-y"></textarea>
                    </div>
                    <div class="text-center">
                        <button type="submit" class="bg-[#5D6BBA] text-white font-bold py-3 px-10 rounded-full shadow-lg hover:bg-[#4E5A9D] transition-colors duration-300 text-lg">Send Message</button>
                    </div>
                </form>
                <p class="text-center text-gray-700 mt-8">Alternatively, you can email us directly at: <br><a href="mailto:info@vexel-japan-guide.com" class="text-[#5D6BBA] hover:underline">info@vexel-japan-guide.com</a></p>
                <!-- Placeholder for social media icons -->
                <div class="flex justify-center space-x-6 mt-6">
                    <a href="#" class="text-gray-500 hover:text-[#5D6BBA] transition-colors duration-300" aria-label="Facebook"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor"><path d="M12 0c-6.627 0-12 5.373-12 12s5.373 12 12 12 12-5.373 12-12-5.373-12-12-12zm3 8h-1.35c-.562 0-.65.232-.65.737v1.863h2.54l-.272 2.72h-2.268v6.79h-2.915v-6.79h-2.228v-2.72h2.228v-2.083c0-2.278 1.135-3.172 3.492-3.172l2.096.002v2.53z"/></svg></a>
                    <a href="#" class="text-gray-500 hover:text-[#5D6BBA] transition-colors duration-300" aria-label="Instagram"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.773 1.693 4.925 4.926.058 1.266.07 1.646.07 4.85s-.012 3.584-.07 4.85c-.152 3.233-1.673 4.773-4.926 4.925-1.266.058-1.646.07-4.85.07s-3.584-.012-4.85-.07c-3.252-.152-4.773-1.693-4.925-4.926-.058-1.266-.07-1.646-.07-4.85s.012-3.584.07-4.85c.152-3.233 1.673-4.773 4.926-4.925 1.266-.058 1.646-.07 4.85-.07zm0-2.163c-3.259 0-3.667.014-4.947.072-4.354.201-6.702 2.55-6.903 6.903-.058 1.28-.072 1.688-.072 4.948s.014 3.668.072 4.948c.201 4.354 2.549 6.702 6.903 6.903 1.28.058 1.688.072 4.948.072s3.668-.014 4.948-.072c4.354-.201 6.702-2.549 6.903-6.903.058-1.28.072-1.688.072-4.948s-.014-3.667-.072-4.947c-.201-4.354-2.549-6.702-6.903-6.903-1.28-.058-1.688-.072-4.948-.072zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.162 6.162 6.162 6.162-2.759 6.162-6.162-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.791-4-4s1.791-4 4-4 4 1.791 4 4-1.791 4-4 4zm6.406-11.845c-.796 0-1.444.647-1.444 1.443s.647 1.443 1.444 1.443c.796 0 1.443-.647 1.443-1.443s-.647-1.443-1.443-1.443z"/></svg></a>
                    <a href="#" class="text-gray-500 hover:text-[#5D6BBA] transition-colors duration-300" aria-label="Twitter"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor"><path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.593 0-6.492 2.901-6.492 6.492 0 .513.056 1.01.166 1.487-5.392-.27-10.147-2.868-13.334-6.071-.54.93-.853 2.02-.853 3.197 0 2.258 1.159 4.247 2.919 5.421-.538-.016-1.04-.165-1.487-.408v.08c0 3.154 2.235 5.786 5.193 6.365-.548.148-1.135.216-1.743.216-.424 0-.834-.041-1.234-.117.828 2.586 3.205 4.484 6.014 4.588-2.228 1.747-5.037 2.787-8.092 2.787-.53 0-1.053-.031-1.566-.092 2.89 1.862 6.305 2.955 9.981 2.955 12.012 0 18.574-9.929 18.574-18.574 0-.281-.008-.562-.023-.842.96-.695 1.794-1.565 2.457-2.551z"/></svg></a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-gray-900 text-white py-8 text-center text-sm">
        <div class="container mx-auto px-4">
            <p>&copy; 2025 VEXEL Japan Guide. All rights reserved.</p>
            <p class="mt-2 text-gray-400">Disclaimer: VEXEL Japan Guide provides guiding services only. We do not arrange accommodation, transportation, or pre-purchase tickets/food/drinks. All additional costs are paid directly by the customer on-site.</p>
        </div>
    </footer>

    <script>
        // Function to pre-fill the contact form and scroll to it
        function bookStudentTour(tourName) {
            document.getElementById('tour-type').value = 'student-community';
            document.getElementById('message').value = 'I am interested in booking the following Student Community Tour:\n\n' + tourName + '\n\nPlease provide more details on availability and how to proceed with booking.';
            document.getElementById('contact').scrollIntoView({ behavior: 'smooth' });
        }
    </script>
</body>
</html>
