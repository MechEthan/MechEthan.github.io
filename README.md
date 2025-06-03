<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Your Name | Mechanical Engineer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet" />
    <style>
      body {
        font-family: 'Inter', sans-serif;
      }
    </style>
  </head>
  <body class="bg-white text-gray-800">
    <!-- Header -->
    <header class="bg-gray-100 shadow p-6 sticky top-0 z-50">
      <div class="max-w-7xl mx-auto flex justify-between items-center">
        <h1 class="text-2xl font-bold">Your Name</h1>
        <nav class="space-x-6 text-sm">
          <a href="#about" class="hover:text-blue-600">About</a>
          <a href="#projects" class="hover:text-blue-600">Projects</a>
          <a href="#resume" class="hover:text-blue-600">Resume</a>
          <a href="#contact" class="hover:text-blue-600">Contact</a>
        </nav>
      </div>
    </header>

    <!-- Hero Section -->
    <section class="text-center py-20 bg-gradient-to-r from-blue-50 to-blue-100">
      <h2 class="text-4xl font-bold mb-4">Hi, I'm Your Name</h2>
      <p class="text-lg">Mechanical Engineering Student | CAD Enthusiast | Problem Solver</p>
    </section>

    <!-- About Section -->
    <section id="about" class="max-w-4xl mx-auto px-4 py-16">
      <h3 class="text-2xl font-bold mb-4">About Me</h3>
      <p class="text-gray-700 leading-relaxed">
        I'm a recent Mechanical Engineering graduate from Auburn University with a passion for CAD design, mechatronics, and hands-on problem solving. I enjoy working on team-based projects and always strive to bring creativity and precision to everything I build.
      </p>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="bg-gray-50 py-16 px-4">
      <div class="max-w-6xl mx-auto">
        <h3 class="text-2xl font-bold mb-8 text-center">Projects</h3>
        <div class="grid md:grid-cols-2 gap-8">
          <div class="bg-white rounded-2xl shadow p-6">
            <h4 class="font-semibold text-lg mb-2">Robotic Arm CAD Model</h4>
            <p class="text-gray-700 mb-2">Designed a 5-DOF robotic arm using SolidWorks and simulated motion paths with accurate kinematics.</p>
            <a href="#" class="text-blue-600 text-sm">View more →</a>
          </div>
          <div class="bg-white rounded-2xl shadow p-6">
            <h4 class="font-semibold text-lg mb-2">Autonomous Line-Follower Robot</h4>
            <p class="text-gray-700 mb-2">Programmed an Arduino-powered robot using PID control for optimized path-following performance.</p>
            <a href="#" class="text-blue-600 text-sm">View more →</a>
          </div>
        </div>
      </div>
    </section>

    <!-- Resume Section -->
    <section id="resume" class="max-w-4xl mx-auto px-4 py-16">
      <h3 class="text-2xl font-bold mb-4">Resume</h3>
      <p class="mb-4">Download my resume or view it online below:</p>
      <a href="resume.pdf" target="_blank" class="inline-block px-4 py-2 bg-blue-600 text-white rounded-lg">Download PDF</a>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-blue-50 py-16 px-4">
      <div class="max-w-3xl mx-auto text-center">
        <h3 class="text-2xl font-bold mb-4">Contact Me</h3>
        <p class="mb-4">I'm currently open to full-time opportunities or collaborations. Let's connect!</p>
        <p>Email: <a href="mailto:your.email@example.com" class="text-blue-600">your.email@example.com</a></p>
        <p>LinkedIn: <a href="https://linkedin.com/in/yourprofile" class="text-blue-600">linkedin.com/in/yourprofile</a></p>
      </div>
    </section>

    <!-- Footer -->
    <footer class="text-center text-sm text-gray-500 py-6">
      © 2025 Your Name. All rights reserved.
    </footer>
  </body>
</html>

