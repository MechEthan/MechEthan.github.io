<!DOCTYPE html> <!-- Defines this document as an HTML5 document -->
<html lang="en"> <!-- Sets the language of the document to English -->
  <head>
    <meta charset="UTF-8" /> <!-- Character encoding for the document -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" /> <!-- Makes the site responsive -->
    <title>Ethan Ashley | Mechanical Engineer</title> <!-- Title shown in browser tab -->
    <script src="https://cdn.tailwindcss.com"></script> <!-- Loads Tailwind CSS framework -->
    <link rel="preconnect" href="https://fonts.googleapis.com" /> <!-- Improves font loading -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet" /> <!-- Loads Inter font -->
    <style>
      body {
        font-family: 'Inter', sans-serif; /* Sets default font to Inter */
      }
    </style>
  </head>
  <body class="bg-white text-gray-800"> <!-- Sets background and text color -->
    <!-- Header -->
    <header class="bg-gray-100 shadow p-6 sticky top-0 z-50"> <!-- Sticky header with shadow -->
      <div class="max-w-screen-xl mx-auto flex justify-between items-center px-4"> <!-- Centers and spaces header content -->
        <h1 class="text-2xl font-bold">Ethan Ashley</h1> <!-- Site title -->
        <nav class="space-x-6 text-sm"> <!-- Navigation links -->
          <a href="#about" class="hover:text-blue-600">About</a>
          <a href="#projects" class="hover:text-blue-600">Projects</a>
          <a href="#resume" class="hover:text-blue-600">Resume</a>
          <a href="#contact" class="hover:text-blue-600">Contact</a>
        </nav>
      </div>
    </header>

    <!-- Hero Section -->
    <section class="relative text-center py-32 bg-gradient-to-r from-blue-50 to-blue-100 px-4"> <!-- Intro section with gradient background -->
      <div class="absolute inset-0 w-full h-full opacity-20 z-0"> <!-- Background image wrapper -->
        <img src="your-photo.jpg" alt="Your Name" class="w-full h-full object-cover" /> <!-- Full-size background image -->
      </div>
      <div class="relative z-10"> <!-- Foreground content -->
        <h2 class="text-4xl font-bold mb-4">Hi, I'm Your Name</h2> <!-- Main greeting -->
        <p class="text-lg mb-6">Mechanical Engineering Student | CAD Enthusiast | Problem Solver</p> <!-- Tagline -->
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="max-w-screen-md mx-auto px-6 py-16"> <!-- About me section -->
      <h3 class="text-2xl font-bold mb-4">About Me</h3>
      <p class="text-gray-700 leading-relaxed">
        I'm a recent Mechanical Engineering graduate from Auburn University with a passion for CAD design, mechatronics, and hands-on problem solving. I enjoy working on team-based projects and always strive to bring creativity and precision to everything I build.
      </p>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="bg-gray-50 py-16 px-4"> <!-- Project showcase -->
      <div class="max-w-screen-lg mx-auto">
        <h3 class="text-2xl font-bold mb-8 text-center">Projects</h3>
        <div class="grid md:grid-cols-2 gap-8"> <!-- Responsive 2-column layout -->
          <div class="bg-white rounded-2xl shadow p-6"> <!-- Project card -->
            <h4 class="font-semibold text-lg mb-2">Robotic Arm CAD Model</h4>
            <p class="text-gray-700 mb-2">Designed a 5-DOF robotic arm using SolidWorks and simulated motion paths with accurate kinematics.</p>
            <a href="#" class="text-blue-600 text-sm">View more →</a>
          </div>
          <div class="bg-white rounded-2xl shadow p-6"> <!-- Another project card -->
            <h4 class="font-semibold text-lg mb-2">Autonomous Line-Follower Robot</h4>
            <p class="text-gray-700 mb-2">Programmed an Arduino-powered robot using PID control for optimized path-following performance.</p>
            <a href="#" class="text-blue-600 text-sm">View more →</a>
          </div>
        </div>
      </div>
    </section>

    <!-- Resume Section -->
    <section id="resume" class="max-w-screen-md mx-auto px-6 py-16"> <!-- Resume download section -->
      <h3 class="text-2xl font-bold mb-4">Resume</h3>
      <p class="mb-4">Download my resume or view it online below:</p>
      <a href="resume.pdf" target="_blank" class="inline-block px-4 py-2 bg-blue-600 text-white rounded-lg">Download PDF</a>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-blue-50 py-16 px-4"> <!-- Contact section -->
      <div class="max-w-screen-md mx-auto text-center">
        <h3 class="text-2xl font-bold mb-4">Contact Me</h3>
        <p class="mb-4">I'm currently open to full-time opportunities or collaborations. Let's connect!</p>
        <p>Email: <a href="mailto:your.email@example.com" class="text-blue-600">your.email@example.com</a></p>
        <p>LinkedIn: <a href="https://linkedin.com/in/yourprofile" class="text-blue-600">linkedin.com/in/yourprofile</a></p>
      </div>
    </section>

    <!-- Footer -->
    <footer class="text-center text-sm text-gray-500 py-6 px-4"> <!-- Footer text -->
      © 2025 Your Name. All rights reserved.
    </footer>
  </body>
</html>
