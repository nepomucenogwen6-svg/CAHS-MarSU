# CAHS-MarSU<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MSU - College of Allied Health Sciences</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .bg-msu-purple { background-color: #6B21A8; }
        .text-msu-yellow { color: #FACC15; }
        .border-msu-yellow { border-color: #FACC15; }
    </style>
</head>
<body class="bg-gray-50 font-sans">

    <nav class="bg-msu-purple p-4 text-white shadow-lg">
        <div class="container mx-auto flex justify-between items-center">
            <h1 class="font-bold text-xl uppercase tracking-wider">MSU <span class="text-msu-yellow">CAHS</span></h1>
            <div class="space-x-6">
                <a href="#" class="hover:text-msu-yellow">Home</a>
                <a href="#" class="hover:text-msu-yellow">About</a>
                <a href="#login" class="bg-msu-yellow text-purple-900 px-4 py-2 rounded-lg font-bold">Login</a>
            </div>
        </div>
    </nav>

    <header class="py-20 bg-white text-center">
        <h2 class="text-4xl font-extrabold text-purple-900 mb-4">College of Allied Health Sciences</h2>
        <p class="text-gray-600 max-w-2xl mx-auto">Empowering the next generation of healthcare professionals through excellence, clinical duty, and community service.</p>
    </header>

    <section id="login" class="container mx-auto py-12 px-4">
        <div class="grid md:grid-cols-2 gap-8">
            <div class="bg-white border-t-4 border-msu-yellow p-8 shadow-md rounded-b-lg text-center">
                <h3 class="text-2xl font-bold text-purple-900 mb-4">Faculty Portal</h3>
                <p class="mb-6 text-gray-500">Manage schedules, rotations, and post emergency announcements.</p>
                <button class="w-full bg-msu-purple text-white py-3 rounded hover:bg-purple-800 transition">Enter Faculty Portal</button>
            </div>

            <div class="bg-white border-t-4 border-msu-yellow p-8 shadow-md rounded-b-lg text-center">
                <h3 class="text-2xl font-bold text-purple-900 mb-4">Student Portal</h3>
                <p class="mb-6 text-gray-500">View your subjects, clinical duty hours, and live announcements.</p>
                <button class="w-full bg-msu-purple text-white py-3 rounded hover:bg-purple-800 transition">Enter Student Portal</button>
            </div>
        </div>
    </section>

</body>
</html>
