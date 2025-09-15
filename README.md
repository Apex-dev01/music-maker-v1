<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Studio - README</title>
    <!-- Favicon links for the new logo -->
    <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Cdefs%3E%3ClinearGradient id='grad' x1='0%25' y1='0%25' x2='100%25' y2='100%25'%3E%3Cstop offset='0%25' style='stop-color:%23818cf8;stop-opacity:1' /%3E%3Cstop offset='100%25' style='stop-color:%23f59e0b;stop-opacity:1' /%3E%3C/linearGradient%3E%3C/defs%3E%3Crect width='100' height='100' rx='20' fill='%231e293b'/%3E%3Cpath d='M25 75 C 40 55, 60 55, 75 75' stroke='url(%23grad)' stroke-width='8' fill='none' stroke-linecap='round'/%3E%3Cpath d='M25 60 C 40 40, 60 40, 75 60' stroke='%23e2e8f0' stroke-width='8' fill='none' stroke-linecap='round'/%3E%3Cpath d='M25 45 C 40 25, 60 25, 75 45' stroke='url(%23grad)' stroke-width='8' fill='none' stroke-linecap='round'/%3E%3C/svg%3E" type="image/svg+xml">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0f172a;
            color: #e2e8f0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
        }
        h1, h2 {
            color: #fff;
            border-bottom: 1px solid #334155;
            padding-bottom: 0.5rem;
        }
        h1 {
            font-size: 2.5rem;
            font-weight: 700;
        }
        h2 {
            font-size: 1.75rem;
            font-weight: 600;
            margin-top: 2.5rem;
        }
        ul {
            list-style-type: disc;
            padding-left: 2rem;
        }
        li {
            margin-bottom: 0.75rem;
        }
        code {
            background-color: #1e293b;
            color: #f59e0b;
            padding: 0.2rem 0.4rem;
            border-radius: 0.25rem;
            font-family: monospace;
        }
        a {
            color: #818cf8;
            text-decoration: none;
            transition: color 0.2s;
        }
        a:hover {
            color: #6366f1;
            text-decoration: underline;
        }
        .logo-container {
            display: flex;
            align-items: center;
            gap: 1rem;
        }
        .logo-container svg {
            width: 60px; /* Adjusted size for the new logo */
            height: 60px;
        }
        .card {
             background-color: rgba(30, 41, 59, 0.5);
             border: 1px solid #334155;
             padding: 1.5rem;
             border-radius: 0.75rem;
        }
    </style>
