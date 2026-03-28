<div align="center">

<img src="https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif" width="350"/>

# Hi 👋, I'm Mahesh R Madiwalar

<img src="https://readme-typing-svg.herokuapp.com?color=00F7FF&size=28&center=true&vCenter=true&width=700&lines=Backend+Developer;MERN+Stack+Developer;AI+Builder;Hackathon+Winner;DSA+Co-Lead+@+GDG" />

<img src="https://komarev.com/ghpvc/?username=mahi-2-ron&label=Profile%20Views&color=0e75b6&style=flat" alt="profile views"/>

</div>

---

# 🧠 About Me

* 🎓 BE (Electronics & Communication Engineering)
  **Dr. Ambedkar Institute of Technology, Bengaluru**

* 💻 Passionate about **Backend Systems, APIs & Scalable Web Apps**

* 🤖 Building **AI-powered platforms and automation tools**

* 🧩 Solved **150+ DSA problems on LeetCode**

* 👨‍🏫 **DSA Co-Lead @ Google Developer Groups (GDG)** mentoring peers

---

export default function FeaturedProjects() {
  const projects = [
    {
      title: "NammaCraft",
      subtitle: "AI Powered Artisan Marketplace",
      tech: ["React", "Node.js", "MongoDB", "Firebase", "Gemini AI"],
      points: [
        "D3.js map for cultural craft discovery",
        "Real-time auction system with bidding",
        "AI-powered pricing & voice listing",
        "Multi-role dashboards (Buyer, Artisan, Admin)",
      ],
      icon: "🧵",
    },
    {
      title: "Jeeva Raksha",
      subtitle: "AI Hospital Management System",
      tech: ["React", "Node.js", "MongoDB", "AI"],
      points: [
        "OPD & IPD workflow management",
        "AI-powered lab report analysis",
        "Smart bed occupancy system",
        "Patient portal for appointments & records",
      ],
      icon: "🚑",
      link: "https://jeevaraksha.netlify.app/",
    },
    {
      title: "Vijnana Lab",
      subtitle: "AI Virtual Science Laboratory",
      tech: ["React", "Firebase", "AI"],
      points: [
        "Interactive virtual science experiments",
        "AI explanations for concepts",
        "Student dashboards & tracking",
        "Hackathon winning project",
      ],
      icon: "🧪",
      link: "https://vijnanalabbyteamsupra.netlify.app/#/home",
    },
  ];

  return (
    <div className="max-w-6xl mx-auto px-4 py-10">
      <h2 className="text-3xl font-bold mb-8 flex items-center gap-2">
        🚀 Featured Projects
      </h2>

      <div className="grid md:grid-cols-2 gap-6">
        {projects.map((project, index) => (
          <div
            key={index}
            className="border rounded-2xl p-6 shadow-sm hover:shadow-xl hover:-translate-y-1 transition duration-300"
          >
            <h3 className="text-xl font-semibold flex items-center gap-2">
              {project.icon} {project.title}
            </h3>

            <p className="text-gray-600 mt-1 mb-3">
              {project.subtitle}
            </p>

            {/* Tech Stack */}
            <div className="flex flex-wrap gap-2 mb-4">
              {project.tech.map((tech, i) => (
                <span
                  key={i}
                  className="text-xs px-3 py-1 rounded-md bg-gradient-to-r from-blue-500 to-cyan-500 text-white"
                >
                  {tech}
                </span>
              ))}
            </div>

            {/* Points */}
            <ul className="list-disc pl-5 space-y-1 text-sm text-gray-700">
              {project.points.map((point, i) => (
                <li key={i}>{point}</li>
              ))}
            </ul>

            {/* Link */}
            {project.link && (
              <a
                href={project.link}
                target="_blank"
                rel="noopener noreferrer"
                className="inline-block mt-4 text-sm font-medium text-blue-600 hover:underline"
              >
                🔗 View Project
              </a>
            )}
          </div>
        ))}
      </div>
    </div>
  );
}

---

# 🔥 GitHub Streak

<div align="center">

<img src="https://streak-stats.demolab.com?user=mahi-2-ron&theme=tokyonight&hide_border=true"/>

</div>

---

# 📈 Contribution Activity Graph

[![Mahesh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=mahi-2-ron\&theme=tokyo-night)](https://github.com/mahi-2-ron)

---

# 🐍 Contribution Snake

<div align="center">

![snake gif](https://github.com/mahi-2-ron/mahi-2-ron/blob/output/github-contribution-grid-snake.svg)

</div>

---

# 🌱 Current Focus

* Building **real-world MERN + AI platforms**
* Strengthening **DSA & system design**
* Learning **scalable backend architecture & cloud deployment**

---

# 📫 Connect With Me

📧 Email
[maheshrmadiwalar@gmail.com](mailto:maheshrmadiwalar@gmail.com)

🔗 LinkedIn
https://linkedin.com/in/mahesh-r-madiwalar-9a468b345

💻 GitHub
https://github.com/mahi-2-ron

---

<div align="center">

⭐ Always learning, building, and collaborating on impactful tech.

</div>
