<h1 align="center">Hi 👋, I'm Yeasin Arafat</h1>
<h3 align="center">A passionate frontend developer from Bangladesh</h3>

<p align="center">
 <img src="https://scontent.fdac41-1.fna.fbcdn.net/v/t39.30808-6/574466426_1393396925750779_974255703922522563_n.jpg?stp=dst-jpg_s1080x2048_tt6&_nc_cat=100&ccb=1-7&_nc_sid=127cfc&_nc_eui2=AeG1idCUext7m5UD3P7R_7kVwiKsEClQDDDCIqwQKVAMMESc5W_6XrwIk4DE93hxTCb_-cnbKnTZTVihvBYdB5EL&_nc_ohc=yoZIV1DuWJ0Q7kNvwHNqrny&_nc_oc=AdmMAPDCUB-HuYmMjeMba7SIHsxnH7hbbnm7tORDlEI6W7STRr0L2qvPtW7NrUz4Mk8&_nc_zt=23&_nc_ht=scontent.fdac41-1.fna&_nc_gid=iUhQxwL6uUAn_Cc1i9qigQ&oh=00_AfjLCG5___sC2j8BJl5TNjgkn7gmctgPo5Knj4yGKbFxcw&oe=69106559" alt="My Banner" width="1000" height="350">
</p>

