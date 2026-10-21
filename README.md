Canceled fetch actual content of user's README.md from GitHub
Checked task Fetch actual content of user's README.md from GitHub
Killed task Fetch actual content of user's README.md from GitHub
Ran fetch raw README.md content

À mình thấy nguyên nhân rồi! Khi bạn copy đoạn code ở trên, **bạn mới chỉ bôi đen được nửa đầu** (đến đoạn `const long = { ... }`), phần kỹ năng và bảng thống kê ở bên dưới chưa được copy hết nên nó chưa hiện ra!

Để đỡ phải dùng chuột kéo bôi đen dễ bị thiếu, bạn làm như sau nhé:

---

### 👉 Cách copy nhanh không bị thiếu:

Rê chuột vào **góc trên bên phải của khung code bên dưới**, bạn sẽ thấy nút **📋 Copy code** (hoặc nhấn giữ `Ctrl + A` bên trong khung code nếu có).

Sau đó bấm vào **cây bút ✏️** trong GitHub, xóa hết đi và dán lại toàn bộ:

```markdown
<div align="center">

  <!-- Banner chuyển màu sóng động -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,12,2&height=220&section=header&text=Hi%20there,%20I'm%20Trần%20Văn%20Long%20👋&fontSize=36&fontAlignY=38&desc=Full-Stack%20Developer%20|%20DTU%20University%20🎓&descAlignY=58&descSize=18&animation=fadeIn" width="100%" />

  <!-- Chữ chạy tự động gõ phím -->
  <a href="https://github.com/Lordnavnart">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=550&lines=Full-Stack+Developer+from+Da+Nang;Building+GreenGive+%26+Modern+Web+Apps;Tech+Stack:+Next.js+%E2%80%A2+TypeScript+%E2%80%A2+Prisma;Turning+coffee+%E2%98%95+into+clean+code+%F0%9F%92%BB" alt="Typing SVG" />
  </a>

  <br/><br/>

  <!-- Badge liên hệ nhanh -->
  <a href="mailto:tranlongbmt147@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="https://github.com/Lordnavnart">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>

---

### 👨‍💻 Về bản thân (About Me)

```typescript
const long = {
  name: "Trần Văn Long",
  university: "Duy Tan University (DTU) 🎓",
  location: "Da Nang, Vietnam 🇻🇳",
  role: "Full-Stack Web Developer",
  currentProjects: ["GreenGive (Donation Platform)", "DaNangGo"],
  focus: ["Next.js 15", "TypeScript", "Prisma ORM", "Tailwind CSS"],
  askMeAbout: ["React", "REST API", "Database Design"]
};
```

---

### 🛠️ Kỹ năng & Công nghệ (Tech Stack)

#### 🌐 Frontend
<p align="left">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
</p>

#### ⚙️ Backend & Database
<p align="left">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white" />
</p>

#### 🧰 Tools & DevOps
<p align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
</p>

---

### 📊 Thống kê GitHub (Activity Stats)

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Lordnavnart&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lordnavnart&layout=compact&theme=tokyonight&hide_border=true" height="165" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Lordnavnart&theme=tokyonight&hide_border=true" />
</div>

<br/>

<!-- Sóng đáy footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24,12,2&height=90&section=footer" width="100%" />
```

---

Dán xong và commit lại, bạn nhớ cuộn chuột xuống dưới trên trang profile để ngắm toàn bộ các phần nhé!
