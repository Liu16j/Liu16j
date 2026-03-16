<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Profile</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;
            background: linear-gradient(135deg, #0d1117 0%, #161b22 100%);
            min-height: 100vh;
            color: #c9d1d9;
            padding: 40px 20px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
        }

        /* 头部信息 */
        .profile-header {
            display: flex;
            align-items: center;
            gap: 24px;
            margin-bottom: 32px;
        }

        .avatar {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid #30363d;
            object-fit: cover;
        }

        .profile-info h1 {
            font-size: 32px;
            color: #f0f6fc;
            margin-bottom: 8px;
        }

        .profile-info .username {
            font-size: 20px;
            color: #8b949e;
            margin-bottom: 16px;
        }

        .bio {
            color: #c9d1d9;
            font-size: 16px;
        }

        /* 徽章区域 */
        .badges {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-bottom: 32px;
        }

        .badges img {
            height: 24px;
            border-radius: 4px;
        }

        /* 统计信息 */
        .stats {
            display: flex;
            gap: 24px;
            margin-bottom: 32px;
            padding: 16px;
            background: #21262d;
            border-radius: 6px;
            border: 1px solid #30363d;
        }

        .stat-item {
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .stat-item svg {
            width: 20px;
            height: 20px;
            fill: #8b949e;
        }

        .stat-item span {
            color: #58a6ff;
            font-weight: 600;
        }

        .stat-item .label {
            color: #8b949e;
        }

        /* 技能标签 */
        .skills {
            margin-bottom: 32px;
        }

        .section-title {
            font-size: 24px;
            color: #f0f6fc;
            margin-bottom: 16px;
            padding-bottom: 8px;
            border-bottom: 1px solid #30363d;
        }

        .skill-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }

        .skill-tag {
            padding: 6px 14px;
            background: #21262d;
            border: 1px solid #30363d;
            border-radius: 20px;
            font-size: 14px;
            color: #c9d1d9;
            transition: all 0.3s ease;
        }

        .skill-tag:hover {
            background: #30363d;
            border-color: #8b949e;
        }

        /* 活动图 */
        .activity-graph {
            margin-bottom: 32px;
            padding: 20px;
            background: #0d1117;
            border-radius: 6px;
            border: 1px solid #30363d;
            overflow: hidden;
        }

        .activity-graph img {
            width: 100%;
            display: block;
        }

        /* 底部信息 */
        .footer {
            text-align: center;
            color: #8b949e;
            font-size: 14px;
            padding: 20px;
        }

        .footer a {
            color: #58a6ff;
            text-decoration: none;
        }

        .footer a:hover {
            text-decoration: underline;
        }

        /* 响应式 */
        @media (max-width: 600px) {
            .profile-header {
                flex-direction: column;
                text-align: center;
            }

            .stats {
                flex-direction: column;
                gap: 12px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- 头部信息 -->
        <div class="profile-header">
            <img src="https://avatars.githubusercontent.com/u/your-github-id?v=4" alt="Avatar" class="avatar">
            <div class="profile-info">
                <h1>Your Name</h1>
                <div class="username">@your-username</div>
                <div class="bio">A passionate developer who loves coding and building amazing projects 🚀</div>
            </div>
        </div>

        <!-- 徽章 -->
        <div class="badges">
            <img src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
            <img src="https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
            <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
            <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
            <img src="https://img.shields.io/badge/-Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white" alt="Vue.js">
            <img src="https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js">
            <img src="https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++">
            <img src="https://img.shields.io/badge/-Qt-41CD52?style=flat-square&logo=qt&logoColor=white" alt="Qt">
        </div>

        <!-- 统计信息 -->
        <div class="stats">
            <div class="stat-item">
                <svg viewBox="0 0 16 16">
                    <path d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25z"/>
                </svg>
                <span>1,234</span>
                <span class="label">stars</span>
            </div>
            <div class="stat-item">
                <svg viewBox="0 0 16 16">
                    <path d="M5 5.372v.878c0 .414.336.75.75.75h4.5a.75.75 0 00.75-.75v-.878a2.25 2.25 0 114.5 0v.878a2.25 2.25 0 01-2.25 2.25h-1.5v2.128a2.251 2.251 0 11-1.5 0V8.5h-1.5A2.25 2.25 0 013.5 6.25v-.878a2.25 2.25 0 114.5 0zM5 3.25a.75.75 0 10-1.5 0 .75.75 0 001.5 0zm6.75.75a.75.75 0 100-1.5.75.75 0 000 1.5zm-3 8.75a.75.75 0 11-1.5 0 .75.75 0 011.5 0z"/>
                </svg>
                <span>567</span>
                <span class="label">forks</span>
            </div>
            <div class="stat-item">
                <svg viewBox="0 0 16 16">
                    <path d="M8 9.5a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"/>
                    <path fill-rule="evenodd" d="M8 0a8 8 0 100 16A8 8 0 008 0zM1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0z"/>
                </svg>
                <span>89</span>
                <span class="label">followers</span>
            </div>
            <div class="stat-item">
                <svg viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M8 1a7 7 0 100 14A7 7 0 008 1zm0 2.122a4.878 4.878 0 100 9.756 4.878 4.878 0 000-9.756zm-2.878 2.878a.75.75 0 11-1.06 1.06.75.75 0 011.06-1.06zm4.756.756a.75.75 0 11-1.06 1.06.75.75 0 011.06-1.06z"/>
                </svg>
                <span>42</span>
                <span class="label">following</span>
            </div>
        </div>

        <!-- GitHub 活动统计图 -->
        <div class="activity-graph">
            <div class="section-title">GitHub Activity</div>
            <!-- 将 your-username 替换为你的 GitHub 用户名 -->
            <div align="center">
                <img src="https://activity-graph.herokuapp.com/graph?username=your-username&theme=xcode" alt="Activity Graph">
            </div>
        </div>

        <!-- 技能展示 -->
        <div class="skills">
            <div class="section-title">Tech Stack</div>
            <div class="skill-tags">
                <span class="skill-tag">HTML5</span>
                <span class="skill-tag">CSS3</span>
                <span class="skill-tag">JavaScript</span>
                <span class="skill-tag">TypeScript</span>
                <span class="skill-tag">Vue.js</span>
                <span class="skill-tag">Node.js</span>
                <span class="skill-tag">C++</span>
                <span class="skill-tag">Qt</span>
            </div>
        </div>

        <!-- 底部 -->
        <div class="footer">
            <p>Made with ❤️ by <a href="https://github.com/your-username">@your-username</a></p>
            <p>© 2024 All rights reserved.</p>
        </div>
    </div>
</body>
</html>
