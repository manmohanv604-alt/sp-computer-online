<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SP Computer Online | CSC & Digital Seva Kendra</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap');
        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: #090d16;
            color: #f8fafc;
        }
        .glass-card {
            background: rgba(17, 25, 40, 0.75);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.08);
        }
        .gradient-text {
            background: linear-gradient(135deg, #38bdf8 0%, #818cf8 50%, #c084fc 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="antialiased selection:bg-sky-500 selection:text-white">

    <!-- Top Notice Bar -->
    <div class="bg-gradient-to-r from-sky-600 via-indigo-600 to-purple-600 text-white text-xs sm:text-sm py-2 px-4 text-center font-medium">
        <span>🚀 Official CSC & Online Digital Services — Fast, Secure & Trusted Support</span>
    </div>

    <!-- Navbar -->
    <header class="sticky top-0 z-50 glass-card border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16 sm:h-20">
                <!-- Logo -->
                <a href="#" class="flex items-center space-x-3">
                    <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-sky-500 to-indigo-600 flex items-center justify-center shadow-lg shadow-sky-500/20">
                        <i class="fa-solid fa-laptop-code text-white text-lg"></i>
                    </div>
                    <div>
                        <span class="text-xl sm:text-2xl font-extrabold tracking-tight text-white">SP Computer <span class="text-sky-400">Online</span></span>
                        <p class="text-[10px] sm:text-xs text-slate-400 uppercase tracking-widest">Digital Seva & Jan Seva Kendra</p>
                    </div>
                </a>

                <!-- Desktop Navigation -->
                <nav class="hidden md:flex space-x-8 text-sm font-medium text-slate-300">
                    <a href="#home" class="hover:text-sky-400 transition">Home</a>
                    <a href="#services" class="hover:text-sky-400 transition">Services</a>
                    <a href="#packages" class="hover:text-sky-400 transition">Charges</a>
                    <a href="#contact" class="hover:text-sky-400 transition">Address & Support</a>
                </nav>

                <!-- CTA Button -->
                <div class="flex items-center space-x-3">
                    <button onclick="openModal('General Inquiry')" class="bg-sky-500 hover:bg-sky-400 text-slate-950 font-bold px-4 py-2 sm:px-5 sm:py-2.5 rounded-xl text-xs sm:text-sm transition shadow-lg shadow-sky-500/25">
                        Apply Online
                    </button>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="relative overflow-hidden pt-16 pb-20 sm:pt-24 sm:pb-28">
        <div class="absolute top-0 left-1/2 -translate-x-1/2 w-[800px] h-[400px] bg-sky-500/10 blur-[120px] rounded-full pointer-events-none"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 text-center">
            <div class="inline-flex items-center space-x-2 px-3 py-1.5 rounded-full bg-slate-800/80 border border-slate-700 text-sky-400 text-xs font-semibold mb-6">
                <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
                <span>Mankapur to Maskanwa Road • Open Mon - Sat (9:00 AM - 8:00 PM)</span>
            </div>
            <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight text-white max-w-4xl mx-auto leading-tight">
                Sabhi Sarkari & Digital Kaam <br class="hidden sm:block" />
                <span class="gradient-text">Ek Hi Chhat Ke Niche</span>
            </h1>
            <p class="mt-6 text-base sm:text-lg text-slate-400 max-w-2xl mx-auto">
                PAN Card, Passport, Ayushman Card, Aay-Jati-Niwas Praman Patra, Online Exam Forms, Banking aur sabhi CSC services bina kisi jhanjhat ke turant karwayein.
            </p>
            <div class="mt-8 flex flex-col sm:flex-row justify-center gap-4">
                <a href="#services" class="bg-gradient-to-r from-sky-500 to-indigo-600 hover:from-sky-400 hover:to-indigo-500 text-white font-bold px-8 py-4 rounded-xl shadow-lg shadow-indigo-500/25 transition flex items-center justify-center space-x-2">
                    <span>Explore All Services</span>
                    <i class="fa-solid fa-arrow-right"></i>
                </a>
                <a href="#contact" class="glass-card hover:bg-slate-800/80 text-white font-semibold px-8 py-4 rounded-xl transition flex items-center justify-center space-x-2">
                    <i class="fa-solid fa-location-dot text-sky-400"></i>
                    <span>Visit Center Location</span>
                </a>
            </div>

            <!-- Quick Stats -->
            <div class="mt-16 grid grid-cols-2 md:grid-cols-4 gap-4 max-w-4xl mx-auto">
                <div class="glass-card p-5 rounded-2xl">
                    <div class="text-2xl sm:text-3xl font-extrabold text-sky-400">10,000+</div>
                    <div class="text-xs sm:text-sm text-slate-400 mt-1">Forms Processed</div>
                </div>
                <div class="glass-card p-5 rounded-2xl">
                    <div class="text-2xl sm:text-3xl font-extrabold text-indigo-400">100%</div>
                    <div class="text-xs sm:text-sm text-slate-400 mt-1">Data Privacy</div>
                </div>
                <div class="glass-card p-5 rounded-2xl">
                    <div class="text-2xl sm:text-3xl font-extrabold text-emerald-400">24 Hours</div>
                    <div class="text-xs sm:text-sm text-slate-400 mt-1">Fast PAN & Certificates</div>
                </div>
                <div class="glass-card p-5 rounded-2xl">
                    <div class="text-2xl sm:text-3xl font-extrabold text-purple-400">4.9 ★</div>
                    <div class="text-xs sm:text-sm text-slate-400 mt-1">Customer Rating</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 bg-slate-900/50 border-y border-slate-800/80">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white">Hamari Mukhya <span class="text-sky-400">Online Services</span></h2>
                <p class="mt-3 text-slate-400 text-sm sm:text-base">Kisi bhi service ke liye apply karne ya documents ki jankari lene ke liye service card par click karein.</p>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Service 1 -->
                <div class="glass-card p-6 rounded-2xl hover:border-sky-500/50 transition group">
                    <div class="w-12 h-12 rounded-xl bg-sky-500/10 text-sky-400 flex items-center justify-center text-xl mb-5 group-hover:scale-110 transition">
                        <i class="fa-solid fa-id-card"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white">PAN Card & Aadhaar Services</h3>
                    <p class="text-slate-400 text-sm mt-2 leading-relaxed">Naya PAN Card (NSDL/UTI), Name/DOB Correction, Lost PAN Reprint, aur Aadhaar PVC Card order & status check.</p>
                    <button onclick="openModal('PAN Card / Aadhaar Service')" class="mt-5 text-sky-400 hover:text-sky-300 text-sm font-semibold inline-flex items-center space-x-1">
                        <span>Request Service</span>
                        <i class="fa-solid fa-chevron-right text-xs"></i>
                    </button>
                </div>

                <!-- Service 2 -->
                <div class="glass-card p-6 rounded-2xl hover:border-indigo-500/50 transition group">
                    <div class="w-12 h-12 rounded-xl bg-indigo-500/10 text-indigo-400 flex items-center justify-center text-xl mb-5 group-hover:scale-110 transition">
                        <i class="fa-solid fa-file-shield"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white">e-District Certificates</h3>
                    <p class="text-slate-400 text-sm mt-2 leading-relaxed">Aay (Income), Jati (Caste), Niwas (Domicile) Praman Patra, Birth & Death Certificate aur Khatauni Nakal.</p>
                    <button onclick="openModal('Income / Caste / Domicile Certificate')" class="mt-5 text-indigo-400 hover:text-indigo-300 text-sm font-semibold inline-flex items-center space-x-1">
                        <span>Request Service</span>
                        <i class="fa-solid fa-chevron-right text-xs"></i>
                    </button>
                </div>

                <!-- Service 3 -->
                <div class="glass-card p-6 rounded-2xl hover:border-emerald-500/50 transition group">
                    <div class="w-12 h-12 rounded-xl bg-emerald-500/10 text-emerald-400 flex items-center justify-center text-xl mb-5 group-hover:scale-110 transition">
                        <i class="fa-solid fa-graduation-cap"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white">Online Exam & Scholarship</h3>
                    <p class="text-slate-400 text-sm mt-2 leading-relaxed">SSC, UP Police, Railway, NTA, College Admission, UP Scholarship Form aur Admit Card / Result Printout.</p>
                    <button onclick="openModal('Online Exam / Scholarship Form')" class="mt-5 text-emerald-400 hover:text-emerald-300 text-sm font-semibold inline-flex items-center space-x-1">
                        <span>Request Service</span>
                        <i class="fa-solid fa-chevron-right text-xs"></i>
                    </button>
                </div>

                <!-- Service 4 -->
                <div class="glass-card p-6 rounded-2xl hover:border-purple-500/50 transition group">
                    <div class="w-12 h-12 rounded-xl bg-purple-500/10 text-purple-400 flex items-center justify-center text-xl mb-5 group-hover:scale-110 transition">
                        <i class="fa-solid fa-passport"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white">Passport & Driving Licence</h3>
                    <p class="text-slate-400 text-sm mt-2 leading-relaxed">Fresh & Tatkal Passport Appointment, Learner & Permanent Driving Licence, RC Transfer aur Vehicle Insurance.</p>
                    <button onclick="openModal('Passport / Driving Licence')" class="mt-5 text-purple-400 hover:text-purple-300 text-sm font-semibold inline-flex items-center space-x-1">
                        <span>Request Service</span>
                        <i class="fa-solid fa-chevron-right text-xs"></i>
                    </button>
                </div>

                <!-- Service 5 -->
                <div class="glass-card p-6 rounded-2xl hover:border-amber-500/50 transition group">
                    <div class="w-12 h-12 rounded-xl bg-amber-500/10 text-amber-400 flex items-center justify-center text-xl mb-5 group-hover:scale-110 transition">
                        <i class="fa-solid fa-building-columns"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white">Banking, AEPS & Money Transfer</h3>
                    <p class="text-slate-400 text-sm mt-2 leading-relaxed">Aadhaar se Paisa Nikasi (AEPS), Domestic Money Transfer, Bijli Bill Payment, Mobile/DTH Recharge & Fastag.</p>
                    <button onclick="openModal('Banking & Bill Payment')" class="mt-5 text-amber-400 hover:text-amber-300 text-sm font-semibold inline-flex items-center space-x-1">
                        <span>Request Service</span>
                        <i class="fa-solid fa-chevron-right text-xs"></i>
                    </button>
                </div>

                <!-- Service 6 -->
                <div class="glass-card p-6 rounded-2xl hover:border-rose-500/50 transition group">
                    <div class="w-12 h-12 rounded-xl bg-rose-500/10 text-rose-400 flex items-center justify-center text-xl mb-5 group-hover:scale-110 transition">
                        <i class="fa-solid fa-print"></i>
                    </div>
                    <h3 class="text-xl font-bold text-white">Printing, Lamination & PVC Card</h3>
                    <p class="text-slate-400 text-sm mt-2 leading-relaxed">HD Color Printout, Urgent Passport Size Photo, Document Scanning, Spiral Binding aur Smart PVC Card Printing.</p>
                    <button onclick="openModal('Printing & PVC Card')" class="mt-5 text-rose-400 hover:text-rose-300 text-sm font-semibold inline-flex items-center space-x-1">
                        <span>Request Service</span>
                        <i class="fa-solid fa-chevron-right text-xs"></i>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Transparent Charges / Packages -->
    <section id="packages" class="py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-14">
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white">Standard <span class="text-sky-400">Service Charges</span></h2>
                <p class="mt-3 text-slate-400 text-sm">Transparent sarkari aur service charges — koi hidden fees nahi.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 max-w-5xl mx-auto">
                <div class="glass-card p-7 rounded-2xl border border-slate-800">
                    <div class="text-sm font-semibold text-sky-400 uppercase">Instant Identity</div>
                    <h3 class="text-2xl font-bold text-white mt-2">New PAN Card</h3>
                    <div class="mt-4 flex items-baseline">
                        <span class="text-3xl font-extrabold text-white">₹150</span>
                        <span class="text-slate-400 text-xs ml-2">(Govt Fee + Service)</span>
                    </div>
                    <ul class="mt-6 space-y-3 text-sm text-slate-300">
                        <li><i class="fa-solid fa-check text-emerald-400 mr-2"></i>e-PAN on Email in 3-4 Days</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-2"></i>Physical Card by Speed Post</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-2"></i>Photo & Signature Upload Included</li>
                    </ul>
                    <button onclick="openModal('New PAN Card - ₹150')" class="mt-7 w-full py-3 rounded-xl bg-slate-800 hover:bg-sky-500 hover:text-slate-950 font-semibold text-sm transition">Book Now</button>
                </div>

                <div class="glass-card p-7 rounded-2xl border-2 border-sky-500 relative shadow-xl shadow-sky-500/10">
                    <span class="absolute -top-3 right-6 bg-sky-500 text-slate-950 text-[10px] font-extrabold uppercase px-3 py-1 rounded-full">Most Popular</span>
                    <div class="text-sm font-semibold text-sky-400 uppercase">UP e-District</div>
                    <h3 class="text-2xl font-bold text-white mt-2">Aay / Jati / Niwas</h3>
                    <div class="mt-4 flex items-baseline">
                        <span class="text-3xl font-extrabold text-white">₹60</span>
                        <span class="text-slate-400 text-xs ml-2">Per Certificate</span>
                    </div>
                    <ul class="mt-6 space-y-3 text-sm text-slate-300">
                        <li><i class="fa-solid fa-check text-emerald-400 mr-2"></i>Official Tehsil Verification</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-2"></i>High-Quality Digital Print</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-2"></i>SMS & WhatsApp Status Update</li>
                    </ul>
                    <button onclick="openModal('e-District Certificate - ₹60')" class="mt-7 w-full py-3 rounded-xl bg-sky-500 hover:bg-sky-400 text-slate-950 font-bold text-sm transition">Book Now</button>
                </div>

                <div class="glass-card p-7 rounded-2xl border border-slate-800">
                    <div class="text-sm font-semibold text-indigo-400 uppercase">Career & Education</div>
                    <h3 class="text-2xl font-bold text-white mt-2">Online Form Filling</h3>
                    <div class="mt-4 flex items-baseline">
                        <span class="text-3xl font-extrabold text-white">₹50</span>
                        <span class="text-slate-400 text-xs ml-2">+ Actual Exam Fee</span>
                    </div>
                    <ul class="mt-6 space-y-3 text-sm text-slate-300">
                        <li><i class="fa-solid fa-check text-emerald-400 mr-2"></i>Error-Free Form Submission</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-2"></i>Photo/Sign Resize & Compression</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-2"></i>PDF Receipt on WhatsApp/Email</li>
                    </ul>
                    <button onclick="openModal('Online Exam Form - ₹50')" class="mt-7 w-full py-3 rounded-xl bg-slate-800 hover:bg-indigo-500 hover:text-white font-semibold text-sm transition">Book Now</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Address, Help & Customer Support Section -->
    <section id="contact" class="py-20 bg-slate-900/70 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-start">
                
                <!-- Left Column: Full Address & Customer Support Details -->
                <div>
                    <span class="text-sky-400 font-bold text-xs uppercase tracking-widest">Visit Our Center & Helpdesk</span>
                    <h2 class="text-3xl sm:text-4xl font-extrabold text-white mt-2">Address & <span class="text-sky-400">Customer Support</span></h2>
                    <p class="text-slate-400 text-sm sm:text-base mt-3">
                        Kisi bhi online form, document status ya technical support ke liye aap hamare center par aa sakte hain ya email ke zariye sampark kar sakte hain.
                    </p>

                    <div class="mt-8 space-y-5">
                        <!-- Center Office Address -->
                        <div class="glass-card p-5 rounded-2xl flex items-start space-x-4">
                            <div class="w-12 h-12 rounded-xl bg-sky-500/10 text-sky-400 flex items-center justify-center text-xl shrink-0 mt-1">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <h4 class="text-white font-bold text-base">SP Computer Online — Head Office</h4>
                                <p class="text-slate-300 text-sm mt-1 leading-relaxed">
                                    Mankapur to Maskanwa Road, Near Maa Gayatri PG College,<br>
                                    Gonda, Uttar Pradesh — <span class="text-sky-400 font-semibold">271305</span>
                                </p>
                                <a href="https://maps.google.com/?q=Maa+Gayatri+PG+College+Mankapur+Maskanwa+Road+271305" target="_blank" class="inline-flex items-center space-x-1 text-xs text-sky-400 hover:text-sky-300 font-semibold mt-2">
                                    <span>Open in Google Maps</span>
                                    <i class="fa-solid fa-arrow-up-right-from-square"></i>
                                </a>
                            </div>
                        </div>

                        <!-- Help & Customer Support Email -->
                        <div class="glass-card p-5 rounded-2xl flex items-start space-x-4">
                            <div class="w-12 h-12 rounded-xl bg-indigo-500/10 text-indigo-400 flex items-center justify-center text-xl shrink-0 mt-1">
                                <i class="fa-solid fa-headset"></i>
                            </div>
                            <div>
                                <h4 class="text-white font-bold text-base">Help & Customer Support</h4>
                                <p class="text-slate-400 text-xs mt-0.5">Documents bhejne ya complaint/support ke liye official email:</p>
                                <a href="mailto:avinashverma83741@gmail.com" class="inline-block text-sky-400 hover:text-sky-300 font-semibold text-sm sm:text-base mt-1.5 break-all">
                                    <i class="fa-solid fa-envelope mr-1.5"></i>avinashverma83741@gmail.com
                                </a>
                            </div>
                        </div>

                        <!-- Working Hours -->
                        <div class="glass-card p-5 rounded-2xl flex items-start space-x-4">
                            <div class="w-12 h-12 rounded-xl bg-emerald-500/10 text-emerald-400 flex items-center justify-center text-xl shrink-0 mt-1">
                                <i class="fa-solid fa-clock"></i>
                            </div>
                            <div>
                                <h4 class="text-white font-bold text-base">Working Hours</h4>
                                <p class="text-slate-300 text-sm mt-1">Monday – Saturday: 09:00 AM to 08:00 PM</p>
                                <p class="text-slate-400 text-xs mt-0.5">Sunday: Urgent Online Appointments Only</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Right Column: Quick Inquiry / Support Ticket Form -->
                <div class="glass-card p-6 sm:p-8 rounded-2xl border border-slate-800">
                    <h3 class="text-2xl font-bold text-white">Send a Support Message</h3>
                    <p class="text-slate-400 text-xs sm:text-sm mt-1">Apna naam aur kaam likhein — hamari team aapko email par turant reply karegi.</p>

                    <form onsubmit="submitSupportForm(event)" class="mt-6 space-y-4">
                        <div>
                            <label class="block text-xs font-semibold text-slate-300 uppercase mb-1.5">Full Name</label>
                            <input type="text" id="custName" required placeholder="Apna naam likhein" class="w-full bg-slate-900/90 border border-slate-700 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-sky-500">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-300 uppercase mb-1.5">Mobile Number</label>
                            <input type="tel" id="custPhone" required placeholder="10-digit mobile number" class="w-full bg-slate-900/90 border border-slate-700 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-sky-500">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-300 uppercase mb-1.5">Select Service</label>
                            <select id="custService" class="w-full bg-slate-900/90 border border-slate-700 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-sky-500">
                                <option>PAN Card / Aadhaar Service</option>
                                <option>Aay / Jati / Niwas Praman Patra</option>
                                <option>Online Exam / Scholarship Form</option>
                                <option>Passport / Driving Licence</option>
                                <option>Customer Support / Status Inquiry</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-300 uppercase mb-1.5">Message / Details</label>
                            <textarea id="custMsg" rows="3" required placeholder="Apni samasya ya service ki details likhein..." class="w-full bg-slate-900/90 border border-slate-700 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-sky-500"></textarea>
                        </div>
                        <button type="submit" class="w-full bg-gradient-to-r from-sky-500 to-indigo-600 hover:from-sky-400 hover:to-indigo-500 text-white font-bold py-3.5 rounded-xl shadow-lg shadow-sky-500/20 transition flex items-center justify-center space-x-2">
                            <i class="fa-solid fa-paper-plane"></i>
                            <span>Send to Customer Support</span>
                        </button>
                    </form>
                </div>

            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-950 border-t border-slate-800/80 py-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row justify-between items-center gap-4 text-center md:text-left">
            <div>
                <span class="text-lg font-extrabold text-white">SP Computer <span class="text-sky-400">Online</span></span>
                <p class="text-xs text-slate-400 mt-1">Mankapur to Maskanwa Road, Near Maa Gayatri PG College, PIN - 271305</p>
            </div>
            <div class="text-xs text-slate-400">
                <p>Help & Support: <a href="mailto:avinashverma83741@gmail.com" class="text-sky-400 hover:underline">avinashverma83741@gmail.com</a></p>
                <p class="mt-1">© 2026 SP Computer Online. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Service Booking Modal -->
    <div id="serviceModal" class="fixed inset-0 z-50 hidden bg-black/75 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="glass-card max-w-md w-full p-6 rounded-2xl border border-slate-700 relative">
            <button onclick="closeModal()" class="absolute top-4 right-4 text-slate-400 hover:text-white">
                <i class="fa-solid fa-xmark text-xl"></i>
            </button>
            <h3 class="text-xl font-bold text-white">Book Online Service</h3>
            <p id="modalServiceTitle" class="text-sky-400 text-sm font-semibold mt-1">Service Request</p>
            <form onsubmit="submitModalForm(event)" class="mt-5 space-y-4">
                <input type="text" id="modalName" required placeholder="Your Full Name" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-sky-500">
                <input type="tel" id="modalPhone" required placeholder="Your Mobile Number" class="w-full bg-slate-900 border border-slate-700 rounded-xl px-4 py-3 text-sm text-white focus:outline-none focus:border-sky-500">
                <button type="submit" class="w-full bg-sky-500 hover:bg-sky-400 text-slate-950 font-bold py-3 rounded-xl text-sm transition">
                    Send Request via Email Support
                </button>
            </form>
        </div>
    </div>

    <script>
        let selectedService = "General Inquiry";

        function openModal(serviceName) {
            selectedService = serviceName;
            document.getElementById('modalServiceTitle').innerText = serviceName;
            document.getElementById('serviceModal').classList.remove('hidden');
        }

        function closeModal() {
            document.getElementById('serviceModal').classList.add('hidden');
        }

        function submitSupportForm(e) {
            e.preventDefault();
            const name = document.getElementById('custName').value;
            const phone = document.getElementById('custPhone').value;
            const service = document.getElementById('custService').value;
            const msg = document.getElementById('custMsg').value;

            const subject = encodeURIComponent(`SP Computer Online Support: ${service} - ${name}`);
            const body = encodeURIComponent(`Name: ${name}\nMobile: ${phone}\nService: ${service}\nMessage: ${msg}`);
            window.location.href = `mailto:avinashverma83741@gmail.com?subject=${subject}&body=${body}`;
        }

        function submitModalForm(e) {
            e.preventDefault();
            const name = document.getElementById('modalName').value;
            const phone = document.getElementById('modalPhone').value;

            const subject = encodeURIComponent(`New Service Booking: ${selectedService}`);
            const body = encodeURIComponent(`Customer Name: ${name}\nMobile Number: ${phone}\nRequested Service: ${selectedService}\nCenter: SP Computer Online, Mankapur to Maskanwa Road (271305)`);
            window.location.href = `mailto:avinashverma83741@gmail.com?subject=${subject}&body=${body}`;
            closeModal();
        }
    </script>
</body>
</html>

