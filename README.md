<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hizkia Roland Portfolio</title>
  <link rel="stylesheet" href="style.css">
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-white text-gray-900 dark:bg-gray-900 dark:text-white">
  <header class="p-6 bg-gray-100 dark:bg-gray-800 shadow-md">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-xl font-bold">Hizkia Roland</h1>
      <nav class="space-x-4">
        <a href="#about" class="hover:underline">Tentang</a>
        <a href="#portfolio" class="hover:underline">Portofolio</a>
        <a href="#contact" class="hover:underline">Kontak</a>
        <button id="toggleTheme" class="ml-4">🌙</button>
      </nav>
    </div>
  </header>

  <main class="container mx-auto px-4 py-10">
    <section class="text-center mb-20">
      <h2 class="text-4xl font-bold mb-4">Selamat datang di portofolio saya!</h2>
      <p class="text-lg">Saya adalah mahasiswa Universitas Negeri Medan, penulis aktif, dan pemuda yang berdedikasi pada isu sosial, pendidikan, dan kewarganegaraan.</p>
    </section>

    <section id="about" class="mb-20">
      <h3 class="text-2xl font-semibold mb-4">Tentang Saya</h3>
      <div class="flex flex-col md:flex-row items-center gap-6">
        <img src="https://assets.kompasiana.com/items/galeri/slider/66479e70ae0d3c64ef44a1cf.jpg" alt="Foto Hizkia Roland" class="w-48 h-48 rounded-full object-cover">
        <p class="text-gray-700 dark:text-gray-300">Saya adalah mahasiswa Pendidikan Pancasila dan Kewarganegaraan di Universitas Negeri Medan. Saya aktif menulis opini dan artikel sosial, serta memiliki pengalaman sebagai narasumber dan peserta seminar nasional. Tulisan-tulisan saya dipublikasikan di Kompasiana dan jurnal akademik seperti Innovative Journal. Saya percaya bahwa pemuda memiliki peran penting dalam menciptakan perubahan positif di masyarakat.</p>
      </div>
    </section>

    <section id="portfolio" class="mb-20">
      <h3 class="text-2xl font-semibold mb-4">Portofolio</h3>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <div class="bg-white dark:bg-gray-800 p-4 rounded shadow">
          <h4 class="font-bold mb-2">Artikel Kompasiana</h4>
          <p><a href="https://www.kompasiana.com/hizkiarolandprawira1930/674cbd0dc925c44f9766e5b2/dunia-baru-negara-dengan-budaya-dan-keunikannya" class="text-blue-500 hover:underline">Dunia Baru: Negara dengan Budaya dan Keunikannya</a></p>
        </div>
        <div class="bg-white dark:bg-gray-800 p-4 rounded shadow">
          <h4 class="font-bold mb-2">Artikel Jurnal Ilmiah</h4>
          <p><a href="https://j-innovative.org/index.php/Innovative/article/view/6882" class="text-blue-500 hover:underline">Partisipasi Mahasiswa Sebagai Kaum Intelektual dalam Mencegah Money Politik</a></p>
        </div>
        <div class="bg-white dark:bg-gray-800 p-4 rounded shadow">
          <h4 class="font-bold mb-2">Dokumentasi Sertifikat</h4>
          <p><a href="https://fliphtml5.com/tudcv/tpog" class="text-blue-500 hover:underline">Sertifikat dan Piagam Penghargaan Hizkia Roland</a></p>
        </div>
        <div class="bg-white dark:bg-gray-800 p-4 rounded shadow">
          <h4 class="font-bold mb-2">LinkedIn</h4>
          <p><a href="https://id.linkedin.com/in/hizkia-roland-prawira-399536276" class="text-blue-500 hover:underline">Profil LinkedIn Saya</a></p>
        </div>
      </div>
    </section>

    <section id="contact">
      <h3 class="text-2xl font-semibold mb-4">Kontak</h3>
      <form class="space-y-4 max-w-xl">
        <input type="text" placeholder="Nama" class="w-full p-2 border border-gray-300 rounded" required>
        <input type="email" placeholder="Email" class="w-full p-2 border border-gray-300 rounded" required>
        <textarea placeholder="Pesan" class="w-full p-2 border border-gray-300 rounded" rows="4" required></textarea>
        <button type="submit" class="px-4 py-2 bg-blue-600 text-white rounded hover:bg-blue-700">Kirim</button>
      </form>
    </section>
  </main>

  <footer class="text-center p-6 bg-gray-100 dark:bg-gray-800">
    <p>&copy; 2025 Hizkia Roland Prawyra Sitorus. Semua Hak Dilindungi.</p>
  </footer>

  <script>
    const toggle = document.getElementById('toggleTheme');
    toggle.addEventListener('click', () => {
      document.documentElement.classList.toggle('dark');
    });
  </script>
</body>
</html>
