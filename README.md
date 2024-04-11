Welcome to My GitHub Profile!
## About Me

👋 Hello! I'm Irawan Aji Pangestu,

🎓 I am part of the Cloud Computing cohort at Bangkit Academy 2024. This program has provided me with a deep understanding of cloud technology, programming, and relevant concepts in the IT industry. 

🏫 Currently, I am pursuing Associate Degree in Information Technology at Brawijaya University, where I am involved in various projects and academic activities that broaden my understanding of the technology world. 

💼 I am highly interested in pursuing a career in cloud engineering and digital business, where I can combine my technical knowledge of cloud infrastructure with a strong understanding of business strategy and digital innovation. 

🚀 I am always eager to continue learning and developing my skills in the latest technologies, as well as contributing to projects that solve real-world problems and make a positive impact.

Thank you for visiting my profile! 😊
## Get in Touch

- LinkedIn: https://www.linkedin.com/in/irawanajipangestu/
- Email: irawanajhi22@gmail.com

Thank you for visiting my GitHub profile! Happy coding! 🚀

<p align="left">
<a href="https://github.com/penuliscode">
  <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=penuliscode&show_icons=true&theme=algolia&include_all_commits=true&count_private=true"/>
</a>
</p>

// Ganti dengan nama pengguna GitHub yang ingin Anda periksa keaktifannya
const username = irawanap;

// URL untuk mengambil data keaktifan pengguna dari API GitHub
const url = `https://api.github.com/users/${irawanap}/events`;

// Lakukan permintaan HTTP GET menggunakan fetch
fetch(url)
  .then(response => response.json())
  .then(data => {
    // Data keaktifan pengguna akan tersedia di dalam variabel data
    console.log(data);
    // Lakukan apa pun yang Anda inginkan dengan data keaktifan, seperti menampilkan di halaman web
  })
  .catch(error => {
    console.error('Error:', error);
  });
