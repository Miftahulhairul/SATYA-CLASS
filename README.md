# SATYA-CLASS
TEMPAT BEL<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>English Vocabulary and Conversations</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #28a745;
            color: white;
            padding: 20px;
            text-align: center;
        }
        main {
            padding: 20px;
        }
        .button {
            display: inline-block;
            margin: 10px 5px;
            padding: 10px 20px;
            background-color: #28a745;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .button:hover {
            background-color: #218838;
        }
        .hidden {
            display: none;
        }
        ul {
            list-style-type: none;
            padding-left: 0;
        }
        li {
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>English Vocabulary and Conversations</h1>
    </header>
    <main>
        <h2>Pilih Aktivitas:</h2>
        <button class="button" onclick="showSection('vocab')">Kosa Kata</button>
        <button class="button" onclick="showSection('conversation')">Percakapan Sehari-hari</button>
        <button class="button" onclick="showSection('quiz')">Ulangan Kosa Kata</button>
        <button class="button" onclick="showSection('quiz-conversation')">Ulangan Percakapan</button>
        
        <section id="vocab" class="hidden">
            <h3>50 Kosa Kata</h3>
            <ul>
                <li><b>Morning</b> - Pagi</li>
                <li><b>Afternoon</b> - Sore</li>
                <li><b>Evening</b> - Malam</li>
                <li><b>Breakfast</b> - Sarapan</li>
                <li><b>Lunch</b> - Makan siang</li>
                <li><b>Dinner</b> - Makan malam</li>
                <li><b>Safety</b> - Keselamatan</li>
                <li><b>Teamwork</b> - Kerja sama</li>
                <li><b>Inspection</b> - Inspeksi</li>
                <li><b>Helmet</b> - Helm</li>
                <li><b>Machine</b> - Mesin</li>
                <li><b>Factory</b> - Pabrik</li>
                <li><b>Manager</b> - Manajer</li>
                <li><b>Employee</b> - Karyawan</li>
                <li><b>Meeting</b> - Pertemuan</li>
                <li><b>Report</b> - Laporan</li>
                <li><b>Job</b> - Pekerjaan</li>
                <li><b>Workplace</b> - Tempat kerja</li>
                <li><b>Friendship</b> - Persahabatan</li>
                <li><b>Health</b> - Kesehatan</li>
                <li><b>Exercise</b> - Latihan</li>
                <li><b>Park</b> - Taman</li>
                <li><b>Restaurant</b> - Restoran</li>
                <li><b>Movie</b> - Film</li>
                <li><b>Vacation</b> - Liburan</li>
                <li><b>Travel</b> - Perjalanan</li>
                <li><b>Adventure</b> - Petualangan</li>
                <li><b>Work</b> - Bekerja</li>
                <li><b>Career</b> - Karir</li>
                <li><b>Job Interview</b> - Wawancara Kerja</li>
                <li><b>Electricity</b> - Listrik</li>
                <li><b>Transport</b> - Transportasi</li>
                <li><b>Equipment</b> - Peralatan</li>
                <li><b>Hazard</b> - Bahaya</li>
                <li><b>Fire</b> - Api</li>
                <li><b>Emergency</b> - Darurat</li>
                <li><b>First Aid</b> - Pertolongan pertama</li>
                <li><b>Workforce</b> - Tenaga kerja</li>
                <li><b>Pollution</b> - Polusi</li>
                <li><b>Environment</b> - Lingkungan</li>
                <li><b>Machine Safety</b> - Keamanan mesin</li>
                <li><b>Risk</b> - Risiko</li>
                <li><b>Accident</b> - Kecelakaan</li>
                <li><b>Weather</b> - Cuaca</li>
                <li><b>Schedule</b> - Jadwal</li>
                <li><b>Plan</b> - Rencana</li>
                <li><b>Work Shift</b> - Shift kerja</li>
                <li><b>Break</b> - Istirahat</li>
                <li><b>Lunch Break</b> - Istirahat makan siang</li>
                <li><b>Machine Operator</b> - Operator mesin</li>
                <li><b>Supervisor</b> - Pengawas</li>
                <li><b>Worker</b> - Pekerja</li>
            </ul>
            <button class="button" onclick="backToMenu()">Kembali</button>
        </section>

        <section id="conversation" class="hidden">
            <h3>50 Percakapan Sehari-hari</h3>
            <ul>
                <li><b>A:</b> Good morning! How are you today?</li>
                <li><b>B:</b> I'm good, thank you! And you?</li>
                <li><b>A:</b> I'm great, thank you!</li>
                <li><b>A:</b> What did you have for breakfast?</li>
                <li><b>B:</b> I had eggs and toast. What about you?</li>
                <li><b>A:</b> I had cereal.</li>
                <li><b>A:</b> Are you going to the park later?</li>
                <li><b>B:</b> Yes, I am. Do you want to join me?</li>
                <li><b>A:</b> Sure! What time?</li>
                <li><b>B:</b> Let's meet at 5 PM.</li>
                <!-- Add more conversations here -->
            </ul>
            <button class="button" onclick="backToMenu()">Kembali</button>
        </section>

        <section id="quiz" class="hidden">
            <h3>Ulangan Kosa Kata</h3>
            <p>What does "Safety" mean?</p>
            <input type="text" id="vocabAnswer" placeholder="Your answer..." />
            <button class="button" onclick="checkVocabQuiz()">Submit</button>
            <p id="vocabResponse"></p>
            <button class="button" onclick="backToMenu()">Kembali</button>
        </section>

        <section id="quiz-conversation" class="hidden">
            <h3>Ulangan Percakapan</h3>
            <p>What does "Good morning! How are you today?" mean?</p>
            <input type="text" id="conversationAnswer" placeholder="Your answer..." />
            <button class="button" onclick="checkConversationQuiz()">Submit</button>
            <p id="conversationResponse"></p>
            <button class="button" onclick="backToMenu()">Kembali</button>
        </section>
    </main>

    <script>
        function showSection(sectionId) {
            document.querySelectorAll("section").forEach(sec => sec.classList.add("hidden"));
            document.getElementById(sectionId).classList.remove("hidden");
        }

        function backToMenu() {
            document.querySelectorAll("section").forEach(sec => sec.classList.add("hidden"));
        }

        function checkVocabQuiz() {
            const answer = document.getElementById("vocabAnswer").value.toLowerCase();
            const response = document.getElementById("vocabResponse");
            if (answer === "keselamatan") {
                response.innerText = "Correct! 'Safety' means 'Keselamatan'.";
            } else {
                response.innerText = "Incorrect, try again!";
            }
        }

        function checkConversationQuiz() {
            const answer = document.getElementById("conversationAnswer").value.toLowerCase();
            const response = document.getElementById("conversationResponse");
            if (answer === "selamat pagi! apa kabar?") {
                response.innerText = "Correct! 'Good morning! How are you today?' means 'Selamat pagi! Apa kabar?'.";
            } else {
                response.innerText = "Incorrect, try again!";
            }
        }
    </script>
</body>
</html>
AJAR BAHASA INGGRIS ANGGOTA SATYA
