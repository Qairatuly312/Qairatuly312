<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Yerassyl Kairatuly</title>
    <style>
        :root{--accent:#0f6fff;--muted:#6b7280;--bg:#f7f9fc;--card:#ffffff; --max-width:900px}
        *{box-sizing:border-box}
        body{font-family:Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial; background:var(--bg); color:#0f172a; padding:32px; display:flex; justify-content:center}
        .cv{width:100%;max-width:var(--max-width);display:grid;grid-template-columns:300px 1fr;gap:24px}
        .card{background:var(--card);border-radius:10px;padding:20px;box-shadow:0 6px 18px rgba(15,23,42,0.06)}
        /* Sidebar */
        .sidebar .title{font-weight:700;font-size:14px;color:var(--muted);letter-spacing:0.6px;margin-bottom:8px}
        .name{font-size:22px;font-weight:800;color:#071033}
        .role{color:var(--accent);font-weight:700;margin-top:6px}
        .techline{margin-top:10px;font-size:13px;color:var(--muted)}
        .section{margin-top:18px}
        .contact a{display:block;color:#0f172a;text-decoration:none;margin:6px 0;font-size:14px}
        .contact a small{color:var(--muted);display:block;font-size:12px}
        .skill-list{display:flex;flex-wrap:wrap;gap:8px;margin-top:8px}
        .skill{background:#f1f5f9;color:#071033;padding:6px 8px;border-radius:6px;font-size:13px}
        .heading{display:flex;align-items:center;justify-content:space-between}
        .heading h3{margin:0;font-size:14px;color:#071033}
        .muted{color:var(--muted);font-size:13px}
        hr.sep{border:0;border-top:1px solid #eef2f7;margin:14px 0}
        /* Main */
        .profile .subtitle{font-weight:700;color:var(--muted);font-size:13px}
        .profile p{margin:8px 0;color:#0f172a;line-height:1.45}
        .job{margin-bottom:12px}
        .job h4{margin:0;font-size:15px}
        .job small{color:var(--muted);display:block;margin-bottom:6px}
        ul.bullets{margin:6px 0 12px 18px}
        .project{margin-bottom:12px}
        a.link{color:var(--accent);text-decoration:none;font-weight:600}
        /* responsive */
        @media (max-width:820px){.cv{grid-template-columns:1fr;}.sidebar{order:2}.main{order:1}}
    </style>
</head>
<body>
<div class="cv">
    <aside class="card sidebar">
        <div>
            <div class="name">Yerassyl Kairatuly</div>
            <div class="role">Back‑End / Full‑Stack Developer</div>
            <div class="techline">Spring Boot • PostgreSQL • Java • Docker • Keycloak</div>
        </div>

        <hr class="sep" />

        <div class="section contact">
            <div class="title">Contact</div>
            <a href="#">Kazakhstan, Almaty <small class="muted">Location</small></a>
            <a href="mailto:kairatulyerasil@gmail.com">kairatulyerasil@gmail.com <small class="muted">Email</small></a>
            <a href="https://www.linkedin.com/in/yerassyl-kairatuly-858391355" target="_blank">linkedin.com/in/yerassyl-kairatuly-858391355 <small class="muted">LinkedIn</small></a>
            <a href="https://github.com/Qairatuly312" target="_blank">github.com/Qairatuly312 <small class="muted">GitHub</small></a>
            <a href="https://gitlab.com/yeraqai" target="_blank">gitlab.com/yeraqai <small class="muted">GitLab</small></a>
        </div>

        <div class="section">
            <div class="title">Competences</div>
            <div style="margin-top:8px">
                <div class="subtitle">Programming</div>
                <div class="skill-list">
                    <div class="skill">Java</div>
                    <div class="skill">JavaScript</div>
                    <div class="skill">SQL</div>
                    <div class="skill">Bash</div>
                </div>
            </div>

            <div style="margin-top:10px">
                <div class="subtitle">Frameworks / Libraries</div>
                <div class="skill-list">
                    <div class="skill">Spring Boot</div>
                    <div class="skill">OAuth2 / JWT</div>
                    <div class="skill">Hibernate / JPA</div>
                </div>
            </div>

            <div style="margin-top:10px">
                <div class="subtitle">Databases & Tools</div>
                <div class="skill-list">
                    <div class="skill">PostgreSQL</div>
                    <div class="skill">MySQL</div>
                    <div class="skill">Docker</div>
                    <div class="skill">Git / GitLab CI</div>
                </div>
            </div>

            <div style="margin-top:10px">
                <div class="subtitle">Web</div>
                <div class="skill-list">
                    <div class="skill">HTML</div>
                    <div class="skill">CSS</div>
                    <div class="skill">REST APIs</div>
                </div>
            </div>

            <div style="margin-top:12px">
                <div class="subtitle">Languages</div>
                <div class="muted">English — B2 <hr >Kazakh — Native <hr> Russian — Native</div>
            </div>
        </div>

        <div class="section">
            <div class="title">Education</div>
            <div style="margin-top:8px">
                <strong>SDU University</strong>
                <div class="muted">Bachelor in Computer Science (2024–2028)</div>
                <div class="muted" style="margin-top:6px">Second year — Learning Programming, Data Structures, Databases, Software Engineering</div>
            </div>
        </div>

        <div class="section">
            <div class="title">Certifications</div>
            <div style="margin-top:8px">
                <strong>PostgreSQL for Everybody — Coursera</strong>
                <div class="muted">University of Michigan, 2025 — SQL & PostgreSQL (fluent)</div>
            </div>
        </div>

    </aside>

    <main class="card main">
        <section class="profile">
            <div class="heading">
                <h3>About Me</h3>
            </div>
            <p class="muted">Backend-focused Computer Science student passionate about building secure and scalable applications. Skilled in Java, Spring Boot, and PostgreSQL, with growing experience in microservices and DevOps.</p>

            <div class="heading" style="margin-top:8px"><h3>Motivation</h3></div>
            <p>I’m a second-year Computer Science student who recently started my journey as a developer. I worked as a Junior Backend Developer, contributing to a Spring Boot application used by 100+ users. Now I’m seeking a new role where I can continue learning, deepen knowledge of databases like PostgreSQL, and grow into a full-stack developer.</p>
        </section>

        <hr class="sep" />

        <section class="experience">
            <div class="heading"><h3>Experience</h3></div>

            <div class="job">
                <h4>Junior Back‑End Developer — IQRA Academy, Almaty</h4>
                <small class="muted">2025</small>
                <ul class="bullets">
                    <li>Developed and maintained backend features for a Spring Boot production application serving 100+ active users.</li>
                    <li>Collaborated to implement and optimize business process logic for workflow automation and reliability.</li>
                    <li>Wrote and reviewed 100+ GitLab commits, improving CI and code quality.</li>
                    <li>Designed RESTful APIs integrated with PostgreSQL for secure, scalable data management.</li>
                    <li>Participated in code reviews, sprint planning, debugging, and production deployment.</li>
                </ul>
                <div class="muted"><strong>Achievements:</strong> Delivered features used in production; refactored queries for better performance; improved documentation and team workflow.</div>
            </div>
        </section>

        <hr class="sep" />

        <section class="projects">
            <div class="heading"><h3>Projects</h3></div>

            <div class="project">
                <h4>Note‑Manager <span style="font-weight:600;color:var(--muted);font-size:13px">• Spring Boot • PostgreSQL • JWT</span></h4>
                <p>Built a secure note-taking web app with user authentication and REST APIs. Implemented JWT-based authentication and Spring Security filters to protect user data.</p>
                <div><a class="link" href="https://github.com/Qairatuly312/notes_manager" target="_blank">github.com/Qairatuly312/notes_manager</a></div>
            </div>

            <div class="project">
                <h4>Planner <span style="font-weight:600;color:var(--muted);font-size:13px">• Microservices • Keycloak • Docker</span></h4>
                <p>Designing a microservices planning app. Implemented OAuth2 with Keycloak, configured HTTPS between services, and deployed components in Docker containers to study distributed system patterns.</p>
                <div><a class="link" href="https://github.com/Qairatuly312/planner-microservices" target="_blank">github.com/Qairatuly312/planner-microservices</a></div>
            </div>

        </section>

    </main>
</div>
</body>
</html>
