<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>KNT Conciergerie - Paris & El Gouna</title>
<script src="https://cdn.tailwindcss.com/3.4.16"></script>
<script>tailwind.config={theme:{extend:{colors:{primary:'#d4b872',secondary:'#ffffff'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css">
<style>
:where([class^="ri-"])::before { content: "\f3c2"; }
body {
font-family: 'Poppins', sans-serif;
}
.hover-scale {
transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
}
.hover-scale:hover {
transform: scale(1.05);
box-shadow: 0 10px 25px rgba(212, 184, 114, 0.2);
}
.font-serif {
font-family: 'Playfair Display', serif;
}
.text-gold {
color: #d4b872;
}
.bg-gold {
background-color: #d4b872;
}
.border-gold {
border-color: #d4b872;
}
.gold-gradient {
background: linear-gradient(135deg, #e9d7a7 0%, #d4b872 50%, #b69c52 100%);
}
.hero-section {
background-size: cover;
background-position: center;
}
.hero-overlay {
background: rgba(0, 0, 0, 0.3);
}
.destination-card:hover {
transform: translateY(-5px);
box-shadow: 0 15px 30px rgba(212, 184, 114, 0.2);
}
.service-card:hover {
transform: translateY(-3px);
box-shadow: 0 10px 20px rgba(212, 184, 114, 0.15);
}
input:focus, textarea:focus, select:focus {
border-color: #d4b872;
outline: none;
}
.custom-checkbox {
position: relative;
padding-left: 30px;
cursor: pointer;
}
.custom-checkbox input {
position: absolute;
opacity: 0;
cursor: pointer;
}
.checkmark {
position: absolute;
top: 0;
left: 0;
height: 20px;
width: 20px;
border: 1px solid #d4b872;
border-radius: 4px;
}
.custom-checkbox input:checked ~ .checkmark:after {
content: "";
position: absolute;
display: block;
left: 7px;
top: 3px;
width: 5px;
height: 10px;
border: solid #d4b872;
border-width: 0 2px 2px 0;
transform: rotate(45deg);
}
</style>
</head>
<body class="bg-white">
<!-- Header -->
<header class="w-full py-4 px-6 md:px-12 flex items-center justify-between border-b border-gray-100">
<div class="flex items-center">
<div class="font-['Playfair_Display'] text-3xl font-bold text-gold">
<span class="font-['Pacifico']">KNT</span>
<span class="text-xl ml-2">CONCIERGERIE</span>
</div>
</div>
<nav class="hidden md:flex items-center space-x-6">
<a href="#el-gouna" class="text-gray-800 hover:text-primary transform hover:scale-105 transition-all duration-300 font-medium">El Gouna</a>
<a href="#paris" class="text-gray-800 hover:text-primary transform hover:scale-105 transition-all duration-300 font-medium">Paris</a>
<a href="#services" class="text-gray-800 hover:text-primary transform hover:scale-105 transition-all duration-300 font-medium">Services</a>
<a href="#activites" class="text-gray-800 hover:text-primary transform hover:scale-105 transition-all duration-300 font-medium">Activités</a>
<a href="#contact" class="text-gray-800 hover:text-primary transform hover:scale-105 transition-all duration-300 font-medium">Contact</a>
<a href="#account" class="flex items-center text-gray-800 hover:text-primary transform hover:scale-105 transition-all duration-300 font-medium">
<i class="ri-user-line mr-1"></i>Mon Compte</a>
<a href="#reserver" class="ml-4 px-6 py-2 bg-primary text-white font-medium rounded-button transform hover:scale-105 hover:shadow-xl transition-all duration-300 hover:bg-opacity-90 whitespace-nowrap">Réserver</a>
</nav>
<div class="md:hidden flex items-center">
<button class="text-gray-800 w-10 h-10 flex items-center justify-center">
<i class="ri-menu-line ri-lg"></i>
</button>
</div>
</header>
<!-- Hero Section -->
<section class="relative w-full h-[80vh] flex items-center justify-center overflow-hidden">
<div class="slider absolute inset-0 z-0">
    <div class="slide absolute inset-0 opacity-0 transition-opacity duration-1000" style="background-image: url('https://readdy.ai/api/search-image?query=Luxurious%20aerial%20photography%20of%20a%20pristine%20beach%20resort%20in%20El%20Gouna%2C%20Egypt%2C%20with%20crystal%20clear%20turquoise%20waters%2C%20white%20sand%20beaches%2C%20and%20luxury%20villas.%20The%20image%20captures%20the%20natural%20beauty%20and%20exclusive%20atmosphere%20of%20the%20location%20with%20perfect%20lighting%20and%20professional%20composition%2C%20showcasing%20the%20high-end%20resort%20destination.&width=1920&height=1080&seq=1&orientation=landscape'); background-size: cover; background-position: center;"></div>
    <div class="slide absolute inset-0 opacity-0 transition-opacity duration-1000" style="background-image: url('https://readdy.ai/api/search-image?query=Stunning%20aerial%20view%20of%20Paris%20at%20dusk%2C%20featuring%20the%20illuminated%20Eiffel%20Tower%20and%20Seine%20River.%20The%20iconic%20Haussmann%20buildings%20and%20tree-lined%20boulevards%20create%20a%20luxurious%20and%20romantic%20atmosphere.%20Golden%20hour%20lighting%20enhances%20the%20citys%20elegant%20architecture%20and%20timeless%20beauty.&width=1920&height=1080&seq=2&orientation=landscape'); background-size: cover; background-position: center;"></div>
    <div class="slide absolute inset-0 opacity-0 transition-opacity duration-1000" style="background-image: url('https://readdy.ai/api/search-image?query=Luxurious%20beachfront%20resort%20in%20El%20Gouna%20at%20sunset%2C%20featuring%20overwater%20bungalows%2C%20pristine%20lagoons%2C%20and%20palm-lined%20beaches.%20The%20warm%20evening%20light%20creates%20a%20magical%20atmosphere%2C%20highlighting%20the%20exclusive%20and%20peaceful%20setting%20of%20this%20Red%20Sea%20paradise.&width=1920&height=1080&seq=3&orientation=landscape'); background-size: cover; background-position: center;"></div>
    <div class="slide absolute inset-0 opacity-0 transition-opacity duration-1000" style="background-image: url('https://readdy.ai/api/search-image?query=Elegant%20Parisian%20rooftop%20terrace%20with%20panoramic%20view%20of%20the%20city%20skyline%20at%20twilight.%20Featuring%20ornate%20wrought%20iron%20details%2C%20blooming%20flowers%2C%20and%20comfortable%20lounge%20furniture.%20The%20scene%20captures%20the%20sophisticated%20lifestyle%20and%20romantic%20ambiance%20of%20luxury%20living%20in%20Paris.&width=1920&height=1080&seq=4&orientation=landscape'); background-size: cover; background-position: center;"></div>
</div>
<div class="absolute inset-0 bg-black bg-opacity-30 z-10"></div>
<div class="relative z-20 text-center px-4 max-w-4xl">
<h1 class="font-serif text-5xl md:text-6xl font-bold text-white mb-4">Votre Conciergerie d'Exception</h1>
<p class="text-xl md:text-2xl text-white mb-8">Entre Paris et El Gouna, vivez des expériences inoubliables</p>
<div class="flex flex-col md:flex-row items-center justify-center gap-4">
<a href="#destinations" class="px-8 py-3 bg-primary text-white font-medium rounded-button transition-all hover:bg-opacity-90 hover:scale-105 hover:shadow-lg whitespace-nowrap">Découvrir nos destinations</a>
<a href="#contact" class="px-8 py-3 border-2 border-white text-white font-medium rounded-button transition-all hover:bg-white hover:text-gray-900 hover:scale-105 hover:shadow-lg whitespace-nowrap">Nous contacter</a>
</div>
</div>
</section>
<!-- Destinations Section -->
<section id="destinations" class="py-20 px-6 md:px-12 max-w-7xl mx-auto">
<div class="text-center mb-16">
<h2 class="font-serif text-4xl font-bold text-gray-900 mb-4">Nos Destinations</h2>
<p class="text-gray-600 max-w-2xl mx-auto">Découvrez nos deux destinations d'exception où nous vous offrons des services de conciergerie personnalisés pour des séjours inoubliables.</p>
</div>
<div class="grid md:grid-cols-2 gap-10">
<!-- El Gouna Card -->
<div id="el-gouna" class="destination-card bg-white rounded-lg overflow-hidden shadow-lg border border-gray-100 transition-all duration-300">
<div class="h-64 overflow-hidden">
<img src="https://readdy.ai/api/search-image?query=Professional%20real%20estate%20photography%20of%20a%20luxury%20beachfront%20villa%20in%20El%20Gouna%20at%20golden%20hour%2C%20featuring%20infinity%20pool%20overlooking%20the%20Red%20Sea%2C%20modern%20architecture%20with%20large%20windows%2C%20and%20elegant%20outdoor%20lounging%20areas.%20Palm%20trees%20and%20pristine%20landscaping%20frame%20the%20property%2C%20showcasing%20the%20exclusive%20lifestyle.&width=800&height=500&seq=2&orientation=landscape" alt="El Gouna" class="w-full h-full object-cover object-top">
</div>
<div class="p-8">
<h3 class="font-serif text-3xl font-bold text-gray-900 mb-3">El Gouna</h3>
<p class="text-gray-600 mb-6">Découvrez le paradis sur les rives de la mer Rouge. El Gouna vous offre des plages de sable fin, des eaux cristallines et un climat idéal toute l'année.</p>
<ul class="mb-8 space-y-2">
<li class="flex items-start">
<span class="text-primary mr-2 mt-1 w-5 h-5 flex items-center justify-center"><i class="ri-check-line"></i></span>
<span>Villas et appartements de luxe en bord de mer</span>
</li>
<li class="flex items-start">
<span class="text-primary mr-2 mt-1 w-5 h-5 flex items-center justify-center"><i class="ri-check-line"></i></span>
<span>Activités nautiques et excursions dans le désert</span>
</li>
<li class="flex items-start">
<span class="text-primary mr-2 mt-1 w-5 h-5 flex items-center justify-center"><i class="ri-check-line"></i></span>
<span>Restaurants gastronomiques et vie nocturne</span>
</li>
</ul>
<a href="#contact" class="inline-block px-6 py-3 border-2 border-primary text-primary font-medium rounded-button transition-all hover:bg-primary hover:text-white hover:scale-105 hover:shadow-lg whitespace-nowrap">Découvrir El Gouna</a>
</div>
</div>
<!-- Paris Card -->
<div id="paris" class="destination-card bg-white rounded-lg overflow-hidden shadow-lg border border-gray-100 transition-all duration-300">
<div class="h-64 overflow-hidden">
<img src="https://readdy.ai/api/search-image?query=Professional%20architectural%20photography%20of%20a%20luxury%20Haussmann%20apartment%20in%20Paris%20with%20stunning%20Eiffel%20Tower%20view%2C%20captured%20during%20sunset.%20The%20interior%20features%20high%20ceilings%2C%20herringbone%20wooden%20floors%2C%20ornate%20moldings%2C%20and%20elegant%20French%20windows.%20The%20space%20is%20decorated%20with%20high-end%20furniture%20and%20chandeliers%2C%20embodying%20Parisian%20luxury.&width=800&height=500&seq=3&orientation=landscape" alt="Paris" class="w-full h-full object-cover object-top">
</div>
<div class="p-8">
<h3 class="font-serif text-3xl font-bold text-gray-900 mb-3">Paris</h3>
<p class="text-gray-600 mb-6">Vivez l'élégance et le charme de la Ville Lumière. Paris vous accueille avec son patrimoine culturel, sa gastronomie et son art de vivre incomparable.</p>
<ul class="mb-8 space-y-2">
<li class="flex items-start">
<span class="text-primary mr-2 mt-1 w-5 h-5 flex items-center justify-center"><i class="ri-check-line"></i></span>
<span>Appartements haussmanniens et hôtels de luxe</span>
</li>
<li class="flex items-start">
<span class="text-primary mr-2 mt-1 w-5 h-5 flex items-center justify-center"><i class="ri-check-line"></i></span>
<span>Visites privées des musées et monuments</span>
</li>
<li class="flex items-start">
<span class="text-primary mr-2 mt-1 w-5 h-5 flex items-center justify-center"><i class="ri-check-line"></i></span>
<span>Expériences gastronomiques et shopping de luxe</span>
</li>
</ul>
<a href="#contact" class="inline-block px-6 py-3 border-2 border-primary text-primary font-medium rounded-button transition-all hover:bg-primary hover:text-white whitespace-nowrap">Découvrir Paris</a>
</div>
</div>
</div>
</section>
<!-- Services Section -->
<section id="services" class="py-20 px-6 md:px-12 bg-gray-50">
<div class="max-w-7xl mx-auto">
<div class="text-center mb-16">
<h2 class="font-serif text-4xl font-bold text-gray-900 mb-4">Nos Services de Conciergerie</h2>
<p class="text-gray-600 max-w-2xl mx-auto">Nous vous offrons une gamme complète de services personnalisés pour rendre votre séjour inoubliable, que ce soit à El Gouna ou à Paris.</p>
</div>
<div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
<!-- Service 1 -->
<div class="service-card bg-white p-8 rounded-lg shadow-sm border border-gray-100 transition-all duration-300">
<div class="w-12 h-12 flex items-center justify-center rounded-full bg-primary bg-opacity-10 mb-6">
<i class="ri-home-6-line text-primary ri-lg"></i>
</div>
<h3 class="font-serif text-xl font-bold text-gray-900 mb-3">Hébergements de Luxe</h3>
<p class="text-gray-600">Accédez à notre sélection exclusive de villas, appartements et suites d'hôtel dans les meilleurs emplacements.</p>
</div>
<!-- Service 2 -->
<div class="service-card bg-white p-8 rounded-lg shadow-sm border border-gray-100 transition-all duration-300">
<div class="w-12 h-12 flex items-center justify-center rounded-full bg-primary bg-opacity-10 mb-6">
<i class="ri-car-line text-primary ri-lg"></i>
</div>
<h3 class="font-serif text-xl font-bold text-gray-900 mb-3">Transport Privé</h3>
<p class="text-gray-600">Profitez de nos services de transfert privé, location de voitures de luxe et chauffeurs personnels.</p>
</div>
<!-- Service 3 -->
<div class="service-card bg-white p-8 rounded-lg shadow-sm border border-gray-100 transition-all duration-300">
<div class="w-12 h-12 flex items-center justify-center rounded-full bg-primary bg-opacity-10 mb-6">
<i class="ri-restaurant-line text-primary ri-lg"></i>
</div>
<h3 class="font-serif text-xl font-bold text-gray-900 mb-3">Expériences Gastronomiques</h3>
<p class="text-gray-600">Réservations dans les meilleurs restaurants, chefs privés à domicile et dégustations exclusives.</p>
</div>
<!-- Service 4 -->
<div class="service-card bg-white p-8 rounded-lg shadow-sm border border-gray-100 transition-all duration-300">
<div class="w-12 h-12 flex items-center justify-center rounded-full bg-primary bg-opacity-10 mb-6">
<i class="ri-ship-line text-primary ri-lg"></i>
</div>
<h3 class="font-serif text-xl font-bold text-gray-900 mb-3">Activités & Excursions</h3>
<p class="text-gray-600">Organisation d'activités sur mesure : croisières privées, visites culturelles, sports nautiques et bien plus.</p>
</div>
<!-- Service 5 -->
<div class="service-card bg-white p-8 rounded-lg shadow-sm border border-gray-100 transition-all duration-300">
<div class="w-12 h-12 flex items-center justify-center rounded-full bg-primary bg-opacity-10 mb-6">
<i class="ri-calendar-check-line text-primary ri-lg"></i>
</div>
<h3 class="font-serif text-xl font-bold text-gray-900 mb-3">Conciergerie Personnelle</h3>
<p class="text-gray-600">Un concierge dédié disponible 24/7 pour répondre à toutes vos demandes pendant votre séjour.</p>
</div>
<!-- Service 6 -->
<div class="service-card bg-white p-8 rounded-lg shadow-sm border border-gray-100 transition-all duration-300">
<div class="w-12 h-12 flex items-center justify-center rounded-full bg-primary bg-opacity-10 mb-6">
<i class="ri-gift-line text-primary ri-lg"></i>
</div>
<h3 class="font-serif text-xl font-bold text-gray-900 mb-3">Services Exclusifs</h3>
<p class="text-gray-600">Événements privés, shopping personnalisé, bien-être et soins à domicile, garde d'enfants et plus encore.</p>
</div>
</div>
</div>
</section>
<!-- Testimonials Section -->
<section class="py-20 px-6 md:px-12 max-w-7xl mx-auto">
<div class="text-center mb-16">
<h2 class="font-serif text-4xl font-bold text-gray-900 mb-4">Ce Que Disent Nos Clients</h2>
<p class="text-gray-600 max-w-2xl mx-auto">Découvrez les expériences de nos clients qui ont profité de nos services de conciergerie à El Gouna et à Paris.</p>
</div>
<div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
<!-- Testimonial 1 -->
<div class="bg-white p-8 rounded-lg shadow-sm border border-gray-100">
<div class="flex text-primary mb-4">
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
</div>
<p class="text-gray-600 italic mb-6">"Un service exceptionnel ! Notre séjour à El Gouna a été parfaitement organisé par KNT Conciergerie. Chaque détail a été soigné, de la villa avec vue sur la mer aux excursions en bateau."</p>
<div class="flex items-center">
<div class="w-10 h-10 bg-primary bg-opacity-20 rounded-full flex items-center justify-center text-primary font-medium mr-3">SL</div>
<div>
<h4 class="font-medium text-gray-900">Sophie Laurent</h4>
<p class="text-sm text-gray-500">Paris, France</p>
</div>
</div>
</div>
<!-- Testimonial 2 -->
<div class="bg-white p-8 rounded-lg shadow-sm border border-gray-100">
<div class="flex text-primary mb-4">
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
</div>
<p class="text-gray-600 italic mb-6">"Notre week-end à Paris a été magique grâce à KNT Conciergerie. L'appartement avec vue sur la Tour Eiffel, le dîner croisière privatisé sur la Seine... tout était parfait !"</p>
<div class="flex items-center">
<div class="w-10 h-10 bg-primary bg-opacity-20 rounded-full flex items-center justify-center text-primary font-medium mr-3">MB</div>
<div>
<h4 class="font-medium text-gray-900">Marc Beaumont</h4>
<p class="text-sm text-gray-500">Genève, Suisse</p>
</div>
</div>
</div>
<!-- Testimonial 3 -->
<div class="bg-white p-8 rounded-lg shadow-sm border border-gray-100">
<div class="flex text-primary mb-4">
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
<i class="ri-star-fill"></i>
</div>
<p class="text-gray-600 italic mb-6">"Un service haut de gamme qui a dépassé toutes nos attentes. Notre concierge était disponible à tout moment et a su répondre à toutes nos demandes avec professionnalisme et efficacité."</p>
<div class="flex items-center">
<div class="w-10 h-10 bg-primary bg-opacity-20 rounded-full flex items-center justify-center text-primary font-medium mr-3">AM</div>
<div>
<h4 class="font-medium text-gray-900">Alexandre Moreau</h4>
<p class="text-sm text-gray-500">Bruxelles, Belgique</p>
</div>
</div>
</div>
</div>
</section>
<!-- Contact Section -->
<section id="contact" class="py-20 px-6 md:px-12 bg-gray-50">
<div class="max-w-7xl mx-auto">
<div class="grid md:grid-cols-2 gap-12">
<div>
<h2 class="font-serif text-4xl font-bold text-gray-900 mb-4">Contactez-Nous</h2>
<p class="text-gray-600 mb-8">Parlez-nous de votre projet de voyage et laissez-nous créer pour vous une expérience sur mesure.</p>
<div class="space-y-6">
<div class="flex items-start">
<div class="w-10 h-10 flex items-center justify-center rounded-full bg-primary bg-opacity-10 mr-4 mt-1">
<i class="ri-mail-line text-primary"></i>
</div>
<div>
<h3 class="font-medium text-gray-900 mb-1">Email</h3>
<p class="text-gray-600">contact@knt-conciergerie.com</p>
</div>
</div>
<div class="flex items-start">
<div class="w-10 h-10 flex items-center justify-center rounded-full bg-primary bg-opacity-10 mr-4 mt-1">
<i class="ri-phone-line text-primary"></i>
</div>
<div>
<h3 class="font-medium text-gray-900 mb-1">Téléphone</h3>
<p class="text-gray-600">Paris: +33 1 23 45 67 89</p>
<p class="text-gray-600">El Gouna: +20 65 358 0700</p>
</div>
</div>
<div class="flex items-start">
<div class="w-10 h-10 flex items-center justify-center rounded-full bg-primary bg-opacity-10 mr-4 mt-1">
<i class="ri-map-pin-line text-primary"></i>
</div>
<div>
<h3 class="font-medium text-gray-900 mb-1">Adresses</h3>
<p class="text-gray-600">Paris: 25 Avenue Montaigne, 75008 Paris, France</p>
<p class="text-gray-600">El Gouna: Marina, El Gouna, Red Sea Governorate, Égypte</p>
</div>
</div>
</div>
</div>
<div class="bg-white p-8 rounded-lg shadow-sm border border-gray-100">
<h3 class="font-serif text-2xl font-bold text-gray-900 mb-6">Formulaire de Contact</h3>
<form>
<div class="grid md:grid-cols-2 gap-6 mb-6">
<div>
<label for="firstname" class="block text-sm font-medium text-gray-700 mb-2">Prénom</label>
<input type="text" id="firstname" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" placeholder="Votre prénom">
</div>
<div>
<label for="lastname" class="block text-sm font-medium text-gray-700 mb-2">Nom</label>
<input type="text" id="lastname" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" placeholder="Votre nom">
</div>
</div>
<div class="mb-6">
<label for="email" class="block text-sm font-medium text-gray-700 mb-2">Email</label>
<input type="email" id="email" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" placeholder="Votre email">
</div>
<div class="mb-6">
<label for="phone" class="block text-sm font-medium text-gray-700 mb-2">Téléphone</label>
<input type="tel" id="phone" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" placeholder="Votre numéro de téléphone">
</div>
<div class="mb-6">
<label for="destination" class="block text-sm font-medium text-gray-700 mb-2">Destination</label>
<div class="relative">
<select id="destination" class="w-full px-4 py-2 border border-gray-300 rounded appearance-none focus:border-primary pr-8">
<option value="">Choisissez une destination</option>
<option value="el-gouna">El Gouna</option>
<option value="paris">Paris</option>
<option value="both">Les deux destinations</option>
</select>
<div class="absolute inset-y-0 right-0 flex items-center px-2 pointer-events-none">
<i class="ri-arrow-down-s-line text-gray-400"></i>
</div>
</div>
</div>
<div class="mb-6">
<label for="message" class="block text-sm font-medium text-gray-700 mb-2">Message</label>
<textarea id="message" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" placeholder="Décrivez votre projet de voyage..."></textarea>
</div>
<div class="mb-6">
<label class="custom-checkbox">
<input type="checkbox">
<span class="checkmark"></span>
<span class="text-sm text-gray-600">J'accepte de recevoir des informations de KNT Conciergerie</span>
</label>
</div>
<button type="submit" class="w-full px-6 py-3 bg-primary text-white font-medium rounded-button transform hover:scale-105 hover:shadow-xl transition-all duration-300 hover:bg-opacity-90 whitespace-nowrap hover-scale">Envoyer ma demande</button>
</form>
</div>
</div>
</div>
</section>
<!-- Footer -->
<footer class="bg-gray-900 text-white pt-16 pb-8 px-6 md:px-12">
<div class="max-w-7xl mx-auto">
<div class="grid md:grid-cols-4 gap-10 mb-12">
<div>
<div class="font-['Playfair_Display'] text-2xl font-bold text-primary mb-6">
<span class="font-['Pacifico']">KNT</span>
<span class="text-lg ml-2">CONCIERGERIE</span>
</div>
<p class="text-gray-400 mb-6">Votre conciergerie d'exception entre Paris et El Gouna. Des services personnalisés pour des expériences inoubliables.</p>
<div class="flex space-x-4">
<a href="#" class="w-10 h-10 flex items-center justify-center rounded-full bg-gray-800 hover:bg-primary transition-colors">
<i class="ri-facebook-fill"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center rounded-full bg-gray-800 hover:bg-primary transition-colors">
<i class="ri-instagram-line"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center rounded-full bg-gray-800 hover:bg-primary transition-colors">
<i class="ri-twitter-x-line"></i>
</a>
<a href="#" class="w-10 h-10 flex items-center justify-center rounded-full bg-gray-800 hover:bg-primary transition-colors">
<i class="ri-linkedin-fill"></i>
</a>
</div>
</div>
<div>
<h3 class="font-serif text-lg font-bold mb-6">Destinations</h3>
<ul class="space-y-3">
<li><a href="#el-gouna" class="text-gray-400 hover:text-primary transition-colors">El Gouna</a></li>
<li><a href="#paris" class="text-gray-400 hover:text-primary transition-colors">Paris</a></li>
</ul>
</div>
<div>
<h3 class="font-serif text-lg font-bold mb-6">Services</h3>
<ul class="space-y-3">
<li><a href="#" class="text-gray-400 hover:text-primary transition-colors">Hébergements</a></li>
<li><a href="#" class="text-gray-400 hover:text-primary transition-colors">Transport</a></li>
<li><a href="#" class="text-gray-400 hover:text-primary transition-colors">Gastronomie</a></li>
<li><a href="#" class="text-gray-400 hover:text-primary transition-colors">Activités</a></li>
<li><a href="#" class="text-gray-400 hover:text-primary transition-colors">Services Exclusifs</a></li>
</ul>
</div>
<div>
<h3 class="font-serif text-lg font-bold mb-6">Contact</h3>
<ul class="space-y-3">
<li class="flex items-start">
<span class="text-primary mr-3 mt-1 w-5 h-5 flex items-center justify-center"><i class="ri-mail-line"></i></span>
<span class="text-gray-400">contact@knt-conciergerie.com</span>
</li>
<li class="flex items-start">
<span class="text-primary mr-3 mt-1 w-5 h-5 flex items-center justify-center"><i class="ri-phone-line"></i></span>
<span class="text-gray-400">+33 1 23 45 67 89</span>
</li>
<li class="flex items-start">
<span class="text-primary mr-3 mt-1 w-5 h-5 flex items-center justify-center"><i class="ri-phone-line"></i></span>
<span class="text-gray-400">+20 65 358 0700</span>
</li>
</ul>
</div>
</div>
<div class="pt-8 border-t border-gray-800 text-center text-gray-500 text-sm">
<p>&copy; 2025 KNT Conciergerie. Tous droits réservés.</p>
</div>
</div>
</footer>
<script>
document.addEventListener('DOMContentLoaded', function() {
// Mobile menu toggle
const menuButton = document.querySelector('.ri-menu-line');
if (menuButton) {
menuButton.addEventListener('click', function() {
// Mobile menu functionality would go here
console.log('Menu clicked');
});
}
// Slideshow functionality
let currentSlide = 0;
const slides = document.querySelectorAll('.slide');
if (slides.length > 0) {
    slides[0].style.opacity = '1';
    
    function nextSlide() {
        slides[currentSlide].style.opacity = '0';
        currentSlide = (currentSlide + 1) % slides.length;
        slides[currentSlide].style.opacity = '1';
    }
    
    setInterval(nextSlide, 5000);
}
});
document.addEventListener('DOMContentLoaded', function() {
// Form validation
const form = document.querySelector('form');
if (form) {
form.addEventListener('submit', function(e) {
e.preventDefault();
// Form validation and submission logic would go here
console.log('Form submitted');
alert('Merci pour votre message ! Nous vous contacterons très prochainement.');
form.reset();
});
}
});
</script>
</body>
</html>