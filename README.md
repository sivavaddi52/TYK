<!doctype html>
<html lang="en">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TYK Workforce Infra - Professional Manpower &amp; Infrastructure Solutions</title>
  <script src="/_sdk/element_sdk.js"></script>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
        body {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
        }
        
        html, body {
            height: 100%;
        }
        
        .gradient-bg {
            background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%);
        }
        
        .section-padding {
            padding: 4rem 1.5rem;
        }
        
        .card-hover {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .card-hover:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
        }
        
        .stat-number {
            font-size: 3rem;
            font-weight: 800;
            line-height: 1;
        }
        
        @media (max-width: 768px) {
            .section-padding {
                padding: 3rem 1rem;
            }
            .stat-number {
                font-size: 2rem;
            }
        }
    </style>
  <style>@view-transition { navigation: auto; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
 </head>
 <body><!-- Navigation -->
  <nav id="navbar" class="fixed w-full top-0 z-50 transition-all duration-300">
   <div class="max-w-7xl mx-auto px-6 py-4">
    <div class="flex justify-between items-center">
     <div class="flex items-center space-x-2">
      <div class="w-10 h-10 rounded-lg flex items-center justify-center text-white text-xl font-bold">
       <svg class="w-8 h-8" fill="currentColor" viewbox="0 0 24 24"><path d="M12 2L2 7v10c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V7l-10-5zm0 18c-3.86-.96-7-5.54-7-10V8.3l7-3.11 7 3.11V10c0 4.46-3.14 9.04-7 10z" /> <path d="M9 12l2 2 4-4" />
       </svg>
      </div><span id="nav-company-name" class="text-xl font-bold text-white">TYK Workforce Infra</span>
     </div>
     <div class="hidden md:flex space-x-8"><a href="#home" class="text-white hover:text-blue-200 transition-colors">Home</a> <a href="#about" class="text-white hover:text-blue-200 transition-colors">About</a> <a href="#services" class="text-white hover:text-blue-200 transition-colors">Services</a> <a href="#industries" class="text-white hover:text-blue-200 transition-colors">Industries</a> <a href="#contact" class="text-white hover:text-blue-200 transition-colors">Contact</a>
     </div><button id="mobile-menu-btn" class="md:hidden text-white">
      <svg class="w-6 h-6" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
      </svg></button>
    </div>
   </div>
   <div id="mobile-menu" class="hidden md:hidden bg-blue-900 px-6 py-4"><a href="#home" class="block py-2 text-white hover:text-blue-200">Home</a> <a href="#about" class="block py-2 text-white hover:text-blue-200">About</a> <a href="#services" class="block py-2 text-white hover:text-blue-200">Services</a> <a href="#industries" class="block py-2 text-white hover:text-blue-200">Industries</a> <a href="#contact" class="block py-2 text-white hover:text-blue-200">Contact</a>
   </div>
  </nav><!-- Hero Section -->
  <section id="home" class="gradient-bg text-white min-h-full flex items-center">
   <div class="max-w-7xl mx-auto px-6 py-32 text-center">
    <h1 id="hero-headline" class="text-5xl md:text-6xl font-bold mb-6 leading-tight">Powering Industries with Skilled Workforce</h1>
    <p id="hero-subheadline" class="text-xl md:text-2xl mb-8 text-blue-100 max-w-3xl mx-auto">Trusted manpower solutions for MNCs, power plants, and large-scale industrial projects across India</p>
    <div class="flex flex-col sm:flex-row gap-4 justify-center"><a href="#contact" class="bg-white text-blue-900 px-8 py-4 rounded-lg font-semibold hover:bg-blue-50 transition-colors"> Get Started </a> <a href="#services" class="border-2 border-white text-white px-8 py-4 rounded-lg font-semibold hover:bg-white hover:text-blue-900 transition-colors"> Our Services </a>
    </div><!-- Stats -->
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-20">
     <div class="bg-white bg-opacity-10 backdrop-blur-sm rounded-xl p-6">
      <div class="stat-number text-white">
       10+
      </div>
      <p class="text-blue-100 text-lg mt-2">Years of Excellence</p>
     </div>
     <div class="bg-white bg-opacity-10 backdrop-blur-sm rounded-xl p-6">
      <div class="stat-number text-white">
       200+
      </div>
      <p class="text-blue-100 text-lg mt-2">Projects Completed</p>
     </div>
     <div class="bg-white bg-opacity-10 backdrop-blur-sm rounded-xl p-6">
      <div class="stat-number text-white">
       2000+
      </div>
      <p class="text-blue-100 text-lg mt-2">Workforce Deployed</p>
     </div>
    </div>
   </div>
  </section><!-- About Section -->
  <section id="about" class="section-padding bg-white">
   <div class="max-w-7xl mx-auto">
    <div class="text-center mb-16">
     <h2 id="about-headline" class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">About TYK Workforce Infra</h2>
     <div class="w-24 h-1 bg-blue-600 mx-auto"></div>
    </div>
    <div class="grid md:grid-cols-2 gap-12 items-center">
     <div>
      <h3 class="text-3xl font-bold text-gray-900 mb-6">Your Trusted Partner in Industrial Manpower Solutions</h3>
      <p class="text-gray-700 text-lg mb-6 leading-relaxed">With over <strong>10 years of proven expertise</strong>, TYK Workforce Infra stands as a leading provider of comprehensive manpower outsourcing and infrastructure support services across India.</p>
      <p class="text-gray-700 text-lg mb-6 leading-relaxed">We specialize in delivering skilled, semi-skilled, and un-skilled workforce to power plants, manufacturing industries, and large-scale construction projects. Our commitment to <strong>safety, reliability, and on-time deployment</strong> has made us the preferred partner for critical industrial operations.</p>
      <p class="text-gray-700 text-lg leading-relaxed">From EPC projects to shutdown operations, we ensure seamless workforce integration, complete compliance, and exceptional project efficiency.</p>
     </div>
     <div class="grid grid-cols-2 gap-6">
      <div class="bg-blue-50 p-6 rounded-xl">
       <div class="text-4xl mb-3">
        🎯
       </div>
       <h4 class="font-bold text-gray-900 mb-2">Quality First</h4>
       <p class="text-gray-600 text-sm">Rigorously vetted workforce ensuring top performance</p>
      </div>
      <div class="bg-blue-50 p-6 rounded-xl">
       <div class="text-4xl mb-3">
        ⚡
       </div>
       <h4 class="font-bold text-gray-900 mb-2">Rapid Deployment</h4>
       <p class="text-gray-600 text-sm">Quick mobilization for urgent project needs</p>
      </div>
      <div class="bg-blue-50 p-6 rounded-xl">
       <div class="text-4xl mb-3">
        🛡️
       </div>
       <h4 class="font-bold text-gray-900 mb-2">Safety Focused</h4>
       <p class="text-gray-600 text-sm">Comprehensive safety training and protocols</p>
      </div>
      <div class="bg-blue-50 p-6 rounded-xl">
       <div class="text-4xl mb-3">
        📋
       </div>
       <h4 class="font-bold text-gray-900 mb-2">Full Compliance</h4>
       <p class="text-gray-600 text-sm">100% adherence to labor laws and regulations</p>
      </div>
     </div>
    </div>
   </div>
  </section><!-- Services Section -->
  <section id="services" class="section-padding bg-gray-50">
   <div class="max-w-7xl mx-auto">
    <div class="text-center mb-16">
     <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">Our Services</h2>
     <p class="text-xl text-gray-600 max-w-2xl mx-auto">Comprehensive workforce solutions tailored to your industrial needs</p>
     <div class="w-24 h-1 bg-blue-600 mx-auto mt-4"></div>
    </div>
    <div class="grid md:grid-cols-3 gap-8">
     <div class="bg-white rounded-xl p-8 card-hover shadow-lg">
      <div class="w-16 h-16 bg-blue-100 rounded-lg flex items-center justify-center mb-6">
       <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewbox="0 0 24 24"><path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z" />
       </svg>
      </div>
      <h3 class="text-2xl font-bold text-gray-900 mb-4">Skilled Workforce Supply</h3>
      <p class="text-gray-600 leading-relaxed">Certified technicians, engineers, and specialists for power plants, manufacturing units, and technical operations. Pre-trained and project-ready.</p>
     </div>
     <div class="bg-white rounded-xl p-8 card-hover shadow-lg">
      <div class="w-16 h-16 bg-blue-100 rounded-lg flex items-center justify-center mb-6">
       <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewbox="0 0 24 24"><path d="M20 6h-2.18c.11-.31.18-.65.18-1 0-1.66-1.34-3-3-3-1.05 0-1.96.54-2.5 1.35l-.5.67-.5-.68C10.96 2.54 10.05 2 9 2 7.34 2 6 3.34 6 5c0 .35.07.69.18 1H4c-1.11 0-1.99.89-1.99 2L2 19c0 1.11.89 2 2 2h16c1.11 0 2-.89 2-2V8c0-1.11-.89-2-2-2zm-5-2c.55 0 1 .45 1 1s-.45 1-1 1-1-.45-1-1 .45-1 1-1zM9 4c.55 0 1 .45 1 1s-.45 1-1 1-1-.45-1-1 .45-1 1-1zm11 15H4v-2h16v2zm0-5H4V8h5.08L7 10.83 8.62 12 11 8.76l1-1.36 1 1.36L15.38 12 17 10.83 14.92 8H20v6z" />
       </svg>
      </div>
      <h3 class="text-2xl font-bold text-gray-900 mb-4">Semi-Skilled Manpower</h3>
      <p class="text-gray-600 leading-relaxed">Trained operators, helpers, and support staff for construction sites, civil works, and industrial facilities. Reliable and efficient workforce.</p>
     </div>
     <div class="bg-white rounded-xl p-8 card-hover shadow-lg">
      <div class="w-16 h-16 bg-blue-100 rounded-lg flex items-center justify-center mb-6">
       <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewbox="0 0 24 24"><path d="M22.7 19l-9.1-9.1c.9-2.3.4-5-1.5-6.9-2-2-5-2.4-7.4-1.3L9 6 6 9 1.6 4.7C.4 7.1.9 10.1 2.9 12.1c1.9 1.9 4.6 2.4 6.9 1.5l9.1 9.1c.4.4 1 .4 1.4 0l2.3-2.3c.5-.4.5-1.1.1-1.4z" />
       </svg>
      </div>
      <h3 class="text-2xl font-bold text-gray-900 mb-4">EPC &amp; Project Support</h3>
      <p class="text-gray-600 leading-relaxed">Complete manpower solutions for Engineering, Procurement, and Construction projects. From planning to execution with full compliance.</p>
     </div>
     <div class="bg-white rounded-xl p-8 card-hover shadow-lg">
      <div class="w-16 h-16 bg-blue-100 rounded-lg flex items-center justify-center mb-6">
       <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewbox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-2 15l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z" />
       </svg>
      </div>
      <h3 class="text-2xl font-bold text-gray-900 mb-4">Shutdown Operations</h3>
      <p class="text-gray-600 leading-relaxed">Specialized teams for planned shutdowns, maintenance turnarounds, and emergency repairs. Minimizing downtime with expert workforce.</p>
     </div>
     <div class="bg-white rounded-xl p-8 card-hover shadow-lg">
      <div class="w-16 h-16 bg-blue-100 rounded-lg flex items-center justify-center mb-6">
       <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewbox="0 0 24 24"><path d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zM9 17H7v-7h2v7zm4 0h-2V7h2v10zm4 0h-2v-4h2v4z" />
       </svg>
      </div>
      <h3 class="text-2xl font-bold text-gray-900 mb-4">Infrastructure Support</h3>
      <p class="text-gray-600 leading-relaxed">End-to-end infrastructure services including civil construction, mechanical works, electrical installations, and facility management.</p>
     </div>
     <div class="bg-white rounded-xl p-8 card-hover shadow-lg">
      <div class="w-16 h-16 bg-blue-100 rounded-lg flex items-center justify-center mb-6">
       <svg class="w-8 h-8 text-blue-600" fill="currentColor" viewbox="0 0 24 24"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z" />
       </svg>
      </div>
      <h3 class="text-2xl font-bold text-gray-900 mb-4">On-Site Management</h3>
      <p class="text-gray-600 leading-relaxed">Dedicated supervisors and project coordinators ensuring smooth operations, safety compliance, and quality control at your site.</p>
     </div>
    </div>
   </div>
  </section><!-- Industries Section -->
  <section id="industries" class="section-padding bg-white">
   <div class="max-w-7xl mx-auto">
    <div class="text-center mb-16">
     <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">Industries We Serve</h2>
     <p class="text-xl text-gray-600 max-w-2xl mx-auto">Delivering excellence across diverse industrial sectors</p>
     <div class="w-24 h-1 bg-blue-600 mx-auto mt-4"></div>
    </div>
    <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
     <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-6 rounded-xl text-center">
      <div class="text-5xl mb-4">
       ⚡
      </div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Power Plants</h3>
      <p class="text-gray-600 text-sm">Thermal, hydro, and renewable energy facilities</p>
     </div>
     <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-6 rounded-xl text-center">
      <div class="text-5xl mb-4">
       🏭
      </div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Manufacturing</h3>
      <p class="text-gray-600 text-sm">Automotive, steel, cement, and heavy industries</p>
     </div>
     <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-6 rounded-xl text-center">
      <div class="text-5xl mb-4">
       🏗️
      </div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Construction</h3>
      <p class="text-gray-600 text-sm">Commercial, residential, and infrastructure projects</p>
     </div>
     <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-6 rounded-xl text-center">
      <div class="text-5xl mb-4">
       🔧
      </div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Oil &amp; Gas</h3>
      <p class="text-gray-600 text-sm">Refineries, pipelines, and petrochemical plants</p>
     </div>
     <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-6 rounded-xl text-center">
      <div class="text-5xl mb-4">
       🏢
      </div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">MNCs</h3>
      <p class="text-gray-600 text-sm">Global corporations and enterprise facilities</p>
     </div>
     <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-6 rounded-xl text-center">
      <div class="text-5xl mb-4">
       ⚙️
      </div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Engineering</h3>
      <p class="text-gray-600 text-sm">Mechanical, electrical, and civil engineering works</p>
     </div>
     <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-6 rounded-xl text-center">
      <div class="text-5xl mb-4">
       🚧
      </div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Infrastructure</h3>
      <p class="text-gray-600 text-sm">Roads, bridges, metros, and public works</p>
     </div>
     <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-6 rounded-xl text-center">
      <div class="text-5xl mb-4">
       🏭
      </div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Chemical Plants</h3>
      <p class="text-gray-600 text-sm">Process industries and chemical manufacturing</p>
     </div>
    </div>
   </div>
  </section><!-- Why Choose Us Section -->
  <section class="section-padding bg-gray-50">
   <div class="max-w-7xl mx-auto">
    <div class="text-center mb-16">
     <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">Why Choose TYK Workforce Infra</h2>
     <p class="text-xl text-gray-600 max-w-2xl mx-auto">Your success is built on our commitment to excellence</p>
     <div class="w-24 h-1 bg-blue-600 mx-auto mt-4"></div>
    </div>
    <div class="grid md:grid-cols-2 gap-8">
     <div class="flex gap-4">
      <div class="flex-shrink-0">
       <div class="w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center text-white font-bold text-xl">
        ✓
       </div>
      </div>
      <div>
       <h3 class="text-xl font-bold text-gray-900 mb-2">Proven Track Record</h3>
       <p class="text-gray-600">Over 10 years of successful project delivery across India with 500+ completed projects and 100% client satisfaction.</p>
      </div>
     </div>
     <div class="flex gap-4">
      <div class="flex-shrink-0">
       <div class="w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center text-white font-bold text-xl">
        ✓
       </div>
      </div>
      <div>
       <h3 class="text-xl font-bold text-gray-900 mb-2">Quality Workforce</h3>
       <p class="text-gray-600">Rigorously screened, trained, and certified professionals ensuring top-tier performance and reliability on every project.</p>
      </div>
     </div>
     <div class="flex gap-4">
      <div class="flex-shrink-0">
       <div class="w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center text-white font-bold text-xl">
        ✓
       </div>
      </div>
      <div>
       <h3 class="text-xl font-bold text-gray-900 mb-2">Rapid Deployment</h3>
       <p class="text-gray-600">Quick mobilization capabilities with pre-trained workforce ready for immediate deployment to meet urgent project timelines.</p>
      </div>
     </div>
     <div class="flex gap-4">
      <div class="flex-shrink-0">
       <div class="w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center text-white font-bold text-xl">
        ✓
       </div>
      </div>
      <div>
       <h3 class="text-xl font-bold text-gray-900 mb-2">Safety First Culture</h3>
       <p class="text-gray-600">Comprehensive safety training, strict protocol adherence, and zero-compromise approach to workplace safety standards.</p>
      </div>
     </div>
     <div class="flex gap-4">
      <div class="flex-shrink-0">
       <div class="w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center text-white font-bold text-xl">
        ✓
       </div>
      </div>
      <div>
       <h3 class="text-xl font-bold text-gray-900 mb-2">Full Compliance</h3>
       <p class="text-gray-600">100% adherence to labor laws, statutory requirements, and industry regulations with complete documentation support.</p>
      </div>
     </div>
     <div class="flex gap-4">
      <div class="flex-shrink-0">
       <div class="w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center text-white font-bold text-xl">
        ✓
       </div>
      </div>
      <div>
       <h3 class="text-xl font-bold text-gray-900 mb-2">Cost Efficiency</h3>
       <p class="text-gray-600">Optimized workforce solutions that reduce overhead costs while maintaining quality and improving project profitability.</p>
      </div>
     </div>
     <div class="flex gap-4">
      <div class="flex-shrink-0">
       <div class="w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center text-white font-bold text-xl">
        ✓
       </div>
      </div>
      <div>
       <h3 class="text-xl font-bold text-gray-900 mb-2">24/7 Support</h3>
       <p class="text-gray-600">Round-the-clock project support and dedicated account management ensuring seamless operations and quick issue resolution.</p>
      </div>
     </div>
     <div class="flex gap-4">
      <div class="flex-shrink-0">
       <div class="w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center text-white font-bold text-xl">
        ✓
       </div>
      </div>
      <div>
       <h3 class="text-xl font-bold text-gray-900 mb-2">Pan-India Presence</h3>
       <p class="text-gray-600">Extensive network across major industrial hubs enabling local support and nationwide project execution capabilities.</p>
      </div>
     </div>
    </div>
   </div>
  </section><!-- Process Section -->
  <section class="section-padding bg-white">
   <div class="max-w-7xl mx-auto">
    <div class="text-center mb-16">
     <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">Our Process</h2>
     <p class="text-xl text-gray-600 max-w-2xl mx-auto">Streamlined approach for seamless workforce deployment</p>
     <div class="w-24 h-1 bg-blue-600 mx-auto mt-4"></div>
    </div>
    <div class="grid md:grid-cols-4 gap-8">
     <div class="text-center">
      <div class="w-20 h-20 bg-blue-600 rounded-full flex items-center justify-center text-white text-3xl font-bold mx-auto mb-6">
       1
      </div>
      <h3 class="text-xl font-bold text-gray-900 mb-3">Requirement Analysis</h3>
      <p class="text-gray-600">We understand your project needs, skill requirements, timeline, and specific workforce specifications.</p>
     </div>
     <div class="text-center">
      <div class="w-20 h-20 bg-blue-600 rounded-full flex items-center justify-center text-white text-3xl font-bold mx-auto mb-6">
       2
      </div>
      <h3 class="text-xl font-bold text-gray-900 mb-3">Workforce Selection</h3>
      <p class="text-gray-600">Rigorous screening and selection of qualified candidates matching your exact project requirements.</p>
     </div>
     <div class="text-center">
      <div class="w-20 h-20 bg-blue-600 rounded-full flex items-center justify-center text-white text-3xl font-bold mx-auto mb-6">
       3
      </div>
      <h3 class="text-xl font-bold text-gray-900 mb-3">Training &amp; Compliance</h3>
      <p class="text-gray-600">Comprehensive safety training, documentation, and compliance verification before deployment.</p>
     </div>
     <div class="text-center">
      <div class="w-20 h-20 bg-blue-600 rounded-full flex items-center justify-center text-white text-3xl font-bold mx-auto mb-6">
       4
      </div>
      <h3 class="text-xl font-bold text-gray-900 mb-3">Deployment &amp; Support</h3>
      <p class="text-gray-600">On-time workforce deployment with ongoing supervision, quality monitoring, and 24/7 support.</p>
     </div>
    </div>
   </div>
  </section><!-- Testimonials Section -->
  <section class="section-padding bg-gray-50">
   <div class="max-w-7xl mx-auto">
    <div class="text-center mb-16">
     <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">Client Testimonials</h2>
     <p class="text-xl text-gray-600 max-w-2xl mx-auto">Trusted by industry leaders across India</p>
     <div class="w-24 h-1 bg-blue-600 mx-auto mt-4"></div>
    </div>
    <div class="grid md:grid-cols-3 gap-8">
     <div class="bg-white p-8 rounded-xl shadow-lg">
      <div class="flex mb-4"><span class="text-yellow-400 text-2xl">★★★★★</span>
      </div>
      <p class="text-gray-700 mb-6 italic">"TYK Workforce Infra provided exceptional manpower support for our power plant shutdown. Their team was professional, safety-conscious, and delivered ahead of schedule."</p>
      <div class="border-t pt-4">
       <p class="font-bold text-gray-900">Rajesh Kumar</p>
       <p class="text-gray-600 text-sm">Project Manager, Leading Power Corporation</p>
      </div>
     </div>
     <div class="bg-white p-8 rounded-xl shadow-lg">
      <div class="flex mb-4"><span class="text-yellow-400 text-2xl">★★★★★</span>
      </div>
      <p class="text-gray-700 mb-6 italic">"We've partnered with TYK for multiple EPC projects. Their ability to mobilize skilled workforce quickly and maintain quality standards is unmatched in the industry."</p>
      <div class="border-t pt-4">
       <p class="font-bold text-gray-900">Amit Sharma</p>
       <p class="text-gray-600 text-sm">Operations Head, MNC Manufacturing Unit</p>
      </div>
     </div>
     <div class="bg-white p-8 rounded-xl shadow-lg">
      <div class="flex mb-4"><span class="text-yellow-400 text-2xl">★★★★★</span>
      </div>
      <p class="text-gray-700 mb-6 italic">"Reliable, compliant, and efficient. TYK has been our go-to partner for construction manpower for over 5 years. Their commitment to safety is exemplary."</p>
      <div class="border-t pt-4">
       <p class="font-bold text-gray-900">Priya Desai</p>
       <p class="text-gray-600 text-sm">Site Director, Infrastructure Development Company</p>
      </div>
     </div>
    </div>
   </div>
  </section><!-- Contact Section -->
  <section id="contact" class="section-padding gradient-bg text-white">
   <div class="max-w-7xl mx-auto">
    <div class="text-center mb-16">
     <h2 class="text-4xl md:text-5xl font-bold mb-4">Get In Touch</h2>
     <p class="text-xl text-blue-100 max-w-2xl mx-auto">Ready to power your project with skilled workforce? Contact us today</p>
     <div class="w-24 h-1 bg-white mx-auto mt-4"></div>
    </div>
    <div class="grid md:grid-cols-2 gap-12">
     <div>
      <h3 class="text-2xl font-bold mb-6">Contact Information</h3>
      <div class="space-y-6">
       <div class="flex items-start gap-4">
        <div class="w-12 h-12 bg-white bg-opacity-20 rounded-lg flex items-center justify-center flex-shrink-0">
         <svg class="w-6 h-6" fill="currentColor" viewbox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z" />
         </svg>
        </div>
        <div>
         <p class="font-semibold mb-1">Email</p>
         <p id="contact-email-display" class="text-blue-100">yedukondaluservices@gmail.com</p>
        </div>
       </div>
       <div class="flex items-start gap-4">
        <div class="w-12 h-12 bg-white bg-opacity-20 rounded-lg flex items-center justify-center flex-shrink-0">
         <svg class="w-6 h-6" fill="currentColor" viewbox="0 0 24 24"><path d="M6.62 10.79c1.44 2.83 3.76 5.14 6.59 6.59l2.2-2.2c.27-.27.67-.36 1.02-.24 1.12.37 2.33.57 3.57.57.55 0 1 .45 1 1V20c0 .55-.45 1-1 1-9.39 0-17-7.61-17-17 0-.55.45-1 1-1h3.5c.55 0 1 .45 1 1 0 1.25.2 2.45.57 3.57.11.35.03.74-.25 1.02l-2.2 2.2z" />
         </svg>
        </div>
        <div>
         <p class="font-semibold mb-1">Phone</p>
         <p id="contact-phone-display" class="text-blue-100">+91 9666344155</p>
        </div>
       </div>
       <div class="flex items-start gap-4">
        <div class="w-12 h-12 bg-white bg-opacity-20 rounded-lg flex items-center justify-center flex-shrink-0">
         <svg class="w-6 h-6" fill="currentColor" viewbox="0 0 24 24"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z" />
         </svg>
        </div>
        <div>
         <p class="font-semibold mb-1">Address</p>
         <p class="text-blue-100">Gummaladibba Village, Thamminapatnam Post<br>
          Chilakur Mandel, Nellore District <br> Andhra Pradesh-524412</p>
        </div>
       </div>
      </div>
      <div class="mt-8">
       <p class="font-semibold mb-4">Business Hours</p>
       <p class="text-blue-100">Monday - Saturday: 9:00 AM - 6:00 PM</p>
       <p class="text-blue-100">24/7 Emergency Support Available</p>
      </div>
     </div>
     <div class="bg-white bg-opacity-10 backdrop-blur-sm rounded-xl p-8">
      <h3 class="text-2xl font-bold mb-6">Send Us a Message</h3>
      <form id="contact-form" class="space-y-4">
       <div><label class="block text-sm font-semibold mb-2">Full Name</label> <input type="text" required class="w-full px-4 py-3 rounded-lg bg-white bg-opacity-20 border border-white border-opacity-30 text-white placeholder-blue-200 focus:outline-none focus:ring-2 focus:ring-white" placeholder="Your name">
       </div>
       <div><label class="block text-sm font-semibold mb-2">Email Address</label> <input type="email" required class="w-full px-4 py-3 rounded-lg bg-white bg-opacity-20 border border-white border-opacity-30 text-white placeholder-blue-200 focus:outline-none focus:ring-2 focus:ring-white" placeholder="your@email.com">
       </div>
       <div><label class="block text-sm font-semibold mb-2">Phone Number</label> <input type="tel" required class="w-full px-4 py-3 rounded-lg bg-white bg-opacity-20 border border-white border-opacity-30 text-white placeholder-blue-200 focus:outline-none focus:ring-2 focus:ring-white" placeholder="+91 XXXXX XXXXX">
       </div>
       <div><label class="block text-sm font-semibold mb-2">Project Requirements</label> <textarea required rows="4" class="w-full px-4 py-3 rounded-lg bg-white bg-opacity-20 border border-white border-opacity-30 text-white placeholder-blue-200 focus:outline-none focus:ring-2 focus:ring-white" placeholder="Tell us about your manpower needs..."></textarea>
       </div><button type="submit" class="w-full bg-white text-blue-900 px-8 py-4 rounded-lg font-semibold hover:bg-blue-50 transition-colors"> Submit Inquiry </button>
      </form>
      <div id="form-message" class="mt-4 p-4 rounded-lg hidden"></div>
     </div>
    </div>
   </div>
  </section><!-- Footer -->
  <footer class="bg-gray-900 text-white py-12">
   <div class="max-w-7xl mx-auto px-6">
    <div class="grid md:grid-cols-4 gap-8 mb-8">
     <div>
      <div class="flex items-center space-x-2 mb-4">
       <div class="w-8 h-8 bg-blue-600 rounded-lg flex items-center justify-center">
        <svg class="w-5 h-5" fill="currentColor" viewbox="0 0 24 24"><path d="M12 2L2 7v10c0 5.55 3.84 10.74 9 12 5.16-1.26 9-6.45 9-12V7l-10-5z" />
        </svg>
       </div><span id="footer-company-name" class="font-bold text-lg">TYK Workforce Infra</span>
      </div>
      <p class="text-gray-400 text-sm">Powering industries with skilled workforce solutions for over a decade.</p>
     </div>
     <div>
      <h4 class="font-bold mb-4">Quick Links</h4>
      <ul class="space-y-2 text-gray-400 text-sm">
       <li><a href="#home" class="hover:text-white transition-colors">Home</a></li>
       <li><a href="#about" class="hover:text-white transition-colors">About Us</a></li>
       <li><a href="#services" class="hover:text-white transition-colors">Services</a></li>
       <li><a href="#industries" class="hover:text-white transition-colors">Industries</a></li>
      </ul>
     </div>
     <div>
      <h4 class="font-bold mb-4">Services</h4>
      <ul class="space-y-2 text-gray-400 text-sm">
       <li>Skilled Workforce</li>
       <li>Semi-Skilled Manpower</li>
       <li>EPC Support</li>
       <li>Shutdown Operations</li>
      </ul>
     </div>
     <div>
      <h4 class="font-bold mb-4">Contact</h4>
      <ul class="space-y-2 text-gray-400 text-sm">
       <li id="footer-email">yedukondaluservices@gmail.com</li>
       <li id="footer-phone">+91 9666344155</li>
       <li>Pan-India Operations</li>
      </ul>
     </div>
    </div>
    <div class="border-t border-gray-800 pt-8 text-center text-gray-400 text-sm">
     <p>© 2024 TYK Workforce Infra. All rights reserved. | Trusted Manpower Solutions Provider</p>
    </div>
   </div>
  </footer>
  <script>
        const defaultConfig = {
            company_name: "TYK Workforce Infra",
            hero_headline: "Powering Industries with Skilled Workforce",
            hero_subheadline: "Trusted manpower solutions for MNCs, power plants, and large-scale industrial projects across India",
            about_headline: "About TYK Workforce Infra",
            contact_email: "yedukondaluservices@gmail.com",
            contact_phone: "+91 9666344155",
            background_color: "#1e3a8a",
            surface_color: "#ffffff",
            text_color: "#111827",
            primary_action_color: "#2563eb",
            secondary_action_color: "#3b82f6",
            font_family: "Inter",
            font_size: 16
        };

        let config = { ...defaultConfig };

        async function onConfigChange(newConfig) {
            const customFont = newConfig.font_family || defaultConfig.font_family;
            const baseSize = newConfig.font_size || defaultConfig.font_size;
            const baseFontStack = '-apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif';
            
            document.body.style.fontFamily = `${customFont}, ${baseFontStack}`;
            document.body.style.fontSize = `${baseSize}px`;
            
            const backgroundColor = newConfig.background_color || defaultConfig.background_color;
            const surfaceColor = newConfig.surface_color || defaultConfig.surface_color;
            const textColor = newConfig.text_color || defaultConfig.text_color;
            const primaryActionColor = newConfig.primary_action_color || defaultConfig.primary_action_color;
            const secondaryActionColor = newConfig.secondary_action_color || defaultConfig.secondary_action_color;
            
            const gradientSections = document.querySelectorAll('.gradient-bg');
            gradientSections.forEach(section => {
                section.style.background = `linear-gradient(135deg, ${backgroundColor} 0%, ${secondaryActionColor} 100%)`;
            });
            
            const navbar = document.getElementById('navbar');
            navbar.style.background = `linear-gradient(135deg, ${backgroundColor} 0%, ${secondaryActionColor} 100%)`;
            
            const cards = document.querySelectorAll('.bg-white');
            cards.forEach(card => {
                if (!card.closest('.gradient-bg')) {
                    card.style.backgroundColor = surfaceColor;
                }
            });
            
            const textElements = document.querySelectorAll('h1, h2, h3, h4, p:not(.text-white):not(.text-blue-100):not(.text-blue-200):not(.text-gray-400)');
            textElements.forEach(el => {
                if (!el.closest('.gradient-bg') && !el.closest('nav') && !el.closest('footer')) {
                    el.style.color = textColor;
                }
            });
            
            const primaryButtons = document.querySelectorAll('a[href="#contact"]');
            primaryButtons.forEach(btn => {
                if (btn.classList.contains('bg-white')) {
                    btn.style.backgroundColor = surfaceColor;
                    btn.style.color = primaryActionColor;
                }
            });
            
            const secondaryButtons = document.querySelectorAll('a[href="#services"]');
            secondaryButtons.forEach(btn => {
                btn.style.borderColor = surfaceColor;
                btn.style.color = surfaceColor;
            });
            
            const companyName = newConfig.company_name || defaultConfig.company_name;
            document.getElementById('nav-company-name').textContent = companyName;
            document.getElementById('footer-company-name').textContent = companyName;
            
            const heroHeadline = newConfig.hero_headline || defaultConfig.hero_headline;
            document.getElementById('hero-headline').textContent = heroHeadline;
            document.getElementById('hero-headline').style.fontSize = `${baseSize * 3}px`;
            
            const heroSubheadline = newConfig.hero_subheadline || defaultConfig.hero_subheadline;
            document.getElementById('hero-subheadline').textContent = heroSubheadline;
            document.getElementById('hero-subheadline').style.fontSize = `${baseSize * 1.25}px`;
            
            const aboutHeadline = newConfig.about_headline || defaultConfig.about_headline;
            document.getElementById('about-headline').textContent = aboutHeadline;
            document.getElementById('about-headline').style.fontSize = `${baseSize * 2.5}px`;
            
            const contactEmail = newConfig.contact_email || defaultConfig.contact_email;
            document.getElementById('contact-email-display').textContent = contactEmail;
            document.getElementById('footer-email').textContent = contactEmail;
            
            const contactPhone = newConfig.contact_phone || defaultConfig.contact_phone;
            document.getElementById('contact-phone-display').textContent = contactPhone;
            document.getElementById('footer-phone').textContent = contactPhone;
            
            const allHeadings = document.querySelectorAll('h2');
            allHeadings.forEach(h => {
                h.style.fontSize = `${baseSize * 2.5}px`;
            });
            
            const allH3 = document.querySelectorAll('h3');
            allH3.forEach(h => {
                h.style.fontSize = `${baseSize * 1.5}px`;
            });
        }

        if (window.elementSdk) {
            window.elementSdk.init({
                defaultConfig,
                onConfigChange,
                mapToCapabilities: (config) => ({
                    recolorables: [
                        {
                            get: () => config.background_color || defaultConfig.background_color,
                            set: (value) => {
                                config.background_color = value;
                                window.elementSdk.setConfig({ background_color: value });
                            }
                        },
                        {
                            get: () => config.surface_color || defaultConfig.surface_color,
                            set: (value) => {
                                config.surface_color = value;
                                window.elementSdk.setConfig({ surface_color: value });
                            }
                        },
                        {
                            get: () => config.text_color || defaultConfig.text_color,
                            set: (value) => {
                                config.text_color = value;
                                window.elementSdk.setConfig({ text_color: value });
                            }
                        },
                        {
                            get: () => config.primary_action_color || defaultConfig.primary_action_color,
                            set: (value) => {
                                config.primary_action_color = value;
                                window.elementSdk.setConfig({ primary_action_color: value });
                            }
                        },
                        {
                            get: () => config.secondary_action_color || defaultConfig.secondary_action_color,
                            set: (value) => {
                                config.secondary_action_color = value;
                                window.elementSdk.setConfig({ secondary_action_color: value });
                            }
                        }
                    ],
                    borderables: [],
                    fontEditable: {
                        get: () => config.font_family || defaultConfig.font_family,
                        set: (value) => {
                            config.font_family = value;
                            window.elementSdk.setConfig({ font_family: value });
                        }
                    },
                    fontSizeable: {
                        get: () => config.font_size || defaultConfig.font_size,
                        set: (value) => {
                            config.font_size = value;
                            window.elementSdk.setConfig({ font_size: value });
                        }
                    }
                }),
                mapToEditPanelValues: (config) => new Map([
                    ["company_name", config.company_name || defaultConfig.company_name],
                    ["hero_headline", config.hero_headline || defaultConfig.hero_headline],
                    ["hero_subheadline", config.hero_subheadline || defaultConfig.hero_subheadline],
                    ["about_headline", config.about_headline || defaultConfig.about_headline],
                    ["contact_email", config.contact_email || defaultConfig.contact_email],
                    ["contact_phone", config.contact_phone || defaultConfig.contact_phone]
                ])
            });
        }

        document.getElementById('mobile-menu-btn').addEventListener('click', () => {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', (e) => {
                e.preventDefault();
                const target = document.querySelector(anchor.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({ behavior: 'smooth' });
                    document.getElementById('mobile-menu').classList.add('hidden');
                }
            });
        });

        window.addEventListener('scroll', () => {
            const navbar = document.getElementById('navbar');
            if (window.scrollY > 50) {
                navbar.style.backgroundColor = config.background_color || defaultConfig.background_color;
                navbar.style.boxShadow = '0 4px 6px rgba(0, 0, 0, 0.1)';
            } else {
                navbar.style.background = `linear-gradient(135deg, ${config.background_color || defaultConfig.background_color} 0%, ${config.secondary_action_color || defaultConfig.secondary_action_color} 100%)`;
                navbar.style.boxShadow = 'none';
            }
        });

        document.getElementById('contact-form').addEventListener('submit', (e) => {
            e.preventDefault();
            const messageDiv = document.getElementById('form-message');
            messageDiv.textContent = 'Thank you for your inquiry! We will contact you within 24 hours.';
            messageDiv.className = 'mt-4 p-4 rounded-lg bg-white bg-opacity-20 text-white';
            messageDiv.classList.remove('hidden');
            e.target.reset();
            
            setTimeout(() => {
                messageDiv.classList.add('hidden');
            }, 5000);
        });
    </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'99c428fca760c151',t:'MTc2Mjc2MzEzNS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