</head>
<body class="py-12 px-4">
    <div class="container">
        
        <div class="logo-container mb-4">
            <!-- New, better-looking SVG Logo -->
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100">
              <defs>
                <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="100%">
                  <stop offset="0%" style="stop-color:#818cf8;stop-opacity:1" />
                  <stop offset="100%" style="stop-color:#f59e0b;stop-opacity:1" />
                </linearGradient>
              </defs>
              <rect width="100" height="100" rx="20" fill="#1e293b"/>
              <path d="M25 75 C 40 55, 60 55, 75 75" stroke="url(#grad)" stroke-width="8" fill="none" stroke-linecap="round"/>
              <path d="M25 60 C 40 40, 60 40, 75 60" stroke="#e2e8f0" stroke-width="8" fill="none" stroke-linecap="round"/>
              <path d="M25 45 C 40 25, 60 25, 75 45" stroke="url(#grad)" stroke-width="8" fill="none" stroke-linecap="round"/>
            </svg>
            <h1>Web Music Studio</h1>
        </div>
        
        <p class="text-lg text-slate-300 mb-8">
            A powerful and intuitive browser-based music sequencer and synthesizer built into a single, self-contained HTML file. Create beats and melodies with four distinct instruments, shape your sound with a built-in mixer and effects, and export your creations as high-quality WAV files.
        </p>
        
        <div class="card text-slate-400 mb-8 italic">
            <!-- It's highly recommended to add a screenshot or an animated GIF of the application in action here! -->
            <!-- Example: <img src="link_to_your_screenshot.png" alt="Web Music Studio Demo"> -->
            Note: Consider adding a screenshot or GIF of the app to visually showcase the project.
        </div>
        
        <section>
            <h2>Features</h2>
            <ul class="space-y-4 mt-6">
                <li><strong>Four Versatile Instruments:</strong> Compose full tracks using:
                    <ul class="mt-2 list-disc list-inside text-slate-300">
                        <li>A classic <strong>Drum Machine</strong> (Kick, Snare, Hi-hat, Crash)</li>
                        <li>A melodic <strong>Piano Roll</strong></li>
                        <li>A deep <strong>Bass Line</strong> synthesizer</li>
                        <li>A plucky <strong>Guitar</strong> synthesizer</li>
                    </ul>
                </li>
                <li><strong>16-Step Sequencer:</strong> Easily program patterns by clicking notes onto the interactive grid for each instrument.</li>
                <li><strong>Advanced Timing Controls:</strong>
                    <ul class="mt-2 list-disc list-inside text-slate-300">
                        <li><strong>BPM:</strong> Adjust the tempo from 40 to 240 BPM with both a slider and precise numerical input.</li>
                        <li><strong>Swing:</strong> Add a human-like shuffle to your rhythms.</li>
                        <li><strong>Loop Count:</strong> Set the total number of loops for offline rendering.</li>
                    </ul>
                </li>
                <li><strong>Synthesizer Customization:</strong> Tweak the sound of each melodic instrument by changing its waveform (e.g., sine, triangle, sawtooth, square, and a custom "plucked" wave for the guitar).</li>
                <li><strong>Full-Featured Mixer:</strong>
                     <ul class="mt-2 list-disc list-inside text-slate-300">
                        <li>Control the <strong>Volume</strong> and stereo <strong>Panning</strong> for each instrument independently.</li>
                        <li>Add depth to your mix with a global <strong>Reverb</strong> effect.</li>
                    </ul>
                </li>
                <li><strong>Dual Export Options:</strong>
                     <ul class="mt-2 list-disc list-inside text-slate-300">
                        <li><strong>Live Recording:</strong> Capture the real-time audio output as you play and tweak your track. Perfect for recording live jam sessions.</li>
                        <li><strong>Offline Rendering:</strong> Export a high-quality, full-length WAV file of your completed song based on your sequence and loop settings.</li>
                    </ul>
                </li>
                <li><strong>Robust Project Management:</strong>
                     <ul class="mt-2 list-disc list-inside text-slate-300">
                        <li><strong>Save & Load:</strong> Save and name your tracks directly in the browser's local storage.</li>
                        <li><strong>Track Manager:</strong> Load or delete previous projects from a clean, modal-based tracklist.</li>
                        <li><strong>Autosave:</strong> Your current session is automatically saved, so you never lose your work.</li>
                    </ul>
                </li>
                <li><strong>Responsive & Modern UI:</strong> The user interface is clean, dark-themed, and fully responsive, working great on any device from desktop to mobile.</li>
                <li><strong>All-in-One:</strong> The entire application—HTML, CSS, and JavaScript—is self-contained in a single file, making it incredibly portable.</li>
            </ul>
        </section>

        <section>
            <h2>How to Use</h2>
            <ol class="list-decimal pl-5 mt-6 space-y-2">
                <li>Open the <code>code_canvas.html</code> file in any modern web browser.</li>
                <li>Click on the grid cells to program notes for each instrument. Active notes are highlighted.</li>
                <li>Use the master controls at the top to <strong>Play/Stop</strong> the sequence, change the tempo (BPM), and adjust other settings.</li>
                <li>Expand the instrument sections to change their volume or waveform.</li>
                <li>Fine-tune your mix using the dedicated volume and pan sliders in the <strong>Mixer</strong> section.</li>
                <li>When you're ready, save your work using the <strong>Save</strong> button or export it using <strong>Record Live</strong> or <strong>Export WAV</strong>.</li>
            </ol>
        </section>

        <section>
            <h2>Technology Stack</h2>
            <ul class="mt-6 space-y-2">
                <li><strong>Frontend:</strong> HTML5, CSS3, JavaScript (ES6+)</li>
                <li><strong>Audio Engine:</strong> The Web Audio API is used for all synthesis, scheduling, and audio processing.</li>
                <li><strong>Styling:</strong> <a href="https://tailwindcss.com/" target="_blank" rel="noopener noreferrer">Tailwind CSS</a> for a utility-first, responsive design.</li>
            </ul>
        </section>

    </div>
</body>
</html>