<!-- Save this file as banner.html and open in a browser (works offline, but icons load from CDN) -->
<!doctype html>
<html lang="bn">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>GitHub Banner (1000x350)</title>
<style>
  /* Canvas size exactly 1000x350 for GitHub README banner */
  :root { --w:1000px; --h:350px; --gap:12px; }
  html,body{height:100%; margin:0; background:#111; display:flex; align-items:center; justify-content:center;}
  .banner{
    width:var(--w);
    height:var(--h);
    border-radius:12px;
    overflow:hidden;
    box-shadow: 0 8px 30px rgba(0,0,0,0.7), inset 0 1px 0 rgba(255,255,255,0.02);
    display:flex;
    background: linear-gradient(135deg, #0f1220 0%, #0b0c10 100%);
    align-items:center;
    padding:28px;
    gap:24px;
    box-sizing:border-box;
  }

  /* Left: profile image */
  .left{
    flex: 0 0 300px;
    height:100%;
    display:flex;
    align-items:center;
    justify-content:center;
    position:relative;
  }
  .avatar{
    width:260px; height:260px;
    border-radius:12px;
    overflow:hidden;
    box-shadow: 0 8px 30px rgba(2,6,23,0.7);
    border: 1px solid rgba(255,255,255,0.04);
    background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(0,0,0,0.35));
  }
  .avatar img{
    width:100%; height:100%; object-fit:cover; display:block;
    filter: saturate(0.98) contrast(1.02);
  }
  /* subtle glow behind avatar */
  .avatar::before{
    content:"";
    position:absolute;
    left:14px; top:50%;
    width:160px; height:160px;
    transform:translateY(-50%);
    background: radial-gradient(closest-side, rgba(59,130,246,0.06), transparent 50%);
    pointer-events:none;
    filter: blur(28px);
  }

  /* Right: icons grid */
  .right{
    flex:1;
    height:100%;
    display:flex;
    flex-direction:column;
    justify-content:center;
    gap:18px;
    padding-right:12px;
    box-sizing:border-box;
  }

  .icons-row{
    display:flex;
    gap:14px;
    align-items:center;
    justify-content:flex-end;
  }

  /* Icon box */
  .skill{
    width:72px; height:72px;
    display:inline-flex;
    align-items:center;
    justify-content:center;
    border-radius:10px;
    background: linear-gradient(180deg, rgba(255,255,255,0.015), rgba(0,0,0,0.25));
    border: 1px solid rgba(255,255,255,0.03);
    box-shadow: 0 6px 18px rgba(2,6,23,0.6);
    padding:8px;
  }
  .skill img{
    width:100%; height:100%;
    object-fit:contain;
    filter: drop-shadow(0 3px 8px rgba(2,6,23,0.6));
  }

  /* layout: two rows of icons arranged to look balanced */
  .row-top { justify-content: flex-end; }
  .row-bottom { justify-content: flex-end; }

  /* responsive fallback if needed */
  @media (max-width:1050px){
    .banner{transform:scale(0.95); transform-origin:center;}
  }
  @media (max-width:820px){
    .banner{flex-direction:column; width:900px; height:420px; padding:22px;}
    .left{flex:0 0 auto;}
    .right{padding:0; gap:12px;}
  }
</style>
</head>
<body>
  <div class="banner" role="img" aria-label="GitHub banner">
    <div class="left">
      <div class="avatar">
        <!-- Replace the src with your direct image link if needed -->
        <img alt="Profile" src="https://i.ibb.co/YT7k1dH/placeholder.jpg" id="profileImage">
      </div>
    </div>

    <div class="right">
      <div class="icons-row row-top">
        <!-- Top row (4 icons) -->
        <div class="skill"><img alt="HTML5" src="https://cdn.jsdelivr.net/npm/simple-icons@v8/icons/html5.svg"></div>
        <div class="skill"><img alt="CSS3" src="https://cdn.jsdelivr.net/npm/simple-icons@v8/icons/css3.svg"></div>
        <div class="skill"><img alt="JavaScript" src="https://cdn.jsdelivr.net/npm/simple-icons@v8/icons/javascript.svg"></div>
        <div class="skill"><img alt="React" src="https://cdn.jsdelivr.net/npm/simple-icons@v8/icons/react.svg"></div>
      </div>

      <div class="icons-row row-bottom">
        <!-- Bottom row (5 icons) -->
        <div class="skill"><img alt="Tailwind" src="https://cdn.jsdelivr.net/npm/simple-icons@v8/icons/tailwindcss.svg"></div>
        <div class="skill"><img alt="Bootstrap" src="https://cdn.jsdelivr.net/npm/simple-icons@v8/icons/bootstrap.svg"></div>
        <div class="skill"><img alt="Git" src="https://cdn.jsdelivr.net/npm/simple-icons@v8/icons/git.svg"></div>
        <div class="skill"><img alt="GitHub" src="https://cdn.jsdelivr.net/npm/simple-icons@v8/icons/github.svg"></div>
        <div class="skill"><img alt="VSCode" src="https://cdn.jsdelivr.net/npm/simple-icons@v8/icons/visualstudiocode.svg"></div>
      </div>
    </div>
  </div>

<script>
/* === Replace profile image src with the user's provided direct link ===
   Your provided link: https://ibb.co.com/gLWdCLVW
   Note: imgbb "display" link often needs to be converted to direct image URL.
   If that link doesn't show the image, replace below URL with a direct image link (ending .jpg/.png).
*/
const userImg = "https://i.ibb.co/YT7k1dH/placeholder.jpg"; // fallback placeholder
// Try to set to the imgbb host direct link if possible:
const provided = "https://i.ibb.co/gLWdCLVW"; // user link (may not be direct image)
const imgEl = document.getElementById('profileImage');

// Heuristic: if provided looks like a direct image (ends with jpg/png) use it, else keep placeholder
if (/\.(jpe?g|png|webp|gif|svg)$/i.test(provided)) {
  imgEl.src = provided;
} else {
  // convert some common imgbb patterns to direct raw link automatically:
  // if the user used i.ibb.co short link, try treat as direct
  if (provided.includes("i.ibb.co/")) {
    imgEl.src = provided;
  } else {
    // Try common imgbb raw path (this may or may not work depending on how user uploaded)
    // If you have the direct image link (ending with .jpg/.png), replace the src manually.
    imgEl.src = provided; // attempt anyway
  }
}
</script>
</body>
</html>



## 🧠 About Me

<div align="justify">
I am a passionate Front-End Developer with a strong foundation in modern web technologies. I enjoy turning ideas into interactive, user-friendly, and visually appealing web applications.

My journey started with building simple static websites using HTML, CSS, and JavaScript, and over time I expanded my skills to React, Tailwind CSS, and Bootstrap to create dynamic, responsive, and modern user interfaces.
</div>

- 🔭 I’m currently working on **Modern Portfolio Website**

- 🌱 I’m currently learning **Next.js, TypeScript, and Framer Motion**

- 👯 I’m looking to collaborate on **Open Source React Projects**

- 💬 Ask me about **React, JavaScript, Tailwind CSS, and Responsive Design**

- 📫 How to reach me **developer.arafatalways@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/yeasin-arafat-02a116372/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="yeasin-arafat-02a116372/" height="30" width="40" /></a>
<a href="https://fb.com/mo.yeasinarafat.1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="mo.yeasinarafat.1" height="30" width="40" /></a>
</p>


## 🌐 Socials:
[![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white)](https://facebook.com/mo.yeasinarafat.1) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/yeasin-arafat-02a116372/) 

# 💻 Tech Stack:
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white) ![React Query](https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white) ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white) ![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-%23EC5990.svg?style=for-the-badge&logo=reacthookform&logoColor=white) ![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

<div align="center">
  <img src="https://profile-readme-generator.com/assets/snake.svg" alt="Snake animation" />
</div>

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=arafatalways&theme=transparent&hide_border=false&include_all_commits=true&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=arafatalways&theme=transparent&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=arafatalways&theme=transparent&hide_border=false&include_all_commits=true&count_private=false&layout=compact)

<div align="center">
  <!-- Change username=ab-azim if needed -->
<a href="https://github.com/ab-azim" target="_blank" rel="noopener noreferrer">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=ab-azim&theme=react-dark" 
       alt="Contribution graph for ab-azim" style="max-width:100%;height:auto;">
</a>
  <p><strong>Contribution activity:</strong> Visual summary of my recent coding — commits, PRs and other contributions over time. (Auto-updated)</p>
</div>

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=arafatalways&theme=dark&no-frame=false&no-bg=true&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=arafatalways&limit=5&theme=dark&combine_all_yearly_contributions=true)

---
[![](https://visitcount.itsvg.in/api?id=arafatalways&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->

