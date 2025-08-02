<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kuis: Keajaiban Ciptaan Allah</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');
        body { font-family: 'Poppins', sans-serif; }
        .plant-bg {
            background: linear-gradient(135deg, #10b981 0%, #3b82f6 100%);
        }
        .question-card {
            background: linear-gradient(135deg, #059669 0%, #2563eb 100%);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        .option-btn {
            transition: all 0.3s ease;
            background: linear-gradient(135deg, #34d399 0%, #60a5fa 100%);
        }
        .option-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
        }
        .correct {
            background: linear-gradient(135deg, #56ab2f 0%, #a8e6cf 100%) !important;
            animation: pulse 0.6s ease-in-out;
        }
        .incorrect {
            background: linear-gradient(135deg, #ff416c 0%, #ff4b2b 100%) !important;
            animation: shake 0.6s ease-in-out;
        }
        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }
        @keyframes shake {
            0%, 100% { transform: translateX(0); }
            25% { transform: translateX(-5px); }
            75% { transform: translateX(5px); }
        }
        .plant-icon {
            font-size: 3rem;
            animation: sway 3s ease-in-out infinite;
        }
        @keyframes sway {
            0%, 100% { transform: rotate(-5deg); }
            50% { transform: rotate(5deg); }
        }
    </style>
</head>
<body class="plant-bg min-h-screen">
    <div class="container mx-auto px-4 py-8">
        <!-- Header -->
        <div class="text-center mb-8">
            <!-- School Logo and Label -->
            <div class="bg-white bg-opacity-20 backdrop-blur-sm rounded-2xl px-6 py-4 mb-6 inline-block border border-white border-opacity-30">
                <div class="flex items-center justify-center gap-4">
                    <!-- Logo Placeholder - Replace with actual logo -->
                    <div class="w-12 h-12 bg-white bg-opacity-30 rounded-full flex items-center justify-center">
                        <svg class="w-8 h-8 text-white" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M12 2L13.09 8.26L20 9L13.09 9.74L12 16L10.91 9.74L4 9L10.91 8.26L12 2Z"/>
                            <path d="M12 12L13.09 18.26L20 19L13.09 19.74L12 26L10.91 19.74L4 19L10.91 18.26L12 12Z" opacity="0.6"/>
                        </svg>
                    </div>
                    <h2 class="text-2xl font-bold text-white tracking-wide">BUMI FITRAH INSTITUT</h2>
                </div>
                <p class="text-sm text-white opacity-75 mt-1 text-center">Sekolah Islam Terpadu</p>
            </div>
            
            <div class="plant-icon mb-4">🌱🍎🍇🥭</div>
            <h1 class="text-4xl font-bold text-white mb-4">Kuis: Keajaiban Ciptaan Allah</h1>
            <p class="text-xl text-white opacity-90">QS. Ar-Ra'd: 4 - Tanda-tanda Kebesaran Allah dalam Tanaman</p>
        </div>

        <!-- Introduction Page -->
        <div class="max-w-4xl mx-auto">
            <div id="intro-container" class="question-card rounded-3xl p-8 text-white">
                <div class="text-center mb-8">
                    <h2 class="text-3xl font-bold mb-6">📖 Renungan Sebelum Quiz</h2>
                    <div class="bg-white bg-opacity-10 rounded-2xl p-6 mb-6 text-right">
                        <p class="text-lg italic leading-relaxed">
                            "Dan di bumi terdapat bagian-bagian yang berdampingan, kebun-kebun anggur, tanaman-tanaman dan pohon kurma yang bercabang dan yang tidak bercabang, disirami dengan air yang sama, tetapi Kami lebihkan sebagian tanaman itu atas sebagian yang lain dalam hal rasanya. Sungguh, pada yang demikian itu terdapat tanda-tanda (kebesaran Allâh) bagi kaum yang berpikir."
                        </p>
                        <p class="text-sm mt-4 font-semibold">- QS. Ar-Ra'd: 4 -</p>
                    </div>
                </div>

                <div class="space-y-6 text-lg leading-relaxed">
                    <div class="bg-white bg-opacity-5 rounded-xl p-6">
                        <h3 class="text-xl font-bold mb-4 text-center">🌱 Pernahkah Kita Mengamati Tanah?</h3>
                        <p class="text-center mb-4">Coba perhatikan baik-baik...</p>
                        
                        <div class="grid md:grid-cols-2 gap-6 mt-6">
                            <div class="bg-white bg-opacity-10 rounded-lg p-4">
                                <p class="font-semibold mb-2">Dari tanah yang sama,</p>
                                <p>tumbuh tanaman yang berbeda-beda.</p>
                                <ul class="mt-3 space-y-1 text-sm">
                                    <li>• Tanahnya sama</li>
                                    <li>• Air yang diserapnya juga sama</li>
                                    <li>• Zat hara, sinar matahari, dan udara—semuanya serupa</li>
                                </ul>
                            </div>
                            
                            <div class="bg-white bg-opacity-10 rounded-lg p-4">
                                <p class="font-semibold mb-2">Tapi...</p>
                                <p class="mb-2">Mengapa buah yang tumbuh bisa berwarna-warni?</p>
                                <div class="text-sm space-y-1">
                                    <p>🍎 Ada yang merah seperti apel</p>
                                    <p>🍌 kuning seperti pisang</p>
                                    <p>🍈 hijau seperti melon</p>
                                    <p>🍇 ungu seperti anggur</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white bg-opacity-5 rounded-xl p-6">
                        <h3 class="text-xl font-bold mb-4 text-center">🎨 Siapa yang "Mewarnainya"?</h3>
                        <p class="text-center mb-4">Adakah pelukis rahasia di balik semua itu?</p>
                        
                        <div class="grid md:grid-cols-3 gap-4 mt-6">
                            <div class="bg-white bg-opacity-10 rounded-lg p-4 text-center">
                                <h4 class="font-bold mb-2">🔴 Bentuknya Beragam</h4>
                                <div class="text-sm space-y-1">
                                    <p>🍉 Bulat seperti semangka</p>
                                    <p>🥭 Lonjong seperti pepaya</p>
                                    <p>🥥 Berduri seperti durian</p>
                                    <p>🍎 Berkulit licin seperti apel</p>
                                </div>
                            </div>
                            
                            <div class="bg-white bg-opacity-10 rounded-lg p-4 text-center">
                                <h4 class="font-bold mb-2">👅 Rasanya Berbeda</h4>
                                <div class="text-sm space-y-1">
                                    <p>🍯 Ada yang manis menggoda</p>
                                    <p>🍋 Ada yang asam menyegarkan</p>
                                    <p>🌿 Ada yang pahit namun bermanfaat</p>
                                    <p>💧 Ada yang menyegarkan tenggorokan</p>
                                </div>
                            </div>
                            
                            <div class="bg-white bg-opacity-10 rounded-lg p-4 text-center">
                                <h4 class="font-bold mb-2">❓ Pertanyaan Penting</h4>
                                <div class="text-sm space-y-2">
                                    <p>Apakah semua itu terjadi karena "kebetulan"?</p>
                                    <p>Apakah semua itu bisa muncul tanpa yang mengatur?</p>
                                    <p class="font-bold text-yellow-200">Tentu tidak. Mustahil.</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="bg-gradient-to-r from-green-600 to-blue-600 bg-opacity-20 rounded-xl p-6 text-center">
                        <h3 class="text-2xl font-bold mb-4">✨ Kesimpulan</h3>
                        <p class="mb-4">Segala keindahan, keteraturan, dan keajaiban ini adalah <span class="font-bold text-yellow-200">tanda-tanda kekuasaan</span></p>
                        <p class="mb-4">Seseorang yang menciptakan semuanya.</p>
                        <div class="space-y-2 mb-4">
                            <p>🧠 Dengan ilmu dan kehendak</p>
                            <p>💚 Dengan rahmat dan kuasa</p>
                        </div>
                        <p class="text-xl font-bold">Dia adalah <span class="text-yellow-200">Allâh ﷻ</span></p>
                        <p class="text-lg">Tuhan yang Maha Pencipta,</p>
                        <p>yang menjadikan dari tanah yang sama buah yang berbeda rupa, rasa, dan manfaatnya.</p>
                    </div>
                </div>

                <div class="text-center mt-8">
                    <button onclick="startQuiz()" class="bg-white bg-opacity-20 hover:bg-opacity-30 px-8 py-4 rounded-xl font-bold text-xl transition-all duration-300 transform hover:scale-105">
                        🚀 Mulai Quiz Sekarang
                    </button>
                    <p class="mt-4 text-sm opacity-75">Uji pemahaman Anda tentang tanda-tanda kebesaran Allah</p>
                </div>
            </div>

            <!-- Quiz Container -->
            <div id="quiz-container" class="question-card rounded-3xl p-8 text-white hidden">
                <div class="flex justify-between items-center mb-6">
                    <span class="text-lg font-semibold">Pertanyaan <span id="current-question">1</span> dari 10</span>
                    <div class="bg-white bg-opacity-20 rounded-full px-4 py-2">
                        <span class="font-bold">Skor: <span id="score">0</span>/10</span>
                    </div>
                </div>

                <div id="question-content">
                    <!-- Questions will be loaded here -->
                </div>

                <div id="options-container" class="grid grid-cols-1 md:grid-cols-2 gap-4 mt-6">
                    <!-- Options will be loaded here -->
                </div>

                <div id="feedback" class="mt-6 p-4 rounded-xl hidden">
                    <!-- Feedback will appear here -->
                </div>

                <div class="flex justify-between mt-8">
                    <button onclick="backToIntro()" class="bg-white bg-opacity-20 hover:bg-opacity-30 px-6 py-3 rounded-xl font-semibold transition-all duration-300">
                        ← Kembali ke Pengantar
                    </button>
                    <button id="next-btn" class="bg-white bg-opacity-20 hover:bg-opacity-30 px-6 py-3 rounded-xl font-semibold transition-all duration-300 ml-auto hidden">
                        Selanjutnya →
                    </button>
                </div>
            </div>

            <!-- Final Results -->
            <div id="results" class="question-card rounded-3xl p-8 text-white text-center hidden">
                <div class="text-6xl mb-4">🏆</div>
                <h2 class="text-3xl font-bold mb-4">Alhamdulillah! Quiz Selesai</h2>
                <div class="text-2xl mb-6">
                    Skor Akhir: <span id="final-score" class="font-bold text-yellow-300"></span>/10
                </div>
                <div id="final-message" class="text-lg mb-6"></div>
                <div class="flex justify-center gap-4">
                    <button onclick="backToIntro()" class="bg-white bg-opacity-20 hover:bg-opacity-30 px-6 py-3 rounded-xl font-semibold transition-all duration-300">
                        📖 Baca Pengantar Lagi
                    </button>
                    <button onclick="restartQuiz()" class="bg-white bg-opacity-20 hover:bg-opacity-30 px-6 py-3 rounded-xl font-semibold transition-all duration-300">
                        🔄 Ulangi Quiz
                    </button>
                </div>
            </div>
        </div>
    </div>

    <script>
        // Audio Context for sound effects
        let audioContext;
        
        function initAudio() {
            if (!audioContext) {
                audioContext = new (window.AudioContext || window.webkitAudioContext)();
            }
        }

        function playClickSound() {
            initAudio();
            const oscillator = audioContext.createOscillator();
            const gainNode = audioContext.createGain();
            
            oscillator.connect(gainNode);
            gainNode.connect(audioContext.destination);
            
            oscillator.frequency.setValueAtTime(800, audioContext.currentTime);
            oscillator.frequency.exponentialRampToValueAtTime(600, audioContext.currentTime + 0.1);
            
            gainNode.gain.setValueAtTime(0.1, audioContext.currentTime);
            gainNode.gain.exponentialRampToValueAtTime(0.01, audioContext.currentTime + 0.1);
            
            oscillator.start(audioContext.currentTime);
            oscillator.stop(audioContext.currentTime + 0.1);
        }

        function playCorrectSound() {
            initAudio();
            const oscillator = audioContext.createOscillator();
            const gainNode = audioContext.createGain();
            
            oscillator.connect(gainNode);
            gainNode.connect(audioContext.destination);
            
            oscillator.frequency.setValueAtTime(523, audioContext.currentTime); // C5
            oscillator.frequency.setValueAtTime(659, audioContext.currentTime + 0.1); // E5
            oscillator.frequency.setValueAtTime(784, audioContext.currentTime + 0.2); // G5
            
            gainNode.gain.setValueAtTime(0.15, audioContext.currentTime);
            gainNode.gain.exponentialRampToValueAtTime(0.01, audioContext.currentTime + 0.4);
            
            oscillator.start(audioContext.currentTime);
            oscillator.stop(audioContext.currentTime + 0.4);
        }

        function playIncorrectSound() {
            initAudio();
            const oscillator = audioContext.createOscillator();
            const gainNode = audioContext.createGain();
            
            oscillator.connect(gainNode);
            gainNode.connect(audioContext.destination);
            
            oscillator.frequency.setValueAtTime(300, audioContext.currentTime);
            oscillator.frequency.exponentialRampToValueAtTime(200, audioContext.currentTime + 0.3);
            
            gainNode.gain.setValueAtTime(0.1, audioContext.currentTime);
            gainNode.gain.exponentialRampToValueAtTime(0.01, audioContext.currentTime + 0.3);
            
            oscillator.start(audioContext.currentTime);
            oscillator.stop(audioContext.currentTime + 0.3);
        }

        const questions = [
            {
                question: "🌱 Menurut QS. Ar-Ra'd ayat 4, apa yang sama dari tanaman-tanaman yang berbeda?",
                options: [
                    "Warna buahnya",
                    "Air yang menyiraminya",
                    "Bentuk daunnya",
                    "Ukuran batangnya"
                ],
                correct: 1,
                explanation: "Allah menyebutkan bahwa tanaman-tanaman itu 'disirami dengan air yang sama' namun berbeda dalam rasa dan kualitasnya."
            },
            {
                question: "🍎 Mengapa buah-buahan memiliki warna yang berbeda-beda meski tumbuh dari tanah yang sama?",
                options: [
                    "Karena kebetulan alam",
                    "Karena kehendak dan kuasa Allah",
                    "Karena pengaruh cuaca",
                    "Karena jenis pupuk yang berbeda"
                ],
                correct: 1,
                explanation: "Keberagaman warna, rasa, dan bentuk buah adalah tanda kebesaran Allah yang menciptakan dengan ilmu dan kehendak-Nya."
            },
            {
                question: "🌿 Apa hikmah dari keberagaman tanaman yang disebutkan dalam ayat ini?",
                options: [
                    "Untuk memperindah taman",
                    "Sebagai tanda kebesaran Allah bagi yang berpikir",
                    "Untuk kompetisi antar tanaman",
                    "Untuk membuat petani bingung"
                ],
                correct: 1,
                explanation: "Allah menyebutkan 'Sungguh, pada yang demikian itu terdapat tanda-tanda (kebesaran Allah) bagi kaum yang berpikir.'"
            },
            {
                question: "🍇 Dalam ayat ini, Allah menyebutkan tanaman kurma yang bercabang dan tidak bercabang. Apa maksudnya?",
                options: [
                    "Kurma jantan dan betina",
                    "Kurma muda dan tua",
                    "Kurma yang berbuah lebat dan sedikit",
                    "Kurma yang tumbuh berkelompok dan tunggal"
                ],
                correct: 3,
                explanation: "Allah menunjukkan keberagaman dalam satu jenis tanaman yang sama, ada yang tumbuh berkelompok (bercabang) dan ada yang tunggal."
            },
            {
                question: "🥭 Mengapa rasa buah-buahan berbeda meski mendapat nutrisi yang sama?",
                options: [
                    "Karena Allah yang menentukan perbedaan itu",
                    "Karena kesalahan petani",
                    "Karena tanah yang rusak",
                    "Karena hama tanaman"
                ],
                correct: 0,
                explanation: "Allah berfirman 'tetapi Kami lebihkan sebagian tanaman itu atas sebagian yang lain dalam hal rasanya' - menunjukkan Allah yang menentukan perbedaan rasa."
            },
            {
                question: "🌾 Apa yang dimaksud dengan 'bagian-bagian bumi yang berdampingan' dalam ayat ini?",
                options: [
                    "Tanah yang letaknya bersebelahan",
                    "Gunung dan lembah",
                    "Sungai dan danau",
                    "Hutan dan padang rumput"
                ],
                correct: 0,
                explanation: "Bagian-bagian bumi yang berdampingan menunjukkan tanah yang bersebelahan namun menghasilkan tanaman yang berbeda-beda."
            },
            {
                question: "🍊 Siapa yang 'mewarnai' buah-buahan dengan warna yang indah?",
                options: [
                    "Sinar matahari",
                    "Zat kimia dalam tanah",
                    "Allah Subhanahu wa Ta'ala",
                    "Proses evolusi"
                ],
                correct: 2,
                explanation: "Tidak ada yang bisa menciptakan keindahan dan keteraturan ini kecuali Allah, Sang Maha Pencipta."
            },
            {
                question: "🌻 Untuk siapa tanda-tanda kebesaran Allah dalam keberagaman tanaman ini?",
                options: [
                    "Bagi para petani saja",
                    "Bagi kaum yang berpikir",
                    "Bagi orang kaya saja",
                    "Bagi para ilmuwan saja"
                ],
                correct: 1,
                explanation: "Allah menyebutkan 'bagi kaum yang berpikir' - yaitu mereka yang mau merenungkan dan mengambil pelajaran dari ciptaan-Nya."
            },
            {
                question: "🥥 Apa yang bisa kita pelajari dari fakta bahwa tanaman berbeda tumbuh dari kondisi yang sama?",
                options: [
                    "Alam bekerja secara acak",
                    "Ada Yang Maha Kuasa yang mengatur semuanya",
                    "Tanaman bisa memilih sendiri",
                    "Tidak ada pelajaran khusus"
                ],
                correct: 1,
                explanation: "Keberagaman dari kesamaan kondisi menunjukkan adanya Yang Maha Kuasa yang mengatur dan menentukan segalanya dengan hikmah."
            },
            {
                question: "🌺 Bagaimana seharusnya sikap kita setelah merenungkan keajaiban ciptaan Allah ini?",
                options: [
                    "Biasa saja, itu hal wajar",
                    "Bersyukur dan semakin beriman kepada Allah",
                    "Takut dengan alam",
                    "Menjadi sombong dengan pengetahuan"
                ],
                correct: 1,
                explanation: "Merenungkan tanda-tanda kebesaran Allah seharusnya menambah rasa syukur dan keimanan kita kepada-Nya."
            }
        ];

        let currentQuestion = 0;
        let score = 0;
        let answered = false;

        function loadQuestion() {
            const question = questions[currentQuestion];
            document.getElementById('current-question').textContent = currentQuestion + 1;
            document.getElementById('question-content').innerHTML = `
                <h3 class="text-2xl font-bold mb-4">${question.question}</h3>
            `;

            const optionsContainer = document.getElementById('options-container');
            optionsContainer.innerHTML = '';

            question.options.forEach((option, index) => {
                const button = document.createElement('button');
                button.className = 'option-btn text-white font-semibold py-4 px-6 rounded-xl text-left';
                button.innerHTML = `<span class="font-bold">${String.fromCharCode(65 + index)}.</span> ${option}`;
                button.onclick = () => {
                    playClickSound();
                    selectAnswer(index);
                };
                optionsContainer.appendChild(button);
            });

            document.getElementById('feedback').classList.add('hidden');
            document.getElementById('next-btn').classList.add('hidden');
            answered = false;
        }

        function selectAnswer(selectedIndex) {
            if (answered) return;
            answered = true;

            const question = questions[currentQuestion];
            const options = document.querySelectorAll('.option-btn');
            
            options.forEach((option, index) => {
                if (index === question.correct) {
                    option.classList.add('correct');
                } else if (index === selectedIndex && index !== question.correct) {
                    option.classList.add('incorrect');
                }
                option.style.pointerEvents = 'none';
            });

            const isCorrect = selectedIndex === question.correct;
            if (isCorrect) {
                score++;
                document.getElementById('score').textContent = score;
                playCorrectSound();
            } else {
                playIncorrectSound();
            }

            showFeedback(isCorrect, question.explanation);
        }

        function showFeedback(isCorrect, explanation) {
            const feedback = document.getElementById('feedback');
            feedback.classList.remove('hidden');
            
            if (isCorrect) {
                feedback.className = 'mt-6 p-4 rounded-xl bg-green-500 bg-opacity-20 border border-green-300';
                feedback.innerHTML = `
                    <div class="flex items-center mb-2">
                        <span class="text-2xl mr-2">✅</span>
                        <span class="font-bold text-green-200">Benar, Mâsyâ Allâh!</span>
                    </div>
                    <p class="text-green-100">${explanation}</p>
                `;
            } else {
                feedback.className = 'mt-6 p-4 rounded-xl bg-red-500 bg-opacity-20 border border-red-300';
                feedback.innerHTML = `
                    <div class="flex items-center mb-2">
                        <span class="text-2xl mr-2">❌</span>
                        <span class="font-bold text-red-200">Maaf belum tepat, coba lagi!</span>
                    </div>
                    <p class="text-red-100">${explanation}</p>
                `;
            }

            document.getElementById('next-btn').classList.remove('hidden');
        }

        function nextQuestion() {
            playClickSound();
            currentQuestion++;
            if (currentQuestion < questions.length) {
                loadQuestion();
            } else {
                showResults();
            }
        }

        function showResults() {
            document.getElementById('quiz-container').classList.add('hidden');
            document.getElementById('results').classList.remove('hidden');
            document.getElementById('final-score').textContent = score;

            let message = '';
            if (score >= 9) {
                message = '🌟 Mâsyâ Allâh! Pemahaman Anda sangat baik tentang tanda-tanda kebesaran Allah!';
            } else if (score >= 7) {
                message = '👏 Alhamdulillah! Anda memahami dengan baik hikmah dari keberagaman ciptaan Allah.';
            } else if (score >= 5) {
                message = '📚 Baik! Terus belajar dan renungkan tanda-tanda kebesaran Allah di sekitar kita.';
            } else {
                message = '💪 Semangat! Mari pelajari lagi ayat-ayat Allah dan renungkan ciptaan-Nya.';
            }
            document.getElementById('final-message').textContent = message;
        }

        function restartQuiz() {
            playClickSound();
            currentQuestion = 0;
            score = 0;
            answered = false;
            document.getElementById('score').textContent = '0';
            document.getElementById('quiz-container').classList.remove('hidden');
            document.getElementById('results').classList.add('hidden');
            loadQuestion();
        }

        function startQuiz() {
            playClickSound();
            document.getElementById('intro-container').classList.add('hidden');
            document.getElementById('quiz-container').classList.remove('hidden');
            loadQuestion();
        }

        function backToIntro() {
            playClickSound();
            document.getElementById('quiz-container').classList.add('hidden');
            document.getElementById('results').classList.add('hidden');
            document.getElementById('intro-container').classList.remove('hidden');
            
            // Reset quiz state
            currentQuestion = 0;
            score = 0;
            answered = false;
            document.getElementById('score').textContent = '0';
        }

        // Event listeners
        document.getElementById('next-btn').onclick = nextQuestion;

        // Initialize with introduction page
        // loadQuestion() is now called from startQuiz()
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'9689dc2461af959b',t:'MTc1NDA5ODc1MC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>

# Haikus for Codespaces

This is a quick node project template for demoing Codespaces. It is based on the [Azure node sample](https://github.com/Azure-Samples/nodejs-docs-hello-world). It's great!!!

Point your browser to [Quickstart for GitHub Codespaces](https://docs.github.com/en/codespaces/getting-started/quickstart) for a tour of using Codespaces with this repo.
