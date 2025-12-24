---
layout: default
title: About Me
permalink: /about/
---

<style>
    .about-section {
        margin-bottom: 40px;
    }
    .about-title {
        font-family: var(--font-title);
        font-size: 1.5rem;
        color: var(--text-title);
        margin-bottom: 15px;
        display: inline-block;
        box-shadow: inset 0 -10px 0 rgba(252, 227, 138, 0.6); /* 형광펜 효과 */
    }
    .about-content {
        font-size: 1.1rem;
        line-height: 1.8;
    }
    .skill-badge {
        display: inline-block;
        background-color: #FFF9C4;
        color: var(--text-title);
        padding: 5px 12px;
        border-radius: 20px;
        margin: 0 5px 8px 0;
        font-family: var(--font-title);
        font-size: 1rem;
        border: 1px solid var(--point-color);
    }
    .contact-link {
        color: var(--text-body);
        text-decoration: underline;
        text-decoration-color: var(--point-color);
        text-underline-offset: 4px;
        transition: 0.2s;
    }
    .contact-link:hover {
        background-color: var(--point-color);
        color: var(--text-title);
        text-decoration: none;
    }
</style>
<div class="post-card">
    <div class="about-section">
        <h2 class="about-title">Hello, World! 👋</h2>
        <p class="about-content">
            안녕하세요! <strong>기록하는 개발자 김망구</strong>입니다.<br>
            배운 것을 정리하고, 소소한 일상을 기록하는 공간입니다.
        </p>
    </div>

    <div class="about-section">
        <h2 class="about-title">Tech Stack</h2>
        <div class="about-content">
            <span class="skill-badge">💻 React</span>
            <span class="skill-badge">🎨 HTML/CSS</span>
            <span class="skill-badge">💛 JavaScript</span>
            <span class="skill-badge">💎 Jekyll</span>
            <span class="skill-badge">🐙 Git/GitHub</span>
        </div>
    </div>

    <div class="about-section">
        <h2 class="about-title">Like & Hobby</h2>
        <ul class="about-content" style="list-style: none; padding-left: 5px;">
            <li>🏃‍♀️ <strong>Running:</strong> 체력을 기르기 위해 달립니다.</li>
            <li>🍔 <strong>Food:</strong> 맛있는 햄버거를 찾아다닙니다.</li>
            <li>✨ <strong>Cute:</strong> 귀엽고 아기자기한 디자인을 좋아합니다.</li>
        </ul>
    </div>

    <div class="about-section">
        <h2 class="about-title">Contact</h2>
        <p class="about-content">
            궁금한 점이나 이야기하고 싶은 주제가 있다면 언제든 연락주세요.<br>
            📧 Email: <a href="mailto:kimango0o@naver.com" class="contact-link">kimango0o@naver.com</a><br>
            🐱 GitHub: <a href="https://github.com/tjswntjswn" target="_blank" class="contact-link">@tjswntjswn</a>
        </p>
    </div>
</div>