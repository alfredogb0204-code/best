<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Hbd bess</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
    />
  </head>
  <body
    style="
      background-image: url(https://plus.unsplash.com/premium_photo-1667761637252-780aa4c33e3f?ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OXx8cmVkJTIwZ3JhZGllbnR8ZW58MHx8MHx8fDA%3D&auto=format&fit=crop&q=60&w=600);
    "
    class="flex justify-center h-screen items-center"
  >
    <div
      class="bg-white border px-10 py-8 border-4 border-gray-300 shadow-lg shadow-red-300 rounded-xl text-center animate__animated animate__backInDown m-8 w-80"
      id="kartu"
    >
      <h1 class="text-3xl">Happy Birthday</h1>
      <h1
        class="text-4xl text-red-500 font-bold animate__animated animate__pulse animate__infinite"
      >
        Best Audrey
      </h1>
      <button
        class="p-2 bg-red-600 text-white rounded mt-5 hover:bg-blue-900 transition ease-in w-full animate__animated animate__delay-1s animate__tada"
        onclick="ubahKartu()"
      >
        Klik Disini Bess
      </button>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/@tsparticles/confetti@3.0.3/tsparticles.confetti.bundle.min.js"></script>
    <script>
      confetti({
        particleCount: 100,
        spread: 70,
        origin: { y: 0.6 },
      });
      let kartu = document.getElementById("kartu");
      function ubahKartu() {
        kartu.innerHTML = `    <h1 class="font-semibold text-wrap animate__animated animate__zoomIn">
      Selamat ultah yang ke-17 ya Bestieku, semoga panjang umur, sehat selalu, dan semua cita-citamu tercapai. Semangat juga yaa SAT nya, semoga bisa tembus skor 1500+. Aku doain yang terbaik buat mu. Sorry gabisa ngucapin langsung, hehe. Nanti kalo bisa ku bawain oleh-oleh dari Jakarta 👍🏻.  🎉🎂
    </h1>
    <h2 class="mt-3 animate__animated animate__fadeIn">
      - Dari : 004 -
    </h2>
    <button
      class="p-2 bg-red-600 text-white rounded mt-5 hover:bg-red-900 transition ease-in w-full animate__animated animate__delay-1s animate__tada"
      onclick="refresh()"
    >
      Tutup
    </button>
    `;
      }
      function refresh() {
        location.reload();
      }
    </script>
  </body>
</html>
